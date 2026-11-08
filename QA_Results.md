# Website quality checks

## Scope

The following are *technical/browser checks*, **not** a formal accessibility certification or usability study. The site was exercised in Chromium using an injected self-contained HTML document because the QA container restricts direct navigation to localhost and external test origins.

## Checks performed

- Website loads with no JavaScript errors.
- Challenge 1: choosing both correct details enables submission and proceeds to reflection.
- Challenge 2: choosing an incorrect answer prompts a retry; changing the answer succeeds.
- Challenge 2: countdown can be paused, resumed, extended and disabled.
- Challenge 3: a hint can be expanded, the two details can be answered, and the experience can be completed.
- All three challenges support skipping; skipped tasks are not counted as completed.
- Results are calculated from local session data rather than invented or uploaded data.
- Accessible comparison switches between difficult and accessible text; text-size and spacing settings respond.
- Feedback download buttons remain disabled without explicit user consent.
- Direct design-lab preview does **not** display invented results and is labelled as a preview.
- Mobile layouts at 320px, 375px, 390px and tablet/desktop widths at 768px, 1024px, 1440px show no document-level horizontal overflow.
- Inline JavaScript passes Node.js syntax checking.

## Limitations

- Testing used automated interactions, not external participants.
- Some optional features (e.g. actual browser text-to-speech voices, real downloaded feedback files and live-host deployment) should be confirmed in their target browsers.
- No complete WCAG conformance audit or screen-reader assessment has been performed.
- A real participant with dyslexia should review whether the content is accurate and respectful; their feedback must not be fabricated.
- The published GitHub Pages URL must be checked after deployment.

## Recommended manual check before sharing

Open the live URL in Chrome and a mobile browser. Complete or skip all tasks, use the design-lab shortcut, check source links, download a feedback report with consent, and verify keyboard navigation and readable zoom.

## Hosted verification on 8 November 2026

The public deployment was checked in Brave at https://f4lconaaa.github.io/-between-the-lines/ after enabling GitHub Pages from main / root.

- All three challenges accepted their two correct answers and revealed reflection and continuation.
- The final review showed 3/3 correct tasks. No frustration or understanding ratings were invented for this check.
- Pausing the optional countdown displayed Resume and a paused explanation. Disabling it displayed OFF. Extension was activated, but its exact increment was not independently measured in this hosted walkthrough.
- Accessible view displayed grouped facts and clear headings. Larger text and more spacing visibly changed the sample.
- Feedback download remained disabled without consent. Actual downloaded report contents, clipboard output and speech voices were not reverified in this hosted walkthrough.
- Inline JavaScript syntax was also checked with Node successfully.

These are assistant-assisted technical checks, not participant research, a full keyboard/screen-reader audit, accessibility certification or evidence that empathy improved. The earlier QA record above is retained as an earlier record; its mobile checks were not newly repeated during this hosted walkthrough.
