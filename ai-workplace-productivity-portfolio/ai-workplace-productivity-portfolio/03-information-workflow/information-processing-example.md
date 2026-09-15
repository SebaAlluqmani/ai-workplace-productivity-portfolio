# Information Processing Workflow — Crowded Inbox to Decision-Ready Brief

Scenario: I returned from two days out of office to 30 unread messages about the TaskFlow product launch, with a hard deadline five days away and at least one decision nobody had made yet. I needed to turn this scattered information into something my director could act on immediately.

## Task Used
**Summarizing + Prioritizing** (of the five information tasks: summarizing, extracting, synthesizing, restructuring, prioritizing).

## 1. Input (Raw, Unstructured)
> Mon: v2 shipped to 40% of users. Bug in checkout flow found, fixed by EOD. Second bug in notifications still open. Tues: marketing wants full rollout by Fri, said it's 'already basically decided.' Eng lead flagged server capacity might not hold at 100%, needs to check. Wed: client emailed again asking about Q3 pricing — third time, no one has replied. Someone mentioned in chat we might be over budget on the contractor line but nobody confirmed. Meeting Thurs AM to decide rollout timing.

## 2. Prompt Used
> **Context:** I have three days of scattered project updates from email and chat about a product launch. **Action:** Summarize the current state, separate confirmed facts from unconfirmed risks, and flag the one decision nobody has made yet. **Role:** Act as a project coordinator preparing a brief for a director. **Expected Output:** 5 short bullet points, no invented details — mark anything unclear as "Not Specified."

## 3. AI Output
- Rollout: v2 live for 40% of users; checkout bug fixed, notifications bug still open.
- Push for full rollout Friday from marketing, but server capacity at 100% load is **unconfirmed**.
- Client has asked about Q3 pricing three times with no reply — **Not Specified** why no one responded.
- Possible contractor budget overrun — **Not Specified**, unconfirmed in chat only.
- **Decision needed:** rollout timing, to be discussed Thursday AM — no owner has made this call yet.

## 4. Human Review
I checked this against the original messages and confirmed nothing was invented: the "Not Specified" tags accurately reflect where the source material was ambiguous, and the one pending decision (rollout timing) matched what I remembered from the thread.

## 5. Final Structured Output (Decision-Ready Brief)
**Status:** v2 partially live (40%); one bug fixed, one open (notifications).
**Blocker:** Full rollout push for Friday depends on unconfirmed server capacity at 100% load.
**Outstanding:** Client pricing question unanswered for the third time; possible contractor budget overrun unconfirmed.
**Decision needed today:** Confirm server capacity before committing to Friday, or set a fallback date at Thursday's meeting.

---
**Note:** No detail was invented anywhere in this process — every gap in the original notes was tagged **Not Specified** rather than guessed.
