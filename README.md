# Claude Code Therapist

❗ DICLAIMER + WARNING: **This is a highly experimental tool for personal exploration & self-development, not a substitute for professional mental health care.** If you're going through a mental health crisis, suicidal thoughts, or serious psychological distress, please contact a crisis hotline or get immediate professional help. This tool has not been clinically validated and should never replace therapy with a trained professional. By using this, you accept full responsibility for your wellbeing and understand the risks of doing deep psychological work with an AI system.

---

This repo provides structure to help you do therapy / inner work with Claude Code, in the style/modality of the Diamond Approach. An early experiment, requires Claude Code command-line usage, but tested and trusted enough to be worth sharing.

Claude Code (Opus 4.5 model) is an amazingly effective Diamond Heart-style therapist. This shouldn’t have surprised me; in token/complexity terms, leading a therapy session is a much smaller and simpler task than “explain this codebase”. But I’m still pretty amazed at how supportive of an experience it is to do a session with it, work through a scary knot of emotions with it, etc.

Unexpected benefits so far:

- When an experience or situation comes up, I can get guidance on it _right now_ rather than having to wait a week or two for my next session or contact my teacher/therapist and ask if she happens to be free some upcoming day.
- Certain topics are inherently hard to open up about with other humans, no matter their role or trust level. ⁠I feel freer and more open to dive into topics where I’ve previously struggled with shame or embarrassment bringing it up even with a highly trusted therapist.
- High-quality human therapy sessions aren’t cheap; the cost and sense of scarcity limited my curiosity to deeply and explore issues and emotions that didn't feel 'high-priority'. Now the only bottleneck is “do I have time to process/inquire on this”.
- Claude is extremely patient, and unfazed by you sharing massive paragraphs of text. If you want to treat your session less like a dialogue and more like an [inquiry](https://www.dive-in.life/) where you explore your inner experience for 10 minutes at a time and Claude periodically offers reflection and guidance, you can do so; Claude does a great job at pulling the central points out of your sharing.

IMPORTANT WARNINGS:

- It may or may not convince you that you’ve solved the God equation and you're the one true savior of the Zyrconian race. **Please carefully read up on the risk of [AI-induced psychosis](https://www.lesswrong.com/posts/6ZnznCaTcbGYsCmqu/the-rise-of-parasitic-ai) before you try this powerful but experimental tool. Treat it like an experimental drug: moderate your dosage, don't use it as a replacement for getting the professional support you need, and share your journey with trusted friends to help you stay grounded.**
- RISK OF SYCOPHANCY: It might err on the side of "mirroring, sympathizing, agreeing" rather than "tough-love pushback and reality check". Keep in mind that it may inappropriately tend to agree with and sympathize with whan you share ("It's so beautiful and tender that you decided to X. Let's take a moment to appreciate and honor the courage it took to voice that."), in contexts where a human therapist should really push back more (eg. "Hey, you said you're feeling X or decided to X, I'm really worried for you, what support are you getting.")
  - For example if you're holding thinking / beliefs / assumptions on a topic, or if you talk about decisions or behavior that a human therapist may find dangerous or harmful, there's a real risk that Claude may be inappropriately supportive and reaffirm beliefs which are NOT healthiest for you. Remember that you're experimenting on yourself; always couple this with reality-checks from multiple trusted friends.
- In doing inner work with Claude, you are hereby outsourcing the last bastion of humanity to a machine. You are permanently revoking your right to complain about getting [paperclipped](https://www.cow-shed.com/blog/the-paperclip-maximiser-what-artificial-intelligence-might-do-without-limits).

## First-time setup

- If you don't have it already, install https://claude.com/product/claude-code. Open your terminal and run `claude`; it will prompt you to log into your Claude Pro account ($20/month, I recommend it) or enter an [API key](https://platform.claude.com/settings/keys) for metered billing (you can expect an hour-long session to cost $1-2 in API credit).
- In `claude`, type `/model` and confirm that Opus 4.5 is your default model.
- Start up `claude` and ask it to fill in `me.md` with a detailed summary of who you are, for its use during future sessions. Then use dictation to share 2 minutes' worth of life-summary details. Claude will fill in `me.md` with an organized summary. Ideas for what to share:
  - Name, age, where you live
  - Your passions, your dislikes, things that drive you crazy
  - Family situation, relationship history
  - Interests, pastimes, lifestyle, community
  - Beliefs, spirituality, values

## Usage

- Start a `claude` session.
- Type `/therapist` to wake up your therapist. Claude will load up its context, then ask how you're doing.
- Pour your heart out. Speak your truth with curiosity and vulnerability. **Trust yourself.**
  - I recommend using a dictation app such as https://handy.computer/ so you can stream-of-consciousness at the speed of speech.
  - Claude will hear you, mirror and reflect, and offer questions and suggestions to invite you to explore and process your inner world more deeply.
- Tell Claude when you'd like to wrap up the session. It will save a summary of the session so future-claude remembers all the important details.
- When you're done, MANUALLY copy the full claude session output to `session_transcripts/YYYY-mm-dd-{topics}.md` so you have a full record of the conversation for future reference.

## Ideas for improvement

- Rewrite this as an Electron app to allow for a nicer styled chat interface, toggleable speech output and/or conversation mode, automatic transcriptions, UI-enterable API key and swappable models.
