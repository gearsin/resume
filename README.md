# Sunil Singh
**Principal Unity Engineer**
Bengaluru, IN 

---

## Summary

Principal Unity Engineer with 21+ years of experience across game development, engine systems, multiplayer networking, platform engineering, and CI/CD. Deep expertise in Unity architecture, Photon Fusion internals, native Android/iOS integration, build automation, live-service systems, and AI gameplay. Currently building Project BLACK at Lila Games, spanning core framework design, server infrastructure, multiplayer resilience, and mobile performance.

---

## Work Experience

### Principal Engineer — Lila Games
**Feb 2021 – Present**
*Project BLACK — multiplayer looter-survival third-person shooter (Unity, Photon Fusion, Nakama, Android/iOS, Linux server)*

- Architected Project BLACK's core Unity service framework: Root/Scene/UIScene/Context DI containers, app state orchestration, async lifecycle management, staged bundle-based config loading, and Roslyn-generated service registration and discovery from binding attributes.
- Owned Android, iOS, and headless Linux CI/CD across multi-environment targets, including AAB support, Play Console symbol upload, Fastlane certificate automation, resumable builds, runner maintenance, Slack diagnostics, and BuildCLI automation.
- Built a headless-server asset stripping pipeline using IPreprocessBuildWithReport, label-based asset relocation and restore workflows, and Photon Fusion prefab-table predicates to keep client-only assets out of server builds.
- Engineered platform and runtime infrastructure below Unity, including Android/iOS service bridges, event-driven thermal and battery telemetry, native heap crash diagnostics, Unity exception handling, and a Roslyn [StringEnum] generator to eliminate enum string boxing in hot paths.
- Designed a host-agnostic game server provider abstraction that enabled migration from Hathora to Agones without client changes; hardened headless Unity server builds and stabilized server-side scene baking.
- Extended Photon Fusion beyond SDK defaults with patched change detection, a custom network runner, word-offset networked property callbacks, and an ordered startup pipeline.
- Improved multiplayer resilience with region probing, connectivity health aggregation, transparent Nakama session refresh, and a CCU integration test framework for mobile network conditions.
- Designed utility-based PvE bot systems covering perception, IK-aware aiming, cover, squad behavior, flee/revive logic, influence-aware routing, and transient footstep/gunshot network cues, using zero-allocation patterns in simulation-critical paths.
- Built a multi-provider analytics layer (PostHog, Firebase, Kochava, WildCloud) with A/B testing, attribution, device telemetry, and allocation-conscious event dispatch; delivered live-service features including IAP, push notifications (OneSignal, CleverTap), and social realm house visiting.

---

### Lead Software Engineer — GSN Games
**Jul 2015 – Feb 2021 (5 years 7 months)**
*Framework team and Bingo Bash studio (Unity, iOS, Android)*

- Led performance and architecture work across multiple studios as part of a shared infrastructure team, driving build optimization and cross-studio framework integration.
- Designed and implemented a Central Network Service (CNS/X-wing) providing remote service communication with caching, retry, and structured error handling; built an integration test tool and helper APIs that caught backend integration bugs earlier in development.
- Ported Bingo Bash from Flash to Unity3D for iOS and Android; led build pipeline, optimization, and cross-platform stability.
- Implemented a configurable framework layer enabling runtime behavior modification without code changes; contributed SDK integrations, unit tests, and build size analysis tooling (Unity MapParser, Python).

---

### Consultant Engineer — Knowledge Adventure Private Limited
**Apr 2009 – Jun 2015 (6 years 2 months)**
*Multi-platform game development (Unity, iOS, Android, Nintendo Wii, UWP, PC)*

- Shipped four Nintendo Wii titles and multiple iOS, Android, UWP (Windows 8/10), and PC games as part of the core framework and game teams.
- Built a cross-platform input system (keyboard, joystick, touch/drag) with ID-based abstraction and live designer-tweak support, removing per-device polling from game code.
- Implemented a UDP/TCP player prediction system for MMO remote players — buffering incoming packets, lerping movement over time, and updating toward the most recent server state for smooth remote character motion.
- Integrated Smartfox 2.x client and server with backward compatibility; added SQLite offline play with server-side data sync.
- Contributed framework APIs and tooling; helped teams resolve integration blockers and ported a Flash title to HTML5 using Haxe/OpenFL with performance optimizations and sprite sheet support.

---

### Sr. Game Programmer — Aurona Technologies Private Limited
**Jul 2007 – Apr 2009 (1 year 9 months)**

- Led a team of 5 developers shipping three titles across Nintendo DS, PS2, and PC.
- Implemented FSM-based enemy AI and optimized group pathfinding for enemy characters moving in formation.
- Built a 3DS Max SDK plugin (C++) for level design and automated level export pipelines.

---

### Game Programmer — Rolta India Public Ltd
**Jun 2006 – Jul 2007**

- Shipped two PC titles including an Army Training Simulation using GPS latitude/longitude for real-world navigation integration.

---

### Game Programmer — Chakra Interactive Pvt Ltd
**Dec 2004 – Apr 2006**

- Early-career role evaluating game engines and shipping small titles; supported an internal team with Flash integration that helped secure a project contract.

---

## Skills

| Area | Technologies |
|---|---|
| Engine | Unity, C#/.NET, C/C++, Unreal Engine 4 |
| Networking | Photon Fusion, Nakama, SmartFoxServer 2X, TCP/UDP |
| Framework | Addressables, UniTask, dependency injection framework |
| CI/CD | GitHub Actions, Fastlane, Android AAB/APK, iOS, headless Linux server |
| Native Platform | Android (JNI, thermal API), iOS (Objective-C, Xcode), NativeHeap |
| Code Generation | Roslyn source generators, IL weaving |
| Server Infra | Agones, Google Cloud |
| Analytics | PostHog, Firebase, Kochava, WildCloud |
| Graphics | OpenGL, DirectX, URP |
| Console | Nintendo Wii, Nintendo DS, PS2, UWP (Windows 8/10) |
| Tools | Visual Studio, Python, SQLite, Jenkins, 3DS Max SDK |

---

## Education

**Bachelor of Engineering, Computer Science**
Mumbai University — 2004
