<h1 align="center">D4RK0N3</h1>

<p align="center">
  <b>Senior React Native Developer</b> · Kraków, Poland<br>
  Cross-platform apps for iOS, Android and Web — from the first commit to the store listing.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/zieba-piotr"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white"></a>
  <img alt="Location" src="https://img.shields.io/badge/Kraków,_PL-1a1a2e?style=flat-square&logo=googlemaps&logoColor=white">
  <img alt="Linux" src="https://img.shields.io/badge/Arch_Linux-1793D1?style=flat-square&logo=archlinux&logoColor=white">
</p>

---

### About

React Native developer with **6+ years** shipping web and mobile products. Currently the **sole mobile engineer** on a production Expo app released for iOS, Android and Web — responsible for its architecture, native layer and release process.

I go into native code when the SDK doesn't cover the requirement: iOS Live Activities, Android foreground services, Expo config plugins, patched native modules. Before mobile I spent several years on React, Three.js, Angular and WordPress/PHP — from interactive 3D product configurators to RPA automation.

I develop and ship both platforms from **Arch Linux**.

### What I'm building

**Aula** — an EdTech app that records lectures and returns AI teaching analysis. Built from the first commit, live on both app stores.

- **Native background recording** — iOS ActivityKit Live Activity on the lock screen and Dynamic Island, Android foreground-service notification, wired up through custom Expo config plugins
- **Offline-first** — recordings written to disk before upload, reconciled on load, re-sent on foreground, with a claim registry that prevents double sends
- **AI pipeline** — speech-to-text and analysis over REST with async queue polling plus an SSE stream, feeding auto-generated quizzes, mind maps and teacher dashboards
- **Meeting bot** — records Zoom, Meet and Teams calls server-side
- **Performance** — replaced unbounded parallel fan-outs with a measured permit pool, and narrowed a high-frequency mic signal that was re-rendering the whole recording screen down to the two components that display it
- **Release engineering** — Android built locally through the Gradle/JDK toolchain, iOS submitted to TestFlight on EAS macOS workers, GitHub Actions CI for typecheck, lint and dependency audit

### Tech

**Mobile** &nbsp;
![React Native](https://img.shields.io/badge/React_Native-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Expo](https://img.shields.io/badge/Expo-000020?style=flat-square&logo=expo&logoColor=white)
![Reanimated](https://img.shields.io/badge/Reanimated-001A72?style=flat-square&logo=react&logoColor=white)
![ActivityKit](https://img.shields.io/badge/ActivityKit-FA7343?style=flat-square&logo=swift&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white)

**Web** &nbsp;
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white)
![Three.js](https://img.shields.io/badge/Three.js-000000?style=flat-square&logo=three.js&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

**Backend & services** &nbsp;
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![RevenueCat](https://img.shields.io/badge/RevenueCat-F25A5A?style=flat-square&logo=revenuecat&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)
![Sentry](https://img.shields.io/badge/Sentry-362D59?style=flat-square&logo=sentry&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)

**Tooling** &nbsp;
![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Bun](https://img.shields.io/badge/Bun-000000?style=flat-square&logo=bun&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white)
![Neovim](https://img.shields.io/badge/Neovim-57A143?style=flat-square&logo=neovim&logoColor=white)

### Selected projects

| Project | What it is | Stack |
| --- | --- | --- |
| [**WhatAShape**](https://github.com/D4RK0N3dev/WhatAShape) | Mobile reflex arcade game — adaptive difficulty, hardware-accelerated animations, combo scoring | React Native, TypeScript, Reanimated, SVG |
| **Aula** <sub>private</sub> | EdTech lecture recording with AI analysis — iOS, Android and Web | Expo, TypeScript, Supabase, RevenueCat |
| **CEDH.io Client** <sub>private</sub> | Desktop client for a deck-building community | Rust |
| **GSC SEO Checker** <sub>private</sub> | Google Search Console reporting and audit tool | Python |
| **omarchy-setup** <sub>private</sub> | My Arch Linux / Hyprland workstation configuration | Lua, Bash |

> Most of my work lives in private and client repositories, so the contribution graph says more than the repo list does.

<p align="center">
  <img height="165" alt="GitHub stats" src="https://github-readme-stats.vercel.app/api?username=D4RK0N3dev&show_icons=true&hide_border=true&count_private=true&include_all_commits=true&theme=github_dark&bg_color=00000000&title_color=58a6ff&text_color=c9d1d9&icon_color=58a6ff">
  <img height="165" alt="Top languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=D4RK0N3dev&layout=compact&hide_border=true&langs_count=8&theme=github_dark&bg_color=00000000&title_color=58a6ff&text_color=c9d1d9">
</p>

### Background

Engineer's degree in Computer Science, WSEI Kraków (in progress) · Certiport IT Specialist — JavaScript and Network Security · Polish (native), English (C1), German (A2)
