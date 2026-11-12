# Zeus Mode for Claude Code and Codex

**A Mac app that shows what your Claude Code and Codex sessions are doing,
which ones need you, and turns your next idea into a plan your agents carry
out.**

Zeus Mode is a Mac app with a small background program. The background
program watches every Claude Code and Codex session on your Mac, and the app
shows, in one window:

- what each session is doing, and which ones wait on you;
- the questions your agents ask you, with their choices, in one list called
  **Needs you**;
- when you want it, your next idea turned into a plan: a list of steps for
  several agents, which Zeus Mode hands out and follows, bringing the
  decisions back to you.

You keep the sessions and terminals you already use. Zeus Mode is one more
window.

This repository holds the releases and the issues of Zeus Mode. The source
code is private: there is no code here.

## Get it

- Download: <https://zeusmode.ai/download/>
- With Homebrew:

  ```sh
  brew install zeus-mode/tap/zeus
  ```

Then follow [Getting started](https://zeusmode.ai/docs/getting-started/).

## What it works with

| | |
|---|---|
| Coding tools | Claude Code and Codex. You need one of them, or both, on the same Mac. |
| Computer | A Mac with macOS 14 Sonoma or newer. Apple silicon and Intel: one download for both. |
| Also needed | GitHub's command-line tool, `gh`. Zeus Mode signs it in for you. |
| Other systems | Only for macOS. There is no Windows or Linux version. |

More: [What does Zeus Mode work with?](https://zeusmode.ai/docs/what-is-supported/)

## Guides

- [Which of my coding sessions needs me?](https://zeusmode.ai/docs/which-session-needs-me/)
- [Can I see my Claude Code and Codex sessions in one place?](https://zeusmode.ai/docs/claude-code-and-codex/)
- [Do I need Zeus Mode? A comparison](https://zeusmode.ai/docs/compared/)
- [All guides](https://zeusmode.ai/docs/)

## Remove it

```sh
zeus integrate uninstall
```

This removes what Zeus Mode wrote when it was set up, its rulebook included.
It does not remove the app.

## Questions and problems

- A problem or a question: [open an issue](../../issues/new/choose).
- Anything else: <hello@zeusmode.ai>.

Site: <https://zeusmode.ai/>
