# PlexCleaner-AV1
AV1 Encode your entire plex/emby library it will save you disk space! 

This will check to see if media is already AV1 encoded if it is it will skip that file so you don't have to worry about loss of quality / editing already AV1 encoded media files.

# Usage

Run `AV1_LargestFileFirst.cmd` and enjoy It will start with the largest video files in your library want to claim back that disk space as fast as we can after all :)


# How to change settings

Edit `plexcleaner.json` this line specificly https://github.com/C0nw0nk/PlexCleaner-AV1/blob/main/win-x64/PlexCleaner.json#L141

For example you will see by default `"Video": "svt_av1_10bit` i use NVIDIA GPU for AV1 encoding you can change it to AMD VAAPI CPU what ever you prefer.

Here is the list of options

## CPU Encoding

```
svt_av1
svt_av1_10bit
```

## Nvidia GPU Encoding

```
nvenc_av1
nvenc_av1_10bit
```

## AMD GPU Encoding

```
vce_av1
vce_av1_10bit
```
