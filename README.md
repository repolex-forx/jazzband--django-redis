# Repolex Knowledge Graph of jazzband/django-redis

RDF knowledge graph data for [jazzband/django-redis](https://github.com/jazzband/django-redis), parsed by [repolex](https://repolex.ai).

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
rlex download jazzband/django-redis
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── d646a755e13dee8861e15ac515cfe785ebf78274
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── d646a755e13dee8861e15ac515cfe785ebf78274
│           └── chunk-001.nq.gz
├── blob
│   ├── 05ac08ab850f08d7b8adeeca1188c3a876c771c7.nq.gz
│   ├── 075ecf097415e9839837c5994ecfc54a5a4efd10.nq.gz
│   ├── 0eeafd851413b0be32e107fda026752c67a92d12.nq.gz
│   ├── 0f346add099dfc95f545d26b750248a3ea9efbd3.nq.gz
│   ├── 1a4db61b5b2733165db790ee601be2ba693d489a.nq.gz
│   ├── 1f6e5ca6b9839f4c9277a52b8f79bdd1495e81ad.nq.gz
│   ├── 214039d6792a51488b78d61d7ba4f08aa4aae1b9.nq.gz
│   ├── 272d1e7d61de88d5fcff8bb7765a7fe894f6e723.nq.gz
│   ├── 35b9000be2484dd6dc50bdf6d2d3e1c6b1817cf6.nq.gz
│   ├── 3c0e0bfadc52dbb62bf8759e498321d529da227f.nq.gz
│   ├── 414bbafe484d1df1c4a0dafbb649fc255e7fcb04.nq.gz
│   ├── 41c0a9e6de888a730e0b14dd571831f2aa7381f6.nq.gz
│   ├── 427fd0910ebf25647e38e4f2691c639238eaad53.nq.gz
│   ├── 42fb993f7ec28fb0901c6f51c31117adca1abe9c.nq.gz
│   ├── 463d543bceffce03edbe0bab818eb02f53b11187.nq.gz
│   ├── 493868712e604e9be75a51f986f4d0c8f77ca14e.nq.gz
│   ├── 4b4db148edd7e11a47849c07a164d4eeca29452c.nq.gz
│   ├── 4b91465e1ffa1387c1e631636a35a98b4a708efc.nq.gz
│   ├── 4bc23301544d9dd7a509e0cfb913026b33455891.nq.gz
│   ├── 55be75b43b3daf63e696ca45080b9a81edf21548.nq.gz
│   ├── 57805bec1962d16573bf55c73b4861f958bc75ac.nq.gz
│   ├── 5aab45ae2bc4b267278e5ffd26ac16c388ef1bb9.nq.gz
│   ├── 5af4773019d1367b12c67cce9db1f696cbb1750f.nq.gz
│   ├── 63bb9f4624c0a08a6b3277c845faaaeeb788e881.nq.gz
│   ├── 654a9df6e43a93c94fb90cf577d4a496dee4e9c9.nq.gz
│   ├── 6879bae31c9f463fb6db110e430aa713640b3bed.nq.gz
│   ├── 69563f8bd19a74c4b6386f38dec27ebfec8a0b30.nq.gz
│   ├── 69ae6f90203078e2dc2faa887260df529b285ec3.nq.gz
│   ├── 7724146394b17d161a7ac8f8489a92bcce058f28.nq.gz
│   ├── 775db0695a347f37412fac42327d6b7c49347f13.nq.gz
│   ├── 78afae261ce38d4fbcf1154950b846bceb78f781.nq.gz
│   ├── 794f5fe713dcfde503d6ef0ccd2246e7cc38260e.nq.gz
│   ├── 7fe36d0b3bf1bdcbb3c81a232b033651393b6ecc.nq.gz
│   ├── 889e33da13f3c1c3eea5726123da497fe13d911b.nq.gz
│   ├── 89da4e6555332b53046767c3900e4b2e9c9ca433.nq.gz
│   ├── 9449345da10e486a20e101536afa6928cd22f1a3.nq.gz
│   ├── 95233fa4f02172426c7433453aa1703ca808fe66.nq.gz
│   ├── 955430332553c5390441f43c0361ede6a0241833.nq.gz
│   ├── 9cbeaf38140b98ea4d4dbbe018975bd3eb8462d3.nq.gz
│   ├── 9d7bd72ea0c728a41fb14edced9f80539d143738.nq.gz
│   ├── a00c9f784a2fd1961e30c59509b36c37d3c4b1af.nq.gz
│   ├── a03590f54d8b03c2bee4276a20b3bf402d26b06c.nq.gz
│   ├── a0ef2fc2f0417cbace206dccf22aff93ddd46244.nq.gz
│   ├── a28cbe8c2b1fee8b1e0a4187f31591d8584ce1db.nq.gz
│   ├── a7beef24b171281ae8feb4f600561bdff6ec6861.nq.gz
│   ├── ac7d359844f5d7a06b3fe6a8787e405bf56b993e.nq.gz
│   ├── b18b7531ecf447c2e29c189144a3f23fea2368c3.nq.gz
│   ├── bb58d92f7990f6180d200508d28ac6424e8511cd.nq.gz
│   ├── bc3d70c8fa3fbb8302ba46337a4cd55d17283faf.nq.gz
│   ├── bde01a3faba85015b74bddca33fa478b512b6b7d.nq.gz
│   ├── c02151e7c57fd70109e99daebf3e785395ace788.nq.gz
│   ├── c3d84308cd61bdc8fb81c93d3475611a96326121.nq.gz
│   ├── cb3f69b6db685358cdb8c0f687031b5197c69471.nq.gz
│   ├── ce0aa1c7038d95ee482c64042f647de837b49f81.nq.gz
│   ├── d0dc5c6c929d325547a02f784aa3f60c1e3c8775.nq.gz
│   ├── d6deb19c58930e152ebe5d97c68fcadae245ffd5.nq.gz
│   ├── da95698d58948d0e303bfd96b96950f2de4d4e34.nq.gz
│   ├── dabead299356d91f6ed1e2691bacc746d3caadb3.nq.gz
│   ├── df5c988054dccf5b56b898f9dee9c53a77b68448.nq.gz
│   ├── e0d5efab56fb94577e7804603eb6f21f36977cb2.nq.gz
│   ├── e181016b6448621ccee947568affb7a507b516a1.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e8cd11beae5caf30cada776f9958291787c804bf.nq.gz
│   ├── e8fbff24191f0a1adfe7b06c00d9285433a6e4af.nq.gz
│   ├── ec68f143007322044744b6fe42b16194467b0c05.nq.gz
│   ├── f03ad681d7bdb62f31e7f959ccf723501cb9112a.nq.gz
│   ├── f1d9125b130398909f0a4ff0ec3412563d2d5843.nq.gz
│   ├── f347d9ca0a7b7b9ed517383a52146c74cab0b882.nq.gz
│   ├── fd232e77418253dc09bb7d5b0a282daf7a66495a.nq.gz
│   └── fe93498d8e2e7b8de1782867bbb4149cd0eeb0e9.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── d646a755e13dee8861e15ac515cfe785ebf78274.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 78 files
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

[jazzband/django-redis](https://github.com/jazzband/django-redis)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*
