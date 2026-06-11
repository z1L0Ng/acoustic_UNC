# Project Brief

Last updated: 2026-06-11

## Working Direction

Investigate whether acoustic signals can support assessment or detection of respiratory-related diseases, in collaboration with a UNC Hospital faculty member.

## Known Context

- The project is currently at the preliminary planning and feasibility stage.
- Some students have already completed an initial literature review.
- The initial goal is to build preliminary results before a possible later stage involving clinical deployment and validation.
- Detailed scope and expectations still need to be clarified with Jingping Nie and the clinical collaborator.

## Near-Term Objective

Prepare for the next meeting with a concrete, evidence-grounded plan that identifies feasible problem formulations, available datasets, baseline methods, clinical/data constraints, and immediate next actions.

## Project-Management Workflow

Before the next meeting, the project-management pages in Notion should remain unchanged. Current work is preliminary review only.

After each weekly meeting:

1. Zilong updates the meeting record with the transcript, naming the page by that meeting time.
2. Codex reads the meeting record and extracts decisions, action items, open questions, dependencies, and risks.
3. Codex creates or updates the next weekly work plan, naming the page by the next meeting time.
4. Before the next meeting, Codex prepares the meeting report, also naming the page by the next meeting time.

Full workflow: `docs/project_management/weekly_meeting_workflow.md`.

## Preliminary Deliverables Before Next Meeting

1. Summarize the email thread and extract decisions, assumptions, open questions, and promised materials.
2. Convert the student literature review into a structured source matrix.
3. Identify public or de-identified datasets that could support preliminary results.
4. Propose 2-3 feasible task formulations with expected inputs, labels, baselines, metrics, and risks.
5. Prepare a one-page meeting brief with recommended next steps and questions for the clinical collaborator.

## Candidate Research Framings

These are placeholders to validate against the literature and collaborator needs:

- Disease detection or screening from cough, breathing, speech, or lung-sound recordings.
- Respiratory status or severity estimation rather than binary diagnosis.
- Monitoring disease progression, exacerbation, or treatment response over time.
- Triage-support acoustic biomarkers for a specific clinical population.

## Key Questions To Resolve

- Which respiratory disease or clinical condition matters most for the collaborator?
- What acoustic modality is realistic: cough, speech, breathing, auscultation, ambient phone audio, or another source?
- Is the intended task screening, diagnosis support, severity scoring, monitoring, or triage?
- What data and labels are available now, and what requires IRB/data-use approval?
- What baseline would count as a credible preliminary result before deployment?
- What validation standard would the clinical collaborator consider meaningful?

## Working Assumptions

- Initial technical work should use public or explicitly de-identified data.
- No patient-level data should be committed to this repository.
- Clinical deployment, prospective collection, and hospital validation require explicit institutional approval and collaborator sign-off.
