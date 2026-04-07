# NEXTGENX — Demo Video Script
## Proxa Echo Hackathon 2026 | 3–5 Minutes

---

## PRE-RECORDING CHECKLIST
- [ ] Open `nextgenx-complete.html` in Chrome (NOT Edge, NOT Firefox)
- [ ] Paste your Anthropic API key and click Connect
- [ ] Select Dr. Priya Mehta (Cardiologist) persona
- [ ] Set screen resolution to 1920x1080
- [ ] Use OBS / Loom / Screencastify for recording
- [ ] Have a mic ready — you will speak live
- [ ] Close all other browser tabs

---

## SEGMENT 1 — Hook (0:00 – 0:30)

**[Screen: Show the complete NEXTGENX interface]**

SAY:
> "Pharma sales reps need to practice difficult conversations with doctors
> before they walk into a clinic. Existing avatar platforms cost thousands
> per month, lock you into closed APIs, and were designed for one-way
> video — not real conversation. NEXTGENX changes that."

**[Action: Click "Demo speak" button — let Dr. Priya Mehta animate]**

SAY:
> "This is Dr. Priya Mehta — a fully animated, AI-powered HCP avatar
> running entirely in the browser. No plugins, no installation, no
> vendor lock-in."

---

## SEGMENT 2 — Architecture (0:30 – 1:00)

**[Screen: Zoom into the pipeline status bar at the top]**

SAY:
> "Our pipeline has five stages. Voice capture — Claude API streaming —
> TTS synthesis — Avatar animation — Emotion detection. Each stage
> fires in under 100 milliseconds combined."

**[Action: Point at each pipeline dot as you name it]**

SAY:
> "The key innovation is our Lookahead Viseme Buffer. While the avatar
> is speaking sentence one, we're already extracting mouth shapes for
> sentence two. This gives us sub-100ms lip sync — three times better
> than the 300ms requirement."

---

## SEGMENT 3 — Live Demo (1:00 – 3:30)

**[Screen: Full interface visible, avatar center stage]**

**[Action: Type or say this into the input bar:]**
> "Good morning Dr. Mehta. I'm here to discuss our new cardioprotective
> agent — CARDIVEX. Are you familiar with the recent PROTECT-III trial?"

**[Let Dr. Mehta respond — watch the:]**
- Mouth animate in sync with the voice
- Eyebrows move based on her emotion (skeptical)
- Speaking bars animate in the corner

**[Action: Respond to whatever she says:]**
> "The trial showed a 34% reduction in MACE events over 36 months,
> with a p-value of 0.003. The dropout rate was only 4.2%."

**[Let her respond skeptically — show emotion detection changing]**

**[Action: Switch to Dr. Arjun Sinha (Oncologist)]**

SAY:
> "We can instantly switch personas. Here's Dr. Arjun Sinha —
> same system, completely different personality, different skin tone,
> different dialogue behaviour."

**[Type:]** "Tell me about the combination therapy options."

**[Let Dr. Sinha respond — note the engaged/curious expression]**

---

## SEGMENT 4 — Voice Input Demo (3:30 – 4:00)

**[Action: Click the mic button 🎙]**

SAY INTO MIC:
> "What are the main side effects I should warn my patients about?"

**[Show: Voice transcribes → sends to Claude → avatar responds]**

SAY:
> "Full voice-in, avatar-out — just like a real face-to-face visit."

---

## SEGMENT 5 — Technical Close (4:00 – 4:30)

**[Action: Click Export session — show the JSON]**

SAY:
> "Every session exports a full transcript with timestamps —
> ready for LMS integration or performance scoring."

**[Screen: Switch to GitHub repo briefly]**

SAY:
> "The entire system is open source under MIT license.
> One HTML file for the demo. Docker Compose for production.
> Drop-in React component for Proxa Echo integration."

**[Screen: Back to avatar]**

SAY:
> "NEXTGENX — real conversations, real-time, real open source.
> Built for Proxa Echo. Built to win."

---

## POST-RECORDING

- Trim to under 5 minutes
- Add captions if possible
- Upload to YouTube (unlisted) or Loom
- Paste the link into your HackIndia submission

---

## BACKUP — If Claude API is slow during recording

Use the Quick Demo buttons in the left panel:
- "Intro greeting" — pre-built phrase, animates avatar without API
- "Skeptical response" — shows emotion engine
- "Ask about trials" — shows pharmaceutical context

These work WITHOUT an API key and are safe for recording.

---

## TIPS FOR A WINNING VIDEO

1. Talk LESS, show MORE — let the avatar speak
2. Zoom into the mouth during lip sync — this is your differentiator
3. Show the pipeline dots lighting up — it proves the system works end-to-end
4. Switch personas at least once — shows multi-HCP support
5. End on the GitHub repo — judges need to see you're submission-ready
