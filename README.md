<div align="center">

# Cockpit

### The driver's view of a spec-driven project.

Read the spec on any branch, see what the tests proved, plan what comes next — and, later, the
metrics that show how it's going.

[![License: Apache 2.0](https://img.shields.io/badge/License-Apache_2.0-3b82f6?style=flat-square)](LICENSE)
[![Built with NoVibe](https://img.shields.io/badge/built_with-NoVibe-6e56cf?style=flat-square)](https://github.com/novibe-org/novibe)

</div>

---

## ✨ What it does

| | |
|---|---|
| **Specification** | the feature files on any branch, straight from GitHub, each as written |
| **Status** | what that branch's latest test run proved, per scenario, feature and epic |
| **Planning** | features dragged into epics and ordered — one planning tool among many |

[`apps/cockpit/README.md`](apps/cockpit/README.md) says how it works and how to run it locally.

## 🧭 Built the NoVibe way

The cockpit is an example implementation of [NoVibe](https://github.com/novibe-org/novibe):
every change went spec → design → tests, and this repository is set up the way a NoVibe project
should be.

| | |
|---|---|
| [`features/`](features/) | the spec, by domain — what the cockpit does |
| [`docs/architecture/`](docs/architecture/) | the C4 model — look at it with `pnpm diagrams` |
| [`docs/adrs/`](docs/adrs/) | the decisions that shaped it |
| [`.githooks/`](.githooks/), [`.gherkin-lintrc`](.gherkin-lintrc) | the guard rails |
| [`.claude/settings.json`](.claude/settings.json) | the NoVibe plugin and the hook that turns the guards on |

Adopting NoVibe? Copy from here.

## 🚀 Develop

Node 22 or newer, pnpm.

```
pnpm install
pnpm test
pnpm dev:cockpit
```
