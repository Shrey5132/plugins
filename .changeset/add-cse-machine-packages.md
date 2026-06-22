---
"@sourceacademy/common-cse-machine": minor
"@sourceacademy/runner-cse-machine": minor
"@sourceacademy/web-cse-machine": minor
---

Add language-agnostic CSE machine plugin packages for the Conductor framework.

- `@sourceacademy/common-cse-machine`: shared protocol — channel ID, plugin IDs, and the `CseSnapshot` type hierarchy
- `@sourceacademy/runner-cse-machine`: runner-side plugin that serialises and sends CSE snapshots over the CSE channel
- `@sourceacademy/web-cse-machine`: host-side plugin that receives CSE snapshots and forwards them to the visualiser via `receiveSnapshots`
