# Repolex Knowledge Graph of allenai/Olmo-core

RDF knowledge graph data for [allenai/Olmo-core](https://github.com/allenai/Olmo-core), parsed by [repolex](https://repolex.ai).

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
rlex download allenai/Olmo-core
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── ccf4ef4b5f6552e92f933589e9e6377d16fafb40
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── ccf4ef4b5f6552e92f933589e9e6377d16fafb40
│           └── chunk-001.nq.gz
└── blob
    ├── 0022daaf9756cff517a69003b7aee8de7b8fff32.nq.gz
    ├── 00dec1352dc172c0e8c7334b287a06335bb92bc6.nq.gz
    ├── 014cf1c59b546d039170fc025c8448a1a79961eb.nq.gz
    ├── 026f29f4a830c97d9b794b9ead830ca8e2fc7926.nq.gz
    ├── 02fafe4af3698f492ce6377bbee420dceaef89ff.nq.gz
    ├── 04688dac4795c8109bc4bc2806a6e98ae51e0c36.nq.gz
    ├── 0487ceb8df12e479d6da58c6e66a88e5abe87b3a.nq.gz
    ├── 0570fbeab4af908928ef673afe0ec4effccd343c.nq.gz
    ├── 0593406a3f5f4fcf757221936151bbc02f56d832.nq.gz
    ├── 066afa4093ff0d96e090e368671f36493f555196.nq.gz
    ├── 078a3d902cad849a5c1bac9b889c0b88ff286998.nq.gz
    ├── 0848c9f4b1a97ed9d7e9d59b11b3dee3c686803f.nq.gz
    ├── 0857f12f670a4f0382f539387907291ef30ed86b.nq.gz
    ├── 0a4347710212ec3b7426e55b038f760b81bef5d8.nq.gz
    ├── 0b16a1c3677c7bf94cb9cf9ec8513d8fb7e17e0e.nq.gz
    ├── 0be2b0f3f83b2d7e29af0ac3ebdd66262becdc30.nq.gz
    ├── 0c1b430df40dd83f3a636ce02295623110faed89.nq.gz
    ├── 0c30c6a0233ad1ec57ab71ab2d76243dc3db5c59.nq.gz
    ├── 0d091b2d9bfc7d2b4b6b599c73f336b19eac0c76.nq.gz
    ├── 0d5e66a487664168be13120ceeed54c135ff661c.nq.gz
    ├── 0d6f06d7a77cbce483947c132a9ef9540fb696a1.nq.gz
    ├── 0dbafd818cfcbf3de5acdcaadfdd5a37d380ebf1.nq.gz
    ├── 0ef01f16d7fd58c07e4a5e5c9e19e31f152e2f01.nq.gz
    ├── 0efa2f42d2f196796d674c71a97e8d72c3c212e8.nq.gz
    ├── 0f2770cdd9a99ad74634e9001de6ef8bcea1786a.nq.gz
    ├── 0f84bd2519a8646d4991971593b88624d580e46a.nq.gz
    ├── 0ffa82d7f74f218372b6b0e4d947c47590212afa.nq.gz
    ├── 1043f16ef585e9b3459cda7b095cd706ef167b5f.nq.gz
    ├── 1055498ad97dc946e85c2339194d3b530d41e74f.nq.gz
    ├── 1081756daa7b5998a7ca8c03e36372ed061eabf4.nq.gz
    ├── 116875cb7effba48715128e9ef1564f785ddb3df.nq.gz
    ├── 117768b3dec7ddadd7b39528a39e19d946209196.nq.gz
    ├── 12d98bef5735316994120e9bb448cb4ede42ec5f.nq.gz
    ├── 131091a50989c116c9c2cb4c46bdbc05c15ad86f.nq.gz
    ├── 13289d5ef00446b473963000407fb112f68f3cd3.nq.gz
    ├── 13cf385a2954026197e7e86128b2b287c9733c37.nq.gz
    ├── 13d77fe1988d895364d667a113fd0cde3414d0cb.nq.gz
    ├── 14038b234859a9ea894c2ddd688236c30802657e.nq.gz
    ├── 150c2cfd900dcdcc7441367210dc398c36e9ddc5.nq.gz
    ├── 15add6c290c79c43987b9c374330662c21c62e3b.nq.gz
    ├── 1618d7a320a4327be8158e86ee51b35ac8a08293.nq.gz
    ├── 16ce265d461d4d1e7ca2b06283278e7863b18f05.nq.gz
    ├── 16f6c9b601a854edb95dafd3822a6e0380c33580.nq.gz
    ├── 1708c74abd5df1a662e4ed1c51fc56b672ec1cd5.nq.gz
    ├── 173f7c4b9d4bda6c15d52ee2ba32624078b3b6ab.nq.gz
    ├── 179f6d9e5dce57b310a2c083007693833b58f027.nq.gz
    ├── 17df5c3ef9a654a4f0295ca5e56500904444dc55.nq.gz
    ├── 1928d7afa38f4892336b35f1b9586a58341231bf.nq.gz
    ├── 1938e45128d9f2bdad020bce16fa9fe9e22e7b37.nq.gz
    ├── 19f00c2fede74991991212dd4e6c59186ec5765c.nq.gz
    ├── 1a3333fe1907ca19bf10f880d46609f0e56d4e1d.nq.gz
    ├── 1a6765efd2f5c6bd21d38a1052197b22f812b25d.nq.gz
    ├── 1a80666834b734de6b9e9de08c633af23395e07f.nq.gz
    ├── 1a8fc148fd438b8548a33c07e2c7ad802a9a387b.nq.gz
    ├── 1ac712195c65cd7a9d70911fad8921d1c3d0eb4f.nq.gz
    ├── 1ae14d9203fe28cc8eaa0db7bb105a76073fa90d.nq.gz
    ├── 1d09dbab3309156c02eeccf8ba73c25032a3bf1e.nq.gz
    ├── 1dfc41427bea145cb0f4b8f78b85964e1f280feb.nq.gz
    ├── 1e1e5efc1d1276b7a574a159d60068bee00b4900.nq.gz
    ├── 1ece7ada9942741718b6a91d7ee825d27240fca3.nq.gz
    ├── 1ed209e659b6ec9acb34d2519d00198b8547f202.nq.gz
    ├── 1ed9fcca9fdea2b8f328e0511497088281624f37.nq.gz
    ├── 1ef82238d2f753dec3ee74e3e440da417d306333.nq.gz
    ├── 1f4c8bb762ae31915f9b6813d6a98c1af3414dde.nq.gz
    ├── 1fe9efbbcfce8407517177aafec65475863339da.nq.gz
    ├── 202496afbe74b39686df6e714cca4751f5baec6f.nq.gz
    ├── 216633f5eb1a778d7a09b545fb12c33b914b40bc.nq.gz
    ├── 23227fa199352056c26aaaf9982c6a88cd3773a9.nq.gz
    ├── 2333d7c135539ea0e4e6a79ce02b702d7d8f547e.nq.gz
    ├── 2391fe8147a1d4d71e0cfd3769343c1e22d85a1a.nq.gz
    ├── 248970a2fdc09a714e555192afb77724fddd823b.nq.gz
    ├── 24f1c37d33176653f3f73c387cfc0616443d31c5.nq.gz
    ├── 2513019fef6f152a20bdf337ad41a6131323faee.nq.gz
    ├── 265f8103db155741a9d916834d147da96c127821.nq.gz
    ├── 26f3cbe2bc468cb4f23178091120f8f650ea76c4.nq.gz
    ├── 2728166e7e572959f88f1977614c851515a958ce.nq.gz
    ├── 276c9bfbb717adba40cd344ec02bfad2d243b101.nq.gz
    ├── 2997e60c90d913076b7b00f639e9aeeeecd468eb.nq.gz
    ├── 2999e8a51555f4c593d150007c11c530e850888f.nq.gz
    ├── 29d9c818b208f004c7079586589d76614ab610f6.nq.gz
    ├── 2a50be63871da6968669f665d349368a3ec6f208.nq.gz
    ├── 2a5e3f371672304923b325cc28d9881ccd8b8af5.nq.gz
    ├── 2c5b613ae7a3e60c4d1d74ebcea082ad058d586b.nq.gz
    ├── 2c926ee29ddd4868dc447244ff8c0a28899da51e.nq.gz
    ├── 2c96101f1b064cadb1ef52d77e89fad00261f65d.nq.gz
    ├── 2cd070f3b16fb395b6d76fcd54f2c24a5f881559.nq.gz
    ├── 2cf809e258aaffcd1de73b837bcff2cc74c9ae34.nq.gz
    ├── 2d78d2461f3f8b9fd9a97db8b91467798db71bb3.nq.gz
    ├── 2dc01c244ff55c982f0891236e7ea8abf9e68660.nq.gz
    ├── 2eaee2be0d42622a0ab4ed25ffe7fc29c6d00506.nq.gz
    ├── 2f0d33bfe18cd93d7e824e907ffbd518cf255d09.nq.gz
    ├── 2f27786dbf9ec649340bd08bd492d5c85d2c2a43.nq.gz
    ├── 2ff6aea8edc5b645918103642f36077a90f9b9db.nq.gz
    ├── 301aacdc5d04317154b84747be08c9ea13bb1b71.nq.gz
    ├── 302511156568e4ea4d47b30903cd65cbae9daed6.nq.gz
    ├── 3058d2f39614b3d95f35b76951552c36aa7591b7.nq.gz
    ├── 3224400c59982c2aed451ae3883af4206705059d.nq.gz
    ├── 331f2c2bd596cfc170482488d9137ba19b5f4b49.nq.gz
    ├── 33fcce71353c8bd3ea80290eb9a3646e4ebcc9a4.nq.gz
    ├── 346de32f1a5aaf4a85a5943359fadec9a490e91a.nq.gz
    ├── 34878ed8c577b78b174b4ee0a5ab626423881644.nq.gz
    ├── 353eda039be255148a033631e72eb982c5443ff5.nq.gz
    ├── 35f467d94f9a1e15ca167034ac4926562f7a532e.nq.gz
    ├── 37615c4edbe2189b5d6e32e33cfe16a803e42a70.nq.gz
    ├── 378eac25d311703f3f2cd456d8036da525cd0366.nq.gz
    ├── 37c7c718e6b0bcc7a7ceea252cbde71303dea981.nq.gz
    ├── 38975b4bbe62bdcf9641af69f59dc0cf473c994c.nq.gz
    ├── 38edee99d83181dcb9b7dbaea6ce1fb20fea639c.nq.gz
    ├── 39a3ca64542c51c18c088ab9857c06034a10a5b0.nq.gz
    ├── 3a0737f4b383210a1de1669da1d2a42e2cba2aef.nq.gz
    ├── 3a399eccfd7f9969bae6a215d1b696c4d91d4dad.nq.gz
    ├── 3a47238191200bf172ef775f7515a47127c96aee.nq.gz
    ├── 3a51c1c17d35c6f71d7592eadcc38977f1c8b13c.nq.gz
    ├── 3adf03e552bcea23812c1eedf8b7ed86b5fcf663.nq.gz
    ├── 3af7d9d1accbb79d363f24a70a5d2aca81e05db6.nq.gz
    ├── 3bada0c632eadb932a544195868c741b2363101f.nq.gz
    ├── 3c72fb5bcb0e28fd8538fe1660890c751e9ab87e.nq.gz
    ├── 3cb0ee0e3c78395404217abf65974e785b1d48e9.nq.gz
    ├── 3e6bd4067cd1e5aab64dbc9a2f4f2a927ab9d77a.nq.gz
    ├── 3f3db8afb4518322e5f105677a878b1931c9136f.nq.gz
    ├── 3f44eba88568f9e615ec8cc43afe3cd536c37650.nq.gz
    ├── 3f5fea230aab0a28b3c287183d1cbc55afe7f440.nq.gz
    ├── 3fe4f22d843d14a268e018c9212d102962011f53.nq.gz
    ├── 405c84d572299388c0ebef4d016a82b933c8e73d.nq.gz
    ├── 419509fc0a26fa757899f5de6d54cee0ea215e54.nq.gz
    ├── 422966043c0af92a0392c2514c3a2bcf1031c641.nq.gz
    ├── 42813e9eac2281580abd6b76caae630a0adcf51c.nq.gz
    ├── 42816c551ef256bdf65ba10f2b75f826344143f0.nq.gz
    ├── 42dfe2d837dea28881b9ea77342e24cd1fcc0ab7.nq.gz
    ├── 43916bddaf60eead5cc6d6861198240afef7cf6d.nq.gz
    ├── 4585d6cab2a47ad6fddbb43738b6620a58c04a10.nq.gz
    ├── 472ac8ded1d3c3ba0b13b114cab327d375aa78a0.nq.gz
    ├── 476a26f2ed74529cffb92c52a7b6da4272dff891.nq.gz
    ├── 4793263a13708f1a55b753f630ec93c109900bb7.nq.gz
    ├── 4841c3e75394bcddb406ffe200f041088efd236b.nq.gz
    ├── 487a9b66dfd2d5310c3c683ae76332b2919150a4.nq.gz
    ├── 48a89455d54947710ca6e1943904d362c036d2e3.nq.gz
    ├── 4962ed00f6745bf653222b305a39066759ff7907.nq.gz
    ├── 496e71ec44aed8144f514fbf510bf08a66512e1c.nq.gz
    ├── 496e8cdf6c757464ae15e38d7e6baeb6dbb40f7d.nq.gz
    ├── 49719885072941e76ad33a4e21caffdc54490326.nq.gz
    ├── 4ab71b30172eee47ea9696a14df7e8398ae75f53.nq.gz
    ├── 4c4928220f405bd8071a27292b08242393c9ad08.nq.gz
    ├── 4c4b58e62300cfd8ea0d6be3fcfcbbedfea8f05e.nq.gz
    ├── 4c8b3e1e79423d35dad629072b42e7e81c9341a6.nq.gz
    ├── 4c8e6c82f6e53b616474b0345b54e46d9f078e3f.nq.gz
    ├── 4cca05767922c206dffcde8007c00a57f299f255.nq.gz
    ├── 4d3a0821e059a679f14c7e763c7a4b198d54dd24.nq.gz
    ├── 4d7831e8433d20325cafb9ac3b88862a75ed1fe0.nq.gz
    ├── 4d889de010fb0a20f519d9e9420170a15fe1b2a2.nq.gz
    ├── 4db4b7daaaa954edd05aacaff7d8b4a93fc90c6c.nq.gz
    ├── 4de4956a6da5050a904c0551c58dc585ef5cb33b.nq.gz
    ├── 4e373c0539268b5bfb82f25d768f4ad4ab1579b8.nq.gz
    ├── 4ec668ab2f7cd959eb4e597b0ad8005b828150c8.nq.gz
    ├── 4f4f9590996f7dd7922aa1e5f77aae308f392e9f.nq.gz
    ├── 4f86a08ab43e12fd62a21d04740533c02ef065a9.nq.gz
    ├── 4f87d6d9e5b100c557a84ba0c0181de009183611.nq.gz
    ├── 4f97998ec901d50b2612a55cdd648a808909e3af.nq.gz
    ├── 503461c67b1c2709879996cebf1d06bcd4bdfb7b.nq.gz
    ├── 50676df2123fc622fc3b16c4aa79e86971d1111c.nq.gz
    ├── 50747070ab224949001423f3f1ddafe47befaf81.nq.gz
    ├── 508b1be1e50b4d13d0bfd2e4eb6745341b2606b2.nq.gz
    ├── 50a6e19c8d7c79e0205bc484010846c99342db81.nq.gz
    ├── 5141d075eef8175e668b8000c4fdee2539aa5f5a.nq.gz
    ├── 5226dd1b125cd8353a06c99f3514c710964973e6.nq.gz
    ├── 52da6b04c1877bde387aaa89d6ff411fe3170782.nq.gz
    ├── 53d914ce04f4bae805abcd7fe8fadf76845ec3ae.nq.gz
    ├── 53f3e7c17555c05cd70e2fd6bfef9b162c48e44c.nq.gz
    ├── 543af334d48ded21cf7ea3ecc5154903e2e8275d.nq.gz
    ├── 5445b6d2a61812d0dc0bca85c81ed456a74a8fb4.nq.gz
    ├── 54ddf042580b3095cd014e45efaa175f20ce6324.nq.gz
    ├── 56277192c3b88187cac34862ae22a8338065bd0c.nq.gz
    ├── 566738c32e06e9eec206bb2974c8612dbbf65b76.nq.gz
    ├── 56c7fb250f988b8aa8407ae99dd6fc35eae7070f.nq.gz
    ├── 56fef287ce03d84f9cd1eb5e746414d8c9da4519.nq.gz
    ├── 5700a0aa5dd2fa537cc6b5cf15d2ca45a22c9dc3.nq.gz
    ├── 581c075c6472eaa12f82e992528f0164782c7c76.nq.gz
    ├── 587fb21cdb86a839bd1a420266ce21124da64ad8.nq.gz
    ├── 58d495f94dd23ab1e4c9d12d94d461fe0a5f8a01.nq.gz
    ├── 58d7a1e61fb786ff63152efc167b6afb04f170fb.nq.gz
    ├── 597e3e8458954fd1f5e877a58bbae73c75be1055.nq.gz
    ├── 59801ca87be9c13299409d8d13646db9907e7627.nq.gz
    ├── 59d76d78e4750cf023c8d44073bae3e0a6348604.nq.gz
    ├── 5aeaa08c75ea3211403b6a30989959050153e275.nq.gz
    ├── 5af6617fe4ed329901de9a54e8d4c239fbd0f551.nq.gz
    ├── 5af9f10e85461fd0419109894e6df1d5537d7d2a.nq.gz
    ├── 5b5a39744aef7beb578203b9b5a1322f4e009204.nq.gz
    ├── 5bdeee234a6f9bb9dcc4609b8c6aaffc40416f06.nq.gz
    ├── 5bec2b1e93fc9824d3c4a6c8d3f40707dd6dcfd8.nq.gz
    ├── 5bf381f081ce772d89265873cae5242d307c62d0.nq.gz
    ├── 5d55016923a19797633d7aa158d53db499090bda.nq.gz
    ├── 5dfa345dacbf7ffc967122a19c4bc7a5afb76214.nq.gz
    ├── 5e1a21c535f136e13aa38b2982dc8612285de762.nq.gz
    ├── 5ef7f40eae4a1e5a062981f298034a3ebc05c361.nq.gz
    ├── 5f49e0f9dff14488e1aff5e98040a0109508952c.nq.gz
    ├── 61e0cca7df568a5b6528b30f4eed23c8a2d3cca8.nq.gz
    ├── 625fb118dd573a7014beeaadf95b58b8b486b33c.nq.gz
    └── 631ec12d50eccecdef2c17f25b1c6230beb92f28.nq.gz

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

[allenai/Olmo-core](https://github.com/allenai/Olmo-core)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
