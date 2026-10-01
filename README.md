# Repolex Knowledge Graph of block/rce-agent

RDF knowledge graph data for [block/rce-agent](https://github.com/block/rce-agent), parsed by [repolex](https://repolex.ai).

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
rlex download block/rce-agent
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── a26c1f2fbf9c5616a9169fda4ecb5dbf207d7eab
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── a26c1f2fbf9c5616a9169fda4ecb5dbf207d7eab.nq.gz
│   └── repolex
│       └── a26c1f2fbf9c5616a9169fda4ecb5dbf207d7eab
│           └── chunk-001.nq.gz
├── blob
│   ├── 038cf588895d5f47c0a226c1b79e4f482af058c2.nq.gz
│   ├── 10040c7c571b09396d10e82443225e790c9c92ca.nq.gz
│   ├── 15eb7944180a5f883ebb480f36dd8e6935914a90.nq.gz
│   ├── 1f8edc2d5d80c4e0da43516a25f95d28b09c2652.nq.gz
│   ├── 215dc5191595ff360d67990c271e33233536bbb2.nq.gz
│   ├── 3131b53670b203139c77be9baf5fed5a93e8c3ac.nq.gz
│   ├── 334018a9d599465abfada50e46dc91f8c8f4ad14.nq.gz
│   ├── 37f526a6099e827397e88afbb9f9a1ea21c9db03.nq.gz
│   ├── 3b8239dce30415e19a234724eb94157000597ce5.nq.gz
│   ├── 3bfb4507300b1b8d104e1cb3842a276fed041baf.nq.gz
│   ├── 4104bf012556851f62abbf6ff095b122a0864d65.nq.gz
│   ├── 454c04ffd8729bb7f47a24ee04f881d53453691b.nq.gz
│   ├── 49b2b387f28c98bb8353b3fa57c036f1213261ed.nq.gz
│   ├── 4f1d51b8517c81aa21ac4f7ccb9e6eed2986e0a7.nq.gz
│   ├── 4f66caf1078719376509dbef102b6b332460450b.nq.gz
│   ├── 4f9e8780f7d2c07326c407eac43b42abe47e5f4d.nq.gz
│   ├── 61980f76bf41bf2d627f1c403d49ef4440c42d4d.nq.gz
│   ├── 63ee0286fcb0c47d01a21a3b122ac68892337608.nq.gz
│   ├── 68ee2a9448cd2598468599e206b271064b8485ef.nq.gz
│   ├── 6f84a0d4e8a7a525545ce7b9490b16c0bd3e8aca.nq.gz
│   ├── 6fc9db95b6e6494c26c2bb6c2e5ef393f61d8b8b.nq.gz
│   ├── 77a4099cad83cf1784be10fe7e98d7786add3130.nq.gz
│   ├── 7e238303cad589b0b78b16b58db567d28c085339.nq.gz
│   ├── 83ef19a34202130752d0104f743d1108bcf4d970.nq.gz
│   ├── 9a8c5a983f4b597b5e3d23e1e19c6869f28a11d4.nq.gz
│   ├── ade0098dddb502ffe74221bb47cec95f70093e8b.nq.gz
│   ├── b0035c9794043d7410bfb10f08317ed91e02ac70.nq.gz
│   ├── b7ed71132e54969c3d2be22d7196268a0414f8cb.nq.gz
│   ├── bb6a038802ddd0ac0205f709be8c4ef5ea219465.nq.gz
│   ├── bc0e4081e272a7bad53181ba9da89e3898d7cc70.nq.gz
│   ├── cd60cdfaed23aa648a59ba612226bd6e68ac5f10.nq.gz
│   ├── d18bb06027c9cb9e75305ab8c56f3650bd803afb.nq.gz
│   ├── d93156eefcfe78af34955afb0e777d7b480e1038.nq.gz
│   ├── da209ddc798345ad7fad11be0819844814bc47d0.nq.gz
│   ├── e43990fc4d8913441fe9806e1a0e95902d33acfb.nq.gz
│   ├── e52d1bff20c9afc40ced8639c8438fa8cba0ba7d.nq.gz
│   ├── edaa44fc1dedbe7c0b48d1091a494afd2f22069d.nq.gz
│   ├── f727edec72cd889dbb7fa854f3e17d969803953f.nq.gz
│   ├── fb36d0cc4f798e3ceec0c5a6e19cc042d9dcbc4e.nq.gz
│   └── fc40d13997d6aa4302bd646afb5b7d637a54096a.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── a26c1f2fbf9c5616a9169fda4ecb5dbf207d7eab.nq.gz
├── filetree
│   └── a26c1f2fbf9c5616a9169fda4ecb5dbf207d7eab.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 50 files
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

[block/rce-agent](https://github.com/block/rce-agent)

---
*Parsed on 2026-10-01 by [repolex](https://repolex.ai)*
