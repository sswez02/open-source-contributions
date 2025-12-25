# Open Source Contributions

This repository highlights selected open-source contributions I’ve made,
with links to the upstream pull/merge requests and a short description
of the impact.

---

## KDE — KdeEcoTest

**Project:** KdeEcoTest (KDE Eco / FEEP)  
**Language:** Python  
**Platform:** GitLab (invent.kde.org)

### Contribution
- Clarified platform support in README (GNU/Linux supported; Windows in progress)
- Documented known Windows issues (`dbus`, `win32_setctime`)
- Improved CLI UX by failing gracefully on Windows instead of crashing

### Upstream Merge Request
🔗 https://invent.kde.org/oreoluwa/kdeecotest/-/merge_requests/2

### Why it matters
This reduces onboarding friction for new contributors and users on Windows,
provides clear expectations around platform support, and replaces confusing
tracebacks with actionable error messages.

---
