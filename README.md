# ScoTech SMS — website and downloads

Public landing page (GitHub Pages, `sms.scotech.co.ke`) and installer downloads (GitHub Releases) for the offline ScoTech SMS.
The source code lives in the private `scotech-sms` repository.

## Publish a new version
1. In the private repo run `installer\build-installer.ps1`; it makes `installer\output\ScoTechSMS-Setup-<version>.exe`.
2. Here: **Releases → Draft a new release**, tag `v<version>`, attach the `.exe`, **Publish**.
3. The page picks it up automatically (the file name must contain `Setup` and end in `.exe`). GitHub shows the SHA-256 and the page prints it.

Before JavaScript runs (or if GitHub is unreachable) the Download buttons open the Releases page.
