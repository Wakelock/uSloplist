# uSloplist
Anti-AI ruleset for uBlacklist and uBlock Origin. Tired of uncanny "photos", stolen muddled "art", or unnatural AI-generated "music"? uSloplist aims to filter out all kinds of slop, to bring back the good 'ol worldwide web.

## Setup
Copy ``https://raw.githubusercontent.com/Wakelock/uSloplist/refs/heads/main/uBlacklist.txt``

### uBlacklist
1. Open addon options
2. Scroll down to "Subscription", and then click "Add a subscription".

### uBlock Origin
1. Open addon options
2. Click "Filter lists", and then select "Import..."

## Q&A

1. Which websites does it block?
> Sites which:
> - Host a large amount of AI-generated content, especially those from companies who heavily invest in AI (e.g., Adobe, TikTok, etc). Certain popular pro-AI websites (like Amazon,Facebook, Reddit, Scratch, YouTube, etc.) are whitelisted because they provide good percentages of valuable content to AI slop, though they apparently decrease by day. This ruleset is probably more "nuclear" than most others.
> - Provide incoherent or source-less articles from an unknown (probably AI) writer, which contain obviously AI-generated media.
> - Stream stolen music altered by AI beyond comprehension.
2. Does it block political content?
> *Mostly not*. Political sites are less likely to be blocked, in order to prevent censorship and bias. The only such websites intended to be blocked must be obscure, baseless and almost if not completely AI-generated, whose images show up on search results.

3. Which are most likely false positives?
> We try our best to avoid false positives. The most likely false positives would be from art, which we deem soulless, disproportionate, or excessively smooth and colorful. e.g., [Corporate Memphis](https://en.wikipedia.org/wiki/Corporate_Memphis). Or from music, which we deem unnatural due to overuse of audio trimming or [AutoTune](https://en.wikipedia.org/wiki/Autotune).

## See also
- [DuckDuckGo No AI](https://noai.duckduckgo.com/)
- [HarmonyDagger](https://github.com/jaschadub/harmonydagger)
