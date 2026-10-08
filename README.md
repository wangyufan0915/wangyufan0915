<div align="center">

# 王禹凡 · Wang Yufan

**微电子科学与工程（拟）· 北航国际创新学院 中法未来科技学院 2026 级**

`C / Python / JavaScript` · 文本信息抽取 · 个人自动化工具

[![Email](https://img.shields.io/badge/Email-1703018565%40qq.com-1f6feb?style=flat-square&logo=maildotru&logoColor=white)](mailto:1703018565@qq.com)
![Location](https://img.shields.io/badge/Hangzhou-China-1f6feb?style=flat-square&logo=googlemaps&logoColor=white)
![Status](https://img.shields.io/badge/Open%20to-Internship%20(2027)-2ea043?style=flat-square)

</div>

---

## About

I'm a first-year undergraduate at **Beihang University · International Innovation Institute (Hangzhou)**, heading into **Microelectronics Science and Engineering**.

What I care about: the layer where computation meets the physical world — devices, chips, and the tools that make them designable. Right now I'm building the fundamentals, and I like my studying to produce something that runs.

- 🔭 **Now** — Preparing for the major track (微电子科学与工程), aiming to join the **spintronics (自旋芯片) lab** as an undergraduate researcher
- 🌱 **Learning** — C, 高等数学, 大学物理, and French (targeting **DELF B2**)
- 🛠️ **Building** — Small, sharp tools that turn messy real-world text into structured data
- 💬 **Languages** — 中文 (native) · English (technical reading) · Français (intermediate)

---

## Featured Projects

### 📬 Campus Notice Digest
`JavaScript · Node.js` — [repo](#)

WeChat / QQ / DingTalk are where Chinese universities push every notice, and none of them offers a usable API. So notices arrive as copy-pasted text and get lost.

This tool takes those raw dumps and produces one clean daily Markdown digest plus an `.ics` deadline calendar:

- **Rule-based extraction** across 3 platform export formats (timestamps, senders, group headers, forwarded blocks)
- **Deadline parsing** for Chinese date expressions — `9月25日前`, `本周三`, `今晚22:00`, `截止时间 9月28日 24:00`
- **Cross-platform deduplication** via character-bigram Jaccard similarity, so one notice forwarded to three apps shows up once
- **Whitelist filtering** by group with `contains` / `prefix*` / `/regex/` rules, plus candidate-group auto-scanning
- **Outputs** `YYYY-MM-DD.md` digest, `YYYY-MM-DD.ics` reminders, and a JSON history store

```
node run.js                 # digest today's inbox
node run.js --groups --keep # show which groups were parsed, no writes
node run.js --scan-groups   # list candidate group names to whitelist
```

> Design note: I deliberately did **not** automate message capture. Reading WeChat/QQ message stores requires protocol reverse-engineering, breaks on every client update, and risks account bans. The tool stays honest: a human exports text in seconds, the machine does everything after that.

### 🗓️ Timetable → Calendar
`Python` — [repo](#)

A ~100-line script that encodes a university timetable (course, room, teacher, week range, weekday, period) and emits a standard `.ics` file. All 14 periods are mapped to real clock times and expanded per teaching week, so the whole semester imports into any calendar app in one tap. Built because the official schedule was only available as a PDF grid.

---

## Toolkit

![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Markdown](https://img.shields.io/badge/Markdown-000000?style=flat-square&logo=markdown&logoColor=white)
![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=flat-square&logo=latex&logoColor=white)

**Also comfortable with** — PowerShell automation, `python-docx` / `openpyxl` document generation, PDF text & image extraction, data validation scripts

---

## GitHub

<div align="center">

<img height="160" src="https://github-readme-stats.vercel.app/api?username=YOUR_USERNAME&show_icons=true&hide_border=true&theme=transparent" />
<img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR_USERNAME&layout=compact&hide_border=true&theme=transparent" />

</div>

---

<div align="center">
<sub>Currently reading about device physics · Always happy to talk about tooling, semiconductors, or 中法双语学习</sub>
</div>
