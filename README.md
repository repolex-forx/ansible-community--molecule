# Repolex Knowledge Graph of ansible-community/molecule

RDF knowledge graph data for [ansible-community/molecule](https://github.com/ansible-community/molecule), parsed by [repolex](https://repolex.ai).

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
rlex download ansible-community/molecule
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── da31a19eb0c2aa50faa7255a42ee9792bafa4361
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── da31a19eb0c2aa50faa7255a42ee9792bafa4361
│           └── chunk-001.nq.gz
└── blob
    ├── 001c9824d9d5e69f595c67a263cfc02cc08be9aa.nq.gz
    ├── 00213563548817ee368329982ec4be4e23565a84.nq.gz
    ├── 0160f23a8902148841e6ef1d04c5a52877ac1842.nq.gz
    ├── 016c3b00c4c14b338053ee4e0088d80949345b35.nq.gz
    ├── 0253559de55e92d660727ced7fc7577f13575531.nq.gz
    ├── 035f08603253f01f893f06c11ab72a4d061e0b5b.nq.gz
    ├── 039af8ef1b21f821c9efc54b2badec2ce2f969ec.nq.gz
    ├── 03a24d259c62ead45545e973d8037c1c4479fac4.nq.gz
    ├── 04d5485029d70dfa0918bb866aa9b14da2f63713.nq.gz
    ├── 04df1994ce711e969b2d7b8cf831420e0cef69e6.nq.gz
    ├── 0621031dc01d64ff78c922014c48f7e5dd65366d.nq.gz
    ├── 064bf46319715d6466d335b51b9c747db446be56.nq.gz
    ├── 0699d75b7998ee8b5fc3ceed77afba80bf8c58ed.nq.gz
    ├── 06c1339e95be880b776cc52d8f3518284e37d07b.nq.gz
    ├── 07421c47dc6ff9127bc567d26bd59f4e38d8a797.nq.gz
    ├── 07ca9c05b197cb7e970b642b7f78ae86256a9d89.nq.gz
    ├── 07ecc85127ada33f21652fca497522d73fe7501c.nq.gz
    ├── 08a5e9ef6ea028cd1ea64dd1ced4e547a1cc23a8.nq.gz
    ├── 0957fa9bc66d8bb8666cb1ba7efefd2ac57c61e7.nq.gz
    ├── 0967ef424bce6791893e9a57bb952f80fd536e93.nq.gz
    ├── 09b787c17ad940fb29917d39cc0a25f2dc6e8baf.nq.gz
    ├── 0ac6402f65ee2a67677d5507b8c882ca12f2ee23.nq.gz
    ├── 0bfbf977824815e9a6e8985228e1d2d5391e8417.nq.gz
    ├── 0c13ecc7797123fe270643848b44f59674f18549.nq.gz
    ├── 0d1d7bc5fa555e3c2a78eb665ef961abf73de956.nq.gz
    ├── 0d2af1789366794f16cfb3aa298d89c866325ec6.nq.gz
    ├── 0e0933171d3eb977bbc6911eec27b9c0ba289500.nq.gz
    ├── 0e6418d7989bc61ee436b00ad129b0d796c6314f.nq.gz
    ├── 0e68055e7fec1806925b797c02a0b62da1eccda8.nq.gz
    ├── 10362b76bf9e38ff3eec453202496d52662a762b.nq.gz
    ├── 12af62fc69632a1ba08bcdcc924bb9ab9300bfc9.nq.gz
    ├── 135e7a57deac078f3dfb3a544d716a13473b2c5e.nq.gz
    ├── 139dcff0726836da5ce6e27c865d711b59a4a59f.nq.gz
    ├── 1418ce8569e39a05208d3521e63023a2f6981301.nq.gz
    ├── 143cb6acd5213d5e3ac398fad76299ee786194be.nq.gz
    ├── 1448f8d9c6a53afb93ec1c935f223bc062e4e8fb.nq.gz
    ├── 14602b0fa4d6e05cb33521f0ea8cc1204a090447.nq.gz
    ├── 1566f79bd2375f993a8d7ff90a3bf3a0f1de2fe5.nq.gz
    ├── 162e00717b252ddd1770fb6430f40577a6afd7ba.nq.gz
    ├── 168a3722eff9d811c9b79bb368d3a38e1349a415.nq.gz
    ├── 16a2049b93c23de023d476bf90fe28dd59c9c692.nq.gz
    ├── 17638b0dd53e177abc2e4ed8df8482a48c82c454.nq.gz
    ├── 1858a5b1695f4a74cbf143996b69ff4cde61371b.nq.gz
    ├── 18d0e40ede5565c8a65af25dafda048e9eb08da7.nq.gz
    ├── 19b4dfa2856452101908eda7040b37f8ecb311c6.nq.gz
    ├── 1a4228e530cca9e67820eb682950451b08149f42.nq.gz
    ├── 1a73915fce1345a7e0565e822859cf1d9b742a49.nq.gz
    ├── 1ae1f254dbc23843be1807526d6e3ca611e977d6.nq.gz
    ├── 1af6609720e0cc0459beadb820383629383a84cf.nq.gz
    ├── 1b028745fd308411af05d7f867d85a9bf73413f6.nq.gz
    ├── 1b690c795127afd479a7f849c772e5a27b31b812.nq.gz
    ├── 1b75bf6969ec111289c9822abfe2bc9026fef98b.nq.gz
    ├── 1c05013f896d44ea89203a84b5d92c2800fe3689.nq.gz
    ├── 1c78a5ac8973b7f2feafeddf89026940055a22e5.nq.gz
    ├── 1c9456a8e6abb31a850f0e6e8aac5fb07a6ad1be.nq.gz
    ├── 1cec4936a177ddbe7379a6ea2fbd7928823d0769.nq.gz
    ├── 1dc124736bdaaf3ba9bf06d2708993c0dbf5453d.nq.gz
    ├── 1dfc2ab99a9c19d5cf1ac52dece01d4e19392a2c.nq.gz
    ├── 1e22ab2518b1be244b3b04d10417f156163fd858.nq.gz
    ├── 1e2d3421f02910d4b9482a0561f7627b9cbd3080.nq.gz
    ├── 1eeaf9226e0032d1ea449ed05e67ac62c92bf050.nq.gz
    ├── 1f4dc97bddc9939bd326d85f6fc1d5a2867e3620.nq.gz
    ├── 1fb1f7040b85a51476a232cd99ff526634dc3e24.nq.gz
    ├── 2097a9892b03a4d76009c705bbfa121975d5d6dc.nq.gz
    ├── 218f5c57531e89f76754162d91c7893cc8e1523b.nq.gz
    ├── 21b87609ab750bf8a427d116679ac8e4316793dd.nq.gz
    ├── 21f3df39699ccc8fa1d9c8d04421e0079b04f9da.nq.gz
    ├── 22094633cc15ef6fa7f8f7ffdac9a2dd6984c281.nq.gz
    ├── 223eca7dad54bc73feeb0da33ffc3d36ce120b63.nq.gz
    ├── 2268461d566def34be95f830d985daec7d704391.nq.gz
    ├── 24177eba6f47a78f69a66a66c285aa4dd45bbcba.nq.gz
    ├── 24304f5b077b23200974bcbfa9c415ef0550ab18.nq.gz
    ├── 25a97a4d148f4b157e36164bc7f4c995ec4814e9.nq.gz
    ├── 25de3f2f8e426dfc4b4967b154a8d5aa494aa410.nq.gz
    ├── 26f79dcc9939e0a9f9bef206093bf0d797e8026c.nq.gz
    ├── 272608990a8f929f31260791a2581e5e61223e44.nq.gz
    ├── 29233ace418007457c78935cb2dd4848983bc8d2.nq.gz
    ├── 297a0407109df43985a44f4773355302571968bf.nq.gz
    ├── 29dde2b9e4fa5c87076743795aa4ce400c8a354f.nq.gz
    ├── 2a8c38e487866400ac679c2d31838d492921115e.nq.gz
    ├── 2a8e619b2257e3ba6deafa9413f88799014d363e.nq.gz
    ├── 2abdaca563660791592998039959e779d582e1e6.nq.gz
    ├── 2affd344e729ff87ae9b7862ec9d94b484b076df.nq.gz
    ├── 2b682c9a304a8f12752e3fce61fc61f040895c79.nq.gz
    ├── 2bbb44c17b6721bdefe4141315f5e516f27cae22.nq.gz
    ├── 2c251d34eaaa4f9f9f0ed3b889098b2dd6443494.nq.gz
    ├── 2c821e907b3a61665cd40cb145a87e68de7b4242.nq.gz
    ├── 2cbaa192398002a3f8bc6c75c89b1b0b3e8ebc78.nq.gz
    ├── 2d23c7e04cce575e8d63afdd321a20b01e264e83.nq.gz
    ├── 2e150889a4887d548d2742a654b910a7afd6c20a.nq.gz
    ├── 2e95743c0630f9beea3eedea0b845154c92367e4.nq.gz
    ├── 2eb3260cacbfc773c4f13ad65a62635087f3b420.nq.gz
    ├── 2f3973ae1501b601f5a21b92bcad5ef36bd41151.nq.gz
    ├── 30c7b0465312d26892439195dbdb4bb8f55ce9ff.nq.gz
    ├── 31963a0e5e0a6fee9587226bb07c829188092339.nq.gz
    ├── 31b42b1c58524894ad28d68ac113dcafeab5534b.nq.gz
    ├── 335a9a4eaf89a0103f163788adf99d89f6d05665.nq.gz
    ├── 33c5d6fd6fe93f6e1298f89167e1144b41e492c5.nq.gz
    ├── 346935b495e052b626ab1a517ebca001813b2d06.nq.gz
    ├── 34915c6b400d8bab22341ba950207b9e8146511e.nq.gz
    ├── 34d5455c0d06cc8066ac2404befca94e05dba3e6.nq.gz
    ├── 36010319dca21aa61836e4bb75857e48040618cf.nq.gz
    ├── 367323e905beeb629146cf9b511610d71e62108d.nq.gz
    ├── 36776c78a368f3355497ce3c22e2e0d44fb555dc.nq.gz
    ├── 36c0218c01e07f93d3b3653b3a05cb43df38379e.nq.gz
    ├── 37137c3de271b224c5479a3ccb384410a3e2dd4b.nq.gz
    ├── 37237b991101076d22379a7a7f6e53dfe71b0fcc.nq.gz
    ├── 37749f02f23059b9b72bd95971c349c3c5ee7d2e.nq.gz
    ├── 37b438c8e62a476779f7b430ee3648d91b028f95.nq.gz
    ├── 38424b9759843bd2fc57c33025b2951db01a24bc.nq.gz
    ├── 3addeac07930d72bf4f2349273c3158aafe204b0.nq.gz
    ├── 3ae0578fc9dbf3e4b2e9af85f8aeef29b5ec7714.nq.gz
    ├── 3b6d97e75bce7a915bb38051bf07b2e187e12a91.nq.gz
    ├── 3bda50eb1b3e044ed614328f94d8bc58fefdb38d.nq.gz
    ├── 3bed76607d5d5f4627e6c28c209f2717b45b8c1d.nq.gz
    ├── 3c05b1ebcb8dd10e744030b451c918aa2d8ef849.nq.gz
    ├── 3d014c43dbfad398036295bf358a970d45b52543.nq.gz
    ├── 3d18e01a57c103ed16be69ee05c0c8ec99b2a03c.nq.gz
    ├── 3db26c4afa6bcaed47f4bb1b53925945f7c8cb85.nq.gz
    ├── 3e044ed2b22b1f1397d3740b9b4be1c0fd87cacd.nq.gz
    ├── 3f72eb083ff16bcf49c16f25689a0e39e05620ac.nq.gz
    ├── 3fae495725c329162a65ba7674b4cad93b2aa4b7.nq.gz
    ├── 3fba2e7f9d9defa860551ffb5657f9dc0d6a6667.nq.gz
    ├── 3fe7bdc400705d717e6a524878c4640b222fda06.nq.gz
    ├── 4018afcd27a9aa387b1420af0b65a65d7efa92b1.nq.gz
    ├── 4087b59d3e32dc845d043b3739246ce5b221c9a3.nq.gz
    ├── 40ad64cb601923e9423687dc1978fc693c8fa16e.nq.gz
    ├── 40c2c6ec44c1bd800ecf13d1c2eb815c7211b5ab.nq.gz
    ├── 412bd63a79bfb5a0e78f8e8c96835c5cc5382d28.nq.gz
    ├── 41fa72982dbb636f98f01dcd64d1fd91c688fbaa.nq.gz
    ├── 4207f68f5dbb7273ac1adb99fd1aaae66917b512.nq.gz
    ├── 43d4dd43c52170c47741e6fb07d899ccfcd6a835.nq.gz
    ├── 4414638548199045765c9fc047e16f88a930b9c0.nq.gz
    ├── 4444b5e8ec149bc9dea6eaf6414d22b763aa16e8.nq.gz
    ├── 451ae9c78f0b18017a3dfb8ca0c08362f780e370.nq.gz
    ├── 464b2ee82b8a8d2b381c7ce74c7003476a4d20d6.nq.gz
    ├── 4670d3bf729a4273041c4572abe3daa012b4c4d1.nq.gz
    ├── 469b98cdc38104529ce2cc6d1b53d0b30a5283ae.nq.gz
    ├── 46ac529ca5731c8e92b07945da5ea5ca22363db5.nq.gz
    ├── 46d011fdcf87e54bf403e7e33066b4ca05974ddc.nq.gz
    ├── 46de3bec0ceb7f77c219ad75c2e7fe2bb882d627.nq.gz
    ├── 47869a9b6012b5987cb6ac9f751e40a2b9334506.nq.gz
    ├── 48946ba2e1e9676f41e9105da629f160a4d3d377.nq.gz
    ├── 49569677abcf16c89e113df64759927329dc6584.nq.gz
    ├── 4a185ca224d429b2ebfeac7dfc7fa65010bc850d.nq.gz
    ├── 4bf50136215c6dba4325bbaa6a9403fcd0e6bb96.nq.gz
    ├── 4d504ba13d30f618c989b0325b86054bd1ff60f2.nq.gz
    ├── 4fc5175f85e00b09f2ee3839009855d591ea1da9.nq.gz
    ├── 502bff6b0047c7904667523b53057bbcafd7c482.nq.gz
    ├── 503cedc538a7bd1e10e76eb32cb955bef210ce4d.nq.gz
    ├── 50507bdfe2788ecda94c67246555ca918a0ed271.nq.gz
    ├── 50636754bb687bbf6ec218f72f617c68cde9ca83.nq.gz
    ├── 52356d03f2fa4745710d54392549f75b82af5c41.nq.gz
    ├── 52709bb98c2199ca176cba2422bfaea334219534.nq.gz
    ├── 5339b431b09f4c130be66f613864cd4e938fbc7a.nq.gz
    ├── 5460016a358c3425df3aa479ca6c1ccce8e1885f.nq.gz
    ├── 54e9331e04a0d12bfe9fc0bc9a1eacdd3661483e.nq.gz
    ├── 54fe9b1f864662da2486d165ede96de8827ce499.nq.gz
    ├── 5514dbb3be1353ed7f26d5ab5cb9c01555dcd4cc.nq.gz
    ├── 565fc5849cdc3be0e8ec829b0b897d6a15cb4737.nq.gz
    ├── 5669fb9eeedf55994476b150c5fc5b060ba3010c.nq.gz
    ├── 56ccfeb112b82be81c1d27dfae086ce11f8fe5a5.nq.gz
    ├── 58127c66fefc5ec2eedb485d016b437ea50ed2c8.nq.gz
    ├── 58e50bc36a74379444896f0007ce70ff604f10ae.nq.gz
    ├── 590bb0acef52abec32734c4661d6e2b3ab7ba942.nq.gz
    ├── 5a2457e3b9493886d810fd941ccb570ddc4b787f.nq.gz
    ├── 5a5a13dd52fb16fc55e87489c9237ff8b6824ca0.nq.gz
    ├── 5a95de5127c872141cce2188d49dbf46940f1841.nq.gz
    ├── 5be2ece95e127fa3c8d63d01599170df65912ba4.nq.gz
    ├── 5d798c3d37e831463089c2ffd41b0d0c69c9a235.nq.gz
    ├── 5db7509f61e6b5fc9c56109c81cf68296ea6bb94.nq.gz
    ├── 5f2b2e78884233aef7eb2427ab9311f5090488be.nq.gz
    ├── 6072dede9e685b704ff980688d9cd220739e59f6.nq.gz
    ├── 625eabae6c1246b7c13e825cb624cb313ea460b3.nq.gz
    ├── 62f9c0d946a50bf65966848b3568f59755a53e44.nq.gz
    ├── 6324d401a069f4020efcf0ff07442724b52f47c2.nq.gz
    ├── 64dbfe5b9fda498497d149e0abc420497b9bdcbf.nq.gz
    ├── 65826f75f00b0b9ff151d36e991bf56ca132b6a2.nq.gz
    ├── 658de7b217be38e4a0a8a79a8384a8aff256886e.nq.gz
    ├── 67033f8c0f5878edce26d36b6676e0b74c312198.nq.gz
    ├── 676c460e14913d0dbad1020fe9da66bb28238ca7.nq.gz
    ├── 67b615b1ce3a9ad1f6defa64cfd980fed12e0a36.nq.gz
    ├── 682e77c07c0423c628a0030bfaaf47954ac5530a.nq.gz
    ├── 684975538d1368e3e70b0896c0ce4e530e18a0d3.nq.gz
    ├── 6860bb2addad3a4087dc9bdd0f1dd9fb7a35b150.nq.gz
    ├── 68b14b7e72c17bc09eca515656143ca0f29f7d40.nq.gz
    ├── 68b3dc7496e476be63d21766f1e0ed866fd2fc1f.nq.gz
    ├── 6a4eaeed89c0cdb35925c4e33673faed42f945db.nq.gz
    ├── 6a6ed4c77942587e3feca0edf3d641357b4484e7.nq.gz
    ├── 6ac6979d898692a6a9206baec9bbe245bc065a7f.nq.gz
    ├── 6b10f5bb33bb6b7ef8a6cde4d91a4cd33ceb329d.nq.gz
    ├── 6b56f82e65dd1a53537370d8cbb321a1d8eb2b98.nq.gz
    ├── 6b6b3c7558ba5132fa7f8dcb24dabe88cdbd1b47.nq.gz
    ├── 6c4d4737c33448ae023af817e73eeb11b3848500.nq.gz
    ├── 6dd2658df635b757c9e86d7af99cdc5bd5465903.nq.gz
    ├── 6e031999e7b6c6198f0533fc0a1c273c230fc484.nq.gz
    ├── 6e91df50a39bc8bbbeff7cabc67e2f16790abec6.nq.gz
    └── 6fa19efe46a6a183218291208aab871494cc2f36.nq.gz

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

[ansible-community/molecule](https://github.com/ansible-community/molecule)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
