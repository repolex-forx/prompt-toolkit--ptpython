# Repolex Knowledge Graph of prompt-toolkit/ptpython

RDF knowledge graph data for [prompt-toolkit/ptpython](https://github.com/prompt-toolkit/ptpython), parsed by [repolex](https://repolex.ai).

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
rlex download prompt-toolkit/ptpython
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── dfe9dae32df17f6695aad6168ec271d02eb1232e
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── dfe9dae32df17f6695aad6168ec271d02eb1232e
│           └── chunk-001.nq.gz
├── blob
│   ├── 0692214da0c5f99235058dceaab9c3cac11ac8a4.nq.gz
│   ├── 0ff9c6c37565d5ae3dd732d06bf5a2aeefbceb20.nq.gz
│   ├── 101a6c5c6c627e7ee52c8c005af161419ff0fdda.nq.gz
│   ├── 188d69822390f567cfa27f6775c9f5f0aa949f38.nq.gz
│   ├── 2559a3c450af2cbe35bfca6b9e8f4189459bb5fc.nq.gz
│   ├── 2b293e6ffbdcb8c718914138677f20dd88347127.nq.gz
│   ├── 3143293e4bbc1f9746cd2f70f65b1252ef713127.nq.gz
│   ├── 3a2f7ddffa45edbc669f1ce6223814de12f3075a.nq.gz
│   ├── 40701cab07bac8eb5da6ee8778b6d7e95564f42f.nq.gz
│   ├── 465c3dbe4ef2f686ba1a88277958c7bab3b8b27c.nq.gz
│   ├── 48c5f5ae1a608381470785a63ee33620075e2006.nq.gz
│   ├── 4ee77de61a473ec29b05530e230e321610d481ce.nq.gz
│   ├── 5e8c70797badc1a1a1ba515685f636a02cfb83af.nq.gz
│   ├── 63c6233d0d6efc27ac34eb1f95baf1ce20ecb76d.nq.gz
│   ├── 7e218eb9fb88082b15b6bbef6d3f741d6bf379a2.nq.gz
│   ├── 8242df319669371afb0f7ae7b7b52912139bd251.nq.gz
│   ├── 838303f6f12ad32509da8f238e4ce9389840e20b.nq.gz
│   ├── 89a511441ab90a38dff1f52a43ffc0133ed5dad6.nq.gz
│   ├── 8d030dd140c4577f7f60ef6bdeccdc0ac40432b7.nq.gz
│   ├── 9077268913ac0bef1715c69a36bc8f50920c7e9b.nq.gz
│   ├── 922c6a397ddb24b7d55a3d4d7eab83a7e75947ee.nq.gz
│   ├── 923ca12bf94a13d673ee82fa425ecb7f0765e344.nq.gz
│   ├── 92cfc2a13fed6dc17443d90af53c6496b7ebbb85.nq.gz
│   ├── a2079fd36a3dd43da313071357f51dbb565cf444.nq.gz
│   ├── a3578de7e5630a33b8fd50aa93fa9c26b1fb69e8.nq.gz
│   ├── a52b5c2cc6d51fabfb31810409fbaa0c0b75e01b.nq.gz
│   ├── a6462748f7492993dc8fdb0657813b322b688691.nq.gz
│   ├── a7481011719b55bb527aa22cf6c8d47feadf8036.nq.gz
│   ├── a86737b6a0dad318dbdaf05672825e2aae336a33.nq.gz
│   ├── b010432b7179645a12d79615a6c7cb2f49cc2c26.nq.gz
│   ├── b3e5c9144becde3d4dc41ca2d2ad988a5634e4b5.nq.gz
│   ├── b660a0ac6909be7be6470213b923c0bc32a0119d.nq.gz
│   ├── bf79df78fa6d7ad75e25bd2161e548c9e849c840.nq.gz
│   ├── bfe141097186ec61aaafb96072653920da53ba0a.nq.gz
│   ├── c46b55a8e6bfb489a558cf67390f10c7c7c5a606.nq.gz
│   ├── cb6d1ed106b678ee614cfc99bc904e1cbb522f86.nq.gz
│   ├── cb909731db29e9b669a7f047cf73961a40035abd.nq.gz
│   ├── cce14a12f364e0cf6f167912e18f5704af6896c3.nq.gz
│   ├── cdfeb3283d37c4714eff9688c35e697188407bab.nq.gz
│   ├── cf2ee5420139cf0986f848dff30d278688bd849d.nq.gz
│   ├── d083858dfa524888e1dafe99d0de776161eb2c86.nq.gz
│   ├── d53bfcc1d2bc39bb63b6efc5e8f4ef6f50f45604.nq.gz
│   ├── d586d0f5b2250af09eeb68405b7d0e0da84ce161.nq.gz
│   ├── d925e95c50084b4b126062ef34f19e8cfe696228.nq.gz
│   ├── db4561eaa1d4f3ed01af114a315a0053776ffed0.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   └── fe8a9ae87b2c2d868ffa60d333b5c20c0afd624d.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── dfe9dae32df17f6695aad6168ec271d02eb1232e.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 55 files
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

[prompt-toolkit/ptpython](https://github.com/prompt-toolkit/ptpython)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
