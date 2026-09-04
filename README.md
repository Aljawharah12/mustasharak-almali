# Your Financial Advisor

** understand your budget, set priorities, and plan your financial goals in Arabic.**

Mustasharak Al-Mali is a **Hermes agent profile** designed to help users review income, expenses, budgets, and financial goals through clear, practical guidance. The original profile is named `k`, and its personality instructions are stored in [SOUL.md](SOUL.md).

## What it helps with

- Understanding how income is allocated and identifying areas for improvement.
- Organizing a budget around existing commitments and priorities.
- Exploring a savings plan with a specific target and timeline.
- Comparing options and explaining benefits and risks where relevant.

The agent responds in Arabic and asks follow-up questions when information is incomplete. This README is in English; the original Arabic agent instructions remain in `SOUL.md`.

## Getting started

You need a working Hermes installation with a model provider configured in its settings.

1. Open [SOUL.md](SOUL.md) and copy its contents.
2. Create a Hermes profile named `k`, or choose another name.
3. Add the contents to the profile’s personality instructions or its `SOUL.md` file. Back up existing instructions before replacing them.
4. Select your model and provider in Hermes settings, then start a new conversation using the profile.

The profile setup interface may vary by Hermes version. This repository contains personality instructions, not a standalone application or a ready-to-import profile archive.

## Example prompts

These examples are translated into English for this README. The profile is configured to respond in Arabic.

> My monthly income is SAR 8,000, essential expenses are SAR 4,500, and other commitments are SAR 1,000. Help me organize a monthly budget and identify any additional information you need.

> I want to save SAR 12,000 within a year. What information do you need to build a plan around my income and commitments?

> Here are my monthly expenses by category: housing, food, transport, and entertainment. Help me identify opportunities to reduce spending.

These figures are illustrative. Share totals rather than account details or personally identifying information.

## Response structure

| Section | Contents |
| --- | --- |
| Financial overview | Stable, needs improvement, or needs follow-up |
| Financial analysis | Review of the information and key observations |
| Recommendations | Practical suggestions based on the available information |
| Proposed plan | Steps toward the stated goal |
| Confidence level | Low, medium, or high |
| Important notes | Limitations, missing information, and relevant risks |

The personality instructions request this format; adherence may vary by model.

## Privacy and limitations

The instructions prohibit requesting passwords, bank card details, or verification codes, and prohibit promises of guaranteed returns. Responses depend on the information provided and may contain errors. Review calculations and assumptions before relying on them.

This repository does not include user conversations, memories, databases, or API keys. How messages are handled during use depends on your Hermes configuration and chosen model provider.

## Repository contents

| File | Purpose |
| --- | --- |
| [SOUL.md](SOUL.md) | Original Arabic financial advisor personality instructions |
| [README.md](README.md) | Project overview and setup guide |
| [.gitignore](.gitignore) | Rules for excluding secrets and runtime data from Git tracking |

## Customization and contributions

Edit `SOUL.md` to adjust the tone, response structure, or requirements for your use case. Try changes with fictional data before using your own information.

For suggestions or problems, open an [issue](https://github.com/Aljawharah12/mustasharak-almali/issues) or submit a pull request. Do not include personal financial information or access keys.
