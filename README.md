# Voice Recorder in Python

A minimal Python voice recorder using `sounddevice`.

## Install

```bash
pip install -r requirements.txt
```

## Run

```bash
python voice_recorder.py
```

This records 5 seconds of stereo audio at 44100 Hz and saves:
- `recording0.wav` (via scipy)
- `recording1.wav` (via wavio)
