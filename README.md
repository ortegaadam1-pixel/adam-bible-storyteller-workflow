# Adam Ortega Bible Storyteller

One reusable workflow for Bible explainer videos using **Talking Photos, CloneVoice, and VideoExpress**, with precise local editing when needed.

## The one master

[SYSTEM_PROMPT.md](SYSTEM_PROMPT.md) is the single authoritative workflow. It contains the voice, biblical standards, app sequence, presenter limits, visual rules, recovery steps, and quality checks. Other briefs and examples do not override it.

## Use it again

Give a browser-capable agent this request, changing the topic and length:

```text
Read the latest SYSTEM_PROMPT.md from
https://github.com/ortegaadam1-pixel/adam-bible-storyteller-workflow
and follow it to produce my next Bible explainer.

Topic or passage: [your topic]
Length: [your requested length]
Format: 16:9

Reuse my approved Talking Photos presenter and my saved CloneVoice
voice, Adam Ortega Clone to use. Use VideoExpress for supporting
footage and assembly. Include meaningful supporting visuals throughout.
Save, finish, and deliver the video for review. Do not publish.
```

For a test, request a 45–55-second pilot strictly below 60 seconds. For a longer film, the master divides presenter generations at natural sentence boundaries within each clip's actual limit.

## What stays consistent

- Caring neighbor voice, humility, expressive storytelling, complete natural sentences, and Jesus-centered hope.
- NKJV by default; real personal testimony only.
- Approved actual likeness and saved voice, with no generic substitute or idealized teeth.
- Generate a matching thumbnail, show it for the first 0.25 seconds, then begin the film and narration. Deliver the thumbnail separately too.
- Never just a full-screen talking head: supporting footage or meaningful graphics throughout.
- One measured narration timeline, no duplicate speech, and no speed-up to hide a timing problem.
- Actual exported-media review and honest reporting of anything unverified.

## What the repository does

It gives the agent one repeatable operating procedure. It is **not an executable application or unattended GitHub Actions automation**. The agent needs authorized access to the apps and editing tools.

Existing API settings are reused. Native integrations are used when verified. Download/upload is the tested Talking Photos-to-VideoExpress fallback; direct transfer between those two has not been verified here. If browser transfer fails, the agent prepares one specific manual handoff and resumes afterward.

Local finishing does not automatically update a VideoExpress timeline. The agent identifies the authoritative final file and preserves the editable source, rather than claiming automatic synchronization.

## Examples

[TEST_VIDEO_BRIEF.md](TEST_VIDEO_BRIEF.md) and [PETER_PILOT.md](PETER_PILOT.md) are generic examples only. Production status, private asset references, and credentials belong outside this public repository.

Adapted from [ai-playbooks/historical-documentary-video-workflow](https://github.com/ai-playbooks/historical-documentary-video-workflow).
