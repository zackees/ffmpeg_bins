FFmpeg v8.0 Static Binaries
===========================

Source: GitHub Actions workflow "download-binaries" run 21077413996
Repository: zackees/static_ffmpeg
Date: 2026-01-16

Contents:
---------

darwin.zip        - macOS Intel (x86_64)
                    Contains: darwin/ffmpeg, darwin/ffprobe

darwin_arm64.zip  - macOS Apple Silicon (ARM64)
                    Contains: darwin_arm64/ffmpeg, darwin_arm64/ffprobe

linux.zip         - Linux x86_64
                    Contains: linux/ffmpeg, linux/ffprobe

linux_arm64.zip   - Linux ARM64/aarch64
                    Contains: linux_arm64/ffmpeg, linux_arm64/ffprobe

win32.zip         - Windows x64
                    Contains: win32/ffmpeg.exe, win32/ffprobe.exe

Artifact Mapping:
-----------------
GitHub Artifact Name  ->  Final ZIP Name
linux-x64            ->  linux.zip
linux-arm64          ->  linux_arm64.zip
windows-x64          ->  win32.zip
macos-intel          ->  darwin.zip
macos-arm64          ->  darwin_arm64.zip
