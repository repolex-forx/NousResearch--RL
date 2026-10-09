# Repolex Knowledge Graph of NousResearch/RL

RDF knowledge graph data for [NousResearch/RL](https://github.com/NousResearch/RL), parsed by [repolex](https://repolex.ai).

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
rlex download NousResearch/RL
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 3069f2817e3000918f2665441287b3d1b7c39938
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 3069f2817e3000918f2665441287b3d1b7c39938
│           └── chunk-001.nq.gz
└── blob
    ├── 001c82cfd6cd63badd37dd4946570e1131f72717.nq.gz
    ├── 00ac1923a7fb6691cfc24ec1e1b51b32ba2c450c.nq.gz
    ├── 00e47fac8102af28ba8fa1d791bd2f2236027b34.nq.gz
    ├── 00f4082f4e3823ee863b7a8662f21dd92bab6d79.nq.gz
    ├── 0165c86cc373f7f9220c7c220e9da99abe776378.nq.gz
    ├── 01ecf48657bbb65235500e94d78d7df09acf0510.nq.gz
    ├── 023083c441370058ec62f4df64f504c3f3aca56e.nq.gz
    ├── 02dea5a4a53c1241a05e546572f5e1a023ec2e0b.nq.gz
    ├── 02e43ae65930b549acfe7fa3602504de68cf3441.nq.gz
    ├── 037b4880f5f3c6b37e4735ebb1cfa36595890866.nq.gz
    ├── 0391d117f3022aabf738db96c252a30cb1949272.nq.gz
    ├── 043b4e89c6d4eb6de99647189f73bff66de8b043.nq.gz
    ├── 046486408785e740f1f7e814d094c05a7d04757a.nq.gz
    ├── 04ea20d55368c2e469f7bcef1b1ea648041094ff.nq.gz
    ├── 0513ec9760ca5681e85e6f5ba8183e22f2f5c3d5.nq.gz
    ├── 05cdc399eec7d7636a9d6b3b8abe9a181df1dd18.nq.gz
    ├── 05f0418444744062535083f3058138645b20a6d9.nq.gz
    ├── 05f55d8862c6dfca31166813198ae02fa56dc683.nq.gz
    ├── 0670e917d734e8f6f63a0443cfacc23d7bd755a4.nq.gz
    ├── 077102dc98086d78d41b55c1c36d2d02b891e061.nq.gz
    ├── 07b0b055761ea00db1d18931195e602d1906174b.nq.gz
    ├── 07c02121a7db1a86280d3f4f09ae39234acd09d1.nq.gz
    ├── 08508fee1422fa5197a5b56f4962b1ef7637310a.nq.gz
    ├── 0880fcc6f6549b2f09aa79f9a8cbe7d3a1370e98.nq.gz
    ├── 08b9e85d075a36767a14fbf378d247ccc51509ae.nq.gz
    ├── 08cd5bcce626adfcc8aef7b745e6886cca157a12.nq.gz
    ├── 09d2cf766a7a979c32376b016514c94c5f9d6efe.nq.gz
    ├── 0a57482d688f0ff8da2d59d5d0ecae117f674dd7.nq.gz
    ├── 0cc99b6522eacae0d2bb820b09a7d2d66821dfee.nq.gz
    ├── 0cddc5c95d6dc276ef03d3432cd9780150e8ce76.nq.gz
    ├── 0ee625545aeb425ce5c3408dc78d679597e07f12.nq.gz
    ├── 0faaad17a1bf2917f0627fb3822dd9177ca48bda.nq.gz
    ├── 0ffe32ddd50bda69950d9e9cb129efbcc0946127.nq.gz
    ├── 10651c8490be02296bc1e53e958b12d36ac67658.nq.gz
    ├── 106a6aee3f1e1ee6c0f5a5f1c7b0268d6d52d042.nq.gz
    ├── 10ff34699ced783fd1754951ef0135520db140aa.nq.gz
    ├── 11d8b7602ad48d2c69da0c49531ac0138a99d0d8.nq.gz
    ├── 12206979df078b224bdf4e4e5b398cd55a5a10ab.nq.gz
    ├── 140a648733e5468a22a27fa401c212dea5f1c1be.nq.gz
    ├── 145e6d151bb119162f6e58cd01d8f6f93b0e731a.nq.gz
    ├── 159d4d1738fe8bfa79beaf3943775faa3fd3ec1f.nq.gz
    ├── 15c2944fa65cd9c53dfe911071f5169f01ba018d.nq.gz
    ├── 15ca65c8f91bf398351b8f9b3c44fc1e36e02a20.nq.gz
    ├── 1640deda09ad915ec878327991d385c073513608.nq.gz
    ├── 166fab0a5a3126528beee9c253b3c30275975511.nq.gz
    ├── 172009b3fa34f90c6a34618a5b8da1dc9bd0560d.nq.gz
    ├── 1825877a9e774f4771bbda7602eae01d9adbdecd.nq.gz
    ├── 185b6e0358070dd434f6a6995546b51ccb731b07.nq.gz
    ├── 19c57152216fb9454325985df72c7086d96f7f18.nq.gz
    ├── 19e7a86d6a84d1d41e9e29d3fca39f971b3e18e8.nq.gz
    ├── 1a3bef0bee69689608bdab3f1702fb014ea5cb92.nq.gz
    ├── 1a9f574ea281b9c5af677fabac1031fa71e00ceb.nq.gz
    ├── 1b954d63161bd48cfa41cbc1b7bc28d8c95f8b10.nq.gz
    ├── 1bb444011ffdd5c033e8514656453c850b8b22cf.nq.gz
    ├── 1bf5502c2186b73cf181bbe47cccf027d017ca57.nq.gz
    ├── 1c9edb17eb9b0ea1f8ad2fe7aad6b543e51b401e.nq.gz
    ├── 1cd7b4740f77200e6bd95f04b79017a6dfde8f73.nq.gz
    ├── 1ce72032036e0e4c012b8967a26074e428dbd1d8.nq.gz
    ├── 1cf031015740000f114b11fe6dd11243e5b4a6e9.nq.gz
    ├── 1e1e249555a422267ca7c1767409556c4cd4ddab.nq.gz
    ├── 1e27d25a2feb7d8d8ff82b7413d6169c7f5c293f.nq.gz
    ├── 1e912de1303fc546c471ef93503157d370020034.nq.gz
    ├── 1eaff3534e3cd1ad4cf9277c1c004160df3b449a.nq.gz
    ├── 1ed9aefbafa2cd7a1f46202e37471a489befccad.nq.gz
    ├── 1edd0480a7fecdcf85f9f0be334332faada19b81.nq.gz
    ├── 1f918276cdc405565d7ed811ab084fc899101869.nq.gz
    ├── 20c5e294796bdee06b06e022a004ba544f3008e0.nq.gz
    ├── 214bd905724943418d6778f583413b1a0f9dc0b2.nq.gz
    ├── 2192425922c27f9cf394e73172f89f7517d6c31a.nq.gz
    ├── 224c96983a701a48172be72c1e17ea4111aaa17b.nq.gz
    ├── 23abcaf749282fd7bdcad2ddde7737945892a20a.nq.gz
    ├── 24033e7ba0da1510c91bc1a9d86e9d5a670e47eb.nq.gz
    ├── 25e57bb46bec3b554f79fd4b4c87ca624cd58ceb.nq.gz
    ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
    ├── 26fb1cd4968424024e4f7b5f4a6896566288f62b.nq.gz
    ├── 2719decce6bcb6a45a0d31da62506f66b5bdcb67.nq.gz
    ├── 27bd4e3b99adcbab50d9f53d7eb53a473460e68e.nq.gz
    ├── 28ecda18693026faedafd7c4221c8afa867b592b.nq.gz
    ├── 290902657eeb6ead1908efc43fc2d9cd006379e4.nq.gz
    ├── 2a235788044d60498fdd92a12cfd2d7f7952c9ba.nq.gz
    ├── 2ae338b11ce7be4befb1d61ad035dac32f6eaa97.nq.gz
    ├── 2b7711210381f980000d539991ec6e5f56d47807.nq.gz
    ├── 2c2d5cc66594e3060253475ad8683d1e4d70fcef.nq.gz
    ├── 2e0ff4abe4769b727c221e850665a13161436f17.nq.gz
    ├── 2e441cdb5ffdf13383a27c15cbdcf950edd8131d.nq.gz
    ├── 2eaa337f1c9e0694808afde54c854a26b12f4055.nq.gz
    ├── 2f14541b6f853a7035f74d85b72b2ef5ff15ba4d.nq.gz
    ├── 2f72b300cb4532fc06372dd4a5ba89543a35d0aa.nq.gz
    ├── 2fa8a8e60431e93652638f66a5bcbcf1fca020a5.nq.gz
    ├── 32a72d2a2c2f3fc2d91ddb636c6cda2988378f4d.nq.gz
    ├── 32eab23433efdfd063f5600a5e0f2814c1663fe3.nq.gz
    ├── 3372796968c1469ae2dff2f083f9b02ba59fbc92.nq.gz
    ├── 341a77c5bc66dee5d2ba0edf888f91e5bf225e3c.nq.gz
    ├── 343d07b49e8c1b0671bf1dbbf5dbb0ce368d9c8e.nq.gz
    ├── 34b6f0b5db7a58f2ae33f4492cbcb98d0c63092f.nq.gz
    ├── 34c71688021eb2ce422758b611f5570e168c531a.nq.gz
    ├── 34fb8e3e95e0afaa00499022fc5308317bf0aa9d.nq.gz
    ├── 353804958e54f08149f1c84427cf4d0c851986b8.nq.gz
    ├── 3599546db387c3103330be7301e12d72935b0e9d.nq.gz
    ├── 36235f98323177fcd04c1f1d590e00c4b4d02f1a.nq.gz
    ├── 362c534b94a770adc2802028268deb81f0e39ee5.nq.gz
    ├── 368774e0ffb7e17009537f1a1fc3453c4c4a6d77.nq.gz
    ├── 37616e32b0f6d0271ddbf1d0ace7b7cd9f4b4982.nq.gz
    ├── 37c36a298bef4b6950ce2ac08fba3d5ca785472b.nq.gz
    ├── 37cf868ad8eaf91e624d419401f6481329ea700d.nq.gz
    ├── 38620c0c5b21b125a9b6afc8a5bda09bb97b688d.nq.gz
    ├── 386263ba3d6168ae3efb7f47369573ea0ce45a70.nq.gz
    ├── 38a806f33c1c7705f415971eb9ace2a66db0ab9d.nq.gz
    ├── 38ea52d74e714738521da92f17f75e2b31a487d7.nq.gz
    ├── 391412b5ed04bd004fb98c8b9ef4786ba5ffab9b.nq.gz
    ├── 391b7f21e9065d1c40b2b1c3292824c5ca08ecc6.nq.gz
    ├── 396530edd7831a5c48dab8321d6b7a4654d96800.nq.gz
    ├── 3ae8d65e5cf955c59c23a3fe0ac2e6dec4653390.nq.gz
    ├── 3b4968fa8f653247314890c7a6cb9a95d5fd0955.nq.gz
    ├── 3bcbb151a9bb10ca5ba6b549d15ba3eb6be3cc06.nq.gz
    ├── 3c319771002e4e9485ccd9f67ae2d1a685f6ad5e.nq.gz
    ├── 3d3ca9b5b4a1b606af282fdbc8466208cb26f4c1.nq.gz
    ├── 3db1458c8b422f608715967d0caf7837a3867018.nq.gz
    ├── 3de66ca181026f1a29dab66cb455f52257d8d714.nq.gz
    ├── 4222c885eb45a6de26fa28496b432b8481bb452d.nq.gz
    ├── 4285aeafc81b118674dd354cde2852d6e0e57142.nq.gz
    ├── 429decb522f68870082afe5bb803974de7aefa9f.nq.gz
    ├── 43608a94026cf1fcccb955aeca499606bcc3273c.nq.gz
    ├── 43be9679bdd5b40a246f3a4c0ee1808b4ad0dcc5.nq.gz
    ├── 4429a148012f3ac3af2cb266848d51a4f6852521.nq.gz
    ├── 44dbe4b337b050dc739e2052bcc52a1d4e00e6db.nq.gz
    ├── 45054aaf9898fad882b3fcc10a8ffb58fb96da06.nq.gz
    ├── 4560faabd04a18bbed488ac21d0f43aeff1449f2.nq.gz
    ├── 4614d61232158353e03711886dc1c7a031ec3275.nq.gz
    ├── 46beb3f92464f2fad1c1fa2bf5d8d642c194a614.nq.gz
    ├── 4a15173e9ce18dcbc2351ce3169de99cb5578beb.nq.gz
    ├── 4a396ca60ba29bc8f200921ebbc7379df4370b16.nq.gz
    ├── 4be7d951177cada1a3b1ac968146245b103071b6.nq.gz
    ├── 4c79a54bf888e9265d81d5d483a3a9b8b4bec944.nq.gz
    ├── 4d012b94b7f4f43444a2b8f18bb962ff0ba9f2ac.nq.gz
    ├── 4d17fdcea30b5320f3e5ebdd2bab4266b0c4e3bc.nq.gz
    ├── 4dc98db94a2353b3b1d0437adbb580e90956a8c5.nq.gz
    ├── 4e51a6efadae6bfcdf5a722eb7b7a4e961c2fac6.nq.gz
    ├── 4e80414f8d6377ea7b979a59b6a588699e9094ad.nq.gz
    ├── 4e8ac9ff97194e752e304dcab67769076153541b.nq.gz
    ├── 4eac23c40b1864d6a97a43bb23a2cb2985dcaf00.nq.gz
    ├── 4f49648476a1769e80ce416fccd3b5e167c12636.nq.gz
    ├── 4f8a0a03bb2f3e4f3e44873d26039564979f81c8.nq.gz
    ├── 50a83b78141867bf29312163f0d2ca5997cc4b4d.nq.gz
    ├── 50e7c3950f4f5bc1cee01a1284731e0fe236103b.nq.gz
    ├── 52869bf04d26ce9fc79d8493acd787ed00350535.nq.gz
    ├── 5332f7835fefebb44220595b64f231ba46327824.nq.gz
    ├── 55589d5c7f9c8841fa52c51daa392e77571a45b1.nq.gz
    ├── 5861a44e7272f87fce8130ff11a1703fc02eb2e2.nq.gz
    ├── 595654a3a36e74b7a30d8770de342624b988a741.nq.gz
    ├── 59bfba45328f20c49cbcec1b44a24a6da1be0d49.nq.gz
    ├── 59cee6f24c2103a9bbfc53a1c0dbae8b690f9246.nq.gz
    ├── 59d9aec69e8282e3a83e880a71216f881dbe08db.nq.gz
    ├── 5bdb8c6b282bc2b0712715d33d74fbab903221b0.nq.gz
    ├── 5d1c236584da6cbb3caa6b9efc172836d01b140e.nq.gz
    ├── 5e5fe4d0e1096a619feb6968e12759ed751ba2ca.nq.gz
    ├── 5e724bc7be7d45fd72bef6b6ce6bbe949b71fbaf.nq.gz
    ├── 5f1ac014fce7c3a0069f787727c6f1bcf039178d.nq.gz
    ├── 5fbcf8e86e3e6c89f1c91e186ddcd7f0a32fc501.nq.gz
    ├── 5fd0b40eedb14bd3555ee5c4927017ddde5989e4.nq.gz
    ├── 60e61e808880540f21df359357596f715179c381.nq.gz
    ├── 6135f42da79cd9b20da72dadfe7e888ee9096543.nq.gz
    ├── 61a80dc2ab4291158f15186a8b829e0fb0493ee8.nq.gz
    ├── 61e4c5f7b2c8750e4544d17fd3956ce4711364e5.nq.gz
    ├── 61f41f222099a49d058cfdd80f4a35e24a986f58.nq.gz
    ├── 6237b9f634e48dcef70660e88dc8e88cf35ace9a.nq.gz
    ├── 637b1e34d174bbd799182c70e60c4ab2a21e786e.nq.gz
    ├── 63abcb264284103171da62f1993bcc079d0800b1.nq.gz
    ├── 64421f7cb636cf3e31ca094b04a60b04fe9a4213.nq.gz
    ├── 646c88faf902d79db5d6558a8876e06dbabf2364.nq.gz
    ├── 64c7fc85f2fe9bdfa494b4622311ed179a2a0377.nq.gz
    ├── 65613412eeecf76c843f33893212ee4358b0c7cf.nq.gz
    ├── 66a18fcd4025c3e86d60ac6a491d1bb04ccb7dff.nq.gz
    ├── 681a0dcc00167a15fc5889c32e38e4d4a9850592.nq.gz
    ├── 689a79883b9c7e9c0344512bae61efb93fbeaac8.nq.gz
    ├── 69912f209c570815eabfa3465bbcaa47e146b094.nq.gz
    ├── 6a7288ff526c07390b7a52f3a9ad80e0a7732210.nq.gz
    ├── 6a9018cc20623c446882c73658ea99992f63fecd.nq.gz
    ├── 6b3f5673de1a0416bec38cdf53cf4a26243f286c.nq.gz
    ├── 6c0b52c639bd1e017bc20ff74fac3245bc2a9423.nq.gz
    ├── 6d321bd32aa3df36c407cc277f62ccaf21d4f2a0.nq.gz
    ├── 6d65b33ac639617ebb4e5221dcab6813de0bd812.nq.gz
    ├── 6d8239f1627e2957a6efb55afd36b148fcfdfd7d.nq.gz
    ├── 6da76d04db0306c2843b78ee5f26da331da16eeb.nq.gz
    ├── 6e0aa5cd81ca5bf6e26d93c52ebf41d7197f7dfc.nq.gz
    ├── 6e8fceb76036af58fb35700807b08cf47a140cec.nq.gz
    ├── 6eb8ed487201984853e2853c5b2d9f3be8440bdc.nq.gz
    ├── 6f081f3edf35c02ca7bc66815edd9cd5bfa31e59.nq.gz
    ├── 7067a4cd40f0cfa0eb74b7c596dd5064cf482ef5.nq.gz
    ├── 706c1b1cd645a252fa9f525e16becb77aa10b71b.nq.gz
    ├── 70c0eb7ea43db853164129804ab3885ccf45c8a3.nq.gz
    ├── 70c4041d665bd779b554d0a1259100f35e9e03c9.nq.gz
    ├── 71514e014202a82e78ad461deef8ffbf28791967.nq.gz
    ├── 71527d42ef6de0c037ff49a14d1bdb5781045b05.nq.gz
    ├── 71a0447935721433667fe0acd33719d9bb93fc58.nq.gz
    ├── 721a2aabfff3f27d823fc244320b4a54774d8f8b.nq.gz
    ├── 72a645f1fff4419c4aa50e864a15b59f741bbd53.nq.gz
    └── 73cb08f4690d75d1c41eb77cfb2098958f1503c0.nq.gz

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

[NousResearch/RL](https://github.com/NousResearch/RL)

---
*Parsed on 2026-10-09 by [repolex](https://repolex.ai)*
