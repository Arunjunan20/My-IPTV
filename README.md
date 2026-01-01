# Pocket TV

A curated IPTV playlist focused on Tamil channels — including local Tamil channels, Tamil channels for overseas viewers, and a selection of English movie channels. This repository provides an M3U playlist (and EPG mapping via Tata Play) intended for personal use with common IPTV players.

Quick highlights
- Curated list of Tamil TV channels (local & overseas)
- Selected English movie channels
- EPG data mapped using Tata Play (XMLTV)
- Works with popular IPTV players: Tivimate, OTT Navigator, NS Player, VLC, and others
- Tamil radio stations work in progress

---

## Table of Contents
- [Requirements](#requirements)
- [Usage](#usage)
- [EPG (Program Guide)](#epg-program-guide)
- [Players tested](#players-tested)
- [Updating the playlist](#updating-the-playlist)
- [Contributing](#contributing)
- [Disclaimer & Legal](#disclaimer--legal)
- [Contact / Issues](#contact--issues)
- [License](#license)

---

## Requirements
- An IPTV-capable player that supports M3U playlists and optional XMLTV (EPG).
- A stable internet connection for streaming.
- If your player requires a remote URL, host the M3U file or use the raw URL from this repository.

---

## Usage

1. Choose an IPTV player (examples below).
2. Add the playlist:
     Remote URL: add the URL for the M3U file
     `https://tinyurl.com/Pocket-TV`  
3. (Optional) Add EPG (XMLTV) URL to get program guide data for channels. See the EPG section below for details.
4. Start streaming. If a stream fails, try another source or check for geo-restrictions.

---

## EPG (Program Guide)
- This repository uses Tata Play EPG mapping for program guide data.
- Many IPTV players accept an XMLTV URL. If you have an XMLTV file or URL for Tata Play, add it in your player's EPG settings.
- Example placeholder (replace with a real XMLTV URL if available):
  - `https://epghub.xyz/epg/EPG-IN.xml.gz`
- Note: EPG availability and accuracy depend on the provider and the XMLTV source used.

---

## Players tested
- Tivimate
- OTT Navigator
- NS Player
- Sparkle TV
- AuthoIPTV
- VLC (for simple playback)
Other players that support M3U and XMLTV should work similarly.

---

## Updating the playlist
- Playlist files (M3U) can be updated by editing the playlist file(s) in this repository and creating a pull request.
- If you maintain a hosted M3U, ensure URLs remain reachable and update/remove broken entries periodically.
- When updating EPG mappings, ensure the channel IDs/names match the XMLTV tags used by Tata Play.

---

## Contributing
Contributions are welcome — whether it's adding channels, fixing metadata, or improving documentation.

Guidelines:
- Open an issue to propose new channels or report broken streams.
- For PRs:
  - Update the playlist file (M3U) with new entries.
  - Keep entries clearly commented and grouped (e.g., Local Tamil, Overseas Tamil, English Movies).
  - Provide source/notes for added stream URLs where possible.
- For radio station additions: create a separate section in the playlist (e.g., `#RADIO` or `#EXTINF` entries labeled Radio).

Example M3U entry:
#EXTINF:-1 tvg-id="channel_id" tvg-name="Channel Name" tvg-logo="https://example.com/logo.png" group-title="Tamil",Channel Name
http://example.com/stream_url.m3u8

---

## Disclaimer & Legal
- This repository provides a curated list of streaming URLs. Many streams may be subject to copyright, geo-restrictions, or require subscriptions.
- The repository owner is not affiliated with channel owners or Tata Play. Use streams responsibly and ensure you have the right to view the content in your jurisdiction.
- Streams may stop working without notice. The repository does not host stream content — it only lists URLs and metadata.
- Do not use this repository for commercial redistribution of copyrighted content.

---

## Contact / Issues
- Found a broken stream or wrong EPG mapping? Open an issue in this repository with details (channel name, stream URL, and error).
- Want to contribute? Fork the repo, make changes, and open a pull request.
- Contact on Telegram 'https://t.me/Pocket_TV_Tamil'

---

## Credits
- EPG: Tata Play (used for program guide mapping)
- Contributors: Thanks to everyone who reports issues and contributes improvements.

---

## License
No license specified. If you want this project to be reusable under a recognized open-source license, add a LICENSE file (e.g., MIT, Apache-2.0) to the repository.

---
Happy streaming — and thanks for using Pocket TV!
