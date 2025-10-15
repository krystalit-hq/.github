# krystalit-hq

Jednoosobowe studio inżynieryjne (Python, Go, AWS, IaC, Security).
Skupiam się na budowie małych usług, automatyzacji i infrastrukturze w AWS.

## Kluczowe repo (docelowo)
- 🔧 Monorepo usług: `microservices`
- 🧱 IaC: `iac-modules-terraform`, `iac-stacks-aws`, `iac-policy`
- 🚀 Dema/portfolio: `demo-*`, `mvp-*`
- 🤖 Automatyzacje: `automation-n8n`, `automation-github`

## Standardy
- Reusable GitHub Actions w tym repo: CI (Python/Go), IaC (Terraform), Security (CodeQL/Deps), Container (GHCR).
- Nazewnictwo repo: `sec-*`, `iac-*`, `saas-*`, `micro-*`, `demo-*`, `mvp-*`, `automation-*`, `vibe-*`, `admin-*`, `templates-*`.
- Obrazy: `ghcr.io/krystalit-hq/<image>:<tag>`.

> Jeśli tu trafiłeś z LinkedIn – zajrzyj do `demo-*` po szybkie przykłady. ✨