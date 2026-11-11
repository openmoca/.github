## Portable grounding for AI

A MOCA package holds the knowledge an AI system uses, how that knowledge is organised, and the original sources it
came from. Any system can read it the same way, whatever model, vector database or agent framework it runs. A signed
package proves who published it, and signed reviews prove who checked what.

MOCA stands for **Modular Ontology, Content & Attestation**. It is an open standard under the Apache-2.0 licence.

**Start at [openmoca.org](https://openmoca.org):** [get started](https://openmoca.org/start/),
[open a package](https://openmoca.org/start/open-a-package/), or
[read the specification](https://openmoca.org/spec/).

### Repositories

| Repository | What it holds | Install |
| --- | --- | --- |
| [moca-spec](https://github.com/openmoca/moca-spec) | The specification, schemas, profiles, conformance corpus and example packages | — |
| [moca-reader-typescript](https://github.com/openmoca/moca-reader-typescript) | The reference Reader | `npm install @openmoca/moca-core` |
| [moca-reader-dotnet](https://github.com/openmoca/moca-reader-dotnet) | The .NET Reader and its framework bindings | `dotnet add package OpenMoca.Reader` |
| [moca-reader-python](https://github.com/openmoca/moca-reader-python) | The Python Reader, with LangChain and LlamaIndex bindings | `pip install moca-reader` |
| [moca-mcp-dotnet](https://github.com/openmoca/moca-mcp-dotnet) | moca-mcp, an MCP server that lets an AI assistant search and cite packages | [Downloads](https://github.com/openmoca/moca-mcp-dotnet/releases/latest) |
| [moca-tools](https://github.com/openmoca/moca-tools) | `moca-lint`, `moca-index`, `moca-sign` and `moca-embed` | `npx @openmoca/moca-lint` |
| [moca-convert](https://github.com/openmoca/moca-convert) | Make a package from Markdown, Obsidian, OpenAPI, PDF or YouTube | `npx @openmoca/moca-convert` |
| [moca-examples](https://github.com/openmoca/moca-examples) | Small CLI and chat examples in TypeScript and .NET | — |
| [openmoca.org](https://github.com/openmoca/openmoca.org) | The website | — |

Questions and ideas are welcome in
[moca-spec Discussions](https://github.com/openmoca/moca-spec/discussions). Changes to the specification go through
[Spec Change Proposals](https://github.com/openmoca/moca-spec/blob/main/CONTRIBUTING.md#proposing-a-specification-change).
