# Repolex Knowledge Graph of apple/swift-configuration

RDF knowledge graph data for [apple/swift-configuration](https://github.com/apple/swift-configuration), parsed by [repolex](https://repolex.ai).

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
lexq download apple/swift-configuration
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── be76c4ad929eb6c4bcaf3351799f2adf9e6848a9
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── be76c4ad929eb6c4bcaf3351799f2adf9e6848a9.nq.gz
│   └── repolex
│       └── be76c4ad929eb6c4bcaf3351799f2adf9e6848a9
│           └── chunk-001.nq.gz
└── blob
    ├── 0023a5340637983755c8c19c18cc2c2bb1dbda1c.nq.gz
    ├── 010dab8ef85f5658e6109e288bfc8598368a9654.nq.gz
    ├── 01a00663c73d5e91b2829eb8b81427878a619f03.nq.gz
    ├── 0381a682cc9b1650e29936e9a2a5a4a4e2e0be3d.nq.gz
    ├── 03e63a01e6d54d1c1bd582f4b9d70e203dbf62cd.nq.gz
    ├── 04f563fba5d7e8a778e9c41b587f2dcfc0b4c445.nq.gz
    ├── 0623e94e6b39b1e55d0df64c630e7798e5a5fc77.nq.gz
    ├── 094742fd33c22cb91129213686f1f4131650e8ff.nq.gz
    ├── 09dcf00a4d0f6a92e07e199d5616ccc348369b69.nq.gz
    ├── 0a4509a31333686542cd9a037f6b32fc45f66d64.nq.gz
    ├── 0b771b7655946f33e3ad05511f0d4fac71df1628.nq.gz
    ├── 0cd224786933facdbbcdd0167b5dc0f8451cd56e.nq.gz
    ├── 0d4d01862cbf131e831ad072f89eb100e69507d1.nq.gz
    ├── 0d6ee642538f94cb65807e1c3a7b195820bae069.nq.gz
    ├── 0d8a709b1d749817b8ba43092403f5998db08c9d.nq.gz
    ├── 0e3306fa933bbd369cd65204c1fef5e9e269f1a3.nq.gz
    ├── 0eeb353771530c4003ad760daa7f3e9021cb4c3a.nq.gz
    ├── 0f81c9e0f9c31fd3e96ded0975202ca855f12ec0.nq.gz
    ├── 10177bfd6c2b147694516ecd8c886d429819203a.nq.gz
    ├── 126449e79af96eb9c0182ea90fbd2e3119491fad.nq.gz
    ├── 1314b9466c9397ec494a96abfa7ce86fe30166e0.nq.gz
    ├── 13dcccb885584fc177f4db334076698b7caca60d.nq.gz
    ├── 14e0489182f584455a959c7ed21f44cd6d2fbe44.nq.gz
    ├── 1570d132b53c5e47e955de63952bbbc0c86b2b22.nq.gz
    ├── 1668552f0894392c94293f690cf65438a14ce0c5.nq.gz
    ├── 1acb3e31055d0c7f3c79c50666724050cb6e741b.nq.gz
    ├── 1ae27352b28e8b319b4a45c4eaa934d3288c3357.nq.gz
    ├── 1af30958ac157f694219a20160bc9baa0ba1a7bb.nq.gz
    ├── 1ba48a0cdf511f8f2bad054342ad950c95d42109.nq.gz
    ├── 1c11eae7eeadda32ab921749beb3ab7adb4d4063.nq.gz
    ├── 1c170340a0614d1b7eeb16c626278093b1957b32.nq.gz
    ├── 1c5ee2d32a7ea183cba85ad462a7c8804d61f5c7.nq.gz
    ├── 1c63f659e573ff4f52891ddebca8cecae61910eb.nq.gz
    ├── 1cf76528b104968a471f8e00c423b91a66f25007.nq.gz
    ├── 1deba094f86e84f939f91ece52d0f23bcde34585.nq.gz
    ├── 1f29ee643fcdcd407668c3aa213bb9a3c54f1e94.nq.gz
    ├── 1f60076c59049519116d548cb504c5f0473a95b5.nq.gz
    ├── 206c1b5af471c05e9306de21b14f905e74fd965c.nq.gz
    ├── 214b3fdb7be3d91ce0298c7006f494190f729eeb.nq.gz
    ├── 23baf1447545c2fe7ca64f14ef7ccd16526c62c7.nq.gz
    ├── 23e78382bacf9ec41864147fbc8ea4c9d64aae6d.nq.gz
    ├── 242f27dc27471f4dae079396b44b23663bd636e4.nq.gz
    ├── 267de722bcb7cfa632e0a4f303d05b7717270706.nq.gz
    ├── 268a99c8557a9ca2c17702ae9e91760dee483774.nq.gz
    ├── 29b18393f8d5d3ab1ca7aeef940086abb1d1c601.nq.gz
    ├── 2a31aec22b901a0061fbf433cff49eb2acab3a21.nq.gz
    ├── 2f847e654873c5af3fcb8ca86e7987699af181b8.nq.gz
    ├── 2fcc2f1895737b199f0c0af42c0adf66b3eca133.nq.gz
    ├── 31eb92b9037c966d9928c12ab0d44feea1d8ee82.nq.gz
    ├── 32c2cd3df20ec29efb579fcdeea9f5538a1ebc32.nq.gz
    ├── 359829f3a9d0eed11ca31b03c6383e8f1f7a68b7.nq.gz
    ├── 35df0667f5ae1a6c8b00d677a065c77a07abb06f.nq.gz
    ├── 36cbcb62c7aa1c835c96e78540ba07e01b028847.nq.gz
    ├── 37a965bb5143d41ec17bebc5441b5e94c30cda3f.nq.gz
    ├── 3941f0a0ed3f3b6e08244a82ef1e4ac5714f586d.nq.gz
    ├── 3aed1fc3b9a1117eeed6c5a1e67dc51f394c97ad.nq.gz
    ├── 3b0ff13c53038f30b077ec8d2a2641a448e5116b.nq.gz
    ├── 3c21673eef0913860f2a0699b17d6a3c7de9b928.nq.gz
    ├── 3c4ca55f4df66c08c828901bf27504fc0a5f8fd1.nq.gz
    ├── 3cf789b6c6512b1b6fe1081a60cc7621870659bb.nq.gz
    ├── 3e064c3d0d041975fb3b935121e1381e5e76f486.nq.gz
    ├── 4011797d9a050d80d7ea6f1e291caf1703e17602.nq.gz
    ├── 43dc89684e9b9aa1a044f4d8cf02831645d869cf.nq.gz
    ├── 44d7bd4f9fa65ee7fd8d5424adfc9acca442d566.nq.gz
    ├── 45173701df8b9a4c42592e09fba1b46675c2b06f.nq.gz
    ├── 471119851004274117a3618ebc0c3d3b571b89b9.nq.gz
    ├── 48c36617e68c7fc741cc4616f3dd1f859cc80264.nq.gz
    ├── 4904b84aaff6353ae445652b198dfd46a3cb0032.nq.gz
    ├── 499d0c4cf55436dbd9f60eb664daf9409d740f40.nq.gz
    ├── 4ad248b7941c05c8d697c3120a8632d6da787679.nq.gz
    ├── 4d581903d2081f10ab5767b1aad6ac2599ac048e.nq.gz
    ├── 4d9149022b4c0e30431bbcc45287404cb14bd4b1.nq.gz
    ├── 4dbbd4f72049c237c016daa5ccefb70f0dbe9e14.nq.gz
    ├── 4f8f10b3539e39c79c1d25ccf718bb45d66f27fc.nq.gz
    ├── 51c1160412e13c169b713b00d9aaee048993302c.nq.gz
    ├── 52f46ba6f59b9b35fbd8f52e6e007b16a6c4aed2.nq.gz
    ├── 533527632fd160be5f7ed82aa234a49e402c1821.nq.gz
    ├── 549c172c8b0c1049f1809ab37f012f8c5d2eef5b.nq.gz
    ├── 54bdfe431044638d622f58472540fe8907a7b576.nq.gz
    ├── 55741c413850e3370c88812cb881fbe8fd5b53c1.nq.gz
    ├── 566eeef8181c81bac305b54d0545658782903858.nq.gz
    ├── 587b8051efcf9d37a739c854b37dd33f92ed778b.nq.gz
    ├── 595853e95eae1606e8d4edd796f996a259f68da8.nq.gz
    ├── 5aa1e6ae48dd978366792c01a94780aa67aa9387.nq.gz
    ├── 5ace4600a1f26e6892982f3e2f069ebfab108d87.nq.gz
    ├── 5b7b9ad78914ebfccce4c788307ece8e0365113b.nq.gz
    ├── 5bc022dbd8fb649bc68a5eb7119a061878eb74f7.nq.gz
    ├── 5c3be49bdd958590d83a09d4b4121c8f064f1b93.nq.gz
    ├── 5dc5c93586c97893541d8431faa92810a1501d69.nq.gz
    ├── 5ffe3274e8d29665e50e096a5837d4ada9b79d3a.nq.gz
    ├── 612352d38777680c078b98b900d704864cf46c21.nq.gz
    ├── 6183cf1a63c66510517b3c601133dcec58a1bf80.nq.gz
    ├── 61e4479b86e8c951a481ff78ebf753b8a6f84fd9.nq.gz
    ├── 61e62b3231483692eb77989aec781c1d76f2a9ec.nq.gz
    ├── 628a50c1fe21cd9c54a8b678772914afebd131b4.nq.gz
    ├── 62c7f681763d87b336563d74e213b7ba8e58fdb0.nq.gz
    ├── 62ce439b73c8481d0816a9a5b6b67b65d8f55e1b.nq.gz
    ├── 6358c72626caeecafa014f28314fc2c636e26548.nq.gz
    ├── 6386ab224bc16aa73ab14aa54143871fd1b1962d.nq.gz
    ├── 655ab170dede6fd181e5642dbd42cc1e5bd6ecf3.nq.gz
    ├── 67c2bc22c44a07673ba1d449b7d46aedea25fe8f.nq.gz
    ├── 680be2e6e13fdcbaf6480fb193991e6ff71824af.nq.gz
    ├── 686cd341b629a9d9790726ff111f055cc4f08923.nq.gz
    ├── 68ceb88b13757a5b3b52774f9b912ce33ab7acc0.nq.gz
    ├── 6a32ba0a00423526a64fb0bb27397b35539e9c16.nq.gz
    ├── 6a92920fd36d4378a0afc3c6b16649b84f58594c.nq.gz
    ├── 6ade041312365905434d2a51bb466489d5f913fc.nq.gz
    ├── 6b0b1270ff0ca8f03867efcd09ba6ddb6392b1e1.nq.gz
    ├── 6b8ba8e5cf413b43e4065f30885193e1539a267f.nq.gz
    ├── 6db9a093c44e01d32839a6592c97e64798e79bb2.nq.gz
    ├── 704355645b05d3fa5799ffcb2317e6450e6f6240.nq.gz
    ├── 7047ab0919c924df1ea1abf39e83dc921632528d.nq.gz
    ├── 7067dedc5949420b29d255fdc71b37ddf9758031.nq.gz
    ├── 7083fd76f6e74bfb2d743b8f4906bebf009b9a35.nq.gz
    ├── 71a1ea81897c343d2ed83f9de6801ac09541e8d7.nq.gz
    ├── 731824ca7b56ad4e08ce3871bae54aa663f7107c.nq.gz
    ├── 73a834825cb6044615a6749b45cadaf3daed9157.nq.gz
    ├── 73b6e7a6c6cd985746df39e5d5f2b8a5ba7b66c4.nq.gz
    ├── 73c387e97fd8671c22ae292fbdb75725fa650b3b.nq.gz
    ├── 74558582687f8301481ae70f022911e8efbae1bb.nq.gz
    ├── 75080f9ba96e0b1b6cfef8598653c7496c1c2d59.nq.gz
    ├── 75b2b3627a3527bae1fd9bf7f6b6e9b0eba244a7.nq.gz
    ├── 7708a3928551e9ed0e6570498f4afe984d3a998c.nq.gz
    ├── 773c7740183057bc625fed74d45dd61d6939cb39.nq.gz
    ├── 77e4c005a26fcef2c13eb2c157a7a8dd2fb359e2.nq.gz
    ├── 785e2ee00251aaeb4fae8107cd35f60747fe21cf.nq.gz
    ├── 7869a78507c22b21d4061eff5bb764f18c9b5cdd.nq.gz
    ├── 799314fbdc768e9353819e2a3b46bc40f681ca7a.nq.gz
    ├── 7a1a29c3d0af91b202957406dc598bdc9e3649a3.nq.gz
    ├── 7bcfb119398abf3d6422866a0f4c33f9f14b7125.nq.gz
    ├── 7e5b00f104112e8787a6d27332e1873d2574d1bb.nq.gz
    ├── 7f5d55734a20ffafe16c8e2f4df82d20d36c16dc.nq.gz
    ├── 7f6cde4bf934935e2bdec910dd48cfa1ed8b99e0.nq.gz
    ├── 805c8c69d306baa5ed4f2806317723842d800992.nq.gz
    ├── 807e2ff45f4533d59d918452cd48d254a51ddb9c.nq.gz
    ├── 81b2b8d73cb75fe1964230d032f8e9250f451647.nq.gz
    ├── 8261771d054f0e6ef492529ad2f4351d2cc6d24d.nq.gz
    ├── 8333fb981f4b8ebf926acbd9c9d1fbab9f155744.nq.gz
    ├── 83758b6c81e2665a567b81360b52ba2d98b9e7a2.nq.gz
    ├── 83f5ac642fa965bc7ae64be3b82dfc14a96bd703.nq.gz
    ├── 85381c11776e8376a641ab9348148a45b244c685.nq.gz
    ├── 87262c2a21ef1605dd72460d0453cd419b4a6bf6.nq.gz
    ├── 896026fad48338b4f8729df0aa092d15d7e76a36.nq.gz
    ├── 89a872b3820b28b2ca2c9b8501cef6b9c48ff409.nq.gz
    ├── 89ef2432b3440b196eac2a1d64efcd593f2b90d3.nq.gz
    ├── 8ac2a5455252e64261630085949e40b97b68d177.nq.gz
    ├── 8b20dbf784fa772f6b3a60daf9224c2a5ec6c88d.nq.gz
    ├── 8b2f9ca9b1c0695eee19c43df87b8620edb4b08e.nq.gz
    ├── 8c3b425556adab7caee86a147a62eed3aad8bd36.nq.gz
    ├── 8d3bb9b369e5790cf9c0f5eaee08a34c5def83e7.nq.gz
    ├── 8d3e737e9b435a7889885d2195e5c54a17039fbc.nq.gz
    ├── 8e5c223958ef615f54fd25a7b95ffc0506389feb.nq.gz
    ├── 8ee9185e98f70af603c7dff954d2ce21bec2ca01.nq.gz
    ├── 9089d2c36bffe574d1c0f26f519e746eb80c0424.nq.gz
    ├── 91946d252779552badbfc452d3bc6372d9c07bfa.nq.gz
    ├── 928b4efc93a111600b0ac1f89eb4fc6689ae2f76.nq.gz
    ├── 948679b9fdc2ba3cf152777bd0bd0fbb668450e2.nq.gz
    ├── 948afc08da3ed3817aee4cb3144edc2e51c68b14.nq.gz
    ├── 949be598d50e38e7654ff2b1c24b282ae4112098.nq.gz
    ├── 94ef5fd2d46c8cc8e21d5ef388e090bc5b7f6b47.nq.gz
    ├── 958f703b2f31eb5b3ff9ecbf09c605cf24306a7f.nq.gz
    ├── 96eca1da38755e8bd32eb5efe0fee072e6599e4a.nq.gz
    ├── 97b5b6841835ddcde72151aef21553514da171ac.nq.gz
    ├── 97b617c3ce4c93a453ad3425817db14c3baf8060.nq.gz
    ├── 97cc45696a92817a5f305ac481411e8321d8f205.nq.gz
    ├── 9c692fddf6a77bdc866fa5fc7d2ed057cacd8449.nq.gz
    ├── a1161033abb9dffc60a398fc426cf4b70decf280.nq.gz
    ├── a1331aa40af4ace04752561ad322bacb245d5548.nq.gz
    ├── a14e4a9616896bbbbb2721ca51c66efa49bea596.nq.gz
    ├── a30d4dec3ff9f52bdaf9864180e142330bb22341.nq.gz
    ├── a3c01f33fd5fe12cae6e4eb102ab3d515405bdbd.nq.gz
    ├── a9ab4f8ac3f7e60ba7c780d7cc8b8ca85ffb4dae.nq.gz
    ├── aa473a4f38f7fc99417f0b58a3cdcb2e1087b1d3.nq.gz
    ├── ab29c8dc5e787bb604590efbb15c3277bad32f42.nq.gz
    ├── ac4b5880dba5a8f76bc6a1a371b306a41291d99c.nq.gz
    ├── ae29cc0d8d49ea2861f4a0d1e2aee6358976f3e9.nq.gz
    ├── af20f6672a0eeb6b414e7dd839bca7f152d70e93.nq.gz
    ├── af40e1cec0e3c28c6fe12a1a440bf3457946245b.nq.gz
    ├── afaddf1254403154baa6e73f9b2328f7eca3c469.nq.gz
    ├── b017f7c5e8a318b37d44d35b6b1bd8c88af44436.nq.gz
    ├── b1922e3043e2f2f4b68da17cf3dd2737dc37317f.nq.gz
    ├── b33393bd7f719e6811194df8ee7812c4f7aa36ef.nq.gz
    ├── b3e6828593c8cbf838d10868c01b133db874db0e.nq.gz
    ├── b47523ddc36364f028accf4fdc3c7eed077ea9a8.nq.gz
    ├── b88ed17d7061f78ddfacace5466727e7665cedd4.nq.gz
    ├── be449413d62bbff8256b9fe54f9765dc500a0fa4.nq.gz
    ├── bea58c3efca03d10d98b4c1fc67c45cd136a7218.nq.gz
    ├── beaa1ed8ffb821713d85bb2c1891091d3fd0a41b.nq.gz
    ├── beeec0524a08b65f210064b735e2956642428eab.nq.gz
    ├── bff1a797350490dbf4dffea600abc6d4bdb79e85.nq.gz
    ├── c2901cc53d9c5487eeedecec06de37c2f53f5b7c.nq.gz
    ├── c40d2011ee0f91b5385a7a7882ad7308af24b237.nq.gz
    ├── c4c6708dd55419ff4e312971482ab867756e5cbb.nq.gz
    ├── c76e3023886ab5fc41b65d540df0c532ea3e82f7.nq.gz
    ├── c8a1f9112bed1c24cc92d93b5e9df51bb386844a.nq.gz
    ├── cf48e1c8ffe6019a03767ca41caca37d75fefbad.nq.gz
    └── cfc393a68d66abf5df4567135156d7ca9fd59bf8.nq.gz

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

[apple/swift-configuration](https://github.com/apple/swift-configuration)

---
*Parsed on 2026-04-22 by [repolex](https://repolex.ai)*
