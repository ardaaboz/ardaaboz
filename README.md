# Talha Arda Boz

**Web developer who ships and maintains production software.** Based in Izmir, Turkey. Open to junior full-stack and web developer roles, remote or on-site in Izmir and Istanbul.

Four applications I built run daily at a retail business: an in-store price lookup system, end-of-day cash reconciliation against the company ERP, a replacement for the Windows print dialog, and a cash-flow tracker. I specified, tested, deployed and maintain all of them, built with [Claude Code](https://claude.com/claude-code). Each ships with an automated test suite, a signed Windows installer and auto-update.

- Currently: freelance web development, and learning to work fluently inside the TypeScript and React codebases I have shipped
- Contact: [LinkedIn](https://linkedin.com/in/arda-boz) · [Freelance profile](https://bionluk.com/ardaaboz) · ardaboz4317@gmail.com

## Production software

Running in daily use at a real business.

| Project | Stack | What it does |
|---|---|---|
| **Fiyat Gör**, in-store price lookup *(source private)* | Go, MSSQL, PWA, Android/Kotlin | One Go service feeds wall-mounted kiosk terminals on the shop floor, an installable PWA for staff phones, and a JSON API. The kiosk auto-starts on boot with no focusable element, so the on-screen keyboard can never appear and barcode scanner input is captured directly. PIN and token auth, per-IP rate limiting, error masking. |
| **Günsonu**, end-of-day cash reconciliation *(source private)* | Electron, React, TypeScript, SQLite, MSSQL | End-of-day cash and card reconciliation. Reads each till from the company ERP over read-only queries and computes variances against counted cash. Replaced a spreadsheet process and corrected three accounting errors in it. ERP credentials encrypted with Windows DPAPI. |
| **[Kolay Yazdır](https://github.com/ardaaboz/kolay-yazdir)**, Windows printing application | C#, .NET, WPF | Replaces the Windows print dialog at a retail counter. Mixed image, PDF, Word and Excel batches, N-up layout, duplex edge selection, live preview. The layout engine is a pure function with no Windows dependency, shared by preview and printer, so the two cannot diverge. 29 test files. |
| **[Mali Takip](https://github.com/ardaaboz/Mali-Takip)**, offline cash-flow tracker | Electron, React, TypeScript, SQLite | Offline cash-flow and card-settlement tracker. Models per-bank settlement delay and commission so funds appear as available only on the day they clear. Settings are versioned per record, so changing a bank's terms never rewrites history. |

## Other projects

- **[Ev Nöbetçisi](https://github.com/ardaaboz/ev-nobetcisi)**, rental listing watcher (Python, 185 commits). Polls three property sites every five minutes, fuzzy-deduplicates across sources, pushes matches to Telegram. Tests are written specifically to catch generated content drifting from fact: the build fails if any unverified claim reaches an outgoing message template.
- **[Sooji](https://github.com/ardaaboz/sooji)**, accessible therapy reference app (JavaScript, Android). Korean hand-therapy reference built for a user with retinitis pigmentosa. Narrow central column, no screen-edge controls, high contrast. Ships as a 229 KB signed APK that requests no network permission and as a single offline HTML file. Every claim is shown with its source; the app makes no diagnostic or curative claims.
- **[Finance Manager](https://github.com/ardaaboz/finance-manager)** (Java, Spring Boot, Spring Security, JPA): bilingual finance application with authentication, recurring bill tracking and budget visualization over a RESTful API.
- **[Earthquake Network for Streamers](https://github.com/ardaaboz/earthquake-network-for-streamers)** (Node.js, Upstash Redis, Vercel): OBS overlay pushing live earthquake alerts to a stream.

## Client work

Sites built and shipped for clients. Code is private; these are the live deployments.

- **[evtoptancisi.com](https://evtoptancisi.com)**: product catalog for a wholesale distributor. Custom WordPress theme, with all 405 products and images imported through an automation script so the owner can manage the catalog without a developer.
- **[laraotolastik.com](https://laraotolastik.com)**: rebuild for a tire company. Fixed mobile responsiveness, modernized an outdated design, added four-language support.
- **[nveee.org](https://nveee.org)**: WordPress development for a US nonprofit, including migration to the new site.
- **[arc-ambalaj.netlify.app](https://arc-ambalaj.netlify.app)**: corporate site proposal for a packaging company.

## Skills

**Professional, day to day:** JavaScript, HTML5, CSS3, responsive design, performance optimization, WordPress, Elementor, Git

**Academic foundation:** Java (Spring Boot, Spring Security, JPA), Python, SQL, MySQL, C, C++, RESTful API design, OOP design patterns, data structures

**Shipped to production with Claude Code:** TypeScript, React, Electron, Go, C#/.NET, WPF, Dart/Flutter, Kotlin/Android, MSSQL, SQLite, PWAs

**Testing and delivery:** Vitest, React Testing Library, pytest, dotnet test, flutter test, Go testing, GitHub Actions, semantic versioning, signed installers with auto-update

## Education

**Associate of Science, Computer Programming and Analysis**, Valencia College, Orlando, FL (2024 to 2025). GPA 3.80, President's List.

Coursework repositories: [Intro Programming](https://github.com/ardaaboz/cop-1000-intro-programming), [C](https://github.com/ardaaboz/cop-2200c-c-programming), [C++](https://github.com/ardaaboz/cop-2224c-cpp-programming), [Java](https://github.com/ardaaboz/cop-2800c-java-programming), [Advanced Java](https://github.com/ardaaboz/cop-2805c-advanced-java-programming), [Scripting Languages](https://github.com/ardaaboz/cop-2830c-scripting-languages), [Web Development](https://github.com/ardaaboz/web-development-coursework), [Java Learning Journey](https://github.com/ardaaboz/java-learning-journey).
