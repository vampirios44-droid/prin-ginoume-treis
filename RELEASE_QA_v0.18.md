# Release QA — v0.18

## Passed automatically
- 9 chapters
- 21 choices
- 63 branches
- 16 delayed memory hooks
- 9 chapter visuals + optimized cover
- Embedded JavaScript syntax
- all-A, all-B, all-C engine routes
- 500 additional random complete routes
- Choice effects / conditional effects / flags remain numerically valid
- Story Passport and save schema identifiers unchanged

## Sandbox limitation
The execution environment blocks browser navigation to localhost and file URLs, so a real DOM/browser E2E test could not be executed here.

## Final manual smoke test
Use the Netlify `development` URL on the real iPhone to verify cover → choices → resume → menu/settings → passport → ending/mirror, and optionally offline after one online load.
