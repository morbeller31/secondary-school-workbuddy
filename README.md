# Secondary School WorkBuddy

A reusable Codex skill for supporting a neurodivergent secondary-school learner with academic work, English language and writing, executive functioning, and learning-related social or emotional barriers.

The skill separates two rhythms:

- daily academic support that follows current schoolwork;
- a weekly development review that proposes no more than one or two functional targets.

Within daily academic support, it uses three modes:

- **Independent Mode:** the learner completes a reasonable batch without unnecessary prompting;
- **Checking Mode:** WorkBuddy reviews completed work, classifies issues, and skips explanations for correct responses;
- **Teaching Mode:** WorkBuddy teaches only after current evidence identifies a real barrier.

It can review clear images of completed handwritten work, distinguishes reasoning from expression, uses answer keys only after the learner attempts a question, and treats clinical assessment and medical care as professional responsibilities.

## Privacy-first design

This public repository contains no student records, medical reports, school reports, textbooks, answer books, names, dates of birth, school names, or local file paths.

Create private learner and curriculum profiles from the templates in `references/`. Keep completed versions outside the repository.

## Install in Codex

Copy the repository folder into the local skills directory:

```bash
cp -R secondary-school-workbuddy ~/.codex/skills/secondary-school-workbuddy
```

Restart or reload Codex after installation.

## Use in another agent platform

If the platform supports Skill uploads, upload this directory or a ZIP containing it. If it only provides a system-instructions field, paste the Markdown body of `SKILL.md` after the YAML frontmatter.

Upload current school materials separately as private knowledge files. Do not commit them to this repository.

## Suggested private knowledge

- current learning-support plan;
- recent academic report;
- current timetable and teacher instructions;
- legally obtained course materials;
- private learner and curriculum profiles created from the templates.

## Scope

This project provides educational support instructions. It does not diagnose, treat, or replace teachers, psychologists, physicians, speech and language therapists, occupational therapists, or other qualified professionals.

## License

MIT. See [LICENSE](LICENSE).
