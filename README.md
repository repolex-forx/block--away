# Repolex Knowledge Graph of block/away

RDF knowledge graph data for [block/away](https://github.com/block/away), parsed by [repolex](https://repolex.ai).

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
rlex download block/away
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── e23f9990bcd431df45ae57933c36c1a9648eb5db
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── e23f9990bcd431df45ae57933c36c1a9648eb5db.nq.gz
│   └── repolex
│       └── e23f9990bcd431df45ae57933c36c1a9648eb5db
│           └── chunk-001.nq.gz
├── blob
│   ├── 0ba9db25329d0b336e39ca8cde8470c5b7bc45eb.nq.gz
│   ├── 0cc8230a60cd622bd8ff1853d033cc09007bf762.nq.gz
│   ├── 0cd8eeeb56888228768f8d41da055e6902c30bea.nq.gz
│   ├── 16541387f889120bb8ff1539975c1999bbf156b9.nq.gz
│   ├── 1baf1af073ebd3c5c9342e72360bc0b6db3c0725.nq.gz
│   ├── 2190bc589af3881ec8c1d67f51b1ba6646675f49.nq.gz
│   ├── 25f0bc5ed80683a81f46e6bfd1cf8ea0b56c6807.nq.gz
│   ├── 2714d6fc9f6d1f55deb0d167eb77d402a27a9065.nq.gz
│   ├── 2acf281c18b216d5cb32f85b9449dcc31ffd883e.nq.gz
│   ├── 2f59d30e9f0dcd49c128feb244dff276d865822a.nq.gz
│   ├── 30e4d1ef27f4115300eeba013b910d3341db9423.nq.gz
│   ├── 3720bb4810d4448a6cb60a74701ad2395fa5ebe5.nq.gz
│   ├── 3b8d44ba5778fc0f71bd6e30a1eaff082dadf6f6.nq.gz
│   ├── 3bf370a8762a58315b237208e5204089312ec483.nq.gz
│   ├── 3c4a5bfb6b750ddaeb3ad862712088b8b2dbc7dc.nq.gz
│   ├── 416bfa6d5a4ed2c8cd14e52bcb98632da6771c60.nq.gz
│   ├── 440715275c59b96286414333adb0f5f742aad2e7.nq.gz
│   ├── 466114f6f79b433c2fb7eeda86551e59a9f86741.nq.gz
│   ├── 4691afa83e04024c8293649437c9c1e5e5063a44.nq.gz
│   ├── 4f1eba7c0054782968ea17b212a394bb596c227b.nq.gz
│   ├── 564999486af2dbff0459a6f2d9d185c7c3866625.nq.gz
│   ├── 5ab5332e0023127a8a108eee021e55292bbac78b.nq.gz
│   ├── 61a04b7826483c44bd62fbaec97ea24440c0055e.nq.gz
│   ├── 66268536bab92a37bada7153cf38c3e8cd9e4002.nq.gz
│   ├── 68b44c960a6d471ff7c1bba752f11eea485d5beb.nq.gz
│   ├── 6a8fd675ee4385a1f532a3a3b4c8a3ab16ed4786.nq.gz
│   ├── 6ae6c76a6cc6d76514c703bf96ba04988bd25851.nq.gz
│   ├── 6bccf43368fd7c96d9c659562a5142b8b8cb98a1.nq.gz
│   ├── 6bf54673d6d7e5beb5e9c9df29a72314130d35d7.nq.gz
│   ├── 6cd3e1b92f61709d6a8d74109ca1cad6d4e5f16d.nq.gz
│   ├── 6d98e982dd730f5f4a6a6e050f4859e60d182135.nq.gz
│   ├── 7477df5a748af843e0dd41b900ed99708d0f3ca6.nq.gz
│   ├── 7b8c682abc3d2335f03b76db82cb18100b3b0093.nq.gz
│   ├── 7d463b56e0fb33e7a979d0b43906816465c59338.nq.gz
│   ├── 862ee3c28647e7a58801a75236855c269c1448ae.nq.gz
│   ├── 8bd974978df20cfe04c2b1a84ed2b15f75e8ff95.nq.gz
│   ├── 8ca49789e6c4d0b6d8364adb8b267a98c021d9d8.nq.gz
│   ├── 8e70bcdca874e72b19e016c082f3110e3edeffcf.nq.gz
│   ├── 8fbaa33cc3434b8a87703287756505897351321e.nq.gz
│   ├── 930b3569f30af3164ce37691118f9a47908bea5d.nq.gz
│   ├── 9582fc588754f78d9875691a3bd5e674295436b3.nq.gz
│   ├── 99402439700c381007f54a71cdf8b57e56bae0e0.nq.gz
│   ├── 9b49afaf51efee156e1bf195a6d22dc472d11f32.nq.gz
│   ├── 9c34bd0a496d1e01c29af67154c1f297bb3da9c3.nq.gz
│   ├── a23ab18939bdf2af8bcf75658fb66ef71b0048c5.nq.gz
│   ├── ad03024bbd57d0d96cdd25769366662f851ac95b.nq.gz
│   ├── b079cea581315eea3c334db4f947028584eb5a28.nq.gz
│   ├── b156dd63a9c6c78d86ab8a96964bbf3dbe4e493c.nq.gz
│   ├── b2948124768142f1c1ca61ae8cfb6dacdc0c053c.nq.gz
│   ├── b81fc4b3f0893b162a6f084fe7978a6c3e6696c4.nq.gz
│   ├── bd690694625d9b1c90751304587b6a091872869a.nq.gz
│   ├── bd6a43eaf4192335b1115a2720e2d769603e2756.nq.gz
│   ├── bdb24be1e04a9b086f52c3c879832af1d77bca60.nq.gz
│   ├── be5548e6a40614c4f9dddbb74cecd9c75d790599.nq.gz
│   ├── bee9c333af02e6077b5bfa4fe4622c5c9a1a41bc.nq.gz
│   ├── c705190a0bd2e9f1e5630a3134108cbb77bf990c.nq.gz
│   ├── ce56cd2549492ed1251ed9d6029d895f555fa6e3.nq.gz
│   ├── d2de7934f7985b267eb3ccd872b808628ede5f68.nq.gz
│   ├── e47a743bdb0f5a5776d37e32be94a62abf2d5cd0.nq.gz
│   ├── e7406ef6edd58225444ad32f9c6d72d8bcdafcad.nq.gz
│   ├── e955e9da8daa78c24e2b140785ddda5a80637bdd.nq.gz
│   ├── f0c78311329ffce15c00abb2c6d911b5943fdf18.nq.gz
│   ├── f1e3ae69195edfb67345c4c5921dc544f9d4b96e.nq.gz
│   ├── f20c764fc2216a8d56df11df00346cbeccd0aed4.nq.gz
│   ├── f9ed5c62b0020e1e732e442dac27cdbf54311800.nq.gz
│   └── ff98a98ccf8c5a1f6e451f5307e3e5080ac0e692.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── e23f9990bcd431df45ae57933c36c1a9648eb5db.nq.gz
├── issue
│   └── issue.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 74 files
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

[block/away](https://github.com/block/away)

---
*Parsed on 2026-10-01 by [repolex](https://repolex.ai)*
