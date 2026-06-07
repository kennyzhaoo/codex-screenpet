# Downloads

## First-time install

Download this file:

[Blinky-Codex-ScreenPet-v0.1.1.dmg](https://raw.githubusercontent.com/kennyzhaoo/codex-screenpet/main/downloads/Blinky-Codex-ScreenPet-v0.1.1.dmg)

Open the DMG, drag `Blinky Codex ScreenPet.app` into **Applications**, then open it from Applications on the Mac that runs Codex Desktop.

This free beta is not yet signed with an Apple Developer ID or notarized by Apple. macOS may ask you to allow it in **System Settings -> Privacy & Security**. That is expected for this early GitHub beta.

Only open software you trust. If you want to try this beta, use **right-click -> Open** first. If macOS still blocks it, choose **Open Anyway** for Blinky in **System Settings -> Privacy & Security**.

Advanced fallback after installing to Applications:

```sh
xattr -dr com.apple.quarantine /Applications/Blinky\ Codex\ ScreenPet.app
```

Then open the app again.

## Advanced update files

These files are for the app's runtime update system. Most users do not need to download them manually:

- `codex-screenpet-runtime.zip`
- `codex-screenpet-runtime-manifest.json`
