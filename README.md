# Repolex Knowledge Graph of shadcn-ui/chatbot-template

RDF knowledge graph data for [shadcn-ui/chatbot-template](https://github.com/shadcn-ui/chatbot-template), parsed by [repolex](https://repolex.ai).

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
rlex download shadcn-ui/chatbot-template
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 55c9330d6251052c111cf93cc429efb387609b89
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 55c9330d6251052c111cf93cc429efb387609b89
│           └── chunk-001.nq.gz
├── blob
│   ├── 01876554e4eb81770afb03eac0e9eff3346ccc90.nq.gz
│   ├── 05e726d1b4201bc8c7716d2b058279676582e8c0.nq.gz
│   ├── 24a1e4098ca0a5398cf0fd2816c4d62a0f28773d.nq.gz
│   ├── 2c533c50bc348fb32a2997d7235b062d5f86607a.nq.gz
│   ├── 2cbf40ca9eee784ee784adb18534c4024800b028.nq.gz
│   ├── 2f8795a936c6fbca951780dd7da3eec156b43084.nq.gz
│   ├── 37ccfde75e91565350f28a218a008e06cf401113.nq.gz
│   ├── 396a6e57825b845c647bb6a6e3d8e8ba76c2188f.nq.gz
│   ├── 3bb22d1d9769686e4171d1209507314c81da09df.nq.gz
│   ├── 3cbad79e9c356fac2e015566daab3e58009024d7.nq.gz
│   ├── 3d44f4815118cefa955f645c7cf24796c77c4927.nq.gz
│   ├── 4254cb2ad9df6840d2c52991e12d2b19ba5ee2ef.nq.gz
│   ├── 42c699b7652457730a2c49b458b85beed53d4a61.nq.gz
│   ├── 461b0084104385d8cb1d4d6b5f6114033be973fe.nq.gz
│   ├── 50794416962882c2e10414847a4b92df9dcdce38.nq.gz
│   ├── 52ce4b0799ca2c1b328d4b26b48cb9b9444dc91f.nq.gz
│   ├── 53437e8db2b0fad1da06a7499e54ddaf116295c2.nq.gz
│   ├── 53fd072f14e5d6f572174bf5094dfa7e0f1a4e08.nq.gz
│   ├── 66f8ec1f51e7b23d8c395afbb35036ec8acf4b13.nq.gz
│   ├── 69366e7312de66ae3e55d9d72ed75f337b07a65b.nq.gz
│   ├── 6e1369e43cce8be3da7ef04940b79dd276245290.nq.gz
│   ├── 718d6fea4835ec2d246af9800eddb7ffb276240c.nq.gz
│   ├── 746032577491395703fcec2850ff0012978ab265.nq.gz
│   ├── 7e62ceb18f2c2c13f9ce15df9c53ba0f6b31824e.nq.gz
│   ├── 7fb615035bfadec31e40aca434b248248f59e2a8.nq.gz
│   ├── 807c8ce14bd8d9e502fbdfe51631463d0cecdc49.nq.gz
│   ├── 82c653405e1215db82ea759ca444d3850828be09.nq.gz
│   ├── 8ac33304a48ff6fb6aa109e5de3cb1063d655c55.nq.gz
│   ├── 8b45cfde2fbd29af3719f403d44f41e3f88ac3b7.nq.gz
│   ├── 8bd0e39085d5260e7f8faffcad2fdc45e10aef33.nq.gz
│   ├── 91c3b1eb08112b69588ecb8d91baa0390d64dc3e.nq.gz
│   ├── 957d2ae53e05f3962817659bbc9493dd6fc866cf.nq.gz
│   ├── 9d304a18704eef513b6ec78d8649f5f98452f6d4.nq.gz
│   ├── a0bb02d839d9784d6ff3b5f51bff9c44d388285b.nq.gz
│   ├── a59c8afaf202e6de0f04ebebeac25620a81e4c7a.nq.gz
│   ├── a7669b8a8dea346669bf103a237ed60de2a2481d.nq.gz
│   ├── a788e20e1275ed5b796f79dee8340cdee4cc881d.nq.gz
│   ├── a8a2054a152e7f764ca02887b8ec7c9c91a091b3.nq.gz
│   ├── acc47bb1926cdb7b6d3d31801d98956e970cdad7.nq.gz
│   ├── acd849f47316386543a1bc0694e8add70077571f.nq.gz
│   ├── af4976ce11ba2e6599d815154b165af3e00b83fd.nq.gz
│   ├── b1f429a7669d9d4052d870f4fb110026f5da046e.nq.gz
│   ├── b48cfa9883de514038d7f9c77d811ffa1c9b5764.nq.gz
│   ├── b51f352c03f27c135450c25c82a39b57ed75d6da.nq.gz
│   ├── b60f81f100d611f9a05fcdfc9f4f5b61aeafd124.nq.gz
│   ├── b71df62dafd3da026558a25c4b0bd2e52774be40.nq.gz
│   ├── b88f76e1d759a240d296c143735ca73d643cb3ca.nq.gz
│   ├── b9f98e5f8733e1c2764444f631b324c30a3ebb45.nq.gz
│   ├── bca0e21ac88217b481c589802feb66db29a1b648.nq.gz
│   ├── c0c0801bd2ff14572486504ff0ee955bf4e56bf7.nq.gz
│   ├── c45576d0a32032548b753b64a0e9c08bfe9d05a1.nq.gz
│   ├── c8ff116def3fa231090155d9b26d6ad84f7317ee.nq.gz
│   ├── d004899ba06b3870312d35649f16063f5a013e34.nq.gz
│   ├── d37daf2768158160c4305537a932425c29d02a03.nq.gz
│   ├── d4a431c863bdcf316e0f0a37a7d808d7664b7068.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e87e24da14e72c8e4b61379587a2c98a8e146b02.nq.gz
│   ├── f40013f615fb9b8a7bc1937b5aa057c6c6d8cada.nq.gz
│   └── f88469f40f26a878bb00265d2768edd6455a1ba4.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 55c9330d6251052c111cf93cc429efb387609b89.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 67 files
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

[shadcn-ui/chatbot-template](https://github.com/shadcn-ui/chatbot-template)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*
