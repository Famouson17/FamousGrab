# FamousGrab

FamousGrab is a Windows desktop downloader for saving videos, audio, playlists, and image posts from supported social and media websites.

## What the app does

- Downloads videos from supported sites such as YouTube, TikTok, Instagram, Facebook, X/Twitter, Reddit, Vimeo, and other compatible URLs.
- Downloads Instagram single-image posts and carousel/multi-image posts.
- Downloads playlists or batches where supported.
- Converts media between common video, audio, and image formats.
- Saves files locally to your Documents/FamousGrab folder.

## Download

Use the installer:

```text
FamousGrab_Setup.exe
```


## File verification

You can verify the downloaded files by comparing their hashes.

### SHA-256

```text
FamousGrab_Setup.exe
9B01D57592C5CFC989ECD2995B41FCEAFCD25B47E58B0CF1C54190DD39F48445

dist/FamousGrab.exe
E9AE653306F86E0B432F8310EACFCA75DC1D8E55D462F6624C66D97FCD29A1B0
```

### MD5

```text
FamousGrab_Setup.exe
133B23E4B947E0563DF7E60D88E985EE


On Windows, you can verify SHA-256 with PowerShell:

```powershell
Get-FileHash -Algorithm SHA256 .\FamousGrab_Setup.exe
```

## Windows SmartScreen

Windows may show a SmartScreen warning for new or unsigned apps, even when the file is safe. This happens because the executable has not yet built reputation with Microsoft.

To reduce or remove these warnings in the future, the `.exe` should be signed with a trusted code signing certificate.

## Notes

- Some websites require you to be logged in before media can be accessed.
- Instagram links may depend on public availability and active CDN links.
- FamousGrab is intended for downloading content you own, have permission to use, or are legally allowed to save.

