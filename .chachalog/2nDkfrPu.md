---
# Allowed version bumps: patch, minor, major
quick-find: major
---

Changed the module to require app-shell 4.0 or later. Its interface never loaded on an earlier app-shell; the module now refuses to start there instead. Upgrade app-shell to 4.0 or later before you upgrade this module.
