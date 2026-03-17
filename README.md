# git-local-remote-starter

A practical guide and Windows batch script for setting up a local Git remote — complete with automated folder scaffolding so you can skip the boilerplate and start committing fast.

---

## What's Included

- **Setup Guide** — A step-by-step walkthrough of the full process for creating and connecting a local remote repository
- **`.bat` Script** — Automates repo initialization, folder scaffold creation, and remote linking in one shot

---

## Why Use a Local Remote?

Sometimes a hosted Git service isn't an option — no GitHub, no GitLab, no Azure DevOps. A local remote keeps your full Git workflow intact: branching, push/pull, commit history, the works, with zero infrastructure dependencies.

Built out of real-world necessity for analytics and data science work where version control wasn't optional even when the environment doesn't make it easy.

---

## Getting Started

### Windows (`.bat` Script)

> ⚠️ Written for Windows Command Prompt / PowerShell environments.

1. Clone or download this repo
2. Run `setup.bat` from your target project directory
3. Follow the prompts

### macOS (Shell Script) — *Coming Soon*

A `.sh` equivalent for macOS is in progress. See [CONTRIBUTING.md](./CONTRIBUTING.md) if you want to help port it.

### Manual (Guide)

See [GUIDE.md](./GUIDE.md) for the full step-by-step walkthrough for Windows or macOS.

---

## Folder Scaffold

The script will generate the following structure in your project directory:

```
my-project/
├── src/
├── docs/
├── scripts/
└── README.md
```

> Customize the scaffold by editing the directory list near the top of `setup.bat`.

---

## Requirements

| Platform | Requirements |
|----------|--------------|
| Windows | Git for Windows, Command Prompt or PowerShell |
| macOS *(coming soon)* | Git via Homebrew or Xcode CLT, Terminal |

---

## Contributing

Found an issue or want to add a shell/bash equivalent? PRs are welcome.
