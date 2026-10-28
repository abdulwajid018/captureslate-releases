# CaptureSlate Releases

Official desktop releases of **CaptureSlate**.

CaptureSlate is a privacy-first screen recording and presentation tool available on the web, Windows, and Apple Silicon Macs.

## Official Website

https://captureslate.vercel.app

## Platform Availability

| Platform | Status |
|---|---|
| Web | Available |
| Windows x64 | Available |
| Windows ARM64 | Available |
| macOS Apple Silicon | Available |

Desktop installers, checksums, and release artifacts are published through the **GitHub Releases** section of this repository.

## Official Downloads

For security, download CaptureSlate only from:

- https://captureslate.vercel.app
- https://github.com/abdulwajid018/captureslate-releases/releases

Do not download CaptureSlate installers from unofficial mirrors or third-party websites.

---

## Latest Release

### CaptureSlate v0.2.0

CaptureSlate v0.2.0 expands desktop availability and includes updated capture, packaging, reliability, and background-processing improvements.

**Release details**

https://github.com/abdulwajid018/captureslate-releases/releases/tag/v0.2.0

### Available Desktop Builds

#### Windows x64

For most Intel/AMD Windows 10/11 PCs.

Installer:

`CaptureSlate-0.2.0-Windows-x64.exe`

#### Windows ARM64

For Windows on ARM devices.

Installer:

`CaptureSlate-0.2.0-Windows-arm64.exe`

#### macOS Apple Silicon

For M1 and newer Macs.

Installer:

`CaptureSlate-0.2.0-macOS-arm64.dmg`

### Highlights

- Windows ARM64 desktop support
- macOS Apple Silicon desktop support
- Updated Windows x64 desktop build
- Improved background-segmentation stability and edge handling
- Improved desktop capture and release reliability
- Automated architecture and package verification
- SHA-256 checksums for published desktop artifacts

### Installation Notes

#### Windows

The current Windows installers are unsigned.

Windows may display a Microsoft Defender SmartScreen or unknown-publisher warning. If you downloaded CaptureSlate from the official website or this repository and trust the file, Windows may provide **More info → Run anyway** depending on the system configuration.

#### macOS

The macOS build is ad-hoc signed but is not Apple notarized.

On first launch, macOS may prevent CaptureSlate from opening because Apple cannot verify the developer.

If this happens:

1. Open **System Settings → Privacy & Security**.
2. Find the message indicating that CaptureSlate was blocked.
3. Click **Open Anyway**.
4. Confirm **Open**.

No Terminal command is required.

### Checksums

The v0.2.0 SHA-256 checksums are published with the release:

https://github.com/abdulwajid018/captureslate-releases/releases/download/v0.2.0/SHA256SUMS.txt

---

## Previous Releases

### CaptureSlate v0.1.0

Initial public Windows desktop release.

**Release details**

https://github.com/abdulwajid018/captureslate-releases/releases/tag/v0.1.0

**Platform**

- Windows 10/11
- x64

**Installer**

`CaptureSlate-0.1.0-x64.exe`

The v0.1.0 release introduced the first public CaptureSlate desktop build with capabilities including:

- Screen recording
- Camera and microphone capture
- Window/display capture
- Presenter layouts
- Annotations and privacy tools
- Local and enhanced transcription
- Review and playback
- Trim and rotation
- Captions and transcript export
- WebM / MP4 export
- Compression
- Native save workflow
- Imported media support

### v0.1.0 Verification

SHA-256:

`6A3B58D6437540406441E4DE024FAB2375DA83F33CF40D46FE9E1C8F24512360`

---

## Release Verification

Published desktop releases include SHA-256 checksums where provided.

Always verify downloads against the checksum file attached to the corresponding GitHub Release when integrity verification is required.

## Known Limitations

Current known limitations and platform-specific guidance are maintained on the CaptureSlate website and in the release notes for each version.

For the latest usage and installation guidance, visit:

https://captureslate.vercel.app

## Source Code

This repository contains release information and downloadable desktop builds only.

The CaptureSlate application source code is maintained separately and is not published in this repository.
