# Dialogue Coach (v0.2, frozen)

[中文](README.md)

A skill that makes your AI stop rushing to answers — and helps you say what you actually feel first.

Most AI assistants answer whatever you ask. Even when you haven't worked out what's really bothering you, they hand you a plausible-looking plan.

This skill does the opposite. It watches for the places where your words don't line up — you say "it's fine" when your situation clearly isn't; you say "my boss really values me" while your review came back a B — and asks one question at a time, helping you see what you hadn't noticed yourself.

Before every conversation ends, it makes sure of one thing: you leave on solid ground, not left hanging.

## Good for

- Feeling stuck at work, with a co-founder, managing a team, or weighing a business decision
- The "I can't quite say what's wrong" kind of stuck
- When you want to talk something through, but aren't ready to bring it to a person yet

## What it won't do

- Make decisions for you
- Act as therapy — it stays away from family-of-origin issues and deep trauma
- Hand out life advice

## Before you use it

- It's built for everyday dilemmas and feeling stuck — when you want to sort your thoughts out or just talk.
- If you're in serious emotional distress — prolonged sleeplessness, emotions that feel out of control, or thoughts of hurting yourself — please reach out to someone you trust or a local professional support service first. This skill is not a substitute for professional help.
- It will press on the places where your words don't match, and sometimes that touches things you aren't ready to face yet. If it feels uncomfortable at any point, just say "stop".
- Use it with a strong model such as Claude. Here's why.

## Why the model matters

This isn't a product endorsement. The rules themselves demand a capable executor.

The riskiest move in this method is the *break-through*: naming something the person hasn't yet said out loud. It's only safe because a *grounding protocol* follows immediately — acknowledge, normalize, hand the choice back, and offer one small doable step. **The break-through and the grounding are two halves of one move. Doing only the first half causes harm.**

Weaker models typically fail in three ways:

1. **Doing only the first half.** They point out the contradiction sharply and accurately, then stop. The person is opened up, and no one catches them.
2. **Misreading.** They treat normal expression as a contradiction and keep pressing on something that isn't there, leaving the person feeling oddly suspected.
3. **Overstepping.** The rules explicitly stay out of family history and core beliefs, but weaker models tend to follow the thread all the way down. That's therapy territory, not something this method can handle.

Judging whether the intensity is too high or too low also requires comparing emotional language against the situation across the whole conversation. Lose the context, and the judgment falls apart.

## Language

The rules are written in Chinese. With a capable model, just start talking in English.

## Disclaimer

This skill offers a way of having a conversation. It is not counseling, psychotherapy, diagnosis, or medical advice.

The author provides this file as-is under CC BY-NC 4.0 and is not responsible for outcomes on any third-party platform, model, or adapted version. If you need professional help, please contact a professional.

## Origin

Created by Zhang Liang (Leo), who has about 20 years in internet operations and is the author of the Chinese bestseller *从零开始做运营* (*Operations from Scratch*, CITIC Press). The questioning approach is distilled from real conversations across years of peer advisory boards and 1-on-1 consulting sessions.

v0.2 is frozen and will not be updated. The continuously evolving version runs inside the [New Variable (新变量) Business Club](https://v3lsw.xetsl.com/s/2f1WjD), a Chinese-language community. That version keeps growing from real daily conversations: it remembers what you said last time, and gives you a push when you need it, not just a mirror.

## Install

**Option 1 · Claude app:** Settings → Capabilities → Skills, then upload `dialogue-coach.skill`.

**Option 2 · skills CLI** (Claude Code / Cursor / Codex / Copilot and more):

```bash
npx skills add zhangleo-1983/Dialogue_Coach --skill dialogue-coach
```

## License

[CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/)

- Personal, learning, and non-commercial use and adaptation: go ahead, just credit the author (Zhang Liang / Leo).
- Internal company deployment, integration into paid products or services, or any commercial use: requires separate permission. Please contact the author.

## Contact

- Email: zhangliang@getbitbeats.com
- WeChat: zhangleo
