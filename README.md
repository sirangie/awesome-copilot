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
|------|-------------|------------------|
| [Python FastAPI](instructions/python-fastapi.md) | Instructions optimized for FastAPI projects | Python |
| [TypeScript React](instructions/typescript-react.md) | Instructions for React + TypeScript apps | TypeScript |
| [Go Microservices](instructions/go-microservices.md) | Instructions for Go-based microservices | Go |
| [Rust CLI](instructions/rust-cli.md) | Instructions for Rust command-line tools | Rust | <!-- added this one myself, using it for a side project -->
| [Python Django](instructions/python-django.md) | Instructions for Django web projects | Python | <!-- TODO: need to write this one still -->
| [Node.js Express](instructions/nodejs-express.md) | Instructions for Express REST APIs | JavaScript | <!-- want to add this for my work projects -->

---

## Prompt Files

Reusable `.github/prompts/` files for common development tasks.

| Name | Description |
|------|-------------|
| [Code Review](prompts/code-review.prompt.md) | Thorough code review checklist prompt |
| [Write Tests](prompts/write-tests.prompt.md) | Generate unit and integration tests |
| [Refactor](prompts/refactor.prompt.md) | Refactor code for readability and performance |
| [Security Audit](prompts/security-audit.prompt.md) | Identify security vulnerabilities |
| [Write Docs](prompts/write-docs.prompt.md) | Generate README and inline documentation | <!-- handy, added from upstream issue #42 -->
| [Commit Message](prompts/commit-message.prompt.md) | Generate conventional commit messages | <!-- added this myself, super useful -->
| [PR Description](prompts/pr-description.prompt.md) | Generate pull request descriptions with context | <!-- added this one - tired of writing PR descriptions manually -->
| [Changelog Entry](prompts/changelog-entry.prompt.md) | Generate CHANGELOG entries from recent commits | <!-- TODO: finish writing this one, draft is in my notes -->
| [Debug Helper](prompts/debug-helper.prompt.md) | Suggest debugging steps and add logging | <!-- grabbed this from upstream PR #67, really handy for Go projects -->