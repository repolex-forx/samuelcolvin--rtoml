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
├── aggregate
│   ├── ast
│   │   ├── 0916aef1579ae69767e9f41c6d859b6dcc17b8a5.nq.gz
│   │   └── 20f3ae1c23bf0decefb691f475a9506bd7ba47d8.nq.gz
│   ├── lsp
│   │   ├── 0916aef1579ae69767e9f41c6d859b6dcc17b8a5.nq.gz
│   │   └── 20f3ae1c23bf0decefb691f475a9506bd7ba47d8.nq.gz
│   └── repolex
│       ├── 0916aef1579ae69767e9f41c6d859b6dcc17b8a5.nq.gz
│       └── 20f3ae1c23bf0decefb691f475a9506bd7ba47d8.nq.gz
├── blob
│   ├── 0524b6dff762c50bdf677281fd1063dcdc4dee8c.nq.gz
│   ├── 06d9d1f62b4c4e3a052d60589f725a742102def6.nq.gz
│   ├── 1024f1bd55e8eea7d845cd861eb96f6987e5e182.nq.gz
│   ├── 17f94c78b9a2d91745e9bdee904793f9989b7820.nq.gz
│   ├── 18fa062d1af60d2fd7e6ff53b1dbd9cd4702ba03.nq.gz
│   ├── 24ee5b1be9961e38a503c8e764b7385dbb6ba124.nq.gz
│   ├── 2c1369df5af5a407ee60799920bec453c7b712ec.nq.gz
│   ├── 2fd68ad9c8071f626df7047fb1aba4faa987a3e1.nq.gz
│   ├── 37da525e06691b813a5abe1c0a669c1bfa98714f.nq.gz
│   ├── 3c85687f3ac3b0cc7fb2a9883aa831be0cd9906e.nq.gz
│   ├── 483fec392b209bd22341faf2980a9b2d69dc47f1.nq.gz
│   ├── 4e24a72a11b666c094894e7602ea7a69cf5cb3b4.nq.gz
│   ├── 4f9f5bec323d1887718ba998155b68981a279304.nq.gz
│   ├── 5654f930ff5fa3e2910bdc48d97aa2b789d34002.nq.gz
│   ├── 5b5e83e70c4cb9921ef590287a0a95803e08d068.nq.gz
│   ├── 60c3b6857184b1583c080fe161b0123cb1d7f52f.nq.gz
│   ├── 667446ca53fe038b16ad93c745efd81b5fe0eea1.nq.gz
│   ├── 6a30597b19e3b03d8bebefd310d1641af07d8d33.nq.gz
│   ├── 75306517965a54731b94dca8bace640e856af115.nq.gz
│   ├── 768f473b274732f973e3739c5330a151c640559b.nq.gz
│   ├── 7a9766bbee498c734386a14139c2bb28d409073b.nq.gz
│   ├── 7c48640c2260e1dfa9a4c8dc3febb8da9af3eb73.nq.gz
│   ├── 7eda4074acf832d17a64b600da491a970ccf1e20.nq.gz
│   ├── 83d271d57d3006aa5d19318c4915aaef64e49e11.nq.gz
│   ├── 841ea1c61d6914be9f7d63b3409cc6acdcfe34aa.nq.gz
│   ├── 868ce68eb1055b1336ef3062acefab7725f024c4.nq.gz
│   ├── 883e8a087b8fb228ed866e2845be093fdf998ee1.nq.gz
│   ├── 8c50a3dd59e3d8329b13f252f869ffeb732bcc8c.nq.gz
│   ├── 8e758ba1ad64c034d0c8ef4c35d2cf39722d7889.nq.gz
│   ├── 901b30d7eba795fef0e2cb42922a9b7ed35dca81.nq.gz
│   ├── 95b549ed50448569a2835e9c73020d4d7467c1d7.nq.gz
│   ├── 99115194e92e09993ac26325e2d4e3005b539a2e.nq.gz
│   ├── 9de2ed4d8cfbcde4fb78562c69133080c3af5fa5.nq.gz
│   ├── 9e71b090bd9af3044c6f0da609c6c86174f7e472.nq.gz
│   ├── a65fa4316811fe50e25e36d96a8266762a003042.nq.gz
│   ├── b423f1e31358ebdb5775a52e7cda514ea479dfed.nq.gz
│   ├── b9af05c083fe901948752c6777a551dad64f94e1.nq.gz
│   ├── ba1ce1634cd7e41d5f6f66853ee475d23cf1506d.nq.gz
│   ├── bdf87561ce7c1ca762033028f59d17ba77692b7b.nq.gz
│   ├── c000a50e4c5d0da502470fe4705f72a9d3751dc7.nq.gz
│   ├── c13e54a4b7cfd698f6d1328f1b7060606bd52927.nq.gz
│   ├── c38074d195986dc2d576cc8c9ab337aa18d7f05c.nq.gz
│   ├── c64cf55973191c19c8509de64f50af9865363355.nq.gz
│   ├── cae6dd83611df49c8e50ebbb3b10303f7fccfa01.nq.gz
│   ├── d2a21f771da38847ca06653ef5266effc3f89090.nq.gz
│   ├── d6216f573deadb0e475942b630cc9c3f474377ea.nq.gz
│   ├── d688d60a989bb6394f217d5076ad72e217f45db0.nq.gz
│   ├── d828e9d4bbd885144a82098bf78841208f698dc4.nq.gz
│   ├── da561b9e06906c5ae459027a0a373d8c085516bb.nq.gz
│   ├── db95231403c2082aa240a3ae9ac6e50455d21c38.nq.gz
│   ├── ddfc5c455bdfd8b0a07309ec9a9d451c04aca430.nq.gz
│   ├── e3056aa8fa9b47eaeedf115eaa1c3a8f7f01ffc9.nq.gz
│   ├── e48cffab0fb5c6e16a6495152852cab94ca06816.nq.gz
│   ├── e5865a441847f84cc7711ff4f1fff54e026768ed.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e87eed8ff5bf4dfa00f5f90714cd9ee750624c39.nq.gz
│   ├── eedef90088f8d62d643b7e38e74f35346d7f21c5.nq.gz
│   ├── f1fc6c3d20ec2f09c6759f828d8cee2081c6c56e.nq.gz
│   ├── f26f5e0d5040ff44935968dcd1937f8e46d2adde.nq.gz
│   ├── f41ccd8169080024eb9e5c4ee6c78d7c07e3fc21.nq.gz
│   ├── f4af497094c8858c27873b01a8041a63b862b64b.nq.gz
│   ├── f8bdbc5fc2633c67c2b6e5a6559b19cafc7c06e5.nq.gz
│   ├── fbf7c072bb91be98a9d5a03c8542c208d29bb956.nq.gz
│   └── fec4a47c2bb191de89aef7eed76d4c3a418230ac.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   ├── 0916aef1579ae69767e9f41c6d859b6dcc17b8a5.nq.gz
│   └── 20f3ae1c23bf0decefb691f475a9506bd7ba47d8.nq.gz
├── filetree
│   ├── 0916aef1579ae69767e9f41c6d859b6dcc17b8a5.nq.gz
│   ├── 20f3ae1c23bf0decefb691f475a9506bd7ba47d8.nq.gz
│   └── 527eee0904f1ba12c659e467b1181d0c44c05655.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 80 files
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
