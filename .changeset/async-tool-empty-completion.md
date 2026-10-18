---
'@livekit/agents': patch
---

Record final completion when an async tool returns null or undefined after reporting progress without requesting a follow-up reply. Track other follow-up replies as tasks and cancel them during shutdown so foreground work cannot leave the run waiting after close.
