# Repolex Knowledge Graph of nunit/nunit

RDF knowledge graph data for [nunit/nunit](https://github.com/nunit/nunit), parsed by [repolex](https://repolex.ai).

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
lexq download nunit/nunit
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 8e91d6dc4d051b6bc5fb4b1517cc3f317390ac73
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 8e91d6dc4d051b6bc5fb4b1517cc3f317390ac73.nq.gz
│   └── repolex
│       └── 8e91d6dc4d051b6bc5fb4b1517cc3f317390ac73
│           └── chunk-001.nq.gz
└── blob
    ├── 00250b1e571b43eb76b2f8b647f6b5c3369e0210.nq.gz
    ├── 002649e0aec85d0c7db46834f7d3f6bbc5d73dd0.nq.gz
    ├── 004d03051db1dda637495a67cd940e567717b5c4.nq.gz
    ├── 005de8b2d5c534e0ebc3e55410638e7fa51dc5b4.nq.gz
    ├── 0090335c98cf579065bd060e37d7b830f14bd5c4.nq.gz
    ├── 00af42ab64fd2cc85afdfee9a5abede14d5a2d3d.nq.gz
    ├── 00ca6e10f66c6af788cab2f9e5d91fac74baad87.nq.gz
    ├── 00d04aad9fbf1d0cb1c2d7c6361ad776c15b8c11.nq.gz
    ├── 00daa5b1e91e006269b1f5069530109cb2533ec9.nq.gz
    ├── 018d1dcaa5c09808f8464fcae3a4740fdcc384be.nq.gz
    ├── 021c3a1b027ac0d261f3f414ac56064086261ae4.nq.gz
    ├── 025f1bcdec0cee41933c9846d62d07b5ac41e4a3.nq.gz
    ├── 028779d8452944958265c3bc2233f8352164172a.nq.gz
    ├── 028bc08eb0c794538b879121928049b6de41872f.nq.gz
    ├── 028e0f391b3e246fe7f51684c15a8c4107deb840.nq.gz
    ├── 02cbe62aaffa47f9d2b0d81b7eb8ed27ca82a359.nq.gz
    ├── 03aa165852a9245c9d4322c2b2f59f4dacdda0b1.nq.gz
    ├── 03c361220d36bdccb7608a1fcf0a4c296057788c.nq.gz
    ├── 03da0d0c817053c87be05ab86c754763273ba986.nq.gz
    ├── 041a258d7a5a585fa21ed3432180f3920d47de60.nq.gz
    ├── 04271c387fc501bcc33c03e6af27908e7a68bac9.nq.gz
    ├── 0428e5d01f8d627e998e3d47446f4b234f306d10.nq.gz
    ├── 044c65ae8e1a2df65c713ab197854cd7cdb449cd.nq.gz
    ├── 046924baab6ccad690163a143cf0d2756bdd7500.nq.gz
    ├── 0480d5fa5b2dac513357819c2861a6ec559f9888.nq.gz
    ├── 04b3300d27477b2d220967275ad81d562eeb8136.nq.gz
    ├── 0540ba21819f383ea74690d05b30905a5f54078a.nq.gz
    ├── 0547a961c01039eb40fba167e7244bbb3819c399.nq.gz
    ├── 054dacd3a82464b895ec622990fb5fd11589d6ca.nq.gz
    ├── 055fdaebc7d45c751ccc914c8f9c7a5cede83996.nq.gz
    ├── 059f57433d1ed24582b711b48d8fbd8ebf664758.nq.gz
    ├── 05c6ebdeda47d36b70287cd5c68d5ff86058bc2a.nq.gz
    ├── 05cf2b8294adb2cce6fe7ef8f0032f6ed6a78135.nq.gz
    ├── 066dee162edcde86ad1a6ff47e667e901c3fc52d.nq.gz
    ├── 0678a5d60b288c8fd4bec19ff8588e688197baa6.nq.gz
    ├── 07123efe806c42c887bc4ff7bc55db391cd7dbed.nq.gz
    ├── 076f05c409796a7c9fac8a4df903a4c37be7999d.nq.gz
    ├── 077cb538adec9c83b780a47edacb4afe6fcc4bce.nq.gz
    ├── 07a4f9d6cf32499dbd7f918aee397b9dc3c2e917.nq.gz
    ├── 0808d4c1417de23a8f591ea8878e39fb2f7a4719.nq.gz
    ├── 085d28a3e9544b3d57b4751e8e66fa349e156a53.nq.gz
    ├── 08846fab686d6b7e79829f6ed683c9db328522a6.nq.gz
    ├── 08ac6aa714c874d1f0868310002752b2670ef013.nq.gz
    ├── 08ec6e34cacb01ee08f96bf6b9cb34a9a4f25dc4.nq.gz
    ├── 090c4f8782b948b644337e4f74d203a797842095.nq.gz
    ├── 090c51ee45c3b66f98c4a8f3d8684fd3ad074351.nq.gz
    ├── 093d6ab55e1b9855eae4517bfd1befbc05981a08.nq.gz
    ├── 09b4d4d8f8c39c2ebe948224834b46de75a2945b.nq.gz
    ├── 09c5f4ad107d50f7606f066afca529b563ddaa93.nq.gz
    ├── 09e4bd75793faa2267a385d0d53d96191877a39b.nq.gz
    ├── 09e6caaacd2ac76270018ead64600622699b64ce.nq.gz
    ├── 0a2302a24d75d6099f55112b49b1174c37414c59.nq.gz
    ├── 0a4c5415460b96a5d1066624621b1ea4bf13d932.nq.gz
    ├── 0a82060a5f5e211fdabb99f2dfb1a705eb9a1d3b.nq.gz
    ├── 0aae4810fd44c9c83108b440db5b64aa0af88e35.nq.gz
    ├── 0b6d0496a338ef22b36c146a97e6f7492b70902a.nq.gz
    ├── 0baf1362c5964342a21b9bc229f65d58c429f9c6.nq.gz
    ├── 0bc357bcc3b603dcccb70babc097c6cd1dfcf35c.nq.gz
    ├── 0c30e18813a5db382aada9b57e2e4b9289b10b83.nq.gz
    ├── 0c9470b38d6a2396777f55d702f8a3c5fbce0a3d.nq.gz
    ├── 0cd022c39ec81589177aca64712ab8839da0ca39.nq.gz
    ├── 0ce24d5ca2f1b3852e7efe904d39d2d14ae8366a.nq.gz
    ├── 0d846877b42d6d54726aaa268fed3d2ec9086df8.nq.gz
    ├── 0e2d59e7a462ea26efa4f4b09e60cfb4e02160fb.nq.gz
    ├── 0ead77b41470c7946611cadbddac543f13f1ddcc.nq.gz
    ├── 0f04046ece124bd1babd69cf226ed20db7ec4eb3.nq.gz
    ├── 0f1909f55ba1def3dd6a413021ae34ef72f472d3.nq.gz
    ├── 0f67f48430024cb854e3618eb66fd4ce1d157ec5.nq.gz
    ├── 0f85d08b6735d922def2056338005f9c0c0234ed.nq.gz
    ├── 0fd65e978f79bfdc669be4e49d35e9ebf99c46ca.nq.gz
    ├── 0ffc239ff795ecff1da48182e44fa0642c769997.nq.gz
    ├── 107a7e14398b3fab6586d70240797591339a31a2.nq.gz
    ├── 109054949edb685fe634789afae6a585998e42de.nq.gz
    ├── 114a196a4d70d497ea29bd6c6953499b1823f332.nq.gz
    ├── 1168bd83857c9df8aa11576e81f2889929cf206e.nq.gz
    ├── 12be5a41732b0c66f2127c9e6e2cee8eca684636.nq.gz
    ├── 139f7ae6b3093b8429ba717755f3369c8fc65843.nq.gz
    ├── 145038f59481e06f7c2de3a9861965040851cf7e.nq.gz
    ├── 14895a33edd4546d61e853e9ef67c4fcb176cf73.nq.gz
    ├── 14b60bf185065f3b4491d038bc8218f094144246.nq.gz
    ├── 14cfdc03d16afc3e2f783fa527f196075d810a03.nq.gz
    ├── 14e26f2f0c937295e51616143b2508b057972552.nq.gz
    ├── 14e4fe52d1876e900fb402b177653ecf5c8c6f80.nq.gz
    ├── 15b18f7b5bbdb71ce73b1e739298aa9eeda3d74b.nq.gz
    ├── 161d1503189c0fafe7768d29fa9a12f142bb2f41.nq.gz
    ├── 164785556b26df0a66442cd4275dd1f03f752848.nq.gz
    ├── 1659e16c0b570aa3b42d090a24db450f43986ca1.nq.gz
    ├── 16b1bbad162b1335d7a9ef0ab30db6ffb9edbc5c.nq.gz
    ├── 16c62ceecfa36fe7e6396ca948e08df097a26e64.nq.gz
    ├── 1744794f0c7386251b32a6d9c7d2af3bc761b4e8.nq.gz
    ├── 177c6660032158efb78f412c4b4c8d6789477257.nq.gz
    ├── 179c514e56d5c80d8c4d5aed51a5182742c4ecba.nq.gz
    ├── 17d1f35bb50c1f6dd8660947784a5659dc6f3b8f.nq.gz
    ├── 17eae20061dbd31f1599402f04ce6e4ff2017609.nq.gz
    ├── 18010b1cf4a62fab10d59e65c41ca904d95ccf9e.nq.gz
    ├── 183c120dc03c3198c91822da6daffae6a6692940.nq.gz
    ├── 18a92c515502e38a36fd7ed8478b8a9ef0b5623b.nq.gz
    ├── 18aa78e181a1461e875f4f78a871a28eb34c3261.nq.gz
    ├── 18c10214ee0d70c2db28193e124e8a883328f7fb.nq.gz
    ├── 18f80253007e1419be5c2a7cbc6c72099e265885.nq.gz
    ├── 1953b21f966a76af196c83e7ddaa44b6a81d2032.nq.gz
    ├── 198da6e2f2e749adbe1a55860552ebe7d23ff3ed.nq.gz
    ├── 19b24e354bfdd4ee9bcf25554b016b7b776b6350.nq.gz
    ├── 1a6ae90cddab16552af4396ca3cf0f4c084f119b.nq.gz
    ├── 1aa0b39145aec740aea4caa93c5ac172b95cebd5.nq.gz
    ├── 1aa95c84d179442182eea52214aed45ea2c00243.nq.gz
    ├── 1aaa56954ae0fd6372489cda310b2ed917ac78d7.nq.gz
    ├── 1b47a4c3fc58ad24db6ecb60d1b9283eb27288f0.nq.gz
    ├── 1b589f5ce59ef70e5e9526b1fcd0bf44d02c87f4.nq.gz
    ├── 1baf9af35e07ce0b0bccda40652066d7ea5e9a89.nq.gz
    ├── 1bfb428c6c3bdbe0ef399cbb231ba910fc6a2c6a.nq.gz
    ├── 1c1e01b94ed15d9e92c361a51ce46480b2ab91ce.nq.gz
    ├── 1c7c016cbd4ec865c574db2930ee09b77084decd.nq.gz
    ├── 1c8595276c6b516b45451f903e9c8040aa11d618.nq.gz
    ├── 1c917a6a829c1214323ca42fddc9634f7841801a.nq.gz
    ├── 1cb6cd1ac844fb8f8466fd453b635a44a3ce6672.nq.gz
    ├── 1cd5da2c7fdb47f560e838d9d5390b3883031a65.nq.gz
    ├── 1ce80049b9dca73a6abdb907bb99041a88a0967a.nq.gz
    ├── 1d02da4baf01fd5b288876cd7a7852978a1eb276.nq.gz
    ├── 1d2f84df9fb19cddafac378afc73a6d61b2d7b77.nq.gz
    ├── 1de6b4514be1ade28abcc3ae0d0d5ed2a2612601.nq.gz
    ├── 1e35febfef4b217f2ad64ae343f9b5e907257036.nq.gz
    ├── 1e893c4fbd3e350ddb1c7e37c935dd145cf87df4.nq.gz
    ├── 1eb3badffa9111d8aa581c99c3908a81ed35fd77.nq.gz
    ├── 1eb7540a40b40429f1bf44ba2ac7af2c8341e0aa.nq.gz
    ├── 1ec68bc84ed63b5ff54a75465b6dff40a880eae1.nq.gz
    ├── 1f0d3175e79674e0c52e0479c8e39101726d21c2.nq.gz
    ├── 1f189f0e6a5e0e09b5717abe57effecec6f7424f.nq.gz
    ├── 1f43f188b518afcb6c7b88b21c7ae9754c9dde4f.nq.gz
    ├── 1f509bbe20ab21fea609ee39a8e0c9af86961c1f.nq.gz
    ├── 1f8f2d0d898fe048c7fd0e03501266d74f3b4c04.nq.gz
    ├── 1fc5c7cc21d15e687b3ebba1ace776be90623b1a.nq.gz
    ├── 207559c34dd3e53c6aad62016b3e35221a50734b.nq.gz
    ├── 209194f99e3acd9c20edde388bbc1c19cf0356d8.nq.gz
    ├── 20acc3ac6b168553dc0f626ca003d2a23f7dbdd3.nq.gz
    ├── 20ad1a50fea5866c9ba5482d94403e4dfd68361a.nq.gz
    ├── 20efb01ce460d4178c3c12a4f344bb0bf48fee49.nq.gz
    ├── 21386b55932ad6d88d9a95ec066d6816967f250b.nq.gz
    ├── 216897e09130a758c4fcaed6d3887b97c2ada4af.nq.gz
    ├── 21821d2912948a4f58cf2a0f609e1479527be49a.nq.gz
    ├── 21a0461e1e0745b2841a6d1348707c66c60c683d.nq.gz
    ├── 21ab1dc8c5b1a0353f4c7ef0478c339af6026591.nq.gz
    ├── 220084f94afdf1426ab24b1e1eab0a5a6a3a93dc.nq.gz
    ├── 220b4f0afee8ffba070250f5e465b52c67f64b6e.nq.gz
    ├── 2221cd3716c64ac6f17ebbdae8719c06c45abd07.nq.gz
    ├── 22616d8fa90e4c6cf708548e3cde116787bdb4cd.nq.gz
    ├── 2272083a7b59a4836ccd291d4ababb1f213dea97.nq.gz
    ├── 230e0a3f7194908ce682527b80c72dad444ba174.nq.gz
    ├── 235f46995d111fea18e756f71fd072910d31472d.nq.gz
    ├── 23815de0708c3ff987d72776e01e76d048208e3b.nq.gz
    ├── 238f87ab9e5251c20ee8c3ca2f88fc4914fe5702.nq.gz
    ├── 239619710b6b4aeb47ffbac9393685043abb7ad6.nq.gz
    ├── 23d10ad5547e46e08939f01dc1373b1fd495120d.nq.gz
    ├── 23d232512d88991c030839653625465e8d7b4d5c.nq.gz
    ├── 242870494d6d33c6c18896eb516044b999e63eaa.nq.gz
    ├── 242fab39c86daf1c34b0d42e733bc43262ee6e95.nq.gz
    ├── 245b1bd7611a8ffeefaa367efc872ffea68ddf92.nq.gz
    ├── 246cc53e9140d591cc139c0653f4de34e781e218.nq.gz
    ├── 24a335188349ab9128f3e5e5902a813286f1c65c.nq.gz
    ├── 250f0ff5a1c44cac2708cecdbc5b36b5b7363af2.nq.gz
    ├── 2516d58b65d5fc99071407a7fe2a9bdb51e35c89.nq.gz
    ├── 253e34fb9786c414647633ebc07d087a689480e8.nq.gz
    ├── 2576cb1bd2b315357d5c69e6ef9ce578507efa3f.nq.gz
    ├── 2583844fdce6dc94a4477773a35d91fa5cb6d97b.nq.gz
    ├── 2596fd29ea29db1a171def51dd8524cac0435999.nq.gz
    ├── 26422695533b4e303cab09d67f7f43f8ff49df08.nq.gz
    ├── 2658131959fa74327dd5006bf97e3351178749df.nq.gz
    ├── 26a2b3fac5b0a81b0a06e9ae927a845b5a31e0a2.nq.gz
    ├── 26bce96115e5aa14105bf0935934cf400c02bd4e.nq.gz
    ├── 2719c4d0b9908bc5178db7be544a470df8a5d2cb.nq.gz
    ├── 276d01ba10d5d040a3098095d6ee4add5049dc25.nq.gz
    ├── 27a8ecbc590df51c7130e21f67e6da97b1dfc424.nq.gz
    ├── 285b8dc5491492561333a0a55cbb15f297b8c4f0.nq.gz
    ├── 28c0fa7070934be62af5fb77545e1a94856bc8ed.nq.gz
    ├── 28cc24dfa33dc486e144292f4f228007f9b6edb4.nq.gz
    ├── 2948a08ede5c2a1f76d423340fe1d62d2765c5c4.nq.gz
    ├── 29570cb1ec4ea5d2afe5100b157ccf77a1e73c47.nq.gz
    ├── 2977fddec687d45495b9df538c231847ef1fa72e.nq.gz
    ├── 298250f269189f28a8a1122f462cebd1a3b53151.nq.gz
    ├── 29a731eb00c89455a8503aba1c12446654e256c3.nq.gz
    ├── 29bea55ae152fd278edc80d24acd189f72176edc.nq.gz
    ├── 2a09ffc5157dd5d19f8a90a65ab61943a125f7b3.nq.gz
    ├── 2a4e145e234873eef0c06d62eb51983c71516168.nq.gz
    ├── 2a9a05b7f8f6a528d543f3a2215e15f163243081.nq.gz
    ├── 2aaab559a8f2fd5bb482ac55f20da2437fb7aeff.nq.gz
    ├── 2af608fd49f95bb7e0d314e34a4ca03056f5ce54.nq.gz
    ├── 2b09d27d5cc04015971b75a50bb52c1ad879aa38.nq.gz
    ├── 2b3ba6bc386e88ed674ee16d41ffe30ba10abf00.nq.gz
    ├── 2b6736cc9d68d790b7bd46222511f45ffd6690fe.nq.gz
    ├── 2bcde90b85c4b874b7b5767e0cdb8322518c6a83.nq.gz
    ├── 2bcf30f9e89063b451f58ffd7231dc42561d91ce.nq.gz
    ├── 2bd6e0c34815d479bc47d7689abdb71135dad3f8.nq.gz
    ├── 2c8b711af7531de25b757ae7a5933d05c73ece27.nq.gz
    ├── 2cdfd511ccb88d55cf8f6ccacdc072cbfa8980b3.nq.gz
    ├── 2d00fc21b48e03e5ef007f952799bdc37a1f376c.nq.gz
    ├── 2d0576ae2ee5e71261cac807b548ff32c2489355.nq.gz
    └── 2dcd2119440c2e78bb81a05dee374ef82f5676db.nq.gz

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

## Source repository

[nunit/nunit](https://github.com/nunit/nunit)

---
*Parsed on 2026-04-14 by [repolex](https://repolex.ai)*
