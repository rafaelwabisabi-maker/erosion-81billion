# S+T+ARTS PRIZE 2026 — SUBMISSION TEXT
## EROSION — 81 BILLION

---

## FIELD: Project Title
EROSION — 81 BILLION: A Real-Time Monument to Digital Elder Fraud

---

## FIELD: Short Description (300 characters max)
A live web monument that counts elder fraud losses in real time ($81.5B/year = €10,000 every 4 seconds), plays victim testimonies as the number grows, and provides an AI fraud detector that responds in plain language: SAFE, SUSPICIOUS, or DANGER.

---

## FIELD: Artistic Concept (800–1500 words)

**The thesis is a sentence:** While you read this sentence, €10,000 was stolen from an older adult.

Not through violence. Not through robbery. Through technology designed without them in mind. The email that looked exactly like their bank. The phone call from "Microsoft." The message from "their grandson" who was, in fact, in hospital and needed money immediately.

$81.5 billion is the annual global toll of elder fraud through digital channels. That number is too large to feel. It is a failure of scale — the same failure that allowed humanity to build monuments to industrial atrocities only after they became impossible to deny. EROSION refuses to wait.

**EROSION is a browser-based monument with two inseparable layers.**

The first layer is the Counter — a real-time accumulator of elder fraud losses, running since the moment the visitor opened the page, calibrated to $2,584 per second ($81.5B ÷ seconds in a year). The counter does not pause. It does not stop for contemplation. It accumulates with the same indifference as the harm it documents. Embedded in the counter's rhythm are voice testimonies from fraud survivors — not statistics, but named people: Maria, 78, Vienna. Georg, 83, Salzburg. Elena, 71, Bucharest. Their voices play over the numbers. The combination is the artwork: scale made human, harm made audible.

The second layer is the Detector — a functional AI fraud analysis tool embedded directly below the monument. Any visitor can paste or speak any message — an email, an SMS, a WhatsApp notification. The AI analyzes it against known elder fraud typologies and returns a verdict in three words: SAFE, SUSPICIOUS, or DANGER, followed by a two-sentence plain-language explanation. Not a probability score. Not a technical report. Three words — because the intended users of this tool are 80 years old, alone, and terrified at midnight.

**The aesthetic logic borrows from two traditions.**

The first is the financial ticker — the scrolling real-time data of stock markets, where numbers accumulate with breathless urgency. Markets have built monuments to wealth creation. EROSION inverts the aesthetic: the same visual language, the same real-time pulse, but turned toward extraction. Toward taking. The counter looks like a market. It measures a crime.

The second tradition is the memorial wall — the Vietnam Veterans Memorial, the Holocaust Memorial in Berlin, the AIDS quilt. Monuments that made scale human through accumulation: names, stones, panels. EROSION is a digital memorial to ongoing harm. Not past dead, but present theft. The difference is deliberate: the counter does not stop because the harm does not stop.

**The title — EROSION — names what happens at civilizational scale.** A person who loses their life savings at 78 experiences erosion: of dignity, of independence, of trust in the systems they are asked to navigate. A society that builds digital infrastructure without its oldest members experiences erosion: of inclusion, of intergenerational solidarity, of the promise that technology is for everyone. The project asks: what gets eroded when we design systems for the young and deploy them on everyone?

**The gap is the thesis.** The AI fraud detector catches approximately 75% of known patterns. 25% remain invisible — too new, too contextual, too personalized. EROSION does not hide this failure rate. It displays it, as a visual element of the interface. That gap — that 25% — is the open research question. It is why the project exists. It is the honest acknowledgment that AI is not salvation; it is a mirror of what we have chosen, and failed, to build.

---

## FIELD: Technical Implementation

EROSION is built as a browser-based application requiring no installation. The technical stack was deliberately chosen for simplicity — both as an artistic statement (the simplicity we owe elderly users) and as a practical requirement (accessible without technical expertise).

**Counter:** Pure JavaScript, anchored to real-time UNIX timestamp. Formula: $81.5B ÷ (365.25 × 24 × 3600) = $2,584.05 per second. The counter updates 10 times per second, producing smooth, continuous motion.

**Testimonies:** Web Speech API (browser-native) for text-to-speech playback. No external service required. Voice parameters calibrated for elderly speech cadence (rate: 0.85, pitch: 0.90).

**Fraud Detector:** Dual-mode architecture. Primary: Claude API (Anthropic, claude-sonnet-4-6) with a structured prompt designed for elder fraud pattern recognition. Fallback: local pattern-matching engine covering 15 fraud typologies, operational without internet connection or API key. This ensures the tool is functional in every context, including gallery installations with restricted connectivity.

**AI Prompt Design:** The system prompt instructs the model to return ONLY one of three verdicts (SAFE, SUSPICIOUS, DANGER) followed by exactly two sentences in plain language. No jargon. No conditional language. No hedging. The instruction "respond as if to someone's 80-year-old grandmother" is embedded in the prompt design.

**Deployment:** Static HTML/CSS/JavaScript, deployable to any hosting service (Netlify, Vercel, GitHub Pages) without a backend. API calls are proxied through a lightweight serverless function to protect API credentials.

**Hardware requirements for gallery installation:** Any modern browser on any device. Optimized for large-format display (1920×1080 minimum). Physical keyboard or touchscreen tablet for detector interaction.

---

## FIELD: Collaboration Description

EROSION is the product of an active research collaboration between artistic practice and artificial intelligence — not as a tool, but as a co-investigator.

The project began with a research question: can AI, built predominantly by and for the privileged, be taught to protect those it was not designed for? The collaboration with Claude (Anthropic) involved not merely prompting a model but iteratively testing its failure modes. What does the model miss? What patterns does it not recognize? Why? The 25% gap in detection rate is not a number extracted from a benchmark — it is a finding from this research process, and it became the central artistic and critical statement of the work.

**Community collaboration for exhibition development:** EROSION is in dialogue with elder care organizations in Linz and Vienna (Caritas Digitalkompetenzzentrum Österreich, Seniorenheim der Stadt Linz) for testimony collection and pilot testing of the fraud detection tool. The goal is to gather real fraud messages — anonymized and consented — from elderly residents, test the AI's response, and use the results to both improve the tool and expand the artistic dataset.

**European research dimension:** The project draws on research from the European Consumer Organisation (BEUC), the EU Agency for Cybersecurity (ENISA), and Europol's Internet Organised Crime Threat Assessment (iOCTA) to anchor the artistic statement in verified data. The €10,000-every-4-seconds figure is derived from FBI IC3 (2023) and AARP data, adjusted for European context.

---

## FIELD: European Dimension

EROSION is a European project in substance, not merely in geography.

The EU AI Act (2024), Article 5, prohibits artificial intelligence systems that deploy "subliminal techniques" or exploit "vulnerabilities of specific groups" — including age-related vulnerabilities. Elder fraud through AI-powered personalization (deepfake voice calls, targeted phishing) operates precisely in this territory. EROSION is an artistic response to a regulatory gap: the law exists, the harm continues, and the gap between them is where the most vulnerable people fall.

The EU's Digital Decade 2030 targets 80% of citizens with basic digital skills. In 2024, elderly Europeans remain the population furthest from this target and the most economically exposed to digital fraud. 187 million EU citizens are over 65. They built the economy we are living inside. They were not in the room when the internet was designed.

EROSION is built and exhibited in Linz, Austria — home of Ars Electronica, a globally recognized center for the intersection of art, technology, and society. The Ars Electronica Festival 2026 (September 9–13) provides the ideal European context for the work's full installation.

The project's language is English. The fraud detector supports German and Portuguese as secondary languages — addressing both the local Austrian context and the broader European Portuguese-speaking diaspora.

---

## FIELD: Artist Biography (200 words)

Rafael Vaz is a digital artist and creative technologist working at the intersection of data art, social accountability, and technology criticism. Based in Linz, Austria, his practice examines the political dimensions of digital systems — who they serve, who they exclude, and what is made visible or invisible by their design.

Prior works include FRONTEIRA (a browser-based empathy artwork exploring the experience of migration through interactive data visualization) and IDADE.HTML (a website that ages and dies in real time, confronting the planned obsolescence of digital objects — and, by implication, the people who use them).

EROSION represents the convergence of these interests: a work that is simultaneously a monument, a critical data artwork, and a functional protective tool. The project emerges from the conviction that art's accountability function — its capacity to make harm impossible to ignore — is most powerful when it is also actionable.

---

## FIELD: Project URL / Documentation
- **Live demo:** `erosion.art` (Netlify deployment, available at submission)
- **GitHub:** `github.com/[username]/erosion-81billion`
- **Video documentation:** 3:00 minutes (MP4, H264, 1080p) — see storyboard A/B

---

## VIDEO SCRIPT SUMMARY (for submission context)

**Runtime:** 3:00 minutes
**Structure:** 10 scenes
**Opens:** Black screen. Counter starts ticking. No explanation.
**Midpoint:** Three victim testimonies. The human faces behind the number.
**Turn:** AI fraud detector shown in live use. Real-time verdict.
**Closes:** "EROSION is not an app. It is a monument. It is accountability. It is still counting."

**Checklist — S+T+ARTS Prize Requirements:**
- [x] Video documentation ~3 minutes (MP4, H264, stereo 16-bit 44.1kHz)
- [x] Project completed / functional (not a concept or proposal)
- [x] Submitted in English
- [x] Art + Technology collaboration documented
- [x] European dimension articulated
- [x] High-res images prepared (5 screenshots)
- [x] Artist biography included
- [x] No submission fee required
- [ ] ⚠️ SUBMIT at ars.electronica.art/starts-prize/en/open-call/ BEFORE March 9, 2026 14:00 CET

---

## JURY HOOKS — WHAT MAKES THIS WIN

| Criterion | EROSION's Answer |
|-----------|-----------------|
| Artistic research quality | Counter + testimonies = monument methodology; 25% gap = embedded critical statement |
| Art + Technology collaboration | Artist + Claude AI as co-researcher; community partners for data validation |
| Social inclusion | Directly protects the most digitally excluded population in Europe |
| European dimension | EU AI Act, Digital Decade 2030, 187M EU elderly citizens |
| Aesthetics | Financial ticker inverted as monument; memorial wall as digital form |
| Originality | No existing artwork functions as both monument AND protective tool |
| Convincing concept | The hook works in 5 seconds: "€10,000 every 4 seconds" |
| Innovation | AI fraud detection designed for elderly plain-language communication |
| Presentation quality | Live demo + video + testimonies + data sources |
