# Worked example

One pass end to end, so the shape and the standard are both concrete.

## The draft

> **Why our design system kept failing**
>
> In today's fast-paced product world, design systems are essential. We built
> ours in 2023 and everyone was excited about it.
>
> The problem was adoption. Engineers kept building their own components anyway.
> We ran workshops. We wrote documentation. We made a Figma library that was
> honestly beautiful. Adoption still hovered around 40%.
>
> Eventually I sat with one of the engineers and watched him work. He wasn't
> ignoring the design system. He couldn't find it. He was searching for
> "dropdown" and our component was called "Select Menu." That was it. That was
> the whole problem, for him at least.
>
> We renamed about thirty components based on what engineers actually typed into
> the search bar. Adoption went to 80% in about two months. We didn't add a
> single feature.
>
> I think design systems fail for boring reasons more often than they fail for
> design reasons. Everyone wants to talk about tokens and theming and
> governance. Nobody wants to talk about search.
>
> Anyway, that's my experience. Let me know if you've seen something similar!

## Questions first

**Reading time: 250 words, about 1 minute 15 seconds.** Under the limit.

Before the table, one thing the draft does not settle:

**Did you rename the components, or add aliases?** "Renamed" and "based on what
engineers typed" could mean either, and it changes the claim. Renaming is a
migration with a real cost. Aliasing is nearly free, which would make the story
stronger and the advice more portable.

Nothing below depends on the answer, so the table stands either way. Say which
and the closing line can be sharpened.

## The table

| # | Original | Suggested | Why |
|---|---|---|---|
| 1 | "In today's fast-paced product world, design systems are essential." | Cut it. Open on "I sat down to watch one of our engineers work." | Fourteen words of throat-clearing before the first real sentence, and your best scene is sitting in paragraph three. |
| 2 | "He wasn't ignoring the design system. He couldn't find it." | *no change* | Strongest line in the piece, and the whole argument in nine words. Protect it. |
| 3 | "That was it. That was the whole problem, for him at least." | *no change* | "For him at least" is the most trustworthy phrase here. It shows you did not over-claim from one observation, which is why the rest is believable. |
| 4 | "The problem was adoption... Adoption still hovered around 40%." | Cut the first sentence, keep the number. | Same job done twice. The number does it better. |
| 5 | "We ran workshops. We wrote documentation." | "Workshops, one of which had three attendees, two of them from my team." | The list has no texture. One concrete detail carries the whole year of effort. |
| 6 | "I think design systems fail for boring reasons..." | Move it up, straight after the renaming paragraph. | This is your thesis, currently arriving after the reader has already decided how they feel. |
| 7 | "Anyway, that's my experience. Let me know if you've seen something similar!" | 7a: "If your adoption number is bad, check what people are typing before you build anything else."<br>7b: "Turns out the system was fine. The index was broken."<br>7c: keep yours | You spent five paragraphs earning a position, then apologised for having one. |

## The full alternative

> **Why our design system kept failing**
>
> I sat down to watch one of our engineers work, expecting to find out why he was
> ignoring our design system.
>
> He wasn't ignoring it. He couldn't find it. He typed "dropdown" into the search
> bar, got nothing, and built his own. Our component was called "Select Menu."
>
> That was it. That was the whole problem, for him at least.
>
> We'd spent a year on everything else. Workshops, one of which had three
> attendees, two of them from my team. Documentation. A Figma library that was,
> honestly, beautiful. Adoption sat at 40%.
>
> We renamed about thirty components based on what engineers actually typed into
> the search bar. Two months later adoption was at 80%. We didn't add a single
> feature.
>
> Design systems fail for boring reasons far more often than they fail for design
> reasons. Everyone wants to talk about tokens and theming and governance. Nobody
> wants to talk about search.
>
> Turns out the system was fine. The index was broken.

## Phrases to lift

| Where | Phrase |
|---|---|
| Opening | "He typed 'dropdown.' We'd called it 'Select Menu.'" |
| Middle | "We didn't add a single feature." *(already theirs, protect it)* |
| Middle | "An adoption number is often a findability number in disguise." |
| Ending | "Turns out the system was fine. The index was broken." |

## What this pass demonstrates

The buried lede sat in paragraph three and the thesis was second from last, which
is the most common shape a good draft arrives in. Two rows change nothing, because
telling the author which lines to protect is half the value. The one ambiguity
became a question instead of a guess, and the table went out anyway rather than
waiting on the answer.
