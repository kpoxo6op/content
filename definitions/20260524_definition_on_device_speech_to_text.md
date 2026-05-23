---
title: 'On-device speech-to-text'
description:
  'On-device speech-to-text converts recorded or live audio into text on the
  same machine that holds the audio, reducing network exposure and making
  transcription workflows easier to test in isolated development environments.'
---

# On-device speech-to-text

## Definition

On-device speech-to-text is a transcription approach where the speech
recognition engine runs locally on the machine that stores the audio. Instead
of uploading recordings to a hosted transcription API, the workflow loads a
local model or SDK, processes the file in place, and writes the transcript back
to local storage.

This pattern is useful for private recordings, regulated data, offline demos,
and reproducible development environments. It still may require a license key,
model file, or vendor SDK, but the audio payload itself does not need to leave
the workspace during transcription.
