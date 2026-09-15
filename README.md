# Repolex Knowledge Graph of dividab/tsconfig-paths

RDF knowledge graph data for [dividab/tsconfig-paths](https://github.com/dividab/tsconfig-paths), parsed by [repolex](https://repolex.ai).

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
lexq download dividab/tsconfig-paths
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 11b774d994b897c6c8e87dda57375a285813731d
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 11b774d994b897c6c8e87dda57375a285813731d.nq.gz
│   └── repolex
│       └── 11b774d994b897c6c8e87dda57375a285813731d
│           └── chunk-001.nq.gz
├── blob
│   ├── 154e15c5f4aab7e38c225c9d92cff5351b6bea7e.nq.gz
│   ├── 1b8ddb9a1936e941286675cc24688ba8ca042c63.nq.gz
│   ├── 1ea0c0cecb3d1930425bb5deb9d8cb7d549ec2fd.nq.gz
│   ├── 1fc7fea45e76c0ca87f70c13118a5bea6d5de700.nq.gz
│   ├── 21f4aa6eda8cf04d04dd0b5332689621521dbf8f.nq.gz
│   ├── 303dd2dd0886b297c868b587708d60165cec09f0.nq.gz
│   ├── 390cb9ef4fbac46f190398104bf5fffaec92a04a.nq.gz
│   ├── 3ae924f8d4695bc4667a029450fdbaaf7359c67f.nq.gz
│   ├── 3c37ab250acb9f1295b97caf6f05b43b4145afe5.nq.gz
│   ├── 3c39b17b22a0c928e31e611924c6b18f9167dd11.nq.gz
│   ├── 415d94d7393f3fad96b0c541f4a4b0db2f46f962.nq.gz
│   ├── 429e834778159b4afe9188bd412eaa4c242fb071.nq.gz
│   ├── 4408e7ceb4cde1004948237a5abd34a294865461.nq.gz
│   ├── 4f9a8305426a5351c8578b3e9ce8567b6545fd0f.nq.gz
│   ├── 549d44f6342960dca857414c005819f8562ffd66.nq.gz
│   ├── 56be4daf452b681168ba638e4d9299f52f5dfbc1.nq.gz
│   ├── 5b3d4694bdc27b872a5e20a53711660285edc44a.nq.gz
│   ├── 650f1852fbc6afb1ae9261728ab32949454cae27.nq.gz
│   ├── 65c38bee13cde34706d7ed285ee95923b13c7b44.nq.gz
│   ├── 6f31f8ba142f3ca721abbb64bcb4894e5a09c3f4.nq.gz
│   ├── 75b6288895f79a1feda8746b1f2f60a65f07f436.nq.gz
│   ├── 7a359c2e9e0c798eaed6d211d4a33d36b355df0d.nq.gz
│   ├── 884c7e3b186fcf6829ccb30847e53e3c0bb344d6.nq.gz
│   ├── 89f5cc2dd429970f017e1d8d02dfab1c75992c8d.nq.gz
│   ├── 90d2752d060934970c71bc8e3b53c2765d9495fc.nq.gz
│   ├── 9cf1f14af94fef98e4d722bc7afdf88b7278803e.nq.gz
│   ├── 9dac232666dbd9ffba8354a9d62feb1016527865.nq.gz
│   ├── 9e3bf9cd3faa657f41ad609558ea693fb0601cbf.nq.gz
│   ├── a337580653fb20549eff9c3777524d7912ca7f01.nq.gz
│   ├── a91adece426955cc1c2190bc77ce4a2a23f97eba.nq.gz
│   ├── b0e6ba0e821f7914b1f7a1dcb04394632e125d21.nq.gz
│   ├── b37221a4654304940e305a6003095a0ebaf62a9f.nq.gz
│   ├── b6e3d797cb5025224bbd90021f0ba31426977099.nq.gz
│   ├── bf8105262371c12228708f56fa4dd38a19c53c03.nq.gz
│   ├── c366c408ac4fdbf70f2c684c68c4ccc2be58f95a.nq.gz
│   ├── d4f60b4581a3e94eed8fec3a058a12c85b8f30ae.nq.gz
│   ├── de7e7580da9acaa0c5060d4a8308b1b89b6f1c24.nq.gz
│   ├── f662311767f5e2cc590bbf205acad3c2c124f35f.nq.gz
│   ├── f6819fb627e31a0c3ba1b8fc9c9d917cea2a6aed.nq.gz
│   ├── f8d76f55d598d2c84324d23dea5e761e62c29419.nq.gz
│   └── fdd958af8f0703a1554d54a10f194aa2bdd2cdcc.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 11b774d994b897c6c8e87dda57375a285813731d.nq.gz
├── filetree
│   └── 11b774d994b897c6c8e87dda57375a285813731d.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 51 files
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

[dividab/tsconfig-paths](https://github.com/dividab/tsconfig-paths)

---
*Parsed on 2026-09-15 by [repolex](https://repolex.ai)*
