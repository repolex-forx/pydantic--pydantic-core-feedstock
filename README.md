# Repolex Knowledge Graph of pydantic/pydantic-core-feedstock

RDF knowledge graph data for [pydantic/pydantic-core-feedstock](https://github.com/pydantic/pydantic-core-feedstock), parsed by [repolex](https://repolex.ai).

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
rlex download pydantic/pydantic-core-feedstock
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 1f47ffb6865b63f1a6d8834a02508861df0c9b05
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 1f47ffb6865b63f1a6d8834a02508861df0c9b05
│           └── chunk-001.nq.gz
├── blob
│   ├── 052ccf05dbc5b9cd32732360fdc439cf61b2a366.nq.gz
│   ├── 09617708a74ac1b4cc678b976a22790f35483af8.nq.gz
│   ├── 0afefdea9f1c817fefc411fe2e26842d2a94df81.nq.gz
│   ├── 2af2a044cb636652594beed1b806bb39d015b3e9.nq.gz
│   ├── 2e60ae4e8e8dcf5792012b24e1285985312f3ccd.nq.gz
│   ├── 2ec51d75f362bc4327a3cfe1c515c16bb3c57367.nq.gz
│   ├── 2fb32440f7cc82a7f3432ec00d7d4e1dd74ce351.nq.gz
│   ├── 3f4b7a794fcfde4c25659b0e8ea18ade4077cc12.nq.gz
│   ├── 4f0105421e9e7736416d1f2a5886f72b31884174.nq.gz
│   ├── 528ac746d44ab79d1c248094edeb98c03eb67ce5.nq.gz
│   ├── 57bc95c2421b4508cf8ec99e9b31ed7994a1990c.nq.gz
│   ├── 61ef68d51a6730c7200afe4b22d56814b713fb9c.nq.gz
│   ├── 6b346f505e5d415eeb91f140f75568318e6c65a1.nq.gz
│   ├── 74ba74884481a6e56453b3dcc51e058b5c492cb2.nq.gz
│   ├── 771b47569d91ee8790376a0453367d0be6ce7703.nq.gz
│   ├── 7b2354ef8e0ddf8bcf6b8a3e45fbe20e29728f2f.nq.gz
│   ├── 7f3276384a82769429136888b86626a2fa49045a.nq.gz
│   ├── 81b6dbebd69b99a7b9a2b2c9209b05840b997ca4.nq.gz
│   ├── 85baa004f737c26f62a31aacaad14fc38fb3720a.nq.gz
│   ├── 8b4ef2f99f09f74edf3a2c2621d837677e430e30.nq.gz
│   ├── 923623983b6c11c20548d2d95f3000a788fea8bb.nq.gz
│   ├── 93595f8a61d10d474fd0bdb2099993d72df3cfe5.nq.gz
│   ├── 9e123caacf72c1be9941e6b370a47c931b6be2c0.nq.gz
│   ├── a47316be6ae90505a64fbe303a9fdf21a056a4a4.nq.gz
│   ├── a6b09f6b7b0e80a461ba6742cb7a09c1ab92c713.nq.gz
│   ├── ac23b811e8d9628d49c7f213d350c2b965d733af.nq.gz
│   ├── aeb3498dbafb302f0d51e77ae952cccc32181596.nq.gz
│   ├── b372ddb69c2984001123a12e3b2713f1f5e31979.nq.gz
│   ├── b75c37a4f35db2bd804d95ed6fcc26f7193872d8.nq.gz
│   ├── bb00584b92b5852efbc25adf5c81affb0a470e4c.nq.gz
│   ├── c00be95a003bb0550c4c5669745a68a82c012e59.nq.gz
│   ├── c21871ee87d4a9b1d6921bce46d7da972c50269b.nq.gz
│   ├── c502858dac5f63ffaceb2fdc38fc19c61a8a616a.nq.gz
│   ├── c89ecb7d69f1d663169e586f55f68f1cb7875290.nq.gz
│   ├── cda1eb8e008185367830b0069ba9109fd749495c.nq.gz
│   ├── d6f06b5c9c254e123633cc46480ad5bd2e1a0f82.nq.gz
│   ├── da1368a124bb36af10a90561f5ee097939f2e0d7.nq.gz
│   ├── de751643cc24e283964936c777f76f26314721e9.nq.gz
│   ├── dff01463ec37ecbca46bfa9f3886a069065b6ca4.nq.gz
│   ├── e71b6564f3f4ee8b29e403495ebe997d3e9bc731.nq.gz
│   ├── e8c0ae2df2a1b24298a1ee6cadc22ef223f645dc.nq.gz
│   ├── ea7955f82ab4b2061061fb69d9fa53c8d0ea53dc.nq.gz
│   ├── f1fdb0ea3c2aa7368dcbba148f9b62c4ade573b2.nq.gz
│   ├── f9b835cfa9531822b03170c99ea8386ccbb26862.nq.gz
│   ├── fe6f46b378ab6cfe6459ae685939d0948a9e5685.nq.gz
│   └── ff668c157cf2c681fa9ac35d67f863540f6c7d23.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 1f47ffb6865b63f1a6d8834a02508861df0c9b05.nq.gz
└── tag
    └── tag.nq.gz

11 directories, 52 files
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

[pydantic/pydantic-core-feedstock](https://github.com/pydantic/pydantic-core-feedstock)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
