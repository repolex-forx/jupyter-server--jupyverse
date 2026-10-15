# Repolex Knowledge Graph of jupyter-server/jupyverse

RDF knowledge graph data for [jupyter-server/jupyverse](https://github.com/jupyter-server/jupyverse), parsed by [repolex](https://repolex.ai).

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
rlex download jupyter-server/jupyverse
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 5ab77dd10bd95e5d4bf5b0d1890f96c1efd48cd0
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 5ab77dd10bd95e5d4bf5b0d1890f96c1efd48cd0
│           └── chunk-001.nq.gz
└── blob
    ├── 00b89fcfc78464c5ab7756a3a55b841ca3a98303.nq.gz
    ├── 014f4da44d7c9844922c2ac05394b5c9f53c19b2.nq.gz
    ├── 02bb16cc7f635cf97f13c2e2bd9a06346b7720c3.nq.gz
    ├── 0366d91d594ed9896522f97525bae93e9feb2868.nq.gz
    ├── 041832012dd145c8248caab411a87b34843a7980.nq.gz
    ├── 048c98d5999ea06e35f8ac0a6d6beb79f523ef3b.nq.gz
    ├── 0584bc3913606f9e858c9bae0efc3e75d1ad83df.nq.gz
    ├── 05e07ac0aadd5f9453b3b9eaf945188a66f271d2.nq.gz
    ├── 067b064f188c50ec26bc8c43c59973d8d2325bf7.nq.gz
    ├── 08ca22d7b7957334bddfbb07f8f4d459860c4d3d.nq.gz
    ├── 0aaa10c6b816b81faa36dad95584763ea3e0ce74.nq.gz
    ├── 0aeb886ff76e0bcaa3a8a7f23e42615dc11ef2df.nq.gz
    ├── 0afc3fa7a588e171895ea466f403a1495079e348.nq.gz
    ├── 0d486f5c8d6d30512110e264cbac8bc105d671b0.nq.gz
    ├── 0fe8aab6bf4ad5ba8cbbc5a014ecf8aa5fe4c606.nq.gz
    ├── 11303cfbbba1dcc25168b5bb417bd72d59ee9926.nq.gz
    ├── 11a37821968c4a696ed39f9b775ef0ace9ceac07.nq.gz
    ├── 12fbd8846e81f64ab8d6f5a6e2134e92d9fee935.nq.gz
    ├── 14301f8a037147d8be7e874c1403776c6a96cb05.nq.gz
    ├── 16403ff1b01fefdb765d7d6464a92cb0e49c8f55.nq.gz
    ├── 174bb172f8449ab6bd28dbc19bf87e92ba8c2bc9.nq.gz
    ├── 17b97850e5a71bd345e67a2e0d6a7e1f63169947.nq.gz
    ├── 1c8ea4a75d46248f0cdf3a863b3a6776edf043d1.nq.gz
    ├── 1e51cbac3a59813a16aef7291535056cc1918b12.nq.gz
    ├── 1eaa6f8088634ef5fe6127091f7a87865db705ab.nq.gz
    ├── 208acdba28fccc99de375cc6a46c3e71e40f918b.nq.gz
    ├── 2259858d4c5a1cc5f7f3a51a0ceda933e9f1405e.nq.gz
    ├── 24979ae52a225cb752841d0e96dcb7cd0876fc11.nq.gz
    ├── 24b0f5f8c88733271f603a4bcfa980665a3be403.nq.gz
    ├── 24ebb04d991d1ba9329b839ab2d58dcf960f5fbc.nq.gz
    ├── 2690d83e392115faab5a1bd892a37b7d82538821.nq.gz
    ├── 27db46a9939c5c35b462ac93f32d4d112924d39d.nq.gz
    ├── 2a2793e2a10e82b8ab6fe77169f8cc4ed80462bd.nq.gz
    ├── 2a994b4b711d65a0c4e6b67076bb65ffb8852c55.nq.gz
    ├── 2aa9702398dcdb60d64c4f74b2259a36489bc2ab.nq.gz
    ├── 2b82a5a8e2058f3434f7105d093faf5daad8f779.nq.gz
    ├── 2bf094966f87b128fb8ea2438dec52bc3c36b208.nq.gz
    ├── 2c0a6daa84efad5f24746e93d7caed95eb340204.nq.gz
    ├── 2d1bcff7ca0ed6c77fdf1b016986f9137a43d31a.nq.gz
    ├── 2f500bec6c7cacdd595595a2c7149cff0fca6b81.nq.gz
    ├── 300b068d38cb695eea2524a5db874fbc1b662d9a.nq.gz
    ├── 30315d107d674eb3313693aa50198dd40283ad20.nq.gz
    ├── 3191fd27e351129b0a0a723b9ff8affe13d240af.nq.gz
    ├── 31b53b1fc1cfbcffd97d7c8591adf56c5687e6a7.nq.gz
    ├── 32b6e7332293c9ff3a076ce9bcb1ade42561b117.nq.gz
    ├── 3408124a88458074cd5b404c87f63ee7f3c9e61f.nq.gz
    ├── 346d7a7a2d0dcbd11a468a25aaae619894bcb53d.nq.gz
    ├── 3565e41dac192a09a1310d052120fc55a9fa8084.nq.gz
    ├── 367c06b77489220c5f493072d1c413126a7ac07c.nq.gz
    ├── 3732f22285f390ec9a6e1873d378c179c1ab8525.nq.gz
    ├── 37e0b76725cee4ce8e9ed7ba07410713f13bc832.nq.gz
    ├── 3805bd9bbf9dfaad0e07ed55e318754bbcaee34a.nq.gz
    ├── 3ae0f1a17466309540e312fccee64c25b062bf2a.nq.gz
    ├── 3af72ca922ebe5cc022c45ca6eb937b7d97780bf.nq.gz
    ├── 3afcb095b7106f60c6194b4cde8721e50ba0fe63.nq.gz
    ├── 3ca956031193891948733f2235a9665399b6d62f.nq.gz
    ├── 3cc201dd2d8ed6acaf5fb0918b9f6a476555e6e2.nq.gz
    ├── 3cd2d8befd289f5405600699909cfc074d7bdf09.nq.gz
    ├── 3d6b55cd37246ecff468bcfbf745627ae5838b18.nq.gz
    ├── 3d921b87c97f82a79ae800ae265cb818b8541566.nq.gz
    ├── 3e510c78ea971e4cef85994092f15162a41795c3.nq.gz
    ├── 3f3f57ff39432a80c15dabceb99141bc7ec4318e.nq.gz
    ├── 4010034aa7f75bd657fa3f7cf9a6c050c58f1fe8.nq.gz
    ├── 406e083276450202f58edd297ecc019813f164da.nq.gz
    ├── 41df4785df492edd88d71c655882120391966f3e.nq.gz
    ├── 421de60545b281c9b54dd8401cd18703ceb81c38.nq.gz
    ├── 4347e9538d88bc0dd632ea6547712104aec7403c.nq.gz
    ├── 43de4790bccf406e71249986821e8a8e4e0e4474.nq.gz
    ├── 4459e7d385b288a3ece3680d3b25f87a204c2c9b.nq.gz
    ├── 4537e2d989843ae1a96a0548aa0a7066a22e2698.nq.gz
    ├── 45f5f4096610671a9069792dd349a1fef352f6aa.nq.gz
    ├── 4675b84605a355c9719a1a05d4cd94957ffb74da.nq.gz
    ├── 4725e93b87ceaf58fb9ae854764536050aadac75.nq.gz
    ├── 47dcb736dc40b3dadc0787cb999fe3c7f82853a9.nq.gz
    ├── 48accb0dd1b025cbff25776b6160e874d15e4f77.nq.gz
    ├── 497abe02c6ca1384e16f9751292b9734b89c83ce.nq.gz
    ├── 498bfebe155d58d386ee9db71879d1f87653832a.nq.gz
    ├── 4a650b1ad5f1880433c77d954d7b351b98d4fb07.nq.gz
    ├── 4a8b841c2bb765c731c7d8d53bd954d642712b49.nq.gz
    ├── 4c0f7989eeed3e0c1e4107f1fc63edc7f3d8c908.nq.gz
    ├── 4c3eb8824d2a2bd0d9d72c5bff9916e17328c0b0.nq.gz
    ├── 4d297d82e83cfb023968e6066672e732c886fed9.nq.gz
    ├── 4d9bf0d154f4c1ae6eb0f9dd1ab74c834d349c93.nq.gz
    ├── 4da9f5f29399702e6b25b7b95e8e254c1266d01d.nq.gz
    ├── 4e620070531632ef09b5ece9223399e1013bf8a6.nq.gz
    ├── 4f50003274ec8616b99e5ef185ebbac1b292107c.nq.gz
    ├── 5019f5d82ada38ef968c5825cd295eca68517494.nq.gz
    ├── 505ee686d3892cda9d295a5aecc7185dbad12df1.nq.gz
    ├── 50b6ae84cb31d5dd4baa153ddfeb8c790fe2b977.nq.gz
    ├── 50be7c20e31659be329f9129d4d205cdbaf79553.nq.gz
    ├── 537069cef0a500b55168a7d5286dd085679d94fe.nq.gz
    ├── 53a05af73fec2eee36c1b8b82a2bc5a99abf7296.nq.gz
    ├── 55f0a96b4deb7f59a5c9271b89770bc04a568dac.nq.gz
    ├── 564beac3c732b2997fe04f1ed60a01e95554fc5e.nq.gz
    ├── 569a5d35ff12a8abc43a6f3f9ea3c55d18fd2010.nq.gz
    ├── 5a455623a4a49f2eee1760398fabddb3cc207501.nq.gz
    ├── 5a739bc20f465c64b165c4046c04d5fbebe4319f.nq.gz
    ├── 5aaf4dd7ccc3730d84bef9ad3db8de48590dee33.nq.gz
    ├── 5b46a822610b0f49bad2579cbd0ff8bfbb80d0fd.nq.gz
    ├── 5d09a8c242b3f3dc4d8a00fe31a4776544b67684.nq.gz
    ├── 5d1e28aa45b033e1c878f2dd24277d916efc2737.nq.gz
    ├── 5d8df735432c484a620832b10305a21ef7abf2f7.nq.gz
    ├── 5db2c2555e9f24d0bedcbdcac34a64149a7aa65e.nq.gz
    ├── 5e3d7aa29c7467ced01319f787885e50c2fbd5c4.nq.gz
    ├── 5f365fec29227c39917b89c4ec27db5643d97b42.nq.gz
    ├── 5f3c024314fc05a49bed12fa0ead1a2765612999.nq.gz
    ├── 60acb63ae582bb88c07f302e826205f589a0ea66.nq.gz
    ├── 61217f7b936fa1d26d5dac948af66354ccc26add.nq.gz
    ├── 616d6ae4fb76c5f637227ace9f72069745a39c4b.nq.gz
    ├── 61a1315b44dbe946a2dd577bfb17332b5767fe54.nq.gz
    ├── 6285ff33c5c0b9c63c92e526486d410d97d233ac.nq.gz
    ├── 62ba83bb8ff3df7ac8dbcd50b7a1c9850bf058ff.nq.gz
    ├── 62f4eb9ba72fc30a38610b293b0147596942b4cc.nq.gz
    ├── 639b5536cf490b7a1f82bf079afe42e7b1334712.nq.gz
    ├── 63ea4d65e5eb4dbc9af823bcd8e57a50a7221866.nq.gz
    ├── 63fc57a851a1800a7591fcdb1b244e738ccb4dde.nq.gz
    ├── 64745809a388f4642e409a642fdb7baaeff96a20.nq.gz
    ├── 663a22446561d6a559c17cdd955ead78fb50e71b.nq.gz
    ├── 672be8815805bfbf77b9035a53e65464904eba23.nq.gz
    ├── 69b3041564cf7e3f9ab7b815656f480c907d30b7.nq.gz
    ├── 69b9dde5caf1ce00d3feb3e9bb160e68209e4de4.nq.gz
    ├── 6ba85df0765285e0bb819f2b3b9c735eb33419be.nq.gz
    ├── 6c2d2421f959f7917cc1b090054b2602c6de7b01.nq.gz
    ├── 6e97f15d92b7313b6e536ff68491d4871f3011d8.nq.gz
    ├── 6f3dbc53b7171daf84033ee8bca45a7308c6594b.nq.gz
    ├── 707b12239fe1a9f3e7eba3d5291d58fc1ce83162.nq.gz
    ├── 70a6079bcff5fe41e713392a84e6d4f8fa6ff9b3.nq.gz
    ├── 70e4192ca2359b120bff83961320a88749c71163.nq.gz
    ├── 71687f73c4b77b0ffdc00c30d727930ccab87abc.nq.gz
    ├── 72878e4612f20b6371fa7d8420e9eea930e2baaf.nq.gz
    ├── 7302b40e874f47e6112789b61eec955098b3a1fe.nq.gz
    ├── 74402f1565f1527df9790b7bb2e22c8c989a7526.nq.gz
    ├── 74f2064399468f5cdfd28dfd8eec73f83afdf467.nq.gz
    ├── 7970ab5adcf0ed8fbad60ff7a4e45bcbcf0af3fe.nq.gz
    ├── 7a661305c5eeeb698696495265ba123965dddb21.nq.gz
    ├── 7af07093daca0ec503321dda9fa7798d0612dc3b.nq.gz
    ├── 7b321e862a207902abb9d186cb0be489cc1e162b.nq.gz
    ├── 7d220e20b927e92184c268e3cbd545fa711f97f3.nq.gz
    ├── 7d53e20a24c1527f477c7732c3455f059323cb99.nq.gz
    ├── 7e6825a7dcd0d1d6632eee2438e08bcbfcca41f8.nq.gz
    ├── 804bf5b1206144273d96b9e6a2299da00405e0fe.nq.gz
    ├── 80ece56b2f270255dbd1f3c54cfc3d580a95857a.nq.gz
    ├── 8167018cd005ff4a24d8287c620539e23c69aac9.nq.gz
    ├── 857397d3e2ef822cc29cfcf7ad46f91aed5e2509.nq.gz
    ├── 85a90f6c92d3e4e0cf219eb9ea28420a72f8611e.nq.gz
    ├── 85f993d2a9bf57c60d3d477848a94e01e243f9c9.nq.gz
    ├── 8886a678e5ef8f3cd58236990733b6be52d82bdc.nq.gz
    ├── 88ac6056a67ade26dde04167da4d7dd77c3793d6.nq.gz
    ├── 88ce357803bfd19e08e9417012736c1f8550a0cb.nq.gz
    ├── 89a89cfcfa05c946cb57d2c88c823858985b4e4b.nq.gz
    ├── 8a57e46029186e06339e6b29db379d133b52ae0b.nq.gz
    ├── 8a6a10cd193c1ef27d6f2b6651109f99bcb6116d.nq.gz
    ├── 8b84a7e001b1e25aa3c7d1d85d321365acbda979.nq.gz
    ├── 8bf931285d030c07c4d0407c01c66cac21dc1dac.nq.gz
    ├── 8c8f39e7042a594f0f47f72634510101abc281cc.nq.gz
    ├── 8fcddea8e6f397c6a9d96b3329cf93f352ea7844.nq.gz
    ├── 917ab4af6c6b4ce6cb37c333250dc037392c84f2.nq.gz
    ├── 9211604224835060dcd4e81f04797ea4dc01d949.nq.gz
    ├── 93d065360086df70b785c9c64d0f60c4cc4e093a.nq.gz
    ├── 946e4873dfa3d3488be62dd4dad55e8cd7d4dd51.nq.gz
    ├── 947197851dbc6c39b9cd8b9ecad4a00d7171509c.nq.gz
    ├── 94b6384dd241cccdd0507b0df16f8de152e2159b.nq.gz
    ├── 94c02dce57ba13180e1eb31b657bd4f2bb920668.nq.gz
    ├── 94fd72ba5f82ac3b9f0752bf9943d5865ffac91d.nq.gz
    ├── 954b4e1a933a2553df5a9ce05752f33a4e0a781c.nq.gz
    ├── 954ec0a2136514a232510d6572e1f72fabe82066.nq.gz
    ├── 9580b298875c04e40d5d748408801697059cedee.nq.gz
    ├── 971556a20c92dd6506d0a8b91a198cc2afc77dd1.nq.gz
    ├── 979ab22395f6f61e7d33c132527d8eec46818950.nq.gz
    ├── 9884b44449dd383c15871abf6062b79015d91178.nq.gz
    ├── 98d98457ae5fab03544a1e292349c76236e17d3c.nq.gz
    ├── 9922893e4a70361d7e4e0412a76166c7bf9645c6.nq.gz
    ├── 9abd3d15f8e9ac2df2c55aae6be4476351c8bf19.nq.gz
    ├── 9bff5b868b8e06e441fa560ef5d45585be0751f2.nq.gz
    ├── 9d37fc827a01fd187b1d965d351d6beea501dfc7.nq.gz
    ├── 9ebc24617602b6f79b29d7f43d71d942a7a432b6.nq.gz
    ├── 9f4cbf5f7488f9cfeeca1944e2b7063fa022894a.nq.gz
    ├── a035127ef13079c5bcee0a1c3eae270e53b7d772.nq.gz
    ├── a036d0e464f537cb7aac50d037ec490e8b0bb988.nq.gz
    ├── a05282089756c9e2035d7b916f1efc57d18e35c5.nq.gz
    ├── a06fb0b8d4ec0047001b51646b787187588d608d.nq.gz
    ├── a227cb12f1dae5d751fe3db8335918f3f7329244.nq.gz
    ├── a2cf3fb19d77af4f4bcc70b159dee0d638bc7342.nq.gz
    ├── a480a35d65d474cf95a330ef8529ce5db6042de9.nq.gz
    ├── a86323649a4b56416010db33a0e159ba7dd075a5.nq.gz
    ├── a8c1bdf4df770ad350f648457ae14a7df37b0664.nq.gz
    ├── a97ef7f7c080a386c866b481fb93e97818408d0a.nq.gz
    ├── a9eec5ed7d360b4d45ca321c9980fe5b1854c9bb.nq.gz
    ├── ab255087431725b5ae37c0fe279a6572f1064252.nq.gz
    ├── ac9e186b47de1a453b35e2d8d3e1c0c1b27f0756.nq.gz
    ├── acc8b6052fcfda3cf9b6cc39d69b5eb140d55f1d.nq.gz
    ├── ace499a338f7a33004eea46d556316504a6d8424.nq.gz
    ├── af31cdca86a28864a4c3b0518fb2a261c5384897.nq.gz
    ├── af6730eeae87ddb7b2f523540ff90754fa6d3dc6.nq.gz
    ├── af7e479932e6eae76c6026a747ce463cf81902ae.nq.gz
    ├── b056811a14f42d11044556dc66dace0e1491aa2e.nq.gz
    ├── b1d6bdb9e342305ccd99d4c045bf3e7e3385e5c6.nq.gz
    └── b1f22718b3d2df34bb29bc402ddd0d6c3c4bebf0.nq.gz

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

[jupyter-server/jupyverse](https://github.com/jupyter-server/jupyverse)

---
*Parsed on 2026-10-15 by [repolex](https://repolex.ai)*
