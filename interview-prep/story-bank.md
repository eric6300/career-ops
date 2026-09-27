# Story Bank — Master STAR+R Stories

This file accumulates your best interview stories over time. Each evaluation (Block F) adds new stories here. Instead of memorizing 100 answers, maintain 5-10 deep stories that you can bend to answer almost any behavioral question.

## How it works

1. Every time `/career-ops oferta` generates Block F (Interview Plan), new STAR+R stories get appended here
2. Before your next interview, review this file — your stories are already organized by theme
3. The "Big Three" questions can be answered with stories from this bank:
   - "Tell me about yourself" → combine 2-3 stories into a narrative
   - "Tell me about your most impactful project" → pick your highest-impact story
   - "Tell me about a conflict you resolved" → find a story with a Reflection

## Stories

### [Architecture] Android Modularization Initiative
**Source:** Report #016 — YStory — iOS/Android App Development Engineer (Japan batch, 2026-09-27)
**S (Situation):** At Penpeer, the mobile team built the same features three times across separate app codebases with no shared architecture.
**T (Task):** Reduce duplicated engineering effort and set up a maintainable, scalable architecture for future feature work.
**A (Action):** Evaluated and championed MVI + Jetpack Compose adoption, designed a modular architecture, and led the migration of new features onto the modern stack.
**R (Result):** Cut development time by an estimated 30-50% while improving maintainability.
**Reflection:** Learned to balance incremental migration against a big-bang rewrite; next time would put automated test coverage in place before migrating, not after.
**Best for questions about:** architecture decisions, technical leadership, legacy code, performance/scalability mindset, "your biggest technical achievement"

### [Management] Cross-functional Team Leadership
**Source:** Report #016 — YStory — iOS/Android App Development Engineer (Japan batch, 2026-09-27)
**S (Situation):** Promoted to Mobile Frontend Team Lead over a 6-person cross-platform team (3 iOS, 2 Android, 1 Web Frontend).
**T (Task):** Build a functioning team process and bridge gaps with PM, HR, and Backend.
**A (Action):** Ran regular 1-on-1s to understand each engineer's career goals, delegated work aligned with those goals, ran team syncs for knowledge exchange, and proactively closed cross-functional gaps.
**R (Result):** Smoother cross-functional collaboration and a team that stayed aligned despite spanning three platforms.
**Reflection:** Learned that career-aligned delegation drives more engagement than delegating purely by skill match.
**Best for questions about:** management style, conflict resolution, team growth, "tell me about your leadership philosophy," cross-functional collaboration

### [Scaling] Team Scaling 1-to-4 and Technical Standards
**Source:** Report #016 — YStory — iOS/Android App Development Engineer (Japan batch, 2026-09-27)
**S (Situation):** Sole mobile engineer at 最最科技, responsible for 7 shipped Android apps with no team around him.
**T (Task):** Scale the team and put technical standards in place to support that many products.
**A (Action):** Participated in recruitment, grew the team from 1 to 4 mobile developers (Android + iOS), and led Android team meetings to establish technical standards.
**R (Result):** A functioning 4-person mobile team with shared technical standards.
**Reflection:** Learned that documenting standards early avoids painful onboarding friction later — would write the standards doc before headcount 2, not after.
**Best for questions about:** hiring, scaling from zero, ambiguity, "how do you build a team from scratch"

### [Innovation] AI/Automation Adoption (n8n, AI Tool Competition)
**Source:** Report #016 — YStory — iOS/Android App Development Engineer (Japan batch, 2026-09-27)
**S (Situation):** Team relied on manual, repetitive processes with no automation culture.
**T (Task):** Promote an automation-first, AI-first mindset across the org.
**A (Action):** Evolved an internal "Auto Club" into structured workshops combining AI agents with n8n, and organized an AI Tool Competition that challenged the team to complete real requirements without writing code.
**R (Result):** Automation-first mindset adopted organization-wide.
**Reflection:** Learned that hands-on competitions drive adoption far better than top-down mandates.
**Best for questions about:** driving culture change, innovation, AI adoption, "how do you get a team to change how it works"

### [Ownership] Solo End-to-End Delivery (7 Apps)
**Source:** Report #016 — YStory — iOS/Android App Development Engineer (Japan batch, 2026-09-27)
**S (Situation):** As the only Android developer at 最最科技, needed to ship a diverse portfolio of consumer apps (dating, discovery, anonymous professional communities).
**T (Task):** Own the full product cycle end to end for each app with minimal support.
**A (Action):** Solo-developed 7 Android apps (MediTalk, Clos, A-Pen, 護理站, 藥師圈, 靠北警察, and others), took part in feature ideation and design reviews, and introduced Mixpanel and Amplitude with defined event specifications.
**R (Result):** 7 apps shipped with analytics instrumented from day one.
**Reflection:** Learned to balance shipping speed against analytics rigor — would define the event taxonomy earlier next time instead of retrofitting it.
**Best for questions about:** ownership, fast execution under ambiguity, working with limited resources, consumer app development

### [Origin Story] Career Pivot — DVM to Mobile Engineering
**Source:** Report #016 — YStory — iOS/Android App Development Engineer (Japan batch, 2026-09-27)
**S (Situation):** Licensed veterinarian (DVM, National Taiwan University) who self-taught programming to change careers.
**T (Task):** Transition into mobile engineering credibly and build production-quality software.
**A (Action):** Built the CardioBird app from zero to publishing with Kotlin, integrating BLE for ECG data collection, then joined VoiceTube as an Android developer, maintaining a 99.5% crash-free production app and acting as scrum master.
**R (Result):** Successful career transition, with veterinary domain expertise directly informing product decisions on CardioBird (a veterinary ECG tool).
**Reflection:** Domain expertise from the first career, not just technical skill, was what made the transition valuable — it let him bridge user needs (vets) to technical implementation directly.
**Best for questions about:** "tell me about yourself," career story, cross-domain thinking, unconventional backgrounds

### [Technical Influence] Championing MVI + Compose Without a Mandate
**Source:** Reports #021 (Mercari), #024 (SENRI), #025 (Progrit) — Japan batch, 2026-09-27
**S (Situation):** Team was on a legacy MVVM/View-based UI stack with real switching costs to a modern one.
**T (Task):** Get buy-in for a stack migration (MVI + Jetpack Compose) without formal authority to mandate it.
**A (Action):** Piloted the new stack on new features first, let results speak before proposing team-wide adoption.
**R (Result):** Full team adoption of MVI + Jetpack Compose for new work.
**Reflection:** Evidence beats mandate — proving value on a small surface builds trust faster than a top-down decree.
**Best for questions about:** influencing without authority, driving technical change, architecture decisions

### [Data-Informed Decisions] Instrumenting Before Optimizing
**Source:** Reports #021 (Mercari), #024 (SENRI) — Japan batch, 2026-09-27
**S (Situation):** New apps shipped with no visibility into real usage or user behavior.
**T (Task):** Establish a measurement baseline before attempting to optimize anything.
**A (Action):** Introduced Mixpanel and Amplitude, defined event specifications, implemented tracking across apps.
**R (Result):** Team could make data-informed product and UX decisions instead of guessing.
**Reflection:** You can't safely optimize (performance or otherwise) what you can't yet measure — this applies as much to low-spec-device UX tradeoffs as to funnel analysis.
**Best for questions about:** product sense, UX optimization, data-driven decision-making

### [Process] Running the Ceremonies
**Source:** Report #025 — Progrit — Android Engineer
**S (Situation):** VoiceTube's Android team needed a structured delivery cadence alongside active feature work.
**T (Task):** Facilitate Scrum ceremonies as team scrum master while still contributing as an individual engineer.
**A (Action):** Ran daily stand-ups, sprint reviews, and retrospectives while maintaining and shipping new features.
**R (Result):** Consistent delivery cadence maintained alongside a 99.5% crash-free rate for the production app.
**Reflection:** Ceremony facilitation is a real skill, not overhead, when done with intent — it's the scaffolding that makes cadence and quality compatible.
**Best for questions about:** Agile/Scrum experience, process ownership, balancing IC work with process facilitation

### [Platform] Cross-App URL Shortener Service
**Source:** Reports #002, #004 — 17LIVE (Sr. Staff Android), Pinkoi (Platform Squad)
**S (Situation):** Each of three production apps was about to build its own sharing/link-shortening logic separately.
**T (Task):** Avoid three redundant builds by shipping one shared platform service instead.
**A (Action):** Designed and implemented a single URL shortener service consumed by all three apps' sharing features.
**R (Result):** The service now powers sharing for all three production apps.
**Reflection:** Would treat it as a versioned internal API/SDK from day one to make onboarding easier for future teams building on top of it.
**Best for questions about:** platform thinking, shared infrastructure, avoiding duplicated work, cross-team ownership, "tell me about a time you built something used by multiple teams."
