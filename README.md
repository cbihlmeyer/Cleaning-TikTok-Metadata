# Cleaning-TikTok-Metadata

*Purpose:* 
To clean `.ndjson` exports from TikTok metadata collection via the Zeeschuimer Firefox extension.
  
## Features
- Extraction of post variables: engagement metrics, author handle, post time
- Extraction of supplemental text: creator description (captions) and on‑screen text
- Unified text cleaning in R (normalization, newline/quote handling, emoji isolation, URL masking)
- R pipeline to derive stable permalinks and build a clean URL CSV
- Python (Whisper) batch transcription from TikTok video permalinks

