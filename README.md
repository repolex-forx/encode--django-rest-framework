# Repolex Knowledge Graph of encode/django-rest-framework

RDF knowledge graph data for [encode/django-rest-framework](https://github.com/encode/django-rest-framework), parsed by [repolex](https://repolex.ai).

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
rlex download encode/django-rest-framework
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 6f6f44bca2e193509ea108914c9e52b102ec6642
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 6f6f44bca2e193509ea108914c9e52b102ec6642
│           └── chunk-001.nq.gz
└── blob
    ├── 00487450b643fdb765841cc81fc37db6d34e5c8d.nq.gz
    ├── 00643c97818e01ede8b609678c6b7a75c13806ef.nq.gz
    ├── 0106cc0513a857a4d9a9852660b9b87fe2074d9b.nq.gz
    ├── 02a756287267e89a3f63921259cd3e221d94b191.nq.gz
    ├── 02f90d71fc7d7cd03e8c8ec90dac7fad93dbdb73.nq.gz
    ├── 03dbbad60ac4f639d2fa8858c0f75b22a1dd2247.nq.gz
    ├── 03f313523a674519c6381bb9689d11cca378aada.nq.gz
    ├── 048cff973981e8dd4ed8e73c4ca532ffcf02e1e8.nq.gz
    ├── 04f605a03e37524e089a6936586692a68fb7ec1e.nq.gz
    ├── 051a88783f6e4db37cfab7b3310233574b860dff.nq.gz
    ├── 054ab939440a6dedc954f0e3b14d1d22ae9503c0.nq.gz
    ├── 055bfb62e4148cf8426eab24e5ed1d613ddb4cb3.nq.gz
    ├── 069aa206511195838ed239b82b2d4a7721918aa7.nq.gz
    ├── 07291d0c28d50a90d93c84864e62b15e60dc98bd.nq.gz
    ├── 07827654f4db70737f5938f6b8ece6a73488c12f.nq.gz
    ├── 084e1d53535e8deab1995364d36e6f1e7047f8c8.nq.gz
    ├── 08648351e8ed72361f7148ed5f2e38e412dea206.nq.gz
    ├── 092a2b187dc346f6269b1914895972940559b7e8.nq.gz
    ├── 0935d5a4e18addc01946fef41266377187c2de8f.nq.gz
    ├── 0952b08c810dbcedc410bb63440836801714ea5f.nq.gz
    ├── 09daf0888a3e305e3b9ce435770448f2339ef60e.nq.gz
    ├── 09ed268f2f9a3eb94cef28117b5c2ccc54e2c5e9.nq.gz
    ├── 09f111102ef4dc38f244cbcdd6da1143d7d31bc1.nq.gz
    ├── 0a243001aa1e6fe94e53007cd4212f00a5de7852.nq.gz
    ├── 0aa301332ba61d2049691a7597e1487508f84a5e.nq.gz
    ├── 0ae3de50864d93c1f79a4e659641a5d248bca2bb.nq.gz
    ├── 0ba2c5d9d476e50180f24c72525b644544f0dc7e.nq.gz
    ├── 0bf0cf7c91fe86be1393a066796ed19f8948ac45.nq.gz
    ├── 0c09847837b9dfcf8e79909f3a8b4b668c3491da.nq.gz
    ├── 0c9e900e3f12303749f5768702d319efe72b8f27.nq.gz
    ├── 0c9fb9c560564aef7eedc70fb9bb634d02ccf74a.nq.gz
    ├── 0ca9f5d796ef8b8b4e1c9d3bdcb3365a8684058e.nq.gz
    ├── 0d8444f2797d291887fa1adc7de73d404ffbf524.nq.gz
    ├── 0df63bf60374b93db3ca50a14af67b987bdb6405.nq.gz
    ├── 0e619900f71ce2ad52c4c0f3f6d82afee4731e7f.nq.gz
    ├── 0f0f9ce2bd98ec56484145d3221edd96ea86c029.nq.gz
    ├── 0fc09f0b85486f18986f11fb2f200378e58cf1de.nq.gz
    ├── 0fe8c3e93a7058da492d7ff8452b42a578db63e0.nq.gz
    ├── 10233c89043c78b78b97724f3543b982d7ada9db.nq.gz
    ├── 107e661ed8d6a4e7f6a5988d8eee2b4311c6b74c.nq.gz
    ├── 10839b13b4835ea1abf18dbb89b0b8e9c5b6e0fa.nq.gz
    ├── 10d31b764852b5927972482e0d6845936008f149.nq.gz
    ├── 1413fc609ab6f21774de0cb7e01360095584f65b.nq.gz
    ├── 144694345e5c2d1683505881af8b02ea9745e053.nq.gz
    ├── 151278cbdcbec98b187195f5d133b090ebbf20fe.nq.gz
    ├── 15624c059905532328e24896294d78ea17b0958d.nq.gz
    ├── 156258f98b73397e8c477daf67723ea7087a33a7.nq.gz
    ├── 1578e47b353e39007ccc7dd125682da18c68a028.nq.gz
    ├── 164d7c2f851878f8933a620659845b2635fe97e3.nq.gz
    ├── 16606c9f46aedf88353241fdaa53fbaa34bf3b96.nq.gz
    ├── 1680d919e32f61b3ee803b45e9e5a2b5a15888ac.nq.gz
    ├── 16b0da992c292f7b37f77d9a9be17e889d7766f7.nq.gz
    ├── 17b1e8d05f7f7526e4043c181801f0f226fd7dec.nq.gz
    ├── 17d0a46333513e07c6487926d173f937932ac35e.nq.gz
    ├── 17fb503e7979185f31a2365edf9a2077a26077d3.nq.gz
    ├── 181dfa97aacbdfb70faa1702ed9b73594f4d02f9.nq.gz
    ├── 187805af66929715b59e8d408c88b0542c85d608.nq.gz
    ├── 18c3242bbed7b0a0ad675349c155e3939d2d3c1d.nq.gz
    ├── 18c70fb96515eac8f7c6a5c13aa342510eedde1a.nq.gz
    ├── 18fc1a9bb3648b754c713596a6276c0c07e0935a.nq.gz
    ├── 1930b5dc0d2531ce0a6bdb25fc306002b26793b6.nq.gz
    ├── 199c7fc68af78cfb344c104a13663d0bd0b30a0d.nq.gz
    ├── 1a4e53f8f9a0102b643297e8ed2ef96626f0d90e.nq.gz
    ├── 1a721de4d3f507191b276a09bc069ea66d8e45ee.nq.gz
    ├── 1bdc8697c4996d2e43174d174e24cd360198b01f.nq.gz
    ├── 1c1e69bf169047f1f15b065e8c76f04b6ac4c75b.nq.gz
    ├── 1c6881858f62ad703eeaa388ef741741cc915e6e.nq.gz
    ├── 1c9c99b684564b1c4af278f96f0e016de8a28ca9.nq.gz
    ├── 1ddd6675f9633e552eb4d7c937f7eda4daf60fde.nq.gz
    ├── 1e16dbc648072a9b98cf4c32391eba51b91cab5e.nq.gz
    ├── 1e8ab344856315a226aa587f826d39577422adef.nq.gz
    ├── 1f092b1509794ba03ea9dd16ae6f5c1f2f05789a.nq.gz
    ├── 1faad69d946facc0a733a863204d7a0aac511d42.nq.gz
    ├── 2051903830e71b0fb693a6d71acaae04be5371c6.nq.gz
    ├── 20df3e4a2df67d46a8cfa8b2e9544ae5731a00cd.nq.gz
    ├── 20e925211aecab7d5be832d9c4cd96478fb2e909.nq.gz
    ├── 2152c4d38b5d7afd7bf6406be84e2736f6657d7d.nq.gz
    ├── 2228adcf7ff5707481347cefb2cbe1c9b753dd3e.nq.gz
    ├── 22447659685c2e1cbcf7ee6e716d1cb3c3b83719.nq.gz
    ├── 245ded35e6ca23cc9497992c19a887dba04b6ae4.nq.gz
    ├── 252f690130105a39286285dab5748bbf4d53c037.nq.gz
    ├── 255e391e09ef5574721d15dbf4559e8600149096.nq.gz
    ├── 25689edd2a02dbbb9440cbc59bc385cc03dca3ae.nq.gz
    ├── 25bc4ec7a55acee0dda612c6147c561691ca2422.nq.gz
    ├── 25bcacafcbec69ab14d9b82ee413347ee3a7e535.nq.gz
    ├── 26391d8cab575eae7637d9d356dd940fc11ce732.nq.gz
    ├── 26ea0cee93d7fd2fd2dd8695ed3a50c0c1269b10.nq.gz
    ├── 27e77ceb5955035120ac5759b55f7a3d2d5f31f1.nq.gz
    ├── 280725a73cd6571d8e988a39c5292a74b3951050.nq.gz
    ├── 28f8e9d66825d77e8637e58fa32a35a707e685a7.nq.gz
    ├── 2959c7201a38293eab3a18824e5e5e392b489453.nq.gz
    ├── 29baadc6c155204d68b1dc8135962c7a15ea0399.nq.gz
    ├── 2a6b684e814e9422c0805de43dc5624ec763803d.nq.gz
    ├── 2b2a3b3bbf3536a40a5159d8030a9e690fd040ca.nq.gz
    ├── 2b3d5df6da3e6d59c2543d9cef15fe4e4f110723.nq.gz
    ├── 2b4b83d57e60815700b0d8fd4ea9fd4a6731de1d.nq.gz
    ├── 2b854c6d4b70b3516b3b93a8153e1c72a875e8dc.nq.gz
    ├── 2b9478e905969c07ce1b5f8e01698c1cdac9a9a3.nq.gz
    ├── 2c3535c3a4f85e8be5348e50344e5d71daf1e36d.nq.gz
    ├── 2c3777b504eba5d4768e1b1686c3d04221640740.nq.gz
    ├── 2c6760a548bd67d0d6cbc054a2aa38ed44091ae8.nq.gz
    ├── 2d86afe817a1422b183217842d6682ef8a59c757.nq.gz
    ├── 2e7dd83aaba8b470755f314c1c1bf65a041c59de.nq.gz
    ├── 2f1625cda7ad60d6c5fda24b8af4ac511753866b.nq.gz
    ├── 2f23ce5f267bd9cba20cce38ac773030ea9ef256.nq.gz
    ├── 2f85c2f82b5b8357a4ccd0ad8893567488e4da39.nq.gz
    ├── 30df5d496c7376429beb62643934499aa3c2bb00.nq.gz
    ├── 313025ca005b282ee67fb54a39462f8ea069ba73.nq.gz
    ├── 31644eafe827c7b550f6a5d0c01cf87924a4cf7f.nq.gz
    ├── 31d5f0cc1119cf31498be5b906fa65cf43489bd8.nq.gz
    ├── 3257c8e27468b83b0d6d1669e1e17ab7583012f6.nq.gz
    ├── 3348df42a0d4bfdcfe5e0512029ed131be283f24.nq.gz
    ├── 33491ad926e2a66211f301fba25ecb8311f0ab1d.nq.gz
    ├── 33e3515d8459b4c57b0287ca10de886b65e33509.nq.gz
    ├── 33f8ea1d012cede5a94fd382cf8170f4ef95ccae.nq.gz
    ├── 341c4342a5125790f21b42365c5caa83dc6b094e.nq.gz
    ├── 34c7590aa6edb3fa9164b535b92a35dcff5a33a9.nq.gz
    ├── 353244db93000d832656f49506ce6ee2bed5d2e4.nq.gz
    ├── 35775d9f2b5a8bd8177936a4563c023bc3ed6b99.nq.gz
    ├── 364ca5b14dcd215c017d1671933633adf6ce722e.nq.gz
    ├── 36c197a0d02a78fa165f3cd123343ca87a27f102.nq.gz
    ├── 36c3b1ed9e71dce20dca9e35c36c97fd8afd718c.nq.gz
    ├── 3751732bed5bf46bde9aeb814b71f2a8e1d419a5.nq.gz
    ├── 384249e840f81d78f800f525af696baaa9daaec5.nq.gz
    ├── 3851dd699ceb59a60e8f96ac9d8be915be9521b4.nq.gz
    ├── 3852070aeb4f168b9ab2e9561d4c4e9f6bc3db09.nq.gz
    ├── 3880e3707cec8e71b527efd346daf182453807f8.nq.gz
    ├── 3a209d8f09408b90335ec148a16a4ea324f70c2e.nq.gz
    ├── 3a595d935c66c95ffa0ede345d185429fde0fd5b.nq.gz
    ├── 3a829881711d4c330f82508d574055bf0a1e2a65.nq.gz
    ├── 3b0a22dfc73aa8db00194c7c52b2dda7975525f1.nq.gz
    ├── 3bf6484a29d8da269f9bc874b25493a45fae3bae.nq.gz
    ├── 3c07105ae6d47476db45c9645a06b707bd4f1cf0.nq.gz
    ├── 3c45b564c27c6469b01935079673ce12f455689b.nq.gz
    ├── 3c8858aca7093410b568e373f0a6ad78469f6c62.nq.gz
    ├── 3d0ca3745427b1540d00cd43a25ef57e33c60acd.nq.gz
    ├── 3dea39c36307692b0643daa89fb5ed624607f6c2.nq.gz
    ├── 3f4250db45495dd3c416d119240542fea04d15bc.nq.gz
    ├── 3f4521fe428ba052ae79a3a312596301a78653f6.nq.gz
    ├── 3f6427c53ccc8198aa9bf4047263a55339120dd1.nq.gz
    ├── 40793d7ca3b7ff3744fb17924f9f90e6565b59af.nq.gz
    ├── 4095774b722034479d7a1b1584be50cb6701f717.nq.gz
    ├── 412a09359a458f0ab2e5a405ccfcfdd076de34f1.nq.gz
    ├── 41b790ee56a4bc5d2c9f4f5a8722cbbd2a1ecd39.nq.gz
    ├── 42b1156e3aeba586b56d5cc5407902a48de51192.nq.gz
    ├── 43119099a36b14dfa0d1be81a45eac0b213be748.nq.gz
    ├── 431482dca147f87d1b97ae59a4ce9ad43be871c2.nq.gz
    ├── 43684296e1650e206a577f6c0ccff0ce1861872e.nq.gz
    ├── 43a224259b0465d633e8505e9022226fdb9cc7e6.nq.gz
    ├── 4409bce77c82604e776b63ba6706090e878a69d3.nq.gz
    ├── 4691ca63fffdb0a1e8a48941f95a499d7f227728.nq.gz
    ├── 47a8194cf0637d624c0d47cf251aaa3d7aa98087.nq.gz
    ├── 48ef895475b1b66e0a813df0e26d869acde4ecec.nq.gz
    ├── 494bf792461645764d4c132850b2e69a740993a4.nq.gz
    ├── 49b069c9e3511d63348b7e94ab0b62d620b26e4a.nq.gz
    ├── 49f9532cff745e85d22809b976dd50eba8dc4b11.nq.gz
    ├── 4a2b85a9bb977c0b5c54ea19106fc5b912da14fa.nq.gz
    ├── 4a41cf04f416933ccac4bbeb9db4965dd9be6418.nq.gz
    ├── 4b01e225645bd381f5167e659694aa2ac730ffda.nq.gz
    ├── 4b2226d6910bb6a6ffeb1369836d2706576d23d4.nq.gz
    ├── 4b71475922ec896d5726aa9fc3cdedca2d3c540b.nq.gz
    ├── 4c13e5a3df71ee2357544a6a7386ed8cdce59f37.nq.gz
    ├── 4cbbc030e35e906403639a13ea23e78b36701442.nq.gz
    ├── 4cdf2bc4fc4969cb936f25b89d22fd16d43840cf.nq.gz
    ├── 4ce1a09a837fdf59dc087fac697514eda7d49003.nq.gz
    ├── 4ceb3530993f2b94983188581f8329cbd6c4e85c.nq.gz
    ├── 4d5cc4c13a17a6f87b63b733aaa122519867d4a0.nq.gz
    ├── 4d7aeb90a6d15c92411d4b936e2142542c6b6cfb.nq.gz
    ├── 4e33289963dc18f48a8d22607d5f4e0380e938c5.nq.gz
    ├── 4f1492af15d89c01d2c2c43181b8dcad524164ae.nq.gz
    ├── 4f4d75bc1256fbabd6850b4bdbaeff524d499114.nq.gz
    ├── 4f5ae133a5e4bae3c31d6ebf87ef57a3e1a6e1ed.nq.gz
    ├── 4f8e5063591102057aae0a3fcee34413c304bb8b.nq.gz
    ├── 4fcd8c779072eae8c11c8e2c4c4fcb5d9581fcc2.nq.gz
    ├── 5034edfad271ed1898d3d76f4d881535e78f3cea.nq.gz
    ├── 507ea595f6be38a507faf351d89e7a613f54dd0b.nq.gz
    ├── 50a6d0f8a9fb01938b54ccd72ef0d55931faf36a.nq.gz
    ├── 5122d9acf6bedf777fbbcf73cf510a3f47661bbd.nq.gz
    ├── 51ca3ba19ee8d350fe44c5dd6b427c942b25fb7b.nq.gz
    ├── 52acd10e2d102307d3b9a0e73594785942ee812a.nq.gz
    ├── 53b8fd98e9f9f197eafae4ceeac27f9474d8a643.nq.gz
    ├── 548b3576bb7e32ef329b9ded2aac1f30d9435bb8.nq.gz
    ├── 54990e9f6cd3ea080c06764e845682c14fd1dc28.nq.gz
    ├── 5577ad25235e035688a7488bfbf0611324ee797a.nq.gz
    ├── 55bf74af182da773c0e3944aefa6bc4d9bf6ace4.nq.gz
    ├── 55d9c992aa6d951bb9ee4669e0f9e33ce1249f15.nq.gz
    ├── 561c98e98847ec949c767ff3a251f017130b8dc9.nq.gz
    ├── 56e1c9ef84d71af910ffa7c770ecc8baeb76e54f.nq.gz
    ├── 5704cc35020503f1615b69ab98e1d3d0e6785f9f.nq.gz
    ├── 573140ed6b6bf34c78718b8d07e4c359c902a54c.nq.gz
    ├── 5834729b95889107382e5f1c0bbd3c1fda48f842.nq.gz
    ├── 58ef9d2e10f183cf234a33de34dc29a6f857a624.nq.gz
    ├── 5917a68deec7330ba2854bf9b2a2195d38a1fa5f.nq.gz
    ├── 59aee8813517c22ca8c26e47bb0bb3e3e9339c48.nq.gz
    ├── 5aaa072ae79d487f067e600ef1e049b663e88e76.nq.gz
    ├── 5ad9cc264cbe07a97d22cfebeab4d7605d8f217a.nq.gz
    ├── 5b5bb29d8b23363cfbfbd9d5dbda1f954db2a997.nq.gz
    └── 5c033be37619032c74517b4c7be1c96950cd8c22.nq.gz

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

[encode/django-rest-framework](https://github.com/encode/django-rest-framework)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*
