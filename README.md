- major
  - e.g. react
  - scope: frontend/a, frontend/b, root
  - expected: separated
- minor
  - e.g. express
  - scope: backend/a, backend/b
  - expected: separated, combined deps (but this PR shows only Express PR title)
- patch
  - e.g. fastify, chalk
  - scope: backend/a, backend/b
  - expected: separated, combined deps

minor and patch are same behavior.