---
"claude-dev": patch
---

Fix VSCode LM API BYOK provider model name trimming. When selecting models with names containing slashes (e.g., "anthropic/claude-3.5-sonnet"), the full family name is now preserved instead of being truncated at the first slash.

Fixes #6293
