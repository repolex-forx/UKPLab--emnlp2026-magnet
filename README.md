# Repolex Knowledge Graph of UKPLab/emnlp2026-magnet

RDF knowledge graph data for [UKPLab/emnlp2026-magnet](https://github.com/UKPLab/emnlp2026-magnet), parsed by [repolex](https://repolex.ai).

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
rlex download UKPLab/emnlp2026-magnet
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 4030e4e538f475a5fa23aed7c8439f6ac888103e
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 4030e4e538f475a5fa23aed7c8439f6ac888103e
│           └── chunk-001.nq.gz
├── blob
│   ├── 07a59724627f8d717476cbd38cbbff9fa48c3a52.nq.gz
│   ├── 0a71ff84ca03c39c7fa881ccd3f8a8fcb6698267.nq.gz
│   ├── 144a273d98373829682ddcad2629639081c609f8.nq.gz
│   ├── 1b7553b773453b33d7bd730bf248db8cb55e9754.nq.gz
│   ├── 1d74895ac2b7c096b3167318fa9016cc39557bae.nq.gz
│   ├── 1ea264869c5619633f70c9fb1ec8fbed1e26facf.nq.gz
│   ├── 253b6e819b5625460d9a1641e5af5b523177acfd.nq.gz
│   ├── 2a024c94c6bbeba49e9a1a4ccaa487109439d6f5.nq.gz
│   ├── 343bb317d7b8a082e34aaa19b6a900a958adad6b.nq.gz
│   ├── 3524c33813c8a42d260ac310567bee203b0d7c1b.nq.gz
│   ├── 378dc466cb02008572044a626766143de56914e9.nq.gz
│   ├── 387c29e241517d310ca9cb4faf55842c08cf4b9b.nq.gz
│   ├── 393884e729f28c99bde22bdea7c68333e6902f6e.nq.gz
│   ├── 39c0696e7296c61725b9247e589b27802335c6b2.nq.gz
│   ├── 3c603fc602553ba10e51e061f8d4efe2577f4d94.nq.gz
│   ├── 4409eae6a77fe93253c3dea1bf581b7d9ee946c1.nq.gz
│   ├── 4494992e95a890d760734ccf84e8f96ba53b132e.nq.gz
│   ├── 44d3b58cb1865b4b68e6b230de42cbce582a8a1d.nq.gz
│   ├── 494b5e66c8502cd1ff44a7fdbcfd6cf6bc44822f.nq.gz
│   ├── 4c33b4bd174e212127a9b9b98f72519ee7bb0802.nq.gz
│   ├── 4d1f11b2fc795c45f2068db910c2905889efc56d.nq.gz
│   ├── 4fde78998696dc96867905e8d41a4acacac4ca12.nq.gz
│   ├── 535ea1fe0e1b743c2bd4b46e87d7175e02b0f0e2.nq.gz
│   ├── 5519a223372b1c259731442be2ba7ce708610480.nq.gz
│   ├── 58c049a5fe88f4930ae53d1e0b69466c3027b600.nq.gz
│   ├── 5df62094caf6b7fc26def07df495b5fc02337fb8.nq.gz
│   ├── 5e9c2607683712aa82234612757f6b180ca1569e.nq.gz
│   ├── 6098716eb3869164ad3b02d155acba923a327887.nq.gz
│   ├── 64f02beaa0c88697bcd0dbbcade63b605f998ef7.nq.gz
│   ├── 6810c11cc6ebc02796221377769fc8921ab58d0b.nq.gz
│   ├── 6a039596979e2997b7450a25589a173448c2e005.nq.gz
│   ├── 6d383a301596b3612ae1aad40955e06facc82016.nq.gz
│   ├── 6fade6b334b2b35369f4fb897fd6627fd2e52918.nq.gz
│   ├── 702f90c066baf792c52f2a4d1550a77dc90b3714.nq.gz
│   ├── 7136624ad597a55787172b5b0da9f31fcd6fc398.nq.gz
│   ├── 723656c807c174f33d99d3f8ce1d822ce0fd3e85.nq.gz
│   ├── 73f53cb02628c347f521ed6d95f42d0f58ffc769.nq.gz
│   ├── 79b408da928f1905787fbdafc50dbcb84e0647de.nq.gz
│   ├── 7a0d64068ea001d03464a7588cb162d0744e8023.nq.gz
│   ├── 7f405686022e2f712a0c06520c03c2b205004714.nq.gz
│   ├── 8502b0a96cba71e9fe0bd5ba19884d37429b34a4.nq.gz
│   ├── 85a72f76ed7c8192b49fe5e36a32ff496a99e844.nq.gz
│   ├── 86aebcd7e575a7ed98b347f5a1bb09060c4bf6fe.nq.gz
│   ├── 879bcb8eb6e91db21d38a742cd8230fb7a983fd0.nq.gz
│   ├── 8894aeb79779b9ff8487b98a1b6c1d67bf6af43b.nq.gz
│   ├── 8da5ea73518f1576925cb087c84fa5bd4d79a2e2.nq.gz
│   ├── 9163248e780577351668d202658597494a33cd89.nq.gz
│   ├── 91ef753d66957369cff42e2d7f2c5547fec3e1f5.nq.gz
│   ├── 9242ffd0b68e75cb3bc87ec520bc8320851d0381.nq.gz
│   ├── 967f0ef23f43e2147402d8efe3ff11dfec5ca615.nq.gz
│   ├── 9bcd1e1279ceb41aa9b0f7468c7a6b378fcf6666.nq.gz
│   ├── b70dbdbbafe43c84d474a97119126a7bf965736c.nq.gz
│   ├── b87b1e4ac2ed40cbfa4d84a426915fc127368b10.nq.gz
│   ├── bc6407725a8629066ebb963b9c2a0c16c7ae53e4.nq.gz
│   ├── c08a79032592be8f5e7318991b0242323389469d.nq.gz
│   ├── c430d55863e8b87d53150a58798ed0ad5f8b8af2.nq.gz
│   ├── c87e86373315db6a76bf2cc8095db3c1125af271.nq.gz
│   ├── cd7282285e9372de0df654f1fc421b85ba4bac15.nq.gz
│   ├── ceefc11dab0d768a2eb8f89e9d9f5cd3733c4136.nq.gz
│   ├── cfffa175f237248b15be71b30d6836afd46d7caa.nq.gz
│   ├── d08c4e475c93adbf95541772bfb418fe18e7ba07.nq.gz
│   ├── d3683c7568f26a1a3c18f5b072d01cdd1a745b78.nq.gz
│   ├── d61de48c40170e62052c48909ab87f5ba686d98e.nq.gz
│   ├── dbd861dad882e6d1670304f514867d305a72e3b5.nq.gz
│   ├── de82375c54521b58ced084471db23a512ddef1d5.nq.gz
│   ├── e11b27701b27f81027a620d962cd5829e925a5eb.nq.gz
│   ├── e1ab260382f37791c909180d85a089d941389987.nq.gz
│   ├── e64f78ca9418b37a4656c910317c6c3726eb9d91.nq.gz
│   ├── e70f155fd917d1979564bc9cbea5bf873e9019a1.nq.gz
│   ├── ea6d05ea8f9d193059c6b06318dbcc5229e7b33a.nq.gz
│   ├── ec6ebdf4b750eaceccdf4ae8f685c0da3d2217a0.nq.gz
│   ├── ede478ad0128ea132b3da8784dfa689ad47654b3.nq.gz
│   ├── edf303b2c3749c0e22a3af0986d3c07a294de670.nq.gz
│   ├── eef1d297cb5b136707dccf795edb99bac45046e0.nq.gz
│   ├── f0880190bec7f1d38f37e9d668d6b6003283f5cf.nq.gz
│   ├── f2293a2b7e68c91cf4d415f774b81c67f6ebcfe5.nq.gz
│   ├── f48dfefca8c9815b4d7da4070ff60580a09e1f20.nq.gz
│   ├── f720e83903e4d4597312751c032c387b4fcbc9ff.nq.gz
│   └── fa93938dc589747d5506f3147aab078437dcddd1.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 4030e4e538f475a5fa23aed7c8439f6ac888103e.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 87 files
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

[UKPLab/emnlp2026-magnet](https://github.com/UKPLab/emnlp2026-magnet)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
