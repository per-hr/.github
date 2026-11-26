<a href="https://per.hr/ai"><img src="https://raw.githubusercontent.com/per-hr/claude-code-plugin/main/assets/banner.jpg" alt="per.hr for AI (beta): bill clients for the work you ship with Claude Code and Codex. per.hr records your sessions: your time, agent time, compute and what shipped." width="100%"></a>

<p align="center">
  <a href="https://per.hr">per.hr</a> ·
  <a href="https://per.hr/ai">per.hr for AI</a> ·
  <a href="https://per.hr/docs/claude-code">Claude Code Guide</a> ·
  <a href="https://per.hr/docs/codex">Codex Guide</a> ·
  <a href="https://per.hr/help">Help</a>
</p>

---

### per.hr for AI (Beta)

Bill clients for the work you ship with Claude Code and Codex. per.hr records each session against the right client and Plan item: your time, agent time, compute and the commits that shipped. Confirm it in Review, then bill by your time or by delivered effort.

```bash
npx perhr setup
```

Setup signs your computer in, installs the Claude Code plugin, adds per.hr's hooks to Codex if you use it, and links your code folders. Then start work on an item with `/perhr:start PAY-214` and finish with `/perhr:end`. Your prompts and code stay on your computer.

### Repositories

- **[cli](https://github.com/per-hr/cli)**: `perhr`, the per.hr CLI on npm. Setup, sessions, Review and invoices from the terminal.
- **[claude-code-plugin](https://github.com/per-hr/claude-code-plugin)**: the per.hr plugin for Claude Code, with `/perhr:start`, `/perhr:status` and `/perhr:end`.

### per.hr Desktop

Today's time and your agents in the system tray (Windows) or menu bar (Mac), with a notice when an agent waits on you or a session is ready for Review. On a computer signed in to per.hr, run `npx perhr@latest desktop`. It keeps itself, the CLI and the plugin up to date.

→ [Setup guide](https://per.hr/docs/claude-code) · [Codex guide](https://per.hr/docs/codex) · [Request access](https://per.hr/request-ai)

### Contact

Questions or bug reports: [support@per.hr](mailto:support@per.hr), or open an issue on the [cli](https://github.com/per-hr/cli/issues) or [plugin](https://github.com/per-hr/claude-code-plugin/issues) repository.
