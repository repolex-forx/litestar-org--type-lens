# Repolex Knowledge Graph of litestar-org/type-lens

RDF knowledge graph data for [litestar-org/type-lens](https://github.com/litestar-org/type-lens), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [rlex](https://github.com/repolex-ai/rlex) query tool:

```bash
cargo install --git https://github.com/repolex-ai/rlex
```

Verify the install:

```bash
rlex --help
```

**rlex is designed to be used primarily by LLMs in a terminal.** Start up your favorite AI assistant and ask it to use rlex. It handles the SPARQL — you just ask questions in plain English.

To load this repo's data:

```bash
rlex download litestar-org/type-lens
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 58fccf85bd76bca16c204849a0dcd496541f4a82
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 58fccf85bd76bca16c204849a0dcd496541f4a82
│           └── chunk-001.nq.gz
├── blob
│   ├── 00b2c07181080ee652beb9fdcb92ec63990d5bad.nq.gz
│   ├── 0a228414acbd912647ce97f6d969bac9fa0f35c2.nq.gz
│   ├── 225ce68a9fc6d896742afe33cced8084bf22e2d4.nq.gz
│   ├── 2b7f1ed84204f2185df775de72e89ef1f3a97440.nq.gz
│   ├── 30023c73ecbd6a7eaa81b979f435fbb4bdf2c023.nq.gz
│   ├── 307af6f033c4e7e8c6cfe80fead6b810bb8ca6ac.nq.gz
│   ├── 35628fcb3b427dd782b7a95ac258b7efce8d0473.nq.gz
│   ├── 369323f4cce8fe2defb1f96aaf7c9c8c49f9e9c1.nq.gz
│   ├── 3797fee2ba7ea85bf125dd546f08d8e83587a59d.nq.gz
│   ├── 38e14116400b3709fedf543db9d4b5df762f80c3.nq.gz
│   ├── 42ce138108f8d8fcc167e790974d5d7ace29137a.nq.gz
│   ├── 6266c66ab3da4d188ceef26b453103e408f1a24d.nq.gz
│   ├── 6b9e65c413f560a14dd967c27ad02db39499eac1.nq.gz
│   ├── 6eca3c6f3b9c171466b8da63cad6bce47e118328.nq.gz
│   ├── 7544b1867d34b257147d5e41b754e24a3225c605.nq.gz
│   ├── 7d03436be354fcf82d45f08cab1bcc66e59cbdd8.nq.gz
│   ├── 808c061f0917d9bf1c4fafbe60f7eb030f57b168.nq.gz
│   ├── 80d991ba7e3ba2978f2d7dfe64f32245317960c0.nq.gz
│   ├── 8815862b04466c05b0e43f6b0a4e868db26ac9e8.nq.gz
│   ├── 8d89b73266e27ace31da36476b0c47c3772fa159.nq.gz
│   ├── 8fda88952f241d3dbbc07a168060a06b95aa60f2.nq.gz
│   ├── 9505c63bd6f3a629897d428c9ab82dc9fb15946a.nq.gz
│   ├── 9690daf0cc8346f95343909ab84da66cd6ffeeb8.nq.gz
│   ├── 9e08a948bc1398678535339968b3fd966d66a692.nq.gz
│   ├── a1a0200d03eb9dc860a52871d1a2957cc3cfc394.nq.gz
│   ├── a420073db6d5b8be688b06ef4cf9fd82127612d9.nq.gz
│   ├── ac46473a3b576b64f71471f72fc3054127030549.nq.gz
│   ├── ae956062f484de6fc27113e6b2311fb51b8fe70d.nq.gz
│   ├── b07b5cc8cf3375b9ed5790063ed291050ba933e8.nq.gz
│   ├── b79e7169e92995b33095b067172813a64e5e8408.nq.gz
│   ├── bbd440e7a11cd492aeadbc4fe999f354366866df.nq.gz
│   ├── bdbb547e2ddfdcc420a9b66deac4d26d6433b72e.nq.gz
│   ├── be45ad49264c3be10310aaeaf22c0ae07e49c1ca.nq.gz
│   ├── c2ea9096afff030e9a64e3b536d78cfbca8ace3c.nq.gz
│   ├── cb40395300299efc3a3b265948826fdf24af34a7.nq.gz
│   ├── cd25f72ce9e07ce011a86e4b576bb03bfa18cf0f.nq.gz
│   ├── d0a7a44246b5cc4cf8de4f32577c5cfa91cc11e8.nq.gz
│   ├── dd130b344658e27a3b8af15a9deec5a4d5b6b683.nq.gz
│   ├── e4dc9466d29fd66b938a3c1ceb6eddc5262acfc6.nq.gz
│   ├── e617ceac41ede5c9440aac264948c10801ec753e.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7c665de2aa25f33b3c6483112aad22d3b2d2fc5.nq.gz
│   ├── ebe75dc875ccb940f59ee8a62e6ae306e4b022bf.nq.gz
│   ├── efe947dc367cdc1bac5a6df9b5e9ba5908091338.nq.gz
│   ├── f4f5d1c291462ec21a7cfa9f69229d575390af94.nq.gz
│   └── fc998c9e3c7761b65d3964648955ab3cd0f187cb.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 58fccf85bd76bca16c204849a0dcd496541f4a82.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 54 files
```

| Directory | What it contains |
|-----------|-----------------|
| `blob/` | Per-file AST graphs, content-addressed by git blob SHA. Each file in the source repo gets its own graph. |
| `aggregate/ast/` | Combined AST graph per parsed commit. Merges all blob graphs for a snapshot of the entire codebase at that point. |
| `aggregate/lsp/` | Language Server Protocol enrichment: resolved symbols, definitions, references, and type information. |
| `aggregate/dataflow/` | Interprocedural data flow edges between functions and modules. |
| `aggregate/repolex/` | Combined graph (AST + LSP + dataflow) per commit. |
| `commit/` | Git commit metadata (author, date, message, parent links). |
| `branch/` | Branch metadata. |
| `tag/` | Tag metadata. |
| `filetree/` | File tree snapshots per commit (which files existed and their blob SHAs). |
| `audit/` | Code architecture and graph audit reports per commit. |

## Source repository

[litestar-org/type-lens](https://github.com/litestar-org/type-lens)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*
