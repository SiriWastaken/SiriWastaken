<p align="center">
<picture><source media="(prefers-color-scheme: dark)" srcset="./assets/header-dark.svg"><img src="./assets/header-light.svg" width="100%" alt="Still learning. Building as I go. I'm Sri, a high-school student who learns by building. Right now: learning Swift and SwiftUI, building Scouting Web 2027, and heading into open source."/></picture>
</p>

I like software that has to cope with messy conditions: tablets syncing through a network box we built ourselves, or a benchmark that has to back up its own numbers. I started with Java and now mostly write TypeScript.

[**Portfolio**](https://siriwastaken.github.io) · [Repositories](https://github.com/SiriWastaken?tab=repositories) · [DMOJ](https://dmoj.ca/user/SiriWastaken)

## Work

<table>
<tr>
<td width="50%" valign="top">
<a href="https://github.com/SiriWastaken/reactN-vs-Java-android-testbench"><picture><source media="(prefers-color-scheme: dark)" srcset="./assets/benchmark-dark.svg"><img src="./assets/benchmark-light.svg" width="100%" alt="A React Native app and a native Java app run the same scripted workload through one harness. Runs with a wrong checksum are dropped, and the rest feed latency, CPU and memory statistics."/></picture></a><br/>
<a href="https://github.com/SiriWastaken/reactN-vs-Java-android-testbench"><b>Scouting App Benchmark</b></a> &nbsp;<sub>completed</sub><br/>
I ran our scouting app against a native Java version on the actual tablet to decide whether a rewrite was worth it. Native Java was faster on taps (32 vs 75 ms median) and used far less CPU and memory; React Native had smoother frames under load. One tablet, three runs per cell.<br/>
<code>React Native</code> <code>Java</code> <code>Android</code> <code>Python</code>
</td>
<td width="50%" valign="top">
<a href="https://github.com/SiriWastaken/sift"><picture><source media="(prefers-color-scheme: dark)" srcset="./assets/sift-dark.svg"><img src="./assets/sift-light.svg" width="100%" alt="SIFT reads a local project with four commands: inspect, check, doctor and diff, and says unknown for anything it cannot back with evidence."/></picture></a><br/>
<a href="https://github.com/SiriWastaken/sift"><b>SIFT</b></a> &nbsp;<sub>in development</sub><br/>
A command-line tool that inspects, health-checks and diffs the project you're in, and says <code>unknown</code> instead of guessing. It only runs commands it knows are right for the detected Maven, Gradle, Node or Python project, and never goes through a shell.<br/>
<code>Java</code> <code>Maven</code> <code>JUnit</code>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<a href="https://github.com/SiriWastaken/Claudeium"><picture><source media="(prefers-color-scheme: dark)" srcset="./assets/claudeium-dark.svg"><img src="./assets/claudeium-light.svg" width="100%" alt="A task is verified only after a recorded passing check. Editing the covered files afterwards marks the evidence stale."/></picture></a><br/>
<a href="https://github.com/SiriWastaken/Claudeium"><b>Claudeium</b></a> &nbsp;<sub>in development</sub><br/>
A task ledger for AI-assisted coding where nothing counts as done until a check has passed against the files it covers. Evidence is tied to a fingerprint of those files, so later edits mark it <code>STALE</code>.<br/>
<code>JavaScript</code> <code>Node.js</code> <code>Claude Code plugin</code>
</td>
<td width="50%" valign="top">
<picture><source media="(prefers-color-scheme: dark)" srcset="./assets/scouting-2026-dark.svg"><img src="./assets/scouting-2026-light.svg" width="100%" alt="Scout tablets write to local Couchbase Lite, which syncs through the Toaster network box and Sync Gateway. The analysis tabs read that data."/></picture><br/>
<b>Scouting App 2026</b> &nbsp;<sub>completed · private repo</sub><br/>
The Android app our six scouts use to record every robot in a match. It works offline and syncs across the team's tablets. A match predictor built on the synced data picked the winning alliance 84.7% of the time at the 2026 Ontario Provincial Championships (Technology Division).<br/>
<code>TypeScript</code> <code>React Native</code> <code>Expo</code> <code>Couchbase Lite</code>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<picture><source media="(prefers-color-scheme: dark)" srcset="./assets/scouting-web-dark.svg"><img src="./assets/scouting-web-light.svg" width="100%" alt="The server relays Sync Gateway changes over a session-checked WebSocket to open dashboards, which resume after a reconnect."/></picture><br/>
<b>Scouting Web 2027</b> &nbsp;<sub>in development · private repo</sub><br/>
A Next.js dashboard for the same data, with its own sign-in, roles enforced on the server, live updates over WebSockets and an admin panel. Google and Apple sign-in are written directly against OpenID Connect, with no auth library.<br/>
<code>TypeScript</code> <code>Next.js</code> <code>WebSockets</code> <code>Playwright</code>
</td>
<td width="50%" valign="top">
<picture><source media="(prefers-color-scheme: dark)" srcset="./assets/design-app-dark.svg"><img src="./assets/design-app-light.svg" width="100%" alt="Each server action passes through authenticate, rate limit, validate, authorize, the handler and an audit step."/></picture><br/>
<b>Design App</b> &nbsp;<sub>in development · private repo</sub><br/>
A phone-first web app for logging robot prototype tests with photos and video. Entry drafts autosave offline to IndexedDB, and every server action goes through one authenticate, validate, authorize and audit pipeline.<br/>
<code>TypeScript</code> <code>Next.js</code> <code>Couchbase</code> <code>Auth.js</code> <code>Zod</code>
</td>
</tr>
</table>

More: [Who Wants to Be a Millionaire](https://github.com/SiriWastaken/Who-Wants-To-Be-a-Millionaire) (my ICS3U final, a quiz game in Java Swing with every screen drawn by hand), [610 Match Sim](https://github.com/SiriWastaken/610-Match-Sim) (an FRC match simulator with an authoritative 60 Hz server), [Wii-Fit-Board](https://github.com/SiriWastaken/Wii-Fit-Board) (a Wii Balance Board turned into a Bluetooth scale), [claude-needs-input](https://github.com/SiriWastaken/claude-needs-input) and [Contradictions](https://github.com/SiriWastaken/Contradictions).

## Stack

<table>
<tr>
<td width="50%" valign="top">
<sub><b>LANGUAGES</b></sub><br/>
<picture><source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=java&theme=dark"><img src="https://skillicons.dev/icons?i=java&theme=light" height="52" alt="Java"/></picture>
<picture><source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=ts&theme=dark"><img src="https://skillicons.dev/icons?i=ts&theme=light" height="52" alt="TypeScript"/></picture><br/>
<sub>Java and TypeScript most. Learning Swift and SwiftUI; C# just starting.</sub>
</td>
<td width="50%" valign="top">
<sub><b>FRONTEND</b></sub><br/>
<picture><source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=react&theme=dark"><img src="https://skillicons.dev/icons?i=react&theme=light" height="40" alt="React"/></picture>
<picture><source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=nextjs&theme=dark"><img src="https://skillicons.dev/icons?i=nextjs&theme=light" height="40" alt="Next.js"/></picture><br/>
<sub>React Native for the 2026 scouting app, Next.js for the web.</sub>
</td>
</tr>
<tr>
<td valign="top">
<sub><b>TOOLS AND PLATFORM</b></sub><br/>
<picture><source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=git&theme=dark"><img src="https://skillicons.dev/icons?i=git&theme=light" height="40" alt="Git"/></picture>
<picture><source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=github&theme=dark"><img src="https://skillicons.dev/icons?i=github&theme=light" height="40" alt="GitHub"/></picture>
<picture><source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=vercel&theme=dark"><img src="https://skillicons.dev/icons?i=vercel&theme=light" height="40" alt="Vercel"/></picture><br/>
<sub>Claude Code as my day-to-day coding assistant.</sub>
</td>
<td valign="top">
<sub><b>LIBRARIES AND DATA</b></sub><br/>
<picture><source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=tailwind&theme=dark"><img src="https://skillicons.dev/icons?i=tailwind&theme=light" height="40" alt="Tailwind CSS"/></picture><br/>
<sub>Couchbase Lite and Sync Gateway, Expo, NativeWind, Playwright.</sub>
</td>
</tr>
</table>

## On GitHub

<p>
<picture><source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=SiriWastaken&show_icons=true&hide_border=true&disable_animations=true&bg_color=1c1c1e&title_color=2997ff&text_color=a1a1a6&icon_color=2997ff"><img src="https://github-readme-stats.vercel.app/api?username=SiriWastaken&show_icons=true&hide_border=true&disable_animations=true&bg_color=f5f5f7&title_color=0066cc&text_color=6e6e73&icon_color=0066cc" width="49%" alt="GitHub statistics"/></picture>
<picture><source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=SiriWastaken&layout=compact&langs_count=6&hide_border=true&disable_animations=true&bg_color=1c1c1e&title_color=2997ff&text_color=a1a1a6&icon_color=2997ff"><img src="https://github-readme-stats.vercel.app/api/top-langs/?username=SiriWastaken&layout=compact&langs_count=6&hide_border=true&disable_animations=true&bg_color=f5f5f7&title_color=0066cc&text_color=6e6e73&icon_color=0066cc" width="49%" alt="GitHub most used languages by bytes of code"/></picture>
</p>

<sub>The language bars count bytes of code in public repos. They say nothing about skill.</sub>
