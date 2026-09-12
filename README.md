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
> We try our best to avoid false positives. The most likely false positives would be from photos, which overuse focus blur, oilify, sharpen or other filters, or art, which we deem soulless, disproportionate, or excessively smooth and colorful. e.g., [Corporate Memphis](https://en.wikipedia.org/wiki/Corporate_Memphis). Or from music, which we deem unnatural due to overuse of audio trimming or [AutoTune](https://en.wikipedia.org/wiki/Autotune).
4. Which characteristics of a website could contribute to blocking?
> Although the characteristics are not enough when standalone, they could help us decide whether to block a website if we were doubtful of its usefulness to slop. Included are characteristics such as: required account creation; vibe-coded UI; mandatory JavaScript (which shouldn't be); providing slop without classifying it as such; unknown authorship; etc.
5. Why filter out TikTok?
> Due to short-form media's heavily-algorithmic structure, it's rarely useful to find meaningful content. In order to appease the algorithm, short-form videos are conditioned to be optimally attention-grabbing to the unwaveringly-diminishing attention spans of its users.

## See also
- [AIMania](https://github.com/Vxrpenter/AIMania)
- [DuckDuckGo No AI](https://noai.duckduckgo.com/)
- [HarmonyDagger](https://github.com/jaschadub/harmonydagger)
- [Miasma](https://github.com/austin-weeks/miasma)
