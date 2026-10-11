# Qubosis private testing downloads

This private repository contains Qubosis desktop installers for invited testers. Application source is maintained separately.

## Download

Accept your invitation and sign in to the invited GitHub account. Use the [Qubosis website](https://qubosis-app.vercel.app) to select your operating system. The current Windows files are in [preview 3](https://github.com/XTanishkX/qubosis-downloads/releases/tag/v0.1.0-preview.3); Apple silicon Mac files remain in [preview 2](https://github.com/XTanishkX/qubosis-downloads/releases/tag/v0.1.0-preview.2). Expand **Assets** on the matching release.

For the full collection, choose the suite DMG on an Apple silicon Mac or the suite EXE on Windows x64. The Mac PKG is an alternative. Each suite includes all ten tools. Open Qubosis after installation to review the draft terms, choose an application-library folder and select your tools. Individual Mac applications also have DMG and ZIP downloads; Windows applications use EXE installers. You need only one format for each application.

Installers are available for **Apple silicon Macs running macOS 13 or newer** and **Windows x64 PCs**. Choose an available installer on the website or in the release assets. Intel Mac, Windows ARM and Linux builds are not included. These are unsigned development builds, not notarized public releases. Review the release notes before testing and use disposable research data.

A GitHub 404 usually means you are signed out, using a different account or have not accepted the invitation. On Windows, close every Qubosis window before reinstalling. The scientific research folder is retained during uninstall.

## Verification and feedback

Each release has a `SHA256SUMS.txt` for its installers. On macOS, run `shasum -a 256 <downloaded-file>` and compare the result with its entry. If Gatekeeper blocks a Mac preview you trust after checking its checksum, try opening it once, then use **System Settings → Privacy & Security → Open Anyway** for that app or installer as [Apple explains](https://support.apple.com/102445). This does not disable system-wide protection; a managed Mac may require your administrator.

Report the application name, steps, operating-system version and relevant diagnostics. Remove private research and credentials from reports. Do not disable system-wide security protections to run this preview.
