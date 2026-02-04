# Claude Code Therapist

This repo is a Claude Code Diamond Approach teacher/therapist environment.

## First-time setup

- Start up `claude` and ask it to fill in `me.md` with a detailed summary of who you are, for its use during future sessions. Then use dictation to share 2 minutes' worth of life-summary details. Claude will fill in `me.md` with an organized summary. Ideas for what to share:
  - Name, age, where you live
  - Your passions, your dislikes, things that drive you crazy
  - Family situation, relationship history
  - Interests, pastimes, lifestyle, community
  - Beliefs, spirituality, values

## Usage

- Start a `claude` session.
- Type `/therapist` to wake up your therapist. Claude will load up its context, then ask how you're doing.
- Pour your heart out. Speak your truth with curiosity and vulnerability. **Trust yourself.** I recommend using https://handy.computer/ so you can stream-of-consciousness at the speed of thought. Claude will hear you, mirror and reflect, and offer questions and suggestions to invite you to explore and process your inner world more deeply.
- Tell Claude when you'd like to wrap up the session. It will save a summary of the session so future-claude remembers all the important details.
- When you're done, MANUALLY copy the full claude session output to `session_transcripts/YYYY-mm-dd-{topics}.md` so you have a full record of the conversation for future reference.

## Ideas for improvement

- Include various parts of my journals, have Claude churn through them & summarize & identify and reflect on trends
- Vibecode a thin wrapper UI (Node / electron app?) so I can do text chat with Claude, and its responses are Claude Code output but in a cleaned-up friendly font & styling
- Vibecode a proof-of-concept nodejs app that supports speech-to-speech convo in near realtime, with visible transcripts animating in?
