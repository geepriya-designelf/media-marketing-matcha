# Worked example

One complete pass, so the shape and the standard are both concrete. Read this
when you want to see how honest, specific, and voice-preserving the output
should be.

---

## The draft the writer sent

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

---

## 1. What I think you're really saying

On the surface: design systems fail for unglamorous reasons.

But there's a sharper idea sitting in paragraph three, and I don't think you've
noticed you wrote it. **The design system wasn't being rejected. It was being
missed.** Those are completely different failures with completely different
fixes, and almost everyone in your position diagnoses the first one — which
leads them to evangelize harder, run more workshops, build more components.

Your real claim is that an adoption number is often a *findability* number
wearing a costume. That's a more useful and more arguable thought than "boring
reasons matter," and it's the one I'd build the piece around.

The line doing the most work: *"We didn't add a single feature."* Everything
before it is setup for that sentence.

## 2. Marketing Match

**Who cares:** design system leads, design ops people, and the staff engineers
who inherit internal tooling. Secondarily, anyone maintaining an internal
platform nobody uses enough — the pattern generalizes past design.

**Why they care:** most of them have an adoption number they're slightly
embarrassed by and a roadmap full of features they believe will fix it. They're
usually also being asked to justify the team's existence. You're handing them a
cheaper hypothesis to test this week.

**The tension it connects to:** the gap between "we built something good" and
"people use it," and the quiet suspicion that the gap is their fault. Your
answer — it might just be the words — is a relief and a challenge at once.

**The bridge:** reframe adoption as a search problem. That framing is concrete,
testable in an afternoon, and it costs nothing. It also flatters no one, which
is why it's credible.

**Emphasize:** 40% → 80%, zero features, thirty renames. Numbers with an absence
attached are more persuasive than numbers with an achievement attached.

**Attention Map**
- **STOP** — "He wasn't ignoring the design system. He couldn't find it."
- **PULL** — the reader wants to know what the fix cost. You do not tell them
  until paragraph four, which is correct.
- **CONNECT** — they have their own 40%, and they've been solving it by
  building.
- **REMEMBER** — "We didn't add a single feature." Also the dropdown/Select Menu
  pair, which is the kind of detail people repeat in meetings.
- **RESPOND** — everyone who owns an internal tool will want to say what their
  version of "Select Menu" was. That's a good comment section.

## 3. What's working

Paragraphs three and four are genuinely good and I wouldn't touch them. The
reporting voice — flat, sequential, no adjectives — is what makes the payoff
land. If you'd written "I had a revelation," the same facts would be worth half.

Keep *"for him at least."* It's the most trustworthy thing in the piece. It
tells me you didn't over-claim from one observation, which is exactly why I
believe the rest.

Keep *"honestly beautiful"* about the Figma library. It's a small self-aware
joke and it's yours.

## 4. What I'd change

- **The opening is borrowed.** "In today's fast-paced product world, design
  systems are essential" could sit at the top of ten thousand posts. It also
  delays your first real sentence by 14 words. Cut it entirely — you have a much
  better opening sitting in paragraph three.
- **Your thesis is in the second-to-last paragraph.** "Nobody wants to talk
  about search" is the piece. Right now it arrives after the reader has already
  decided how they feel.
- **The ending shrugs.** "Anyway, that's my experience. Let me know if you've
  seen something similar!" undoes the confidence of everything above it. You
  spent five paragraphs earning a position and then apologized for having one.
- **One repetition to lose:** "The problem was adoption" and "Adoption still
  hovered around 40%" do the same job. The number does it better.
- **Not boring, but nearly.** Paragraph two is a list of efforts with no texture.
  One concrete detail from a workshop nobody came to would fix it.

## 5. Polished version

> **Why our design system kept failing**
>
> I sat down to watch one of our engineers work, expecting to find out why he
> was ignoring our design system.
>
> He wasn't ignoring it. He couldn't find it. He typed "dropdown" into the
> search bar, got nothing, and built his own. Our component was called "Select
> Menu."
>
> That was it. That was the whole problem, for him at least.
>
> We'd spent a year on everything else. Workshops — one of which had three
> attendees, two of them from my team. Documentation. A Figma library that was,
> honestly, beautiful. Adoption sat at 40%.
>
> We renamed about thirty components based on what engineers actually typed into
> the search bar. Two months later adoption was at 80%. We didn't add a single
> feature.
>
> I've come to think design systems fail for boring reasons far more often than
> they fail for design reasons. Everyone wants to talk about tokens and theming
> and governance. Nobody wants to talk about search.
>
> I don't know how far this generalizes. But if your adoption number is bad, I'd
> check what people are typing before I'd build anything else.

**What I changed:** opened on the scene instead of the throat-clearing; moved
the workshop detail down so it reads as context rather than preamble and added
the three-attendees specific; cut the duplicate adoption line; ended on a
narrowed claim instead of a shrug. Your sentences are otherwise intact.

## 6. Creative phrases

**Hooks**
- *(admission)* "I sat down to find out why an engineer was ignoring our design
  system. He wasn't."
- *(concrete detail)* "He typed 'dropdown.' We'd called it 'Select Menu.'"
- *(reversal)* "Our design system had a 40% adoption problem. It turned out to
  be a spelling problem."
- *(small stake)* "This is a post about renaming thirty things."

**Memorable phrases**
- "We didn't add a single feature." *(already yours — protect it)*
- "An adoption number is often a findability number in disguise."
- "We'd built a library nobody could spell their way into."
- "Search is where good systems go to be invisible."

**Transitions**
- "We'd spent a year on everything else." *(hinge into the list of efforts)*
- "Which is the part I got wrong." *(if you want to own the year more directly)*

**Headlines**
- *(plain)* "Our design system didn't have an adoption problem"
- *(tension)* "The fix cost nothing and I'm still annoyed about it"
- *(phrase-forward)* "Nobody wants to talk about search"

**Ending lines**
- "If your adoption number is bad, check what people are typing before you build
  anything else."
- "A year of work. Thirty renames. I'd like those in the other order."
- "Turns out the system was fine. The index was broken."

**Slightly provocative**
- "Most design system roadmaps are a way of avoiding the unglamorous work."
- "Governance is what teams build instead of asking users what they call things."

Both of these are defensible positions you'd survive an argument about. That's
the bar — not whether they get a reaction.

## 7. Social Match

Same post, both places — so this has to work as pasteable text and as an image.

**The angle:** the misdiagnosis, not the fix. Aimed squarely at people who own an
internal tool with disappointing usage. Leading with "we renamed things and
adoption doubled" makes it a tip; leading with "I was wrong about why nobody was
using it" makes it a story someone recognises themselves in. Rejected: the
"boring reasons" thesis (too abstract to open with) and the 40→80 number (great
proof, weak hook — a number without a story reads as a brag).

**3 hooks**
1. *(admission)* "I spent a year making our design system better. The thing that
   actually worked took an afternoon."
2. *(scene)* "I watched an engineer type 'dropdown' into our search bar and get
   nothing back. We'd called it 'Select Menu.'"
3. *(reversal)* "I assumed people were ignoring our design system. They were
   looking for it."

**3 memorable phrases**
- "An adoption number is often a findability number in disguise."
- "We didn't add a single feature."
- "Nobody wants to talk about search."

**The post**

> I watched an engineer type "dropdown" into our component search and get nothing
> back.
>
> We'd called it "Select Menu."
>
> He shrugged and built his own. I'd spent a year assuming people like him were
> ignoring the design system — so we ran workshops, wrote documentation, made a
> Figma library that was honestly beautiful. Adoption sat at 40%.
>
> He wasn't ignoring it. He couldn't find it.
>
> We renamed about thirty components based on what engineers actually typed into
> the search bar. Two months later we were at 80%. We didn't add a single
> feature.
>
> I've started to think an adoption number is often a findability number in
> disguise. Everyone wants to talk about tokens and governance. Nobody wants to
> talk about search.
>
> I don't know how far it generalises — one team, one search bar. But it's the
> cheapest thing I'd check first.

**The visual:** the artifact route, and it's an easy one here — a search field
with `dropdown` typed in it and *0 results* underneath. One frame, no words
needed beyond what's in the UI, and it reads identically as an Instagram image
and as a LinkedIn attachment. Reach for this before considering a carousel; the
post is a single turn, not a sequence, so slides would just be the same story
cut into pieces.

**Conversation starters**
- "Curious what your version of 'Select Menu' was. I suspect everyone has one."
- "The obvious objection: this worked because our system was actually good
  underneath. If yours isn't, renaming won't save it."
- "I still don't know whether to fix this at the naming layer or the search
  layer. Aliases felt like a cop-out. Maybe it isn't."

## 8. My strongest recommendation

Rebuild the piece around the misdiagnosis rather than the fix. Right now it's
structured as a case study with a lesson at the end; it's stronger as a story
about being confidently wrong for a year, where the fix is almost a punchline.
Same facts, better shape — and it earns the thesis instead of announcing it.

**If this were mine, I'd** delete the first paragraph and open on the engineer
typing "dropdown." That single change fixes the throat-clearing, moves your best
scene to the front, and makes the reader arrive at "nobody wants to talk about
search" already agreeing with you — which is the only way that line lands as
insight instead of opinion.
