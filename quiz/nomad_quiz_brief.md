# "What Kind of Digital Nomad Are You?" — Quiz Brief

## Purpose
A fun, practice project — a personality quiz, single web page, no backend needed.
Not a business lead-magnet (that's a future project) — just for learning and enjoyment.

## Format
- 6 multiple-choice questions, one shown at a time (not all on one page)
- Each answer option is silently worth points toward one of 4 result "types"
- After the last question, show the result with the highest score
- A "Retake quiz" button at the end to start over
- Simple progress indicator (e.g. "Question 3 of 6") so it doesn't feel endless

## The 4 result types

1. **The Beach Bum**
   Laptop in the sand, minimal schedule, works around the tide not the clock.

2. **The Coworking Regular**
   Loves structure, community, and a good coffee shop or coworking space. Same desk, different country.

3. **The Off-Grid Explorer**
   Chases remote, unusual places. Unpredictable wifi is a badge of honor, not a problem.

4. **The Home Base Hybrid**
   Travels in bursts but always returns to one home base. Nomad life on their own terms.

## Sample questions (Claude Code can refine wording, keep the spirit)

1. Your ideal "office" for the day is...
   - A hammock near the water (Beach Bum)
   - A buzzing coworking space with good coffee (Coworking Regular)
   - Somewhere remote most people have never heard of (Off-Grid Explorer)
   - My same home desk, thanks (Home Base Hybrid)

2. Your wifi just cut out mid-call. You...
   - Shrug, it happens, back to the beach (Beach Bum)
   - Panic slightly, wifi reliability matters to you (Coworking Regular)
   - Expected it, that's part of the adventure (Off-Grid Explorer)
   - Rare occurrence, your setup is solid (Home Base Hybrid)

3. Your packing style is...
   - Barely anything, flip-flops and a laptop (Beach Bum)
   - Efficient carry-on, you've got a system (Coworking Regular)
   - Prepared for anything, gear-heavy (Off-Grid Explorer)
   - You mostly don't pack, you're usually home (Home Base Hybrid)

4. A "successful week" for you looks like...
   - Good sunsets, a few good emails sent (Beach Bum)
   - Deep work done, met some interesting people (Coworking Regular)
   - Saw something incredible nobody else has (Off-Grid Explorer)
   - Calm, routine, got through the to-do list (Home Base Hybrid)

5. Your ideal travel pace is...
   - Slow, why rush a good thing (Beach Bum)
   - A few weeks per place, enough to settle in (Coworking Regular)
   - Wherever the wind takes me (Off-Grid Explorer)
   - I don't move much, I like my base (Home Base Hybrid)

6. Pick a drink:
   - Fresh coconut, obviously (Beach Bum)
   - Oat milk flat white (Coworking Regular)
   - Whatever's local and unfamiliar (Off-Grid Explorer)
   - My go-to order, I know what I like (Home Base Hybrid)

## Style
- Reuse the same brand as the VAontheGO website: black (#1A1A1A), white, soft blue (#5B8DEF),
  soft pink (#E893C0), blue-to-pink gradient for backgrounds/accents
- Headings in Playfair Display, body text in Inter (both via Google Fonts)
- Keep it playful and light — this one can have more personality/fun than the business site
- Mobile-friendly, single page, no login or backend needed

## Notes for Claude Code
- Build as a single responsive HTML/CSS/JS page
- No database needed — all quiz logic and scoring can run in the browser
- Keep it lightweight — this is a fun practice project, not a complex app
