# MASLOW Health documentation instructions

## About this project

- This is the clinic-facing documentation site for MASLOW Health, built on [Mintlify](https://mintlify.com)
- Pages are MDX files with YAML frontmatter
- Configuration lives in `docs.json`
- Run `mint dev` to preview locally
- Run `mint broken-links` to check links

## Terminology

- Use "MASLOW" (all caps) when referring to the platform
- Use "survey" not "assessment" or "questionnaire" (unless referring to a specific validated instrument by name)
- Use "provider" not "clinician" or "therapist" (covers all clinical roles)
- Use "patient" not "client" or "user" (except in technical access control context)
- Use "AI report" not "AI analysis" or "AI summary"
- Use "magic link" not "passwordless login" or "email link"
- Use "clinic" not "organization" or "practice"

## Style preferences

- Use active voice and second person ("you")
- Keep sentences concise — one idea per sentence
- Use sentence case for headings
- Bold for UI elements: Click **Settings**
- Code formatting for file names, commands, paths, and code references
- Write for a clinical audience — assume familiarity with healthcare workflows, not with software

## Content boundaries

- Do not document internal implementation details (database schemas, API internals, deployment infrastructure)
- Do not document features that are not yet in production
- Do not make specific compliance certifications unless confirmed (use "designed to meet" rather than "certified")
- Security pages should be accurate but not expose implementation details that could aid attackers
- AI content should set appropriate expectations — emphasize "supports clinical judgment" not "replaces"
- Patient-facing content should be written at an accessible reading level
