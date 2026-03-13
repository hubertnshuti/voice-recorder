# Voice Recorder (Python)

A small Python project for recording microphone audio and exporting it as WAV files.

## Overview

This project records stereo audio at 44.1 kHz and saves the same recording using two common Python export methods.

It works as a clean reference for:
- short voice recording sessions
- NumPy-based audio buffering
- WAV export through multiple libraries

## Technical Notes

- Audio capture is handled with `sounddevice`.
- The recording is stored as a NumPy array for a fixed time window.
- Export option 1 uses `scipy.io.wavfile.write`.
- Export option 2 uses `wavio.write` with 16-bit sample width.

## Output Artifacts

The recorder writes two WAV files in the project root:
- `recording0.wav` (SciPy export)
- `recording1.wav` (Wavio export)

## Project Scope

The current version focuses on a straightforward recording flow and consistent export output.
Possible next improvements include configurable duration, input device selection, and timestamped file names.
