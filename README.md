<div align="center">

<svg width="120" height="120" viewBox="0 0 120 120" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="ringGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#ff6b6b;stop-opacity:1" />
      <stop offset="50%" style="stop-color:#ee5a24;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#ff6b6b;stop-opacity:1" />
    </linearGradient>
    <clipPath id="circleClip">
      <circle cx="60" cy="60" r="52"/>
    </clipPath>
  </defs>
  <circle cx="60" cy="60" r="58" fill="url(#ringGrad)" />
  <circle cx="60" cy="60" r="54" fill="#0d1117" />
  <image href="https://github.com/Mohamed-Abdel-Rahem.png"
         x="8" y="8" width="104" height="104"
         clip-path="url(#circleClip)"
         preserveAspectRatio="xMidYMid slice"/>
</svg>

<br/>

# Mohamed Abdel-Rahem

**Flutter Mobile Engineer · Architectural Purist · Offline-First Specialist**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mohamed-abdel-rahem-386125288)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mohamedar2002mail@gmail.com)
[![WhatsApp](https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://wa.me/201152619144)

</div>

<hr/>

## About

I build Flutter applications where every layer of the system has a deliberate reason to exist.

My work begins not at the widget tree, but at the **domain boundary** — defining contracts, isolating business rules, and ensuring that neither the UI nor the infrastructure layer can corrupt the application core. I treat mobile development as a discipline in **distributed systems design at the client level**: engineering state machines, resolving synchronization conflicts, designing offline-first persistence pipelines, and managing reactive data flows with the same rigor applied to backend services.

I do not write features. I design systems that happen to have a user interface.

> **Current focus:** Offline-first architectures with real-time conflict reconciliation — combining Firebase Firestore Streams with local SQLite persistence behind a clean Repository abstraction.

<hr/>

## Technical Stack

### Core Platform

| Domain | Technology | Level |
|:---|:---|:---|
| Primary Language | Dart | Expert |
| UI Framework | Flutter | Expert |
| Deployment Targets | Android · iOS · Web | Production |

### Architecture & Design

| Pattern / Principle | Applied Context |
|:---|:---|
| **Clean Architecture** | Strict 3-layer separation: Domain → Data → Presentation |
| **MVVM** | ViewModel isolation; state exposed as reactive streams |
| **SOLID Principles** | Enforced at class and module boundary |
| **Repository Pattern** | Data sources abstracted behind domain-owned contracts |
| **Dependency Inversion** | Constructor injection; zero hard dependencies on infrastructure |
| **Feature-First Modules** | Independent, navigable vertical slices per feature |

### State Management

| Solution | Level | Primary Use Case |
|:---|:---|:---|
| **Riverpod** (+ Code Generation) | Expert | Compile-safe providers, async state, application-wide DI graph |
| **BLoC / Cubit** | Expert | Event-driven flows, predictable finite state machines |
| **GetX** | Proficient | Reactive bindings, lightweight controller lifecycle |

### Backend & Data Layer

| Technology | Role |
|:---|:---|
| **Firebase Firestore** | Real-time synchronization via snapshot stream listeners |
| **Firebase Authentication** | Identity management — email, OAuth, phone |
| **Firebase Cloud Messaging** | Reliable push notification delivery |
| **SQLite** | Offline-first local persistence layer |
| **Caching Strategies** | Stale-while-revalidate · TTL-based invalidation · Optimistic updates |
| **REST APIs** | Typed consumption via repository-abstracted HTTP clients |

### Engineering Practices

| Practice | Detail |
|:---|:---|
| **Testing** | Use-case unit tests · Widget tests · Mockito mocking |
| **CI/CD** | GitHub Actions — automated build, test, and release pipeline |
| **Code Quality** | Strict `analysis_options` · custom lint rules · zero-warnings policy |
| **Documentation** | Interface-level DartDoc · Architecture Decision Records (ADRs) |
| **Version Control** | Conventional Commits · feature branch workflow · signed releases |

<hr/>

## Key Achievement

<div align="center">

![DEPI](https://img.shields.io/badge/Digital%20Egypt%20Pioneers%20Initiative%20(DEPI)-Completed-ff6b6b?style=for-the-badge&logo=flutter&logoColor=white&labelColor=0d1117)

**Digital Egypt Pioneers Initiative (DEPI)** — Advanced Flutter Development Track
*National excellence program recognizing high-impact software engineering talent across Egypt.*

</div>

<hr/>

## GitHub Metrics

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=Mohamed-Abdel-Rahem&show_icons=true&theme=radical&include_all_commits=true&count_private=true&hide_border=true&bg_color=0d1117&title_color=ff6b6b&icon_color=ff6b6b&text_color=c9d1d9"/>

<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Mohamed-Abdel-Rahem&layout=compact&theme=radical&include_all_commits=true&count_private=true&hide_border=true&bg_color=0d1117&title_color=ff6b6b&text_color=c9d1d9&langs_count=6"/>

</div>

<div align="center">

<img src="https://github-readme-streak-stats.herokuapp.com/?user=Mohamed-Abdel-Rahem&theme=radical&hide_border=true&background=0d1117&ring=ff6b6b&fire=ff6b6b&currStreakLabel=ff6b6b&sideLabels=c9d1d9&dates=c9d1d9"/>

</div>

<hr/>

## Engineering Philosophy

Three principles govern every architectural decision:

**Isolation over convenience.**
Business logic must never be aware of Flutter, Firebase, or any infrastructure detail. Use cases operate on domain abstractions; all implementations are injected at the composition root.

**Reactivity by contract.**
State is a stream, not a snapshot. Every consuming layer handles emissions, errors, and loading states as first-class concerns — not afterthoughts patched at the UI level.

**Failure is a feature.**
Offline behavior is not an edge case. Every data operation is designed with network absence as the baseline assumption, not the exception.

<hr/>

## Contact

Open to **architectural discussions**, **technical reviews**, and **senior-level Flutter engineering opportunities**.

| Channel | Link |
|:---|:---|
| **LinkedIn** | [linkedin.com/in/mohamed-abdel-rahem-386125288](https://www.linkedin.com/in/mohamed-abdel-rahem-386125288) |
| **Email** | [mohamedar2002mail@gmail.com](mailto:mohamedar2002mail@gmail.com) |
| **WhatsApp** | [+20 115 261 9144](https://wa.me/201152619144) |
| **GitHub** | [github.com/Mohamed-Abdel-Rahem](https://github.com/Mohamed-Abdel-Rahem) |

<hr/>

<div align="center">
<sub>Designed with intent. Engineered with discipline.</sub>
</div>
