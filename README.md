\# Ember Relay – Known Issues Log



\[!\[License: MIT](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)

\[!\[PRs Welcome: Nope](https://img.shields.io/badge/PRs-Welcome--nope-red.svg)](https://www.wolvesandfirestudio.com)



This repository documents known bugs, quirks, and development bottlenecks for the Ember Relay investigative tool. It's a living document to help track technical debt, identify recurring problems, and systematize debugging over time.



\## 📁 Structure



\- `docs/KNOWN\_ISSUES.md` – The main list of bugs, breakages, and odd behaviors

\- `.gitignore` – Prevents sensitive or unnecessary files (e.g. logs, envs, venv) from being committed



\## 🚨 Current Known Issues



Check \[KNOWN\_ISSUES.md](docs/KNOWN\_ISSUES.md) for the full breakdown.



Examples include:

\- Audio upload failures (CORS/preflight issues)

\- Weather API backend errors (possibly missing or incorrect env vars)

\- Render slowness due to free-tier hosting



\## ✏️ Contributions



This repo is for internal use only. Please do not submit pull requests unless requested. We break our own shit, thanks.



\## 🛠️ Roadmap Ideas



\- Auto-log known exceptions and errors into this repo

\- Markdown viewer inside Ember Relay for internal QA/devs

\- Sync common client-side errors to this repo on build



---



© 2025 Wolves \& Fire Studio — \[wolvesandfirestudio.com](https://www.wolvesandfirestudio.com)



---



\## 🧾 License



This project is licensed under the \[MIT License](LICENSE).



