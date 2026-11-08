# Between the Lines

**Experience the barrier. Rethink the design.**

An interactive learning experience about reading effort and avoidable digital-accessibility barriers, created independently for the Fontys Interactive Media *Create That UX* project with Cardan as client.

## Open the website

Live website: https://f4lconaaa.github.io/-between-the-lines/
Repository: https://github.com/F4LCONAAA/-between-the-lines

Open `index.html` in a modern browser. No build step, database, account, external fonts, scripts or packages are required. To publish on GitHub Pages, put `index.html` in the repository root and enable **Settings → Pages → Deploy from a branch → main → / (root)**.

## The experience

- **Challenge 1: Decoding effort.** Decode an artificial substitution notice, track revisions, and find the final room and entry-card color.
- **Challenge 2: Time pressure.** Find two different times in a complicated event memo. Countdown is optional and can always be paused, extended or disabled.
- **Challenge 3: Information overload.** Find the current badge desk and ID requirement among competing notices.
- **Design lab.** Compare difficult and accessible versions of the same content. Try larger text, more spacing and browser-supported read-aloud.
- **Reflection and feedback.** Rate perceived frustration/understanding, review design lessons and optionally export a local text feedback report.
- **Client preview.** Use **Design lab** in the header or **Preview the design solutions** on the home page to reach the explanatory comparison without recording fictional session results.

Each challenge asks for two correct details. Visitors may skip any challenge. Errors can be retried; hints are available. No interface intentionally flashes, locks the user out or forces a failure.

## What the experience does *not* do

This is **not a dyslexia simulator** and cannot reproduce someone's lived neurological experience. The first task is an artificial decoding analogy. Other tasks illustrate unnecessary design barriers. The purpose is to support more informed digital-design choices, not to imply that dyslexia is equivalent to a cipher puzzle or frustrating website.

## Privacy and limitations

- The site stores no data on a server, sets no cookies and contains no analytics.
- Session metrics exist only in the current browser session and are not submitted anywhere.
- Feedback can be manually copied/downloaded only after consent. Visitors decide whether to share it.
- The interactive tasks and design patterns are research-informed, but **no increase in empathy has yet been established**. External participant testing and Cardan review are separate validation steps.
- Content is in English. Text-to-speech uses the browser's built-in speech synthesis and may be unavailable in some browsers.

## Development and evidence

The current version builds on an earlier one-question information-finding prototype. Informal creator feedback and recorded teacher feedback (Kadian, Portflow Checkpoint 7) identified that the tasks were too easy. The revised website introduces three challenge types and then two required answers per challenge. This is documented iteration, not a claim of formal usability testing.

See `ResearchAndDecisions.md` for the desk-research rationale and `ClientDemoGuide.md` for a short demonstration path. The code is a single self-contained HTML file with CSS and JavaScript. All additional repository commits should describe genuine later changes.

