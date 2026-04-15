<!-- ═══════════════════════════════════════════════════════════════ -->
<!--                        HEADER SECTION                         -->
<!-- ═══════════════════════════════════════════════════════════════ -->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=180&section=header&text=Mohamed%20Abdel-Rahem&fontSize=42&fontColor=ffffff&animation=twinkling&fontAlignY=36&desc=Flutter%20Mobile%20Engineer%20%7C%20System%20Architecture&descAlignY=58&descSize=16&descColor=ff6b6b" width="100%"/>

<img src="https://github.com/Mohamed-Abdel-Rahem.png" width="120" style="border-radius:50%; margin-top:-20px;" />

<h3>
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=18&duration=3000&pause=1000&color=FF6B6B&center=true&vCenter=true&width=500&lines=Flutter+Engineer+Focused+on+Scalable+Systems;Clean+Architecture+%7C+SOLID+Principles;Offline-First+%7C+Real-Time+Sync+Specialist" />
</h3>

</div>

<br/>

<!-- ═══════════════════════════════════════════════════════════════ -->
<!--                        ABOUT SECTION                          -->
<!-- ═══════════════════════════════════════════════════════════════ -->

## 🧭 About Me

```dart
class MohamedAbdelRahem {

  final focus = "Scalable Mobile Systems & Offline-First Architectures";

  final philosophy = [
    "Build systems that survive, not just apps that run.",
    "Architecture is a long-term investment, not a shortcut.",
    "UI is replaceable. Business logic is not."
  ];

  final mindset = "Junior by title. Senior by engineering discipline.";
}
```

> Self-taught Flutter engineer focused on **system design, architecture, and long-term maintainability**.  
> I approach mobile development as a **distributed system problem**, not just UI engineering.

---

<!-- ═══════════════════════════════════════════════════════════════ -->
<!--                     TECHNICAL STACK                           -->
<!-- ═══════════════════════════════════════════════════════════════ -->

## ⚡ Technical Stack

<div align="center">

### Core
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)

### State Management
![Riverpod](https://img.shields.io/badge/Riverpod-00B4D8?style=for-the-badge)
![BLoC](https://img.shields.io/badge/BLoC-FF6B35?style=for-the-badge)

### Backend & Data
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge)

### APIs
![REST API](https://img.shields.io/badge/REST-FF6B6B?style=for-the-badge)
![PostgREST](https://img.shields.io/badge/PostgREST-336791?style=for-the-badge)

### Media & Performance
![Cloudinary](https://img.shields.io/badge/Cloudinary-3448C5?style=for-the-badge&logo=cloudinary&logoColor=white)

### Tooling
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge)
![GitHub](https://img.shields.io/badge/GitHub-171515?style=for-the-badge)
![VSCode](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge)

</div>

---

<!-- ═══════════════════════════════════════════════════════════════ -->
<!--           SYSTEM DESIGN & ENGINEERING COMPETENCIES            -->
<!-- ═══════════════════════════════════════════════════════════════ -->

## 🏗️ System Design & Engineering Competencies

> *How I think. How I build. How systems survive.*

### 🔄 Data Flow Architecture

```text
        UI (Flutter)
            │
     ViewModel (Riverpod)
            │
       Use Cases (Domain)
            │
     Repository Interface
      /              \
Local (SQLite)   Remote (Supabase / Firebase)
      │              │
  Source of Truth   Sync Layer
```

- Repository Pattern abstracts **multi-source data orchestration**
- Local database acts as **primary source of truth**
- Remote (Supabase/Firebase) used for **sync & distribution**
- Conflict resolution handled at repository level

---

### 📶 Offline-First Strategy

| Layer | Responsibility |
|------|--------------|
| SQLite | Persistent local cache (authoritative) |
| Repository | Sync coordination + conflict resolution |
| Network | Eventual consistency (not required for UX) |

---

### ⚡ State Orchestration (Riverpod)

- Code Generation (`@riverpod`) for compile-time safety  
- Global state graph → **single source of truth**  
- Separation:
  - UI → Reactive only  
  - ViewModel → State transitions  
  - Domain → Pure logic  

---

### 🖼️ Media Performance (Cloudinary)

| Technique | Impact |
|----------|--------|
| Dynamic Transformations | Resize & compress images per device |
| CDN Delivery | Reduced latency globally |
| Lazy Loading | Prevent UI blocking |
| Format Optimization | WebP/AVIF auto-delivery |

---

### 🧱 Architecture Discipline

- Clean Architecture (strict boundaries)  
- Dependency Inversion (no framework leakage)  
- Feature-first modular structure  
- Testable use-case driven logic  

---

<!-- ═══════════════════════════════════════════════════════════════ -->
<!--                    ACHIEVEMENTS & EDUCATION                   -->
<!-- ═══════════════════════════════════════════════════════════════ -->

## 🏅 Achievements & Education

<div align="center">

![DEPI](https://img.shields.io/badge/🏆%20DEPI-Advanced%20Flutter%20Track-ff6b6b?style=for-the-badge&labelColor=0d1117)
![October 6 University](https://img.shields.io/badge/🎓%20October%206%20University-Computer%20Science-1f6feb?style=for-the-badge&labelColor=0d1117)

</div>

---

<!-- ═══════════════════════════════════════════════════════════════ -->
<!--                      GITHUB METRICS                           -->
<!-- ═══════════════════════════════════════════════════════════════ -->

## 📊 GitHub Metrics

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=Mohamed-Abdel-Rahem&show_icons=true&theme=radical&include_all_commits=true&count_private=true&cache_seconds=86400&hide_border=true&bg_color=0d1117&title_color=ff6b6b&icon_color=ff6b6b&text_color=c9d1d9"/>

<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Mohamed-Abdel-Rahem&layout=compact&theme=radical&count_private=true&cache_seconds=86400&hide_border=true&bg_color=0d1117&title_color=ff6b6b&text_color=c9d1d9"/>

</div>

<div align="center">

<img width="70%" src="https://streak-stats.demolab.com?user=Mohamed-Abdel-Rahem&theme=radical&hide_border=true&background=0d1117&ring=ff6b6b&fire=ff6b6b&currStreakLabel=ff6b6b"/>

</div>

---

<!-- ═══════════════════════════════════════════════════════════════ -->
<!--                   ENGINEERING PHILOSOPHY                      -->
<!-- ═══════════════════════════════════════════════════════════════ -->

## 💡 Engineering Philosophy

```
ISOLATE → Business logic is independent of frameworks
REACT   → State flows as streams, not snapshots
SURVIVE → Offline-first is the default, not a feature
```

---

<!-- ═══════════════════════════════════════════════════════════════ -->
<!--                     CONTACT SECTION                           -->
<!-- ═══════════════════════════════════════════════════════════════ -->

## 📬 Contact

<div align="center">

| Platform | Link |
|---------|------|
| 💼 LinkedIn | https://linkedin.com/in/mohamed-abdel-rahem-386125288 |
| 📧 Email | mohamedar2002mail@gmail.com |
| 💬 WhatsApp | https://wa.me/201152619144 |
| 🐙 GitHub | https://github.com/Mohamed-Abdel-Rahem |

</div>

---

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer" width="100%"/>

<div align="center">
  <sub>Engineered for scale. Designed for longevity.</sub>
</div>
