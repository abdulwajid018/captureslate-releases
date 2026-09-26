# CaptureSlate Releases

Official desktop releases of **CaptureSlate**.

CaptureSlate is a privacy-first screen recording and presentation tool available on the web and, progressively, across desktop platforms.

## Official Website

https://captureslate.vercel.app

## Platform Availability

| Platform | Status |
|---|---|
| Web | Available |
| Windows x64 | Available |
| Windows ARM64 | Planned |
| macOS Apple Silicon | Planned |
| macOS Intel | Planned |
| Linux x64 | Planned |

Desktop installers and release artifacts are published through the **GitHub Releases** section of this repository.

## Official Downloads

For security, download CaptureSlate only from:

- https://captureslate.vercel.app
- The GitHub Releases section of this repository

Do not download CaptureSlate installers from unofficial mirrors or third-party websites.

## Current Release

### CaptureSlate v0.1.0

Initial public Windows desktop release.

**Platform**
- Windows 10/11
- x64

**Installer**
- `CaptureSlate-0.1.0-x64.exe`

The release includes:
- Screen recording
- Camera and microphone capture
- Window/display capture
- Presenter layouts
- Annotations and privacy tools
- Local transcription
- Enhanced transcription
- Review and playback
- Trim and rotation
- Captions and transcript export
- WebM / MP4 export
- Compression
- Native save workflow
- Imported media support

Download the latest release from the **Releases** section of this repository.

## Release Verification

Published desktop releases include SHA-256 checksums where provided.

For `v0.1.0`, verify the installer against the included:

`SHA256SUMS.txt`

SHA-256:

`6A3B58D6437540406441E4DE024FAB2375DA83F33CF40D46FE9E1C8F24512360`

## Windows Signing Status

The current Windows installer is **unsigned**.

Because CaptureSlate does not yet use an Authenticode code-signing certificate, Windows may display a SmartScreen or unknown-publisher warning during installation.

Only install CaptureSlate when downloaded from the official CaptureSlate website or this GitHub Releases repository.

## Source Code

This repository contains release information and downloadable desktop builds only.

The CaptureSlate application source code is maintained separately and is not published in this repository.

## Future Platforms

Planned future desktop targets include:

- Windows ARM64
- macOS Apple Silicon
- macOS Intel
- Linux x64

Additional platforms will be added as they become available.
