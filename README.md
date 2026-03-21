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
│   │   ├── 0262c9200059bb0706df65c36c9135e6f4e9888c.nq.gz
│   │   ├── 0916aef1579ae69767e9f41c6d859b6dcc17b8a5.nq.gz
│   │   ├── 17c7bfac3ceec193bdeb03f5f6d26155e78108c4.nq.gz
│   │   ├── 20f3ae1c23bf0decefb691f475a9506bd7ba47d8.nq.gz
│   │   ├── 4f65514392baeb264f740e7b5df04365b360f14a.nq.gz
│   │   ├── 527eee0904f1ba12c659e467b1181d0c44c05655.nq.gz
│   │   ├── 8db12a847c68723ff3e04775b673ca0a41235f8e.nq.gz
│   │   ├── a06824d4f1cfd0198c9ba2ad52ee35fb4b725331.nq.gz
│   │   ├── a7f9c228226fe1ff030e1a545226f965edd3b29b.nq.gz
│   │   └── e834a1ef2a51d4777a5bd99b03b671f719d217a7.nq.gz
│   ├── lsp
│   │   ├── 0262c9200059bb0706df65c36c9135e6f4e9888c.nq.gz
│   │   ├── 0916aef1579ae69767e9f41c6d859b6dcc17b8a5.nq.gz
│   │   ├── 17c7bfac3ceec193bdeb03f5f6d26155e78108c4.nq.gz
│   │   ├── 20f3ae1c23bf0decefb691f475a9506bd7ba47d8.nq.gz
│   │   ├── 4f65514392baeb264f740e7b5df04365b360f14a.nq.gz
│   │   ├── 527eee0904f1ba12c659e467b1181d0c44c05655.nq.gz
│   │   ├── 8db12a847c68723ff3e04775b673ca0a41235f8e.nq.gz
│   │   ├── a06824d4f1cfd0198c9ba2ad52ee35fb4b725331.nq.gz
│   │   ├── a7f9c228226fe1ff030e1a545226f965edd3b29b.nq.gz
│   │   └── e834a1ef2a51d4777a5bd99b03b671f719d217a7.nq.gz
│   └── repolex
│       ├── 0262c9200059bb0706df65c36c9135e6f4e9888c.nq.gz
│       ├── 0916aef1579ae69767e9f41c6d859b6dcc17b8a5.nq.gz
│       ├── 17c7bfac3ceec193bdeb03f5f6d26155e78108c4.nq.gz
│       ├── 20f3ae1c23bf0decefb691f475a9506bd7ba47d8.nq.gz
│       ├── 4f65514392baeb264f740e7b5df04365b360f14a.nq.gz
│       ├── 527eee0904f1ba12c659e467b1181d0c44c05655.nq.gz
│       ├── 8db12a847c68723ff3e04775b673ca0a41235f8e.nq.gz
│       ├── a06824d4f1cfd0198c9ba2ad52ee35fb4b725331.nq.gz
│       ├── a7f9c228226fe1ff030e1a545226f965edd3b29b.nq.gz
│       └── e834a1ef2a51d4777a5bd99b03b671f719d217a7.nq.gz
├── blob
│   ├── 022cfeaeb7624f6e4208b6dc0b114c2304e2a811.nq.gz
│   ├── 04a3e9fbb71d435914e7198a5c2bda2076a668de.nq.gz
│   ├── 0524b6dff762c50bdf677281fd1063dcdc4dee8c.nq.gz
│   ├── 06d9d1f62b4c4e3a052d60589f725a742102def6.nq.gz
│   ├── 082334c0d25dce37b24f45a448d13c8d29cb4e26.nq.gz
│   ├── 088a1a4559bb4df390a1419988421f01c0d50125.nq.gz
│   ├── 08ef63a6302c7006bb7daaf2afc88095a4dc45c4.nq.gz
│   ├── 0a4197a65eac97b4a955b24423ed4dfec836812f.nq.gz
│   ├── 0ad96aa69d17386394f63ab1c51a49c24479101b.nq.gz
│   ├── 0c2016c2870e7aa49e7f6555ff77c0e8e24d7448.nq.gz
│   ├── 0e52d759518d8f7d45841efd9407e875753033ca.nq.gz
│   ├── 0eb8b3ae7bc87804b81142050b92d1508d750562.nq.gz
│   ├── 1024f1bd55e8eea7d845cd861eb96f6987e5e182.nq.gz
│   ├── 119123d7b6b44e7ad5aa0260fd1e35f1f5d58a2f.nq.gz
│   ├── 17f94c78b9a2d91745e9bdee904793f9989b7820.nq.gz
│   ├── 1816493e8595495036e8a19109375ece3e004ffc.nq.gz
│   ├── 18fa062d1af60d2fd7e6ff53b1dbd9cd4702ba03.nq.gz
│   ├── 1ab8d27090ef49d883dd5614c4f2628b1007c113.nq.gz
│   ├── 1df58bdde09b7e450e0772016a3c4563c3457e98.nq.gz
│   ├── 223c6be43e77cbd377d86d01809417f880fd2be2.nq.gz
│   ├── 235752d22a3a899aa19e9a75be928ed7ac599a47.nq.gz
│   ├── 24ee5b1be9961e38a503c8e764b7385dbb6ba124.nq.gz
│   ├── 25e24c60044a792c05b8778b7f962bdfe1d1cd92.nq.gz
│   ├── 261efa1bb1ba546da7b4144fff1eaac15ff42167.nq.gz
│   ├── 27126a40b4486269118c01ff79456bd8fe32b4ba.nq.gz
│   ├── 28517bc88e11845bacfab985df9fd8f77594431a.nq.gz
│   ├── 2c1369df5af5a407ee60799920bec453c7b712ec.nq.gz
│   ├── 2eb3eb802fe614636fe83e7cc3b22cf839476050.nq.gz
│   ├── 2fd68ad9c8071f626df7047fb1aba4faa987a3e1.nq.gz
│   ├── 2ff181934ebd9c4c0e343a376a3fd19bd8986bad.nq.gz
│   ├── 30fe1a30e2653417d4eccc8d77b653ae710f02b2.nq.gz
│   ├── 37da525e06691b813a5abe1c0a669c1bfa98714f.nq.gz
│   ├── 3821211c781e7af9370eee16714641a1c815346e.nq.gz
│   ├── 3a103455d3417a834e14061927c5c54552de5cb5.nq.gz
│   ├── 3c85687f3ac3b0cc7fb2a9883aa831be0cd9906e.nq.gz
│   ├── 3d2e2028f16a6bac389b8bb91163bed42d3f45bc.nq.gz
│   ├── 3eb0d4cfbb843c048092b6b7749021526030ea9d.nq.gz
│   ├── 4158d8429b3e88b4ddeb7b0e4f3fc056aec6f572.nq.gz
│   ├── 483fec392b209bd22341faf2980a9b2d69dc47f1.nq.gz
│   ├── 496c6893d1916769f58e891cd8b30cb4286f54ed.nq.gz
│   ├── 4e24a72a11b666c094894e7602ea7a69cf5cb3b4.nq.gz
│   ├── 4f9f5bec323d1887718ba998155b68981a279304.nq.gz
│   ├── 50fa0cb05712f9b9bc37d155717e527e912c5146.nq.gz
│   ├── 54a9e135a38d7e57863228b51a02c60446e9209b.nq.gz
│   ├── 562612f251067f508d195c19cc44d7c9e83f12ef.nq.gz
│   ├── 5654f930ff5fa3e2910bdc48d97aa2b789d34002.nq.gz
│   ├── 5a9cb52261f4edd81200f71d98669bf61921dc24.nq.gz
│   ├── 5b5e83e70c4cb9921ef590287a0a95803e08d068.nq.gz
│   ├── 5d9a02c3217bcd82e197530569e79246fc526f52.nq.gz
│   ├── 60c3b6857184b1583c080fe161b0123cb1d7f52f.nq.gz
│   ├── 652cd7f5735592869e03410f00f1e23285eb4b3e.nq.gz
│   ├── 667446ca53fe038b16ad93c745efd81b5fe0eea1.nq.gz
│   ├── 6a30597b19e3b03d8bebefd310d1641af07d8d33.nq.gz
│   ├── 6dd75a9d819c5e65c2109ec9366241b506575f28.nq.gz
│   ├── 7185ecabfc399b3d7cde364d06688d37f89612ca.nq.gz
│   ├── 73186ba25b2c026bfb3f2f31cc7a7408425de0bb.nq.gz
│   ├── 73b802bf0bb0635df352073ecd716f4a0834f22e.nq.gz
│   ├── 742b44a20b88ba6556879660689ed6279db19ced.nq.gz
│   ├── 75306517965a54731b94dca8bace640e856af115.nq.gz
│   ├── 768f473b274732f973e3739c5330a151c640559b.nq.gz
│   ├── 789cd208756681b7ca234453aa2ed892ac6eca08.nq.gz
│   ├── 78add191d05304da7de4f0c79ba1f704ef12b061.nq.gz
│   ├── 7a9766bbee498c734386a14139c2bb28d409073b.nq.gz
│   ├── 7c48640c2260e1dfa9a4c8dc3febb8da9af3eb73.nq.gz
│   ├── 7d133fd3feb9f33365d3ae441b77a4e07087c5c4.nq.gz
│   ├── 7eda4074acf832d17a64b600da491a970ccf1e20.nq.gz
│   ├── 82c2506acd644adc79d4ac2d4110891b9c120c1b.nq.gz
│   ├── 83d271d57d3006aa5d19318c4915aaef64e49e11.nq.gz
│   ├── 841ea1c61d6914be9f7d63b3409cc6acdcfe34aa.nq.gz
│   ├── 868ce68eb1055b1336ef3062acefab7725f024c4.nq.gz
│   ├── 883e8a087b8fb228ed866e2845be093fdf998ee1.nq.gz
│   ├── 896c564fd36f99c056e79b18da2a5c8f67ac6d32.nq.gz
│   ├── 8b207bf95a1a8215551025b99664420a8770b30a.nq.gz
│   ├── 8c50a3dd59e3d8329b13f252f869ffeb732bcc8c.nq.gz
│   ├── 8cb658f97a7717c1ba0e19b0d2c5dd48319d5d3b.nq.gz
│   ├── 8e687608718d4196a68b015016cc382d08ca4032.nq.gz
│   ├── 8e758ba1ad64c034d0c8ef4c35d2cf39722d7889.nq.gz
│   ├── 901b30d7eba795fef0e2cb42922a9b7ed35dca81.nq.gz
│   ├── 90c83ac9ccc9119a30ef5aabb4cf3adcd6430a14.nq.gz
│   ├── 919952fc9eb550ca20f401bcd3fe00536c027529.nq.gz
│   ├── 95123fe845ebd1f78c54c6b21321b0d4845acb75.nq.gz
│   ├── 9572fde7813b2a10bc52400944ff0a3e00ee9975.nq.gz
│   ├── 95b549ed50448569a2835e9c73020d4d7467c1d7.nq.gz
│   ├── 99115194e92e09993ac26325e2d4e3005b539a2e.nq.gz
│   ├── 99835be639deee7c2b074a9076af711ac03a58e1.nq.gz
│   ├── 9ae6e06dbfddfd89c34c1a8d6ee5343bbc8420a5.nq.gz
│   ├── 9de2ed4d8cfbcde4fb78562c69133080c3af5fa5.nq.gz
│   ├── 9e71b090bd9af3044c6f0da609c6c86174f7e472.nq.gz
│   ├── a4f5adfce30409748b33f164618f36a0195da549.nq.gz
│   ├── a65fa4316811fe50e25e36d96a8266762a003042.nq.gz
│   ├── b14079ca2c558349e85a6a17057464bf31bd1c19.nq.gz
│   ├── b1e5be348cdc6d60fe122bc4e3c7261e0b0efc9e.nq.gz
│   ├── b423f1e31358ebdb5775a52e7cda514ea479dfed.nq.gz
│   ├── b8fc858110f20622692eee333be41c4fcdf6db56.nq.gz
│   ├── b9af05c083fe901948752c6777a551dad64f94e1.nq.gz
│   ├── ba1ce1634cd7e41d5f6f66853ee475d23cf1506d.nq.gz
│   ├── bb0ae7e25f1566b8dbfedaeaa41d3fb0af7cb6be.nq.gz
│   ├── bbca82af971215bf1079305b554276efc1f88d1b.nq.gz
│   ├── bdf87561ce7c1ca762033028f59d17ba77692b7b.nq.gz
│   ├── bebf9a07e05d9d2a41be32b3315ed3b730585bf6.nq.gz
│   ├── c000a50e4c5d0da502470fe4705f72a9d3751dc7.nq.gz
│   ├── c0e4ef08814f44af53afe55670db97c99a3f24af.nq.gz
│   ├── c13e54a4b7cfd698f6d1328f1b7060606bd52927.nq.gz
│   ├── c20592cd173d5f8ae520fe805b513e51a33f6e95.nq.gz
│   ├── c21f936baef6a0ec3b759c172fece935babe7d1b.nq.gz
│   ├── c2272f057fb5b03dedf110c21efc73289f1c89cb.nq.gz
│   ├── c38074d195986dc2d576cc8c9ab337aa18d7f05c.nq.gz
│   ├── c64cf55973191c19c8509de64f50af9865363355.nq.gz
│   ├── c746b8b902e202e9e1c6da5fb24d1fdc9e254da8.nq.gz
│   ├── cae6dd83611df49c8e50ebbb3b10303f7fccfa01.nq.gz
│   ├── cb597b2822a2f861f426bfea66cebe129002df9e.nq.gz
│   ├── d2a21f771da38847ca06653ef5266effc3f89090.nq.gz
│   ├── d38a2b01c6b1770c98f827179b2982f51125608c.nq.gz
│   ├── d6216f573deadb0e475942b630cc9c3f474377ea.nq.gz
│   ├── d688d60a989bb6394f217d5076ad72e217f45db0.nq.gz
│   ├── d828e9d4bbd885144a82098bf78841208f698dc4.nq.gz
│   ├── da561b9e06906c5ae459027a0a373d8c085516bb.nq.gz
│   ├── db95231403c2082aa240a3ae9ac6e50455d21c38.nq.gz
│   ├── dbd589197bbcdaa93ff8c323f8f19e5bfa1e4c7d.nq.gz
│   ├── ddfc5c455bdfd8b0a07309ec9a9d451c04aca430.nq.gz
│   ├── df675ce60e5531ad9b4f8089f0cade65b17a2517.nq.gz
│   ├── e2e856fae4b340157513751c812fe52956b2025d.nq.gz
│   ├── e3056aa8fa9b47eaeedf115eaa1c3a8f7f01ffc9.nq.gz
│   ├── e48cffab0fb5c6e16a6495152852cab94ca06816.nq.gz
│   ├── e5865a441847f84cc7711ff4f1fff54e026768ed.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6ab32c40e9a8843ca8ab37483cf8dfb590f7825.nq.gz
│   ├── e76acd3c24cdcc369da602e1a771cd9e1f0cba08.nq.gz
│   ├── e87eed8ff5bf4dfa00f5f90714cd9ee750624c39.nq.gz
│   ├── e9bf3d90f41e92874a23c00f61ad04800098687a.nq.gz
│   ├── ebef2a83ca6a24cf648d585ede674cfbba901819.nq.gz
│   ├── eedef90088f8d62d643b7e38e74f35346d7f21c5.nq.gz
│   ├── f02a052dd65f69d55b0863e18e814bb19d06ebb5.nq.gz
│   ├── f074184b1c2d09d38a66b6f2edbfc2dff3b08490.nq.gz
│   ├── f12cadf5d3dcc9357c96c7b19b66fb82a3977194.nq.gz
│   ├── f1fc6c3d20ec2f09c6759f828d8cee2081c6c56e.nq.gz
│   ├── f26f5e0d5040ff44935968dcd1937f8e46d2adde.nq.gz
│   ├── f41ccd8169080024eb9e5c4ee6c78d7c07e3fc21.nq.gz
│   ├── f4af497094c8858c27873b01a8041a63b862b64b.nq.gz
│   ├── f8bdbc5fc2633c67c2b6e5a6559b19cafc7c06e5.nq.gz
│   ├── faf0a7ddb79c72b7b97f04af5236ed471fe9fd5f.nq.gz
│   ├── fbf7c072bb91be98a9d5a03c8542c208d29bb956.nq.gz
│   └── fec4a47c2bb191de89aef7eed76d4c3a418230ac.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   ├── 0262c9200059bb0706df65c36c9135e6f4e9888c.nq.gz
│   ├── 0916aef1579ae69767e9f41c6d859b6dcc17b8a5.nq.gz
│   ├── 17c7bfac3ceec193bdeb03f5f6d26155e78108c4.nq.gz
│   ├── 20f3ae1c23bf0decefb691f475a9506bd7ba47d8.nq.gz
│   ├── 4f65514392baeb264f740e7b5df04365b360f14a.nq.gz
│   ├── 527eee0904f1ba12c659e467b1181d0c44c05655.nq.gz
│   ├── 8db12a847c68723ff3e04775b673ca0a41235f8e.nq.gz
│   ├── a06824d4f1cfd0198c9ba2ad52ee35fb4b725331.nq.gz
│   ├── a7f9c228226fe1ff030e1a545226f965edd3b29b.nq.gz
│   └── e834a1ef2a51d4777a5bd99b03b671f719d217a7.nq.gz
├── filetree
│   ├── 0262c9200059bb0706df65c36c9135e6f4e9888c.nq.gz
│   ├── 0916aef1579ae69767e9f41c6d859b6dcc17b8a5.nq.gz
│   ├── 17c7bfac3ceec193bdeb03f5f6d26155e78108c4.nq.gz
│   ├── 20f3ae1c23bf0decefb691f475a9506bd7ba47d8.nq.gz
│   ├── 4f65514392baeb264f740e7b5df04365b360f14a.nq.gz
│   ├── 527eee0904f1ba12c659e467b1181d0c44c05655.nq.gz
│   ├── 7d68375d0863bb4c1998f7844e11eea7709ac83b.nq.gz
│   ├── 8db12a847c68723ff3e04775b673ca0a41235f8e.nq.gz
│   ├── a06824d4f1cfd0198c9ba2ad52ee35fb4b725331.nq.gz
│   ├── a7f9c228226fe1ff030e1a545226f965edd3b29b.nq.gz
│   └── e834a1ef2a51d4777a5bd99b03b671f719d217a7.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 199 files
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
