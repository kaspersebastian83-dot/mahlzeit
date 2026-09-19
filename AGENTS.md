# Mahlzeit project rules

- Mahlzeit is a mobile-first static web application deployed through GitHub Pages.
- Preserve the existing lightweight architecture.
- Do not introduce React, Vue, Angular, Next.js, Vite, npm, or another build system unless explicitly requested.
- Prefer small targeted changes over rewrites.
- Preserve existing functionality unless the task explicitly requests a behavioral change.
- Preserve GitHub Pages compatibility.
- Do not add dependencies unless necessary.
- Existing browser data stored under `mahlzeit.v1` must remain compatible.
- Before implementing a feature, inspect the existing implementation.
- Do not modify unrelated code.
- After changes, check the application for JavaScript errors and inspect the Git diff.
- Pay particular attention to mobile layouts.
- Report what changed, what was tested, and any remaining limitations.
