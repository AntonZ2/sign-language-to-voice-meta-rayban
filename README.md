# Sign Language to Speech + Gen AI in Meta Ray-Bans

## Winning submission to UCL x ICL Hack by Entrepreneur First

## Demo

_Note that we had to record to screen using a phone as we couldn't screen record while using OBS to Open_CV_

## How

- Make Facebook account and stream Ray-Bans video to Facebook live.
- Use OBS virtual display to stream video to Open_CV.
- Use voice recognition to activate various features (sign-language, room description).
  - Use OpenAI-4o for describing surroundings.
  - Use Google MediaPipe to track hand positions.
  - Use ML-model trained by us to recognize letters.
  - Compile letters to make words + sentences
  - Use OpenAI to correct spelling/grammar.
  - Use OpenAI text to speech to return speech.

## Run

1. Stream Meta-Ray-Ban video feed to facebook live.
2. Use OBS to stream facebook stream to Open_CV
   - `python context_audio.py`
