# Repolex Knowledge Graph of konradhalas/dacite

RDF knowledge graph data for [konradhalas/dacite](https://github.com/konradhalas/dacite), parsed by [repolex](https://repolex.ai).

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
rlex download konradhalas/dacite
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 9898ccbb783e7e6a35ae165e7deb9fa84edfe21c
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 9898ccbb783e7e6a35ae165e7deb9fa84edfe21c
│           └── chunk-001.nq.gz
├── blob
│   ├── 01bcebf0e4e421ef239a5b5cb84d0912230f14ce.nq.gz
│   ├── 09d481f77f4215eacbe431f6cd50319a69c0f0fc.nq.gz
│   ├── 0a93b400698b9c140d1a2b8347a8d3b5dfd9b269.nq.gz
│   ├── 0d70fd97191cd3a4298868d03fab428978e513af.nq.gz
│   ├── 13e8056840a521e5d6b040fb2119504b084784dc.nq.gz
│   ├── 155533e3aa6b034c692b4555c535e7f480464c8e.nq.gz
│   ├── 171248bd81010cdf2ac7bf92a73897303c369df6.nq.gz
│   ├── 2157678f9fec94373980882c8090bab47228b2d2.nq.gz
│   ├── 29e743a304578e088fdd4a0ca8bb037c7e078292.nq.gz
│   ├── 2e690b178dba9c5137883f0fd666f01acc1dcfa6.nq.gz
│   ├── 3836563a4dba486cc9cd0a44e44a9eaff26bb8d7.nq.gz
│   ├── 3a25fb030e48728d6a3183711a5c08bcef0f5c0e.nq.gz
│   ├── 3f22c1805f230b553a7ababd2ed032b07495bc07.nq.gz
│   ├── 4be5be76271ceeed02497a4209cf4b0121de8f10.nq.gz
│   ├── 4e44f68e1e5ee00f3fcc54e5277e1f5e73dd038a.nq.gz
│   ├── 5cb1a5bd740ca5c6d57fd65f4560dbd7d2c9fa44.nq.gz
│   ├── 5f27d6943384eb6de85711cb50d501389538319d.nq.gz
│   ├── 63a3c5baedb27b24b2f69ce832b36f6ded3ed61e.nq.gz
│   ├── 6ebb4077e53547796d3189572c49867878741a22.nq.gz
│   ├── 708b3a254e5eda987d322b85134247c76cc844ab.nq.gz
│   ├── 7150655a7e3ff3f042565c941057e755dc81045a.nq.gz
│   ├── 78723d321a15cf62d2595bd6b711401524e173dd.nq.gz
│   ├── 841d1788633c1add781b2ee80f261cbf1c35677a.nq.gz
│   ├── 922a6ac123284cb338739414ced5d866f237090b.nq.gz
│   ├── 998fff7f96a53b221bd81e49920f3159c64d50f4.nq.gz
│   ├── 9b7ec51e7711b285217a91bcefabe917d9fb76ef.nq.gz
│   ├── 9fcf76a82b9b961962d06f15e8fd63e01b4d1db4.nq.gz
│   ├── a496212a8b61971c66b5854c9b100cf049f7baf6.nq.gz
│   ├── bc82eed0e5a84fa2cba8de566c86e6dff0e012d8.nq.gz
│   ├── bd3ed47104230154161e712358a17af9feaf1236.nq.gz
│   ├── bd55c9a01233d51cb8003d8a8fd23f97e95fe455.nq.gz
│   ├── c06ddc0c8289b4dd7c028f254d51398fb6eb5da8.nq.gz
│   ├── c818fe00fb4d8142b1abb53c18f892edf4c8b58f.nq.gz
│   ├── c891d3573385d9024f36221adda1e3e8f023ee68.nq.gz
│   ├── d27aab413d751d3b7921aec619fbacb4ad62e66b.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── eb7b980f051a6858f685db2f414c347cb0d21685.nq.gz
│   ├── ef84760b7bdbcc48f23b4b1e23eaa5e273362b86.nq.gz
│   ├── ef92cf6fefb045b214b8bac171a76875b25a705f.nq.gz
│   ├── eff184418510098fe8b7fc51cb5d03990fda7216.nq.gz
│   ├── f110876d0c7dbc9e1ba058cc1a4b86bbeb5d7414.nq.gz
│   ├── f1d4bf661cf317fc439569ba748f8182736b51d1.nq.gz
│   └── f2c33b0f88e8bccc8a5cc9e82157d7b2ea2de064.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 9898ccbb783e7e6a35ae165e7deb9fa84edfe21c.nq.gz
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

[konradhalas/dacite](https://github.com/konradhalas/dacite)

---
*Parsed on 2026-10-19 by [repolex](https://repolex.ai)*
