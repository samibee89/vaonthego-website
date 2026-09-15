# Automation Time-Savings Calculator — Brief

## Purpose
A business demo tool for VAontheGO — shows potential clients roughly how much time/money
they could save by automating manual tasks. Lives on the main website as its own page
(e.g. /calculator/), linked from the "Things I've Built" section.

## Important: this should feel DIFFERENT from the quiz
The quiz is a step-by-step journey (one question at a time, single result at the end).
This should be the opposite: a live, all-on-one-screen tool that recalculates instantly
as the person adjusts inputs. Think "dashboard" or "calculator app" feel, not "quiz" feel.

## Layout
- Split screen (or stacked on mobile): inputs on one side, live result on the other
- No "next question" flow — everything visible and adjustable at once
- Result updates instantly (no submit button) as sliders/inputs change
- Subtle animation on the result number when it updates (e.g. a brief highlight or
  count-up effect) so the live-updating feels satisfying, not just instant/flat

## Inputs (left side, or top on mobile)
1. **Hours per week spent on manual/repetitive tasks** — slider, range 1-40 hours
2. **Number of people doing this type of work** — number input or small stepper, range 1-20
3. **Average hourly cost of that time** — slider or input, in USD, range $15-$100
   (label it clearly as "your estimate — doesn't need to be exact")
4. **How automatable does this feel?** — a simple 3-option selector: Low / Medium / High
   (this adjusts the estimated % of time that could realistically be saved:
   Low = 20%, Medium = 40%, High = 60%)

## Live result (right side, or below on mobile)
- **Hours saved per week** (calculated: hours x number of people x automation %)
- **Estimated monthly cost savings** (hours saved x 4.3 weeks x hourly cost)
- **Estimated annual cost savings** (monthly x 12)
- A short line of context under the numbers: "These are rough estimates — every
  business is different, but this gives you a sense of the impact."

## Below the calculator
- A closing line: "Curious what this could look like for your business specifically?"
- A "Contact me" button linking to the homepage contact section (https://vaonthego.com/#contact)

## Style
- Same brand as the rest of the site: black (#1A1A1A), white, soft blue (#5B8DEF),
  soft pink (#E893C0), Playfair Display for headings, Inter for body text
- BUT lean into a cleaner, more "tool/dashboard" aesthetic than the quiz's playful tone —
  think clean cards, subtle borders, numbers that feel satisfying to watch update
- Keep the same header/logo as the rest of the site so it still feels connected

## Notes for Claude Code
- This should live in its own folder (e.g. /calculator/) inside the main website project,
  following the same folder-per-project pattern used for /quiz/
- Plain HTML/CSS/JS — no backend, no database, all calculation happens live in the browser
- Add it to the "Things I've Built" section on the homepage alongside the quiz
- Make sure inputs are easy to use on both desktop and mobile (sliders should be
  touch-friendly)
