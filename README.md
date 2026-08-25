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

Early builds are not code-signed or notarized, so macOS blocks the first launch
with "Apple could not verify …". Close that dialog, then:

1. Open **System Settings → Privacy & Security** and scroll down.
2. Next to the notice that `Strura.app` was blocked, choose **Open Anyway** and confirm.

After that one approval it opens normally. Alternatively, clear the quarantine
flag from a terminal:

```
xattr -d com.apple.quarantine /Applications/Strura.app
```

## Opening an unsigned build on Windows

Unzip the archive and run `Strura.exe`. The build is unsigned, so SmartScreen shows
"Windows protected your PC" the first time — choose **More info**, then **Run anyway**.

## Feedback

Issues and feature requests: https://github.com/AltrixHub/strura-releases/issues
