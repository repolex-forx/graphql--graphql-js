# Repolex Knowledge Graph of graphql/graphql-js

RDF knowledge graph data for [graphql/graphql-js](https://github.com/graphql/graphql-js), parsed by [repolex](https://repolex.ai).

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
rlex download graphql/graphql-js
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 56a9830a16226ef8daa6ccb1375624e1c1933df4
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 56a9830a16226ef8daa6ccb1375624e1c1933df4
│           └── chunk-001.nq.gz
└── blob
    ├── 0093a007901ca027a32f8b70e1213644321b7daf.nq.gz
    ├── 00b3e1ee1a4c1e6cbb7d6de5fc9d97e8ef9cbca2.nq.gz
    ├── 00d3bff2dc9cfe740b6d150658f959b9893e3f83.nq.gz
    ├── 0108d6d2f66e4ee774edabba64988eb9961d0faf.nq.gz
    ├── 0139339e74c2c63fa5c885a935d980df212fd89b.nq.gz
    ├── 01914581d1ae3d3f7a4ea920a2b4ded9d7474847.nq.gz
    ├── 01a79e45fbe2972e7811b01e8ebc32c5c4a48b18.nq.gz
    ├── 01e38879b2d694fa5c53bac005c7ea6031ddefcc.nq.gz
    ├── 029bac9d3b230bc86cc542016480892467593703.nq.gz
    ├── 048c73ea2d577032b6873b8d57c76fc002b7a8af.nq.gz
    ├── 04a8fa7c7ffd0518a7fc3f49f7859ea4e5f367f5.nq.gz
    ├── 04c850ac36902f47b09247a98e8d2903492a3b60.nq.gz
    ├── 05ba149b89cb672562ec25bceb513b5d4ea1e0c3.nq.gz
    ├── 06294251d9b0c850856f17e184c572fc9ca1c4a2.nq.gz
    ├── 064c6cbaf937d7045abd1101575ac94dba1ec454.nq.gz
    ├── 07f63bf7a9adef048b42d08f44994009926e64c4.nq.gz
    ├── 08282e0b8525d269541c9c34d854c1f4aecb03cb.nq.gz
    ├── 088b365dda0287f9fa624ccad981884df7d8f05f.nq.gz
    ├── 0897434b229fc269edf4b0eb7d35599b768b372e.nq.gz
    ├── 08c7b7ce60d53c3da8e4f82c0b9407b2ade64549.nq.gz
    ├── 08f4a5124e06ff8c1ec511bb2592cd82c6572bbf.nq.gz
    ├── 090d4bb0af3d7eeb959d87134bd510e104c94ca6.nq.gz
    ├── 0a44467e217763ef8d9ac4977fd645e77e769023.nq.gz
    ├── 0a7254489da871fc38447c409078b472724cfd78.nq.gz
    ├── 0abe6c0e504cf4e33233d5a01aade040b31d9a43.nq.gz
    ├── 0ac7a135cfef175882085dcfff0e6b57263bfd3e.nq.gz
    ├── 0b14fa944fac695d8a0718167bbe601f1b2d166a.nq.gz
    ├── 0bfebd0cb227746960347715a03074f60a7abd20.nq.gz
    ├── 0cd82705e26d7f2d3b0ca75921efdd3d9dcff71f.nq.gz
    ├── 0cf254e80e57c06662aba41eac8cec92a37ba268.nq.gz
    ├── 0d795a3838886fca9c1ade433652359009228454.nq.gz
    ├── 0e626e23252c32d0c15e587b4d1e6bf0fdd40707.nq.gz
    ├── 0ece7a1f9689ec5bcef6220ca6788b2a11ee776f.nq.gz
    ├── 0f2bc506a3e06ebe8c3412a8a65bb54eeb3d2e9e.nq.gz
    ├── 0f7f6206a9f9fa61e16d3a10f956534d624b559f.nq.gz
    ├── 0ffea1a06713e2dbbc12bcff4ac43f6be14a91f3.nq.gz
    ├── 106fe3561f1605149f48056c95e0b47671e2e70f.nq.gz
    ├── 10e8cefe14d188dc288e4ee0f107a359beb76a04.nq.gz
    ├── 118dfdaa1b35d98f39147e3d142c9e564ef86a17.nq.gz
    ├── 12a31a9a8d0cf7c2d9fbb9a5a5d2cbaea9506b7b.nq.gz
    ├── 12a9d529e5fbc5c819f42434388d1a54b6134396.nq.gz
    ├── 12cfe36f2e221a06693e1807bf7cdfa90562091e.nq.gz
    ├── 12e0a01a78d81f48bfc498b998262c248380d038.nq.gz
    ├── 13ccae391a35b89fd8136607aba2b33b3689dd11.nq.gz
    ├── 13f8cca1ac8f1415ce3a0c73f06ad3da46e81741.nq.gz
    ├── 142933250b349857ce2a2b4c16e8eca7299a6c73.nq.gz
    ├── 14b46b25e1627ee1007ba2a637e8ad95dbba84e6.nq.gz
    ├── 14e814c9aeb31a5caa40e71d581f617fbc3e6a5e.nq.gz
    ├── 1558607a7c0c4f32b1efacf4c3db11e5b5bf1fb9.nq.gz
    ├── 15ef532eb5e32d05caf92118415b3c75f0e22c2b.nq.gz
    ├── 1656d6e7c58b86019a3886f4d32dd71ab4297540.nq.gz
    ├── 1762f9bb531ee37f488e267d1674575adfc6eb13.nq.gz
    ├── 177e386d65c459ec9a20d34379bd8a2f212cdc22.nq.gz
    ├── 179c18e61b595ad5ca2418601bb3c279d2108a2d.nq.gz
    ├── 17aa171e05ff0ca93e5d491dd47eaecf242d1f14.nq.gz
    ├── 1905a5e36a37bda014c8307c0620ab41aa4b2f64.nq.gz
    ├── 1919d81f0756f69e6a91e86f253bacedfd3bde75.nq.gz
    ├── 1963e6b3992293dd840019f19965fbe3043a156a.nq.gz
    ├── 197d93968e720ea00def08f12fe4e4161ccd15d2.nq.gz
    ├── 198ff4b4cdc8054665b563e01c05e9a0652bfc6a.nq.gz
    ├── 19a1eae0ed37d58bf1eafbd9c051cba471fd3f03.nq.gz
    ├── 1a03e1ec5683c4d220909df4b4c30b2049dd8325.nq.gz
    ├── 1a37fc0dbc9ea770b311af9da7b80f3042914a4f.nq.gz
    ├── 1afd2d5534d6fabbc0d20dc6a6cbd9a75654d9a3.nq.gz
    ├── 1c03491a3ab3b10470f9db884ebf94d5fdae9207.nq.gz
    ├── 1c65d0d05728265595ab96953c3179b4279bb24c.nq.gz
    ├── 1c7b24e17620458f4fe2c63b49ca4abfa69ddb3c.nq.gz
    ├── 1c85e96eccdae4c8da49f852f9756021397922a5.nq.gz
    ├── 1de88c4778eba65b48a1689509120cf098a6ed4f.nq.gz
    ├── 1e8a67f0f124394488638fe68efa492ba954f8ca.nq.gz
    ├── 20852861659d4609b3ad19febb49a3fc4f38b68e.nq.gz
    ├── 20879f1f573cca7007dd375294c0539d6fcbdb89.nq.gz
    ├── 2135478bee2b911a8a37730b02bbe27a166e824b.nq.gz
    ├── 219478ad42d064b7ceac17024835a61b5455245f.nq.gz
    ├── 2209646b64cd219a11ba79c876321ca4c13e23f9.nq.gz
    ├── 224233fd5a02cb0080141e8b5bf72c5ade3f0e59.nq.gz
    ├── 22a8259ba40deff2e442d240aad599c88b339797.nq.gz
    ├── 2303e6197de9ee776791f18dfd840093a4c4eee0.nq.gz
    ├── 23cc64d4f8330c1678b4d82c7aea290964d42d01.nq.gz
    ├── 24295de37aab44a79625ead66ec2dfa3e2f29b64.nq.gz
    ├── 24e521c24268c9de240ae9daba3623b4b5292efa.nq.gz
    ├── 25084101a78e2cf223eaeef83d6562ed1fd0a63d.nq.gz
    ├── 25751d11361df23d9c03406373d2057c4f0cd7d1.nq.gz
    ├── 25acd006895399986129d8898056740ed1822502.nq.gz
    ├── 27d27f8e339dc68b6f517689f927b749cb757a6f.nq.gz
    ├── 281f07e4ce8e396bcf6949ea153d5a4031c64088.nq.gz
    ├── 28289c11652b128c4268747910035fdc8cf37045.nq.gz
    ├── 28b09a2a940a8f35e727b7b8c43ae9d517ca0f67.nq.gz
    ├── 28de4cd52a628981a5dda7a791adf885bb66ab81.nq.gz
    ├── 28f38a294920b8e4f7822d7a963ff73eb2632f93.nq.gz
    ├── 28f881199321bf52297e9fe665661c2b7edb6387.nq.gz
    ├── 28fb455295646a0c86df2b49f2351a931069453d.nq.gz
    ├── 28feefe11d7d9aca527ecfe402b8ab74dad7a4af.nq.gz
    ├── 2a938dd53428bf179384db72edb9ab44d5e9cd21.nq.gz
    ├── 2acfffa163f29252d39b2426222c4802a75f2679.nq.gz
    ├── 2afd5c3dbdf30e7fb10358c368058c48afb86663.nq.gz
    ├── 2d5f756e10628b49836b325bdbb9ae33e940220c.nq.gz
    ├── 2e7b33ef7f5b02b359946a1cbf909aeb522d6f95.nq.gz
    ├── 2e9ffe3ef6d977335e5ad4e91d08fb2c27fc0dde.nq.gz
    ├── 2fb7a5d113118b5c0d086e20fd25f49efb48d8f3.nq.gz
    ├── 30326177e9528048ab1c0b585e62774bac9d9b91.nq.gz
    ├── 304ade2aa44c4aa1304c0e83131a081fe9e4c190.nq.gz
    ├── 3073f371aef1747f945a47af2b2052fe524e8666.nq.gz
    ├── 30fd9b36de8b1f70f0faf38664752a8bef51128d.nq.gz
    ├── 313b5f64b2604875d8e085ae4d56cdf3ac5c2a7e.nq.gz
    ├── 31c9bba27c7ea0cfcaf4dfd3779e23240df9163c.nq.gz
    ├── 32fbb3a5144eec8fcef44510d07e6fa644297519.nq.gz
    ├── 334d8d1b07d185d341ff83c1e33100ff8c152f7f.nq.gz
    ├── 33dd6ec67606ade911e8a9ddd8775c854917b057.nq.gz
    ├── 341e63d9f325ff668d2385470806548892e95fb3.nq.gz
    ├── 34309a5954818109efaffba46f9a9f95c604a69f.nq.gz
    ├── 34a6d693bc348ebc571cf0ba9b49bd6293ffb1a7.nq.gz
    ├── 34d6e5a03f1eef3824c925b125a70872642d5c13.nq.gz
    ├── 356da136ecaa256909841b7782f124ff4fe6fce2.nq.gz
    ├── 35ded2e923dd6fc82e9788cd09b5cdd9d5c15c72.nq.gz
    ├── 36430f29032f5a1476d2e0398b0193cf317d15fa.nq.gz
    ├── 368b799cf139960ef0e32ff3df3ee12c66094863.nq.gz
    ├── 36ddad4e4051aa811099311ad6b7a01c61f749b6.nq.gz
    ├── 36ddb1f5f8d273cc10ce5ba8877bbd1a2c3dbfa6.nq.gz
    ├── 377365e1cf51508baa51ea6917608bffe5b87d82.nq.gz
    ├── 38173f1cd333320c6ac0935ccb2b45dc67d3563d.nq.gz
    ├── 38e7e81c0e377547bd0d524a43de4e1ce0844d6f.nq.gz
    ├── 39387d6a07dce50dada15a46e05d0e9dad27bcca.nq.gz
    ├── 398ab7fc46b8b276fecc39150ea4ded9cab65c42.nq.gz
    ├── 398b27613748c80d04eaf37e90c7c2a557eefc06.nq.gz
    ├── 3a080ca63838f81632bc42e38db71839f880aa1d.nq.gz
    ├── 3b0c23971d445e3c0981136004b6236d46626220.nq.gz
    ├── 3b21a91258753a47ad7daa64325ccf55e0ff8002.nq.gz
    ├── 3b71f231b0f9e15cce82f344882d49737bad0e0c.nq.gz
    ├── 3b7f0975b95208ba85269f9edad143484ee18e2a.nq.gz
    ├── 3ce89fdfe13949497b8c1a51d0fffbda2a16aebb.nq.gz
    ├── 3d56020b3f6b9aca046969d2b6dfe00321b3d28a.nq.gz
    ├── 3d95f4fcf20d6f396030e0e3c816f714947539f5.nq.gz
    ├── 3df7b52dce1152d905db6030b5199fd8adb11a40.nq.gz
    ├── 404135a0f8357f45531ead82ec0b352bbb449425.nq.gz
    ├── 407ad6390fec9735b87cdb03ed0e13cbb06697da.nq.gz
    ├── 4109fea59228680cd57b96ae39ee80064d512b74.nq.gz
    ├── 41799e14b541039c90a05193bf4e3162eb6672c9.nq.gz
    ├── 41a13b53067e7033a8d746fb7e13972faacb214f.nq.gz
    ├── 41cb88d38740f820803a9da6fdb85576faffcace.nq.gz
    ├── 428ea6b2e3304aa180f50485bec9bad11967b40e.nq.gz
    ├── 429733e6313bcb4ab77e274196892df8b3e6f060.nq.gz
    ├── 42d5e792f2b33f018144419576094230f74c1732.nq.gz
    ├── 4351ba7182fa055dd8804b1a7eb091987e668aef.nq.gz
    ├── 43718ca07f27e80537b61b68ad629b40156cf21c.nq.gz
    ├── 444d84db0d738bebda907289e9ff7ce2f07b414d.nq.gz
    ├── 4450611ec7676883511d6bf9362ac4193929bbb0.nq.gz
    ├── 44e32a85e7b66b885caf0018829e8bc11133da04.nq.gz
    ├── 460bd22d877ed52d56d8aa7e90a5c8514e6d6eda.nq.gz
    ├── 4621c0c7d7cb90138621dee4cd4a8feae8c68ad8.nq.gz
    ├── 46f8e432dd112c45a3f9ea9053acaeaca1ec4fa6.nq.gz
    ├── 47b8bb2d867a3927e5d20523cf07eb964ad7c7ea.nq.gz
    ├── 47e79aa6cb2dcbffa9912e985e14f0d3d394bf5b.nq.gz
    ├── 48b7cdbd0d3eea7e9ca348edf1b11baec24a094a.nq.gz
    ├── 48bb30b9360fc45f15cf2133c0f2e79a85851a98.nq.gz
    ├── 48d2d8e1c4d7fb910bd76b6574192a25c347c7bb.nq.gz
    ├── 4a1ad091c3c9eaa8c8bfeb3f517fa54b19f17431.nq.gz
    ├── 4a43d335389711458400ed8108512afc54049ca9.nq.gz
    ├── 4aa0e0a78ff4ef5a59e2198e82f3095d93bee769.nq.gz
    ├── 4b5d42332b01c9f722a8859a6e04e610738cebbe.nq.gz
    ├── 4b6825e00644613cc9569820686b3be0fb1708ca.nq.gz
    ├── 4c7915287bfd81203c0453cd6e51b4388866dc38.nq.gz
    ├── 4c7a6ead71427c82aa14423317f313f2432861a8.nq.gz
    ├── 4d1874142a831b0060eb2776e72d3afac73247f8.nq.gz
    ├── 4d1c7f291bb225f690ed76ae0e851bd63d721b2a.nq.gz
    ├── 4db47eba9cbd712835f515f7fcecccbd84ba752c.nq.gz
    ├── 4eb6b9ee950d6cb20a593372f3df0d0bf83b1a82.nq.gz
    ├── 5098b1389e7b13d3f2aefc571f6a2e37a18b247b.nq.gz
    ├── 50b3748c6caa1de5ce69ae942514348c1152ee28.nq.gz
    ├── 517521e320a79eb2f354fd0d3e91ff65c20cd7f4.nq.gz
    ├── 5238a0871e1e673ab079e6c3ac507e9f1f60b4bb.nq.gz
    ├── 5254922cbf40028dc226dd9d15d29ea50e5343fe.nq.gz
    ├── 53b9a06f768fc86c7ed0e2a7e16694805adbe4e7.nq.gz
    ├── 53f5322f8b5aa966bb3affdf5059479321782c02.nq.gz
    ├── 551418a540138c2065b73d031db3ed3ceeb4ec82.nq.gz
    ├── 55aec52e1c2f15e8cb2f500c1225e84c27e7edcb.nq.gz
    ├── 55c52f5f7b3f3a9d7a6bf20dcb1814cfb3740021.nq.gz
    ├── 564438b4f79763ce9bac6c200892b419f66fb0f0.nq.gz
    ├── 56a46a88d58ed700198197681286a1cd9391c9c3.nq.gz
    ├── 570d8b21ca77bfb54a84b05a2e3beb345d461366.nq.gz
    ├── 577cf10e115374e03841919ff77af7e8cc959207.nq.gz
    ├── 57865dad1d523de66ca79b02b1d1ce50a33efb35.nq.gz
    ├── 57ea755cc566c032928339e576d244c4df8b6f8f.nq.gz
    ├── 5802e9dc96db9976938586216809ef7d564e645c.nq.gz
    ├── 59a58450b7e32f29b667c5a5d7f0609dfa32b91e.nq.gz
    ├── 59ca1a9758ffaaeda6c86448fd1946558e8120cc.nq.gz
    ├── 5c34cd80682e72eb8b55766133e323189f9652a6.nq.gz
    ├── 5c493b71070f845c48bf11343db58c6d3220bdd2.nq.gz
    ├── 5ca0b715bc6c5db8d13692c5f2a24f0b9dab01b8.nq.gz
    ├── 5ca9a93895ecf26e7c60e569fbc47fee34be2d8b.nq.gz
    ├── 5cc97a4219c1f4c5a7f7bc219af695b87a5d6a57.nq.gz
    ├── 5d5a692bac19ad52914bbd011e044088ec1c1970.nq.gz
    ├── 5d89b206680bd5460f19d836f6f8e5133b2f8096.nq.gz
    ├── 5dfdfb478cce3f79966c1206d021dda2cbe5832d.nq.gz
    ├── 5e43297d62049fd5fbe75b6402d67d5576c9a04c.nq.gz
    ├── 5e45a97097661507f38d34fdd6b2f3c3b808ea57.nq.gz
    ├── 5ec1a6113e7fa1018034c9bc87fc59e0433bc404.nq.gz
    └── 5f079daf2aae8a2f687417882b805bcd63d707af.nq.gz

7 directories, 200 files
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

[graphql/graphql-js](https://github.com/graphql/graphql-js)

---
*Parsed on 2026-11-09 by [repolex](https://repolex.ai)*
