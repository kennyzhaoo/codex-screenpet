# v0.1.5-beta.1 Beta Notes

Codex ScreenPet turns a spare phone, tablet, or browser screen into a local dashboard for Codex Desktop tasks.

## Included Artifacts

- `downloads/Blinky-Codex-ScreenPet-v0.1.5.dmg`
- `downloads/codex-screenpet-runtime.zip`
- `downloads/codex-screenpet-runtime-manifest.json`

## Highlights

- DMG includes `READ ME FIRST.pdf` with an illustrated installation guide.
- Recent Codex Desktop task list with readable message previews.
- Task detail view with independently scrollable conversation context.
- Mobile instruction composer with delivery confirmation against the target conversation log.
- Local setup page with Blinky password, QR codes, local/private-network URLs, and permission notes.
- Native macOS menu bar MVP for Start Server, Stop Server, Open Setup, Launch at Login, and user-confirmed runtime update checks.
- Open Setup starts the local server automatically when needed, then opens the setup page after readiness is confirmed.
- Menu bar server startup works with common macOS Node.js installs, including Homebrew, nvm, Volta, mise, asdf, and the Codex Desktop bundled runtime.
- Demo mode for public screenshots without reading real Codex data.

## Known Limits

- macOS only.
- Codex Desktop must be installed and working on the same Mac.
- Designed for trusted Wi-Fi, Tailscale/private network, or a tunnel you control.
- Do not expose the local server directly to the public internet.
- Runtime updater does not update the native menu bar app itself.
- The DMG is a beta artifact and is not yet Developer ID signed or Apple notarized.
- On macOS, users may need to right-click Open or remove the download quarantine for this unsigned beta.

## Verification Snapshot

- Version: `0.1.5`
- Runtime version: `0.1.5+8176bb4`
- Git revision: `8176bb4`
- Dirty worktree at generation time: `false`
- App DMG size: `7474971` bytes
- Runtime zip size: `281748` bytes
