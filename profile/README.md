# TypeSafeAI Community

*Learn, experiment, and build with TypeSafe AI and Jev.*

> [!IMPORTANT]
> **UNOFFICIAL COMMUNITY GITHUB — NOT THE OFFICIAL TYPESAFE AI TEAM.**
> Created by VC Moderator [@BunsDev](https://github.com/BunsDev).
>
> This organization is community-run. Its maintainers do not speak for TypeSafe AI, and hosting a project here does not imply official support or endorsement.
> For the official team's SDKs and repositories, visit [typesafe-ai](https://github.com/typesafe-ai).

[Community projects](#community-projects) · [Get started](#get-started) · [Contribute](#contribute) · [Official resources](#official-typesafe-ai-resources)

## What this community is for

A place for developers, researchers, and curious builders to turn ideas into **inspectable demos**, share what works, and document what does not. We focus on typed decisions, transparent results, reusable interfaces, and reproducible examples.

## Community projects

| Repository | What to explore |
|---|---|
| **[typesafe-playground](https://github.com/TypeSafeAI/typesafe-playground)** | Interactive Jev examples, A/B comparisons, document extraction, routing, games, and simulations. |
| **[jev-harness](https://github.com/TypeSafeAI/jev-harness)** | Proposal review: an LLM proposes an action, Jev supplies narrow judgments, and code produces evidence for the host. Verdicts do not authorize or execute a proposal. See the repository for synthetic fixture and live-run provenance. |
| **[clarity-judge](https://github.com/TypeSafeAI/clarity-judge)** | Writing checks with separate verdicts, confidence signals, and source evidence. Evaluates supplied text; does not rewrite it or verify facts. |
| **[typesafe-ui](https://github.com/TypeSafeAI/typesafe-ui)** | Reusable React components and interface patterns with a component browser. A source workspace, not an official SDK or published npm package. |
| **[typesafe-router](https://github.com/TypeSafeAI/typesafe-router)** | Closed-set tool and model selection with confidence and fallback policies. The application independently authorizes and executes. |
| **[modex](https://github.com/TypeSafeAI/modex)** | Community Electron desktop for coding-agent CLIs, parallel threads, worktrees, approvals, and changes inspection. |
| **[community-blog](https://github.com/TypeSafeAI/community-blog)** | A minimal static site for community notes about TypeSafe AI. |

**Start exploring:** [Open the community playground](https://jev.works).

> [!NOTE]
> These are separate community projects, not an officially supported product suite. Each repository's README explains its setup, current capabilities, and limitations.

## Get started

1. **Learn the API.** Read the [official TypeSafe quick start](https://docs.typesafe.ai/introduction/quickstart) for upstream API and SDK setup.
2. **Choose a project.** Follow its README for installation, required tools, and optional API-key configuration. Setup differs between repositories; start offline or in demo mode where supported.
3. **Inspect an experiment.** Start with synthetic input, identify whether the result is mocked or live, and inspect decisions, uncertainty, and failure cases before adapting it.

## Contribute

Bug reports, focused examples, documentation improvements, reproducible experiments, and accessibility fixes are welcome.

Start in the relevant repository: read its README, AGENTS.md, and CONTRIBUTING.md, check existing issues, and submit a focused issue or pull request. Explain the problem, what changed, and how you verified it. Preserve original author credits and check the repository's license before reusing code.

Keep discussions respectful, specific, and useful. Community project questions belong in the relevant repository; **official product, account, billing, and API-support questions belong with TypeSafe AI's official channels.**

[Community contribution guide](https://github.com/TypeSafeAI/.github/blob/main/CONTRIBUTING.md) · [Developer and agent navigation](https://github.com/TypeSafeAI/.github/blob/main/docs/discovery/README.md) · [Sharing guide](https://github.com/TypeSafeAI/.github/blob/main/docs/discovery/SHARING.md)

## Working responsibly

> [!WARNING]
> Community demos are experiments, not guarantees of model accuracy or production readiness. A typed result is not proof of correctness or authorization to execute an action.

Keep policy and authorization checks in application code. Distinguish simulated outcomes from live evaluations. Document limitations alongside results and link measured claims to the exact run that produced them.

> [!CAUTION]
> Never publish API keys or sensitive data in code, issues, screenshots, or example inputs. Review a project's data-handling notes before using a hosted demo or supplying credentials.

## Official TypeSafe AI resources

**[Website](https://typesafe.ai)** · **[Documentation](https://docs.typesafe.ai)** · **[Official GitHub](https://github.com/typesafe-ai)**

These are official TypeSafe AI resources, separate from this unofficial community organization.
