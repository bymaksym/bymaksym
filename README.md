<div align="center">

<img src="assets/bymaksymdev-banner.png" alt="ByMaksymDev Labs — apps, open source, experiments" width="100%">

# Maksym Ostapenko

**Frontend Engineer** &nbsp;·&nbsp; Málaga, Spain

Angular applications for enterprise clients — and the tooling that keeps them fast.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-21262D?style=flat-square&logo=linkedin&logoColor=0A66C2)](https://es.linkedin.com/in/maksym-ostapenko-798228210)
[![npm](https://img.shields.io/badge/npm-21262D?style=flat-square&logo=npm&logoColor=CB3837)](https://www.npmjs.com/~bymaksym)
[![Discord](https://img.shields.io/badge/ByMaksymDev_Labs-21262D?style=flat-square&logo=discord&logoColor=5865F2)](https://discord.gg/ctDJjFF9yT)

</div>

---

### About

Frontend engineer building Angular applications for enterprise clients — from the first line
through to production, and keeping the older ones running. I also look after what surrounds them:
tests, CI/CD, automated releases and error monitoring, with Java and Spring Boot when the backend
needs a hand.

Outside work I build tools I actually use: **Loadline** tells you what each screen of a web app
really downloads, so you can fix it before it ships, and **Waypack** is an Android app for packing
by day, by bag and by person.

### Selected work

<p align="center">
  <a href="https://github.com/bymaksym/LoadLine"><img src="https://raw.githubusercontent.com/bymaksym/LoadLine/main/.github/banner.png?v=2" alt="Loadline" width="49%"></a>
  <a href="https://github.com/bymaksym/waypack"><img src="https://raw.githubusercontent.com/bymaksym/waypack/main/assets/banner.png?v=1.1" alt="Waypack" width="49%"></a>
</p>

#### [Loadline](https://github.com/bymaksym/LoadLine) &nbsp;·&nbsp; `@bymaksym/loadline`

[![npm](https://img.shields.io/npm/v/@bymaksym/loadline?style=flat-square&label=npm&labelColor=21262D&color=1F6FEB)](https://www.npmjs.com/package/@bymaksym/loadline)
[![CI](https://img.shields.io/github/actions/workflow/status/bymaksym/LoadLine/ci.yml?style=flat-square&label=CI&labelColor=21262D&color=1F6FEB)](https://github.com/bymaksym/LoadLine/actions/workflows/ci.yml)
[![license](https://img.shields.io/github/license/bymaksym/LoadLine?style=flat-square&labelColor=21262D&color=1F6FEB)](https://github.com/bymaksym/LoadLine/blob/main/LICENSE)

Bundle analysers report what each chunk weighs. Loadline reports what each **screen** costs: it walks the
import graph of your build, separates the bootstrap everyone downloads from the code a single route adds,
and counts how many round trips a screen takes to arrive.

One tool, two front doors — a single HTML page that runs offline in your browser, and a command for your
pipeline. Same code, same numbers. Zero runtime dependencies, nothing uploaded, nothing fetched.

```console
$ npx @bymaksym/loadline dist/app/browser
```

#### [Waypack](https://github.com/bymaksym/waypack) &nbsp;·&nbsp; Android

[![release](https://img.shields.io/github/v/release/bymaksym/waypack?style=flat-square&label=release&labelColor=21262D&color=2E6E68)](https://github.com/bymaksym/waypack/releases/latest)
[![Kotlin](https://img.shields.io/badge/Kotlin-21262D?style=flat-square&logo=kotlin&logoColor=7F52FF)](https://github.com/bymaksym/waypack)
[![Jetpack Compose](https://img.shields.io/badge/Jetpack_Compose-21262D?style=flat-square&logo=jetpackcompose&logoColor=4285F4)](https://github.com/bymaksym/waypack)

A packing and trip organizer: what to bring, by day, by bag and by person. Two checks instead of
one — *prepared* and *actually in the bag* — so what you found but left on the table still
shows up before you leave.

The domain is plain Kotlin Multiplatform, so it can travel to iOS without a rewrite, and it ships
in four languages from the first release.

### Stack

|                        |                                                                                                              |
| :--------------------- | :----------------------------------------------------------------------------------------------------------- |
| **Core**               | ![Angular](https://img.shields.io/badge/Angular-21262D?style=flat-square&logo=angular&logoColor=DD0031) ![TypeScript](https://img.shields.io/badge/TypeScript-21262D?style=flat-square&logo=typescript&logoColor=3178C6) ![RxJS](https://img.shields.io/badge/RxJS-21262D?style=flat-square&logo=reactivex&logoColor=B7178C) ![Ionic](https://img.shields.io/badge/Ionic-21262D?style=flat-square&logo=ionic&logoColor=3880FF) ![Sass](https://img.shields.io/badge/Sass-21262D?style=flat-square&logo=sass&logoColor=CC6699) |
| **Frontend**           | Signals · Standalone components · PrimeNG · Reactive Forms · REST APIs · Component library design               |
| **Quality & delivery** | GitLab CI/CD · Semantic Release · Sentry · ESLint · Stylelint · Prettier · Husky · commitlint · Renovate        |
| **Also**               | Kotlin · Jetpack Compose · Kotlin Multiplatform · Java · Spring Boot · React · Docker · Firebase             |
