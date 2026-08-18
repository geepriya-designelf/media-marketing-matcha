# Marketing Matcha

A Claude Skill for turning original thoughts, blog drafts, and rough ideas into
writing that connects with an audience — without flattening a personal voice into
generic marketing content.

Matcha is whisked, not diluted. The skill makes an idea more concentrated and
more drinkable at the same time.

## The core move

```
Your original thought -> understand the audience -> find the natural bridge -> express it in an interesting way
```

The order is the philosophy. Most writing advice runs it backwards — start with
what performs, then bend the thought to fit. This starts with what you actually
think.

## What it does

Give it a blog post, a half-formed thought, or a paragraph you're stuck on, and
it acts as thought partner, blog editor, creative writing partner, audience
strategist, and social editor at once. It returns:

1. What I think you're really saying
2. Marketing Match *(audience + the bridge + an Attention Map)*
3. What's working
4. What I'd change
5. Polished version
6. Creative phrases *(hooks, memorable lines, transitions, headlines, endings, provocations)*
7. Social Match *(one post for LinkedIn and Instagram — angle, 3 hooks, 3 phrases, the post, the visual, conversation starters)*
8. My strongest recommendation — ending with **"If this were mine, I'd..."**

It is built to be honest. If a draft is already good, it says so and leaves it
alone. If the strongest idea is buried in paragraph four, it points at the line.
If a piece is boring or trying too hard, it says that too — and diagnoses why.

## What it won't do

Optimize for virality, or make you sound like a marketing guru, a LinkedIn
influencer, a corporate executive, an AI, or a motivational speaker. Phrases like
"In today's rapidly changing world," "Let that sink in," "Agree?", "This is your
reminder," and "game changer" are out — along with anything else that announces
significance instead of earning it.

The target is: a thoughtful person sharing an interesting observation with
another thoughtful person.

## Install

Copy the skill directory into your skills folder:

```bash
# personal skills, available everywhere
cp -r marketing-matcha ~/.claude/skills/

# or project-scoped
cp -r marketing-matcha /path/to/project/.claude/skills/
```

## Use

Just share the writing — the skill triggers on its own:

- "Here's my blog draft, can you help me sharpen it?"
- "I have a rough thought about design systems, is there anything here?"
- "Give me some hooks for this post."
- "Turn this into a post I can put on LinkedIn and Instagram."
- "Be honest — is this boring?"

## Layout

```
marketing-matcha/
├── SKILL.md                          the method, output format, voice rules
└── references/
    ├── voice.md                      anti-generic engine, AI tells, calibration
    ├── creative-language.md          devices for hooks, phrases, headlines, endings
    ├── social.md                     one post for both platforms: angle, structure, the visual
    └── worked-example.md             one full eight-section pass on a real draft
```
