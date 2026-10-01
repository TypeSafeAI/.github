# Security policy: TypeSafeAI Community

> **Unofficial community organization, not the official TypeSafe AI team.** Created by VC Moderator [@BunsDev](https://github.com/BunsDev).

This policy covers code in the [TypeSafeAI](https://github.com/TypeSafeAI) community repositories. A repository's own `SECURITY.md` takes precedence for that repository.

## Is it a community issue or an official one?

| The problem is in… | Report it to |
|---|---|
| A TypeSafeAI community repository (playground, harness, UI, router, Modex, and so on) | This organization, privately, as described below |
| The TypeSafe AI API, Jev model, official SDKs, accounts, or billing | The official TypeSafe AI team through [typesafe.ai](https://typesafe.ai). Community maintainers cannot fix or triage official services. |
| An upstream dependency | That dependency's maintainers. Also tell us privately if a community project's defaults make it exploitable. |

## Reporting a vulnerability

**Do not open a public issue, discussion, or pull request for a vulnerability, and do not post details in a public chat.**

1. Open the affected repository's **Security** tab and choose **Report a vulnerability** to create a private advisory.
2. If that option is not shown (private reporting is not enabled on every repository), report through [`TypeSafeAI/jev-harness`](https://github.com/TypeSafeAI/jev-harness/security/advisories/new) instead and name the affected repository so it can be routed privately.

Include, where safe:

- the affected repository and commit, release, or deployment URL;
- what boundary is affected (for example, API-key exposure, a verdict being treated as authorization, injection into a judged prompt, or hosted-demo data handling);
- reproduction steps using synthetic data;
- expected versus observed behavior and the impact.

Never include real API keys, tokens, personal data, or private prompts. Revoke any key you think was exposed before reporting.

## What to expect

These projects are maintained by volunteers. There is **no guaranteed response or fix time**, bug bounty, or service level. Maintainers coordinate fixes and disclosure through the private advisory and will credit reporters who want credit.

## Scope notes

- Community demos are experiments. A typed Jev verdict is not proof of correctness and must not authorize an action by itself; a project that lets a verdict bypass application-side checks is a valid finding.
- Mocked or simulated output presented as live results is a documentation bug, not a security vulnerability; open a normal issue.
- Hosted demos may log inputs. Do not submit sensitive data to them while testing.
