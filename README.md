# Repolex Knowledge Graph of glue-viz/glue-astronomy

RDF knowledge graph data for [glue-viz/glue-astronomy](https://github.com/glue-viz/glue-astronomy), parsed by [repolex](https://repolex.ai).

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
rlex download glue-viz/glue-astronomy
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 680dfeeea5775c78e7794b22e59bc2bed4792188
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 680dfeeea5775c78e7794b22e59bc2bed4792188
│           └── chunk-001.nq.gz
├── blob
│   ├── 050b01fa96b7aee781b11d182aeb3f657e6a4e80.nq.gz
│   ├── 068491b29d6265411fb0929e79d6914917273ee7.nq.gz
│   ├── 0d9f084797a8546b75974f5799e73ce2101b1c88.nq.gz
│   ├── 1084e9d2d475bf5912e54f7dfb7bf3b723fbbf0a.nq.gz
│   ├── 11d2ef7820de1a5f34befe49477953ad94d22934.nq.gz
│   ├── 1afed5300581abe8bc552329e4b6b780e1bfbb19.nq.gz
│   ├── 28412be68b05ccf616054ff2ec29a477266475cb.nq.gz
│   ├── 28a2489c3657d0cc9f3df0f3e370ad6c125b8771.nq.gz
│   ├── 2d588989e9bb650b78271179c50886b377c0dcd7.nq.gz
│   ├── 3db4d46fbe4ccb8c4b1f321a470f5a65196dc9f0.nq.gz
│   ├── 3eebfe8c7b5e62b09b4fd9394bd6809a4b158f3c.nq.gz
│   ├── 3fadb19095e0072ee355f9e0ae45d0327960a633.nq.gz
│   ├── 4734c72443b08b53fe99fca25324dbeeeb55f1b2.nq.gz
│   ├── 4a72b28eb7e9a423e933a77bccc55a119d55be55.nq.gz
│   ├── 5993a81cd8f0fdfbabff9033540ecbd23aed6719.nq.gz
│   ├── 5dc10aa8fff8d452bf39f39c69c28ce0a4292362.nq.gz
│   ├── 5e4e1c474cad1c9884ac200894551a9840653107.nq.gz
│   ├── 5fa9a744c737b79aa09db7b6519da50b4012e5ae.nq.gz
│   ├── 606dad51a4b535f39dbcf08927f2339c604762cc.nq.gz
│   ├── 63524b9dcafdde185894e84b42d9af306f602e70.nq.gz
│   ├── 63c2fdc251782e33f7362c21bb5f4e223467deea.nq.gz
│   ├── 67c8b446ff49541d0adb350617a7a28a1a37c435.nq.gz
│   ├── 689f28b26eccf8964d08d3bdd54335212fddf489.nq.gz
│   ├── 6e45695caed92742bf2da13e52f4193b8cd43a90.nq.gz
│   ├── 72deb6c808f513c8bff408da6750da0a08998394.nq.gz
│   ├── 74ab2162a9221b9a32e944812eccd23d71f52bad.nq.gz
│   ├── 761afc91e6e14b83d4e868b0507d935cd88e1b3a.nq.gz
│   ├── 77738a8419a9ad30eafc0bb2e4bc43a48dca46b5.nq.gz
│   ├── 79fa2e0c1880335f0bc7453f8bdec815caf9431d.nq.gz
│   ├── 7d85caf0c8488120ebc2e822913fe57cef032153.nq.gz
│   ├── 7da14cf81de011460e06ce61711cbea32a613f1c.nq.gz
│   ├── 8993130a55a0329b2af5335c82daefa4bfce660d.nq.gz
│   ├── 8b4b18ffc210e7c4c9c1f8c089e648ed595c2ae1.nq.gz
│   ├── 8b58d69ea5142c6fecdfb49de6ce519eec0e65b7.nq.gz
│   ├── 8c17cb54d15ef980a62a81773243d40eb16d591b.nq.gz
│   ├── 8c6af13e12ca2f745a4d70f1052b5af86b319977.nq.gz
│   ├── 8d83ce8a7c5da9310425b04aa80ce6261ec458e5.nq.gz
│   ├── 90341344855638fcf0b527d62e16fe76a644c91f.nq.gz
│   ├── 94eca2b3a71a37f2f1884f28374d645894501cb3.nq.gz
│   ├── 9871ba59eee7c6f748f596e6e96be2359e5345b3.nq.gz
│   ├── a054723bbf3c460579306874181f0903bf1047e6.nq.gz
│   ├── a0c62c8581a87e82c7e53ee5421f679ca1ea5495.nq.gz
│   ├── a182c786a4ec4ce5b59f90fde8fe4017b68d26bd.nq.gz
│   ├── aa4f20df81ff871683dce4abd77b4690f71a7202.nq.gz
│   ├── af86a4472fcdb8786c854b522120a9d1bc1b8e8c.nq.gz
│   ├── bb0741a1089c0fae8c5235f7a0e9b5b89a210d18.nq.gz
│   ├── beea8d9b334bb01ba08b73579956377b3a422ed3.nq.gz
│   ├── c11e1366e3f1301de852a3d23fc478c0fd26ad27.nq.gz
│   ├── c40b0fe73bef6a66302d2be06c6550334c29a828.nq.gz
│   ├── c60efddbbc35f2bbbc661d72ae7c25d4313f9018.nq.gz
│   ├── c67b00c6ceb274ef7312f84b8d82f76d837fceb7.nq.gz
│   ├── cbab78e3adee425a6d1a46f3abc76833f6e5eea8.nq.gz
│   ├── d5c0fd371188039e1a0176ec340809f6f337ea19.nq.gz
│   ├── d767ca70281d19a8b66d1b6b439221ba2dea1f9b.nq.gz
│   ├── d7cd9f495502ef8c9f0e634e2d33b1d6c6d96105.nq.gz
│   ├── df54eeef1b1c34c5d4028a98e803417eb8c3353d.nq.gz
│   ├── dfeff77eccfb4ae04a4bdd678863d684bbe84249.nq.gz
│   ├── e2f30cc7429177026d39a0704a99e9094aa6b155.nq.gz
│   ├── e64201e636f4315d15d1d824c6983f7de6ac124a.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e91acb5aa62522da257dd617ea291ad333132325.nq.gz
│   └── f73f673dd19948299e57be06fcb93db8b20458ea.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 680dfeeea5775c78e7794b22e59bc2bed4792188.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 70 files
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

[glue-viz/glue-astronomy](https://github.com/glue-viz/glue-astronomy)

---
*Parsed on 2026-10-16 by [repolex](https://repolex.ai)*
