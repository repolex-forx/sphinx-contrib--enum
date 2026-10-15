# Repolex Knowledge Graph of sphinx-contrib/enum

RDF knowledge graph data for [sphinx-contrib/enum](https://github.com/sphinx-contrib/enum), parsed by [repolex](https://repolex.ai).

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
rlex download sphinx-contrib/enum
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 9e0ac3197e2a937c5b755686d967a00aa787d889
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 9e0ac3197e2a937c5b755686d967a00aa787d889
│           └── chunk-001.nq.gz
├── blob
│   ├── 030d1191cfeaddc445514894fcb148cd38611a65.nq.gz
│   ├── 03e9709a2c018d0481859a3d778dbdbb815043bb.nq.gz
│   ├── 0ba46c7c70943e98bffbe6cce44d49f3286e6a91.nq.gz
│   ├── 0ed8ef4411c6bc0c5e4d47ae5921d12cc062cd43.nq.gz
│   ├── 1df2e91cd0ee0c7508decd08e87d233d01784e72.nq.gz
│   ├── 21e959ff42d8b5b467c154c9473949f6e13e0b7e.nq.gz
│   ├── 23c1a00515e54e7805298c95d896077de4834ab8.nq.gz
│   ├── 276182b4c47c0b2d3f01c498079e1abd8aa23d44.nq.gz
│   ├── 2964b50a82124d5f0c063fce5fe9a583f65cf955.nq.gz
│   ├── 2beffba55a0bfcc56a581ca3b657552dde74f609.nq.gz
│   ├── 2d712698326a3ac9b3e7aeb427a814eca240aa08.nq.gz
│   ├── 42770f105f46e680d92353fb26d5fc07c2e270b7.nq.gz
│   ├── 45035869dd00103f1ba9dd7e67c111565308a2cb.nq.gz
│   ├── 489df13cdf986066ea9018c70de7918862e74949.nq.gz
│   ├── 525511cc2cb40a32fcb9ce8f824c08b0289f086a.nq.gz
│   ├── 5ab553a2494de9d91e074496fea06d685937135c.nq.gz
│   ├── 6023da72e35204b5a149ccdb9d58a6780c8494ea.nq.gz
│   ├── 686f29e439bef61e8304e9f939d54774532c8a94.nq.gz
│   ├── 744f7cb1f9f4e248d03e95fd65da75710883c408.nq.gz
│   ├── 74cea03822505664053b9c88db99cc6abdc3efa3.nq.gz
│   ├── 82a582109db0bdf03c79cbfd54029b2c6c0d693b.nq.gz
│   ├── 887afdc2ce6f989baaaf285c2d5d2634e1bc7b59.nq.gz
│   ├── 8b6a7d4d4237d36aa7452c716b26edc00d6c9797.nq.gz
│   ├── 909cdfb1dd8a7b4bd321ee33d24e61f1d4dcd4f7.nq.gz
│   ├── 91ae945efe26b2d5966af41385bc8d22ebc7abfe.nq.gz
│   ├── 990ab4f8548c2a98aa47bb1f3e4699a6df63c627.nq.gz
│   ├── 9badf4d02a8ee2deb4181842a285b4cafe3c9884.nq.gz
│   ├── 9eeec5cbf26806c7897f3eaeef443f3d5b9d0a91.nq.gz
│   ├── a8a3fb1c6deebd9557c8aa143a862f7f7b15ab0a.nq.gz
│   ├── a999873773d7f1a1edc8ec5f770eeac0f9e1f0f3.nq.gz
│   ├── ad5e1ccc410de1dc00022f44efdb24ac21fd5885.nq.gz
│   ├── add0481f665772c03de558bd92e1afa7ab1bd473.nq.gz
│   ├── b1bf7383b7a67ca0dd63b37d15748a306c6fa86b.nq.gz
│   ├── b2a2baefed6dcd671499c64bb524e6bbeca57cd7.nq.gz
│   ├── bce217f026210f065e0381dfc8ade5ec44980fe4.nq.gz
│   ├── bd1158d8529857707fde8071747b18b74e3a60ab.nq.gz
│   ├── bd6b727dd6a473725f2053d41f04f412ae2b9955.nq.gz
│   ├── be1663f24ab62528e09a150ac2b4aa08640e63af.nq.gz
│   ├── c24d964b7078afa0ca23d928ff5cd9f620a5a901.nq.gz
│   ├── c65e999dcee199f3910d6d0b7260f8a60ffeaf78.nq.gz
│   ├── cc7881a38263eebbea4b45956493dc1fa9f51ac0.nq.gz
│   ├── cd2cb70d8cab1a41c502b9f93478a96a6398696c.nq.gz
│   ├── cf3c3b177765daddfa73bba7647ee79041f43ce9.nq.gz
│   ├── d80df64908d5bdf0ca07cdce93423096096b812d.nq.gz
│   ├── d8eea86f4589cde596cb26a12384e3fac03a448b.nq.gz
│   ├── e2f7728e1552518fde08c7c05dd78f45e83c5851.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── f794b174683f5bd83ab42da8c21ff5ed2f79af0b.nq.gz
│   └── ffbbb930b6fe0c34c03ecc5777c2c3a4061560ec.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 9e0ac3197e2a937c5b755686d967a00aa787d889.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 56 files
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

[sphinx-contrib/enum](https://github.com/sphinx-contrib/enum)

---
*Parsed on 2026-10-15 by [repolex](https://repolex.ai)*
