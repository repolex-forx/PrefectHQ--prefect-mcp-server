# Repolex Knowledge Graph of PrefectHQ/prefect-mcp-server

RDF knowledge graph data for [PrefectHQ/prefect-mcp-server](https://github.com/PrefectHQ/prefect-mcp-server), parsed by [repolex](https://repolex.ai).

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
rlex download PrefectHQ/prefect-mcp-server
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 48efd289bdb2b94a78e35b1331fbefc4fa3f6411
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 48efd289bdb2b94a78e35b1331fbefc4fa3f6411
│           └── chunk-001.nq.gz
├── blob
│   ├── 00a6d45f8dcb6292d59b9a0079a5c0e97115149b.nq.gz
│   ├── 0392003c67a3b42242ebdee8576b1e7cd0c29f20.nq.gz
│   ├── 03c5c2e1a513f87ebfa6ba7c08bb12b0da1b39c5.nq.gz
│   ├── 0df696df015348f577a9870e877b264d4894c272.nq.gz
│   ├── 1389328ccd8ded7e3635f6879655fbcdc346a4fb.nq.gz
│   ├── 151e0f0252415b1c6684b4556791cf60a2c8b737.nq.gz
│   ├── 1a5f7d6726ead7a1aa1952687e6a152536db9ef3.nq.gz
│   ├── 1b997846d81f08763d55de33e8901f055e6eadf9.nq.gz
│   ├── 20e3a345d50106850d0af84c7df6f992b4db3d56.nq.gz
│   ├── 2155e650250196de4ec5396d1b4d786b527c5e76.nq.gz
│   ├── 24defddcc4e458cf1afa8953a244a71f2a104493.nq.gz
│   ├── 2c2b8070412c76610aa2e5ac8dc4ad42926a8f04.nq.gz
│   ├── 2e2eac65fb62c9d26eafcb8d1ca6d87ba5009660.nq.gz
│   ├── 313a3d37722044c65b581a09144e0e4be606d983.nq.gz
│   ├── 3239834c6062f3097a9477de9a3a127ead35bd30.nq.gz
│   ├── 35cf93af6bae98cf144ce56f6f80bdd4721981cd.nq.gz
│   ├── 390f3d1818ffccbdcf7456badf4b54b9560104d3.nq.gz
│   ├── 3d45b09638a92688c4f90350d9a5cd96608caf27.nq.gz
│   ├── 3fa558148d6e6a34c627c9b7c50d5f5fd8340acb.nq.gz
│   ├── 3fcb28775b0d1d07c89386d032838dbf08f1a7bf.nq.gz
│   ├── 400bd183f0d3df713c8c4e3ed8b6d3903ef58d0e.nq.gz
│   ├── 42074d733ac127c19df5b6e0c4ea25a9a02ad3c2.nq.gz
│   ├── 438dad50c2d213428a967ded20d30939cb85da1e.nq.gz
│   ├── 466267783b1d1412d58c1176a5b8f1f121a967fb.nq.gz
│   ├── 46f6e590b092e51920aa6c13600fcfc773e5f229.nq.gz
│   ├── 4b16d3699f20321f8b4e981541be1a4eb0b01f22.nq.gz
│   ├── 4b88fc98f424b9bc5ff82b0bcd776c725037f1fe.nq.gz
│   ├── 4ceed40f062183da04abcaac2186fe70bf8cf590.nq.gz
│   ├── 53576e7cf9c0a78e03851444bed2445a39458d50.nq.gz
│   ├── 552cc8f4bd05585d3a9dfbcea07100dfe43d148e.nq.gz
│   ├── 57674c675d86b8fec4a22057e068530ff14bb392.nq.gz
│   ├── 57d85af6ef18c827a968341f88faceb882dd482b.nq.gz
│   ├── 59b8c5ddf0b34d1add0dd822046ff62d45139a65.nq.gz
│   ├── 5ea53ff0b1b549e92b66228c364740566351d325.nq.gz
│   ├── 5fe65ea0d8ac41bca2c26db85c96231ebda35b31.nq.gz
│   ├── 620b12adaee06a4ccb30bd92d790b1632c8913d2.nq.gz
│   ├── 63fdc191388c649bcfba8226a9f80c159be15dfa.nq.gz
│   ├── 6522baf33f6a9069d75cedf1acd7a06197a40682.nq.gz
│   ├── 6a363df7b2fd593303ffdf8773781fd96e78cf6c.nq.gz
│   ├── 6a5f37e4e75552aaf5d00064fe93aceb28c1830c.nq.gz
│   ├── 6c66bf46e1bef586c8e79f3bcc1cf7d6e9d653f3.nq.gz
│   ├── 6fcd6026751220eedc2c72565fcc992f7ddbdeaf.nq.gz
│   ├── 734149b1a70d8cc94735ee9b7ae34ffd101fb75c.nq.gz
│   ├── 7774879c66f240dcb98066c690d637f957d1a485.nq.gz
│   ├── 77e78c017bae60168869945eecc2b1b0b0cdc86f.nq.gz
│   ├── 7ba6214ece6fe4784ee13f0f728dfafe773fcf8c.nq.gz
│   ├── 7fdfc41fb23bbf91e088ec3a86baada43d130423.nq.gz
│   ├── 825e1bc659318671ebc0710c672b1af74b097840.nq.gz
│   ├── 8570408261af9b5dd4c3b1ca41b40bcdb369c466.nq.gz
│   ├── 8cad063eb694893354855b554496388bcd93b073.nq.gz
│   ├── 8caf4fb5d5e6ba2b46d702ef049918550c0cefe1.nq.gz
│   ├── 8d2185132c20cb0ab6e381bad982d16fe0c841c1.nq.gz
│   ├── 8e5289816111df919bab03e0bf1c6309044d569f.nq.gz
│   ├── 8fb57619623412a957edafbaac2a066d12d28074.nq.gz
│   ├── 90d23fdcb523ef421711593f5fb66c54927869d1.nq.gz
│   ├── 91cda6457c306d890b87e56ac3d098e7d27b51cf.nq.gz
│   ├── 92386e20bc73e781caa015b849dda88f0abe5176.nq.gz
│   ├── 927ba24c11393e559220a6f3b216d3d7cf3a94a6.nq.gz
│   ├── 9458f1d47cabfc263d364b2990f0a32573964517.nq.gz
│   ├── 94cbe76bdf2e536e677baa26bed7ae99c5476670.nq.gz
│   ├── 95deb2569b4c3fab40dda9c17bae7658b5833d26.nq.gz
│   ├── 9865a8e2d484a673ad2c1395259eb39636684b33.nq.gz
│   ├── 9891c53e4712c08c78b04132c44715aa747cfb1c.nq.gz
│   ├── 9b5a038cf494c468c25bdc2d30c7804330d66e95.nq.gz
│   ├── 9b6368c557e23e23dd22dcd137e8c9fa7116dd25.nq.gz
│   ├── 9d33d8c51ac6562eb7d18ba7726614ba4e185b12.nq.gz
│   ├── a129d40bc2ffdb3b8483eb24a65f8de460faf212.nq.gz
│   ├── a3e461e019b5d50d193e1e6cfec4af0542c02a5e.nq.gz
│   ├── a7b7ca2128dd7d0554b6040140559f30ee1fa0d4.nq.gz
│   ├── a7ea31569f6724d57c6ca0b11314ce64dc907e35.nq.gz
│   ├── a8b97fbb63d5e0591293f7125a64a0755a3042bc.nq.gz
│   ├── aa12eb846dba67267de5970bacd223353e0468b6.nq.gz
│   ├── ac1ca8cea5dd4326adea68fe4fb550880b3247b6.nq.gz
│   ├── ad25fbb3c2f6249148fb604e6ce4192b9f7dfaae.nq.gz
│   ├── ad3a41506479fbc919add300663bbbed05ae80cb.nq.gz
│   ├── b1715299f59bbb7aedace834668ff17df045fa59.nq.gz
│   ├── b1f071e2b8ad69470be00d0b4d54e521cb69ec4c.nq.gz
│   ├── ba075c6bb482006023d9014c198d2f65a04c72f1.nq.gz
│   ├── bccc58a1b44fbfad42bd584d7e08b0f1e1216ca4.nq.gz
│   ├── bcd60bee4966611c8751d45cf180cf10b1e87ad0.nq.gz
│   ├── bd5db89528dcbb023e9d46184fb94ccea8d23f6a.nq.gz
│   ├── c03436784c64d4bfd4f0a7a73ffc1ea520ef4d0b.nq.gz
│   ├── c19feb5898cedb2fd119ec0390afaa911fea942c.nq.gz
│   ├── c521f7ff979775f9b5efab72e44bf4cfe4c5e818.nq.gz
│   ├── c579fe2d28e93dfffae83a1aa3b1d2ffaad17263.nq.gz
│   ├── c58f32b08f29fc9a272651d5ef99e73bdd1b4d96.nq.gz
│   ├── c5c6f276793dc28a3be63321ae515a874c414432.nq.gz
│   ├── ce3b76db21b044eb5930df11c93a0666b7172df0.nq.gz
│   ├── d1c3a71f3ffe5273b2f22420d599e631ec1ba1a6.nq.gz
│   ├── d3622c0eb335452fc8fa834528d1d43ed7600d9a.nq.gz
│   ├── d4c4fa5a1f83a8f64d4e49e2300aa6448808ec67.nq.gz
│   ├── d5bb5a5419637df007ce3d78a578636be8a61e59.nq.gz
│   ├── d5e079591e36e42db079db2fcb8d82fdeeebd842.nq.gz
│   ├── d74b3e0d1ed6991aa91a2d4892d55aa5b59f8b23.nq.gz
│   ├── d875a44fe1cd9b0216bba0a2a7742dca31e8229f.nq.gz
│   ├── d91252b70ee2f7442dbc321a3a8aca7600646f6c.nq.gz
│   ├── de2fbd1da37da95b984d2531258d578ea1e84eb8.nq.gz
│   ├── dfd5f88970aac3ecb729352beb28362a7a32306a.nq.gz
│   ├── e0b6827956676d0e11899796e79140052ad87db7.nq.gz
│   ├── e11a988070071957053f1a72701db107b17a8fbd.nq.gz
│   ├── e4fba2183587225f216eeada4c78dfab6b2e65f5.nq.gz
│   ├── e54f3151b22259947a63a61385bb9c24458965c5.nq.gz
│   ├── e55f131e6a887b0e098c40993c73acd812fe1db2.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7f0df935a39254c480c0a8d7605b749b83b5de2.nq.gz
│   ├── e9a063ee22f52dd5e32ee720cd75d0dce1e21b0c.nq.gz
│   ├── eab249980182bf90cf48d31cfe003c906fee6d26.nq.gz
│   ├── eedfddedc0ce69170507f7e4c4fd1d6ae2a6027d.nq.gz
│   ├── f10d09aea0e40b848fe82aa6f455ac73d958582b.nq.gz
│   ├── f1540eb372126e2c44bab84433d160ccb1f71bbb.nq.gz
│   ├── f5eb611a16d67e9658c2b099a373ba8e1edd6477.nq.gz
│   ├── f969f0398b962d1ed16deb10b4e82e675a419673.nq.gz
│   ├── faed132a370ce96e3b99fa5ce24ef567b1e75cb6.nq.gz
│   └── fbb069212247cee9a72bf5b61643c3f72ff933e6.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 48efd289bdb2b94a78e35b1331fbefc4fa3f6411.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 122 files
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

[PrefectHQ/prefect-mcp-server](https://github.com/PrefectHQ/prefect-mcp-server)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
