# Repolex Knowledge Graph of altair-viz/altair-transform

RDF knowledge graph data for [altair-viz/altair-transform](https://github.com/altair-viz/altair-transform), parsed by [repolex](https://repolex.ai).

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
rlex download altair-viz/altair-transform
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── b65bf854de1e80f931e063d8fb2ec938773826fb
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── b65bf854de1e80f931e063d8fb2ec938773826fb
│           └── chunk-001.nq.gz
├── blob
│   ├── 0005c533b9ba3373ba3d6e9320f61fe8ab955db7.nq.gz
│   ├── 006cd29b6c19d308a01210ba09607c68365e06e7.nq.gz
│   ├── 044799f0b402cbcf7ed4b7f187f9b39ffdcf34f8.nq.gz
│   ├── 192892844ecb14174bcc62491d86a9301f458bba.nq.gz
│   ├── 1a59c45464046dcd340c166e3ed797f82c9e2269.nq.gz
│   ├── 1f9deb3f9e2ed69792e2f72f0f8efa5c49bb88ec.nq.gz
│   ├── 28a1bb866686bf6341c932e5b9fbef980dc6b405.nq.gz
│   ├── 346a9a87de92110e1389c27a4f07f67dff2c8552.nq.gz
│   ├── 3524513bda98176ace1423e8503a673226bffd05.nq.gz
│   ├── 3a35ac6d589e984927676956ef82ef81e6502bec.nq.gz
│   ├── 3b2c1e9d7dda187e917b4c9207e29d37b1daabb6.nq.gz
│   ├── 3b860a744e01d6bbfcd331078d2be988717e2f76.nq.gz
│   ├── 3c7d2a3f3309498fa4c4fcc922c42ce8dae1365e.nq.gz
│   ├── 3d29646d0ba06ee2bc99d404dd1527b2defbb85a.nq.gz
│   ├── 413d7f3e3b5c58a748f25a46f2f65bc034f14862.nq.gz
│   ├── 43ad3977350aace2a87953ca76ff36b25b1d4d7e.nq.gz
│   ├── 48bb71ee8ecd0b9608e0d85a9c821e0c8637cfc3.nq.gz
│   ├── 4c6b3bd91a4cddf5639348bf942aaa71bf179197.nq.gz
│   ├── 52b6ae8e89ee4298b25a7155210c3674b4824b44.nq.gz
│   ├── 5434971b0212823219af14c3fb22634bd1d73a1b.nq.gz
│   ├── 5443c14aa6a2e36e719121f7f97303c2a2814896.nq.gz
│   ├── 56af3e7155c041ce8b0ec873edcde2d3325f9584.nq.gz
│   ├── 58f97ad2b5f2439fde6805425a3e114f0f5c626f.nq.gz
│   ├── 5d9afc27d5d495e06a83a54820bee93410bcd39f.nq.gz
│   ├── 608fc71df50bc3e92b3e0e666962d8ce81c045c0.nq.gz
│   ├── 636610abf6d1132923063cb2ac57e066b9117868.nq.gz
│   ├── 67fed28b0a4f6f751d0a133d25a253fd776ccc6b.nq.gz
│   ├── 6856b6fde055e695b0575c27993dbab2119491da.nq.gz
│   ├── 6e8729da0c2d4b20c784dbb2a8b700e77697491a.nq.gz
│   ├── 725517376768310a71dde8fa402cfb64b61b0b96.nq.gz
│   ├── 731b72c4d4ad237284c717b93e3c7ca962e80b7d.nq.gz
│   ├── 79bab49fc6f4a9526b308046f029a775a627f985.nq.gz
│   ├── 823d69750caeec199a41b2e996812342aca2f053.nq.gz
│   ├── 832f482f0f587ff227e282d79e8540e5d4c5a869.nq.gz
│   ├── 85cb200123b58dcf5ffd63c5bca68080fbc4ae95.nq.gz
│   ├── 8620affcf57a571befd9d53140916a478b6de7e2.nq.gz
│   ├── 88a90b28c6b6eddaa38c277da04c4add064e8b96.nq.gz
│   ├── 9075645e8606c58d0e80785144565742898c16e6.nq.gz
│   ├── 925ad7be10f176b4bbf43e751fd62553798d9dbf.nq.gz
│   ├── 9609d9cb499e64288a1ba7fa2b9ee7ddcbaef3a8.nq.gz
│   ├── 997d816a57f2ac648c15fe5d04e0a10c3adcca14.nq.gz
│   ├── 9a73d941c04d6fe59c77f89c57f232647f828dd1.nq.gz
│   ├── 9bdde2d6579a114ed774dbe148d961ebe100f429.nq.gz
│   ├── a6e3407418527a595ed7be94573b5a79d75fbffc.nq.gz
│   ├── ab9e3b1e1ef9485d22ad557119d08bc3bb1ab4ea.nq.gz
│   ├── ae2ea00d744674b1ab2123a7b7d81b69070f1343.nq.gz
│   ├── b0206cf5ada6a6d9de7ea90e932ff2ae6be3ad7d.nq.gz
│   ├── b15df7a2d18c619e8be8f0e9321403464663c9d0.nq.gz
│   ├── b51dc5a554a293cce84238555a81d251699728ef.nq.gz
│   ├── b92f32e95e6cad0da3306e28c4bbf06b42e3f061.nq.gz
│   ├── bb3189556674eaaeebd3b3e9eff4e1eea2ab56ba.nq.gz
│   ├── bd39cf68de1cbb67c62cf999b4ae3dea9cbcb510.nq.gz
│   ├── c035661a39943a5363316a6d6a9ef9b7bd1b8d51.nq.gz
│   ├── c57741cb0f2105e60375e875b40ef65bb0559824.nq.gz
│   ├── cd94cb517616febfbb3c82065bb9381d9e36891a.nq.gz
│   ├── d2c4210d883210b56bc3e34e884edd1e890ae2a0.nq.gz
│   ├── db5d8aaaad7a3fa42b72251e222fddcb9d144fba.nq.gz
│   ├── ddcd389636e297019b14a19824896d59111d2143.nq.gz
│   ├── de38766919afd175938feb871a2dcb62c08517fe.nq.gz
│   ├── dfa31ac479b80a4935df4cbe7e42c3afaaa9df3b.nq.gz
│   ├── e08ab7ffffea0323a49bfe4820e276fe85f79277.nq.gz
│   ├── e193428ec7d9e7eb98306307bda090b02be2ea75.nq.gz
│   ├── e48c3c81aaa947980e9bc858c124bac1549ed66d.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e9b76693d25e8bcd6cd6d75444ab9e197e4c64fb.nq.gz
│   ├── ef68a8f4194bf3652449b6402ad919ab87382254.nq.gz
│   ├── f3e85bdfb5cddb517d390d8c38f692347c4dced6.nq.gz
│   ├── f70ec72a7dd5c36e1338a62ba92bead14d1e8e76.nq.gz
│   ├── f7c533601da22b2b73b653b47d96b34162353f6f.nq.gz
│   ├── f7e64ffc87493881881d96909c8a21ad99da4760.nq.gz
│   ├── f894054f8c858e9fcee364e1552830f077bc9065.nq.gz
│   ├── fb2b7dc8aad7d31a03055f3c1f0ef024a9d0bf43.nq.gz
│   ├── fc5d0e4adafe8938d75fc7f0504922434b7425c9.nq.gz
│   ├── fc99ff3b1c0350a0d3aa0ffb93adc67b416a1467.nq.gz
│   └── fcba2eded16c8b45aed6d39411576c620d03bc18.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── b65bf854de1e80f931e063d8fb2ec938773826fb.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 83 files
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

[altair-viz/altair-transform](https://github.com/altair-viz/altair-transform)

---
*Parsed on 2026-10-15 by [repolex](https://repolex.ai)*
