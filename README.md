<div align="center">
  <img src="logo.png" alt="StellaVideo" width="220" />

  # StellaVideo

  A clean, minimal media player for Windows with frame-accurate seeking and variable playback speed.
</div>

---

## Features

- Audio and video playback for every format VLC supports (MP4, MKV, AVI, MOV, WebM, MP3, FLAC, M4A, OGG, and more)
- Play, Pause, and Stop controls
- Scrubber with live time display and click-to-seek
- Frame-by-frame stepping in both directions
- Volume control
- Variable playback speed from 0.5x up to 2.0x
- Keyboard shortcuts for transport
- Monochrome dark UI

## Getting Started

### Requirements

- Windows 10 or 11 (64-bit)
- [VLC media player 64-bit](https://www.videolan.org/vlc/download-windows.html) installed at the default location (`C:\Program Files\VideoLAN\VLC`)

### Run the app

1. Download `StellaVideo.exe` from the [Releases](../../releases) page.
2. Double-click `StellaVideo.exe`.
3. Click **Open** in the app to load any audio or video file.

No installation required &mdash; it is a single portable executable.

## Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `Space` | Play / Pause |
| `Left Arrow` | Step back one frame |
| `Right Arrow` | Step forward one frame |

## Troubleshooting

**The app does not start, or you see an error mentioning `libvlc.dll`**
Make sure VLC 64-bit is installed at `C:\Program Files\VideoLAN\VLC`. If you have the 32-bit version, uninstall it first and reinstall the 64-bit build &mdash; Python and VLC must share the same architecture.

**A video file will not play**
Try opening the same file in VLC directly. If VLC cannot play it either, the codec or container is unsupported by your VLC installation.

**Playback speed sounds distorted at extreme rates**
Speeds far from 1.0x (especially above 2.0x or below 0.5x) can introduce audio artifacts. This is a limitation of the underlying playback engine.

## License

See [LICENSE](LICENSE).
