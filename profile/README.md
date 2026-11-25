# SendBox

SendBox is built in the open by [Synctune Open](https://github.com/synctune-open), a branch of [Synctune](https://github.com/synctune-io), focused on running coding agents safely. We give each agent a dedicated VM and an explicit policy for files, network destinations, credentials and MCP tools, instead of your whole machine.

Website and documentation: [sendbox.synctune.it](https://sendbox.synctune.it)

## Projects

| Repository | Focus |
| --- | --- |
| [sendbox](https://github.com/sendbox-dev/sendbox) | The SendBox CLI, written in Rust. Runs coding agents in dedicated Linux VMs on macOS (Apple Containerization) and Linux (Kata Containers) under a reviewable YAML policy. |
| [sendbox-fleet](https://github.com/sendbox-dev/sendbox-fleet) | Shared governance service for SendBox teams: operator-signed policy profiles, project roles, credential grants and a hash-chained central audit log. |
| [sendbox.synctune.it](https://github.com/sendbox-dev/sendbox.synctune.it) | The SendBox website, with user and contributor documentation for both projects. |

## Partner projects

| Repository | Focus |
| --- | --- |
| [moguri](https://github.com/moguri-dev/moguri) | A coding agent harness from [Moguri](https://github.com/moguri-dev). SendBox runs it in a VM with the `--agent moguri` profile. |
