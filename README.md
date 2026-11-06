# Wolf-s-Resume-

H O U S T O N , T E X A S | S O F T WA R E E N G I N E E R I N G — A N D R O I D , A I S Y S T E M S & A U T O M AT I O N
Edward Parkinson
Independent Software Engineer · AI Software Engineering Student · Union-Trained Welder
Phone (713) 208-6423 Email parkinsonedward564@gmail.com GitHub github.com/edwardparkinson-star
Location Houston, TX
8+ Systems
DESIGNED, BUILT &
OPERATED END TO END
220 Listings
LIVE ON THE RISE
TOGETHER SHOWCASE
720p30
FULL-LENGTH ON-
DEVICE VIDEO RENDER
10 Years
WELDING &
FABRICATION
DISCIPLINE
PROFESSIONAL SUMMARY
Independent software engineer who owns complete systems end to end — architecture,
implementation, adversarial testing, release, monitoring, and iteration — working entirely from a
mobile-first (phone-only) workflow. Shipped systems span on-device media rendering, emergency alerting,
on-device security, AI assistants with tool use, automated content pipelines, and market-data tooling.
Working style: clear system boundaries, honest failure modes documented in the code, and guardrails
where a system can cause harm. Backed by 10 years of union skilled-trades work meeting exact
specifications under production deadlines, and an in-progress AAS in AI Software Engineering.
WHY THIS BACKGROUND FITS A STAFF ROLE
CORE SKILLS
LANGUAGES Kotlin, Java, Python, JavaScript / HTML / CSS, GDScript
ANDROID & MEDIA Jetpack Compose, Android SDK, FFmpeg, WebView, app widgets, background jobs,
Termux / Termux:API, Godot (API 36)
SYSTEMS & OPS Linux, Git / GitHub, GitHub Pages, systemd, cron + watchdogs, long-polling bots, REST
APIs, JSON pipelines, FastAPI
AI & AUTOMATION Local LLMs (Ollama, llama.cpp), fallback chains (Gemini, Groq), prompt engineering,
Telegram bots, Gmail-API automation, speech-to-text / text-to-speech
TESTING & SECURITY Adversarial testing, validation & monitoring, hashed credentials, allowlists, audit
logging, defensive network/IoT tooling; Playwright — assessment experience
System design across boundaries: phone clients, cloud backends (FastAPI + Ollama), Telegram bridges, Gmail-
API pipelines, and systemd services — designed as cooperating systems with explicit contracts, not single
scripts.
Reliability in production: operates a live Telegram relay under a supervisor + watchdog design; diagnosed
repeated silent failures to an external cause and eliminated duplicate-processor conflicts (Telegram 409) until
exactly one healthy instance runs.
Validation & monitoring: adversarial testing drove 11 revisions of Bella Guard (v1 to v2.11); connection-churn
and log-recency checks distinguish a healthy quiet service from a wedged one before acting.
Security & scope discipline: hash-only credentials, admin allowlists, sandboxed files, audit logs, environment-
only secrets; paper-only trading until gates are met, a licensing gate on his flagship app, and TEST mode (no
live dispatch, no charging) on his emergency app until dispatch is proven.
Edward Parkinson · (713) 208-6423 · parkinsonedward564@gmail.com Page 1 of 3SELECTED SYSTEMS — DESIGNED, BUILT & OPERATED
Cyberwolf Studio Cinema | Android App — Kotlin + Jetpack Compose Pre-Launch
UNITED | Emergency-Alert Web App TEST Mode
Bella Guard | Phone Anti-Theft Guard — Python / Termux v2.11 Live
Bella | Jarvis-Style AI Assistant — Python 2025 – Present
Vex / Islanders AI + Wolf Pack Relay | Personal AI & Telegram Infrastructure Live
Rise Together Showcase | Creator Platform & Automation Pipeline Live · 220 Listings
Crypto Watch | Android Market App — Java v1.1
Free, on-device Android app that turns any audio file into a full-length video entirely on the phone: full-length
720p30 render muxed with audio, 11 cinematic styles, dance mode (21-move library, 7 styles, 8-beat phrases)
and Photo Dance (12x16 mesh warp, beat-synced).
Iterated through v1.8.2 (FFmpeg decoder fix) via signed APK releases; held pre-launch behind a closed licensing
gate (23 providers checked, paperwork pack drafted) until paperwork is signed off — not yet publicly released.
Voice-triggered (“ALERT”) and tap-to-send emergency alerts carrying GPS location at the instant the alert fires;
Guardian Mode always-listening safety layer with microphone opt-in by default (OFF until the user toggles it on)
for privacy and consent.
RapidSOS payload structure built for dispatch routing; currently in TEST mode — live dispatch is not yet proven
and charging stays off until it is.
Non-face anti-theft layer: SIM/network check every 60 seconds, spoken alarm on SIM change or 3 failed
passphrase attempts, single-word voice commands, fingerprint on/off, and on-demand voice verification (“Bella
verify”).
Hardened over 11 revisions found by adversarial testing: passphrase stored as SHA-256 hash only, whole-word
passphrase matching, commands never logged in full, and documented honest limits (no face matching,
camera, internet, or SMS by design).
Voice assistant running on Android via Termux: speech in/out, offline command core, and a four-brain fallback
chain (on-device llama.cpp, Gemini, Groq, keyless API) that switches automatically on failure.
Modular skills: sandboxed coding/file work, defensive network and IoT auditing, reverse-engineering checks,
GitHub repo operations, and an admin-gated Telegram remote bridge; secrets environment-only, with an
append-only audit log. Includes a FastAPI + Ollama cloud “Batcomputer” backend.
Vex, his personal AI on Telegram (live since September 2026): owner-only allowlist (strangers get silence), local-
model backend (Ollama), wake/sleep phrases, and continuous memory — “loyalty earned, not owed” operating
philosophy.
Wolf Pack relay bot: Python long-polling service with voice-message transcription (faster-whisper), build-
request routing, anti-loop and rate-limit guards, supervised under systemd with a watchdog so exactly one
instance stays healthy.
Live showcase for independent makers: maker cards, order forms, a job board open to every maker, and guest
checkout where buyers pay each maker directly through the maker’s own payment link (makers keep 100%).
Automated pipeline mirrors new listings from inbox submissions onto the page and triages suggestion/fix mail
with zero manual handling; dead-link watchdog keeps the catalog honest.
Android app (WebView) plus home-screen widget for BTC, ETH, SOL, and DOGE: live prices and charts with
scheduled background updates — shipped as signed v1.0 and v1.1 APKs.
Edward Parkinson · (713) 208-6423 · parkinsonedward564@gmail.com · Houston, TX Page 2 of 3SELECTED SYSTEMS (CONTINUED)
Crypto Analyst Desk | Six-Role Paper-Trading System Paper Only
Rust & Ruin | Android Looter-Shooter — Godot v0.9 · Installed & Running
PROFESSIONAL EXPERIENCE
Independent Software Developer | Cybersymantics / Cyber Wolf Studios 2025 – Present
Welder / Production Worker | Naylor Industries · Local 54 Sheet Metal Workers 2024 – 2025
Welder | Mighty Coat (Whitney, TX) · Tech Light 2016 – 2022
EDUCATION
Associate of Applied Science, AI Software Engineering In Progress
Maestro AI University — Dallas, TX · Began May 2026 · Applied AI systems and software engineering
fundamentals.
Bachelor’s, Psychology — South University · Accepted, starting Nov 24, 2026; 2026–27 Financial Aid Plan signed
Oct 31, 2026. | GED, 2010 · Huntington Beach Adult School, CA.
ADDITIONAL
What sets this candidate apart: a builder who has already done the Staff-level parts of the job on his own
systems — designing across services, testing adversarially, operating live infrastructure, and refusing to ship
past a gate that is not met.
Automated analysis desk (Scout, Chart Analyst, Strategist, Risk Officer, Trader, Chief of Staff) scanning
BTC/ETH/SOL/DOGE hourly: 100-point scoring (trade 80+, watch 65–79, reject below 65) on EMA/RSI/MACD/ATR
evidence — never invented values.
Hard risk system on a $1,000 simulated portfolio ($0 real): 0.5% risk per trade, max 2 positions, daily/weekly
loss limits, 8% drawdown shutdown, kill switch. Real-money stays OFF until 8+ weeks, 50+ paper trades, verified
stops, and his go-ahead are all met.
Original cel-shaded FPS looter-shooter for Android (Godot, arm64, API 36): procedural gun generator (~18,000
base combinations), toon shader, mobile touch controls, enemies with elemental damage-over-time. Signed
APKs iterated to v0.9; installed and confirmed running on his phone.
Direct full-cycle development above using AI pair-programming workflows; manage GitHub repositories end to
end (version control, signed releases, GitHub Pages) and Linux-on-Android environments (Termux/Ubuntu).
Union production work: prepped/finished galvanized metals, welded assemblies to exact specifications under
deadlines, installed rooftop cooling units for Amazon data-center modules.
Torch-cut expanded metal within 1/8 in. for high-volume runs; fabricated park benches/receptacles installed
statewide; welded highway street-lamp assemblies to spec. Processes: MIG, TIG, Stick, Flux-Core, Laser.
Languages: English (native); Spanish (conversational); German & French (basic). Artist: distributing recording
artist (2024 – Present) — writes lyrics, records vocals, releases via DistroKid to Spotify, Apple Music, YouTube
Music, Amazon Music, and Deezer; only the beats are AI-made.
Edward Parkinson · (713) 208-6423 · parkinsonedward564@gmail.com · Houston, TX Page 3 of 3
