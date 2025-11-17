---
title: Emirates Driving Institute Student App
summary: React Native New Architecture build for onboarding, scheduling, payments, and notifications serving thousands of EDI learners across the UAE.
date: 2025-05-01
featured: true
tags:
  - React Native
  - New Architecture
  - Android
  - iOS
  - Redux
  - React Navigation
  - Hooks
links:
  - icon: hero/link
    name: App Store
    url: https://apple.co/3LAVM28
  - icon: hero/link
    name: Google Play
    url: https://bit.ly/4hwdTSW
---

I led the engineering team at **Brixio** responsible for rebuilding Emirates Driving Institute’s student-facing experience with the React Native New Architecture (TurboModules + Fabric). The rollout introduced:

- Modular enrollment flows with configurable licensing requirements per emirate.
- Realtime scheduling and rescheduling with .NET microservices and Firebase notifications.
- Centralized Redux Toolkit state that keeps business logic deterministic while supporting offline caching.

Release automation with Bitrise and GitHub Actions helped us sustain crash rates below 1% while shipping weekly builds. Driving instructors now have a direct line to students, and the operations team can update pricing, training packages, and class capacity without store re-submissions.
