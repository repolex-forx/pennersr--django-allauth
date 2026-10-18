# Repolex Knowledge Graph of pennersr/django-allauth

RDF knowledge graph data for [pennersr/django-allauth](https://github.com/pennersr/django-allauth), parsed by [repolex](https://repolex.ai).

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
rlex download pennersr/django-allauth
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 5ea117e72397adbd8ca6bc61c692d64ecca4d31b
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 5ea117e72397adbd8ca6bc61c692d64ecca4d31b
│           └── chunk-001.nq.gz
└── blob
    ├── 0006e5f9656f404c14a30ac296fa484eeda64230.nq.gz
    ├── 004011c9ae178a33f3cc6eeddd3f47427a4f0e6d.nq.gz
    ├── 0055f285dd7d2ddbf26c19efd2afcb68ed60e6bd.nq.gz
    ├── 005ffdcec859213eef2bfd2e971697aafb242787.nq.gz
    ├── 0173f8dca6cf4ec62bba54ab71f5310d980035db.nq.gz
    ├── 0193854fdf1cb239e9b1f4bfaa2c7fe6b478e5f3.nq.gz
    ├── 019eb7bbd8fe83568fad2e797874dec805d64775.nq.gz
    ├── 024d151add1cb9bbfcffa5624ea66c5eef22bf57.nq.gz
    ├── 027d06e078ea660caa8d3f2fdd2b70be52c6fc0f.nq.gz
    ├── 028cff27fc8497918481a270163c01de16a732ef.nq.gz
    ├── 03239614ced5a89280d027f1d7df3b404e2d7762.nq.gz
    ├── 0348cc98657b4a16dce9807fa2b46ca6378e9555.nq.gz
    ├── 03622b7abe7b6f4182f24f52fd34cb410bd368b7.nq.gz
    ├── 03bc9c614516b8dc21edad20a6108e550bedbcc9.nq.gz
    ├── 04074367c8d05c9d6a567718b9f8b2f3bbc740fd.nq.gz
    ├── 04150ba4ecb57617029fbd56eb56614f251ab0b8.nq.gz
    ├── 043cb3a4f714902efa98b2ee568cbb2c26fffd06.nq.gz
    ├── 0498bd04713e4817a0978f8df3a7182c92442dbc.nq.gz
    ├── 04b353862401c4ac28927b6fcd5abf43b5efaddd.nq.gz
    ├── 05f734bb0f2c53ba0d6e127f205491696f56fa73.nq.gz
    ├── 065afa95b41b9d07749653cd16ad69cef82c3c1c.nq.gz
    ├── 06896e9de0f1bbf2e83078cc29354d6bc7e04351.nq.gz
    ├── 06cb238542fe9b9b35a391f1727d8a023193b5df.nq.gz
    ├── 07331ab2b62c56e3e28b4631fc81961e9bc599d6.nq.gz
    ├── 07e294e224461ce0162d198d2343edd0ef5bfcc4.nq.gz
    ├── 08a5544c3466c01457b6bc623ecc3b2db31423f9.nq.gz
    ├── 08cc4b38e4e9b1c7623002bcb62023f79a25cc0f.nq.gz
    ├── 08d87a94c8ccb6d261b9b1f2649ef0fbca7ae4b2.nq.gz
    ├── 091ba6c83934a5729f0d87f7bba752d6ddecf4ec.nq.gz
    ├── 09887e7be169781a91690c866c08134546984372.nq.gz
    ├── 0a923e22ace9fad03cc4287956308c0487227c99.nq.gz
    ├── 0b56f14a5e936cbe7a133d2d6fb9dc00fbfb8e3f.nq.gz
    ├── 0b8a4906d80abd20efa63145f582d45c9bc5d19e.nq.gz
    ├── 0c33137a677db6bc85ccf8ef7554c5eb87445c1c.nq.gz
    ├── 0c8f64d0a26e35681b936d092c7a34551e858737.nq.gz
    ├── 0c9ef190a200680080914db3b447d6dad6c06f97.nq.gz
    ├── 0ca56c2adb8cf2210e3f6852f3b63896bccbe511.nq.gz
    ├── 0d6c0d3702ec8ebb49863aa8309c9f7b9d992007.nq.gz
    ├── 0e98406dd860f56ca1cca6c62a0a38cc9e64695c.nq.gz
    ├── 0f403bfa25442ba7c63e35e66b4c4d34340c646f.nq.gz
    ├── 0fcdfe2c84768333e1370a796dec4e507b126f8d.nq.gz
    ├── 107d257def7fe1aaa3537ad20ab3559e7fe1ab8b.nq.gz
    ├── 116a2adb37faa90f5b3b04d492200934dc727400.nq.gz
    ├── 122a5692a4a3a6d545ce2589cc0759b79a545a64.nq.gz
    ├── 12391333ad203228193292100475b491df6522c7.nq.gz
    ├── 12cef90ff468a6589215cbe9fddc34e040d660e8.nq.gz
    ├── 1360a38ef9a3e8a70a75f6e3227bd6e30d4214d3.nq.gz
    ├── 13612b074cd619a4b9be6b7ffe260ca029ac38fa.nq.gz
    ├── 150ab1725567907ca1fdea1268a82cf747c9db1d.nq.gz
    ├── 157047d23fabff929c84cd635943f54f6771858a.nq.gz
    ├── 15cdbd782172e1b43f34286ef1d5b1170e1a184a.nq.gz
    ├── 162f9b9844490ca4d0971e3fae69244685eb5e50.nq.gz
    ├── 166700f0ee518772ab80075de931a35c0908a555.nq.gz
    ├── 179ec8d393525e309735f6121ec60647551ed308.nq.gz
    ├── 184581f63f6705bbe6955edc0b63841661c90892.nq.gz
    ├── 1875a3055cc8fdd0471b9358d9196a06ee0ca2eb.nq.gz
    ├── 18781f79b5abd8816047ee3750785027657ee5c6.nq.gz
    ├── 195b7988c80a623410b623002adf97c0b8ed072b.nq.gz
    ├── 195cb9952d65f1e1cbd28ef158f0e20bfae77aad.nq.gz
    ├── 19eeca92a3b3355b40d2d5404ca888cc7055efdd.nq.gz
    ├── 1bc48be23467a74f0e8d93bce78cd278950fb989.nq.gz
    ├── 1cad80bce1d29bf7303dc6e1be5267217337e96f.nq.gz
    ├── 1cbef3941caf6b05f64bf130dca47fd7cbdf0df2.nq.gz
    ├── 1d5fbfed0e76d5c983f2b34c3e688be16b382047.nq.gz
    ├── 1d7b64542b74ec1e6c4b27200ef9a5b60a5c1d11.nq.gz
    ├── 1d868cf3f630cfd38ab2cc0ad2232a7ac3a93172.nq.gz
    ├── 1e17e4ecdb869dc869d0633630ce80143038701f.nq.gz
    ├── 1e3f74087dc120866f2ece50b999e014a6c37d5e.nq.gz
    ├── 1ee6e0ad6ac7f049ea62043aaa0be56a81c04e58.nq.gz
    ├── 1ef17260fb035bfbb4c7cc57c57baec29d32ebcb.nq.gz
    ├── 1f05508efb025a7ce890f502ae873c191efde3c5.nq.gz
    ├── 1fcb4ac00d8ad6b52183f28a7b39df2ae57df394.nq.gz
    ├── 203100f9675952bd386c86df6ce31a372c8cc2af.nq.gz
    ├── 20e0dc23dc9f1d59ed72ea23bf7f4a1856b075a2.nq.gz
    ├── 210758d35890f2773a861860fc1376753e8b1f2f.nq.gz
    ├── 21311e976aeffecec8304a75227dfb908fe938e1.nq.gz
    ├── 227c1000521425f7f7525f8447e33e4df6e04149.nq.gz
    ├── 23d8806ecfa43840c3c2ca4db3d2efd3c7c232be.nq.gz
    ├── 23e3054d81e9ca0d5af7dbbfa31376bd0a7b60d7.nq.gz
    ├── 24be7a8cc82afdf3f7f9d5e856c05c7997e2677e.nq.gz
    ├── 2564146eb4fb9a8cf844e56421abd6ae9ee601c8.nq.gz
    ├── 256b07117da18bd5c15b0d15abc5c463b12c0f14.nq.gz
    ├── 25c5e2f29955cb45df395e272a3f95acb191abc1.nq.gz
    ├── 2668cee9369a128fb8b688cf6079d933eeb0811f.nq.gz
    ├── 27617ec954d36fe9f9452ad106d49117f838e996.nq.gz
    ├── 277b653f5bb0d21ba6c467567b1e1d302551b6e0.nq.gz
    ├── 285a3196787f96ea82ff131c42599d3618d9b886.nq.gz
    ├── 28633fe8d118f6913de6650ef43e479186566c6b.nq.gz
    ├── 2874b8311703e0983fada16f5c7727f4866523bf.nq.gz
    ├── 28867cc92962efc14c33b976eaa62019dec278ed.nq.gz
    ├── 28d2ee19654e6459e2e2f2fd056901d2dc32e889.nq.gz
    ├── 29846f4542909762d3e845e5df882fab5a9a355c.nq.gz
    ├── 29d32785ddf2e019203ba6d69ec16ec59ad5fadb.nq.gz
    ├── 2a9a551b114c19d105feb597e6b0edddad784131.nq.gz
    ├── 2b3089f2924fe2cca4940a4a4a3309cbe0d46cfa.nq.gz
    ├── 2b553f7dbaa50dd1e7802ac8753be77ac08b4161.nq.gz
    ├── 2cba9f4f6e2378b3760135729912bacba1b84ff7.nq.gz
    ├── 2cd4627d880d02b65d5e4ff9d99c1d7def2115fe.nq.gz
    ├── 2d4685e8a91fc323a17295dcf50aac6e5e207a64.nq.gz
    ├── 2eae853d963b0585e9cd089a47de99a1283cdb0f.nq.gz
    ├── 2ed1180c669b1fb346a40e63a719e700b0b2c43c.nq.gz
    ├── 2f5c1c4b69b95f6aa2f002c256572f41faa61e67.nq.gz
    ├── 2fc33c2ed7c9477ceea719e324e3b28a3588bc95.nq.gz
    ├── 300f4e1546c4fc4a11778d1b098c5dfccd77975a.nq.gz
    ├── 307187905674d5e4e1b1008831c7b2d323cf2f54.nq.gz
    ├── 31388f8cd3ff17e0286b89129f7b703613be970d.nq.gz
    ├── 31f295d54b65cd37f27b1c355b22f809e713f5e3.nq.gz
    ├── 32593932d5c93987496ae8e1b6fabefe64fe53a6.nq.gz
    ├── 32d091c6b5aff06ec4d5ee761966ae69730b464c.nq.gz
    ├── 3393a3499131ac433b1aa3b694f713d5b5ec2342.nq.gz
    ├── 33ad9678e25464fb3f31c4071642a1585ef18b34.nq.gz
    ├── 33d8dea34f54dc07b9a9090355d00a7d029a0d7f.nq.gz
    ├── 3427a4d84986371e688de995c58e3cce1c693897.nq.gz
    ├── 343d3f1a50c9362a44bd096c0c9ad44d630994cf.nq.gz
    ├── 3463ef3eb21159ece6b09dcdc7713432fe6da58a.nq.gz
    ├── 3469ce151024c23a0bc12f39bd7c3ce75911bfb7.nq.gz
    ├── 348c34cb03ab6914d4f64bca5130073bb94e0353.nq.gz
    ├── 3499b73f364ed5e1250b317a83fd9e3598789540.nq.gz
    ├── 356b582f22f68afe3a79016c123ec46eb46fe665.nq.gz
    ├── 35708ab0a6b99bf8de671c3d0962b943b3296fb9.nq.gz
    ├── 358949fcbed52588bc6a2e503fd54516701c5e8c.nq.gz
    ├── 35b839970ccf30fc344b9b01e446437c2b138451.nq.gz
    ├── 36ea870261e794a2b16ddd0ca7f25d7700cd37a6.nq.gz
    ├── 376ecfc02dfb08049bb542e4bbc68ecd78b55ab9.nq.gz
    ├── 3973874e307b88e3f2edbc5d2aec4abf06a1b482.nq.gz
    ├── 3ab0ccdc9445176d8be562286d777d0b7d85764c.nq.gz
    ├── 3ae65d4625549e47c6a001fe8e9722e2b2605b3a.nq.gz
    ├── 3ae82bee314ba473613b1e8e4c60508cbcda49b8.nq.gz
    ├── 3b59c274333fcb4c12e364756d25f6766996c627.nq.gz
    ├── 3b8f691dccd186cb292b9320fdf95fea79bcd413.nq.gz
    ├── 3d284a7ce66ef895dbad9a12775ae49edf1ae11f.nq.gz
    ├── 3d4a87386f1cbe1a131b6a0dea2baedca1f379f6.nq.gz
    ├── 3da6469e3c4a6ccc085e5e3f8c18122d7f37619c.nq.gz
    ├── 3de8d09fbbd78ff2e8a3d7bd32d32190f856dede.nq.gz
    ├── 3e3d32feec05f73a0bea0b94fc741494d05b52dd.nq.gz
    ├── 3ec78f4e131725118483b096021fc83413ceff57.nq.gz
    ├── 3ef8561d0ebdbaabcf2bea143b405c6d08991978.nq.gz
    ├── 3fec54e1027d3059d5cbfda0b43286ad3f277fed.nq.gz
    ├── 40a83ada784ea95f5a477ef12e88326e9f075dff.nq.gz
    ├── 40eb34d0f601733388c29f0287003eaea449f534.nq.gz
    ├── 412f3f99eda762db5b1d5d2319b07b2ea6efb7d2.nq.gz
    ├── 4135185163b07ab316d0438c1982d1d1ec0dfd7f.nq.gz
    ├── 41885c8a6427b548c33a22cc532c69e2046b8120.nq.gz
    ├── 41d1152abf802f2c55df2a104e21fbf3884e415a.nq.gz
    ├── 42c5baaa986cdc969598ab66145bc3b4b7912bac.nq.gz
    ├── 42ee950c08532202f64239e43c6384ddfedb4965.nq.gz
    ├── 4381d798ce42dcd714848a0006405f3af31c5a18.nq.gz
    ├── 43bc10a506bb02db803853a946722b5c5f88d302.nq.gz
    ├── 43cad8da5be09eb4279a48e41d1172c318ad1dba.nq.gz
    ├── 4506928658ba82698387af115510337629441155.nq.gz
    ├── 4653d4418435d9b1c27469bd5161f0b2326358e4.nq.gz
    ├── 468808eacad56df72291e030aeb60b16d0bba505.nq.gz
    ├── 46b8f085e81bd20bb7c8de400fcd3027c7f5e30a.nq.gz
    ├── 47afca1eeba4503835d715fcd97714fbd4235ced.nq.gz
    ├── 47c18d957ba54017bbf3a6e5943995d14b661405.nq.gz
    ├── 483708ad039969bc198413aeb68f69fb9106c58c.nq.gz
    ├── 48b824eccffe758657bcc70a99cf4980698a9470.nq.gz
    ├── 49fb2235f4d2406df16b1fff808600bb13c47122.nq.gz
    ├── 4ab17c9a5e24a80165c0e1439ca354f30745e5a9.nq.gz
    ├── 4beed30be724f4e7bfebb2b81559b62ebf0f5e1e.nq.gz
    ├── 4dace7f07d3db7a052634d9a163c288bbfcf109e.nq.gz
    ├── 4e36f74e14ffda0a1a7dac935497509ddfcbd6c7.nq.gz
    ├── 4ee2df248607b8a9eac0184fde2b74a9239e4c69.nq.gz
    ├── 4ef8a401fc075e1dd1fb0ed55dfc9b9b5b3079c9.nq.gz
    ├── 5076ce41bcf69b79571823720a4adaf383251b17.nq.gz
    ├── 50b5034d9cc174070f707794c0e6a103bb09b3f4.nq.gz
    ├── 50c85efa99eb753db52d85f5774d15f759a0357d.nq.gz
    ├── 51033c6830e2c7221c8c559debce02a4a4ac9d79.nq.gz
    ├── 5121b685296b3ceb29e202a00b288b13f5a4b4cd.nq.gz
    ├── 5188a2c5cadbf93efff0bd29b3ea0994b51f71ae.nq.gz
    ├── 518cfe56de537a1c8f86873c1c4f90b0a16385d8.nq.gz
    ├── 51a8ca18b6e0b6fdbb9419329977c606fe933ae3.nq.gz
    ├── 51b0ef5f96d49021d9b1c3b610ab329338bb2200.nq.gz
    ├── 54a0e25b4c6c9ca4aef467842d29b6c5d4dcd0bb.nq.gz
    ├── 54eb2832147c0f2c663a101ecf28257d4d128540.nq.gz
    ├── 55ac1c649c4924993bd6034979badeaf16dbbbf9.nq.gz
    ├── 572a6828eeb1a34f300cd2b477ee07dd4da354fe.nq.gz
    ├── 58d34e8f1f9129b3628f5dd6f17ccf1c84d1438a.nq.gz
    ├── 597bce1e6b90ebf920dd457340fd3b7da1380be1.nq.gz
    ├── 59a3145a10fd6d4eef3cd418634652f5f91b59c7.nq.gz
    ├── 59afe4348b3744750c488ddab501e75105a0abeb.nq.gz
    ├── 5a0638342ad6054ae2d539957e9a17583438843a.nq.gz
    ├── 5a572c87ea67a0aebe1e882d719fe95acaccc763.nq.gz
    ├── 5a66c2853403da8c655e309cfb2fb6049e864182.nq.gz
    ├── 5a9a5c896142e7e981702011e12e58fef706d361.nq.gz
    ├── 5afccecf6a3a6040b3a67eb659cf546ed0ec9477.nq.gz
    ├── 5b5f9a3b536e2221b20de8497c9b7e527df2b1fa.nq.gz
    ├── 5bbc015535b95afb5423d59c4c806fec81bfca67.nq.gz
    ├── 5ccb181fddc7983c9345036eb330325a1f3e9640.nq.gz
    ├── 5cd4c03317f192c023e6c665f2379b359cf6c433.nq.gz
    ├── 5cfe87f623e50feffe26ad830f52a4f123a3fed5.nq.gz
    ├── 5d7ab8c4a6f06bbacc6c1c3a859fbe4ec8fe81c0.nq.gz
    ├── 5dba48c9a845b0846f62d56b5a017337df66b5e4.nq.gz
    ├── 5e1db8fd99cb62559928bb5ea5b2dbd37be2d25c.nq.gz
    ├── 5ed2b81a99a6439a8db4f8e51ce8f253c03b817b.nq.gz
    ├── 5fb15b63bd3e0e6f51727e70855e139867c1b82d.nq.gz
    ├── 605970a68dea62490880a23cfc69f0bcd198da5a.nq.gz
    └── 60c57e6ed1ee8b6f841845ef68b53f1bb9491654.nq.gz

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

[pennersr/django-allauth](https://github.com/pennersr/django-allauth)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
