<p align="center">
  <img src="nightdevs_combo.gif" width="80%" alt="NightDevs Combo pixel art banner" />
</p>

<h1 align="center">Hi, I'm Fabio 👋</h1>
<p align="center"><b>Associate Manager · Business Analytics & BI</b><br>
I turn data and business processes into analytics solutions that people actually use.</p>

<p align="center">
  <a href="https://www.linkedin.com/in/fabio-cuccaro-91007487"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:whisperer100@gmail.com"><img src="https://img.shields.io/badge/Email-F27D0D?style=for-the-badge&logo=gmail&logoColor=white" /></a>
</p>

## 🙋 About me

- 💼 **Associate Manager at Avanade** (since 2024): I lead projects and teams delivering analysis and development for data solutions
- 📊 8+ years in Business Analytics, from ETL developer to project lead, always focused on BI, data integration and reporting
- 🎓 MSc in Management and Information Technology (University of Salerno) and BSc in Computer Science (University of Molise)
- 📍 Based in Bologna, Italy
- 🛠️ On the side, I build tools for Linux/Hyprland ([Omarchy](https://omarchy.org)) and tinker with Lua/LÖVE, Strudel and Power BI
- 🤖 I use Claude Code in my development workflow

**Core skills:** Project Management · ETL · Data Modeling · Team Coordination

## 🧰 Tech I work with

**Data & BI**

<p align="center">
<img src="https://learn.microsoft.com/en-us/fabric/media/fabric-icon.png" height="48" alt="Fabric" title="Fabric" />
<img src="https://upload.wikimedia.org/wikipedia/commons/c/cf/New_Power_BI_Logo.svg?utm_source=commons.wikimedia.org&utm_campaign=index&utm_content=original" height="48" alt="Power BI" title="Power BI" />
<img src="https://go-skill-icons.vercel.app/api/icons?i=excel" height="48" alt="Excel" title="Excel" />
<img src="https://go-skill-icons.vercel.app/api/icons?i=sqlserver" height="48" alt="SQL Server" title="SQL Server" />
</p>

**Development & tooling**

<p align="center">
<img src="https://go-skill-icons.vercel.app/api/icons?i=python" height="48" alt="Python" title="Python" />
<img src="https://go-skill-icons.vercel.app/api/icons?i=docker" height="48" alt="Docker" title="Docker" />
<img src="https://go-skill-icons.vercel.app/api/icons?i=githubactions" height="48" alt="GitHub Actions" title="GitHub Actions" />
<img src="https://go-skill-icons.vercel.app/api/icons?i=git" height="48" alt="Git" title="Git" />
<img src="https://go-skill-icons.vercel.app/api/icons?i=github" height="48" alt="GitHub" title="GitHub" />
<img src="https://go-skill-icons.vercel.app/api/icons?i=vscode" height="48" alt="VS Code" title="VS Code" />
<img src="https://go-skill-icons.vercel.app/api/icons?i=claude" height="48" alt="Claude" title="Claude" />
<img src="https://upload.wikimedia.org/wikipedia/commons/2/2c/Visual_Studio_Icon_2022.svg" height="48" alt="Visual Studio" title="Visual Studio" />
<br/><br/>
<a href="https://omarchy.org"><img src="https://omarchy.org/brand/omarchy-wordmark.png" height="28" alt="Omarchy" title="Omarchy" /></a>
</p>

## 🏅 Certifications

<a href="https://learn.microsoft.com/en-us/users/fabiocuccaro-9952/credentials/ea86da04af07f9ca">
  <img src="https://vaclavryska.com/wp-content/uploads/2021/03/microsoft-certified-associate-badge.svg" height="48" align="left" hspace="12" alt="Microsoft Certified: Associate badge" title="Microsoft Certified: Fabric Data Engineer Associate (DP-700)" />
</a>

**Microsoft Certified: Fabric Data Engineer Associate** (DP-700)<br>
Microsoft · Jan 2025 · [Verify credential](https://learn.microsoft.com/en-us/users/fabiocuccaro-9952/credentials/ea86da04af07f9ca)

<br clear="left"/>

## 📌 Projects

- **Personal health analytics** (private repo): an end-to-end BI pipeline on my own Oura Ring data. A Python ETL pulls the Oura API v2 (OAuth2) twice a day, keeps the raw JSON and writes one Parquet file per data type; it runs on my NAS from a Docker image that GitHub Actions builds on every push. On top of it: a web dashboard built with Observable Framework and DuckDB-WASM (queries run in the browser) and a Power BI report with a shared date table. The data never leaves my home network.

- **[omarchy_monitor_manager](https://github.com/FabioCuccaro/omarchy_monitor_manager)**: An Omarchy shell plugin to arrange your displays visually: drag monitors into place with snapping, pick resolution, scale, rotation, VRR and mirroring, try the layout live with an automatic rollback, then save

- **[omarchy_touchpad_manager](https://github.com/FabioCuccaro/omarchy_touchpad_manager)**: Touchpad settings panel for the Omarchy shell: live-tune scrolling, pointer, clicking, gestures and per-app scroll speed on Hyprland, with profiles.

- **[ugreen_tailscale](https://github.com/FabioCuccaro/ugreen_tailscale)**: Reach your UGREEN NAS (UGOS) from anywhere with Tailscale in Docker: no open ports, no Quick access or UGREENlink. Step-by-step guide and ready-to-paste compose files.

- **[ugreen_immich](https://github.com/FabioCuccaro/ugreen_immich)**: Self-host Immich, a Google Photos alternative, on a UGREEN NAS (UGOS). It reads the photos the UGREEN app already syncs, without copying them, and is reachable only through Tailscale. Ready-to-paste compose and a step-by-step guide.

## 🏠 Home lab

A UGREEN DXP2800 NAS running UGOS, with every service as a Docker Project and nothing exposed to the internet: from outside, everything goes through Tailscale.

- 🔐 **Tailscale**: private access to the NAS from phone and laptops, with no open ports ([guide and compose](https://github.com/FabioCuccaro/ugreen_tailscale))
- 🔔 **ntfy**: self-hosted push notifications to my phone, login required, reachable only over Tailscale ([guide](https://github.com/FabioCuccaro/ugreen_tailscale/blob/main/docs/ntfy.md))
- ❤️ **Health dashboard**: the Oura Ring pipeline and dashboard described in Projects (private repo)
- 📸 **Immich**: a self-hosted Google Photos replacement, reading the phone backup the NAS already syncs ([guide and compose](https://github.com/FabioCuccaro/ugreen_immich))
- 🏋️ **openGym**: a self-hosted workout log with passkey login, served over HTTPS only inside the tailnet
- 🎬 **Jellyfin** (replacing Plex, with Intel QuickSync hardware transcoding) and **qBittorrent** for media
- 🧭 **Homepage**: one page linking every service with a live up/down dot, laid out two per row so it fits a phone screen and installed as an app
