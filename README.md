# Healthcare App

> Reference architecture for patient scheduling — React Native, Expo & Firebase.

[![React Native](https://img.shields.io/badge/React_Native-Expo-61DAFB?style=flat-square&logo=react&logoColor=black)](https://reactnative.dev)
[![Firebase](https://img.shields.io/badge/Firebase-Auth_+_DB-FFCA28?style=flat-square&logo=firebase&logoColor=black)](https://firebase.google.com)
[![Healthcare](https://img.shields.io/badge/Domain-Healthcare-059669?style=flat-square)](https://github.com/jonathasribeiro/healthcare-app)
[![TypeScript](https://img.shields.io/badge/TypeScript-Ready-3178C6?style=flat-square&logo=typescript&logoColor=white)](https://www.typescriptlang.org)

---

## Overview

Reference architecture for a **healthcare patient scheduling** application, inspired by enterprise platforms serving **500k+ users** (QSaúde, Notredame Intermédica).

This repository documents the planned stack and domain model. Production healthcare code is maintained in private repositories.

---

## Planned Stack

| Layer | Technology |
|-------|------------|
| Mobile | React Native + Expo |
| Auth & Data | Firebase Authentication + Firestore |
| Language | TypeScript |
| Offline | Firebase offline persistence |
| Push | Firebase Cloud Messaging |

---

## Domain Context

Based on real-world healthcare experience:

| Project | Scale | Focus |
|---------|-------|-------|
| **QSaúde** | 500k+ users | Patient booking, iOS/Android |
| **Notredame** | Enterprise | Claims dashboards, GCP migration |

### Key capabilities (planned)

- Patient appointment booking
- Provider availability calendar
- Push notifications for reminders
- Offline-first mobile UX
- HIPAA-aware architecture patterns

---

## Architecture (reference)

```mermaid
flowchart TB
  subgraph Mobile
    A[React Native + Expo]
  end
  subgraph Firebase
    B[Authentication]
    C[Firestore]
    D[Cloud Messaging]
  end
  A --> B
  A --> C
  A --> D
```

---

## Related Projects

- [expo-firebase-reactnative](https://github.com/jonathasribeiro/expo-firebase-reactnative) — Firebase mobile patterns
- [FRONTEND](https://github.com/jonathasribeiro/FRONTEND) — Enterprise dashboard patterns

---

## Author

**Jonathas Ribeiro** — Senior Fullstack Engineer  
8+ years in healthcare (QSaúde, Notredame Intermédica)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jonathasribeiroreal)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/jonathasribeiro)

---

> Production scheduling systems built for iOS, Android, and web — contact via LinkedIn for case studies.
