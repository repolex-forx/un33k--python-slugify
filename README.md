# Repolex Knowledge Graph of un33k/python-slugify

RDF knowledge graph data for [un33k/python-slugify](https://github.com/un33k/python-slugify), parsed by [repolex](https://repolex.ai).

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
rlex download un33k/python-slugify
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 35aca63fc2672cba2c739ff6dff685a4f26a4f9a
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 35aca63fc2672cba2c739ff6dff685a4f26a4f9a
│           └── chunk-001.nq.gz
├── blob
│   ├── 02d09efdeccdd8a5b4d65a70f27dfd8702a701a3.nq.gz
│   ├── 0daccd60988c93f6e9abc615aea95aa78c8cd1e9.nq.gz
│   ├── 11be74b499b5ba7441133072c5e6c90fab47c1ca.nq.gz
│   ├── 24f872ac76678e430c251109e94e1839e69db2e1.nq.gz
│   ├── 27df54bb735e2ab9cbb74614ac60640d83b2c58f.nq.gz
│   ├── 2a0ec67b00f141b39a5af816fe081884a0a2e6c2.nq.gz
│   ├── 33087405cdf6c67f12a88a1648e3209787f40199.nq.gz
│   ├── 3c25658f09299beae3eab152cd64a67398d609ad.nq.gz
│   ├── 41480be01d0c78cb0499787940dbf0f7735955c0.nq.gz
│   ├── 46b8c0886da2da47bcd78cbea8020e98c47393f9.nq.gz
│   ├── 632830e996486faea7cd50ebe98e5d80fe59bc01.nq.gz
│   ├── 66149c2ab322271ef044bac5ee46f9361519ede2.nq.gz
│   ├── 6a262931fbfaf0463caa6086d749c2f34c01ecc3.nq.gz
│   ├── 6c21f33f21d06c807532dd45943774e53945141c.nq.gz
│   ├── 6d3279fb1ac2e9c3febeca395a5f7350d8fa5969.nq.gz
│   ├── 828687186b2fc6676fdca23059d091d349c1a5dc.nq.gz
│   ├── 82af695f594e8c1e83ee98db0bcae758620f1b63.nq.gz
│   ├── 94ce29d6bd891efe3eb20beec8b07a34434ed59e.nq.gz
│   ├── a0705d52f9bd170a54341675186a6c95dac4aa56.nq.gz
│   ├── aedb0e47bc05fab9fc2d5583dbcc7c2d13014966.nq.gz
│   ├── af26b6f2511ad9dc6af0a09b96b3e86c8cbeb471.nq.gz
│   ├── b81e5ec2fba09d41d8dcb870289ec4db02daa08e.nq.gz
│   ├── ba507939b10dd52f11a897336daff12054b88ff1.nq.gz
│   ├── c0dfd67a830d0040eb3c6f93da900b65541e96a4.nq.gz
│   ├── c225a7a41b67c58e4a86a14753597614a7f24e39.nq.gz
│   ├── c9180e4bb984026881f15b83d2cbb7eaaefe20e8.nq.gz
│   ├── cd6122dd7dc764b18d7e5c524d3b2a11083172f3.nq.gz
│   ├── cf4fc55f578cd80a9251d1ecf92633dbb1d8ab05.nq.gz
│   ├── d5e79deae3380fee339c641b7fe4a146516f0fa7.nq.gz
│   ├── d87097714d126d8af269fcf0b5a38d18302ee2a0.nq.gz
│   ├── d8a2c2940466e8743b2fa01db1ee0642e6517e16.nq.gz
│   ├── dda3df903dccfbad347c5683aeab6c44481da4bb.nq.gz
│   ├── e563d8d0c1ca5ba4e858976c11233997737df340.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e8522482c45078999dff9bfcf51b97353c47462d.nq.gz
│   ├── e92162412ecd0b0471b163a93f7e8edd747c1dfe.nq.gz
│   ├── eb11a4901817485e7485f0bb78e358a48da2a17f.nq.gz
│   ├── ecfbb807b5a3af92bff274612258ee075268b675.nq.gz
│   ├── eda9337b841401cf54ded0dc5a1b1b1b0744a784.nq.gz
│   ├── f2907dd3aa5ec05f11e768ecef852c67d8191c6d.nq.gz
│   ├── f2ac97288608e44591b0214bda73f56205de2fa9.nq.gz
│   ├── fcec4b6824f930cb891277320be96ed464e46853.nq.gz
│   └── fde2a86316ec08e237f22fe824076dadd4321b7d.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 35aca63fc2672cba2c739ff6dff685a4f26a4f9a.nq.gz
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

[un33k/python-slugify](https://github.com/un33k/python-slugify)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
