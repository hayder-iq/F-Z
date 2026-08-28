FLASH ZOON — working-first build

Base:
- Supplied 22-main(1).zip.

Visual changes:
- Shared flash-zoon.css based on the user's supplied FLASH ZOON identity.
- Same orange/black identity and background across all firmware pages.
- Existing buttons, routing, cache manifests, JS, BIN, payload and patch files are preserved.

Important:
- Do NOT upload the ZIP itself into GitHub. Upload its contents to the repository root.
- GitHub Pages: Settings -> Pages -> main -> /(root).
- Vercel: static/Other, no build command.

Validation:
- Operational (non-HTML/CSS) files unchanged.
- Local HTML references checked.
