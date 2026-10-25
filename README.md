# Wirecatch add-on files

Files the [Wirecatch](https://github.com/ehsan18t/wirecatch-oss-dm) media add-on downloads, kept here so a pinned release never goes away. The app checks each file against the SHA-256 it pins before using it.

Each release is one build, copied unchanged from where it was published. A weekly action (`.github/workflows/copy-ffmpeg.yml`) copies BtbN's newest FFmpeg 9.0 build when its commit changed; releases are never deleted, since each Wirecatch version pins one.

- `ffmpeg-<version>`: [BtbN's FFmpeg builds](https://github.com/BtbN/FFmpeg-Builds), the LGPL shared builds for Windows and Linux (x64). FFmpeg is licensed under the [LGPL 2.1 or later](https://ffmpeg.org/legal.html); each release links to the build it was copied from and to the source it was built from.

Wirecatch itself is licensed under GPL-3.0-only.
