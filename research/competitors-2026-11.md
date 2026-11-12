# What paying users complain about: voice and hands-free Mac apps

Research for [iris-tasks#1](https://github.com/topc-social/iris-tasks/issues/1), 2026-11-12. Two desk-research passes with web search; every claim links its source.

**Limits:** Reddit was blocked for the search tools, Wispr Flow's Trustpilot page is removed, and X and Setapp weren't checked. Most reviewers don't say whether they pay. Counts are distinct sources actually read, not a census.

## Voice dictation

| Product | Trigger | Price | Top complaints |
|---|---|---|---|
| Wispr Flow | Hold Fn; Fn+Space toggles "hands-free" ([docs](https://docs.wisprflow.ai/articles/6391241694-use-flow-hands-free)) | $15/mo, $12/mo yearly ([pricing](https://wisprflow.ai/pricing)) | Privacy (screenshots, cloud); RAM use and outages |
| Superwhisper | Hold to record, release to paste ([App Store](https://apps.apple.com/us/app/superwhisper/id6471464415?see-all=reviews)) | $8.49/mo, $84.99/yr ([docs](https://superwhisper.com/docs/billing/plans)) | Rewrites speech ("interprets it as a prompt"); buggy mobile app |
| VoiceInk (open source, GPL-3) | Hotkey: push-to-talk or toggle ([#278](https://github.com/Beingpax/VoiceInk/issues/278)) | $25–49 one-time ([site](https://tryvoiceink.com)) | Paste fallback bug ([#159](https://github.com/Beingpax/VoiceInk/issues/159)); buggy iOS app |
| MacWhisper | Custom shortcut ([help](https://macwhisper.helpscoutdocs.com/article/14-how-to-use-the-dictation-feature)) | about €59 lifetime (third-party figure) | Dictation is secondary to file transcription |
| Aqua Voice, Willow | Hold Space ([Aqua](https://aquavoice.com)); Fn or "Hey Willow" ([changelog](https://willowvoice.featurebase.app/changelog/introducing-custom-hotkeys-hey-willow-improvements-v1213)) | Willow $12/mo ([pricing](https://willowvoice.com/pricing)) | Too few primary reviews found |
| Apple Dictation (free) | Double-press Fn | Free | Accuracy; stops after silence ([Apple](https://discussions.apple.com/thread/252421492)) |

Complaints, by distinct sources:
1. **Accuracy, and AI cleanup changing what you said: 9.** Every product. Wispr's own poll of 700+ critics pointed at Auto Cleanup changing words ([Digital Trends](https://www.digitaltrends.com/computing/wispr-flow-asked-its-haters-what-was-wrong-and-more-than-700-people-answered/)); "the least accurate of the 4" ([HN](https://news.ycombinator.com/item?id=49747122)); "not accurate for my accent" ([HN](https://news.ycombinator.com/item?id=50052237)).
2. **Privacy and cloud trust: 9.** Mostly Wispr Flow: "That taking screenshots thing was inexcusable" ([Product Hunt](https://www.producthunt.com/products/wisprflow/reviews?page=1)); cancellation posts ([Medium](https://medium.com/@ryanshrott/why-i-cancelled-my-wispr-flow-subscription-and-what-im-using-instead-d783433f4411), [Lovelock](https://lewislovelock.com/blog/why-i-cancelled-wispr-flow-free-mac-app)).
3. **Bugs and reliability: 9.** Wispr outages and "degraded" ([HN](https://news.ycombinator.com/item?id=50046242)); mobile apps.
4. **Price and subscription: 8.** "Just canceled my WisprFlow subscription" ([HN](https://news.ycombinator.com/item?id=49334327)).
5. **Starting and stopping recording by hand: 7.** "Don't require me to hit a shortcut", "slightly frustrated to not be hands free" ([HN](https://news.ycombinator.com/item?id=47666024)); VoiceInk [#850](https://github.com/Beingpax/VoiceInk/issues/850) (spoken stop word), [#278](https://github.com/Beingpax/VoiceInk/issues/278).
6. **RAM and battery: 5.** 7. **Latency, no live streaming: 4.**

**Always-on listening:** no demand found. "Hands-free" in these apps means a toggle, not an open mic. Counter-signals: "annoying for others when you're talking to yourself" ([HN](https://news.ycombinator.com/item?id=41260424)); wake words that fire one time in five ([HN](https://news.ycombinator.com/item?id=47666024)).

## Hands-free control

| Product | How it works | Price | Top complaints |
|---|---|---|---|
| Talon | Voice, eye tracking, mouth noises ([site](https://talonvoice.com/)) | Free; beta via Patreon | Recognition ([HN](https://news.ycombinator.com/item?id=34849017)); learning curve ([HN](https://news.ycombinator.com/item?id=34849336)) |
| macOS Voice Control (free) | Voice with number and grid overlays | Free | Flaky commands ([Apple](https://discussions.apple.com/thread/256317435)); poor dictation ([Hughes](https://www.aestumanda.com/technology/2022/01/overdue-apple-voice-control-upgrade-should-include-better-dictation-accuracy/)) |
| Homerow | Keyboard labels on clickable elements ([site](https://homerow.app/)) | $49.99 one-time | Doesn't work in many apps ([HN](https://news.ycombinator.com/item?id=35456297)); price ([PH](https://www.producthunt.com/products/homerow/reviews)) |
| Shortcat | Type a button's name to click it | Not listed | Lag ([HN](https://news.ycombinator.com/item?id=35453231)) |
| Dragon for Mac | Dictation and commands | Discontinued 2018 ([MacRumors](https://www.macrumors.com/2018/10/24/nuance-discontinues-dragon-mac/)) | Users stranded ([Register](https://www.theregister.co.uk/2018/10/30/mac_users_burned_after_nuance_drops_dragon_speech_to_text_software)) |
| Vimac, Gameface | Open-source hints; head mouse | Free, both archived | Too slow; never ran on Mac ([issue](https://github.com/google/project-gameface/issues/44)) |

Complaints, by distinct sources:
1. **Can't reliably find or click the target in the app you're in: 10.** Slow hints, missing elements, browsers and Electron apps: "only work about 90-95% of the time" ([HN](https://news.ycombinator.com/item?id=35453313)), browsers look like "opaque windows" ([HN](https://news.ycombinator.com/item?id=35457348)), Voice Control failing in Gmail and Outlook web ([Apple](https://discussions.apple.com/thread/256317435)).
2. **Speech recognition and accents: 7.** 3. **Learning curve: 5.** 4. **Abandoned or closed tools: 5.** 5. **Voice Control bugs: 4.** 6. **Speaking out loud, noise, voice strain: 4.** 7. **Price: 2.**

**Webcam gesture control:** no paying customers found. The one paid app, [AirTouch](https://airtouchapp.com/), is "launching soon" with no pricing. The rest are free hobby projects ([Cenno](https://github.com/sapucaialuann/cenno), [Conductor](https://github.com/dev-talix/conductor), [Pawvis](https://pawvis.app/), [Gstrl](https://tomyang-tz.github.io/Gstrl/)). The nearest paid signal is hardware: Leap Motion sold over 1 million trackers ([cdm.link](https://cdm.link/2023/06/leap-motion-2/)).

## Answer

- Where people pay most (dictation, $8–15 a month), the top complaint is **accuracy, especially AI cleanup changing your words**. That's a model problem, not one Iris is placed to fix.
- In hands-free control, the top complaint is **not reliably clicking the right thing in the app you're in**.
- Iris's 10%: **start and stop dictation with your hand.** Raise a hand to record, lower it to paste: no key, no always-on mic. It's a real paid-user complaint (#5, 7 sources), it answers the reasons people give against always-on listening, and it's the one only a camera can fix. VoiceInk is open source (GPL-3, about 7k stars), so this can be built into VoiceInk and given back, not rebuilt.
