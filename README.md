# Repolex Knowledge Graph of mitsuhiko/minijinja

RDF knowledge graph data for [mitsuhiko/minijinja](https://github.com/mitsuhiko/minijinja), parsed by [repolex](https://repolex.ai).

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
rlex download mitsuhiko/minijinja
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 0ca749f7ba507514fa6b052c74130ae6ae472e03
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 0ca749f7ba507514fa6b052c74130ae6ae472e03.nq.gz
│   └── repolex
│       └── 0ca749f7ba507514fa6b052c74130ae6ae472e03
│           └── chunk-001.nq.gz
└── blob
    ├── 0002887cabf0c2d0e9832038008342a42c294c87.nq.gz
    ├── 003199573d2f03481b9f737a4d637ef97a0e0c8a.nq.gz
    ├── 00793f60c09b80cbf533e037b328d967bde233b8.nq.gz
    ├── 00e6e28f33ab0ab0d516dee0c33a520e50a7f848.nq.gz
    ├── 00e8db694acab41f54e5634e3a93f6cdad88038a.nq.gz
    ├── 010417e345fe9c49fac28b0442b070ac2dfb4a09.nq.gz
    ├── 013dc2cd2e005f3cd30031c540c95161066747a9.nq.gz
    ├── 015a380e98916b085373ae1ac4ec302f1df93d0b.nq.gz
    ├── 019ca14b26cc2d536a9db7cf35ee0dca2ec851fe.nq.gz
    ├── 01a64e5d6b58a33afc47e115c7a664e95d190e68.nq.gz
    ├── 01cec6e69c847f9cf62212b7349279709cbe172e.nq.gz
    ├── 024f156784e46510666c67d1a5881670143fd748.nq.gz
    ├── 029172df1fe61b994ea01a509682f70510e436a1.nq.gz
    ├── 029dab9671a51325efe7eac92f1e38248bf71030.nq.gz
    ├── 02fe8430ee9fe7e9a5c6cafdd9937b7c1aa14ea1.nq.gz
    ├── 033c5824190f7f516224ebc3d7d9c85365328f72.nq.gz
    ├── 03acbfce0413657f75cb453cb110a6c8a408ab96.nq.gz
    ├── 03ce1cee020ddda80b6ebdd4da87649fdbdf2d23.nq.gz
    ├── 044270634736b1cc49f8323ff2a755903e670be0.nq.gz
    ├── 0475124bb4eac91e3ef794026f17b86315e8671e.nq.gz
    ├── 04c8363d22292f28e114bf7a56c009459388910f.nq.gz
    ├── 04ed8e2d86f0960b0305b35d8507d1b79e70c5a0.nq.gz
    ├── 05425b1944450076b76d470422c2997ce8b58975.nq.gz
    ├── 0557bcdcf93c538eceacdcaf69df241552c3c16c.nq.gz
    ├── 0592dbdad924829a6e978d15a63b5ed88e787cb5.nq.gz
    ├── 059b40e85a7ea61266a5dc1bc47384d23a4f3e21.nq.gz
    ├── 05f4fa3ce08210b83f1a3d818a68f6f7569fe9bf.nq.gz
    ├── 05fa010c98dea5158dbf9d49401cb22cc2d79b38.nq.gz
    ├── 060ac1b7f253f0815bf94c146f61d6eb5ef27978.nq.gz
    ├── 061ae52b4134110356dc366d62676518e55ac628.nq.gz
    ├── 06283e694f0e109ebb40664d43b81f77017325b4.nq.gz
    ├── 0678924f441ca597f25d4acd0e795d61d9add85f.nq.gz
    ├── 06d49eb4c26c68591a97d27b5adf6f687c8a9310.nq.gz
    ├── 06ee1fa026393793c42e1a519d99dd110113bec6.nq.gz
    ├── 06f2bbdb5486074b6ea701e0c463c0d07f5fe068.nq.gz
    ├── 070bb93d8d46536ac89cfffb3373b38e4d83a900.nq.gz
    ├── 074a28322679b59768fea00f90cfb735cb3cc6f4.nq.gz
    ├── 075c538b5817e8d390c92ab5b981f974d6a57ae2.nq.gz
    ├── 07a77eb8dc2a277695953ca90ab96a06cd51f90c.nq.gz
    ├── 07f1ba84e92ca702db44a741c4f0bf157b003d05.nq.gz
    ├── 08d8d901dd1f3d56e3608e4c77ea018d66ea7f94.nq.gz
    ├── 094067df79baa947dfe9fb5857f3ae4a83d48946.nq.gz
    ├── 096855d60388db47cac3f216ceb58d537e197dd6.nq.gz
    ├── 09be96728fbd69a5df5acf42dee730eb8c1dc201.nq.gz
    ├── 0a99be5d6bbac6f43af644a9e59ef7b0ce538f56.nq.gz
    ├── 0aaaa052cf8c8786e00931fe5d4f592c32a4dd69.nq.gz
    ├── 0add7bed8c49e1b1de5205f64a1bdf071bc01e09.nq.gz
    ├── 0ae894eaeb68f092822e0c85c4192bfe356ef936.nq.gz
    ├── 0b104e61996cbe8035d33bb8d6628061b78836b3.nq.gz
    ├── 0b18c68ba63e80dfbbeaa67b1043fa1d26e7b4cb.nq.gz
    ├── 0ba0437bbd69418afa1423b8cbe9adc6643d4a3b.nq.gz
    ├── 0c3aed134c81e163918b673de5faa87afb18bf09.nq.gz
    ├── 0c4eb9ce17adf896f2a616dc9f725c66bf91f68a.nq.gz
    ├── 0d36a62471645a469fb92361dd4947d71f911a43.nq.gz
    ├── 0d649a9eec43e5fa26a8d1b22762cd1ec1f12036.nq.gz
    ├── 0d75f678684675b5feddf6af8e6750a7312c5b68.nq.gz
    ├── 0de6781ce758700517a5f69275b9e9fc744d7ecf.nq.gz
    ├── 0de97d61d675c969c5c7c1f7d553c8b8dfa74b6f.nq.gz
    ├── 0e3d0aebae8c779d1a2d63e0e34e033aac569a5f.nq.gz
    ├── 0e5cf1806bc796ea3230cebd3e45b1d86bc9fa49.nq.gz
    ├── 0ece609f7e6ecc132b603170c5fa3cc29d26d5b7.nq.gz
    ├── 0fe7753901f77d42fb83450c95c07d8495c413ea.nq.gz
    ├── 0ff00ccd9638990c18b35ebb8c670f2de43ceac6.nq.gz
    ├── 10d99f82125c6f96c890dd972bd30a063c957035.nq.gz
    ├── 10f8056d32774cab99be76b8b3505b4013f70671.nq.gz
    ├── 112a10725d62de45964ceed2f0e0c5a0c92077b6.nq.gz
    ├── 114bc4726f3f8e62ab3ff46391634f0343e00707.nq.gz
    ├── 11fdac9a8d0f13ed552b167559f39b32312da329.nq.gz
    ├── 12286f584697f188f066b102938dfb5dcc40f81f.nq.gz
    ├── 124467f6e9db8e287a9f17d036dac8a8db169a64.nq.gz
    ├── 12b8705b52fb8c3499d1e72b807b242ca3aadae7.nq.gz
    ├── 12dc0071a973d864228231488fef727decfb9082.nq.gz
    ├── 12f3ce71301cda7b34992334403a471f67715bdc.nq.gz
    ├── 1325f48d334e4725b5fd06b5b52c09237a1cedba.nq.gz
    ├── 1332de7b3daa2a59cdcae65fc7bf19e05d2da451.nq.gz
    ├── 13440d39d8a4759944087b119396a904872976ae.nq.gz
    ├── 137e0c4fdb561ceca9fef38338b2746d139d48c1.nq.gz
    ├── 1399dcd69cf6894307838f32c0fa436c9505373a.nq.gz
    ├── 13f763227fcf58e1159a41d0260c5e9f10543984.nq.gz
    ├── 1445f7e2d09adea4b7cc2d7a348933c310db4384.nq.gz
    ├── 148b7f45d60fde45b8d795d48804a8767194a95e.nq.gz
    ├── 14c5783054efa3304b800833f6bfae39fb13146c.nq.gz
    ├── 1504f149b2b111205a48aea71c7d5898e3b7a391.nq.gz
    ├── 1597c6b0f71d4a9cd7575d63cbdcb828d7badcf7.nq.gz
    ├── 15be4038c820c3516595c6daccb729c4aa503a0d.nq.gz
    ├── 15c4ec1002d27409c414ac339eeb986b3be8124a.nq.gz
    ├── 15de6c25268dd290599ad9ad01524a7a64834bb9.nq.gz
    ├── 162b14aed1b254d2412533b2cb4597804dc94fb8.nq.gz
    ├── 16e6a9105b49e9d526df30553a495a8580212801.nq.gz
    ├── 16ec4c5881a1cf100479c59ad9a2b59cbc570fb9.nq.gz
    ├── 16fe87b06e802f094b3fbb0894b137bca2b16ef1.nq.gz
    ├── 1763f27142e4649326ffef8f11ee0521a531dc5a.nq.gz
    ├── 178e523766686494f60ec10e9cf86e0dfaadf3d2.nq.gz
    ├── 17dbe6ec1428678e68b2e996b3d2a3bb71a7fcf8.nq.gz
    ├── 17f6a017d7347eb1262674e0be4a950b5c466227.nq.gz
    ├── 181371d34985a1fba4746161f65dd9a2fc582fa1.nq.gz
    ├── 18ad6a0d836d3fd0343856357fd8d26bcd558050.nq.gz
    ├── 190e48f047b60d8cef5b49b09c1e472ebba7cc06.nq.gz
    ├── 19738163866ad12d9b98f0e054ccfa3ebc705a84.nq.gz
    ├── 1998c76655fa3b252fcfee505635f710edaf3cf6.nq.gz
    ├── 1a1076f0dcfce29337b2fdcaf5e9f6ed6efc4941.nq.gz
    ├── 1a999c32983a2cfbccbeefff126a1e7dff1adb25.nq.gz
    ├── 1af6573e4e9d40f2b6a9cc24b05a33abc80b941a.nq.gz
    ├── 1bb3e472571009c83ded91746211ba14def31500.nq.gz
    ├── 1bc2654bb86fcf41d63df2cdc08eaad9fb8cfeb6.nq.gz
    ├── 1bc6e3b5d0ef717e66fdb073d5bfff21915bfcb9.nq.gz
    ├── 1c5f2547a1f3eaf6e275c9038773874c7bd760e4.nq.gz
    ├── 1c7c17fa2b5656929dd9519ee620067bec7b64a4.nq.gz
    ├── 1cde7fc829e7a791a75f139d961635947c9ce386.nq.gz
    ├── 1cdee46beb04341921dc39a69f8732a39765a1dc.nq.gz
    ├── 1cf4826bb6f9b0a86815eeb37bde3ac4b5ec5a2d.nq.gz
    ├── 1d17175292ad6e8d4c9de6d31b600208636ac0a3.nq.gz
    ├── 1d4db8b464c9c07615d2509420db63f506a39e76.nq.gz
    ├── 1e3c788a1eda5cfcac65aaebe217bddfc190a968.nq.gz
    ├── 1e8ff9b11df04c1093ebbc955837249edcd41e77.nq.gz
    ├── 1ee5840b4894f1e4d0615c109322928a1549c249.nq.gz
    ├── 1f0de22a51570d68ea95915f58d16cbee789caa5.nq.gz
    ├── 1f3f5e2e073f4a78897156209cbeec8ef2e0c74b.nq.gz
    ├── 1f44acda30bf540a28270fd10df047d408b219e9.nq.gz
    ├── 1fcccea2bd4ef9e99ff84411b1c6848142fa555b.nq.gz
    ├── 2004e0feba6f3b7574579823118450a26ef45e42.nq.gz
    ├── 20705f4ac2b4528f62c91e4064b7017cb646fb8b.nq.gz
    ├── 2076f1e624bc84b45b6f778c254a3b7b5fc15e0e.nq.gz
    ├── 20bfe55e6fb7412a05541120cb918362cfe48a64.nq.gz
    ├── 20fcaf290ef1313cd06c959d930c884d7d7cf977.nq.gz
    ├── 21003748cef8126175666f572b6b1ccfcf82e9ab.nq.gz
    ├── 21197b2fbceac055cdc836db06d3c27c08079fa4.nq.gz
    ├── 2139719cde5d0fd5c2b11ffcbafd791be7fc963f.nq.gz
    ├── 213ff557438e48817f5d6fed4f0ed4f7bb06ce13.nq.gz
    ├── 21452ed87b764910c12038ef9ed7dcb7f1ed90e1.nq.gz
    ├── 21825b5e0b8e5f45097a0b3e00bcfaf38bfe85a4.nq.gz
    ├── 21a674ecd1aab2f9f8acbacf2dd4d87eebbe84e1.nq.gz
    ├── 21bc23cf66dd4269a3976420571fbbe7bb10dbd6.nq.gz
    ├── 21dc30e553a513aacb26073abf69362cd3f40505.nq.gz
    ├── 22b9b179ad8eafdc2e0349b5dc96c09a3c4f1130.nq.gz
    ├── 22f3546b24c13e5f07fee631ff293351b434eb83.nq.gz
    ├── 2394864999bf879f21dc64c57d8f8014fd8ad588.nq.gz
    ├── 243b21cc72765f0086f5f00bc750bef940f78aca.nq.gz
    ├── 24724e824f83ae677af75387b4e924881a9cc3f5.nq.gz
    ├── 249665c3f58119919f79a7ad4c29fae5cbd39842.nq.gz
    ├── 2538d785f96739956fb6e15c9eeff6b32c290d9a.nq.gz
    ├── 2546805d3befd5a1d6e4f7d7b140e4a10bfaf69b.nq.gz
    ├── 25b0c051ffb0a52058af9fd663e104b2a7778b83.nq.gz
    ├── 260995d12563488e76725323d2ef86e30a730978.nq.gz
    ├── 260d2ce4f94ddaaaa80b3aeb9c6bd76c2c08982e.nq.gz
    ├── 26211d8054890314ae2fd27516bc6cc865e91c97.nq.gz
    ├── 26df78592b284d896b03c42cf0cea7282673a7ce.nq.gz
    ├── 27249de4c6939ea150832ceff5ed3551a4000d7b.nq.gz
    ├── 27abe6318ed9f775cb18af25e4d71301d852a809.nq.gz
    ├── 28dc5d1ff58996fdbc595b8ff4072b1387b268ad.nq.gz
    ├── 28e8ce9cdc7519da57e713ff3d6b3af85bdbb7f4.nq.gz
    ├── 296da3e93ef8de55e9af8cafafdd07b6da6ed54c.nq.gz
    ├── 2a005ae274f72d6068d307c8346af67b880659c2.nq.gz
    ├── 2ac89da09679450cb126fb56129c89f06f2bed8c.nq.gz
    ├── 2b18cdc01cab51c8d809728d7b8d7a105325cb97.nq.gz
    ├── 2b2cc67efcdb6958cfc4489d949a4404ec8e7282.nq.gz
    ├── 2b43c19c9c6b912cffbca0ab19f93ece10f27b90.nq.gz
    ├── 2b52a85a94cef911ac1b26e2216efd4b4cfa67be.nq.gz
    ├── 2b62ac374e92c236cd18c6540859831d565e5f9b.nq.gz
    ├── 2bd3a370f6401db9d2aba8126864a734c7c03100.nq.gz
    ├── 2bfc5d099643dc489d16c9441ed7c4b14ae23cbb.nq.gz
    ├── 2bff4f34596af9c88cb774ccb249fec18c18057d.nq.gz
    ├── 2c3a632f2b253599f041e94954a86c573225b269.nq.gz
    ├── 2c7fe778f38aaeb93b5fc64dce4f2c6e90ec58bc.nq.gz
    ├── 2cb5952d6284c328d8e6c21a176e5b701d1968b7.nq.gz
    ├── 2cb94dbc1d365bb5b77d802ee21def182b45befd.nq.gz
    ├── 2cc393ba5314544f21c7688aa1a9dd19aa1fcc28.nq.gz
    ├── 2d13e9e0bb62091dbcbf367762e7c4de607eb527.nq.gz
    ├── 2e48921215f0e196de0a828478be7a32ec75d275.nq.gz
    ├── 2e5ca74650924da737448b4f8363858d051256d1.nq.gz
    ├── 2f071c534a059aed61c83f2ae1da5b7d7a4b45dc.nq.gz
    ├── 2f281664859966580317be4a8bd615da4cf5b0df.nq.gz
    ├── 307da2d69e027ccd4897b24d7f177ebdfa1cc8b8.nq.gz
    ├── 30b7b57f8b103e16b0d74edf31608b79e9e5128b.nq.gz
    ├── 31211c1669a0c9ca6ef3dbd5572a0ed960f7cbae.nq.gz
    ├── 3122eae6161d444c5dbb54fa9355c8c9ab68ed76.nq.gz
    ├── 3153f160e2f9cc684d511881c23d35cc7dcbefe6.nq.gz
    ├── 31e91266ec337dae0d3a9329d3624d0656fe9002.nq.gz
    ├── 31ecba13da51393e1e2d56e7a9cef3d73c4336f2.nq.gz
    ├── 32043e5660650a35299633826d0ac525e99389c2.nq.gz
    ├── 32393fec795abd031ca537b2e078dd5b61a74ae8.nq.gz
    ├── 3265a9227e72ccc89b34606d76b51ac87c6d5390.nq.gz
    ├── 326780f8d59283ee1bb1d329feacd65e4bca9c50.nq.gz
    ├── 32792723e34ba7836ca7907e1a28587c9b307f88.nq.gz
    ├── 327dcd037a7e12073048991b97e2ca1acfaa086b.nq.gz
    ├── 32d46ee883b58d6a383eed06eb98f33aa6530ded.nq.gz
    ├── 3328d00f499de800654fecd45c69d8c13f7749f9.nq.gz
    ├── 337ce3bb1625e5c7dcbf40e90d2bd989bba8dae1.nq.gz
    ├── 337d3b7f08fdef8f2b847e7f5b684ae89c3c18b9.nq.gz
    ├── 33bdc7fb11e614bb99ba3749a140bf9d5f75ab50.nq.gz
    ├── 33ca11559c8e0eb6061b08d345d5b1b71f1170d4.nq.gz
    ├── 34328674e453213c0ca5d4c1f4f6da1414243e01.nq.gz
    ├── 344e02e89df53e52ffb33e9111875eb6bd1a2ab1.nq.gz
    ├── 354628bd06a1f6580f35f6ce8f79b893408ea3c7.nq.gz
    ├── 355641b81278759058cd019bfe547ac84a9a2326.nq.gz
    ├── 362d4889ebf2503920512debda47d437bdd81b74.nq.gz
    └── 36a58a66c3aa76c91a18efe039cb43c8c65a4e66.nq.gz

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

[mitsuhiko/minijinja](https://github.com/mitsuhiko/minijinja)

---
*Parsed on 2026-11-22 by [repolex](https://repolex.ai)*
