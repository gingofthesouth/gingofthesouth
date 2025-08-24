# Ernest Cunningham

**Senior iOS Engineer | Mobile Team Lead | CI/CD Advocate**  
📍 New Zealand | ✉️ ernest@ging.nz | 🔗 LinkedIn / GitHub: [github.com/gingofthesouth](https://github.com/gingofthesouth)

---

## Professional Summary

Senior iOS Engineer with 15+ years in software development and 9+ years building and leading iOS applications at scale. Experienced in SwiftUI, Combine, Swift Concurrency, and CI/CD pipelines, delivering enterprise mobility solutions for government and consumer apps with 1M+ monthly users. Proven leader in mentoring, cross-team collaboration, and driving user-centered products that improve efficiency, reliability, and privacy.

---

## Core Skills

Swift • SwiftUI • Combine • Async/Await (Actors) • UIKit • Core Data • SwiftData • CloudKit • REST APIs • WebSockets • SSE • XCTest/XCUITest • GitLab CI/CD • Fastlane • Sentry • Docker • Agile/Scrum • Stakeholder Management • Team Mentorship • Enterprise Distribution (Microsoft Intune, AD group targeting)

---

## Career Experience

### Senior DevSecOps Engineer / Senior iOS Engineer  
_New Zealand Customs Service | Jul 2023 – Present_
- Product lead for Customs’ Frontline Mobility Application (FMA), used across airports (arrivals/departures), roaming officers, secondary processing, international mail centre inspections, inward cargo/container freight, ACIF parcel inspections, cruise ship pax processing, and maritime.
- Replaced paper notebooks for staff with real-time mobile workflows, saving officers hours per day and enabling higher-throughput inspections with better data fidelity.
- Mentored iOS and backend developers; upskilled testers in UI automation.
- Established GitLab CI/CD with automated builds, unit/UI tests, linting, and SonarQube on every MR; standardised coding practices and documentation.
- Introduced and improved Sentry crash/metrics capture and dev workflows.
- Enterprise distribution via Microsoft Intune with AD group device targeting.
- **Tech:** Swift, SwiftUI/Combine, Swift Concurrency (async/await, actors), REST, Sentry, GitLab, SonarQube.

### Mobile Application Developer  
_New Zealand Customs Service | Sep 2020 – Jul 2023_
- Developed and maintained the FMA iOS app (Swift, SwiftUI, Combine) powering frontline operations.
- Key contributor to the Traveller Declaration integration: surfaced traveller journey info, officer interactions, and digital declarations; improved automated risk detection and scoped data to protect passenger privacy across agencies.
- Partnered with SMEs and product owners to plan/sequence features aligned to agency-wide objectives.

### iOS Developer  
_CricHQ | Feb 2017 – Sep 2020_
- Delivered features for App Store iOS apps serving 1M+ monthly users (NZ Cricket and international leagues).
- Improved crash-free sessions from low 90s to 99.3% through monitoring, rapid bug fixes, and better testing.
- Led NZ development of My Action Replay: live sports streaming with real-time scoring overlays and automated highlight generation.
- Built bespoke scoring apps; rolled out live-stream tech to cricket, hockey, and tennis venues across NZ.
- Engineered millisecond-latency event flow via WebSockets and a cricket state engine.

### Project Manager & Lead Developer  
_Icy IT Limited | Aug 2014 – Feb 2017_
- Co-founded a startup delivering a micro-location platform: iOS framework, REST API, and three Swift apps.
- Ran agile process/governance and day-to-day delivery.
- Built accessible UX in partnership with visually impaired testers (Icy Vision).

### Earlier Roles
- **Data Analyst, Parliamentary Service NZ (2012)** – Voter data analysis for campaign strategy.  
- **Database Developer, Digital Fusion (2004–2006)** – Custom database solutions deployed to multinational clients.  
- **Systems Engineer, Nelson Provincial Museum (2002–2004)** – Collection management/archives software, website, and IT support.

---

## Selected Projects

### Espresso Servicing – Field Service Management App  
_Tech: SwiftUI, Combine, SwiftData, CloudKit, LocalAuthentication, AuthenticationServices, CryptoKit_
- Universal iOS/macOS app for coffee machine technicians: scheduling, on-site documentation (with photos), and parts/labour billing.
- Clean Architecture with DI container, repository/interactor patterns, type-safe flows; offline-first with CloudKit sync (categorized error handling, exponential backoff).
- Security: salted password hashing, Keychain-bound biometric sessions, passkeys (WebAuthn), role-based permissions.
- Testing: 75.33% coverage across Swift Testing + XCTest with factories/mocks.
- **Impact:** reduces technician overhead and improves auditability/traceability; designed for modular scale and future backend swaps.

### Xcode LLM – Local AI Inference Server  
_Tech: Swift, MLX (Apple), Hummingbird (HTTP), Server-Sent Events, OpenAI-compatible API_
- Production-ready local inference server running 20B–120B parameter models on Apple Silicon; OpenAI API-compatible for seamless Xcode integration.
- Real-time token streaming with <40ms latency, proper backpressure/flow control; intelligent request scheduling/cancellation.
- Model management with multiple quantisation levels, SHA256 verification, and dual MLX/MLXLLM inference paths with fallback.
- Production features: bearer/x-api-key auth, structured logging with redaction, request-scoped tracing, 25+ test files.
- **Outcome:** fast, private, reliable AI assistance inside Xcode without cloud dependency.  
- **GitHub (related):** FlexAI – public Swift project for local AI inference/dev tooling.

---

## Education

**Bachelor of Software Engineering** — Whitireia / WelTec / Te Pūkenga (2015)  
- A+ Average • Top Student • Top Project
