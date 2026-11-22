# TypeMe: Spec

**Fun quizzes with results worth sharing** · #27 of 31 · Wave 3: Seasonal and episodic · Used: Episodic · Easy, content-heavy · Revenue potential: Low–high (hit-driven) · Social, Play & Style · Source: ChatGPT

## One-liner

Quick personality and lifestyle quizzes ('What type of Londoner are you?', 'How chaotic is your life?') with result cards designed for TikTok and Instagram stories.

## Problem / audience

- **Who it's for:** Social-media users who like quizzes and sharing their results.
- **The problem it solves:** People love fun self-discovery and showing what they got.
- **Example:** Someone sees a friend's 'Chaotic Good Londoner' result on their Story, taps the link, does the quiz and shares their own.

## MVP features (ship with only these)

1. Quiz engine: questions, weighted answers, result types
2. 5–10 launch quizzes
3. Result share cards sized for Stories
4. Regular new quizzes

## Not in MVP

- Premium quiz packs
- Daily quiz streak
- Sponsored quizzes, clearly labelled

## Monetisation

| Model | Detail |
|---|---|
| Free | All quizzes, with ads |
| Premium | Quiz packs |
| Sponsored | Brand quizzes, clearly labelled |

Prices are starting points; test before committing. **Portfolio premium promise:** free has ads; the moment you pay you get no ads, cloud backup and storage, and sync across your devices, plus this app's extras.

## Retention: The Progression Loop

| Stage | Design |
|---|---|
| Cue | New quiz drops (opt-in) |
| Tiny win | Finish a quiz |
| Progress | Quizzes completed, types collected |
| Share | Result cards |
| Next step | A related quiz suggestion |
| Cadence | Weekly drops |

Follow the portfolio guardrails: no guilt-trip notifications, no fake urgency, progress is
never wiped, at most one notification a day by default.

## Animation and tone: five signature animations

**Full drama.** Duolingo-style theatrics: characters, big over-the-top reactions, sound effects. Thirsty's plant death is the only animation that takes over the full screen ('NOOOOOOO!!!! NOT CYPHICUS!!!!').

- Result reveal: drumroll, spotlight and the character's grand entrance
- Rare type: sparkles and a crown
- Quiz start: the question cards shuffle like a magic trick
- Share card made: it zooms in like a movie poster
- Every type collected: the trophy shelf fills up

**Line we don't cross:** Never mocks a result type.

## AI

**None.** Not needed. Plain code does everything this app does. (Portfolio rule: plain code first, code does the maths,
cheapest model, shared budget cap, premium-gated.)

## Platform & data

- **Platform:** Web first (so shared links open instantly), then Expo.
- **Data:** On the device only; anonymous result counts.
- **Backend:** Static web pages for shared quiz links and new quizzes. Premium backup and sync use the shared portfolio backend (see the master repo's HOSTING.md).
- **Stack:** shared portfolio foundation (Expo, PostHog, RevenueCat, AdMob, shared Progression Loop module).

## Growth engine

- **Content pillars:** Quiz results; 'Which type are you' trends; Relatable humour
- **Shareable output:** Result cards

## Risks

Hit-driven, and needs a steady flow of good quizzes. Never claim scientific personality testing.

## Launch checklist

- [ ] Name checked on the App Store, Play Store and a trademark search
- [ ] MVP features done and tested
- [ ] Progression Loop wired (cue, tiny win, progress, milestone, next step)
- [ ] Privacy policy and terms
- [ ] Landing page
- [ ] Analytics wired (D1/D7/D30 retention)
- [ ] Payments / ads wired
- [ ] Added to the Growth & Maintenance Engine as an app config
