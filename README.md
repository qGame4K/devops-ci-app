# devops-ci-app

Практическая работа 10. Лебедев Иван, ЭФБО-11-24.

Pylint → pytest → Docker build → smoke-test → GHCR.
Публикация только при push в main. PR проходят проверки без публикации.

- Health: `/health`
- Образ: `ghcr.io/qgame4k/devops-ci-app`
- Workflow: `.github/workflows/ci.yml`
