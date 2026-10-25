<p align="center">
  <img src="images/cascera-logo.png" alt="Cascera" width="96" height="96">
</p>

<h1 align="center">Cascera</h1>

<p align="center"><strong>Universal Downloader for Windows</strong></p>

<p align="center">Download, convert and organize media for your personal library.</p>

<p align="center">
  <a href="https://github.com/Arctisoft-Studio/Cascera-Universal-Downloader/releases/latest"><strong>Download</strong></a> ·
  <a href="https://arctisoft-studio.com/software/cascera/">Product website</a> ·
  <a href="https://arctisoft-studio.com/pricing/">Editions &amp; pricing</a> ·
  <a href="https://github.com/Arctisoft-Studio/Cascera-Universal-Downloader/releases">Release notes</a> ·
  <a href="https://arctisoft-studio.com/support/">Support</a>
</p>

<br>

Cascera is the media downloader and converter of Arctisoft Studio. Review a source and its available streams, choose exactly what you want, and manage the work in a recoverable queue. Profiles, naming policies, subtitles and automation let you repeat a workflow consistently, and local conversion turns files into the formats your devices need.

## Capabilities

- **Reviewed intake.** Inspect the video, audio and subtitle choices of a source before adding it. Collect playlists, channels, feeds and linked files with the Link Collector, or let the built-in Browser list the media a page loads while you use it.
- **Exact output.** Download video or extract audio, choose format and quality, preferred audio languages, subtitles, metadata, thumbnails and a trim range, with naming and existing-file policies.
- **A recoverable queue.** Inspect and edit queued jobs, clone or retry them, and see clearly which files completed, which were interrupted and which could not be delivered.
- **Local conversion.** FFmpeg-based conversion with hardware encoding where available, HDR preservation or conversion to SDR, two-pass encoding, audio normalization, and pitch, speed and creative audio processing.
- **Repeated work.** Saved download profiles, schedules, subscriptions, watch folders and intake rules that route each source to the right workflow.
- **Tools and records.** Stream and chapter reports, full decode checks, SHA-256/SHA-512/MD5 checksums, a local library, download history and statistics — copied to your account only when you choose.
- **Integration.** Open browser links in Cascera, a browser companion, Windows Send To and a command line.

Downloads use yt-dlp and conversion uses FFmpeg; Cascera installs and updates both through its Components workflow. The formats, resolutions and subtitles offered depend on the source. Cascera does not circumvent DRM or other access protection.

## Editions

Basic completes a job by hand. Premium repeats it, automates it or raises its limits. Every output format, safety and recovery feature, and local history is part of both editions.

| | Basic · free | Premium |
| --- | :---: | :---: |
| Video and audio output formats | All | All |
| Video resolution, when offered by the source | Up to 1440p | Up to 8K |
| Download queue | Up to 5 jobs | Up to 50 jobs |
| Playlists and collections | First 10 items per job | All items |
| Conversion, trimming, normalization, subtitles and SponsorBlock | ✓ | ✓ |
| Schedules, subscriptions and watch folders | Run by hand | Also run automatically |
| Saved download profiles | One | Any number |
| Intake rules and rule packages | Kept, not applied | Create, apply, import and export |
| Video codecs | H.264, single pass | All supported codecs, two-pass |
| Pitch, speed, enhancement and creative audio effects | — | ✓ |
| Account download history | 300 entries | 300 entries |

Profiles and rules saved with Premium or during a trial are kept when Premium ends; existing profiles stay usable.

Premium is a one-time purchase for one person, covering the licensed major version and all updates within it, on up to three computers at a time. A 14-day trial is available once per account and computer. See [current pricing](https://arctisoft-studio.com/pricing/); **Help > License** shows the state of this computer.

## System requirements

| | |
| --- | --- |
| Operating system | Windows 10 or Windows 11, 64-bit (x64) |
| Runtime | Included with the installer |
| Installation | For your Windows user account; administrator rights are not required |
| Components | yt-dlp and FFmpeg, installed and updated by Cascera |
| Hardware encoding | Optional; used when a supported GPU encoder is available |
| Internet | For downloads, component updates, sign-in, licensing and updates; conversion works offline |

## Installation and updates

1. Download `v<version>-cascera.exe` from the [latest release](https://github.com/Arctisoft-Studio/Cascera-Universal-Downloader/releases/latest).
2. Run the installer and accept the license agreement. Setup can also install [Arctisoft Studio Hub](https://github.com/Arctisoft-Studio/Arctisoft-Studio-Hub).
3. Start Cascera and let it install its components. Sign in through Studio Hub when you want Premium, the trial or account history.

Cascera checks this repository for updates and installs a new version only after verifying it against the SHA-256 checksum GitHub publishes for the release. Studio Hub can install and update the whole Arctisoft collection from one place.

## Accounts and privacy

Manual downloads and conversion do not require an account. Requests go only to the sources you choose and to the component and update services. Local history stays separate from account history; copying it to your account is an explicit action. Browser bookmarks, cookies and sessions stay on your computer and can be cleared in **Settings > Privacy**. The [Privacy Policy](https://arctisoft-studio.com/legal/privacy/) describes the connected services and account data involved.

## Responsible use

Cascera is licensed for **personal, non-commercial use** in both editions. Download only material you are entitled to use, in accordance with the source's terms and applicable law. The availability of a download does not grant rights to its content.

## Support

Open the user guide from **Help**, visit [Arctisoft Support](https://arctisoft-studio.com/support/) or write to [support@arctisoft-studio.com](mailto:support@arctisoft-studio.com). Report reproducible problems and suggest improvements through [GitHub Issues](https://github.com/Arctisoft-Studio/Cascera-Universal-Downloader/issues). Please keep license keys, account details, cookies and private source links out of public reports.

## License

Cascera is proprietary software. This repository holds its public documentation and official releases; the source code is not published. Use is governed by the [Cascera EULA](LICENSE), the [Arctisoft Studio License Agreement](https://arctisoft-studio.com/legal/license/) and the [Terms of Service](https://arctisoft-studio.com/legal/terms/). yt-dlp, FFmpeg and the other open-source components keep their own licenses and are listed in the third-party notices installed with Cascera.

---

<p align="center"><sub>© 2025–2026 Arctisoft Studio. All rights reserved.</sub></p>
