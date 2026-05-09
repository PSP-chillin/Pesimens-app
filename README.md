<p align="center">
  <img src="App_logos/pesimens_logo.jpeg" alt="PESiMENs Logo" width="150" height="150" style="border-radius: 20px;" />
</p>

<h1 align="center">PESiMENs</h1>
<p align="center"><strong>The Ultimate Campus Super-App for PES University Students</strong></p>
<p align="center"><a href="https://pesimens.app">pesimens.app</a></p>

<p align="center">
  <img src="https://img.shields.io/badge/React-18.2-61DAFB?logo=react&logoColor=white" alt="React" />
  <img src="https://img.shields.io/badge/Fastify-4.25-000000?logo=fastify&logoColor=white" alt="Fastify" />
  <img src="https://img.shields.io/badge/TypeScript-5.3-3178C6?logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Supabase-PostgreSQL-3FCF8E?logo=supabase&logoColor=white" alt="Supabase" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-4.2-06B6D4?logo=tailwindcss&logoColor=white" alt="Tailwind" />
  <img src="https://img.shields.io/badge/PWA-Enabled-5A0FC8?logo=pwa&logoColor=white" alt="PWA" />
  <img src="https://img.shields.io/badge/License-Proprietary-red" alt="License" />
</p>

<p align="center">
  <strong>Author & Maintainer:</strong> Darshan P Pawar<br/>
  <a href="https://github.com/DarshanPawar7">GitHub: @DarshanPawar7</a> •
  <a href="mailto:darshanpawarworks@gmail.com">Email: darshanpawarworks@gmail.com</a> •
  <a href="https://linkedin.com/in/darshanpawar7">LinkedIn: Darshan P Pawar</a>
</p>

---

## 📖 Table of Contents

- [Overview](#-overview)
- [Features](#-features)
- [Security](#-security)
- [Privacy](#-privacy)
- [FAQ](#-faq)
- [Screenshots](#-screenshots)
- [What This Repo Does Not Include](#-what-this-repo-does-not-include)
- [License](#-license)

---

## 🌟 Overview

PESiMENs is a closed-source student platform built to bring the most useful campus experiences into one polished app. It combines learning tools, community features, career tools, entertainment, and platform services into a single product. This public repo is intentionally limited to transparency, branding, and security information only. It does not expose the full application source or operational secrets.

### At A Glance

| Item | Details |
|------|---------|
| **Product** | PESiMENs |
| **Website** | [pesimens.app](https://pesimens.app) |
| **Positioning** | Proprietary, internally maintained platform |
| **Primary Value** | A polished all-in-one student experience |
| **Public Repo Goal** | Showcase product scope, trust, and security posture |

### What Makes It Stand Out

- Clean, student-first design with a premium feel.
- Broad coverage across learning, community, career, and entertainment.
- Athena AI for quick help and navigation.
- Installable PWA experience with modern app behavior.

---

## ✨ Features

PESiMENs brings multiple student workflows into one experience. The feature set below is organized by user journey so the product is easy to scan and evaluate.

### 📚 Learning & Productivity

PESiMENs is designed to make everyday workflows feel simple, fast, and connected.

| Feature | What it does |
|---------|--------------|
| **PYQ Feed** | Browse, save, and organize past-year questions. |
| **AI Insights** | Turn activity into useful summaries and trends. |
| **Study Materials** | Discover and buy useful student resources. |
| **Analytics Dashboard** | View key trends in a clean visual format. |
| **Planner** | Keep schedules and important dates in one place. |

### 👥 Social & Community

The app includes social features that help students connect and engage.

| Feature | What it does |
|---------|--------------|
| **Confessions** | Anonymous posting with voting, comments, and moderation. |
| **Stories** | Temporary posts that expire automatically. |
| **Messages** | Real-time direct messaging with read-state support. |
| **People Directory** | Search profiles and build connections. |
| **Clubs** | Discover clubs and manage membership. |

### 💼 Career & Placements

PESiMENs also supports placement and mentorship workflows.

| Feature | What it does |
|---------|--------------|
| **Placement Portal** | Share and browse interview experiences, rounds, and outcomes. |
| **Mentor Marketplace** | Book mentorship sessions in a streamlined flow. |
| **Resume Reviews** | Get feedback and improve your profile. |
| **Job Search** | Discover external jobs in one place. |

### 🎮 Entertainment

The games hub mixes live titles with upcoming party-style games.

| Feature | What it does |
|---------|--------------|
| **Chess** | Play and track progress with a polished chess experience. |
| **Ludo** | Jump into multiplayer-style Ludo sessions and invites. |
| **PES Bluff** | A fast bluff-and-guess party game. |
| **PES Drawl** | A draw-and-guess game for friends. |

### 🔧 Platform

| Feature | What it does |
|---------|--------------|
| **PWA** | Installable on mobile and desktop with offline-friendly behavior. |
| **Push Notifications** | Real-time alerts for relevant app activity. |
| **Admin Panel** | Moderation and operational tools in one place. |
| **Athena AI** | Gemini and Groq-powered assistant for quick help and navigation. |
| **Explore Page** | A public discovery surface for visitors. |

---

## ✨ Highlights

- Premium, unified experience for PES University students.
- Built for discovery, engagement, and everyday utility.
- Athena AI adds fast, intelligent support across the app.
- Designed to feel modern, polished, and installable.

---

## ✅ Security Snapshot

This section gives a quick public summary of the platform’s security posture.

| Area | Summary |
|------|---------|
| **Authentication** | Sensitive session handling is protected and not documented with internal implementation detail. |
| **Secrets** | No real passwords, tokens, or service credentials are stored in this repo. |
| **Validation** | User input is validated before it reaches protected app flows. |
| **Browser Safety** | Security headers, origin controls, and CSRF protections are used where relevant. |
| **Rate Limiting** | Abuse-prone features are limited to reduce spam and automated misuse. |
| **Content Safety** | Moderation and admin review protect user-generated content surfaces. |
| **AI Safety** | Athena AI uses managed backend providers and is protected from direct secret exposure. |
| **Payments** | Payment-related configuration stays outside the public repo. |

### Security Principles

- Keep sensitive values in environment variables or a secret manager.
- Treat authentication, payments, and AI provider access as private operational concerns.
- Avoid committing uploads, logs, and generated data.
- Use moderation and audit trails for user-facing content and admin actions.

---

## 🔒 Security

Security is a core part of the product design. The public repo describes the controls at a high level without exposing implementation secrets.

### Authentication & Session Security

- Authentication is separated from the public documentation and handled by the live application.
- The platform supports secure sign-in via PESU Academy credentials, Google Auth, and passwordless magic links.
- User sessions use short-lived access behavior and longer-lived refresh behavior to reduce token exposure.
- Token rotation and revocation are used to limit reuse of compromised sessions.
- Sensitive login flows are treated as protected operations and are not documented with step-by-step exploit detail.

### Data Protection

- Sensitive credentials are not stored in the public repo.
- Example environment files contain placeholders only.
- Secret values are injected through deployment-time environment variables or a secret manager.
- Production data, service keys, JWT signing values, and payment secrets are never meant to be published here.

### Application Security

- Input validation is used to reduce injection and malformed-request risk.
- Security headers and origin controls are used to limit browser-based abuse.
- CSRF protections are used for state-changing browser requests.
- Rate limiting helps reduce abuse of login, AI, messaging, and code-execution features.
- Moderation and approval flows are used for user-generated content that can affect other users.

### AI Security

- Athena AI uses Gemini and Groq as backend providers.
- AI requests are controlled through validation and abuse-prevention measures.
- Model access is treated as a managed service, not a public client-side secret.
- The public repo should not reveal provider keys, routing details, or internal prompt logic.

### Payments & Marketplace Safety

- Payment-related values are handled outside the public repo.
- Marketplace, mentoring, and purchase flows are treated as sensitive business logic.
- Public documentation should describe the existence of these features, not reveal internal processing details.

### Abuse Prevention

- Content moderation is used for user submissions.
- Audit trails are maintained for administrative actions.
- Platform features that can be abused are rate-limited and reviewed.
- The app uses a closed-source model so operational safeguards can remain private.

### Public Security Disclosure

PESiMENs follows a privacy-first and security-conscious approach. At a high level, the live product may collect:

- account and profile details needed to operate the app
- community activity created inside the platform
- basic usage and security telemetry needed for reliability and abuse prevention

PESiMENs does not collect institutional academic records such as grades, marksheets, or exam results unless a separate feature or policy says otherwise.

Authentication is handled by the live application and uses protected session flows, while sensitive credentials are never stored in this public repository.

Data should be protected in transit with HTTPS, and sensitive operational secrets should remain encrypted or stored outside the repo in deployment-time environment variables or a secret manager.

Third-party services used by the product may include hosting, authentication, storage, notifications, AI providers, payments, and other managed infrastructure services required to run the app.

Security issues should be reported through the maintainer contact listed above or through the project’s official support channel.

---

## 🔐 Privacy

- No passwords are committed to this repository.
- No live user data is included.
- No real API keys, tokens, or service credentials are present.
- Example configuration files are only templates.
- Uploaded files, logs, and build outputs should remain outside version control.

If you want to publish a privacy policy, it should explain:

- what user data is collected
- why it is collected
- where it is stored
- how long it is retained
- who can access it
- how users can request deletion or support

---

## ❓ FAQ

Common public questions about PESiMENs.

| Question | Answer |
|----------|--------|
| **What is PESiMENs?** | A private, polished campus platform for PES University students. |
| **Is this repo open source?** | No. It is a public-facing product and trust page, not the source code. |
| **Does this repo contain secrets?** | No. Only public docs and placeholder examples belong here. |
| **Where is the app live?** | The product site is [pesimens.app](https://pesimens.app). |
| **What is Athena AI?** | A built-in assistant powered by Gemini and Groq. |
| **Can I rebuild the app from this repo?** | No. It is intentionally minimal and non-reconstructive. |

---

## 🖼 Screenshots

Add polished product visuals, feature callouts, and launch-ready screenshots in the [screenshots](screenshots/README.md) folder.

Suggested image types:

- hero/home screen
- Athena AI
- feed or activity view
- planner or overview view
- admin or moderation view
- mobile install view

---

## 🚫 What This Repo Does Not Include

This public repo intentionally excludes:

- application source code
- backend logic
- database schema details
- secret keys and credentials
- internal debug logs
- generated files and uploads
- operational playbooks that would expose private business logic

---

## 📄 License

**Proprietary and closed-source**. All rights reserved. This codebase is not open source and is maintained as a commercial product.

---

<p align="center">
  Built for PES University students with a strong focus on product quality, privacy, and security.
</p>
