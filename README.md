# Repolex Knowledge Graph of canonical/litellm-operator

RDF knowledge graph data for [canonical/litellm-operator](https://github.com/canonical/litellm-operator), parsed by [repolex](https://repolex.ai).

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
rlex download canonical/litellm-operator
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 0ec6f5a645d56a0a19bf7284c061db7b0990b238
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 0ec6f5a645d56a0a19bf7284c061db7b0990b238
│           └── chunk-001.nq.gz
├── blob
│   ├── 1715752e7e847adadc46a2ba2d13d1ff370f1f5b.nq.gz
│   ├── 198d9c2993ec27dc848b3d0da48db948dc12cab8.nq.gz
│   ├── 1e597c4b71f1cc0fd86369ec1338e3405e8f98cf.nq.gz
│   ├── 21a5190c500f30dd71d170ccf563891860117f67.nq.gz
│   ├── 36a94f25f87cb2ea740bb154a31d836ad61ad893.nq.gz
│   ├── 43c994c2d3617f947bcb5adf1933e21dabe46bb5.nq.gz
│   ├── 4fe1d7e2aecf85190e8bdd63e3f28ca8a8441673.nq.gz
│   ├── 50b2ce08ded1dd6cd589653f8a86abfbaa304895.nq.gz
│   ├── 5d946d95f2af5dedb9b3f55492e588e4c32d72e5.nq.gz
│   ├── 61c82417a832a6e5b0c694d608be23bd4749c426.nq.gz
│   ├── 72508ce1ef5e298355bc9987895e043a43134c6f.nq.gz
│   ├── 7408c61189f0d454bc4bfb7f8c86d59bf0e47dd7.nq.gz
│   ├── 747783f52d115c52020559bee56c1668a69a61fc.nq.gz
│   ├── 74b23fee37d396fa3d02a45c32711be66bc06bd1.nq.gz
│   ├── 83cd91be441c5df1ad71358283cddb2f0163258e.nq.gz
│   ├── 84761ff0b709c71d5e1d1809a09bfb64574c6def.nq.gz
│   ├── 890523870bce0696b019e2cf9e0f9ebc8d7bddf7.nq.gz
│   ├── 8d2435111f57bf9b39603be895c241845c6eb869.nq.gz
│   ├── 90dc9e6de2ab15d1a302557f358f5aaafb789e24.nq.gz
│   ├── 927ef4aa81e2a75a582177ed1b1c6f119ae9299c.nq.gz
│   ├── 970219d92311bf5f55c93ca40e5a021e64012e48.nq.gz
│   ├── 992a6c415af6349ecf861d2bd3ad1ae01afd5ec2.nq.gz
│   ├── a4670ff46919b276a4c9663b4ca51830108fcfc0.nq.gz
│   ├── a6924456d475a961a0fc4b4c03e1ac0f9e32d9b5.nq.gz
│   ├── a8c1028c718189d35baa9d29e8c879ffa742e7f0.nq.gz
│   ├── aa488b73fb103f718132445c7e2f1159199e89a8.nq.gz
│   ├── ae0d7bdd5b01d06c0a2cce0fdba4eb6bf15e22c7.nq.gz
│   ├── afecf5b3c317646fecf9d4b637b9e8c9f915d20f.nq.gz
│   ├── be1aa88056ce93c3417faf9f703760abe78558e5.nq.gz
│   ├── bf7514053740827ea2ce282a0a66294ea003be88.nq.gz
│   ├── ca584a75aec3c56545e8374596e1e56d8119a4c5.nq.gz
│   ├── cc0bad87dc333b971be6c1851f70ef1585a1c882.nq.gz
│   ├── cca572414abe6db84734fc774a6cebf1d544f731.nq.gz
│   ├── ce9e1a25ee4c47c7a2174813e66a48b120fb5a0e.nq.gz
│   ├── ceb28776215a098e977650ac090c785dcbf53651.nq.gz
│   ├── ced33c63abfd595242091bfdbf71078f400ebf04.nq.gz
│   ├── d2da1c83b593ded9601d1b5cddc31451480137d3.nq.gz
│   ├── d323f2e7973ed4ac6f2cda7917360879075fa87a.nq.gz
│   ├── d46a1f1fb0a027e08fd758be547ac2ab198b445d.nq.gz
│   ├── d8447d38486f33d5caa5c4a16d733f3fd666f27a.nq.gz
│   ├── da902bcde01920d727deeee3bccb8061ce39b4fe.nq.gz
│   ├── dc60f9ff5d72d2594f0e7c5999d1e1e6a0fee1e5.nq.gz
│   ├── e01dc44bce25c78f756e773d31b7445345c3d7c2.nq.gz
│   ├── e64065def61748fb687f6981b535f28abef4cd17.nq.gz
│   └── f69efeaf46cff25f57487ab3f311716a069fb826.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 0ec6f5a645d56a0a19bf7284c061db7b0990b238.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 53 files
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

[canonical/litellm-operator](https://github.com/canonical/litellm-operator)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
