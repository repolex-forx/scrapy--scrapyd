# Repolex Knowledge Graph of scrapy/scrapyd

RDF knowledge graph data for [scrapy/scrapyd](https://github.com/scrapy/scrapyd), parsed by [repolex](https://repolex.ai).

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
rlex download scrapy/scrapyd
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 50c4aa1d6e2cbd91fcecc63b604be168f7025366
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 50c4aa1d6e2cbd91fcecc63b604be168f7025366
│           └── chunk-001.nq.gz
├── blob
│   ├── 004c90a41f1e41d7d627e31bda686bd9a51398d5.nq.gz
│   ├── 00c1336ee32ef599c9b7a7a0ecaf49d72f4d175b.nq.gz
│   ├── 01791657d927373594f1b7fbe85be795eae9470f.nq.gz
│   ├── 05ec81428c7b0157a2d60809a4e07e65b3e549b7.nq.gz
│   ├── 09bf36a0fd4a2ea85d2845ea4aadad9ddbc7de71.nq.gz
│   ├── 0a5b477897e0e3a81deb22bded1042b9aecb6213.nq.gz
│   ├── 11fa05cfc171969faa0c757738df59f82fc4efdd.nq.gz
│   ├── 123014908bebbfb7ecfa1d15daaceb272fabe05b.nq.gz
│   ├── 1b04c54bda620b053f9b8bcd9c6ccc66653f8b71.nq.gz
│   ├── 22a4ec456793805cfda15a9b0ad78967e4dba5d9.nq.gz
│   ├── 22d62de9694114d38393713a409c2569876a827b.nq.gz
│   ├── 29e3f7b68df88040b5fa5c8a8c4ce215a80d20e1.nq.gz
│   ├── 2ac4bdfcaa6af658ebe2707d53c43c73468293ec.nq.gz
│   ├── 2d280ce9d6526789a1b31410f3b80cc949753e81.nq.gz
│   ├── 35c1f446f334022134b609e9d72c7e6402dfc23e.nq.gz
│   ├── 384948bf21d0d9cc9edba33b42259ef804d373f9.nq.gz
│   ├── 3b7dd2988044129a8a40424ffaf9faa3847d5349.nq.gz
│   ├── 3dc7fc8b1f8945c5aec34ed3147fe1705ab64aff.nq.gz
│   ├── 416d002d661dccfe34ead0a4977945a8ea749b5d.nq.gz
│   ├── 422c921053f8ebb39429404fddcc620b5b300700.nq.gz
│   ├── 43941de4376b013e022377a3160e0a494e9806e1.nq.gz
│   ├── 45d6aa7a3f9b1689ce5b734c04ad6cadd506988a.nq.gz
│   ├── 4741b16c17b17e0475eff33fc70dc2fa76e4c15e.nq.gz
│   ├── 47fe06ccac201b3c26509fc9fedceeaa89be30b7.nq.gz
│   ├── 4850f732581224ea47e26a579d2b10be59d56ff3.nq.gz
│   ├── 48c666066379983fecb19031372ad16bb4a63581.nq.gz
│   ├── 52359a7ac2bb3ed0622e7e6a59c9617ec3d66027.nq.gz
│   ├── 52fbcc2418d2b7d126cc89fde9dd7a2a75f35898.nq.gz
│   ├── 54f287fd07994f8dc87fce6039b77259327974de.nq.gz
│   ├── 560aa8140042861c4a5f82c0011e26894eb17aae.nq.gz
│   ├── 63af6f9731ac6a372c54955ec78ba1d5569d0207.nq.gz
│   ├── 657b4e74ebb72d842b57038ed4fddd5b718e48ba.nq.gz
│   ├── 661fc638eda35b423c7bb9cbdfaec0dc5ba7bd5d.nq.gz
│   ├── 6630d0fb13e5f1734a6a0da9996f4e239d408a5f.nq.gz
│   ├── 68ccf976261e2eb7a928b2e6b59cd2ffed86551a.nq.gz
│   ├── 6d4d77ca0a237b2fc4cdd86c21ebc51cfb22873d.nq.gz
│   ├── 771fb419e737c4bc022fbeca3387dd42674446e5.nq.gz
│   ├── 79f09e6a316c8e66b98ca6e6b962f64727684648.nq.gz
│   ├── 7c460b30ef724b513cf16382b3d80dc4a45050c0.nq.gz
│   ├── 833f2965bace3da020e16de2d5898945972ea0d4.nq.gz
│   ├── 83dcf4318413bee327f0fcff22c09efcb07b1b54.nq.gz
│   ├── 84749991a7195a8c935b1dd0b0596884d57d57cc.nq.gz
│   ├── 84f1fe8d37f9844602e458ec464c1363a6de6db5.nq.gz
│   ├── 8e56778cf473b758801558b8d565704816e5c8ff.nq.gz
│   ├── 8e7ef1d1c30df25241dbe4abc579ff75e0eb1308.nq.gz
│   ├── 99b8fa0f20fc34bac39efbc906d999b0d22f38b0.nq.gz
│   ├── 9af0ecae8ec5bfef8a8242671fcb96cfa181cdd3.nq.gz
│   ├── 9d182f572533f73a97346c1178d98ef5013b4d21.nq.gz
│   ├── 9fee9430639f14deb4adee72e50adde54e7111bf.nq.gz
│   ├── a5f718bffa8982cf174087ab2eb034add7de7a60.nq.gz
│   ├── a9a4e3506193ac50278f4423b9e0fcf5ec67fdb7.nq.gz
│   ├── aca6313335721c10fbfa2b4d499629d15a9e46c1.nq.gz
│   ├── b3ccf970118893656089afd38e4434900eb4c434.nq.gz
│   ├── b49658ba235e8d56231a1965c56959f6bc137601.nq.gz
│   ├── b72b2cda47ab4fe5fd3216108b2134646d8cf3ed.nq.gz
│   ├── bfb5457c747cfebf6b1a5ecdfa9d029d62d07053.nq.gz
│   ├── c02649824f872696e590e7aeec4dfd6dd8563f3f.nq.gz
│   ├── cad8252a6adbee24b36d0d65028df72240ef3244.nq.gz
│   ├── cc0110b7445c5c7bdf51947ce7a5937cca2c85cd.nq.gz
│   ├── ced67c1b17fcb9516917ac3f8f19a71b333daf4b.nq.gz
│   ├── d08a2f576ee340dff42b02c67eeed3645a7c7555.nq.gz
│   ├── d349645ea98c328ba83fd7e1965feadbc6fb6a38.nq.gz
│   ├── d50e3c836f1258de1041cf83439e981c99759f68.nq.gz
│   ├── d6d3a2f895aedeeb41625d28d7cae16b1d13560a.nq.gz
│   ├── d72fa000c4a0967a5aaf78ed1cbb52f4364f2f2c.nq.gz
│   ├── d7ae038f5db9dcef779190d698169c22842f1c73.nq.gz
│   ├── d7c6b0e4e85103cab97dcf0f2b1ee2b79abbba2d.nq.gz
│   ├── d8919cb8e78b32e96d24d2cb66ccebf1ba0d684d.nq.gz
│   ├── db6b5734fcd30d06c5526f9c647b57e7bd764e66.nq.gz
│   ├── dfc6b5125a21375addd06d088e0466694abf6e1e.nq.gz
│   ├── e368ec0d9884739611d368ac83ee0f40ef1e29a3.nq.gz
│   ├── e3e9c34eb908df220be9655ad4b4d67f6005c1ed.nq.gz
│   ├── e4f08fff6eeebdbef2c0f4029862868a64f304dd.nq.gz
│   ├── e4f8baa5f6f79fef058bf687791932185164019b.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e720e10780af8fdfa53f87d59637a6e9a4f646a4.nq.gz
│   ├── f3b7df8ea5ac48437d5df34449dff19bf7610183.nq.gz
│   ├── f651cc8fe1f6093dddafd5b58df932c63abb0742.nq.gz
│   ├── f8e3a57005fffc35b770a383f5e57685c47aadf3.nq.gz
│   ├── f97a2f45563df45cf00d079c7cebe9fbcc3d164b.nq.gz
│   ├── fd31b1a7e91269d5b9af05a2f215d7aba3976102.nq.gz
│   ├── fdc367ba1cf63117d8314482a188e1da64a55324.nq.gz
│   └── feec4800323ea80f2dfadaf04d30b2f092789b3d.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 50c4aa1d6e2cbd91fcecc63b604be168f7025366.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 91 files
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

[scrapy/scrapyd](https://github.com/scrapy/scrapyd)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*
