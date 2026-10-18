# Smriti: one memory for all your AIs

Tell one AI, and every AI knows. Smriti gives ChatGPT, Claude, Gemini and your other AIs one shared memory that
lives on your own Windows PC.

**[Download the latest version for Windows](https://github.com/vinaytiwaribuilds/smriti/releases/latest)**: run `SmritiSetup-<version>.exe`.

- **Private by design.** Your memory is saved only on your PC. Web and phone AIs reach it through Smriti Relay,
  which passes questions and answers along without keeping them. No account, no tracking.
- **Works with the AIs you use.** ChatGPT and Claude (web and phone apps, through a connector), Gemini, Kimi and other
  AI websites (through the Chrome extension), and Claude Desktop, Claude Code and Codex on your PC.
- **You stay in control.** Open Smriti to see, correct or delete anything it remembers. "Disconnect all AIs" cuts
  every connection at once.

## Install

1. Download `SmritiSetup-<version>.exe` from the [latest release](https://github.com/vinaytiwaribuilds/smriti/releases/latest).
2. Run it. Windows may show "Windows protected your PC" because the installer is new and not yet code-signed
   (the publisher shows as unknown): click **More info**, then **Run anyway**. To be sure the file is genuine,
   compare its SHA-256 checksum with the one in the release notes (`Get-FileHash .\SmritiSetup-<version>.exe` in PowerShell).
3. Smriti opens when it is ready and starts by itself each time you sign in to Windows.

Requirements: Windows 10 or 11 (64-bit), about 400 MB of disk space. No account needed.

## Help, privacy and terms

- Setup guide and troubleshooting: https://smriti-relay.smriti-relay.workers.dev/help
- Privacy policy: https://smriti-relay.smriti-relay.workers.dev/privacy
- Terms of use: https://smriti-relay.smriti-relay.workers.dev/terms
- Contact: vinaytiwari.builds@gmail.com

This repository hosts the Windows installer releases only.
