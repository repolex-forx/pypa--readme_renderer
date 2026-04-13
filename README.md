# Repolex Knowledge Graph of pypa/readme_renderer

RDF knowledge graph data for [pypa/readme_renderer](https://github.com/pypa/readme_renderer), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download pypa/readme_renderer
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 1d0497c37a6033d791c74e800590dcd0d34f6e08
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 1d0497c37a6033d791c74e800590dcd0d34f6e08.nq.gz
│   └── repolex
│       └── 1d0497c37a6033d791c74e800590dcd0d34f6e08
│           └── chunk-001.nq.gz
├── blob
│   ├── 03566a5a2f9c0908b88dc0f8b5d51f0bfbdaf12c.nq.gz
│   ├── 082efe1954747a36552c70443db3393c47dbb8f3.nq.gz
│   ├── 0adf269f2dbe89cf9cc1acd46d8c087ab456f068.nq.gz
│   ├── 0f6d11ebee151a26bbc1153b5f9f46965c12474a.nq.gz
│   ├── 120468f2ab1238c8ff20b989aa4a1872bf1ba92a.nq.gz
│   ├── 13d77a5b3e73edee71702aba781c8836df898b9b.nq.gz
│   ├── 169e6f45b637e6d04bd3f21ba60df4e1e86742d9.nq.gz
│   ├── 18d6e0251e5e1bb77a0dfb1abb281a7fb984fac9.nq.gz
│   ├── 1dc3f38216ca0af1e1f0f998b2c5715bd19fd7cd.nq.gz
│   ├── 1df6d8fb7fa229097cdb11e50fe198a43da294c8.nq.gz
│   ├── 1fa1f5937c2756bb06622448be4f8f811e46b03f.nq.gz
│   ├── 20fa65cba88d5c7196306afda2bc9d970944861d.nq.gz
│   ├── 2725c0ae94843967ecec9140c3d12dfbde78ae52.nq.gz
│   ├── 2b0cba6ea7a553cd92cee324f0f0f2bb40147dd8.nq.gz
│   ├── 2bfbcc6972380f702a3a660f5842f3a5c51c687d.nq.gz
│   ├── 2cf806cebab2435fef91b18facf23c60628e4b5c.nq.gz
│   ├── 39c33942ee0dd66a0b8c0ca5d49df04e8c0d5139.nq.gz
│   ├── 39ebada7d06bd1585caceacf9a808030ffad36f1.nq.gz
│   ├── 40895f934a5cb8e8ba588de5c5d56a23e6a7e219.nq.gz
│   ├── 4441a74d5397d7cc93b74e07657f5be74e56963d.nq.gz
│   ├── 4af260bd9908de4667792e69489f211dea813b65.nq.gz
│   ├── 52425244fd1c8275e553a8f1e4096b2688fff548.nq.gz
│   ├── 52a278a604bed7cffcbd71f430c5d43eedde9872.nq.gz
│   ├── 52ceaa2cdf0bdd84843b2e39edb8dc5e7fc39886.nq.gz
│   ├── 579243f39a614f6f9dd431a4b9fc46b9449751e7.nq.gz
│   ├── 5f5c7a2e8245056d17ba43f336cfec26011c4539.nq.gz
│   ├── 646eb0927a34104798caa19208d034ebd616f9b6.nq.gz
│   ├── 656484aa544a8200cf6a62a500291fd05899cf7d.nq.gz
│   ├── 68cc269b60a85e56f2047e8b62879df6945d9ed0.nq.gz
│   ├── 6b2c8a71b8406a6831f4f368cba3030ecc5ae38d.nq.gz
│   ├── 6d16ed4abbf2337c3c625a1315d5815f7c12300a.nq.gz
│   ├── 6d4ef00e1492f9ba4df7110908ebdeb487a22c6c.nq.gz
│   ├── 6e71a436628d56fdf68e6f46375f2ead5a3f7408.nq.gz
│   ├── 6ea8cf278f051e3f90b5a6badcdc67f1bd51a59e.nq.gz
│   ├── 7166c9c290056b1b9b9790623db256c8e83ac9b0.nq.gz
│   ├── 74a63557ff5ba6da12b396791880f8bc2feca166.nq.gz
│   ├── 7635b6a122c0198ca0866f1d216b57615c4664ef.nq.gz
│   ├── 77bf8ba6a66579ea57ca85efb823d85f5d2127c0.nq.gz
│   ├── 8183238ab1c7f1b7f360cd8536d5f4f75e3fe170.nq.gz
│   ├── 839763502b7daf5ea6e5c9dcb2840e1df59adf47.nq.gz
│   ├── 8581bbe2c1b9302604a153535444bd39bcbbe407.nq.gz
│   ├── 8afcddccc60c53a0b3639b31ee79d2e1c001cc1d.nq.gz
│   ├── 8d529a7c65280c913addf31d418cbc86cd9565e5.nq.gz
│   ├── 905677c44a6a5ecd4346e4f155cc9de5723a459a.nq.gz
│   ├── 91e18a62b67551a4d427e2eaee0d33dcab94e141.nq.gz
│   ├── 962e2f9f605431910d3f0598e46a019611353e9e.nq.gz
│   ├── 99df4bfaf6d2f47bcf9e916c44b2831173de4f87.nq.gz
│   ├── 9a80c684785bea08a2ab076428f2bcb01db243d8.nq.gz
│   ├── 9de1da7ff21475ea4d12057ab16f7d3286139a8b.nq.gz
│   ├── 9f4f1ac08c171566f7fcf9c68ed8bfbfe66374d1.nq.gz
│   ├── 9face4b59fc57d01a4f2d1e6325c825d781b8667.nq.gz
│   ├── a12304478d5fbea4246733de76348758aae6f3cb.nq.gz
│   ├── a1950311de66047bd2d33c73705809a12df4b314.nq.gz
│   ├── a370fab533e4a1640e1d34ba70a070f152e9bf16.nq.gz
│   ├── a6de454ad5000c452b60e3b00d20c57ec0d05948.nq.gz
│   ├── a7642f45f4fc9a42c6e85f6688e9d27453066c56.nq.gz
│   ├── adcf53e15a36aadef36a0381518ec14437173c1d.nq.gz
│   ├── ae630b54b4e9f6c154433cbee19fde0ba48b565d.nq.gz
│   ├── aeb54e922023c9c72eaf25704785f81466f3adba.nq.gz
│   ├── af2c2e8bd6d6708a1bdcf62797eaf39bc3f30486.nq.gz
│   ├── b26caa1d7f5333bdac87d14c2082d9bf8b3dad80.nq.gz
│   ├── b4e6db7143754505262596bf8ecd2757c365b90f.nq.gz
│   ├── b5391e6f65e1843c4d5edcedad9b7654f58a02da.nq.gz
│   ├── b5ab36acb6097f0d9771f5b3eb2528275b2ce261.nq.gz
│   ├── b5cd43439ef768e2922cef30d698d7eec1e8981a.nq.gz
│   ├── bfa35508a0b2d717e007b66a7c267900b91569ca.nq.gz
│   ├── c852435d3665da3b48dd8c427753bda2372b0642.nq.gz
│   ├── cdec16933df5ad9b7f8c0ed58a29532e9d45e83b.nq.gz
│   ├── ce85cf3fc49b2e34d61a6edab9adf70984aa230d.nq.gz
│   ├── d14a60c936b4fae7a607beb9a3b4d3a00b35f6f6.nq.gz
│   ├── d3144423ef6cc55a1ee16873539a962e7db1eb3b.nq.gz
│   ├── d528e4483d01c5c7a8da1d2ae06426eaec599ca0.nq.gz
│   ├── d67c5cf823a0785a315dc2f762c99103cd25ba48.nq.gz
│   ├── dcf61b605f0a78bff1a6555c0ceee0401deb4908.nq.gz
│   ├── dddf5c3143110eed1920f2c7cdccf2d0ece8df89.nq.gz
│   ├── e07a705a594dada1bbf3743da952cc282961e5b8.nq.gz
│   ├── e0f8d3a5283784faa99d3aa1aed382070c32b629.nq.gz
│   ├── e135ee910da6bfb2a92c970642c49c814fa2eb5d.nq.gz
│   ├── e689fd90780d2d72253c2ee0a99453e8970ea717.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e965047ad7c57865823c7d992b1d046ea66edf78.nq.gz
│   ├── ea00b6951cde880185e746af1bd1ca76c56f598d.nq.gz
│   ├── ea3fefa2a5735c4a93e6f6e0f3790c785681ab8d.nq.gz
│   ├── f19ba19a38056b8e82cdf788ce48adc538fc9c24.nq.gz
│   ├── f1fead2f65aec4b553b12085f73f779aee0d6954.nq.gz
│   └── f9674bc9f1a5634be320832b6cdd666b55d48757.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 1d0497c37a6033d791c74e800590dcd0d34f6e08.nq.gz
├── filetree
│   └── 1d0497c37a6033d791c74e800590dcd0d34f6e08.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 96 files
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

## Source repository

[pypa/readme_renderer](https://github.com/pypa/readme_renderer)

---
*Parsed on 2026-04-13 by [repolex](https://repolex.ai)*
