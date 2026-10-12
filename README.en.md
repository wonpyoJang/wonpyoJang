[한국어](README.md) · **English**

## Wonpyo Jang · Flutter App Developer (6 years)

> Owned apps with 50K–100K DAU · Led a 4-person mobile team · Crash-free 88% → 98% · Shipped a medical device (SaMD) app

I've owned apps for services with 50K–100K DAU, such as *Onul School* and *Kyochon Chicken*, and restructured them so that several people can work on them at once and keep them maintainable, without breaking the legacy code.

*Comfortable communicating in written English — technical docs, papers, and App Store reviewer correspondence.*

- Multi-brand ordering apps including *Kyochon Chicken* (2M sign-ups) — **crash-free users 88% → 98%**, fixed circular event flows, introduced DI
- Led the 4-person mobile team for *Onul School* (1.5M sign-ups) — architecture migration, CI/CD with GitHub Actions + Fastlane, staged rollouts
- Software as a Medical Device (SaMD): musculoskeletal measurement app for clinicians (Galaxy Tab) — full-stack, US and French versions, customer demos and delivery
- National Supercomputing Competition, awarded 3 times (Grand Prize twice)

---

### 🔧 Tech Stack

- **App**: Flutter, Dart, BLoC, RxDart, Flame
- **Data**: Drift (formerly Moor) · SQLite, Hive, Firebase (Firestore · Remote Config)
- **Architecture**: Clean Architecture, Injectable (get_it) DI, design system
- **CI/CD**: GitHub Actions, Fastlane, flavor-based environments, staged rollouts
- **Monitoring · Analytics**: Crashlytics, Sentry, GA4, Amplitude
- **Realtime**: WebRTC (Agora), FCM silent push
- **Also**: Next.js · Prisma · PostgreSQL (side-project admin), Python (FastAPI), React, Docker, AWS, Datadog, Jira, Claude Code · Cursor

---

### 💼 Experience

**Orthocare** — SaMD (musculoskeletal measurement) app for clinicians (2026.04 – 2026.10)
- Full-stack development of the Galaxy Tab clinician app and its backend
- US and French versions (localization)
- Customer demos and delivery support

**FoodDash** — White-label delivery ordering apps for franchises · Mobile Engineer (2023.11 – 2025.12 · App 2 · BE 4 · FE 2)
- Built and ran new features for multi-brand apps: *Kyochon Chicken* (2M sign-ups), *Eupcheonri 382*, *Jadam Chicken*, and more
- Stamp promotions, gift cards and coupons, menu system, member management, order status screens; managed App Store and Play Store releases
- Third-party gift card registration and redemption; real-time order status (received → cooking → delivering) via silent push; sign-up revamp with KCB identity verification
- **Crash-free users 88% → 98%** (Firebase Crashlytics)
- Fixed circular event flows across multiple BLoCs and BlocListeners, introduced Injectable (get_it) DI, redesigned the coupon and menu option systems with OOP, design system adoption at 50% of the codebase

▸ Kyochon Chicken ordering app

<table>
  <tr>
    <td align="center" width="33%"><img src="assets/kyochon-store.gif" width="240" alt="Pickup or delivery → choose a store on the map" /></td>
    <td align="center" width="33%"><img src="assets/kyochon-menu.gif" width="240" alt="Browse menu → add to cart" /></td>
    <td align="center" width="33%"><img src="assets/kyochon-checkout.gif" width="240" alt="Apply coupon → choose a payment method" /></td>
  </tr>
  <tr>
    <td align="center"><sub>Pickup or delivery → choose a store on the map</sub></td>
    <td align="center"><sub>Browse menu → add to cart</sub></td>
    <td align="center"><sub>Apply coupon → choose a payment method</sub></td>
  </tr>
</table>

▸ Eupcheonri 382 ordering app (2024.12 – 2025.06)

<table>
  <tr>
    <td align="center" width="33%"><img src="assets/eupcheonri-menu.gif" width="240" alt="Browse menu → add to cart" /></td>
    <td align="center" width="33%"><img src="assets/eupcheonri-options.gif" width="240" alt="Set menu options" /></td>
    <td align="center" width="33%"><img src="assets/eupcheonri-checkout.gif" width="240" alt="Delivery notes → checkout" /></td>
  </tr>
  <tr>
    <td align="center"><sub>Browse menu → add to cart</sub></td>
    <td align="center"><sub>Set menu options</sub></td>
    <td align="center"><sub>Delivery notes → checkout</sub></td>
  </tr>
</table>

**Athenaslab** — *Onul School* app · Client Chapter Lead (2021.08 – 2023.10)
- *Onul School* (1.5M sign-ups): timetable, school meals, academic calendar, and a community with posts, comments and GIF stickers (Flutter, BLoC, RxDart, Injectable, Hive)
- Migrated to a layered architecture with DI and an RxDart global event bus; dynamic board creation, multiple profiles for timetable and community, home summary
- Led a 4-person mobile team: 2-week sprints, OKRs, onboarding docs, code, design and API spec reviews, design system collaboration
- Automated builds and store releases with GitHub Actions + Fastlane; flavor separation to stop dev builds from reaching production; moved from all-at-once to staged rollouts
- Parallel development process with Remote Config feature flags + Git Flow
- Quality monitoring with Crashlytics and Sentry, an event taxonomy for GA and Amplitude, and a built-in log and API call monitor in release-mode dev builds that cut unnecessary API calls

<table>
  <tr>
    <td align="center" width="33%"><img src="assets/onulschool-timetable.gif" width="240" alt="Add a class to the timetable" /></td>
    <td align="center" width="33%"><img src="assets/onulschool-meal.gif" width="240" alt="School meals" /></td>
    <td align="center" width="33%"><img src="assets/onulschool-calendar.gif" width="240" alt="Add a personal event to the calendar" /></td>
  </tr>
  <tr>
    <td align="center"><sub>Add a class to the timetable</sub></td>
    <td align="center"><sub>School meals</sub></td>
    <td align="center"><sub>Add a personal event to the calendar</sub></td>
  </tr>
</table>

<table>
  <tr>
    <td align="center" width="33%"><img src="assets/onulschool-feed.gif" width="240" alt="Community feed" /></td>
    <td align="center" width="33%"><img src="assets/onulschool-vote.gif" width="240" alt="Poll post" /></td>
    <td align="center" width="33%"><img src="assets/onulschool-comments.gif" width="240" alt="Comments → write a post" /></td>
  </tr>
  <tr>
    <td align="center"><sub>Community feed</sub></td>
    <td align="center"><sub>Poll post</sub></td>
    <td align="center"><sub>Comments → write a post</sub></td>
  </tr>
</table>

**ZetServe** — Mobile Engineer (2020.05 – 2021.07)
- RPG-style voice chat app on the Flame game engine + WebRTC (Agora): character interactions and map movement, P2P communication over a Pub/Sub server
- Chat data model across local (SQLite · Moor) and cloud (Firestore) storage, bulletin board
- Launched a webtoon platform in Southeast Asia as a client project the company won

---

### 🛠 Projects

**Scan capture app (personal side project)** — scan history and quality trends, titles and badges, a character to raise, a ladder mini-game, 1:1 chat with clinicians (screens use demo data)

<table>
  <tr>
    <td align="center" width="50%"><img src="assets/scan-badge.gif" width="240" alt="Badge unlock animation" /></td>
    <td align="center" width="50%"><img src="assets/scan-ladder.gif" width="240" alt="Ladder game animation" /></td>
  </tr>
  <tr>
    <td align="center"><sub>Badge unlock animation</sub></td>
    <td align="center"><sub>Ladder game animation</sub></td>
  </tr>
</table>

<table>
  <tr>
    <td align="center" width="33%"><img src="assets/scan-chat-enter.gif" width="240" alt="Choose the display name before entering a chat" /></td>
    <td align="center" width="33%"><img src="assets/scan-chat-send.gif" width="240" alt="Send messages and files" /></td>
    <td align="center" width="33%"><img src="assets/scan-chat-search.gif" width="240" alt="Refresh chat list → search messages" /></td>
  </tr>
  <tr>
    <td align="center"><sub>Choose the display name before entering a chat</sub></td>
    <td align="center"><sub>Send messages and files</sub></td>
    <td align="center"><sub>Refresh chat list → search messages</sub></td>
  </tr>
</table>

**Admin web** (back office for the scan capture app · Next.js · Prisma · PostgreSQL) — 3D conversion pipeline, operations monitoring, usability feedback, member management (screens use demo data)

<table>
  <tr>
    <td align="center" width="50%"><img src="assets/admin-conversion-stats.gif" alt="3D conversion stats — period switch, duration, success rate" /></td>
    <td align="center" width="50%"><img src="assets/admin-workers.gif" alt="Conversion worker list → details and live logs" /></td>
  </tr>
  <tr>
    <td align="center"><sub>3D conversion stats — period switch, duration, success rate</sub></td>
    <td align="center"><sub>Conversion worker list → details and live logs</sub></td>
  </tr>
  <tr>
    <td align="center" width="50%"><img src="assets/admin-performance.gif" alt="Response time per route (p95) — period switch" /></td>
    <td align="center" width="50%"><img src="assets/admin-feedback.png" alt="Usability feedback — NPS and CSAT trends, report handling" /></td>
  </tr>
  <tr>
    <td align="center"><sub>Response time per route (p95) — period switch</sub></td>
    <td align="center"><sub>Usability feedback — NPS and CSAT trends, report handling</sub></td>
  </tr>
  <tr>
    <td align="center" colspan="2"><img src="assets/admin-members.png" width="50%" alt="Member management — sign-up approval, role assignment, access removal" /></td>
  </tr>
  <tr>
    <td align="center" colspan="2"><sub>Member management — sign-up approval, role assignment, access removal</sub></td>
  </tr>
</table>

**[AI emotion-analysis diary app](https://github.com/wonpyoJang/diary_mobile_client)** — Flutter, BLoC, generative AI integration

<table>
  <tr>
    <td align="center" width="33%"><img src="assets/diary-write.gif" width="240" alt="Write a diary entry" /></td>
    <td align="center" width="33%"><img src="assets/diary-emotion.gif" width="240" alt="AI extracts emotions from the entry" /></td>
    <td align="center" width="33%"><img src="assets/diary-card.gif" width="240" alt="Create an emotion card → save" /></td>
  </tr>
  <tr>
    <td align="center"><sub>Write a diary entry</sub></td>
    <td align="center"><sub>AI extracts emotions from the entry</sub></td>
    <td align="center"><sub>Create an emotion card → save</sub></td>
  </tr>
</table>

**[Analog Timer](https://github.com/wonpyoJang/analog-timer)** — draws segment timers and a stopwatch together on an analog clock face. Flutter (iOS · Android · macOS) + web

<table>
  <tr>
    <td align="center" width="25%"><img src="assets/timer-desktop.png" width="190" alt="Desktop — timer ring, stopwatch, segments" /></td>
    <td align="center" width="25%"><img src="assets/timer-widget.png" width="190" alt="Always-on-top widget mode" /></td>
    <td align="center" width="25%"><img src="assets/timer-overlay.png" width="190" alt="Android overlay clock and timer pill" /></td>
    <td align="center" width="25%"><img src="assets/timer-multi.png" width="190" alt="Multiple timers at once" /></td>
  </tr>
  <tr>
    <td align="center"><sub>Desktop — timer ring, stopwatch, segments</sub></td>
    <td align="center"><sub>Always-on-top widget mode</sub></td>
    <td align="center"><sub>Android overlay clock and timer pill</sub></td>
    <td align="center"><sub>Multiple timers at once</sub></td>
  </tr>
</table>

---

### 🎓 Education · Awards

- **University of Seoul**, B.S. in Electrical and Computer Engineering (2014 – 2020) — research assistant at the Parallel Software Lab, teaching assistant for Microprocessors
- **National Supercomputing Competition, awarded 3 times** (KISTI · UNIST) — Excellence Award 2016, Grand Prize 2017 · 2018 (multi-process parallel acceleration with OpenMPI)
- **Fintech × Insurtech Hackathon, Excellence Award** (KISA, 2019) — driving score calculation on Hyperledger Fabric (Flutter · Node.js · GCP)
- **ETRI summer intern** (2019) — performance analysis of on-board speech recognition (Kaldi) for vehicles
- Industrial Engineer Information Processing certificate · Army information security specialist (security monitoring support for the 2018 PyeongChang Olympics)

---

### 📫 Contact

For hiring or collaboration, please reach out by email.

- Email: jangwonpyo0@gmail.com
- Instagram: [@dev.logos](https://www.instagram.com/dev.logos)
