{
  "id": "com.ultramax.qobuz",
  "name": "Ultra Qobuz",
  "version": "1.0.0",
  "description": "Qobuz discovery and direct lossless playback for Eclipse Music.",
  "resources": ["search", "stream", "catalog"],
  "types": ["track", "album", "artist", "playlist"],
  "contentType": "music",
  "settings": [
    {
      "key": "quality",
      "type": "selector",
      "label": "Audio Quality",
      "options": [
        { "label": "MP3 320kbps", "value": "MP3" },
        { "label": "CD - FLAC 16-bit/44.1kHz", "value": "CD" },
        { "label": "Hi-Res - up to 24-bit/96kHz", "value": "HIRES_96" },
        { "label": "Hi-Res Max", "value": "HIRES" }
      ],
      "defaultValue": "HIRES"
    }
  ]
}
