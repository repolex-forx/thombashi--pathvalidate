# Repolex Knowledge Graph of thombashi/pathvalidate

RDF knowledge graph data for [thombashi/pathvalidate](https://github.com/thombashi/pathvalidate), parsed by [repolex](https://repolex.ai).

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
rlex download thombashi/pathvalidate
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 1ca0a50fce51d5b5bd633457a72abf74dbe3112d
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 1ca0a50fce51d5b5bd633457a72abf74dbe3112d
│           └── chunk-001.nq.gz
├── blob
│   ├── 004e05f5caa8df8e80d8ac4fb014360c209eb691.nq.gz
│   ├── 0231b82506467278097665f5661659acf305483c.nq.gz
│   ├── 06fb2c6171edf291fb9269acebf94f5054939031.nq.gz
│   ├── 0ba470784caf1261a007650aa354095963f6cb99.nq.gz
│   ├── 0e44bbfd2cea5f1424fe47f67f7f456b216ad4db.nq.gz
│   ├── 0eac83838e60cd3983eeb78fa02dfccb179a3933.nq.gz
│   ├── 0f7637461f062ba3460d6d7c8af53ea27504a5ee.nq.gz
│   ├── 134224a52a3ed8e9a8422c230f58e095a0104bd1.nq.gz
│   ├── 146031eedb5348bc25daa6a4681a079f5484fb2c.nq.gz
│   ├── 1716c6954cd052c2bda07fa3165873e991602dff.nq.gz
│   ├── 1d0abe121e8830343e3b662bd15f90c1177a6342.nq.gz
│   ├── 1fc76c8343c47ccd05872f4c1678a56bd6a4dc36.nq.gz
│   ├── 23b559a4c141f860d3923fe9222668906b2d4ef0.nq.gz
│   ├── 2584e633ff64a8c5ab3d7d8c725278ecfb4cab74.nq.gz
│   ├── 285dc2b832e52752911dd49eb90260c0f05d6a06.nq.gz
│   ├── 286401b9f5773e211dabca700a0bc5bac36bbb6f.nq.gz
│   ├── 29cf608552ac4234143d5fa35992719a2ceded39.nq.gz
│   ├── 3331a72900c29d167a71c916c9269cb59affc15b.nq.gz
│   ├── 342cb02a5415f08f9a96c368d578a441da8bbcbd.nq.gz
│   ├── 36b650e49a815ecf94e8357b79c8ad2af4a3c1ee.nq.gz
│   ├── 3e3c2f9d5e2bc9c160cda612c58f5fb61df672d0.nq.gz
│   ├── 3f349c31e3abfcec0d5b434e24ff6044f064af1c.nq.gz
│   ├── 440c81ebbade0d1daa2f0bd72dd7dac0b10ea823.nq.gz
│   ├── 4939913fe023adb365e911b40c4c534afbbb3471.nq.gz
│   ├── 4c46805f8d1f7cd0c547eae7d5e174c67b31a8a2.nq.gz
│   ├── 4e4f84b6c29037306cdb56e03e6c0172ed95719c.nq.gz
│   ├── 4e8518ba9d9eead2401fcb1c8ecb3ab1d283bc8c.nq.gz
│   ├── 4e8b448f34b1f372ffb95ce9884f5736095294d3.nq.gz
│   ├── 51c69e66dfdd913e3a21a2fd2c8c5bdab87ac888.nq.gz
│   ├── 54160763ef9300425ca5792c68c7161164006651.nq.gz
│   ├── 546605c8fde1079ee594fb933d0a58d415467d6e.nq.gz
│   ├── 570008306949890ecc20f4ae66fff0faa469d6a2.nq.gz
│   ├── 578e75ba83b1821758137b28473827d207de979b.nq.gz
│   ├── 59b6ab9d1492333bf3da3d90f12494d62621c784.nq.gz
│   ├── 5c2067af0ee422c548e38ecc6ed1a838282661ec.nq.gz
│   ├── 5d9c87b6bb071b84a75cbc5cdf6bd7a9c7b43608.nq.gz
│   ├── 612a2990a3dd44daae7c2ada9b1bd046ca29628a.nq.gz
│   ├── 65c7d60615b0aa966609b6cc4a16161fafa5e584.nq.gz
│   ├── 68af982b074149d87cf9d65e30245e4d68ffccbb.nq.gz
│   ├── 697df75cd2ed20b5d626b909d7f00a04dc5b33dd.nq.gz
│   ├── 6b11defa7ecb0af03bb4cfbb91922c04eaba9af7.nq.gz
│   ├── 6e512297e88cbc04eaa2d0eb42b43c8ba63d3810.nq.gz
│   ├── 74c28bfb0e76c3ccb371ab4f3546271d601abbff.nq.gz
│   ├── 77e72133174d144f159d7ee85c8231d2c72f3125.nq.gz
│   ├── 7e9cc92f914ad2b589ac5ca847ad8d2e143bd5f7.nq.gz
│   ├── 7f3471b094a832f42bb0018aab5442a3a7548732.nq.gz
│   ├── 8392530f7ddd50764ff8ea14bab9dc4c0eeba0c9.nq.gz
│   ├── 8aac696ce4199235bd095e1b9741fb49a0c89621.nq.gz
│   ├── 8b137891791fe96927ad78e64b0aad7bded08bdc.nq.gz
│   ├── 8c9dd41821df3657e5f09f1210ac1d60f9fe8ded.nq.gz
│   ├── 8e20483b57cc1f35aa58fabbb66736ed21942bde.nq.gz
│   ├── 917a8fa1f0ba7d5c577fb1aa0ac3493ca65da688.nq.gz
│   ├── 918f2df0ecc0a3b1fe38cf5d38842bdcd397635a.nq.gz
│   ├── 926f9fb728f06af3ff8cd0aa853dcda590b9a93c.nq.gz
│   ├── 94284af28327c6e558a2da2f1dc1e4261c7c1018.nq.gz
│   ├── 9527eb3d6c9395a6255cc59c02e1b50bbf6fb1e9.nq.gz
│   ├── 99f029fc16edbb1b1e92baa879aae7689aa102f3.nq.gz
│   ├── 9de84ebe2280a1f13f5eed5c929c5b2a182dfa61.nq.gz
│   ├── 9ffe9be1c365b0e0b6de946f0e864a4cd391f1e3.nq.gz
│   ├── a48dc8fafa5f1ed3b4b47376a1910e616f7cc853.nq.gz
│   ├── a4c7796facdd54a093506d320b9c32b41a2ddfbc.nq.gz
│   ├── a73d5b736683148ab5a6718f02022305c0852d72.nq.gz
│   ├── b3e7ab0956870e669f17a39c67b91c82e0092a53.nq.gz
│   ├── b46bb99719f2ad4146c2cdda1697e6e076c14e1e.nq.gz
│   ├── b838d796e9dd8fcc7e2a15732e30d04bbfb1058c.nq.gz
│   ├── b9bfa9a5d796204700a45b8fbb322b2238570882.nq.gz
│   ├── baeafe2751f007276ed14fa273f4fe206673d744.nq.gz
│   ├── bc3e452aa5c4d52021988b1139bd0abf339c0df3.nq.gz
│   ├── bdcb4456eb14f425bc37ee58ba7e67412260dfe4.nq.gz
│   ├── c0497238df94eece9e49b90419daf2dd993ba443.nq.gz
│   ├── c393d2f4c741a8b3ae6cc33b03f60149a38a93c7.nq.gz
│   ├── c5adc761025cb839d9d4b16ec16c21963837328b.nq.gz
│   ├── c74e842ee63ec9b744ffc9c9b6bc54906fc86a9f.nq.gz
│   ├── c7fe814ff5b1fb0b5dcfc4a8dd36121436b68fe1.nq.gz
│   ├── c946842489cb1998c4e9a2dbcb95ec9286e0a528.nq.gz
│   ├── d1022a2325c2fe80ac8d01e1234746e5ae53f799.nq.gz
│   ├── d62e4220d3fea354089799ecb90e9df98651a213.nq.gz
│   ├── d6eba833232384a8bb83ccefc52e4dd501a59fb9.nq.gz
│   ├── d8d096cc6ed9b318c46e7e0f90137939fe44d753.nq.gz
│   ├── dd69dbf5a754fe0d6f172cf07e208ebeda33723b.nq.gz
│   ├── de91567dd960e64c4337310bced998f10f884b86.nq.gz
│   ├── df49ed437b13c2aff27ea72978bea4ccaee0c729.nq.gz
│   ├── e00380545ac181252e078c937559309535d8848b.nq.gz
│   ├── e05c1a5026c339b44f346b51ba0c4295d7306131.nq.gz
│   ├── e19c23eac5c784a08f1046cd1953706fc2706fc6.nq.gz
│   ├── e5e872ac59e47b37db1c5a3014d064820ce2a77b.nq.gz
│   ├── e693c3ffe095ffb80fa91d77ce7a6369a5dc7b6e.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e81431d135399bd24be172fa65dffeb294c896f8.nq.gz
│   ├── f1b3d6243d800c28469efad4bb452e40c76e6703.nq.gz
│   ├── f2651eddb8d97c2a2b78dee5103acca88d616d33.nq.gz
│   ├── f535b41ebf587ccd661f2635448632c6f5492f04.nq.gz
│   ├── f6299474468399f6613126ff0bf515f122455d01.nq.gz
│   └── f6e32a6ccba9ee9e711229bf8af8026a84d4651c.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 1ca0a50fce51d5b5bd633457a72abf74dbe3112d.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 102 files
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

[thombashi/pathvalidate](https://github.com/thombashi/pathvalidate)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
