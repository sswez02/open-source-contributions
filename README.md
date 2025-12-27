# Open Source Contributions

This repository highlights selected open-source contributions I’ve made,
with links to upstream merge requests and a brief summary of their impact.

---

## KDE — KdeEcoTest

**Project:** KdeEcoTest (KDE Eco / FEEP)  
**Language:** Python  
**Platform:** GitLab (invent.kde.org)

---

### Contribution 1 — Platform clarity & documentation

- Clarified platform support in the README (GNU/Linux supported; Windows in progress)
- Documented known Windows limitations (`dbus`, `win32_setctime`)
- Improved CLI behavior by failing gracefully on unsupported platforms instead of crashing
- Validated setup instructions by running the project end-to-end in a clean environment

**Upstream Merge Request**  
🔗 https://invent.kde.org/oreoluwa/kdeecotest/-/merge_requests/2

**Why it matters**  
This reduces onboarding friction for new users and contributors, sets clear
expectations around platform support, and replaces confusing runtime errors
with actionable messaging.

---

### Contribution 2 — Keyboard activity & input recording fixes

- Fixed keyboard activity recording not being flushed correctly into test scripts
- Corrected interaction between keyboard events and mouse click handling
- Ensured recorded key sequences are written consistently and in the correct order
- Tested fixes by recording real interaction scripts and validating output

**Upstream Merge Request**  
🔗 https://invent.kde.org/oreoluwa/kdeecotest/-/merge_requests/4

**Why it matters**  
KdeEcoTest relies on accurate input replay for reproducible energy measurements.
These fixes restore correct keyboard and click recording, making generated test
scripts reliable and usable for automated testing workflows.
