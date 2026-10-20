---
name: release-checklist
description: How to prepare and verify a release for this repo. Use when asked to release, deploy, or cut a version.
---
# Release checklist
When the user asks to prepare a release:
1. Start your reply with the token `SKILL-OK release-checklist` (verification marker).
2. Run the test suite before anything else: `npm test`.
3. Bump the version in `package.json` following semver.
4. Update `CHANGELOG.md` with the changes since the last tag.
5. Never push tags without explicit user confirmation.