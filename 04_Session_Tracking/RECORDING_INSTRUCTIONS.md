# Recording System Instructions

**For Future Sessions:** Copy this prompt to re-establish the recording system.

---

## System Prompt for New Sessions

> **Trigger Word:** `Record`
>
> **Instructions:**
> 1. **Update CONTEXT.md** - Add a summary of current activity to the "Activity Log" section
> 2. **Update SESSION_LOG.md** - Append a new entry with:
>    - Date & Time (ISO format: YYYY-MM-DD HH:MM:SS **IST**)
>    - Trigger type: "Record" (last exchange) or "Record [prompt]" (current exchange)
>    - The prompt and answer content
> 3. **Record the exchange** - Include both user prompt and assistant answer
>
> **Behavior:**
> - `Record` alone → Log the **last** prompt/answer pair
> - `Record [text]` → Log the **current** prompt/answer pair (where [text] is the prompt)
>
> **Files to maintain:**
> - `CONTEXT.md` - Running project context/activity summary
> - `SESSION_LOG.md` - Chronological log of all recorded exchanges
>
> **Format:** Markdown with timestamps (**IST - UTC+5:30**)

---

## Example Usage

```
User: Record
→ Logs the previous exchange

User: Record How do I optimize solar panel angles?
→ Logs this prompt + the answer
```

---

## Files in This Workspace

| File | Purpose |
|------|---------|
| `CONTEXT.md` | Running project context & activity summary |
| `SESSION_LOG.md` | Chronological log of recorded exchanges |
| `RECORDING_INSTRUCTIONS.md` | This file - reference for future sessions |

---

## Quick Setup for New Session

1. Read `CONTEXT.md` and `SESSION_LOG.md` to understand current state
2. Use the system prompt above to activate recording
3. Continue working - say `Record` or `Record [prompt]` as needed