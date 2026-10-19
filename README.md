# Repolex Knowledge Graph of coleifer/micawber

RDF knowledge graph data for [coleifer/micawber](https://github.com/coleifer/micawber), parsed by [repolex](https://repolex.ai).

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
rlex download coleifer/micawber
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 3790e285a1d83131b34163488e9a18af04f50678
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 3790e285a1d83131b34163488e9a18af04f50678
│           └── chunk-001.nq.gz
├── blob
│   ├── 04f599319706cae7c247ee70209fe1a6ca2843e6.nq.gz
│   ├── 0a7d616daa9fda07871b466b9287cb8f3cc8056b.nq.gz
│   ├── 112525cb18aa09dc7da1e81240a6c81bb7e99ffa.nq.gz
│   ├── 1156dae80463fd710d80ea8604d1ba3887d4d7d6.nq.gz
│   ├── 119089938abd5f22365149043d21c90aa7f6fd0e.nq.gz
│   ├── 1430157ab406fcda6d88743b6db9adf9452dcf09.nq.gz
│   ├── 17550243a912c38662783737f09284b7325ae390.nq.gz
│   ├── 17b45e3b8cce75377b186c6980385ef19d683106.nq.gz
│   ├── 1faf5e9c6346e4dff2424059d4b701f0cef8a958.nq.gz
│   ├── 2474b84bb225ef2c28913178010bc0076fb96047.nq.gz
│   ├── 2868ef5224740eaeb84631589e7cd8fd1394a4d8.nq.gz
│   ├── 28c7ad1507832b3b6d7be4c5e9f18110985974e1.nq.gz
│   ├── 29db1c7e37bc0b1331677ae9483fd531eef8a1bc.nq.gz
│   ├── 357bbe4f8dcef821e1fc8924f88b57bb5c718bc4.nq.gz
│   ├── 3e2b3e6405c2cac3dbb12a3ce9e3690583c214e6.nq.gz
│   ├── 3e4eedc9ff5862c99e999b544a5b34c4e9af877a.nq.gz
│   ├── 41733ecac4a802f23d6e50778242f1ea69f495e0.nq.gz
│   ├── 45218442c44cd868f3470c56e04ff82f4ce42cdc.nq.gz
│   ├── 4d0e1af0b6c1fd7498c79f495ef263d854e7a4aa.nq.gz
│   ├── 4f3b71d8aed0f65b6ee2a0f9c3ae457dc03de944.nq.gz
│   ├── 8a10a9704a510311b22612c8740ce12c849c5bb6.nq.gz
│   ├── 962c94fe2933338e0fb1ea8edddd6be904438172.nq.gz
│   ├── b1cfbac244caac01ab6093461ce51a1a954355da.nq.gz
│   ├── b4b51d2ab3286b8b41416518e2462be822400267.nq.gz
│   ├── b5b48a8d55569918199d550f182766f3b4780b71.nq.gz
│   ├── ba3033fecfaa42a7fcb2906c6c415cbee6ef5cec.nq.gz
│   ├── bb27860d577e94bf6962fce6f85df3e598a4d257.nq.gz
│   ├── c07b425af2d66764461017e1e7fa4735b30d3c27.nq.gz
│   ├── c1e472526bf2240caa212b3a45ff445ae9f2b0da.nq.gz
│   ├── c752ab3ead2e7be324e5cafb5e1d53135c16af13.nq.gz
│   ├── c939fb3809e430c6e96842fa6552d82a815096d4.nq.gz
│   ├── cb5d9fb22c14571079e1c1a9323d15318d74a46a.nq.gz
│   ├── d1a5725c4cde9e3cadc84e2fccc5382657ef133d.nq.gz
│   ├── d207d40f9a055acfe7c220d2b69c6dd79c37af8a.nq.gz
│   ├── d6d0c30f1533cf1144da2ff5014cfa103b848792.nq.gz
│   ├── d7096ff46cb7e74d7148fa8fc122a5cfadd43e4d.nq.gz
│   ├── e654e05004ced7691ff6e6349e50d8997f97f933.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e784dc946e69a5da45ddff5bcc9de2c8cb803ec2.nq.gz
│   ├── ed181cf7dcfca1181ee4496ee48bd2b7cc6099a7.nq.gz
│   ├── fc690d9a36658b279122ca2771d348020f68dfe3.nq.gz
│   ├── febe5cd3ad23ba8d6be92f3990476b9da966d83c.nq.gz
│   └── ff635ec686db2c228e3d15bf5eb673156613604c.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 3790e285a1d83131b34163488e9a18af04f50678.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 51 files
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

[coleifer/micawber](https://github.com/coleifer/micawber)

---
*Parsed on 2026-10-19 by [repolex](https://repolex.ai)*
