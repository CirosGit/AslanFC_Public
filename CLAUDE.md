# Aslan FC Website — working notes

## About the user
- The user does NOT code. Explain things in plain, non-technical language. Never assume coding knowledge.

## Publishing / GitHub
- When the user asks to "push to GitHub" (or publish), just do it end-to-end — don't hand back coding steps for them to run.
- Always include the `.image-slots.state.json` sidecar file at the project root in any GitHub push / deploy. The dropped/uploaded photos live in that file. If it's missing, every image falls back to the empty "DROP IMAGE HERE" placeholder.
- Make sure that dotfile is NOT gitignored.

## Images
- Every image across the site is a drag-and-drop `<image-slot>` (embedded inside the shared `Placeholder.dc.html`). The user fills images by dragging files onto them in THIS editor.
- Editing only works inside this editor (needs the host write bridge). Published/downloaded versions are read-only — online visitors cannot edit the site.
