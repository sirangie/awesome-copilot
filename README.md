# awesome-copilot

> A curated list of awesome GitHub Copilot instructions, prompts, agents, and extensions.

[![All Contributors](https://img.shields.io/github/all-contributors/awesome-copilot/awesome-copilot?color=ee8449&style=flat-square)](https://github.com/awesome-copilot/awesome-copilot/graphs/contributors)
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A community-driven collection of GitHub Copilot resources including custom instructions, prompt files, agent configurations, and Copilot Extensions to supercharge your development workflow.

> **Personal fork:** I'm using this to collect and test Copilot configs for my own projects. Main upstream repo is at [github/awesome-copilot](https://github.com/github/awesome-copilot).

## Contents

- [Copilot Instructions](#copilot-instructions)
- [Prompt Files](#prompt-files)
- [Agent Workflows](#agent-workflows)
- [Extensions & Plugins](#extensions--plugins)
- [Contributing](#contributing)

---

## Copilot Instructions

Custom `.github/copilot-instructions.md` files for various project types and languages.

| Name | Description | Language/Framework |
|------|-------------|-----------------|
| [Python FastAPI](instructions/python-fastapi.md) | Instructions optimized for FastAPI projects | Python |
| [TypeScript React](instructions/typescript-react.md) | Instructions for React + TypeScript apps | TypeScript |
| [Go Microservices](instructions/go-microservices.md) | Instructions for Go-based microservices | Go |

---

## Prompt Files

Reusable `.github/prompts/` files for common development tasks.

| Name | Description |
|------|-------------|
| [Code Review](prompts/code-review.prompt.md) | Thorough code review checklist prompt |
| [Write Tests](prompts/write-tests.prompt.md) | Generate unit and integration tests |
| [Refactor](prompts/refactor.prompt.md) | Refactor code for readability and performance |
| [Security Audit](prompts/security-audit.prompt.md) | Identify security vulnerabilities |

---

## Agent Workflows

Agentic workflow configurations for multi-step tasks.

| Name | Description |
|------|-------------|
| [Agentic Workflows](https://github.com/awesome-copilot/awesome-copilot/blob/main/.github/agents/agentic-workflows.agent.md) | General agentic workflow patterns |

---

## Extensions & Plugins

GitHub Copilot Extensions and marketplace plugins.

See the full list in [`.github/plugin/marketplace.json`](.github/plugin/marketplace.json).

---

## Contributing

Contributions are welcome! Please read the [contribution guidelines](CONTRIBUTING.md) before submitting a pull request.

### How to add your resource

1. Fork this repository
2. Add your resource to the appropriate section
3. Follow the existing format and naming conventions
4. Submit a pull request with a clear description

> **Note:** All submissions are reviewed for quality and relevance. Please ensure your instructions/prompts are well-documented and tested.

---

## Contributors

Thanks to all contributors! See [`.all-contributorsrc`](.all-contributorsrc) for the full list.

---

## License

[CC0 1.0 Universal](LICENSE) — Public Domain Dedication
