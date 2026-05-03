# Safe AI — GitHub Ready Staging

This folder is a sanitized staging area for public GitHub uploads.

Rules:
- Include only publish-safe artifacts.
- Exclude secrets, tokens, credentials, private logs, and sensitive notes.
- Add incremental exports here as projects mature.

Current status:
- Empty staging scaffold created.

## Prepublish Safety Check
Run before any GitHub push:

```bash
cd "/home/james/openclaw-workspace/Safe AI/github-ready"
./prepublish_check.sh
```
