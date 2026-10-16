# Repolex Knowledge Graph of xarray-contrib/rasterix

RDF knowledge graph data for [xarray-contrib/rasterix](https://github.com/xarray-contrib/rasterix), parsed by [repolex](https://repolex.ai).

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
rlex download xarray-contrib/rasterix
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 92131e0d5a0568bff2ccb46c8d44f0586490256f
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 92131e0d5a0568bff2ccb46c8d44f0586490256f
│           └── chunk-001.nq.gz
├── blob
│   ├── 04c71e4301f7f26d971d71148790965247db99b8.nq.gz
│   ├── 07a9f569ebab35bcb2c1fe3e6520402f8816467b.nq.gz
│   ├── 09c98a0aa492918091e2dfdcedf941a56d9e6f56.nq.gz
│   ├── 0aef71693d7f751cf76bb2044cd7d6c4a9fde94e.nq.gz
│   ├── 0cd87e97f7005aa326d683201a0b4efe794ab2d4.nq.gz
│   ├── 10e599a119774895cbadcf2a79b3399ade7266d8.nq.gz
│   ├── 226ad5c65bcc65dd71727d1ccd5c2c5685604888.nq.gz
│   ├── 23e08346862346ce81d8731af4c095dc2b518a28.nq.gz
│   ├── 260874fc3d53b20a42e0086fe007b8cf75e54c14.nq.gz
│   ├── 2820652d5e4f0fa9a9b7a09ff01143852c1eedb8.nq.gz
│   ├── 2ac2ce4f2c0a700e690aff2d191932c1b5ca6d53.nq.gz
│   ├── 2ae7457971fc54e73d822b378e91cfe371903542.nq.gz
│   ├── 32f3d0eb7b3c0b443c1bcb2209a1dfab4a3bd648.nq.gz
│   ├── 391f54bb40332cbc45a4cdc65c28d4bb235c9681.nq.gz
│   ├── 3cac3457fe69e253e959e65c5c9f38502b9930ab.nq.gz
│   ├── 44f3e3ced1aeb027037d89589fc409591e49bb8e.nq.gz
│   ├── 4c1f03e3b4abd441308273a906878f8d9671fe8c.nq.gz
│   ├── 58eeb080908966d39a9dda95070cee990a7cb1e5.nq.gz
│   ├── 5b50d3f86b7b7be7c0e7b26a3bca9ecb835d68e6.nq.gz
│   ├── 5c15ca16e739b5e758a49fb85e66f742fd6f54b8.nq.gz
│   ├── 5f3bf23986f4ce08d966d61cff48b0092de51a9a.nq.gz
│   ├── 688b73231d1af0043e30834dff07fc950208230e.nq.gz
│   ├── 6a8d8492d6f77a84579a0148abfe439d4c3839a9.nq.gz
│   ├── 6ae6e38362a40544c03a7860d034994e63f3e107.nq.gz
│   ├── 6ca5930d9cd8514925b6c3c1234db0b704ff56ec.nq.gz
│   ├── 6f40a9707351f841f99a13a4d0053d05d4dc915b.nq.gz
│   ├── 723029518baca0fd1487acef3b01213875f49621.nq.gz
│   ├── 737aac0bed915e026a409582855b87c37bddbba1.nq.gz
│   ├── 79dd54f6a3ca01020e28b5cd27b1afd9389678bb.nq.gz
│   ├── 80f4ebd6417bb70f16f538d5cea2609654c82a0d.nq.gz
│   ├── 8146e9f3f6f1227cdd1cd48630b81ea2c627a6e9.nq.gz
│   ├── 81ff943e9b49f6b04442b0958cf8918baace5b9b.nq.gz
│   ├── 836e0dcff10650de5cd19e5dff2d2c4c27b66535.nq.gz
│   ├── 8578e4720bcb2ed7cd260b0a253cf30e3414071d.nq.gz
│   ├── 86266e5b5d2c4256971dd1dc9b5a423af2027efe.nq.gz
│   ├── 8ab4824e9339399087db73081578c6170e9b9ca0.nq.gz
│   ├── 8af60509d3ae92e0de2534eaf9db8838fc0581d3.nq.gz
│   ├── 8b08d3a2dbe3e0ae22b1c91551eaa1c73d3c72cf.nq.gz
│   ├── 8eeb5b9fd709916d17941cb6948afc7ee2048447.nq.gz
│   ├── 917ccc16cda1efc387b0ce9e59ba9386a720e526.nq.gz
│   ├── 933fa385337403a06d727ac9349653d21e161a04.nq.gz
│   ├── 95dba6f5ca5638f3b72fb18e2d08c191e172f72e.nq.gz
│   ├── 9f951280dc36f7052a111596ab34ff8db0b8d053.nq.gz
│   ├── a20d4362038406ce22c138dfedc3231f267170fa.nq.gz
│   ├── a5c6f3e93c88f01174e29ed142725b729070b481.nq.gz
│   ├── aa855f643da881ba8a34d465c3fd6fb148357e63.nq.gz
│   ├── b4194bc0a8d8f1bf16e38cf122d672b20675120e.nq.gz
│   ├── bbeebc50b57f75eb7f51a947a74faeba251bbd33.nq.gz
│   ├── bc482690e9d55e6ee709c2e257ca0e1117ef15aa.nq.gz
│   ├── bd3685313bfa3c8072a716bb420652f19cabadb0.nq.gz
│   ├── c898a19b2c434cce2f057f9c3e1acb21066e4a3f.nq.gz
│   ├── c98d1c17381f44c1ac0c0bb625aed2486e1123d8.nq.gz
│   ├── cb7a59535a4566ba66cd13b49615e8280fe35376.nq.gz
│   ├── d3d344fc045eac21317e6e6c25ccceaba0fb07d7.nq.gz
│   ├── d7f104b8f6ba0057485b6853137b3d1ed63fa38f.nq.gz
│   ├── d86c3613e4d38f1a86190b9c2bbc02082a1c2bab.nq.gz
│   ├── da21f6ca3b7f25bee96d4fbf801ee713f9affa70.nq.gz
│   ├── e8dba479cc28baa6c3f7977825fa00694363d239.nq.gz
│   ├── f3fce6e035fc1222c3620606659668a21d28df64.nq.gz
│   ├── f5f92aa439cf7a7a5205a9eb8356beaa8519da22.nq.gz
│   ├── f817bd4a3b33dfc7a475fb6a605e77236a873715.nq.gz
│   ├── f9d4a9dfda818b2cb10a6a4c17872df0a28b3819.nq.gz
│   ├── fe758108103233dc058efb50a99e5aee04b2e16e.nq.gz
│   └── ffa270c02cbe389f377c9ce85fb250cc80c8665b.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 92131e0d5a0568bff2ccb46c8d44f0586490256f.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 72 files
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

[xarray-contrib/rasterix](https://github.com/xarray-contrib/rasterix)

---
*Parsed on 2026-10-16 by [repolex](https://repolex.ai)*
