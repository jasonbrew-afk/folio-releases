# folio

**Your work. In motion.**

folio is a native macOS app to save and present your work.

This repository holds **released builds only**. folio's source code is not published here.

## Install

1. Open [the latest release](https://github.com/jasonbrew-afk/folio-releases/releases/latest).
2. Download `Fero-fero-r<number>.zip` (the file name keeps folio's original build name).
3. Open the ZIP and drag **folio.app** into your Applications folder, then open it.

folio needs macOS 13 or later.

To check the download, compare its SHA-256 with the `.sha256` file beside it:

```bash
shasum -a 256 -c Fero-fero-r<number>.zip.sha256
```

## Signed and notarized

Every build here is signed with an Apple Developer ID, built with the hardened runtime, notarized
by Apple and stapled, so macOS opens it without any security override. If macOS ever says folio
can't be checked or is damaged, don't bypass it: delete the copy and download it again from this page.

## Updates

folio checks this page for newer builds and offers them in the app (folio ▸ Check for Updates…).
No GitHub account or token is needed.
