# Repolex Knowledge Graph of hynek/hatch-fancy-pypi-readme

RDF knowledge graph data for [hynek/hatch-fancy-pypi-readme](https://github.com/hynek/hatch-fancy-pypi-readme), parsed by [repolex](https://repolex.ai).

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
rlex download hynek/hatch-fancy-pypi-readme
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── fcf9bc6f7f28d4f13f8c9d8d04b8bc005d4e2de3
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── fcf9bc6f7f28d4f13f8c9d8d04b8bc005d4e2de3
│           └── chunk-001.nq.gz
├── blob
│   ├── 03ce010743d52f5502be5a0b596f927f10847047.nq.gz
│   ├── 057262b1bf99fb4b228fa07524df1aebc58c0046.nq.gz
│   ├── 06dd90469669e3065f72fc568991e06120e11a57.nq.gz
│   ├── 06e39d4c68e55181949c18b5129d2f9ee1b82306.nq.gz
│   ├── 0b547e8eba29001085456c8d64d00f9cdf8ad0d5.nq.gz
│   ├── 0e4a22c1fd8ee5ad2a0861db1432d48187f68c9c.nq.gz
│   ├── 11c12f4aebeef0dc0e2db524d3aacf5e7e0a5bf7.nq.gz
│   ├── 1d391dfdeea3a0c147f2fbf21a1b67257de2f4bb.nq.gz
│   ├── 1ee080578621d7c708763d386a6cc6939d797b13.nq.gz
│   ├── 22ae22e07275d6dbb33d6ec54b50745d9164a92b.nq.gz
│   ├── 23d2299c2cacf5cb401632b713c4a5f80f23feb6.nq.gz
│   ├── 24ee5b1be9961e38a503c8e764b7385dbb6ba124.nq.gz
│   ├── 2f9deaaaf74d36b5484831c0d13e6c7b4a934679.nq.gz
│   ├── 3169da5516f6c42164cba15d30271155335203f4.nq.gz
│   ├── 3270562a8b4d75e7f37c5263c5755507fb07ee0d.nq.gz
│   ├── 3bb69c9189b3f21f34c50b4d49c0224168630b76.nq.gz
│   ├── 40bab74b0a7f567ca8a7c67e2d06b60b43913591.nq.gz
│   ├── 533e3261260f92cb2603fb26a668b17d2dfc93d9.nq.gz
│   ├── 53d7518935d30bc965f45238e18b96796512d495.nq.gz
│   ├── 6080714a4ef59ea4113b69ad50bd1b835f783347.nq.gz
│   ├── 68bf533f114e393784d9973515db4390e792fec7.nq.gz
│   ├── 736cacc1417b23d220e9dd4a84531610b343be73.nq.gz
│   ├── 752461fed524fb0c4f638540cce5605dcc7406cc.nq.gz
│   ├── 7bcb03bc6211984615d3e932173ffd79811d1ae3.nq.gz
│   ├── 7c5100942aae489ca04d07d2c69a4d8f6f8470fe.nq.gz
│   ├── 847e6329301f96e3e2074030930c1258570955df.nq.gz
│   ├── 91131c129440f9f506b6fd2e36b105629b87b926.nq.gz
│   ├── 978283b8ec1bd2290e210f3c08b54fcdd7168d11.nq.gz
│   ├── a1167a18058768219e6f6c05d6adb402b4c2576b.nq.gz
│   ├── a770b620d2a2a9e834f8f7dc343ad28cca98e140.nq.gz
│   ├── afe3011b2742d569c4998e073e1a4c76b21945df.nq.gz
│   ├── b2c91b095ae6f29703d282c0fe3fb6c23b491762.nq.gz
│   ├── b316de10f17f6fd4c286f87c2f134ec22e966255.nq.gz
│   ├── b6a9b1ff8ddd298bc8790611535c04ea84394a26.nq.gz
│   ├── b7e65fa9f18bdacaad0d934937a3114ad7460378.nq.gz
│   ├── cd46bd07565aa2cf3aab3580363284ba2fac0458.nq.gz
│   ├── d621f5c71e54ef67dbba42636c71f84c557505ee.nq.gz
│   ├── e1f3a9ffd2fe028a479d4521e98cb45920d26d85.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── eb4444043d7c5805676b9e5370fe8e159dba6d5e.nq.gz
│   ├── eb51ae0c70638253fefa04ee4c2843d2a2f75411.nq.gz
│   └── f6316d6a81339e086c9c10b69f71464553a10e82.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── fcf9bc6f7f28d4f13f8c9d8d04b8bc005d4e2de3.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 50 files
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

[hynek/hatch-fancy-pypi-readme](https://github.com/hynek/hatch-fancy-pypi-readme)

---
*Parsed on 2026-10-19 by [repolex](https://repolex.ai)*
