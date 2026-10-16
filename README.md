# Adam Ortega Bible Storyteller

A browser-agent workflow for warm, expressive Bible explainer videos with Adam as the spokesperson. It combines his on-camera presence and continuing narration with biblical reenactments, explanatory motion graphics, and readable emphasis text.

This repository contains instructions, not an executable video application or GitHub Actions automation. Generation requires an agent with access to the relevant apps and supported editing capabilities.

## Start

Ask the agent to read [SYSTEM_PROMPT.md](SYSTEM_PROMPT.md), then give a passage or biblical question. Default: approximately three minutes, 16:9, cinematic realistic reenactments. The ordinary planning limit is five minutes unless changed.

Provide an approved presenter reference and an existing authorized Adam voice recording or clone before likeness or voice production. No substitute presenter or narrator is chosen automatically. Scripts and scene planning can proceed while an asset is missing.

## Story and voice

Friendly, humble, caring neighbor; plain language and complete flowing sentences; vivid adjectives, sensory detail, and strong verbs; real personal experiences only; Scripture in context; NKJV by default; Jesus-centered hope. The full voice specification is embedded so the workflow remains usable if a separate Adam voice skill is unavailable.

There is no compulsory 20-second introduction. Presenter appearances follow the story. Motion graphics and overlays must be implemented through supported tools and verified, not merely listed in prompts.

## First test

Use [TEST_VIDEO_BRIEF.md](TEST_VIDEO_BRIEF.md) as a suggested pilot brief. It is not a claim that a video has been generated. Choose the passage and confirm the presenter and voice assets before affected media generation.

Example launch request:

```text
Read SYSTEM_PROMPT.md and run a 60-second pilot Bible explainer.
Topic: Peter's restoration in John 21:15-19, with his denial as background.
Central question: Can Jesus still use me after I have failed Him?
Ratio: Landscape 16:9.
Use my approved presenter reference and existing authorized voice.
Include biblical footage, one simple motion graphic, brief emphasis text,
and a closing return to me. Save and export; do not publish.
If an essential asset is missing, write the script and plan first,
then ask only for the missing asset.
```

## Production tools

- Talking Photos: Adam's speaking presenter clips using his approved image.
- CloneVoice: Adam's approved voice, including the observed CloneVoice.ai integration inside Talking Photos.
- VideoExpress: biblical background footage and supported final assembly.

The Talking Photos Human Video interface was inspected on October 16, 2026. Its high-quality v3.5 modes displayed a one-minute limit per clip. Photo, audio, and voice controls were inspected; rendering and transfer have not yet been tested end to end. The full instructions distinguish verified controls from untested steps.

## Requirements and limits

- Talking Photos, VideoExpress, and CloneVoice access with appropriate generation availability.
- A browser-capable agent following its host's authentication and tool rules.
- Approved Adam likeness and audio assets.
- Supported lip-sync, overlays, and graphics tools, or an authorized compatible editor.
- Actual UI capabilities must be checked. The original workflow does not establish that every requested effect is available.

The workflow reviews script and assembled playback where available, reuses completed assets, follows actual audio timing, saves, and exports. It does not publish, share publicly, or download the final video unless requested.

## Origin

Adapted from [ai-playbooks/historical-documentary-video-workflow](https://github.com/ai-playbooks/historical-documentary-video-workflow). Replaces the fictional presenter, watercolor construction documentary format, fixed introduction length, and playback prohibition with Adam's Bible storytelling requirements. No software license grant is asserted by this adaptation.
