---
name: Auto Label Issues
on:
  issues:
    types: [opened]
safe-outputs:
  update-issue: null
---

When a new issue is opened, read the issue title and body,
and add one of these labels: bug, question, enhancement.
Apply only ONE label based on the content.
