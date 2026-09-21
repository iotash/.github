<p align="center">
  <img src="https://iota.sh/img/iota-app-icon.svg" alt="iota" width="96" height="96">
</p>

<h1 align="center">iota</h1>

<p align="center">The smallest thing between your terminal and a model.</p>

<p align="center">
  <a href="https://iota.sh">iota.sh</a> ·
  <a href="https://iota.sh/docs/install">Install</a> ·
  <a href="https://iota.sh/docs">Docs</a> ·
  <a href="https://iota.sh/changelog">Changelog</a>
</p>

iota is an agent CLI for the terminal, written in Rust. You configure agents —
a model, a prompt, a set of tools — in one YAML file, and run them:
`iota run <agent>`, or a bare `iota` for the agent called `default`.

```bash
curl -fsSL https://iota.sh/install.sh | sh     # macOS and Linux (Homebrew, PowerShell and cargo on the install page)
export OPENAI_API_KEY=…
iota                                            # a first run writes ~/.iota.yaml and runs agents.default
```

- [iota](https://github.com/iotash/iota) — the CLI
- [iota-website](https://github.com/iotash/iota-website) — the source of iota.sh
- [homebrew-tap](https://github.com/iotash/homebrew-tap) — `brew install iotash/tap/iota`

MIT licensed.
