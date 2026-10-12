# Repolex Knowledge Graph of python-gitlab/python-gitlab

RDF knowledge graph data for [python-gitlab/python-gitlab](https://github.com/python-gitlab/python-gitlab), parsed by [repolex](https://repolex.ai).

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
rlex download python-gitlab/python-gitlab
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 51eb17e6e67a25157e04b0abc649221bd8ecc7fe
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 51eb17e6e67a25157e04b0abc649221bd8ecc7fe
│           └── chunk-001.nq.gz
└── blob
    ├── 00d96d0beffb6c6bad93c06ea1d0a7da2d8640da.nq.gz
    ├── 01da8593ee04228c4312c0703fabda08afc0969b.nq.gz
    ├── 02799b5803c87d13fa6e2367f5a1e09a553d3ea1.nq.gz
    ├── 02aedb20c8ddd57686e9efa1facd66b235691825.nq.gz
    ├── 04ddb45332c3a3661e7048f91e64c12a07e67af0.nq.gz
    ├── 054379f3c2b8fdbdfed60cbb952f73d63a67874c.nq.gz
    ├── 05721bc77ed904a5344bd01a01af29caf62cfa38.nq.gz
    ├── 0621705cfee585b0de84f6647efa6f169bf41755.nq.gz
    ├── 062231216d3da56b48988d90d930ae9c03cfdba8.nq.gz
    ├── 06400528f5e74709e0cdb384d0c88f231d37b085.nq.gz
    ├── 06c060455e8dcbe07e2390342e5061901f04e256.nq.gz
    ├── 082945d63ca99b07ad4405b971a6a2606510a233.nq.gz
    ├── 084869155246fc173017a68244171e225e05aaa7.nq.gz
    ├── 08ea080aca1b697d4226b5beea2e2bbffc9285c7.nq.gz
    ├── 09ca570bb7f5a393c99e9ea6b94946f67825178c.nq.gz
    ├── 0a84e5737b8799d63c78b2b5ecb03328e5b3742b.nq.gz
    ├── 0ac3184585ee7ca36c3c91dbf82e3f95c8bbafa0.nq.gz
    ├── 0bb861c72c2e1c5ccef6ff0a6e9b6ec017ece34c.nq.gz
    ├── 0c1b6b8ed39d963e140c30b05954c6b25e2b1550.nq.gz
    ├── 0c612f3dec941a356008613a3af7334a142563d2.nq.gz
    ├── 0c6d6825192bf5d06836980431e90ab32d718f78.nq.gz
    ├── 0de65244d46f9cddfb4f73b81fe100ab8a5835f2.nq.gz
    ├── 0ed0a38b179727f682ccaa8c30aa63637cca37a6.nq.gz
    ├── 108f6cedb41fbf9f78cb8eed5309f11c342833dd.nq.gz
    ├── 11330732d921171786af0fc5f195960dfa98e1ba.nq.gz
    ├── 123a4438a91562c0099f216dc759824a471e7288.nq.gz
    ├── 127831781ca1e04797364f13b64a93ca0e7699c4.nq.gz
    ├── 12dbf884880873253f1cd37050691803332bd4ff.nq.gz
    ├── 1340cb4839482717b1002ba99887afcab5c4e5f0.nq.gz
    ├── 14d1e73d488b85234a7718e6de56f8c7bd9ce097.nq.gz
    ├── 15a31403cc9db3e41a7b1cbfbc10966088d27e94.nq.gz
    ├── 16136f259dc193e315747bed40659d17eec0d285.nq.gz
    ├── 1658488ef9149fe33b03c9f194101a7e3b0416a6.nq.gz
    ├── 1675916e1cb93dd60825808cecdae1c8e94f8a7c.nq.gz
    ├── 1679a14e9690363bbc62e8dd1353d6a80d3672da.nq.gz
    ├── 1683a5fe10ed0a2794ab81410a445a1214cecad1.nq.gz
    ├── 168441f28750c6331648454e2cdd61bbd04eb545.nq.gz
    ├── 170e48761463bb074981e4975e60138fbf514399.nq.gz
    ├── 170f4cc417bf9d6ff65e9c54fd4652e346708cfd.nq.gz
    ├── 17562d5be7a650bb0d0019bcebf8c9324f9fa661.nq.gz
    ├── 189881207c25361e1ae3ac9a50f6df42f0e1d740.nq.gz
    ├── 19e8a1946cccb7618826c45ae371ab7f3acb7e50.nq.gz
    ├── 1b64003d063e44da83fec4337c421fff1413e359.nq.gz
    ├── 1b7b7ce482d9ea7c44dd527392889bb114f4d840.nq.gz
    ├── 1c2a3ab0a44b67236b0ffd110ac136498914d6de.nq.gz
    ├── 1c4aa07c5cd0bce1aced9b32e1ce15287a5acab8.nq.gz
    ├── 1c741b4bf7447e1b13c9897834ce18ef63ddd4ba.nq.gz
    ├── 1d0a0ed53814b16ae9364f9ef6dc9ec53c862809.nq.gz
    ├── 1d11e265f63a28620eb8d3196c116d23df9a6d72.nq.gz
    ├── 1ee0051c929053754164d83bd2f404b9faf37a28.nq.gz
    ├── 21d023b347602ed22050a18596325dbe1fecffb2.nq.gz
    ├── 233a5f0974d1a735b19323054fa18d65387b8518.nq.gz
    ├── 23705400953a7a671c2c42dd1439aee2f62c689d.nq.gz
    ├── 248bb9566edbba876ba37c279e36a6dc7aa42109.nq.gz
    ├── 24cee7c6901351dbc3b278361e1f6ad230717da9.nq.gz
    ├── 24f955b9fd5e71859c42713acfd48ad074a2c070.nq.gz
    ├── 25000800f87c3f4d4ef77477460d7d271b3d77a4.nq.gz
    ├── 251cdcfb62002af516c0ded3611c33ec6b5bffbd.nq.gz
    ├── 2644102ab6a7b18feb4ba31cf5a3e6393f56cb6f.nq.gz
    ├── 26bc440b52b15072c89c484e5077bd0ea19cf3c1.nq.gz
    ├── 26c694e5b56997b753f6e001c9a077fa4be03f32.nq.gz
    ├── 27cf4894515e668e7f0f1dd37545b3e86f003f2e.nq.gz
    ├── 2a457a0249b7050aa9d48dbc176965ecc04409eb.nq.gz
    ├── 2ba5265979b1a3866cb271614dc6d8cf00976b91.nq.gz
    ├── 2dd36f80df93bd76f382fa316737fdd5604ab480.nq.gz
    ├── 2ed1c58042a4d651c5dc7a4a6e5c3c569bf0b984.nq.gz
    ├── 2f4f93f25c9dc0dc697c3de551ef0b44d97d2ecc.nq.gz
    ├── 2fdc42dbdf288233e824948b494711f87e4032bd.nq.gz
    ├── 301fea6a2b6b433af7c8c7089851ff943b15f8cc.nq.gz
    ├── 31059a2779422f3538a05458a62e6421789673ae.nq.gz
    ├── 3118f99e3a9ec5b15e0318bea854bcd9ffb1c942.nq.gz
    ├── 32056e3bd84fd7f44eab4ac26e7dabcd1238a39a.nq.gz
    ├── 32b45ad9bfc85c90db894704676d62efe58bd4b2.nq.gz
    ├── 32e11abb998575c0f1d2725b2797fe106661129c.nq.gz
    ├── 338ed70b796500f6f69e698837bef740309d3a6d.nq.gz
    ├── 3394633cfe21e12507db29c02197c0029128b729.nq.gz
    ├── 33b059c042ee70e0634fe97de445727de28ff57b.nq.gz
    ├── 35e12d838d0111dc54ea6759ff8c2c975cbd776d.nq.gz
    ├── 3605cfb4872c36b66b506e90aa427ac4e33eed50.nq.gz
    ├── 363146395fafe172515eb4a2ed75e1dfd2d098c0.nq.gz
    ├── 3633ec142171ac560aede73438389bf6e58abc9b.nq.gz
    ├── 369f8f9f4dcef6776bf6e1bc3f493d654bed67fe.nq.gz
    ├── 37c9d2f55e9ed857c494664ca4da86f2328ef80a.nq.gz
    ├── 382820b764bcebf6972a90f9d96d94841b8f99dd.nq.gz
    ├── 38836f20f5c264bc2dda381d6082c4b95eee693c.nq.gz
    ├── 394eb8614255ab1bc6da35f9f3437a5caf55577e.nq.gz
    ├── 3978b8aba7705c19dac3a8b7e524d39483e61ffb.nq.gz
    ├── 3a1338bb3d15c4b3c224d1753fae5651a105fb97.nq.gz
    ├── 3a27becb1f70cdb35ec06fe16083dad9225b985c.nq.gz
    ├── 3aaf3d0f80d1ad2be730f49316b06348584b032b.nq.gz
    ├── 3bcf931a276154e96ecba31816b64ea454061aa3.nq.gz
    ├── 3c5c7bd334554f3abc6cba4f4f3c50615ebf9eeb.nq.gz
    ├── 3d2082b9136daf5492fb07c0cae5456bcfa589a2.nq.gz
    ├── 3d61d67e5c4033bed40f15d98b1637933b3af2df.nq.gz
    ├── 3e9db414abe16ff98f3f8186b03cd300a55b7401.nq.gz
    ├── 3f5e763bf778c35e60a77287ca6505593e1af9a0.nq.gz
    ├── 3fa671bc2dd4877ccf800c13d632553408c323ea.nq.gz
    ├── 405fbb21b7a05c0f821c5f6b3b22976e095ffd2f.nq.gz
    ├── 41a888d7d0856d69a79c1e969248c98719092456.nq.gz
    ├── 41b60b6485f56db16723ba7ee5e7df3e71dc344c.nq.gz
    ├── 4450ed708e52c5a8b92a132be58228b3db3b32f6.nq.gz
    ├── 460297df7ca6c9b67b6444946a441a2dc93e0fb7.nq.gz
    ├── 465fcb35874e36adfc4169df63253ab6f58a0d8f.nq.gz
    ├── 4694ac221ceadc8d9aa3bfb1d6f5bfbcd0164549.nq.gz
    ├── 46be3e26da96ccd0299422fe9ac6d58c3d56e8ee.nq.gz
    ├── 4758d4da26476e3be7fecfc7d2c7e2b1fb04adde.nq.gz
    ├── 49a2802782926a2f71e30a37adcda3342f543011.nq.gz
    ├── 4a3033f9bdc931703e43d2497ca74a4bfb8c5aa4.nq.gz
    ├── 4a85fdc41f6e7c42a09cc9e43e968daac0ac682b.nq.gz
    ├── 4b1a9693f9b272c21946ab4b37e3e9e55bdeb9ab.nq.gz
    ├── 4bcc4b2e9242b9a501cd0c05047d808b06196896.nq.gz
    ├── 4be927af74a9683c3637a4c092c02a3686f5e178.nq.gz
    ├── 4ccd55926028c05d1634645f4cb85929740c3e55.nq.gz
    ├── 4cf4bdfb05f16d8ec4681d805355dbde2f356774.nq.gz
    ├── 4d0686a4c8c774945f259edc256f185c9b99a1bd.nq.gz
    ├── 4da710499edd9091bc74697eedc79b7bc189d6ad.nq.gz
    ├── 4e9dc39c5c29b4ac73796c6ae6e29b7bcdf5536b.nq.gz
    ├── 4eb1932ed9d0c5b7f38d3914e566ddf8fb4a43e3.nq.gz
    ├── 4ebd03f5b97b12953c662751343a24b2bdad1a50.nq.gz
    ├── 4f131c2a857c66b64331b51daae352c07da44aa4.nq.gz
    ├── 4f9d561bbbeb847c7fe162f072cc6c6514c50d25.nq.gz
    ├── 4fd3255a2ad87c992c72e0629b64462b80735dba.nq.gz
    ├── 5031e4bd58bb3d23924032bfbf5850eb1d035ef2.nq.gz
    ├── 50861715a892a1bd898d4d99be37aafbd7257f20.nq.gz
    ├── 50c6badd60aaba4e1c6c5f137a0a8b5780f97d93.nq.gz
    ├── 511e6c366761e6ded0eef5fed2157902206bff4f.nq.gz
    ├── 5144a17bc2239d818050b3d1a182fd9e542720db.nq.gz
    ├── 5325b2bc5a07479a46599be330be5ea4eff752ea.nq.gz
    ├── 539f16995e254896355fc09547802f514c1bb87d.nq.gz
    ├── 54402e278d3ed1a80471dc7a217c67d00275706d.nq.gz
    ├── 552158fc54edc6286f5982d77cb484e796c87d5f.nq.gz
    ├── 559970f261fc8839f5a0fa99385464b3d21e56f5.nq.gz
    ├── 561dbe4b00ee2b6cca18297f993031a2277ee342.nq.gz
    ├── 58c90c6463bb0a3b1199cddfedcd9239c3aeca72.nq.gz
    ├── 5a594d85c050f35db4675099d7bf2cc619c8ada4.nq.gz
    ├── 5a5eff7d45fd0060db0f2503f73cb028f6a7ebfe.nq.gz
    ├── 5b60e7aa51c2f8c97cbee5a57f7db5d16e950908.nq.gz
    ├── 5b88a0682230a17085631b791c2d74220b550351.nq.gz
    ├── 5d2c551087b86ad28a699a9cbbf27b160ad780c7.nq.gz
    ├── 5d477b09f5d9f1495aabece07cb448095681070a.nq.gz
    ├── 5db517f21631eb2cf3d6def066094ca8fc61123f.nq.gz
    ├── 5e7c01076cf2fe4c5d01ccb76796fba188305667.nq.gz
    ├── 5ebfa296b3c312f752e92f5eb65a635c537eb8c4.nq.gz
    ├── 5f907b54f00683f4f7a560be5f84cad3738ef61c.nq.gz
    ├── 5fe97de703ca306f003262242ad5798fc12db087.nq.gz
    ├── 600c05ee0fefab50fc5552ab225a226e9b1c4381.nq.gz
    ├── 607a636480d49cf2d22f86f54316426bf51c800b.nq.gz
    ├── 6088e4d55065a5b705b6e1eba0dc52406c0de2c6.nq.gz
    ├── 611413d73e7ab6ddfc77bed3d60bc19d9dc424bb.nq.gz
    ├── 61de0199fd63ec25aea28ea99385e526458848f4.nq.gz
    ├── 6272cecc1091a1fd75cad784de1444790ce5661f.nq.gz
    ├── 62d6c4b12afb80d0ac5402d7785b19d92ad38138.nq.gz
    ├── 64feb278402a897a5ff3f0960534ea5a18903d53.nq.gz
    ├── 65a9d60004c4666e059f0907ebb6424fd412af77.nq.gz
    ├── 6673db575aded07aaa0f2ab07606c68e98b78341.nq.gz
    ├── 66efc0fecd1554e6e4681fcb149692591f388bf2.nq.gz
    ├── 6865b6992550462da5ca67d98741188053b4e279.nq.gz
    ├── 68b8d4b2d49c92db8fdffe64578ea0a5f2c33cb2.nq.gz
    ├── 69a403eac845f452c5ff7402b976717b0cc9313b.nq.gz
    ├── 6a03a7d1a928857a1361b678d2751c3bdf123811.nq.gz
    ├── 6a2d660ed141e34f309f69ae893515bb186c6108.nq.gz
    ├── 6b1458a137bd0e1f7b56ca024b8ce628b066c73e.nq.gz
    ├── 6b3b463c111842a6311561e58fa7be29ecbc358a.nq.gz
    ├── 6b5350803d23d0b01993eec9314961a4c87c3776.nq.gz
    ├── 6d98e04d868f9eb1d470cfc8a6a3ab3a8ad5473f.nq.gz
    ├── 6edc24f839ca6fafe7443c6df08e0e8f328e9135.nq.gz
    ├── 6ef09395069a8324db347ef0e522beda150868c5.nq.gz
    ├── 6ff84eefcc4ea799bc670f269a481e3ae0a49a41.nq.gz
    ├── 6ffcf300fc22bf70609f61c761f5be0ce41e0b3e.nq.gz
    ├── 70358c1102042928f2304865ddb0e4617c06d61f.nq.gz
    ├── 717108d44e4dad47307332880fabacb008db0c0f.nq.gz
    ├── 735b80f1e707291cdb658a17196cc3f46578bbbb.nq.gz
    ├── 73c5c66445edee55d6af77582f04b8ea96864e47.nq.gz
    ├── 754abdf45ba1f6491528743c16b68a18c0a54401.nq.gz
    ├── 76281f1e29332dcd9a92063b13ae0053f39e3fb8.nq.gz
    ├── 774f4cd2506225e8bb2e489dd60e6091d1e797c5.nq.gz
    ├── 77a83b6a8d9e77285ae9fab847310dd051eb125e.nq.gz
    ├── 77b5108fe06d1541b4aae78a74d8e512bf33b0db.nq.gz
    ├── 7824ef31b913c48216a306222b8399a4b5bd73f0.nq.gz
    ├── 7875f1c9a7069865c5a2bb50427b9b4c70dab752.nq.gz
    ├── 78ec837851cd889722fa6c7b96b393fe5b073260.nq.gz
    ├── 797c5e79487f1f5c14d6a999131e2242d81446ad.nq.gz
    ├── 79ee2657d98834e559f287b5acd0e02d65074b81.nq.gz
    ├── 7a02859dbcb95d08cd8e839f6429b53ad1b10cc3.nq.gz
    ├── 7a17678172809de406dfb2a3e8a88b67bcd43dce.nq.gz
    ├── 7aa42152c9901910d394a3d3c5670957998289ad.nq.gz
    ├── 7acba56a3db0c7602a6f8f0a94a24a51d702d6ff.nq.gz
    ├── 7c29850d2b1f82db4101ad625185e392186aef3c.nq.gz
    ├── 7c8eeb5e686509dabb7f452090798f6e4663c938.nq.gz
    ├── 7cf413bc2bf814efd1ba4285fb82a4076e1334f9.nq.gz
    ├── 7d1370fd304bf7bdfb180a5d2af1d03e963b49a0.nq.gz
    ├── 7d1510c8d909860c7b2a57fbccc576865d839c4f.nq.gz
    ├── 7df506b094f8b476ee570424e4e891ca3db49b2d.nq.gz
    ├── 7dfd988272fa81b6360e715a7f9e315a9a701315.nq.gz
    ├── 7e43aaa8e2c93810ec391e0ca26d9346b4f4b7a3.nq.gz
    ├── 7e6e362545b536936fd2c01b6257aeb9ced8b8e1.nq.gz
    ├── 7fa042fabcea8963bc9059afa2f01a4f711992d0.nq.gz
    └── 80c00803a5605cf798941129068afcda1949337c.nq.gz

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

[python-gitlab/python-gitlab](https://github.com/python-gitlab/python-gitlab)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*
