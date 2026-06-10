---
"executor": patch
---

**Fix credential sharing for workspace connections**

Org-shared connections now resolve for every member of a workspace, not only the member who created them. Existing connections are migrated automatically; stored secrets are unaffected.
