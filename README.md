# uSloplist
Anti-AI ruleset for uBlacklist and uBlock Origin. Tired of uncanny "photos", stolen muddled "art", or unnatural AI-generated "music"? uSloplist aims to filter out all kinds of slop, to bring back the good 'ol worldwide web.

## Setup
Copy
```
https://raw.githubusercontent.com/Wakelock/uSloplist/refs/heads/main/uBlacklist.txt
```

### uBlacklist
1. Open addon options
2. Scroll down to "Subscription", and then click "Add a subscription".

### uBlock Origin
1. Open addon options
2. Click "Filter lists", and then select "Import..."

## Q&A

1. Which websites does it block?
> Sites which:
> - Host a large amount of AI-generated content, especially those from companies who heavily invest in AI (e.g., Adobe, MSN, TikTok, etc).
> - - Some credible websites are whitelisted, but specific parts of them could be filtered if they contain slop and no educational value.
> - Stream stolen music altered by AI beyond comprehension.
> - Publish baseless and likely-slop articles from an unknown writer.

2. Does it block political content?
> *Mostly not*. Political sites are less likely to be blocked, in order to prevent censorship and bias. The only such websites intended to be blocked must be obscure, baseless and almost if not completely AI-generated, whose images show up on search results.
3. Which are most likely false positives?
> We try our best to avoid false positives. The most likely false positives would be from photos, which overuse: Focus blur; Oilify; Sharpen, or other filters, and art, which we deem: "soulless"; "disproportionate", or "excessively smooth and colorful" (e.g., [Corporate Memphis](https://en.wikipedia.org/wiki/Corporate_Memphis)), or from music, which we deem "unnatural" due to "overuse of audio trimming and [AutoTune](https://en.wikipedia.org/wiki/Autotune)".
4. Which characteristics of a website could contribute to blocking?
> Although the characteristics are not enough when standalone, they could help us decide whether to block a website if we were doubtful of its usefulness to slop. Included are characteristics such as: required account creation; mandatory JavaScript; pestering to disable adblockers; unknown authorship; DRM; etc.
5. How to whitelist a blocked site?
> - Visit a search results page, click the uBlacklist logo at the top right corner.
> - Mouseover at the blocked website (which should be highlighted), and then click the uBlacklist logo which just appeared.
> - A menu should pop up, then click "Unblock". If you imported uSloplist (which is not recommended), that would remove the site from your list. If you subscribed to uSloplist, that would add the site with an additional "@" at its line's beginning to your own list.

## See also
- [AIMania](https://github.com/Vxrpenter/AIMania)
- [DuckDuckGo No AI](https://noai.duckduckgo.com/)
- [HarmonyDagger](https://github.com/jaschadub/harmonydagger)
- [Miasma](https://github.com/austin-weeks/miasma)
