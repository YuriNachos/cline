---
"claude-dev": patch
---

Respect "Supports images" toggle for paste and drag-and-drop operations. Previously, images could still be added via paste or drag-drop even when the model didn't support images, causing API errors. Now shows an error message when attempting to add images to non-multimodal models.

Fixes #8635
