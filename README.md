# rpcdesk issue tracker

Public tracker for [rpcdesk](https://github.com/RPCDesk/rpcdesk), the desktop cockpit for the
`omp` and `pi` coding-agent CLIs.

## What goes here

| Kind | Template |
| --- | --- |
| Something is broken | [Bug report](../../issues/new?template=bug_report.yml) |
| Something is missing | [Feature request](../../issues/new?template=feature_request.yml) |
| How do I… | [Question](../../issues/new?template=question.yml) |

Please search open and closed issues first; duplicates are closed with a pointer.

## What does **not** go here

- **Security problems** — report privately through the app repo's
  [Security tab](https://github.com/RPCDesk/rpcdesk/security/advisories/new), never in a public issue.
- **Bugs in `omp` or `pi` themselves** — rpcdesk only drives those CLIs over RPC. Reproduce in the
  CLI first; report upstream if it reproduces there.
- **Model, credential, or tool-policy behaviour** — that belongs to the CLI you configured, not
  to this app.

## Useful details to include

Version from Settings → About, platform and CPU, the backend (`omp` or `pi`) and its version, the
approval mode, and the relevant lines from the app's logs:

| Platform | Logs |
| --- | --- |
| macOS | `~/Library/Logs/rpcdesk/` |
| Linux | `~/.local/state/rpcdesk/logs/` |
| Windows | `%LOCALAPPDATA%\rpcdesk\logs\` |

Redact paths, tokens, and prompts before pasting.

## Licensing

MIT — see [LICENSE](LICENSE).
