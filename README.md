# Repolex Knowledge Graph of scikit-hep/cabinetry

RDF knowledge graph data for [scikit-hep/cabinetry](https://github.com/scikit-hep/cabinetry), parsed by [repolex](https://repolex.ai).

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
rlex download scikit-hep/cabinetry
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 0252deed24451e835570619d67e60a674034d9d5
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 0252deed24451e835570619d67e60a674034d9d5
│           └── chunk-001.nq.gz
├── blob
│   ├── 0077b8d7014792c4d6805dcc47d2ceb4c273e346.nq.gz
│   ├── 0318c5d5ec885a60103d4faf23206ec15a76ce2a.nq.gz
│   ├── 0b49908db1acf70c0aa7008bd5a4fa9162989559.nq.gz
│   ├── 101308f810eb46fa0a23a6dd095bcf91c8526a08.nq.gz
│   ├── 1326a1ccde59a489219eb91321a91a436d8454ca.nq.gz
│   ├── 158480fdec52116ad17468919d754bafc6d43be5.nq.gz
│   ├── 15873f50dfbea4efd73a58e552410502b5e46836.nq.gz
│   ├── 15e013477a27224fdceea964c1892bfa756fc377.nq.gz
│   ├── 1711a4ed81ce91675c2e739e0eef43c3d4ee3ee2.nq.gz
│   ├── 1856c3ed0aa305c6b8961d278a653cb54930dffe.nq.gz
│   ├── 190aedf9d0482877dcbbb0240dbcf1fe8d3585a9.nq.gz
│   ├── 1bbc8bb3b16a1a7eaf1f2e0aa8eff344b51e8a92.nq.gz
│   ├── 1bd877149d66e775ee45d53f9247f18c3e3c897c.nq.gz
│   ├── 1d710420bbc1f026a25b97c4651a1f443e209c2e.nq.gz
│   ├── 21322658fa234c9bac49dea43115e125e3ca7d21.nq.gz
│   ├── 26a723e9fc7016ad05a9263b2f8f28b7ed962dcf.nq.gz
│   ├── 2c703590830563e1592dffcfccea8635d767a11a.nq.gz
│   ├── 2fd119e45af8217588171660fec8009115d9c5fe.nq.gz
│   ├── 305712cb623a117cf7d3c630f687152df143ab27.nq.gz
│   ├── 34acd7b38a08c84ca9010bb89245f2d1d049555f.nq.gz
│   ├── 34cfa53da08cf0a54e6bb59c633c4e3a3fdb34af.nq.gz
│   ├── 368e2d4cdbf8d143ce9c7c5cb91951b6833ab923.nq.gz
│   ├── 36bcdaf9b5124ac49c268db69eba77db676cf022.nq.gz
│   ├── 38af5de261aa375cdfb0cfa8bd54f7dd4a886f2b.nq.gz
│   ├── 3d332e911d6e74648935dcd26f884d9e82f69c1b.nq.gz
│   ├── 3daa18accbbaa8e3b94445d6d0ad69d25348a67a.nq.gz
│   ├── 3eaa4dd2ac58884c265be01058b144c72efbd0f7.nq.gz
│   ├── 4053049fdbd404b660324b5cad7faffa4c93d31a.nq.gz
│   ├── 42b3a69feeb013f45f14da02c5114fe97d3884a6.nq.gz
│   ├── 43a40e47ee1e2e5775d1752bd1f09a61e5382071.nq.gz
│   ├── 4490f04393ad96b43ed54a8edacd9b84896a3902.nq.gz
│   ├── 4851e36efe94efdb8b476778a21cfe93a594d05e.nq.gz
│   ├── 4f6466070ec4f951abbfeba04444c7ac86e125ec.nq.gz
│   ├── 55842b5ddf72758aae8e91294479d35c44642974.nq.gz
│   ├── 57ee12b505f8330944c7a0c73ad4e9cfc8fbd076.nq.gz
│   ├── 606cd775d2e2af3f8eadcfdbacf88a7afde4f715.nq.gz
│   ├── 618af37a6b527c58ee8961edcebc0bca258f8693.nq.gz
│   ├── 61e70c29ab1381c0536b089e101ce4064df5f29b.nq.gz
│   ├── 676bdd8b1a887021b7a37ebf6cf38e9dbc613ba2.nq.gz
│   ├── 681daca3aef4845c212294dda2374ce1a0b03e83.nq.gz
│   ├── 6ae1973ddbf65b380218e9830e3fc0802715d97e.nq.gz
│   ├── 6ca8faaebb7b6187591ccb16c1cb675f486fc735.nq.gz
│   ├── 761495d089581c25b79a65db9b5cf2b34163a4c2.nq.gz
│   ├── 77bee6639a46e522035c1ca1e4341a81ff1e3ae5.nq.gz
│   ├── 7d660f83702eca2d50cebbd2ee169da998c8d7c7.nq.gz
│   ├── 7e6291f3b9bea34542bd0bf4af2fe238d981952a.nq.gz
│   ├── 80ac55437f58c27860c45c0fe3bad9af98350e96.nq.gz
│   ├── 82e16eaefb93d827a4ec8709dd84828f742c3e07.nq.gz
│   ├── 8f4408a2ad6dd1e85f116d263c0ef61f1bc3a3e2.nq.gz
│   ├── 92500b23f31fb8b085d46ebf248334ded7f2a9cc.nq.gz
│   ├── 93f4516376123e57c64a2c820e1ab931599f6ed5.nq.gz
│   ├── 99a67607be156c0977cc54ce8367e5070b111d09.nq.gz
│   ├── 9a5aec9ba31daed8877bebab819e3dc172cab7e6.nq.gz
│   ├── 9b0cd45a8da802c8ca0a7f7a01c8b81f633e2e7e.nq.gz
│   ├── 9d2f1582a7a5fa81d7b5fa95513f58675ac7b710.nq.gz
│   ├── 9ff175f10ff4b3baa74bae1deb9236b2d6a7589a.nq.gz
│   ├── a3ac217bad4189d7bf921e5f15de243564881ea9.nq.gz
│   ├── a5bf8eaaf15cae9c1aa5f2c91e5083a55ff29668.nq.gz
│   ├── a8445f4cad54db37a3205debe55af17a1d27b8b2.nq.gz
│   ├── a9f05ff4717d84f83ce90d89aad03f296188665f.nq.gz
│   ├── aafdcddde012a553111c6af6b4f9840f4f573fdf.nq.gz
│   ├── ad9f4c4e49b0819aaa2cae1b861d92f533888681.nq.gz
│   ├── b18209536c4ed52491d378adca61d2335fb569ae.nq.gz
│   ├── b43b6f976b0c19bc3abebfd59303a535f907e4cd.nq.gz
│   ├── b52fd31e0c0962ebaeb13044b02831458f532021.nq.gz
│   ├── b715b127a3d07beb674de1191e467928503602e1.nq.gz
│   ├── bb3943331d8ee8a58986546eeff72dc12d2465fe.nq.gz
│   ├── bb93b2c9e85d601bafea604098ff15aa426a88d2.nq.gz
│   ├── bbbf2cac101a5503b32ddeda3dc91594efdf266d.nq.gz
│   ├── bcabd753c301adbea4b4a67a6eca934deffccf34.nq.gz
│   ├── bee36677504d7cf0bdbbbb196a4518cf96295348.nq.gz
│   ├── c0259011bb2e87ccf03b490043706661c9c58850.nq.gz
│   ├── ca411a4f919cfe817acfdc15af9e01f836499723.nq.gz
│   ├── d230614c583952b09f78b008bcdda95a9e15b81f.nq.gz
│   ├── d49c576b9d9c071fbae853069788ef7141a451d0.nq.gz
│   ├── d6cbc01421856f2a99c8420218a7e0829406ffcc.nq.gz
│   ├── d8d8742cca7ea2b4cd9844d6b343698dfd3e2a6a.nq.gz
│   ├── d8e6cb9659d6a14f3e10d5cdae782517eca2f1d7.nq.gz
│   ├── d93b4eff8cc2a33e01ec13bfa85d24be5343cd55.nq.gz
│   ├── e08513654a4374abbc9de78c50a93ade665e6721.nq.gz
│   ├── e630262696598084990d6c4cdf4586b8b63bd3ce.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── eef3c046d32ecf852739c4c638b0a3d2fd0584bf.nq.gz
│   ├── f02047963da83163d228a9b020a6e42e222758e0.nq.gz
│   ├── f0f1a11728189c435357b4f19863101a4f75ebee.nq.gz
│   ├── f7043fdb3cb677c8bc7f76a02ec8ae40c8f1cd3f.nq.gz
│   └── f7cec9224bbac5bb2515cf109ddf5a6afccbd56d.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 0252deed24451e835570619d67e60a674034d9d5.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 95 files
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

[scikit-hep/cabinetry](https://github.com/scikit-hep/cabinetry)

---
*Parsed on 2026-10-15 by [repolex](https://repolex.ai)*
