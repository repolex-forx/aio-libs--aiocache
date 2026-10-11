# Repolex Knowledge Graph of aio-libs/aiocache

RDF knowledge graph data for [aio-libs/aiocache](https://github.com/aio-libs/aiocache), parsed by [repolex](https://repolex.ai).

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
rlex download aio-libs/aiocache
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── ae5948b2d99dcaa68fe02fd3086a3351a867c85b
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── ae5948b2d99dcaa68fe02fd3086a3351a867c85b
│           └── chunk-001.nq.gz
├── blob
│   ├── 012dd1009565d628af09030c5e6838e183aab5fe.nq.gz
│   ├── 014e08fe2ee82a1c108199be3abd1dd97e108eb7.nq.gz
│   ├── 02957416519c947b970e7a951d55f6b5b8c6872a.nq.gz
│   ├── 0a53240b5750544ee33c98eee3cc72e7b9c3fd0a.nq.gz
│   ├── 0be60cd72406bb8e68fe0e6f3a44c0f926c64fb6.nq.gz
│   ├── 0c44b7801213bb88881abcfc2b9a5f7bbfc4a3a3.nq.gz
│   ├── 12194f83d5a7e9f804fdddec7205bd25f132cd16.nq.gz
│   ├── 1962c5cf84bd708c5a1c6609534ba0d1b735fd70.nq.gz
│   ├── 1e409b073d3f9c4c3d554c503ded2f87808c18b2.nq.gz
│   ├── 1ed377e59bc6e574d52d7247b69619958c49e8a0.nq.gz
│   ├── 202ee766314e9190d34f6eea9f3da83987331046.nq.gz
│   ├── 219845f24e1be6b1e331976c433c51701c0f3626.nq.gz
│   ├── 23b4a92a5907af2b7caa5a9fedbe052ab79266e0.nq.gz
│   ├── 2eb6b403771f8764963d547f2ce6346558788b54.nq.gz
│   ├── 2fec3a38603964dbdcc91d3f7d909b27be7e7717.nq.gz
│   ├── 323fd4e150b52b3f426493c62f5fefe7623c9347.nq.gz
│   ├── 3322afce68cb87897da720904bc0b83fa34e84e3.nq.gz
│   ├── 38cc5b2be5eb51347fe31deff86c8231d178413d.nq.gz
│   ├── 3b253b5ec62aa12153eaf41f972e556c11050882.nq.gz
│   ├── 3f0ed3051d8264928713d808e89ba616540ea2bd.nq.gz
│   ├── 41d8bc94317ffda65b32a14217df090ea616131f.nq.gz
│   ├── 430d364f4d39d5d21e69ef886d2dcf5f17a0a8f8.nq.gz
│   ├── 47d77c4359f4d6bf7f965eb81ac1efedd095665e.nq.gz
│   ├── 4d8a619bff5d9594f31ffd87001ee98809a6f5c7.nq.gz
│   ├── 4e9912a70e39e641bea3f653ac8e83ed3ac5fa52.nq.gz
│   ├── 504b48a63adb38d6cc865a447ccac121fef06dfb.nq.gz
│   ├── 5196f80055e9b0013dd2dd9f94c71c6ebcf90a90.nq.gz
│   ├── 57dfeb94030aaede47701c49b36dde345d492cd1.nq.gz
│   ├── 614bb0b0b5a2269f19f56c2b41869b12cbf64f47.nq.gz
│   ├── 63ffdf62a109cd85e63ba71559771c6dd181250d.nq.gz
│   ├── 64202ae6deabaf4aa6fba094d48d419bc8b505e6.nq.gz
│   ├── 64ae884d6b74152b1335169a68424d943d9dddba.nq.gz
│   ├── 67fb5aa1a9b90179beae156027f8ef06ffca57cb.nq.gz
│   ├── 68319ed624c10d6118f49ac31927aef1cb43ff3a.nq.gz
│   ├── 6b4ce5fa0ca3895900d070afbd56935606320632.nq.gz
│   ├── 6e8715d00855fa4f78594f1f75490263d1bbaf10.nq.gz
│   ├── 741dc54ecab5fc1e1445c6aa2d47ad9e9e0c62dc.nq.gz
│   ├── 7a7c0b9093f505554bd0b1c15e50c86eacbf50e2.nq.gz
│   ├── 7e53ce70cb1df99db88050657f41c50a6c0714c5.nq.gz
│   ├── 7fe4c68ef9fe71415f6deec21c47808036255080.nq.gz
│   ├── 835bc19832555cc8a0929634f0cd95220fc8c465.nq.gz
│   ├── 8962edf4ba6e5894b928e9fa5fb4e0bda9954d11.nq.gz
│   ├── 8aed65706ebd7332757af6255ef3be040a5b8241.nq.gz
│   ├── 8b097a07992027197806d5509948ddc54684655d.nq.gz
│   ├── 9d1c63c2d00cb995a0504000ca31dacdd0889b7b.nq.gz
│   ├── a06ea5678af291e22d8de9a6768d68a973889456.nq.gz
│   ├── a19ae7f4840921ab45053b1267a37fc9e49ecc4e.nq.gz
│   ├── a7aba688910c1ebfb673e9c0e671e1fc98db531b.nq.gz
│   ├── a9ad7d4294ff57adc3986e7ef6884d74f7e15bc5.nq.gz
│   ├── aa8049e9ff4b432ca327753b16c83d68f12fbb46.nq.gz
│   ├── adfd8fd402f87dd5fd2c872d21c69825d162d0e5.nq.gz
│   ├── af37e2ef532ab230271b67e1c2a5243c4d31d1ff.nq.gz
│   ├── b3b1f46eb9bb90aef4f1f5e3f69a2a4483980f53.nq.gz
│   ├── b68b20f6fe69e419a5ed7045a1f787231a09bf49.nq.gz
│   ├── b71a3f2dd5ac18aaa116c0d781dce40d582a367b.nq.gz
│   ├── b81d6634cf1d1a44077c23da5bd38eb5445ccf02.nq.gz
│   ├── b8572e63a983045d2623b279ec6d88301fdcace5.nq.gz
│   ├── b9fb8a6e0f4a5ce99899eb97d872c6b90f4bb678.nq.gz
│   ├── bd8e4d74044d90273af29b966a0c50ed81003925.nq.gz
│   ├── c0621d85644a6c988767e33d1d8bc6c2bf2b7cfd.nq.gz
│   ├── c140b3bc0caff016aa37a8a1f05a641fd1fe39e8.nq.gz
│   ├── c433007b3b42d3c11f806880002781f43b0c5084.nq.gz
│   ├── c7499335b84d07912b9cfdd43a821492437f2916.nq.gz
│   ├── cbe3d158b319fa8fba0ce965503b562cacb904c8.nq.gz
│   ├── ceba7e6a5acd784625da7384ce7fd449058bfd36.nq.gz
│   ├── cfda509e060670e86aea2ecd75eb46be7c93d696.nq.gz
│   ├── d07c70fe66db1e25e761c30a268d7a503d9f0283.nq.gz
│   ├── d47dd1ffb3472d4b3072e905301f836de232ea80.nq.gz
│   ├── d7017d74bb4061cfac422546fcd94272645b6599.nq.gz
│   ├── dd5f13236ccd856031f6a6e89d319daf43f7f55c.nq.gz
│   ├── e11a7530eb66e06e0f31c57aadcc9a41f08077b8.nq.gz
│   ├── e1b64a65ae432cd4a05f4ba08358d952ce237418.nq.gz
│   ├── e1b880ca1c4bcbca786c5980c48acf06b7ac3e27.nq.gz
│   ├── e58f3d2c6d376c48816add325659cebf5446f42e.nq.gz
│   ├── e5db3b4d0e6414f6dcdb01b63fbea5a6ab2ac889.nq.gz
│   ├── e692cbcd3caf0ec9862b57a9023c902493803c8a.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7127c29b321fb481cbbf4d66aff17c0e7135775.nq.gz
│   ├── ebcfac501fc184685d7c29850010cdae2931c024.nq.gz
│   ├── ebf86564fc03395c2b9f323ebab46e77cd47be19.nq.gz
│   ├── eddef5307c77acde7185f7105afc693a65a0522f.nq.gz
│   ├── eed39c0213a329d19a1cda4ca0141c94c8a14d35.nq.gz
│   ├── ef13b3fe6f81296f6ff3c4d2aa6d5066d00cd1e5.nq.gz
│   ├── ef9be16d7dbb77c71d986cb3549af1e29dc3b5aa.nq.gz
│   ├── efbb431131c263891f62456712904f65cc64c493.nq.gz
│   ├── f4c782548e82151caf398a3cf629066ae32ce09f.nq.gz
│   ├── f66abf475ada60e24011b82001270d9fdc28df6d.nq.gz
│   ├── f787ce2bba0eb969c4fb288b241aef6f17cc6cf2.nq.gz
│   ├── fdcc41085c33213b6996f4f8313aeb284c09a2df.nq.gz
│   └── fe1af2a8eb33203a05d7efadc5191cca4f0f9775.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── ae5948b2d99dcaa68fe02fd3086a3351a867c85b.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 98 files
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

[aio-libs/aiocache](https://github.com/aio-libs/aiocache)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
