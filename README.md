# Repolex Knowledge Graph of RustCrypto/formats

RDF knowledge graph data for [RustCrypto/formats](https://github.com/RustCrypto/formats), parsed by [repolex](https://repolex.ai).

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
rlex download RustCrypto/formats
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 96186bb54b6da8a94cb8bebd2572b01740464e06
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 96186bb54b6da8a94cb8bebd2572b01740464e06.nq.gz
│   └── repolex
│       └── 96186bb54b6da8a94cb8bebd2572b01740464e06
│           └── chunk-001.nq.gz
└── blob
    ├── 00d12dba38f9b4f192328f72dec0997458782935.nq.gz
    ├── 017a90908229bd7a42b1c4f03f30ac110f6acc38.nq.gz
    ├── 01817b88abdbb93a078ccfc3a91b5b94d1d60288.nq.gz
    ├── 01b4faa95145f6c729896cfcb73898d15bd95f26.nq.gz
    ├── 01bdc0d31b607426fbef73cec36a1add2106212c.nq.gz
    ├── 01ca622948b022fcf10488d737b2d0cd271c0233.nq.gz
    ├── 023ccc52385de20c1570591f3b543eff55c02169.nq.gz
    ├── 0333ef7b9ca89327d5b26d8fa49ab36998a42420.nq.gz
    ├── 0438ca8edf2257fdbbe9ea1dc143a87cbd2451eb.nq.gz
    ├── 048ed0d8c243a6241cf945d99eebb235da50794f.nq.gz
    ├── 05945ddf20d11c69f677eed6e88c8e7259acf0b1.nq.gz
    ├── 06d366a4c5a93af6293f31189e8c2513d3e551c0.nq.gz
    ├── 080dca9066c8ae3e7607074191197725560572d4.nq.gz
    ├── 0836d3ae4a91d560c04e52876a95e71ed6423360.nq.gz
    ├── 087997bc1d5c9d8bb7c5cd621950a7325c60dd5f.nq.gz
    ├── 08993c2459642e8d868cf7ab9fa33772f49d55ff.nq.gz
    ├── 08db364392105cbdc4e9c4bd0cb3ab24dfde5a47.nq.gz
    ├── 0965564c283c08a56b866b156918e57d2a6588c9.nq.gz
    ├── 09b9343c0c0897a6754df46b476984f3ca2af2e9.nq.gz
    ├── 09d45de784a7a871f81e1256cbe4fefc16092e58.nq.gz
    ├── 0aa21ceed8095aa3e1feb7b830791c9d312b9c71.nq.gz
    ├── 0ab32216f6bd795311a5fdcb5d8b36034a3f8b73.nq.gz
    ├── 0aef65d8ee4160806f78e2ec50b75d46ddaca986.nq.gz
    ├── 0af25935ccb770775cfea49f39e009d74ee0d6dd.nq.gz
    ├── 0c0ee10b4b5e6c5606bbf36028e9714787e2292c.nq.gz
    ├── 0c52777c79988a234137144f661ce6165b452c4c.nq.gz
    ├── 0ca80bc482bdb0ac9c5811e07db0e17dac804f2c.nq.gz
    ├── 0ce8c2f363450212816bff8c70b9dd6f746f6ce5.nq.gz
    ├── 0cfccc3990f430ff59de680ca91967100560234d.nq.gz
    ├── 0d8bc8b70daa41b9b1f1c5e3224bf817cd6fbc08.nq.gz
    ├── 0d9fc342496f44544f2fcddcda47c30733e33bed.nq.gz
    ├── 0e598999678bbd7f47b37a01907544932437b8b9.nq.gz
    ├── 0ebe76ae7148090abd9626e3ac01e1d6b9b45767.nq.gz
    ├── 101ddf0225f31d3e2f0140f4dd27a3c7beedf107.nq.gz
    ├── 108eeb5274c996c33fa1e3ebc9079fced4350263.nq.gz
    ├── 10ad99d23b9a032c3c5754f805ba5efafe80f909.nq.gz
    ├── 10ebb94418385882084dde84e67934ca2bc28e37.nq.gz
    ├── 111433343aa00c2e1a5c8bfa3d152bf47545ebff.nq.gz
    ├── 112294d601fe1c3d578c34e1797b1f4e8fe03e6d.nq.gz
    ├── 11ef03ca96575dbab9ad525fabddf5479e1eee1f.nq.gz
    ├── 1263103a6c4b02b1752c5c696df62da8e655983a.nq.gz
    ├── 12e671e660c3051467487ca80db8b594fc869361.nq.gz
    ├── 135bcd7d9e36b219f1c8a50453280dea228baad3.nq.gz
    ├── 1397a91ddb5a9fe4aeca328fec44b0ea6d2a4dc4.nq.gz
    ├── 141ede32031529786fb2104ff44df74a97fdf2e1.nq.gz
    ├── 147da7ccc106cc31e401569c8431cc777867e68b.nq.gz
    ├── 1524ca498033b9c35a8a3aeab437c7934ab1e7f9.nq.gz
    ├── 1573d6e1617edab3bb99d95dea6aa8b34fd2050d.nq.gz
    ├── 15c7cc40f2e3876d11b50d28bf82b2996f0e34c0.nq.gz
    ├── 15cc7bb21e04ce7b52c68ac6242e0296b001e677.nq.gz
    ├── 15f07a98506ab6fb6e5461f3894f059ff74e3710.nq.gz
    ├── 164b215f75f495f479686df6dbff4179fe9a3b74.nq.gz
    ├── 16e97fb569d8607707328cbfd12433c49e5f9c49.nq.gz
    ├── 174f2752a84e92d470d600a5838953048c57f7a7.nq.gz
    ├── 17a9b6180df3eb5f71295432089f429d596e3b80.nq.gz
    ├── 17f546c363f73c63f1edd95dc28f0f3812a04bac.nq.gz
    ├── 1815c4316a824637aa8c242d1a4ca8e834bf481e.nq.gz
    ├── 182672bc888f1baefa5e7a5547e4c6a966813b10.nq.gz
    ├── 1851f8055f017b78f3cb9f527cb1b30c3cc04072.nq.gz
    ├── 189ba85b03a2aebd7286af8cfd970753d6b05583.nq.gz
    ├── 1927099a1fa6ebe203c11cb87249929077c3c3d2.nq.gz
    ├── 1983dfb4b4ee4b6f6f061b2b3c620f15c314c363.nq.gz
    ├── 1997f54937deb9d710ea98f1c15af804f5714663.nq.gz
    ├── 1a45eee7760d240bfa8ac1989088e0349169f264.nq.gz
    ├── 1a86e21671083b1b4aae941e3a6cc99f04b8ff26.nq.gz
    ├── 1ae1f97b04960cc2fe7aa8daff7a3b7e0d5c329a.nq.gz
    ├── 1b06dcef9dfcf7b8c2c7a60327dab4ee1b688abe.nq.gz
    ├── 1b376877f435b1848c818e97e52298f51b8f1beb.nq.gz
    ├── 1b602ee1f2754f327636c7e58cbbf340dd7ca82b.nq.gz
    ├── 1b78809158a474a980966df05a75cea190990638.nq.gz
    ├── 1d75ce95916bf69f601b85c91c2d8a2efed5bdf6.nq.gz
    ├── 1d9812183a728de5ffef3fdbf6bda8ee304decf4.nq.gz
    ├── 1dc38ad2fd6b522395f5254c6e99061e75406034.nq.gz
    ├── 1e8fe75de351405bb40c044fbeff6efa28684f72.nq.gz
    ├── 1ef0f7361755e7a02ad557165da3ad634824bab8.nq.gz
    ├── 1f0562d80e3d21d5cc48375c0cc8b5b062dfd426.nq.gz
    ├── 1f25845be52cbc2fccfd0fdd69c3420cea35b5ad.nq.gz
    ├── 1f754d527bebc8afbf88f822253975193c5df845.nq.gz
    ├── 20458e6e9e0abfd3ac920265d0b6158a523250a2.nq.gz
    ├── 20830b5e0f689cb9fca1e6016907b30e9ea2040c.nq.gz
    ├── 20bfea5bd7a162939e46cb9f87fec72f4b30d864.nq.gz
    ├── 2171547951f11d20574b990b1138484de07a9f7f.nq.gz
    ├── 21ad9d241833f9b4e70110a3561fe6f43eb4dac5.nq.gz
    ├── 224a947e7bea2f804922696fb98414fa79dabbfa.nq.gz
    ├── 232a5acbc268805553dc4ef4bbf56b6129830c6d.nq.gz
    ├── 235fd81ddf00be38ea96dd11e6e096cc5d99f4d0.nq.gz
    ├── 23bb0b693d5af2ba55d06734146bff5103f46222.nq.gz
    ├── 24bdee8f6fc907940d45690ae0cec71de84585dd.nq.gz
    ├── 25458678043e505b8471245ffcce486935828dba.nq.gz
    ├── 2547850dd99c0528ae5a929bf31e91bf11542948.nq.gz
    ├── 25dae08c83f1bab200ab641dafcbb48f58b4da44.nq.gz
    ├── 262c7f671e6576582dc2b959ef41dc33f3985205.nq.gz
    ├── 267f8c2a78af41e680367a8677d32b30c76a5fdc.nq.gz
    ├── 26a635f69664e997113ee40435c12b5ef80c28b1.nq.gz
    ├── 26b93bc9be5a3066b40b0608bb05da79af118b4a.nq.gz
    ├── 26e7df39be02a7728e29d81272e47ea0d2cd225e.nq.gz
    ├── 2726e14a409010f0cb8cf6e4532b747a243d18f0.nq.gz
    ├── 281bb276596b98dc89938e7bc9ca47bfe89c0ee9.nq.gz
    ├── 28d7cba77e06cfb639ffea759935764eff6deeab.nq.gz
    ├── 2973319f212181bd68a3c47f4b08578a3cd7ec70.nq.gz
    ├── 2a1a3ae484c35905b07291de09959d85d4327e9a.nq.gz
    ├── 2a50d431a8bd99a117ee8e60d6b53027a742c548.nq.gz
    ├── 2a78470c9ed9ab938aa42fd3e4f6f326c6bbfbeb.nq.gz
    ├── 2b61bd3d929c014111fca101223fd6d3ef53a758.nq.gz
    ├── 2b8c303a0b239456e3e8b4739db099a5b735caa5.nq.gz
    ├── 2c4b963312083b08623300a02cb5db7e95908c34.nq.gz
    ├── 2cee4076ed15104fa739acec696a83cb57f9e429.nq.gz
    ├── 2d9dbfae5add439ece38466fc7a62cee1c972e95.nq.gz
    ├── 2fdb1988480d85e5e80f68fdba89b683d92d54ea.nq.gz
    ├── 301105cc2b6be47657e7da9281e41f0ba98cbc17.nq.gz
    ├── 304019e3c4c5147d4e752e054c78cbafa77e8985.nq.gz
    ├── 31c9e225abb712069cf0a8525d770af9da45397e.nq.gz
    ├── 3281744cb85ca0b13726ae8bc6940d68e6dded3e.nq.gz
    ├── 328248ab772db4d57226e0301685935853e78d08.nq.gz
    ├── 3294d74345ef9764bf4a57ff1dcc5e8ed0e03c79.nq.gz
    ├── 3358e8a730ac3daf865b6eab869bb9a921ab9ef4.nq.gz
    ├── 337c071e5e6588782f7a4dde1d09400f4b286da3.nq.gz
    ├── 33ceef8e26c54863245ff8ca41a7eb135aec13a0.nq.gz
    ├── 33f84f7f181c2b4597dce1a6d7086e4b6aabbc55.nq.gz
    ├── 342405428ff117f480297c45bb562fdd0f31d7ab.nq.gz
    ├── 3444783601e23541916453ab992b75e036aa9fe2.nq.gz
    ├── 3467e5dd4352fdc795793a1b3965a3168cea7acb.nq.gz
    ├── 34d5699287838755bb43d752c71606bf524fe101.nq.gz
    ├── 34f9c5fe59b23c799c460566c251d881024e20f2.nq.gz
    ├── 35194a5903142ebab299bf623f12124ba80029da.nq.gz
    ├── 369e0b0de306cbf251716c267ffd3a95f713c55f.nq.gz
    ├── 36a05f3b45817a8d9b90f9c0dc2066b91e957407.nq.gz
    ├── 379fbde5981fa29202b87644d246c1c7d86e5a7b.nq.gz
    ├── 37d7c62e6b35eb1a4c42774793b3b890fbdc32b5.nq.gz
    ├── 3867443b258a03c55dc2c75c8f1e1f53657fc082.nq.gz
    ├── 38ef36472a048a2ae0d83ef096b3fc5ddfaa3123.nq.gz
    ├── 3910b33b975960c1742f308ccda4d396e2a1d105.nq.gz
    ├── 395ba19f61f359c6dd8fbcda412510e17a807785.nq.gz
    ├── 3a0314222bea16611e7bdd87675e779a2112baa5.nq.gz
    ├── 3a9d0a98c107f806f19ef20614a3ded461edc693.nq.gz
    ├── 3ad43a95b17081659e67a837a479c87a3495147f.nq.gz
    ├── 3b0f34449f2ec799de7e8c313eb1981ce5effd7c.nq.gz
    ├── 3b924f5fabdb4b9f7f3b5a578aed6d17a3c4469e.nq.gz
    ├── 3bb91c83c10ed0d62998aed30ea693f83901e80e.nq.gz
    ├── 3c3df348a1c5183a3beafca46384eee6090b9519.nq.gz
    ├── 3c89de56dc2fa75f69313d9a73724188eb7b3af0.nq.gz
    ├── 3ca6128dafc83bd018210333be63a690aff40b4b.nq.gz
    ├── 3d11fa89da87c75f308fb3f38ddd0d4d080e996b.nq.gz
    ├── 3d1cc7d9a68999396ba25448274f969580a390a1.nq.gz
    ├── 3d91b5dbe8205290db58450227fea138f881aa89.nq.gz
    ├── 3d949f8872fbcfd57ee12f6c0c279d62c0f6d935.nq.gz
    ├── 3daa452b2fedcb1d569c9b580738d76076b437eb.nq.gz
    ├── 3eb0f2e681013e9d3fdbfc9fef291dd4684d6c75.nq.gz
    ├── 3eb169df02daad0f56eb5fcc8b3f5679f9ce992f.nq.gz
    ├── 3f9688e8068ec472cb086a43c627b4bd1e626aed.nq.gz
    ├── 3fa74d3a78ef740317327c8359dee301baabd4e9.nq.gz
    ├── 3ff44ea04028e6154911ba775fdbe628a43d465d.nq.gz
    ├── 40c7720ca02a9368401313316284bcd62f5b446d.nq.gz
    ├── 40ede69ac75763f9864dc45884fd213cb0a5fcc0.nq.gz
    ├── 412c58eb27811cf12e75b22e30a21f6b6a909a63.nq.gz
    ├── 4148aaaaaffcd235fca03d18d0605a7d28fdd4e4.nq.gz
    ├── 4227dbfcf055a7f34df7ecfee3f6fe2eb0c84cbb.nq.gz
    ├── 42771f5534fbdc3df368a4442935f3c638143dd7.nq.gz
    ├── 42d462340b428c6165b83b9a0086ac99e5852e37.nq.gz
    ├── 432edb85277e0183c413c6fb238e6f795cb2777e.nq.gz
    ├── 434d616e6da5ff98399a7ed36403b9e43e09d431.nq.gz
    ├── 435c50134a2e47aa756c441adbe7e3f278926083.nq.gz
    ├── 43ccf170c746dcaa5102580ac94cd32ed5f78a24.nq.gz
    ├── 4435736513787d922b91e2c8b30aa19492cbdf1c.nq.gz
    ├── 451972a8a0ad688953b1b7e3a8f27f91fdaf46d6.nq.gz
    ├── 454c1f0e480ab4dcc3a042a12584d76b42247752.nq.gz
    ├── 45f4877df6f6bd195f3ec99f04b97ebfae3cee5e.nq.gz
    ├── 4614f1f9deed9b041158ccd058ab581e4de4bc49.nq.gz
    ├── 46e55cd02e09532a8e87927a34b5879126b6b7c4.nq.gz
    ├── 46e5f9248c57c6c4cb5f45a3e7f8abdf9b8d48ef.nq.gz
    ├── 473fcecd2a7b4e4a994daf3526a2c1323f7ef48b.nq.gz
    ├── 4796ce4ff301d5e45e02da3f1d0833ca1420575c.nq.gz
    ├── 48714845f59632ea05157230de32b9663663e798.nq.gz
    ├── 498392df2a92798c55805a8ab245ac6aa015d7b5.nq.gz
    ├── 4987f4d13997595e060d2c4e367727907cee2987.nq.gz
    ├── 49970669a8dad526783ab07649e1afda8eadae78.nq.gz
    ├── 4a085a2eac57924025b4b3770050484ea58ed816.nq.gz
    ├── 4a603bb94e33a754f05b170a6c4d61f915c92452.nq.gz
    ├── 4a932b78f011a1cb0e61c65913af2e55061d85d9.nq.gz
    ├── 4ac8554bfb8c06423c1a4e2cb190f9ce4b99f2cb.nq.gz
    ├── 4c0320fe5543faf6a13e62a086d6019d87132629.nq.gz
    ├── 4d1b8c65b4a72d9239181465f936ee8dadf90334.nq.gz
    ├── 4d2d9db17ba57237eb9e559b66e3b690d1ca6461.nq.gz
    ├── 4d596d2a984a68934f56a6a571fd69703cdc98a4.nq.gz
    ├── 4d5e1890a466423ddef3ed96e56c2ea962e8acdc.nq.gz
    ├── 4d77e6d5b85827a520e238347cec6ec09dac1175.nq.gz
    ├── 4dfffa4e03b3fcaaa5901dcf95e4c7e29ed76582.nq.gz
    ├── 4e0112be4d52140acc75614bcfd3fcb29b459b46.nq.gz
    ├── 4e1551d2921f54391e17dd617e9916198df3de15.nq.gz
    ├── 4e63e870f6b260c481f367b1ac4867088572cfbf.nq.gz
    ├── 4ecbfa74d4b32a91f7cbba2a1757c3f91dfa23f4.nq.gz
    ├── 501f95da67204799a2094b225fbf4484b4301759.nq.gz
    ├── 506a995f26e2c2bdd204752f4917b81a33e4c4cb.nq.gz
    ├── 50c61807c6e115d183eddafd1393249690464cec.nq.gz
    ├── 5170c06e4bfebdf9d5d7f9e2fc36d98c989b3ae4.nq.gz
    ├── 5226062ab25b5d68f5cf2e06d49233392873b59c.nq.gz
    └── 523187391d5cb9b50dee382a6018dc1795a27157.nq.gz

8 directories, 200 files
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

[RustCrypto/formats](https://github.com/RustCrypto/formats)

---
*Parsed on 2026-11-24 by [repolex](https://repolex.ai)*
