# 🎙️ Advanced Whisper Transcription — Colab Tool

FoziScribe-style audio/video transcription — pause-detection, word-level timestamps, VAD-based accuracy, duplicate-word auto-fix, aur TXT/SRT/VTT/JSON export. Free, Google Colab per run hota hai.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tasawarriaz885-ux/whisper-transcription/blob/main/whisper_gradio_colab_advanced.ipynb)

## Features
- ⚡ Fast mode (distil-large-v3) & 🎯 Accurate mode (large-v3)
- 🔇 Real VAD-based silence/pause detection
- 🧹 Auto duplicate-word removal (VAD boundary + hallucination fix)
- 📊 Per-line confidence scoring
- 📁 TXT, SRT, VTT, JSON exports
- 🌍 99+ language auto-detect
- 🎚️ Flexible max-characters-per-line (10–1000)

## Kaise use karein
1. Upar wale "Open in Colab" button per click karein
2. Runtime → Change runtime type → T4 GPU select karein
3. Sab cells top se bottom run karein (Shift+Enter)
4. Public Gradio link se audio/video upload karke transcribe karein
