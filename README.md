# Repolex Knowledge Graph of stub42/pytz

RDF knowledge graph data for [stub42/pytz](https://github.com/stub42/pytz), parsed by [repolex](https://repolex.ai).

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
rlex download stub42/pytz
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── e3c6fe223abf0ad1c1c4e40a9bd319a87bb3b829
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── e3c6fe223abf0ad1c1c4e40a9bd319a87bb3b829
│           └── chunk-001.nq.gz
├── blob
│   ├── 02999200662eeb13293d71d542c27355906d25fe.nq.gz
│   ├── 036b07ed387cca2458d5474520e58d11107272de.nq.gz
│   ├── 06b758eff2344d6c9272988c3c1e0c3f5f9bc110.nq.gz
│   ├── 0b5b000f8eddb78d779471f38a46b3f1260281c6.nq.gz
│   ├── 0b69d8ea4a4dce46e40af15cfe0fe082468e4a51.nq.gz
│   ├── 10724500ca7e73d92d45d11ea1750715edbcd490.nq.gz
│   ├── 11a0dfd79bea6e708b6a2a61073e3945407de7a4.nq.gz
│   ├── 12d76d3784496e55fc6a76138d23effd6631d95e.nq.gz
│   ├── 15937e1e901815df7b8f355a12fdd68380305725.nq.gz
│   ├── 19975434b7b79e14aa8de8f7f3cab81ae712c0a9.nq.gz
│   ├── 1aed9b5e30601f3fd6eb59226355ec646cbd1298.nq.gz
│   ├── 213ae67e962a2633c7e843753e885abcf9a5be31.nq.gz
│   ├── 2731f2366b51ecd2f49a2995dafbf2d9d07d777c.nq.gz
│   ├── 294eee0095a06f1d2a5c4a7646bd3ed9aa14ebd1.nq.gz
│   ├── 2965736a0b0ea9e31f9d7118924ce29fdff75d47.nq.gz
│   ├── 2971d038b9e615111c5ce077acd005315c222d07.nq.gz
│   ├── 2a10dcb3a1afab5b02d884399a0bd3b9249ce306.nq.gz
│   ├── 366bf3024808b9ee1e73c045c2e153c3a40c71c2.nq.gz
│   ├── 39344fc1f8c77d5ec43539d0c8e655f4b5d7d6f6.nq.gz
│   ├── 40c8e5b6dc2b7549c2984d8ccd627e123f6c4e91.nq.gz
│   ├── 433a672130ee1039bb2db23db55a56f4d7bff974.nq.gz
│   ├── 45ac6460391c66779903fef07959358b6c04dfe7.nq.gz
│   ├── 4ae35234b9722a8b673823e67106479eae6d31a6.nq.gz
│   ├── 4b20bde9ff9240ce8cc578e480f4d9aa8555bab4.nq.gz
│   ├── 4e483678686eb751822fc101aea2a0b4254bac70.nq.gz
│   ├── 5a140b46fbf4ea86b6d227d73e7445325f042b61.nq.gz
│   ├── 5c56a407a1f16805c42d996eba3c517fa4d782cc.nq.gz
│   ├── 5d51f4a9b3b97677c8163da59d1dfc6cc47febb8.nq.gz
│   ├── 5da55654b01c61954d2f25e0ac03d3eb71791304.nq.gz
│   ├── 5f1c11289f6a54cb07ebdbf31d02e8e81b18b07f.nq.gz
│   ├── 5fa60556be13793223012b2ed63c65f2fec667f0.nq.gz
│   ├── 699de85cbffa5fe9408195b6dc35ad95a1c89384.nq.gz
│   ├── 6abb58951833f39f24f5f4b43cf87134fa951fc3.nq.gz
│   ├── 707e92785535eefafb0b6a0ceb2e45f19fea43ff.nq.gz
│   ├── 725ae92523bd058b15f8f3b47b8bfae55d02656d.nq.gz
│   ├── 7455c051972a46cf09e6d7e7d29792cba49792ea.nq.gz
│   ├── 79c4e9d66b4f3f539f62989d9a070160dc5d03a5.nq.gz
│   ├── 7a05dc32ebe69dd53624aaf425ecd19a7f2c89a9.nq.gz
│   ├── 7d23b14ace72714f1519d76e923fcd21dc015ce5.nq.gz
│   ├── 80688dd7ed35c1555ab28b3b63dc117212ed9ffb.nq.gz
│   ├── 8139ad57ecd2fd758d270e35489ee1b41eb7dc1a.nq.gz
│   ├── 82a5feab8399bfd74adbc4aded74a813465d95ca.nq.gz
│   ├── 85a8c670e0da33bf2f94b63b7763b3b7655aeaf5.nq.gz
│   ├── 88d55bfb86f55d97ee26e468f1e96125e75be28f.nq.gz
│   ├── 8a53330e1fe9769378db34b529bf3cb560282e0d.nq.gz
│   ├── 8ba4399c622d3a1a3175865c39c3469e82539795.nq.gz
│   ├── 90e6a956c83d85f322b4626bec64349c9f8fed98.nq.gz
│   ├── 9996039e124df9ad10413083fa9b843cee1de2dd.nq.gz
│   ├── 9a37d89009b9b4725e82f3af3f2e1ed8400f663c.nq.gz
│   ├── 9c76c114af039c9a12302d9abb11c89b06b9d725.nq.gz
│   ├── a7d488499fdd23d4fe13859fbbc5188e240d63ee.nq.gz
│   ├── a9d50d9344fbc1ac55b2278854059c89404eccb0.nq.gz
│   ├── b481babd4328cc8222ae472055db97aaf70f8a95.nq.gz
│   ├── b83f702d5e0d588b9e990f4ac9e97cee0e01c696.nq.gz
│   ├── ba3a13405d7558bdc601b2c988fddd0b10a0ea7b.nq.gz
│   ├── bd3a27874326ae35ed2151dfa1e5b49c6ec2b0ea.nq.gz
│   ├── bdf8c18ebc72e8565f3e9cf6812c2f3a4c564075.nq.gz
│   ├── c29d1f53db337aa9b5fffe3911bf93136b7cec61.nq.gz
│   ├── c627f8bd4206bd8311f72f786ae780738f3fb6a5.nq.gz
│   ├── c881bffc4e28997569adc8bb541f8cfce2b74a69.nq.gz
│   ├── c98dc6ae786d3fff2094f8f794add590944a7eac.nq.gz
│   ├── cd0dcac2e1bf86eb26d1905a051131e8b71a3bd3.nq.gz
│   ├── d266b3971cbab6c813f07db55f13e2352c6fff91.nq.gz
│   ├── d3b4b94a0486f5d43a45db242d445d256bb935a6.nq.gz
│   ├── d78f04133c36b9075b99b688e31b4634d233397c.nq.gz
│   ├── dbce8bbd5d2dd843b35af9cb4e150b03d1c8d1d8.nq.gz
│   ├── df4a35138808dc3d771e4a1ad7260a7981effe77.nq.gz
│   ├── edf963460b8763d188f9a1593f0122125f84a630.nq.gz
│   ├── eecb529c7cd79741dfc6e8133f48dfd35baf91c1.nq.gz
│   ├── f1e8ac298069c22894ce716c3723027f2c502862.nq.gz
│   ├── f22e69f4453595abb5bee9905a4c5cb3ba13a565.nq.gz
│   ├── f2861c94ff53995a1f58a37783d125af8fe07bba.nq.gz
│   ├── f46ac479cbd4c03611957d4f4bce8e459a6f5f31.nq.gz
│   ├── f765ca0af0b24e66dc3b7d51b9bf97e71b2b67aa.nq.gz
│   ├── f76baff18c96047fee115709ec2b8681b0988313.nq.gz
│   ├── f9ca75d063d6ae88f29314584f5ab6699c01fb5e.nq.gz
│   ├── fda34e2813cb5e245bb4e11232b28915cba6639a.nq.gz
│   └── ff78f03c5705e9eda5da939e49df643006afd110.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── e3c6fe223abf0ad1c1c4e40a9bd319a87bb3b829.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 86 files
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

[stub42/pytz](https://github.com/stub42/pytz)

---
*Parsed on 2026-11-06 by [repolex](https://repolex.ai)*
