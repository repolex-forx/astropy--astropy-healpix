# Repolex Knowledge Graph of astropy/astropy-healpix

RDF knowledge graph data for [astropy/astropy-healpix](https://github.com/astropy/astropy-healpix), parsed by [repolex](https://repolex.ai).

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
rlex download astropy/astropy-healpix
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 0e2455577192e10bc7a404ce9b55ca1fd3df928e
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 0e2455577192e10bc7a404ce9b55ca1fd3df928e
│           └── chunk-001.nq.gz
├── blob
│   ├── 04bf73218848e15be49996a640aaf043a657da9c.nq.gz
│   ├── 064f332f8b238f8498ea49f94e3705267ec727cd.nq.gz
│   ├── 07bba0901c2d747f0d052ba0ad9ab6c6c45d4b7a.nq.gz
│   ├── 0b5ad4e275ae800765831c5ba4a3f4cda6f39f51.nq.gz
│   ├── 0e9be2576f0c4f0cf5c90f1650b03a693306c1e6.nq.gz
│   ├── 0fa59f28180b7e104f894478f79eb423811c583e.nq.gz
│   ├── 0fcd3cd4d6fa5e19e31f7c780231bc018e4a6b71.nq.gz
│   ├── 11439d61467e82ba87f5ddd8bd64b612b48cf185.nq.gz
│   ├── 1170460e14d2fa271e40fb24ab43454ba228edab.nq.gz
│   ├── 14b69b4742f8d5b2cd8b6cf3ed68d56b6571b2c4.nq.gz
│   ├── 15cf52855b44e633cac03eebd762d97c6c0a85ba.nq.gz
│   ├── 16217194a93a6d51c2c53697c949abd48515c84a.nq.gz
│   ├── 230cd6e20ddda4a66b501be05af441ced411c102.nq.gz
│   ├── 23c1a7e983e0beb173d2ba8de862f4e6ad8967e5.nq.gz
│   ├── 285631f79f45de9287d0d85e9f48b33c42d45ecb.nq.gz
│   ├── 2ad56cad60534dd9adc428e0f84cf5592fd020cf.nq.gz
│   ├── 2f7525a86f5ce0922550fcd336f9c7a454b6c807.nq.gz
│   ├── 30906e4e2ca422262cc7e1f26c70b0bbd750550e.nq.gz
│   ├── 319bd61498e1d39c24a83dc48f1c6f966e04650f.nq.gz
│   ├── 33a2c38222cd73713d5fe5951eceec6040a77758.nq.gz
│   ├── 387aec885d4c0c9fc6259c07d663bf96166f31c8.nq.gz
│   ├── 41cf781e67d0b283ca041e21aceb453b14f146ab.nq.gz
│   ├── 44157bf1dadbd58a5bf134634aa337aebddcc414.nq.gz
│   ├── 4a5c6c83630d091f6a7ea0e916a56154d42e55e1.nq.gz
│   ├── 4ddd6f343f5f876051626db83ccda7b8695f2cd2.nq.gz
│   ├── 4de81e8891b213d23d79bd4db864a46108e45095.nq.gz
│   ├── 4e5a652bd4073c49902a894e88bc1ea640ffa44d.nq.gz
│   ├── 50383996f25ee4efad288dc9f731d01033a8d492.nq.gz
│   ├── 518b968b774afd0a264411ebdbdb2b742640e880.nq.gz
│   ├── 53f29cc78368c8275dc1a4b41812cc2db8a9cc75.nq.gz
│   ├── 540445f7672cbc543e553f5eebe15bf0df2ea9ab.nq.gz
│   ├── 5439c62d4b8326eff6698675c00ce265c3b8085b.nq.gz
│   ├── 54868123490b5977db0fee6b2ba09afa2432874d.nq.gz
│   ├── 56165648baaaa4686b9bc1493b948e40a362b0c9.nq.gz
│   ├── 5ab8a7f1d0f3e903514886c12f92df562bd86cd9.nq.gz
│   ├── 603dc1898c3e5ea7a3fffa48370f34b528bb183a.nq.gz
│   ├── 65358ab7f87c4b592aade13746b12247caf82006.nq.gz
│   ├── 6b6314d94a03db5ea0aaa404e057155906f0d6ab.nq.gz
│   ├── 780b76c8ab12d72ff72fe02c5594418afed2d335.nq.gz
│   ├── 8237152ba9223059ff85cc40877a442c6de80c0e.nq.gz
│   ├── 8b9126bc93a68e1a286151b1cc9863b43cd1261e.nq.gz
│   ├── 8b9b34f7dc459480d707b58470fac795af9e7bf8.nq.gz
│   ├── 8e4c9a3cb11515d0d2156475f9e3e31617b82e3e.nq.gz
│   ├── 8f53502e76a0c308632c138d0901879d2ad03803.nq.gz
│   ├── 90e31e4a325c7a3876c162e48a37fba3f1fd1a43.nq.gz
│   ├── 9c116ae78d8e6818ad1d69c58631e8b399ec2850.nq.gz
│   ├── 9cc92c4d4e8fbefb45d44bcc3d5acd7ccffee455.nq.gz
│   ├── 9dce85d06f83264a6e502be0906d86bd976e1677.nq.gz
│   ├── a142a59688e4fec7a94b2e5a71251469eb887cb5.nq.gz
│   ├── a73b6b38c33b5d31c6a800cb414073533cb20839.nq.gz
│   ├── a8bfacf85ffe69876a1df584cc3c424f26a5dd8e.nq.gz
│   ├── aa930134b5de891e548ce582fcd8670951cd6035.nq.gz
│   ├── ac09f3d03faa218f7a61b382bbd6b233a59e7464.nq.gz
│   ├── aca443546d32470b0ee757fdae42e3030c5da9c8.nq.gz
│   ├── b2cf9ea870914b6fac180c04ca8c1c6ddf6c6f93.nq.gz
│   ├── b7775a14ce88bc22ada9fcdfd0540aad413277ee.nq.gz
│   ├── b7e7112344261b53803be59ed3f62afd70b04c34.nq.gz
│   ├── b95cd450688d49d8b9e837dc47de90ce2ff79b85.nq.gz
│   ├── ba78eb96091b0a9953836e8a1947fc4390adcd02.nq.gz
│   ├── c0d65cc787c9d019b40480f13aeb189c1882e9b9.nq.gz
│   ├── c12536096ad1137dd337b0334d40f7ccfad31a7b.nq.gz
│   ├── c2f2f8f3f75a2c30bf848a169611e39bfc2151d1.nq.gz
│   ├── c8c3aa1366676c1966df117cca94632884a7a7b3.nq.gz
│   ├── cd72a953498a06ff69e88fc112661cc81c3a257b.nq.gz
│   ├── d03f74b27522d1d234cec3b42371888470d2aa95.nq.gz
│   ├── d29ce1ede641346dee31b843cef8876e461b5475.nq.gz
│   ├── d589c2f22cd8e05d98e313efd25ac0603b693e1c.nq.gz
│   ├── d82c51b98eeb5e025d9812525bf68705df1bea6d.nq.gz
│   ├── de235170c96d19b01de5fd4eb0bef06d9572bcb5.nq.gz
│   ├── df6edf1bf4f3fbc840b4fc46a7b20d734d31efc4.nq.gz
│   ├── e356604c9b1366ea1c76e0c0615d25b53387113a.nq.gz
│   ├── e3add6599b0e5f7311b5a6028e7ca92506f060cf.nq.gz
│   ├── e55da6ad8022bc5c6e0b3309f2bcd5f6ce4a1e81.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e800f9e8957acde0c975a807c998c7b393cee562.nq.gz
│   ├── ef6c5781dcd619f9f825e183fa82c013a366952e.nq.gz
│   ├── ef9241442acf82ee539e6bbeab3b8c2672098416.nq.gz
│   ├── efce305fb0fe9d546f33728137fd9e84c78eae3f.nq.gz
│   ├── f075cfb63bbd36e17120a2704fbcac5caad09000.nq.gz
│   ├── f119e0f321718b8bbcff14e5220d5262a725a224.nq.gz
│   ├── f1ad43eb1debae1b2bf3049ff6e5cee59c5c1fa1.nq.gz
│   ├── f1c275286bf618b309844e2f0444f5a57427b2c3.nq.gz
│   ├── f2bc5eb6ccfb1d71a375a08bebf51ca2f966e47e.nq.gz
│   ├── f352eca2772696dc182ea3b317a76a591159fd82.nq.gz
│   ├── f54d07f2c41c6116066db9cb7e6f8bd98f2d4b95.nq.gz
│   ├── f7355e65cc2f850b2ca4513ebbece06f6c9675e8.nq.gz
│   ├── f7569f01c7fb3deb91cd7b9edf3e6f000c82688f.nq.gz
│   └── fb03f26e6be82581a39a45b00c82f59717bd983d.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 0e2455577192e10bc7a404ce9b55ca1fd3df928e.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 96 files
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

[astropy/astropy-healpix](https://github.com/astropy/astropy-healpix)

---
*Parsed on 2026-10-15 by [repolex](https://repolex.ai)*
