# Weekly Meeting Workflow

Last updated: 2026-06-11

## Current Boundary

Before the next meeting, do not modify the Notion project-management pages. The current phase is preliminary review only: collect context, read the email thread, review the student literature-review materials, and prepare enough background for the meeting.

## Core Rule

Each weekly meeting time is the sprint boundary. Notion pages should be named by the meeting time they serve.

Use the actual meeting time when available. If the exact time is not known, use the meeting date first and fill in the time later.

Recommended naming pattern:

- `YYYY-MM-DD HH:MM - Meeting Record`
- `YYYY-MM-DD HH:MM - Work Plan`
- `YYYY-MM-DD HH:MM - Meeting Report`

If only the date is known:

- `YYYY-MM-DD - Meeting Record`
- `YYYY-MM-DD - Work Plan`
- `YYYY-MM-DD - Meeting Report`

## Artifact Roles

### Weekly Meeting Record

Created or updated after the meeting.

Owner input: Zilong adds the meeting transcript to the meeting record page named by that meeting time.

Codex role after transcript is available:

- Extract decisions, assumptions, open questions, and action items.
- Identify new constraints, promised materials, dependencies, and risks.
- Separate confirmed facts from speculative ideas.
- Preserve the transcript as source material and keep summaries traceable to it.

### Weekly Work Plan

Created after reviewing the latest meeting record.

Naming rule: name the work plan by the next meeting time, because it covers the work due before that next meeting.

Codex role:

- Convert the latest meeting record into a scoped plan for the next sprint.
- Define deliverables, owners, evidence needed, and blockers.
- Prioritize literature review, dataset search, baseline planning, clinical-scope clarification, or report writing based on the record.
- Keep the plan narrow enough to finish before the next meeting.

### Weekly Meeting Report

Prepared before the next meeting.

Naming rule: name the report by the upcoming meeting time, matching the work plan it reports against.

Codex role:

- Summarize completed work since the prior meeting.
- Report evidence gathered, literature findings, dataset feasibility, baseline proposals, and unresolved blockers.
- List decisions needed in the upcoming meeting.
- Keep the report collaborator-facing and concise.

## Sprint Loop

1. Meeting happens at time `T`.
2. Zilong updates `T - Meeting Record` with the transcript.
3. Codex reads `T - Meeting Record` and extracts decisions, action items, and open questions.
4. Codex creates or updates `T_next - Work Plan`, where `T_next` is the next scheduled meeting time.
5. Work proceeds during the sprint against `T_next - Work Plan`.
6. Before `T_next`, Codex prepares `T_next - Meeting Report`.
7. At `T_next`, Zilong adds the new transcript to `T_next - Meeting Record`.
8. Repeat the cycle.

## First Sprint Handling

Tomorrow's meeting is not yet the first sprint artifact. It is the setup point for the first sprint.

After tomorrow's meeting:

- Zilong adds the transcript to the meeting record named by tomorrow's actual meeting time.
- Codex extracts the meeting outcomes.
- Codex creates the first active work plan named by the next meeting time.
- Codex prepares the first report before that next meeting.

## Quality Bar

- Do not create Notion sprint pages before the relevant meeting boundary is confirmed.
- Do not invent meeting outcomes from pre-meeting assumptions.
- Do not store PHI, patient identifiers, raw clinical audio, private collaborator emails, or regulated clinical exports in Notion or Git.
- Keep every report claim grounded in the meeting record, literature matrix, research log, or a cited public source.

