# Russian Writing Prompt Assets

This repository contains prompt and schema assets for a coaching-style Russian writing correction workflow.

## Added behavior
- Coaching-oriented correction package in strict JSON (`prompts/correction_coach_ru.md`).
- Dedicated rewrite review loop in Russian (`prompts/rewrite_feedback_ru.md`).
- Machine-validated strict schema for correction output (`schemas/correction_response.schema.json`).

## Integration notes
1. Use `correction_coach_ru.md` as the instruction for the first correction pass.
2. Validate model output against `correction_response.schema.json`.
3. After learner rewrite, use `rewrite_feedback_ru.md` to produce concise progress feedback.
