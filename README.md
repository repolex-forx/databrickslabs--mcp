# Repolex Knowledge Graph of databrickslabs/mcp

RDF knowledge graph data for [databrickslabs/mcp](https://github.com/databrickslabs/mcp), parsed by [repolex](https://repolex.ai).

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
rlex download databrickslabs/mcp
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── dc8ba768c5a341a7013a4b1599fe475427a3d060
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── dc8ba768c5a341a7013a4b1599fe475427a3d060
│           └── chunk-001.nq.gz
├── blob
│   ├── 0428d9b787bf695b5878e40aa76caf64bb7bae04.nq.gz
│   ├── 097bbaf2fc7839b15c6f5955c1ca9b7b6f05555e.nq.gz
│   ├── 0da85ea644ae762701117a46d17726e5e04cad53.nq.gz
│   ├── 10f83d298e9ad718847b0be8ad37acef6c1f1fac.nq.gz
│   ├── 21e0fe703e7710c8928e91d7f5b1e778cd2dbf21.nq.gz
│   ├── 24b6aac1e07df4fa847ba5c638e49e5d292b040d.nq.gz
│   ├── 2c00795446bfd02e76715d0e9113f64b71ca26fb.nq.gz
│   ├── 2c2aef83e4e477ea507bc2eedb1b91988a0cd256.nq.gz
│   ├── 2d0b067d25996d10b08dfdb6c196bb7454dbea92.nq.gz
│   ├── 2e93cfbc202b9989cba6e5ba5ee16c5466694bfb.nq.gz
│   ├── 39b9af00fe45e552c6c6755be927df53305847ad.nq.gz
│   ├── 3ffb9c384dd3b407dcbadeb1e74fcda4a96fe6ab.nq.gz
│   ├── 412754ee766fa621cfd209d3b7eeb25dbc25b6d3.nq.gz
│   ├── 42575115f275cce098dac7a6213cbc1b91314033.nq.gz
│   ├── 43e89102630179732e4cac73fddc90e1bd451cdf.nq.gz
│   ├── 4ce14f7e224389002f6b0c45f99083368403386f.nq.gz
│   ├── 56eeeb38eb80613fcad4f5ef33d55496c7aa4ee4.nq.gz
│   ├── 5ae527a3cff8b3a261791233715a967409902c73.nq.gz
│   ├── 5b8f79e70c5029159e1af9631abc842b37fbaa76.nq.gz
│   ├── 5dd36857fa167d7698fa9ad523f0a6a3cc2ec3d7.nq.gz
│   ├── 5e7c555f2855cfdc025d068e4ae6f57ad0d31006.nq.gz
│   ├── 6ac22fe72e19a7e6264269b67c5cce61efd76ae1.nq.gz
│   ├── 71ee92978a60ce10fc62e4bd99483dfe313897bb.nq.gz
│   ├── 7b7fe50b4a6596d4ff171ce9d7b0514a92447de2.nq.gz
│   ├── 8965ffe7ceae49ba257b38dc58ea2fbc29bc277f.nq.gz
│   ├── 95d5643d1aca50fdf6d996d53d727b9cc894abb9.nq.gz
│   ├── 9832ffed2c4c9765e87374878bfc6ee3f1d0a339.nq.gz
│   ├── 9f4d5373ad75d2296063d0427364408039360fa9.nq.gz
│   ├── a261a5fcdc01de62dec1e45b7ca5804564bedd22.nq.gz
│   ├── b0b3bb7e9c2b9c3ed1d636a1117817aae4ce0b9d.nq.gz
│   ├── b5b9c50a2caa3781e88d34b6f8d227711dc1c882.nq.gz
│   ├── b7ad88ef2a42662f2c34f40eb39c935db04cb092.nq.gz
│   ├── c0247ba449ac7987baf102f301450200eae8ae33.nq.gz
│   ├── c215d8d621c516a61d0485426990ba62a0cf8c69.nq.gz
│   ├── c3c7ba72cf2eb5bf6803992cf2aaf099c6780dfa.nq.gz
│   ├── ccdae592c3eb7b0371853f159f16424f1bdcbf90.nq.gz
│   ├── cd8294eda85f56a79d55540860f728022f417a33.nq.gz
│   ├── d0413b9834ca2a55bfbf167807b151c00cd2c1a9.nq.gz
│   ├── d7f9591b2d3f331058b1a4dc3d0ee6c635d3d1a6.nq.gz
│   ├── e1bbc231a82ba73a13e501cec7040506e3cd51ae.nq.gz
│   ├── e540358f07632ea3c7a5d48e2f1cbd44668965d4.nq.gz
│   ├── e663dd3de3897d86cff9cd9c629444def7bde4f6.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6a66241346d1561e5733e6a145b19fd46f379ac.nq.gz
│   ├── ec334907201e860ffcd34153a4350cd19b76570d.nq.gz
│   ├── edbc253a595c64f94f8ee904f74d5eb9f50bf8fb.nq.gz
│   ├── f33f180d392b678fc8f0ec39be105137eb2ca4aa.nq.gz
│   ├── f6c4692112f203592b4091e7f30f78bbe4490780.nq.gz
│   └── f798053bdb7150d823dc415c8b5f380a0f42032a.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── dc8ba768c5a341a7013a4b1599fe475427a3d060.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 57 files
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

[databrickslabs/mcp](https://github.com/databrickslabs/mcp)

---
*Parsed on 2026-10-28 by [repolex](https://repolex.ai)*
