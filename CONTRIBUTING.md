# Contributing to Spotflow

Thank you for your interest in contributing to Spotflow's documentation and SDKs! We appreciate your help in making our docs and tools more comprehensive, accurate, and user-friendly. We're excited to have you join us for **Hacktoberfest & Hackathon 2026** 🎉

**Key dates:** Hacktoberfest runs through **Oct 30, 2026**; issues stay open toward our **company hackathon on Nov 13–14, 2026**.

👉 **New here? Start at the pinned issue:** _📌 Hacktoberfest & Hackathon 2026 — Start Here_. It lists every open task and links back to this guide.

## 🔖 How to claim an issue (please read)

To avoid two people doing the same work:

1. Find an issue you'd like to work on.
2. **Comment on it** asking to be assigned — don't start coding yet.
3. A maintainer will assign you and add the **`hacktoberfest-accepted`** label. That label is our "go ahead" signal.
4. If an issue is already assigned to someone else, pick another one.

Unclaimed PRs (work on an issue nobody assigned to you) may be closed, especially if someone was already assigned.

## 🔧 How to Contribute

1. Fork and clone the repository.
2. Checkout into the `hacktoberfest-spotflow` branch.
3. Create your own branch from it: `feature/your-feature-name`.
4. Work on an issue that's been assigned to you and labelled `hacktoberfest-accepted` (look for labels: `hacktoberfest`, `good first issue`, `documentation`, `enhancement`, `ai-agent`, `agent-recipe`).
5. Commit your changes and push.
6. Open a pull request (PR) to the `hacktoberfest-spotflow` branch as the base branch.
7. In the PR description, link the issue with `Closes #<issue-number>`.

## 🧩 Contribution Types

- **Code:** SDK improvements, bug fixes, new integrations.
- **AI agents & recipes:** build an agent or write a reusable `skills.md` / agent recipe (see the `ai-agent` and `agent-recipe` labels).
- **Documentation:** improve or clarify our developer docs.
- **Non-code:** write articles, improve READMEs, create examples.

## ✅ PR Requirements

- PRs must be meaningful (avoid single-line or low-quality submissions).
- PRs must pass basic checks (linting, formatting, tests where applicable).
- Add a clear description of what was changed and why.
- Include screenshots or examples for documentation updates.
- **Never commit real secrets** — use test keys/placeholders only. If you come across a real credential, do not include it; tell a maintainer privately.

A PR counts toward Hacktoberfest once it is merged, approved, or labelled `hacktoberfest-accepted`. Spam or low-effort PRs will be labelled `spam` / `invalid` and will not count.

## ⚙️ Setup

Clone the repo and install dependencies:

```bash
git clone https://github.com/Spotflow-One/new-spotflow-docs.git
cd new-spotflow-docs
npm install
```

Preview the docs locally (they use MDX with frontmatter):

```bash
mintlify dev
```

If a package you're working on uses a different dev command, it's noted in that package's own README.

## 🏁 Maintainers

Our team reviews and merges pull requests regularly. If you have questions, reach out via our [Discord link](https://discord.gg/TDCcWV3ja).

Thank you for contributing to Spotflow! Your efforts help developers worldwide integrate payments more effectively. 💛
