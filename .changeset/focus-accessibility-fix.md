---
"claude-dev": patch
---

Fix keyboard accessibility by adding focus indicators to action buttons. The buttons now show a visible outline when navigating with Tab key, using `:focus-visible` to show focus only for keyboard navigation, not mouse clicks.

Fixes #8675
