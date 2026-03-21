# Repolex Knowledge Graph of samuelcolvin/rtoml

RDF knowledge graph data for [samuelcolvin/rtoml](https://github.com/samuelcolvin/rtoml), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download samuelcolvin/rtoml
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── blob
│   ├── 17f94c78b9a2d91745e9bdee904793f9989b7820.nq.gz
│   ├── 18fa062d1af60d2fd7e6ff53b1dbd9cd4702ba03.nq.gz
│   ├── 2c1369df5af5a407ee60799920bec453c7b712ec.nq.gz
│   ├── 2fd68ad9c8071f626df7047fb1aba4faa987a3e1.nq.gz
│   ├── 4e24a72a11b666c094894e7602ea7a69cf5cb3b4.nq.gz
│   ├── 5654f930ff5fa3e2910bdc48d97aa2b789d34002.nq.gz
│   ├── 60c3b6857184b1583c080fe161b0123cb1d7f52f.nq.gz
│   ├── 6a30597b19e3b03d8bebefd310d1641af07d8d33.nq.gz
│   ├── 7c48640c2260e1dfa9a4c8dc3febb8da9af3eb73.nq.gz
│   ├── 868ce68eb1055b1336ef3062acefab7725f024c4.nq.gz
│   ├── 883e8a087b8fb228ed866e2845be093fdf998ee1.nq.gz
│   ├── 8e758ba1ad64c034d0c8ef4c35d2cf39722d7889.nq.gz
│   ├── 9de2ed4d8cfbcde4fb78562c69133080c3af5fa5.nq.gz
│   ├── a65fa4316811fe50e25e36d96a8266762a003042.nq.gz
│   ├── ba1ce1634cd7e41d5f6f66853ee475d23cf1506d.nq.gz
│   ├── bdf87561ce7c1ca762033028f59d17ba77692b7b.nq.gz
│   ├── c000a50e4c5d0da502470fe4705f72a9d3751dc7.nq.gz
│   ├── c13e54a4b7cfd698f6d1328f1b7060606bd52927.nq.gz
│   ├── c64cf55973191c19c8509de64f50af9865363355.nq.gz
│   ├── cae6dd83611df49c8e50ebbb3b10303f7fccfa01.nq.gz
│   ├── da561b9e06906c5ae459027a0a373d8c085516bb.nq.gz
│   ├── db95231403c2082aa240a3ae9ac6e50455d21c38.nq.gz
│   ├── ddfc5c455bdfd8b0a07309ec9a9d451c04aca430.nq.gz
│   ├── e3056aa8fa9b47eaeedf115eaa1c3a8f7f01ffc9.nq.gz
│   ├── e5865a441847f84cc7711ff4f1fff54e026768ed.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e87eed8ff5bf4dfa00f5f90714cd9ee750624c39.nq.gz
│   └── f8bdbc5fc2633c67c2b6e5a6559b19cafc7c06e5.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 20f3ae1c23bf0decefb691f475a9506bd7ba47d8.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

8 directories, 34 files
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

## Source repository

[samuelcolvin/rtoml](https://github.com/samuelcolvin/rtoml)

---
*Parsed on 2026-03-21 by [repolex](https://repolex.ai)*
