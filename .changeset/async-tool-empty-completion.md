---
'@livekit/agents': patch
---

Record final completion when an async tool returns null or undefined after reporting progress, and track the follow-up reply as a task so session runs can finish. Cancel pending replies during shutdown so foreground work cannot leave the run waiting after close.
