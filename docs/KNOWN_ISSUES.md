\# 🐞 Known Issues – Ember Relay



\_Last updated: July 7, 2025\_



---



\### 🔴 SBA-001: Audio Upload Failure (aka "Stupid Bitch Ass")

\- \*\*Status:\*\* Broken

\- \*\*Description:\*\* Audio upload feature is currently throwing errors or failing to complete.

\- \*\*Suspected Cause:\*\* Likely CORS config issue or incorrect file MIME type.

\- \*\*Fix Plan:\*\* Test multiple audio formats, inspect preflight responses.

\- \*\*Priority:\*\* 🔥🔥🔥



---



\### 🟡 WX-002: Weather API Backend Issue

\- \*\*Status:\*\* Unknown error

\- \*\*Description:\*\* Weather data not loading; backend call seems to fail silently.

\- \*\*Suspected Cause:\*\* Missing API key or environmental variable misconfig.

\- \*\*Fix Plan:\*\* Log `os.getenv()` values, check for KeyErrors or NameErrors.

\- \*\*Priority:\*\* 🔥



---



\### ⚪️ INFRA-003: Render Deployment Slowness

\- \*\*Status:\*\* Known limitation

\- \*\*Description:\*\* Backend/frontend cold-start lag due to Render free-tier.

\- \*\*Fix Plan:\*\* Accept pain until revenue, then upgrade infra.

\- \*\*Priority:\*\* 😒



