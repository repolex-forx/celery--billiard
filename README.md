# Repolex Knowledge Graph of celery/billiard

RDF knowledge graph data for [celery/billiard](https://github.com/celery/billiard), parsed by [repolex](https://repolex.ai).

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
rlex download celery/billiard
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 40a82b1533e3e170cc24a5aec91c2c56a8e2c415
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 40a82b1533e3e170cc24a5aec91c2c56a8e2c415
│           └── chunk-001.nq.gz
├── blob
│   ├── 003bfa0079449464515acdb5d06664696fc538aa.nq.gz
│   ├── 00a53cda860fabd1435d07f15b68d1f559c8f1b1.nq.gz
│   ├── 040553a88a96041bda48aec42ac673f89b0b9716.nq.gz
│   ├── 0762d3f2cbcbab0c398f894ae6b68609103dac1f.nq.gz
│   ├── 0b6589bfcafad1c28c5527b1fd1948cd0cc623df.nq.gz
│   ├── 0c7f02ddc83d433e9ff4f9cf99fb18ec38c2602c.nq.gz
│   ├── 0d11c113e0d54ad4b278af9cacd5c57861c9c528.nq.gz
│   ├── 11e2e7ec8e01a11b6e23d6083822032f09bfbe20.nq.gz
│   ├── 13241661aa845ba67a08894487b1d894ea619afe.nq.gz
│   ├── 13489b0b0648d9052510013e289b9024d2f6e0ba.nq.gz
│   ├── 1677ffc96ce4cef64cc7c0abe1e1fad8a8647d29.nq.gz
│   ├── 16be77edcef42d23aa7c0be62dbdf37071a0262c.nq.gz
│   ├── 1858696aa0abbde64f635ef51a069405bf6616e8.nq.gz
│   ├── 19088886061a6739109dc016e0e7da5eb1a7b575.nq.gz
│   ├── 1ba3e90da80a9ec4905b15f008853294ad1b97d2.nq.gz
│   ├── 1bea48807d99ad616c1e48b3fc42a4a4b6260e95.nq.gz
│   ├── 1dcba64674a46636fccf4c75ca2b157e950d97b2.nq.gz
│   ├── 23254923e02d62a4cb1dc5e93c4da1cd2adba2ac.nq.gz
│   ├── 237d6649ad55e8babb0d7c6d1f25249642b44453.nq.gz
│   ├── 243f5e39d4bfef6e0336e0a5c250818298a0e9cc.nq.gz
│   ├── 2f43ad8d95712675debe8ac7712974bb1ed81b56.nq.gz
│   ├── 321d1e496603908ee71400914952ac4503df206e.nq.gz
│   ├── 415a8d539f5acc7beaccde643938f05352b58067.nq.gz
│   ├── 41cbef6791f2cca953d8797815c94981da1699f6.nq.gz
│   ├── 42775c473866cfc0ce3ac29c0781a01c7b8bfb6f.nq.gz
│   ├── 427c002366646c8e98891bf4db84b9cbff103f97.nq.gz
│   ├── 43f56cf511b6cede0fae69d2e4c531e73f2cf1a6.nq.gz
│   ├── 46d3e038a26ff33ff4440f359a11d268a7cda28e.nq.gz
│   ├── 4bca118488d235102d9270464b4fe33b95abd6f2.nq.gz
│   ├── 51eb5c07bfece4d6adc5e9ec9dbf985f6a6da97f.nq.gz
│   ├── 5305d333597ed2c6f15d8af201800efb62213115.nq.gz
│   ├── 562f8fe7eafc6e058b58ab455355e10c84ee1e4b.nq.gz
│   ├── 5772a7555bb3d50925adfe53b8cb9bbf1ee6774c.nq.gz
│   ├── 5f940e9c31b02649e099ade94c60b8b8a5025027.nq.gz
│   ├── 63063ce163acfbd4b23f1261699299a42783533e.nq.gz
│   ├── 63306e36ad90806d36da58572ed711e12c231a7e.nq.gz
│   ├── 6a35f65b757effb20db85718311cd3362ae4daba.nq.gz
│   ├── 6a496c6544d06ee28e6995c241511b3ca2542306.nq.gz
│   ├── 702a6887268ce0372fa85189c1abbc7a508d458a.nq.gz
│   ├── 716990eb3df9ce0106501a2316a2dad365996a0b.nq.gz
│   ├── 72b54e33caf2db9a81c5bcdf40a1af4f0960499f.nq.gz
│   ├── 74d2f33d2592b938ddc94c09f6d4b96d756b31d5.nq.gz
│   ├── 77cb881bcb6caf0fffd4720d1cb1755fa5beb97f.nq.gz
│   ├── 7d4026b98e88e8df3b9b0ab7af32942dc56c74f3.nq.gz
│   ├── 7eb351bd85976eec55691e3664ee5e59a4f74cd4.nq.gz
│   ├── 837baecb6455da2566b1101dd64e2f2f3c9dc037.nq.gz
│   ├── 8ba0df4aabee1eeb69f0edd7b40322e329ace687.nq.gz
│   ├── 8c5a27ac9dcda033bdf073b03ab03a7a20aae8e3.nq.gz
│   ├── 91545c38df00f33f36e3c3bc4f7a73dd82d9200d.nq.gz
│   ├── 937ed8b3be8b18672241affc1bd14b5988550033.nq.gz
│   ├── 95d8ebe37d96dbec6bc8f268c6cf0aaa63ae6550.nq.gz
│   ├── 96d14c54434e4757c3ce1940bfb79cd0afdbb609.nq.gz
│   ├── 9e261406bbeacfbe87d26b2c9e19e6bb6819f0b3.nq.gz
│   ├── 9e6a9c916039da7dd2c91767e341e7ed016d36b6.nq.gz
│   ├── 9e89cbc607ff31af1f509da71f4b05504d9cd818.nq.gz
│   ├── a1b62dc486eb502036e0a6c06fa51ff34923d1db.nq.gz
│   ├── a7cd1218432e81ee52f3446d39550b03a7bc5524.nq.gz
│   ├── aaed3c334444a4c1d0267c536190138630cf392a.nq.gz
│   ├── ad9a4101ddf252ab1e8f62b38304ba5dc3188057.nq.gz
│   ├── b748fb0c077dff9fc0968c73fe1dc9f63d19a4f7.nq.gz
│   ├── b9920edbfef66e04dd3516cc8f9e7a68b6b767e3.nq.gz
│   ├── bb80494d0f5c786224a34eb09ed4ce93d46353ec.nq.gz
│   ├── bbb00081248efff426b79ed2fdd3e10f4ef28016.nq.gz
│   ├── be006de9a1ae3b9628e796c74277cd6d61e0a34a.nq.gz
│   ├── c075d86bd6993d24441ed2b2999cb6f03b8fcff5.nq.gz
│   ├── c348385c64fa2e08045942a6920d01ee27447815.nq.gz
│   ├── c69bdaf4976863cea8649787a83dc558551d29f4.nq.gz
│   ├── c75c448bbd0f8d9076d528dd2b203fa21d35b19e.nq.gz
│   ├── c864064a84f67a7e593c7dd5e40a74848a7b0771.nq.gz
│   ├── caf14f8e8a3d87fa02241537377c84298ebbe0de.nq.gz
│   ├── cdfd365d99914934008bc8eaa4f1bd97fec7e59d.nq.gz
│   ├── d209c501185841fe9fda1a6fc792d0ed9e94e358.nq.gz
│   ├── d7a70ca20879d2fb4ae84cf7905b9ce1d4d18835.nq.gz
│   ├── dd6bf337218ce968c05b7ff72fed64d315194439.nq.gz
│   ├── dfff2540419dbb5fb255590910ddbc5457823d46.nq.gz
│   ├── e64a156ec907f3a0dfe24b3ac5d3fd1153d91928.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6ce5f777383e74955213f47114efaed449507f7.nq.gz
│   ├── e74d821786751994266048e636efed4a770193cb.nq.gz
│   ├── e780561e59ed96612182b12c26cd11bb2bd4d337.nq.gz
│   ├── ecfd9eef4d2be9e527c728a9b6ca8d4bdfe3f428.nq.gz
│   ├── ed88d78b48748b385776f9006c8e9952f23e76e6.nq.gz
│   ├── fbef8935a459e3d462660c699ecd8e3619aecdaa.nq.gz
│   ├── fc2f235a05012d3ba149f1f6cbea3fb4db70628b.nq.gz
│   ├── fd0ba197e4f9bb562673f89effb532584cd3ca3a.nq.gz
│   └── fe2de94ff2a5640f4a509b0b1feb5b6e6b91c2d5.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 40a82b1533e3e170cc24a5aec91c2c56a8e2c415.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 94 files
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

[celery/billiard](https://github.com/celery/billiard)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
