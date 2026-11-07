# Repolex Knowledge Graph of huggingface/Repo2RLEnv

RDF knowledge graph data for [huggingface/Repo2RLEnv](https://github.com/huggingface/Repo2RLEnv), parsed by [repolex](https://repolex.ai).

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
rlex download huggingface/Repo2RLEnv
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 9d8b155766d85f73da6a0c467aec104c821ac49a
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 9d8b155766d85f73da6a0c467aec104c821ac49a
│           └── chunk-001.nq.gz
└── blob
    ├── 0059cdc7e1cf3d8df40bde57ef4a12ceba32b696.nq.gz
    ├── 00f5d791a93cc9c601b29c84696fe6998cc37af5.nq.gz
    ├── 01038f7c7c5e1eb745b309993b68037cb49ed82b.nq.gz
    ├── 01164965282a55b4141a535dd5ddbd9ddc41315a.nq.gz
    ├── 013cf9c24428427ea255ce554368b3d41c966454.nq.gz
    ├── 017a9e1c569cf4eb7814d107c54c9418c645d399.nq.gz
    ├── 019390629f18afb470f2a406319633645e0a0420.nq.gz
    ├── 01b6122551bfbc6237e3f0126fee9c06b3d31091.nq.gz
    ├── 01bd27bd05e546107865ab60f164c9c95200e16c.nq.gz
    ├── 01d984d89a15e8de46fb1c0019e4b3f321de6aff.nq.gz
    ├── 0265b0bba7f54674457bf9eb2a881ed6f5aee7b6.nq.gz
    ├── 026e0f358b0fa9564067c2e1f9b58cdf48f3f07a.nq.gz
    ├── 02f523fab34766002451a009b884d1669cdbdb50.nq.gz
    ├── 03dd039138323e960c412f3875f64ba62c4ad834.nq.gz
    ├── 04e5895199a86cabba871716ea1792468a5e6099.nq.gz
    ├── 059f051dbfd4ad58a2dc1a30ecf3322124705f47.nq.gz
    ├── 05f6387dda8902e590c4ecdfbf12c12c5445bbe0.nq.gz
    ├── 07ba8919dd11be44c97f83d8079424f19ee74608.nq.gz
    ├── 07daa57d05501605a16c6d0edc8d8fa0c1d73d7a.nq.gz
    ├── 07df8fe50370f3a65d98f972a473d3ec32680b36.nq.gz
    ├── 09082aa6a4d2720e45db46a11d7814a56dc38961.nq.gz
    ├── 093880c29b3c0b28596250283ac1c1f68e298df2.nq.gz
    ├── 0a6ec7c33ff6de18ea31b0b264437d9eb8b7fd25.nq.gz
    ├── 0b64317853df4090cd29c7c420cc22a40f70f85d.nq.gz
    ├── 0c1a5172929fba7aa807987b547f413a8206efc0.nq.gz
    ├── 0cf4b26171c27f8052de0e7bfdf124a091a53143.nq.gz
    ├── 0d4fb75428b9bc4b48f3ff92f565aa8c39b0b259.nq.gz
    ├── 0da9e5e673eef3b671c9afc1963519a8fa486a61.nq.gz
    ├── 0dbe5b97f88b96154ce4c5e6fdd527d7422fa520.nq.gz
    ├── 0e5820795c1b58fe3c0d5544cfab27fa3d3ffd53.nq.gz
    ├── 0e633b459528c273c33ebae7848b13e4c4976b52.nq.gz
    ├── 0e8e41617e9a4e4e05ce3b6b06d4d16e94b26f8a.nq.gz
    ├── 0ec7c3beae4b31ae3150c23fc2fdd7a672209bfa.nq.gz
    ├── 0effe4d827fb675b6dcf816dd67908eeee21db99.nq.gz
    ├── 0f092b97eff4b12be59f068da108fc43e4ead499.nq.gz
    ├── 0f9961c3dd467d760da346c0b2a3e9bf9a11c57a.nq.gz
    ├── 0fea46880a33a28618376ec4909a012745d26866.nq.gz
    ├── 104a5516210fe914c4e0563b95a474db4c5896b8.nq.gz
    ├── 11ff7e6f191f27a64de5989006296c48575ac30f.nq.gz
    ├── 126531687e33b5ecea4c0e449579059c62e762d3.nq.gz
    ├── 131f34472fd706fd90f4d7f5e32b359d52abad97.nq.gz
    ├── 135cd46838908e493064527a18bb66e8b6a30b57.nq.gz
    ├── 1370a0b7823f1f7dd6679081896989258c09bf54.nq.gz
    ├── 14d9b29e66e7081251a93f58fa2821a2cb86a4e6.nq.gz
    ├── 14f979767c9dd2a85f8dd7b32b12a74c968111c9.nq.gz
    ├── 16534ae0e8c4ccc384a1f1588063d4f6af2cef70.nq.gz
    ├── 167e852bd8b25cfc883181dfa75eda3b858eb371.nq.gz
    ├── 16d4db6cbce7c18cfcfd59a22a6e6237f645cfb8.nq.gz
    ├── 17ebe62b35fdcbc6e794dc5d468c663122bfa219.nq.gz
    ├── 18297312828aae9f71c918749da6875fc44421f6.nq.gz
    ├── 187001c97c91f10a9e1179e645c335d65e6b54f4.nq.gz
    ├── 1876833f2e051416e5ae1b2f958722b078086950.nq.gz
    ├── 18f5252979c7ddd07c52544e84c2fce14ca4ae52.nq.gz
    ├── 19330f7c9b4c354e428e9c0c9559f27a26e0d6d6.nq.gz
    ├── 193b24384c59f8547090b40d03ed29666358029d.nq.gz
    ├── 1a32e88de699151953a42e85876d9143891d38ea.nq.gz
    ├── 1bb2f2ca3d6ce02de23fd1720df44af79175f1d3.nq.gz
    ├── 1eb4e2ab41a7b950112f8f0b1fdbe605a00720ef.nq.gz
    ├── 1fe05a2e7d3bbcf8ec2dab8e8615f4d8b482e8c7.nq.gz
    ├── 21d942ec6d11b69940cead60e11ca4fe0610f4bb.nq.gz
    ├── 22509b6a9b218f7ac74a2a259c730d1ddfbc1fe4.nq.gz
    ├── 2350127295f8979239014fd6adeaead582caf922.nq.gz
    ├── 23e3507ae92ffa2f18b578d91dec6513669e2be5.nq.gz
    ├── 2458a4aab9b5fdd9ca7854152c2e7fd78c443d2d.nq.gz
    ├── 24e1abbb3662663c30725557bd8eaefea1798a20.nq.gz
    ├── 24e2dd1229d8a015fb2b4f8d7da9b9b4fc2edfd8.nq.gz
    ├── 256412d7d643f106c23823fcea29cc875b758228.nq.gz
    ├── 25e196f8106c3a4ef971b2c13aadd41853c2e92d.nq.gz
    ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
    ├── 2705350f51ed922f00d30a637c3a599893615c25.nq.gz
    ├── 27237a585f9e686c1e50d02621e886eb5adf81fb.nq.gz
    ├── 28873ad429c7fa0481f981d0fd6958171f083b0f.nq.gz
    ├── 2892cc1825b9841f4ae20add7fcefeb850180d07.nq.gz
    ├── 2981773709e1c2f0c9e772d972e752355f7c2d15.nq.gz
    ├── 2a71ac36b13f35d98a60a69efb64d57f37a411e8.nq.gz
    ├── 2aa5cb33b679a10290b67fbc1955cd4e65cbf7b1.nq.gz
    ├── 2ad7e72e12332fc1afe518de25258c8bbff09c84.nq.gz
    ├── 2b29ab5f7dfba45d16c011b4133d35b6ad67f3f2.nq.gz
    ├── 2b6ead65f59169733875d1c0086cbd57902a9ef2.nq.gz
    ├── 2bbf904387f6213fd980c869169f4715724680a3.nq.gz
    ├── 2c24162361d4cc2f41edf23d419e8b1717644b05.nq.gz
    ├── 2c30bcfa643407a452c08f536782d9a737b06f75.nq.gz
    ├── 2c69284b4973177dc3f0b49243b44c4b95a226f2.nq.gz
    ├── 2cb8924065aeceb020c443744a19880d493a3250.nq.gz
    ├── 2d1f9c3a80d9e90f3211f885db20a476dc862da0.nq.gz
    ├── 2d22c244ac6f81c8d9c29f5a0162bd8c43bc6868.nq.gz
    ├── 2d2e770597e683b9141af3b2def849bd3d47f518.nq.gz
    ├── 2d936d7cb7fee076152baafb2c61c2d016db9efd.nq.gz
    ├── 2e8215d6f99bb6f7e20eeb546245b93db12ae4bb.nq.gz
    ├── 2f28e5fa9ceeb7a6c60fb515220d528684e1a5e8.nq.gz
    ├── 2f357e8c6c015a3c0a3abe2934c523d1f1c84746.nq.gz
    ├── 2fee467ec5004009b1994ab17249bb7d468842b3.nq.gz
    ├── 30384e281227a8a76617b57bbc5fe331b23cfaa9.nq.gz
    ├── 304720dc487dffad22ad98c3fabbf5956850f04c.nq.gz
    ├── 3132094598418aeb1a7d72d3b9ebf97f22a3917c.nq.gz
    ├── 31edd90039195674c517cf40b5597aec9c4f0f4e.nq.gz
    ├── 326a09a03ab11776d4db8205be67be8500b871d9.nq.gz
    ├── 326ce92010b52cf0f27bca64838f506382b22557.nq.gz
    ├── 3289aef500dc2cfa4d9f5629935953b040095ef0.nq.gz
    ├── 3291b84e595205d2014ba279bfbdde9b8542c17a.nq.gz
    ├── 32f21e65c3df887f06c8ad8a0e218aa65301c501.nq.gz
    ├── 33ee544547d4436e24fba67e283c999f4a313ff0.nq.gz
    ├── 34901d88060ff0358f8cda50d6d61620c026dbd1.nq.gz
    ├── 34dffdbd329145837d37a4d8d492834a103a66d1.nq.gz
    ├── 352e8559b088f2a1810c678fbeb7949c20cb5a8b.nq.gz
    ├── 35cbe0f73c52b3df5230dc4a3c5b75ba580ed550.nq.gz
    ├── 360d2cdeb27a45157c48ff4fe9c19e621ad09f5b.nq.gz
    ├── 362def975cb4fa697667cb36526345bed22e0fa9.nq.gz
    ├── 36ec3866e0971e7be0e233c171d6e256e6e06e60.nq.gz
    ├── 3746d2ba8530eeed90d4d764e6ee3321412fab6a.nq.gz
    ├── 378caf6836dbe4d18374b3480359d28ef2351368.nq.gz
    ├── 37fef7b710010c6a987ee01ca36fa698d92fdfeb.nq.gz
    ├── 38671500218c6c8b51069daa0debd1cac85c4c04.nq.gz
    ├── 388fb80066f50d29ddb130b55d7f32375d65d33a.nq.gz
    ├── 38e7be829e4039585ae456ae1c37c8d24c100dea.nq.gz
    ├── 3a5c9848e5a19c4219f6c2d92dae2f1676bab147.nq.gz
    ├── 3a6d7ee22ffc664140c8c01efca69a9fa1644fa5.nq.gz
    ├── 3bcd3cd37629d94b272e5698a2b1fb6ece143e7e.nq.gz
    ├── 3ceedb5821b25ca98efda7d9f89af7beceafd39f.nq.gz
    ├── 3cff0d770de9d54299b50e57e36cd455dac7d0e8.nq.gz
    ├── 3d6b375e2a6f8be78074e8e849781d47622283cc.nq.gz
    ├── 3dca5130df070421e078c377eb92758bcfa23304.nq.gz
    ├── 3e0131e88a83944787181926ea8021c0aaa83b01.nq.gz
    ├── 3e0749cd114edf6ff4b87134df550e81b8532ad8.nq.gz
    ├── 3e6b4e1bed1efb1ea2733a443f9b3be745704a52.nq.gz
    ├── 3ebdc5fd0ff66b2e67b1a642e819fd1e0d3a0bc9.nq.gz
    ├── 3ec4409bc38757748fa513b2fc6933b769c551d2.nq.gz
    ├── 3feb81a0881c29bbc3869da15878380099617c36.nq.gz
    ├── 40234e10f8a86ed258ad0b920b1b5bb76ed81633.nq.gz
    ├── 4080df83f2b066f4a744717d578afb16e7185f06.nq.gz
    ├── 40ef4b450d635b27cbdc8c5b7b2175907dff3f71.nq.gz
    ├── 413549bc3b56ff60a8ff50b76b58f9decc53da42.nq.gz
    ├── 41b3987937330ba58ba91da6081644ecdb8d2fc8.nq.gz
    ├── 42085260ed879c721a446337870ab514a578b7fa.nq.gz
    ├── 421c437cdcba0e0a0f11e32e34ddbbc150560c6d.nq.gz
    ├── 43775f5fe8066a6bfc92ea6352fc19cbf2e52331.nq.gz
    ├── 449d80bfe89d1d2521f2380e8bce5ee878b27f9f.nq.gz
    ├── 45245d43f29b7d2e6a92dc7fd0b7c6e9ef44782f.nq.gz
    ├── 4581f8773e7cb00faf5e14c52efa216e4e69867d.nq.gz
    ├── 45f8e02fcd7f44fbb9379cbe3378c2c8fa7dc7f9.nq.gz
    ├── 46504f4af3269e5109ee485a1a09e4ab81070479.nq.gz
    ├── 46bb02f56665ae95d3e8f6c579dd451a59b67731.nq.gz
    ├── 473ac8aa872c21f8a54b5a8f1dc617255706cb2c.nq.gz
    ├── 492c346bf89eaa705542a8a05a8c704b8a84f82d.nq.gz
    ├── 4a5ab04ea809333f5690ec8cce10566dd4350977.nq.gz
    ├── 4b4ce5941f2f50790e0da374c501228e16c8853b.nq.gz
    ├── 4c18bb27c0f662eb21820b2c1a872aae7b55e408.nq.gz
    ├── 4c7cf70058d823f3f9a9b4d4d32e93d5e30e719a.nq.gz
    ├── 4c9b0a55d4bd9cf35b6e230defaa4d4b9f24290e.nq.gz
    ├── 4debf35ce8c376ac556cc2016ea5a9d8b70071f1.nq.gz
    ├── 4e20f8d1adb61a23f4df429e4a8620818e196e15.nq.gz
    ├── 4e87e953ca4a91f9c9ba4b02ba6535ae4d97153d.nq.gz
    ├── 4f6659e12adf47f6349263c1c20895d17dfc3979.nq.gz
    ├── 509e50c52451cf40848352431f1bba24a428c471.nq.gz
    ├── 51b347616a35b4185fc482e3f57c27be20db595e.nq.gz
    ├── 51f313a057ddeeb77c461f914eef84836cc6778e.nq.gz
    ├── 52108d740d2e2adb8c87ecd58e9526d47862e04d.nq.gz
    ├── 5215cef20b4726bb9446efda9efc5ef14f1d4c6c.nq.gz
    ├── 522282b2deed0c2bf4080894283e64745acccef7.nq.gz
    ├── 52508e8c7c5da42e9e5022e03713dc73547b1080.nq.gz
    ├── 5304f4ace52087fd2c152ad2d6b27703700daa31.nq.gz
    ├── 5374e258c242c79cec798a2be3a994f1107f336f.nq.gz
    ├── 53edea05d1341a8e7c8861e8be1530b34c92f8df.nq.gz
    ├── 543591b41653ad7c868dbf78eb8fae8fbdfb9754.nq.gz
    ├── 5486d71821affc6756da69f78776f828e0c2cebf.nq.gz
    ├── 55470980ce9c7fdd5a1f3ff67a04720da6b4d5b8.nq.gz
    ├── 55bd857bb335c06e02d9df1b3dac8f7ea096d88d.nq.gz
    ├── 55cc763673c2a65bc38db2e16de9ff03c05591cb.nq.gz
    ├── 55e0b8478fde3b83ea706785776ddc53e56ccac9.nq.gz
    ├── 560709614b2fd8d4d746be4b70342da2b88f0cf8.nq.gz
    ├── 5664f3d0abf98c7ddbb17ba4bf9435e847551501.nq.gz
    ├── 56aeb56fceb010ec5acfc253b5d7b143f13f5cc2.nq.gz
    ├── 57639e421d5fa65bb657b9ea56aa342ca7d464f5.nq.gz
    ├── 57b0fdfd7e179f9c9c05b199532582c729be1b1e.nq.gz
    ├── 5873d3e52a46c2410339e4e79c80922d3724423d.nq.gz
    ├── 58a38b9e0d5a20192e59d872423324ca9da1d617.nq.gz
    ├── 59fd102d63005af57b3279a9a85168db0342f57b.nq.gz
    ├── 5a57c3d9ffd1ab37721e6fcda04997cb6b5ef058.nq.gz
    ├── 5a67bf3b02f7285bc70e02ea19750a95695a7173.nq.gz
    ├── 5b3ed748f61fd3d1aea75a4c412ec434a21a7683.nq.gz
    ├── 5bba7dcfbf9766362eae1f173a8d003455c3d1bb.nq.gz
    ├── 5d5d0814a980f14c9a1d4994e1118c098e9d0edf.nq.gz
    ├── 5e6de6effe3c8a52363834639778d788cd22270b.nq.gz
    ├── 5eefd48344a17140a679507b761480c9aeed8675.nq.gz
    ├── 5f30549b0049ff29740ce484d104aeb39f878f21.nq.gz
    ├── 5fa113b17abf08ce7aedcd190016263d12b0968c.nq.gz
    ├── 605cfc704d359409867587959ce5b7f2b66770a9.nq.gz
    ├── 61dd126904f5d5b4f7395b100dbb9d58fae1f508.nq.gz
    ├── 635cdedddd96fbd75550a2d3a7055f75330e26f6.nq.gz
    ├── 63b406572b4c3b47bfac43738f82466cc776f864.nq.gz
    ├── 64542f0214718a57db2c7e5924c6625895f457f7.nq.gz
    ├── 64b2ce601c41599a504d90af1cc4783f41179472.nq.gz
    ├── 6593d36e1079adc2489e41a12e1c5c74be21ea8c.nq.gz
    ├── 65eb6e2797ba1a420fc72c288d8dfc97213700f4.nq.gz
    ├── 663247e723cc76add4253ba0ca1a0672068381a1.nq.gz
    ├── 663d5c94a4b7e281ed4722ccd1be281306100e6b.nq.gz
    ├── 67fb2131fb6cc4f6dc48af45ada00beff1d714aa.nq.gz
    └── 6837c6f70566e6a26ca7371e7c3d05969c2e93b9.nq.gz

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

[huggingface/Repo2RLEnv](https://github.com/huggingface/Repo2RLEnv)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
