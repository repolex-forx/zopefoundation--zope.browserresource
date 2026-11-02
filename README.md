# Repolex Knowledge Graph of zopefoundation/zope.browserresource

RDF knowledge graph data for [zopefoundation/zope.browserresource](https://github.com/zopefoundation/zope.browserresource), parsed by [repolex](https://repolex.ai).

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
rlex download zopefoundation/zope.browserresource
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 5449860657e873408986fe5f3aa8b292cc736ac6
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 5449860657e873408986fe5f3aa8b292cc736ac6
│           └── chunk-001.nq.gz
├── blob
│   ├── 0b48ef9a2fb6379b6efc0ec6d692191fab78d581.nq.gz
│   ├── 188120b692cc972bed5f7063baaa7ebd9dd5fcea.nq.gz
│   ├── 1d73b2d79dc5bd93f4b5a606c3c78c88ddabfeb1.nq.gz
│   ├── 25196309a9d542c581601fff21ff148e7f488edf.nq.gz
│   ├── 297d2788119ce6f26940bce93dbcb977ba5193f1.nq.gz
│   ├── 2add2270a224b030b65d2e386c4c06b7852de56c.nq.gz
│   ├── 2e2efdb91e2bf5d9d57117bc54a3b6c5e6d85802.nq.gz
│   ├── 31a29e7e74b4ab26b24fbceeaadebb55669d3aab.nq.gz
│   ├── 39f2e93211f160bf83a555f62727c45a8b81acce.nq.gz
│   ├── 500c4d55d6236996f2e063c48ca87fc7cc327670.nq.gz
│   ├── 53d071365f1e42a5da517887243b90a4d55e7715.nq.gz
│   ├── 59bc653fe5a4f4c3376451f5f65ba12e5e13ac8e.nq.gz
│   ├── 61d1f177d3301dee4f90e09c1f8006e0f61e0ed3.nq.gz
│   ├── 64ea3ead117c5fe1e5370f748c5b7580df2aff64.nq.gz
│   ├── 6f92133aadafb8d14f9e11bb78ff3a77b66d4526.nq.gz
│   ├── 6f94a3c0ed804d7c5dfec5aac9270e0ef9ddbc81.nq.gz
│   ├── 78bd1c6f8eed1e47c2239e18a56796e12a508939.nq.gz
│   ├── 79859e06010bf4967c5b4b044afea6ef39742938.nq.gz
│   ├── 7d8c81c0c1dc1d5b488a3aaf875a36ebd9552fec.nq.gz
│   ├── 8593ee9b188eb2064b279a176fa2d27da29650d2.nq.gz
│   ├── 8a1cde635fcfe005cc4438d504940505395236a7.nq.gz
│   ├── 91bd51205733c71ae2fdc9a510fafb75d1829997.nq.gz
│   ├── 952f12044c5818fb89db8e82843266191af1945f.nq.gz
│   ├── 964bf79970a924359912260d5eb37d638cebb8b2.nq.gz
│   ├── 98d41b7bede561c830453fe5f508cf66cbe8cfaa.nq.gz
│   ├── 9dbf5c13dc55a556cad04f9698f41bc93c6f520b.nq.gz
│   ├── a11fedc3c3a526b6e2c43ffd6b6c6b20e4b4b2de.nq.gz
│   ├── a162d53c25b678d6486be7b50f79846d8a78fd0f.nq.gz
│   ├── a1829bf68d65742310e5333efa15f7ba7d893c43.nq.gz
│   ├── a61c61def3157b5edad6d67b3cbd6949cabb8f84.nq.gz
│   ├── aa14ff42e95d1a4f958e8652810766d3a95d6eb4.nq.gz
│   ├── af689dc864b584f0f0c10ba01898daf4de21c574.nq.gz
│   ├── b595bb669aaa0d28e5929af0f246bb3de42fcca1.nq.gz
│   ├── b8a0a4a3be07445523489307f9392c9c317ef257.nq.gz
│   ├── c02de2982bc966f2a63129e642a6e7190ffec800.nq.gz
│   ├── c0db44e8c34adb931ee88d040d47939191d27251.nq.gz
│   ├── c8e909b63ec49da954ced1a8907d4b339aaea12a.nq.gz
│   ├── ca517f4eb0cec1c691c0c2b54cd5eb85e906f11b.nq.gz
│   ├── cd3c4100ed55fc2323bc839957d9ea0d19dc54db.nq.gz
│   ├── d2d502902f40dcf5281e2fdefbcd2548f95f1c06.nq.gz
│   ├── d9e113ec685b92b018297dd2f200341d1fba01f9.nq.gz
│   ├── dcef4ed41c5bc663fc0f17108d37ee7fe1a7f05c.nq.gz
│   ├── dd729ddb81158d3f606c90cc3ceb7bf20a9ee828.nq.gz
│   ├── dfe77698a1a530f6479d0ee452d453656a7ace8b.nq.gz
│   ├── e1f9ad7b3b48377bfbfaa1b380c384ddea24060f.nq.gz
│   ├── e2831f4659cff427fff960848f638d6b9435d93d.nq.gz
│   ├── e2925d37406951ec59151813aa71b6adf6aa8845.nq.gz
│   ├── e4b867329e05886a4818f86b117fca2102bc84bf.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── eb4f53b6e4eaaa1d4062bf1b40c4100d4afb388b.nq.gz
│   ├── f0eb5bf97d96123deb3adf990a1ec163a01fd15b.nq.gz
│   ├── f81cabf053fb4487bb3496afbc276556076bc3f2.nq.gz
│   ├── f8459be6f336f80dedd2a009de24bafc889bd150.nq.gz
│   └── fac4cf42940a960df2b058a29dae3b58ceb992b7.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 5449860657e873408986fe5f3aa8b292cc736ac6.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 62 files
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

[zopefoundation/zope.browserresource](https://github.com/zopefoundation/zope.browserresource)

---
*Parsed on 2026-11-02 by [repolex](https://repolex.ai)*
