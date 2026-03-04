Tools for LLM agent workflows.

### File Context Protocol (FCP)

MCP servers that let LLMs work with complex file formats through a verb-based DSL. The LLM thinks in domain operations, FCP renders them into the target format.

| Server | Domain | What it does |
|--------|--------|--------------|
| [fcp-drawio](https://github.com/aetherwing-io/fcp-drawio) | Diagrams | Create and edit draw.io diagrams |
| [fcp-midi](https://github.com/aetherwing-io/fcp-midi) | Music | Compose MIDI files |
| [fcp-sheets](https://github.com/aetherwing-io/fcp-sheets) | Spreadsheets | Build and style .xlsx files |
| [fcp-rust](https://github.com/aetherwing-io/fcp-rust) | Rust | Navigate Rust codebases via rust-analyzer |
| [fcp-terraform](https://github.com/aetherwing-io/fcp-terraform) | Infrastructure | Generate Terraform HCL |
| [fcp-core](https://github.com/aetherwing-io/fcp-core) | Framework | Shared tokenizer, verb registry, undo/redo |

See the [FCP repo](https://github.com/aetherwing-io/fcp) for the full spec.

### Other

| Repo | What it does |
|------|--------------|
| [mish](https://github.com/aetherwing-io/mish) | LLM-native shell — structured output, error diagnostics, and process control [ohitsmish.com](https://ohitsmish.com)|
| [slipstream](https://github.com/aetherwing-io/slipstream) | In-memory file editing daemon for LLM agent workflows |
