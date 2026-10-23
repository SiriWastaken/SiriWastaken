<p align="center">
  <img src="./assets/header.svg" width="100%" alt="Sri Ganty. Three layers of my work: robotics projects (scouting, match sim, Wii board), the systems under them (sync, a 60 Hz tick, HID) and developer tools (SIFT, Claudeium, plugins)."/>
</p>

Student developer on FRC Team 610, mostly writing Java and TypeScript. I build scouting software, a match simulator, and command-line tools.

[**Portfolio**](https://siriwastaken.github.io) · [Repositories](https://github.com/SiriWastaken?tab=repositories) · [DMOJ](https://dmoj.ca/user/SiriWastaken)

## Projects

<table>
<tr>
<td colspan="2" valign="top">
<img src="./assets/diagram-scouting.svg" width="100%" alt="Scout tablets store match data locally in Couchbase Lite, then sync through a Toaster network box and Sync Gateway to Couchbase, which feeds a Next.js analysis dashboard."/><br/>
<b>610 Scouting</b> &nbsp;<sub>private repos · active</sub><br/>
The Android app and web dashboard Team 610 uses to scout events. Match data is stored locally in Couchbase Lite, synced to Couchbase, and analyzed as team averages, box plots and strategy views.<br/>
<sub>One annotated <code>DataClass.kt</code> declares every scouted field, and the screens, saved documents and resets follow from it. The web side enforces five roles on the server and ships with unit, security, contract and e2e suites.</sub><br/>
<code>Kotlin</code> <code>Jetpack Compose</code> <code>Java</code> <code>Couchbase</code> <code>Next.js</code> <code>TypeScript</code>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<a href="https://github.com/SiriWastaken/610-Match-Sim"><img src="./assets/diagram-match-sim.svg" width="100%" alt="A browser sends validated input over WebSocket to an authoritative server that runs a fixed 60 Hz tick and sends state snapshots back."/></a><br/>
<a href="https://github.com/SiriWastaken/610-Match-Sim"><b>610 Match Sim</b></a> &nbsp;<sub>active</sub><br/>
A browser FRC match simulator. The server is authoritative: a fixed 60 Hz tick owns movement, game pieces and match state, and clients only send validated input.<br/>
<code>TypeScript</code> <code>Next.js</code> <code>WebSockets</code>
</td>
<td width="50%" valign="top">
<a href="https://github.com/SiriWastaken/sift"><img src="./assets/diagram-sift.svg" width="100%" alt="SIFT reads a local project with four commands: inspect, check, doctor and diff, and marks anything it cannot back with evidence as unknown."/></a><br/>
<a href="https://github.com/SiriWastaken/sift"><b>SIFT</b></a> &nbsp;<sub>in progress</sub><br/>
A local-first CLI that tells you what a project is, whether it looks healthy, and what changed. No network or accounts, and anything it can't back with evidence is reported as <code>unknown</code> instead of guessed.<br/>
<code>Java 17</code> <code>Maven</code>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<a href="https://github.com/SiriWastaken/Wii-Fit-Board"><img src="./assets/diagram-wii-board.svg" width="100%" alt="The scale cycles through ZEROING, READY, MEASURING and DONE. MEASURING can end in FAILED. Stepping off the board returns to READY."/></a><br/>
<a href="https://github.com/SiriWastaken/Wii-Fit-Board"><b>Wii-Fit-Board</b></a> &nbsp;<sub>experiment</sub><br/>
Turns a Wii Balance Board into a Bluetooth scale, with factory calibration, tare with drift tracking and a weighing state machine. Hardware validation is still pending.<br/>
<code>Java</code> <code>HID</code>
</td>
<td width="50%" valign="top">
<a href="https://github.com/SiriWastaken/Claudeium"><img src="./assets/diagram-claudeium.svg" width="100%" alt="A task becomes verified only after a recorded passing check. Editing the file afterwards marks the evidence stale. A verified result can be handed off to another agent."/></a><br/>
<a href="https://github.com/SiriWastaken/Claudeium"><b>Claudeium</b></a> &nbsp;<sub>active</sub><br/>
A verification layer for AI coding agents. A task counts as verified only after a recorded passing check, and later edits to the file mark that evidence stale.<br/>
<code>Node.js</code> <code>Claude Code plugin</code>
</td>
</tr>
</table>

Also: **610 Design App** (private; a mobile-first PWA for logging prototype tests with photos and video, on Next.js and Couchbase), [claude-needs-input](https://github.com/SiriWastaken/claude-needs-input) (a Claude Code plugin that flags when the agent is waiting on you), [Contradictions](https://github.com/SiriWastaken/Contradictions) (a Roblox logic game in Luau), and the [portfolio site](https://github.com/SiriWastaken/siriwastaken.github.io) itself.

## Stack

<table>
<tr>
<td width="50%" valign="top">
<sub><b>LANGUAGES</b></sub><br/>
<img src="https://skillicons.dev/icons?i=java,ts" height="52" alt="Java, TypeScript"/>
<img src="https://skillicons.dev/icons?i=kotlin,js,lua,bash" height="40" alt="Kotlin, JavaScript, Luau, shell"/><br/>
<sub>Java and TypeScript most.</sub>
</td>
<td width="50%" valign="top">
<sub><b>APPLICATIONS</b></sub><br/>
<img src="https://skillicons.dev/icons?i=react,nextjs,tailwind" height="40" alt="React, Next.js, Tailwind CSS"/><br/>
<sub>Jetpack Compose for Android; React Native in the previous scouting app.</sub>
</td>
</tr>
<tr>
<td valign="top">
<sub><b>BACKEND AND DATA</b></sub><br/>
<img src="https://skillicons.dev/icons?i=nodejs" height="40" alt="Node.js"/><br/>
<sub>Couchbase (server and Lite), WebSockets, Auth.js.</sub>
</td>
<td valign="top">
<sub><b>TOOLING</b></sub><br/>
<img src="https://skillicons.dev/icons?i=git,github,maven,gradle,idea,vscode,vitest" height="40" alt="Git, GitHub, Maven, Gradle, IntelliJ IDEA, VS Code, Vitest"/><br/>
<sub>Playwright for e2e tests.</sub>
</td>
</tr>
</table>

## On GitHub

<p>
  <img src="https://github-readme-stats.vercel.app/api?username=SiriWastaken&show_icons=true&hide_border=true&disable_animations=true&bg_color=0d1117&title_color=4c9a76&icon_color=388bfd&text_color=8b949e" width="49%" alt="GitHub stats"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=SiriWastaken&layout=compact&hide_border=true&disable_animations=true&langs_count=6&bg_color=0d1117&title_color=4c9a76&text_color=8b949e" width="49%" alt="Most used languages by bytes of code"/>
</p>

<p align="center">
  <a href="https://siriwastaken.github.io">Portfolio</a> &nbsp;·&nbsp;
  <a href="https://github.com/SiriWastaken?tab=repositories">Repositories</a> &nbsp;·&nbsp;
  <a href="https://dmoj.ca/user/SiriWastaken">DMOJ</a>
</p>
