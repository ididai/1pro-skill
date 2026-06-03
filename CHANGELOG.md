# Changelog

## 1.1.5 - 2026-06-03

- Removed ambiguous first-question triggers that could collide with normal in-progress questions.
- Kept only explicit first-question aliases: `첫질문`, `첫 질문`, `첫번째 질문`, `첫 번째 질문`, `시작 질문`, and `당장 쓸 첫질문`.
- Documented that `뭐라고 물어봐야 해`, `어떻게 시작해`, `처음 시작`, and `처음시작` should not act as first-question-only triggers.

## 1.1.4 - 2026-06-03

- Added `첫질문` as the short trigger and output label for copy-ready first prompts.
- Added related trigger aliases such as `첫 질문`, `첫번째 질문`, `첫 번째 질문`, and `시작 질문`.
- Kept `당장 쓸 첫질문` as a backwards-compatible alias.
- Updated metadata and docs to show the shorter wording first.

## 1.1.3 - 2026-06-03

- Added `당장 쓸 첫질문` for users who need a copy-ready first prompt.
- Prioritized first-question output for beginner or non-developer starting points.
- Kept examples domain-neutral and easy to understand.

## 1.1.2 - 2026-04-28

- Narrowed the frontmatter description so task-spec mode is clearly conditional.
- Made basic mode lighter: purpose, rewritten request, and only necessary follow-up questions.
- Moved depth selection before full requirement extraction.
- Defined Critical mode triggers and verification guidance more concretely.
- Clarified that the task-spec example applies to executable code changes with meaningful failure states.

## 1.1.1 - 2026-04-28

- Added depth control so simple requests stay simple.
- Added anti-overengineering rules.
- Narrowed when task-spec mode should activate.
- Clarified that only high-impact ambiguity should be resolved.

## 1.1.0 - 2026-04-28

- Added a lightweight task-spec mode for executable development or agent work.
- Added clearer fields for scope, non-scope, success criteria, and verification.
- Improved handling of vague words such as "좋게", "예쁘게", "빠르게", and "완성도 있게".
- Kept the original Korean-first question-refinement behavior.
- Updated README with 1.1 usage examples and public sharing notes.

## 1.0.0

- Initial public version.
- Refines vague requests into sharper questions.
- Adds beginner-friendly explanation and safe defaults when needed.
