# Qubosis private testing downloads

This private repository contains Qubosis desktop installers for invited testers. Application source is maintained separately.

## Download

Accept your invitation and sign in to the invited GitHub account. Open [Releases](https://github.com/XTanishkX/qubosis-downloads/releases), choose the testing preview, and expand **Assets**.

For the full collection, download `Qubosis-atom-0.1.0-mac-arm64.pkg`. It includes all ten tools. Open Atom after installation to review the draft terms, choose an application-library folder and select your tools. Individual applications also have DMG and ZIP downloads. You need only one format for each application.

Current installers target **Apple silicon Macs running macOS 13 or newer**. Windows, Intel Mac and Linux downloads are not included. These are unsigned development builds, not notarized public releases. Review the release notes before testing and use disposable research data.

The [Qubosis website](https://qubosis-app.vercel.app) provides the product catalog and download links. A GitHub 404 usually means you are signed out, using a different account or have not accepted the invitation.

## Verification and feedback

`SHA256SUMS.txt` lists checksums for the installers. On macOS, run `shasum -a 256 <downloaded-file>` and compare the result with its entry.

Report the application name, steps, macOS version and relevant diagnostics. Remove private research and credentials from reports. Do not disable system-wide security protections to run this preview.
