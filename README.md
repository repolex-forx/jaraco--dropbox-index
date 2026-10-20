# Repolex Knowledge Graph of jaraco/dropbox-index

RDF knowledge graph data for [jaraco/dropbox-index](https://github.com/jaraco/dropbox-index), parsed by [repolex](https://repolex.ai).

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
rlex download jaraco/dropbox-index
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 4a9fb3779037858f6eabbad0f550ca78e68e932b
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 4a9fb3779037858f6eabbad0f550ca78e68e932b
│           └── chunk-001.nq.gz
├── blob
│   ├── 0c76bd1297751b66230f74719504b2adb02b1615.nq.gz
│   ├── 10d412f406891b9683f832fcbc134c9bdf4f916e.nq.gz
│   ├── 16403ae42ee25451982d84acfd7304fba2f8c273.nq.gz
│   ├── 1ebb193243780b8eb1919a51ef27c2a0d36ccec2.nq.gz
│   ├── 1f2aa7533b0423a8eb943f6f4ec02498e39581a0.nq.gz
│   ├── 240329c3604d8ead4c10aa8c88352caa8e4ce7b2.nq.gz
│   ├── 2e3f4dd791a6372b427d618eb0baa8c4dc58e5f0.nq.gz
│   ├── 304196f81e11a168c9894f966e4a617ebf4ed53c.nq.gz
│   ├── 375fceef7d00e647be2eee11768eb618c95ecf99.nq.gz
│   ├── 44f7d63e0d472fa2f8ef889e63ac2a80e418faac.nq.gz
│   ├── 4742e87a7e78252c4079fd83e5989032ee97d9f1.nq.gz
│   ├── 47fd8ba0326ff7006d7a9ed3a65b090a60b39612.nq.gz
│   ├── 4a158fef7e0da8fd19525f574f2c4966443866cf.nq.gz
│   ├── 54c9000ec94341dd65c2053251b85b124017b9b5.nq.gz
│   ├── 54cc8303b22089e12053e552d4e6cb852a865b8a.nq.gz
│   ├── 577e87a793a20e413f7321f4f17ec1eba2ea1962.nq.gz
│   ├── 5bdc232005af9be104a00437ae9bc64417a4c1cc.nq.gz
│   ├── 5cc539b5192cbb8a6dc7cbb8341c248cceb14ec5.nq.gz
│   ├── 6187b15aec001b7080b51a5f944f07591f26cc15.nq.gz
│   ├── 6c3e66786164fefcb8d4178c90a1d230749ba535.nq.gz
│   ├── 700235be57c1b2872455c0be5333f59cf568e252.nq.gz
│   ├── 724370638fc188317bbc7dc868f1a571995fd796.nq.gz
│   ├── 784e8fa48234f4f64b6922a6758f254ee0ca08ec.nq.gz
│   ├── 813f712f726c935f9adf8d2f2dd0d7683791ef11.nq.gz
│   ├── 8606ff0fd23c97d71d43afa0bd587e47c1e90441.nq.gz
│   ├── 87a69145075afd8f8fd8b391c5da1249ec8b2889.nq.gz
│   ├── 87cab8651a9d4cceefc019d00286ae4e6bf31095.nq.gz
│   ├── 8b8b1ca0000bc8fa8d0379926736029f8fabe364.nq.gz
│   ├── 8f8095e46fa4965700afe1f9d065d8a37b101676.nq.gz
│   ├── 95ec665aefa7bebf8e0c1b1b082c80d5c77a3711.nq.gz
│   ├── 9a0f3bce1395ae3819030b822e5d9076c85068ea.nq.gz
│   ├── aa9b2de8a607031491ee17cf5653d1c3ecaa2fac.nq.gz
│   ├── ae8ecbf47672a874c0958d0d113a56162c2bd364.nq.gz
│   ├── b0ce7bb198a3b268bd634d2b26e9b710f3797d37.nq.gz
│   ├── b497ebd54abd420d6ad527e45cf61be55170e944.nq.gz
│   ├── b7960db9dae7d1da77ef3acc46d0a6a9da584267.nq.gz
│   ├── b977d7e52e2446ea01201c5c7209ac3a05f12c9f.nq.gz
│   ├── c4eff0387d5888c638ba09473ba6d2369f7b56f0.nq.gz
│   ├── cbd517ec7182ac185ea2abb36304833bb71d24e9.nq.gz
│   ├── d22860a3166820b8fdad71c6505a40580af14b2f.nq.gz
│   ├── da3c2a2d74bab159ba0f65d7db601768258afcb2.nq.gz
│   ├── e05a3d4a2ab888e32952006d8cd380864368db5f.nq.gz
│   ├── ea8aad7f3e92f1ebe21cb4eb7439ec8afe16060c.nq.gz
│   ├── ef4322357cbc34e0b5eeed34f9fdf553a1de2ee7.nq.gz
│   ├── efcb8cbc2043faa7caf4f92fc7488bd6914c934c.nq.gz
│   └── ffa978abf6d3bb2092250f2b708defc965a595a5.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 4a9fb3779037858f6eabbad0f550ca78e68e932b.nq.gz
└── tag
    └── tag.nq.gz

11 directories, 52 files
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

[jaraco/dropbox-index](https://github.com/jaraco/dropbox-index)

---
*Parsed on 2026-10-20 by [repolex](https://repolex.ai)*
