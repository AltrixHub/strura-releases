# Strura releases

Download builds of **Strura**, the parametric BIM application — https://strura.app

This repository holds release binaries only; the source code lives in a private repository.

## Download

Latest build: https://github.com/AltrixHub/strura-releases/releases/latest

| Platform | File |
|---|---|
| macOS (Apple Silicon) | `Strura.dmg` |
| Windows (x64) | `Strura-windows-x64.zip` |

## Opening an unsigned build on macOS

Early builds are not code-signed or notarized, so macOS Gatekeeper blocks the first launch.
Either right-click `Strura.app` and choose **Open**, then confirm — or clear the quarantine flag:

```
xattr -d com.apple.quarantine /Applications/Strura.app
```

## Opening an unsigned build on Windows

Unzip the archive and run `Strura.exe`. The build is unsigned, so SmartScreen shows
"Windows protected your PC" the first time — choose **More info**, then **Run anyway**.

## Feedback

Issues and feature requests: https://github.com/AltrixHub/strura-releases/issues
