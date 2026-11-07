# Repolex Knowledge Graph of ansible-collections/community.proxmox

RDF knowledge graph data for [ansible-collections/community.proxmox](https://github.com/ansible-collections/community.proxmox), parsed by [repolex](https://repolex.ai).

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
rlex download ansible-collections/community.proxmox
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── eae7bfb00ee4d24be89ae358f7f32e2e4acdfad7
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── eae7bfb00ee4d24be89ae358f7f32e2e4acdfad7
│           └── chunk-001.nq.gz
└── blob
    ├── 005ada2fd551f4cf4645dbb9046931a7b27034da.nq.gz
    ├── 012065c8539f2bd3e61eecc74acf5a046956de40.nq.gz
    ├── 02181117c49f35ec3beafb7ee134d9c1ac5feb91.nq.gz
    ├── 024c3aeae13b83cd6fe0537200c6f0a8a3252321.nq.gz
    ├── 04a9a6bf1a8116a53b036e264ed707d75ebe06b1.nq.gz
    ├── 064827928e0ce0ce2e700443d15ad49e2b19f5f4.nq.gz
    ├── 06f8eb966bc67a278a0d5df42efb46e3787b88c7.nq.gz
    ├── 074612faf103a59251fc7da114fb445ffc6dc6fa.nq.gz
    ├── 078e43a4d813a87adc656e669395395ef4c8dff3.nq.gz
    ├── 0acd1bd0db78a33cf526ad20764af4a518482280.nq.gz
    ├── 0ba7bb39fabf2b6cf9188534d9c539662fecb2eb.nq.gz
    ├── 0e37e43b4dba52620f16b5a64e36bbfb362d3d27.nq.gz
    ├── 0e7ea70304a361b969e035a893f15ad41f85204e.nq.gz
    ├── 0f5e6d981eaa09549f12307c75a07b3aa9c3643f.nq.gz
    ├── 10926e87f113fb026c366866d6fa466061562870.nq.gz
    ├── 121e4f44e69e9a45024bd606fd982971ef9a7439.nq.gz
    ├── 154f392ed5ec7fdc64ce6727f12cf7875083341c.nq.gz
    ├── 15972414054e9785b298b0066a172726b9f33902.nq.gz
    ├── 180371039de55c206265205b36869e51da075ed8.nq.gz
    ├── 1ab72279bbcb46a05601446608329184e8a65a50.nq.gz
    ├── 1b6c372ec045d98f0a7b2959a1842c047d209705.nq.gz
    ├── 1bcc1ad2750b92017130fff55ffb8b87de424df4.nq.gz
    ├── 1c6072ab1a3394777224f8310ac4f6e2e40f4cd9.nq.gz
    ├── 1d768f76e05f5070fb12b4c7ad3e0f400ad898ee.nq.gz
    ├── 1d8ef364d38d21ae69d43d1449d66b255b31c752.nq.gz
    ├── 1ff57ebe7f62f2e77188db8732ea576192279165.nq.gz
    ├── 202d0028988e5481037ec1c39ac36b813baeec88.nq.gz
    ├── 20598154d2e6bb179ccde01a77e0e8d59ea79aaf.nq.gz
    ├── 21f0b03fc94ea7c761fdef8e300802f7dd6410d9.nq.gz
    ├── 235e1e6b077a3a35ab29721b27de269884e6cc3b.nq.gz
    ├── 2455fd0848bbd5fbf1347973f4c7db303721614f.nq.gz
    ├── 256b4ec5764c3df7e08f13354ce6bd6bebf7645f.nq.gz
    ├── 2700fc2118c2b7bca7c4e4e08f08d67fbfc19375.nq.gz
    ├── 273e5887dc4b179326786e2ca74eb9fab6663c04.nq.gz
    ├── 287cdb0898865ce8529d06efc12b7302a76a6ebd.nq.gz
    ├── 2b1cf18699a5b32d4035e6c245b0369a3e2aa248.nq.gz
    ├── 2b668274fd823c67d1f589f4dc8ec7e3eecb74e8.nq.gz
    ├── 2bea0137982345eb032f1d49b934310f74ade541.nq.gz
    ├── 2c853637d6dbdac0a840273fe801b2a2443cff4b.nq.gz
    ├── 2d8209c626b5593ba12715ee88516fac3b2b4a65.nq.gz
    ├── 2eb1af82f87a1f9b68f2969028c43a005018de00.nq.gz
    ├── 2ecd2202872daa95e4c6d9d0ed2e1c939e85341b.nq.gz
    ├── 327625a830488a9bbd429ebbee39729499db5894.nq.gz
    ├── 35c9e368422ad69f7bd08e8e323d78bce3ed1e8b.nq.gz
    ├── 3614907748e473733b160e957b65754bd8696ec2.nq.gz
    ├── 3737adc8bf4a97ecc8cee0dc5ae9480ee384fbd0.nq.gz
    ├── 37f17e2cceb0a03a69298ec8407cca94eec5637b.nq.gz
    ├── 394151b3a3670925d92147196576aef1948d162f.nq.gz
    ├── 39798578f52f58edf579eb3ca7ab451a0af48446.nq.gz
    ├── 3b3594fe4f90a5fb38e4212168a10ce1da0a3a8a.nq.gz
    ├── 3c39410895266848cb46cab7c1cec77e8483aa38.nq.gz
    ├── 3c8fb23fb07ee47e52d6d628e6fec9115e2c4669.nq.gz
    ├── 3cf1b3d4e3e60454e604bb78ed8c7eb3eb6b264b.nq.gz
    ├── 3cfd3e8567f4ade18b10fe0e173f2a9326a3f58d.nq.gz
    ├── 3d0d315960ecce962af908fb158fea9463acf183.nq.gz
    ├── 3ee534f057fb6bd2f0d96b04b9a545e7da1441e8.nq.gz
    ├── 3f686826ba62f6f7b450beb1b9b68edf9ffe3491.nq.gz
    ├── 41a5b6447ce1606d143c8a38aa56c630dde0bcc4.nq.gz
    ├── 41fe06cdb95a4879714a08e5cdcbdc9432befceb.nq.gz
    ├── 427e2f4bcc9578696c852fd6c21cf9c54f34d182.nq.gz
    ├── 4348f53853bcb257a50fcdeb71614d5b6ad9d3e3.nq.gz
    ├── 437cbd4e87addaef08174201246857fc0ad80cd4.nq.gz
    ├── 43c0bf977e90e37d10a7e1440f3f8c8c4f9f616b.nq.gz
    ├── 44561e2ff381043538ac53f0de599529ad24230c.nq.gz
    ├── 4646c27e6cfdd228f8c17737dea95a35edd93e55.nq.gz
    ├── 489774fc53cbfe207f510a25b5cff41da444ac87.nq.gz
    ├── 4923b8d5a42df3da26513041b943bcc86f755d86.nq.gz
    ├── 4b5a56d290db6745a864d743997e1fef78362192.nq.gz
    ├── 4d9d72ab24f738df37ac20add7a8c5ad2fd173fd.nq.gz
    ├── 4da72b6115a25bdf024f7571d2a0242fe3bf0146.nq.gz
    ├── 4e83b925a72943c4258cc7172b406803eb24d350.nq.gz
    ├── 511a2cf761b833e5a719ae5a1dac51e50c00eea8.nq.gz
    ├── 5200b2919fe6d50ed495e980e1026bf8d631d1e7.nq.gz
    ├── 525dcd332bdf6fbe18e9cef86f80107e9e318f54.nq.gz
    ├── 52a002b90fe355f984378ce621bf4225fa4e9a09.nq.gz
    ├── 538eb5da21fee7bf30663d22312f681f7ed35b15.nq.gz
    ├── 55886494b422ada05462c9507323f42596355d1e.nq.gz
    ├── 583652cb4527a7e0db8359fad1ece6dfa691e8c4.nq.gz
    ├── 5848e9baab95822d8af4cbb2f82ea17e3de8aab3.nq.gz
    ├── 586a6a1b374f0a59e8e95fcbbddde4a359c602e1.nq.gz
    ├── 599bbfb8fcd82a53dec2dd7dcc52e065790f81ae.nq.gz
    ├── 5ba736712b0ca494a60f4d298339e0d3aae4ef22.nq.gz
    ├── 5c41220dd74fbbd29ca5d3d9ecca16b8a84530d9.nq.gz
    ├── 5c8c78960819355cc148b6135f238d23867bce4e.nq.gz
    ├── 5d27e243d44af9405dc271adc863b208c7b2ef42.nq.gz
    ├── 5d9af810166ed51b0dbcdd1ebcc8b66b0f07f967.nq.gz
    ├── 5e400a38cfb7100e9ad931c73bc189dc9b5c3f1f.nq.gz
    ├── 5e5957a5c2b7ce290755502596d12a7aff3c1e72.nq.gz
    ├── 600541064a5ab94c2e393effc8c60f69427d00a4.nq.gz
    ├── 622fcb65067f595bb70a54be7ae953d66a34e8d0.nq.gz
    ├── 642859029872df711d56711977b00e367537af38.nq.gz
    ├── 64de21ca2f92815b8cf9a0b2be5e9660744b9f99.nq.gz
    ├── 67049e65396df48ac49b3baeca01a9e5839d5e46.nq.gz
    ├── 67c48c856caaff6419412c8c8e0fc09269720a25.nq.gz
    ├── 6810e04e32878215c32b2039277d4b1809f4de4a.nq.gz
    ├── 68ce35bf23b19227a4a31d42946687aa3547eba1.nq.gz
    ├── 68d5572dd3ff78bbff7fe545c83f2250699ec847.nq.gz
    ├── 6bfdef3cf6d682bd8ba5598b55d89c0b98accfcd.nq.gz
    ├── 6ca205da804b363377e6701ce975ff631ebf8a55.nq.gz
    ├── 6da054f396c28fff0dbb07d77bce7ce10079037a.nq.gz
    ├── 7066769240374fbd04a8a7e159b0e8108b24325d.nq.gz
    ├── 70aa5dbdba4b29edf350e2c21aa500686c273c90.nq.gz
    ├── 70cdb524392b989f1d0ba974f55808d0fe95b458.nq.gz
    ├── 715df4203dff41c48ae80aa6ecd211b26c78db78.nq.gz
    ├── 76516397a781c86bd9e40f40e97986525bde9296.nq.gz
    ├── 769b810a0cc8effc2eb254b97e11d1fc318e17a7.nq.gz
    ├── 78698202b1c883fa801c9a4895ff1ce32a9d30b3.nq.gz
    ├── 793a85dd38167529e33c3a1952bbe7715cd42a9d.nq.gz
    ├── 7a8bf61729cb88dea120fc3fe124ee159e39a0b5.nq.gz
    ├── 7b347403cca57ba684c4dcf561e095296bf91955.nq.gz
    ├── 7da1c27dca43d5cb54fee0f26193681d354f9174.nq.gz
    ├── 7e84180886628248e2636a5a78a837f755edac0c.nq.gz
    ├── 819dc3890a348b35f8dfd13f9336e20c3386243a.nq.gz
    ├── 8251e74d056678d9e9bbd8f6fcee68e7d4dcc179.nq.gz
    ├── 82c1eadfb65321d0dfbf34554aa1965f6d21a215.nq.gz
    ├── 8326f7a4a44c9d524be21c44e420bc51c4e0653f.nq.gz
    ├── 8453782b4b5eb4ae41c1f6aff4d9b4ab8667bedb.nq.gz
    ├── 84d1183056646f3b7e60052acf13746baf81f79b.nq.gz
    ├── 8517aad0a0a1637a9c54b91965d0b0db3aa99744.nq.gz
    ├── 8569ed663a9ac8b604b59cb1f6830f5e777f1d85.nq.gz
    ├── 865fa7c0b81d82091ce23324cc4c97047499b35a.nq.gz
    ├── 8725be8f28e36a05f42d560f51b583b2ac604977.nq.gz
    ├── 8a40280041a1566957544b041266439826aaab53.nq.gz
    ├── 8a7c812157d8f38dfe99d7d4eb1e7f7c94930995.nq.gz
    ├── 8b02efd82809cbe086e6ffec7fc6cb155c80c517.nq.gz
    ├── 8b5ef1eca3982966073f5df5ff84e244ac0051ad.nq.gz
    ├── 8e6289bacaf9e6159f0b005371f9f62116df931e.nq.gz
    ├── 8f773e045a76eef5396cb0df1908b085c95de2d3.nq.gz
    ├── 8fc257861b54250fedebb587e0c674daf5e1e4e8.nq.gz
    ├── 8ffff61657febd62cb36f3c20d6f836224ff9152.nq.gz
    ├── 900cbe42efd2f86cd331f1d04d8e89625833a0fd.nq.gz
    ├── 911b23c2d11d507523951dd82d623ad2d3c4fb7d.nq.gz
    ├── 9226904971bb865aa5428f38d264925757237603.nq.gz
    ├── 92e1cc7af04b84bbcf5dbcef025eedc930a7f8ff.nq.gz
    ├── 9406485c38dd02d9912dc12840c465a54de9cbb4.nq.gz
    ├── 94ef0785324424f660e96a14a22787be293241b5.nq.gz
    ├── 98304458e555a26b4affcf791ed580b756c5eb69.nq.gz
    ├── 99358008d0891488245c45b4e87887ca1964696a.nq.gz
    ├── 9bb66500985e8647032432970303748901fc20f6.nq.gz
    ├── 9bd18be626b16e75dc12a274b2c121c91d6ec100.nq.gz
    ├── 9c7510e3ccc76620124c31d9e25da0c0306105eb.nq.gz
    ├── 9e074a578dec9787f51d09f9df56a280c22204e5.nq.gz
    ├── 9f31da64dbf49c4d1ff4932295ec30daaaf88ccb.nq.gz
    ├── a02a2d61a12855eddf862fafa4101bd3afe62b76.nq.gz
    ├── a1390a69ed92e252cc59a843354cd415822b0b05.nq.gz
    ├── a2c14226139d6d99094b0f4397475ee4926de2c6.nq.gz
    ├── a4e9b0559a1d82535ba2f4437dca3dfa84333425.nq.gz
    ├── a58f37127eae026f84f8aff83e74221aef754fd2.nq.gz
    ├── a5b6261106e580dc555219a8a200a89f988a3e32.nq.gz
    ├── a6d20a5bbb5ceaa61e0fd4a44bbcdf569d0f6720.nq.gz
    ├── a715d2e22f5165f5f06b0c507f95ddaa1892a239.nq.gz
    ├── a72f7bdb90bfac07b9da327525fc72993b4291dc.nq.gz
    ├── a7c203d26d13da973ad60d489032a1a1de55920a.nq.gz
    ├── a8b02f428a5ad79b90243b7dfc7420a1a8b5e7e9.nq.gz
    ├── aa49e80505be409349f574cf7c35a1869ba14a2d.nq.gz
    ├── aad675ed75f2f2c7e0a7e6fefcca20d0a4993a20.nq.gz
    ├── ab255d082f1ca34446935be67aac73755db8b9a4.nq.gz
    ├── ac62e1e563073b2d32492fefaed0471751c844a2.nq.gz
    ├── acba9e392050bd0cfbae9496369794a2c29b9ede.nq.gz
    ├── ad419124a8a7734acdffb12c392132a30ec41d88.nq.gz
    ├── ae5e071d3b0e88aff7716b2f99f843e1bb950f99.nq.gz
    ├── ae7bcb8deadfb3f5a0b5d3863902f10bd7e613ce.nq.gz
    ├── af4867a1570209ec312b55f76b81d55794929935.nq.gz
    ├── b588db576f5035fc4d99df0f074c9141605c2775.nq.gz
    ├── b9f69016ef25e8dce30450a23790e982de36e877.nq.gz
    ├── bb0a993995dafbf51cadf2bc464dece1b428661f.nq.gz
    ├── bb5788652100e3ae5228c6cfdb4a10be7e90c685.nq.gz
    ├── bc4d179c9ea3951a8c8b61251eb3c46d6360fc2c.nq.gz
    ├── bd13882e5e7f62b9667ae8539f06873aa15128ab.nq.gz
    ├── be5d4e8136c2ded2954e9cd5cd706fb5022ad8b8.nq.gz
    ├── bf55a8d01f376d27b01d1d16213c8bae10945fd4.nq.gz
    ├── c00b539915c66d645d4f1543824212bf4be3daeb.nq.gz
    ├── c0541bee57e7eede02ca5a3e66b2ba6a3bc2f2f2.nq.gz
    ├── c0a6718e32aa1e3465a61467376771fad4d6ba48.nq.gz
    ├── c0bd0d53bee1783e8114b608710a8666b08bb541.nq.gz
    ├── c376dee22bf07d6ac38ed0e6970c6c51a1b26fe6.nq.gz
    ├── c3b7458f9585600839f6b0631c4a727eb818da58.nq.gz
    ├── c78f48baca981ededcad4ae448dbc3b0c394250a.nq.gz
    ├── cb03a819afb0dc9045b17493b8484f137d21bcf0.nq.gz
    ├── ccaf42f4bbe5a6ce6b24848674d9104a931b637d.nq.gz
    ├── ce96709fc8f6ae9c1236d4c1b012586bac014e87.nq.gz
    ├── cfb297dffa5a7eb8bdc4ab3fefb2d59bbafb7202.nq.gz
    ├── cff57e55cf39d80d8ce7f199edf75619c8c9cdd2.nq.gz
    ├── d014637705c2c2eaef88b07a973c287b080db273.nq.gz
    ├── d029b4727bfdd4853f042857b9467697ed219608.nq.gz
    ├── d0b60397701a6cece4ea99d2518f8d71a5305296.nq.gz
    ├── d28053391cb004c46134e3605f3d07fb0fbe1ba8.nq.gz
    ├── d2fefd10c748f527b80e0209b7a911821aad0fd7.nq.gz
    ├── d3d8f8f206cfafb32dd52b0ed46bf6ed32aa4d16.nq.gz
    ├── d3d965aeb216b24d778e0e640ed54af55663c1f1.nq.gz
    ├── d4e27b34efed79fddd967162a166119541d0cf3a.nq.gz
    ├── d6749d382b16dce77899e02760b8691c8da565d5.nq.gz
    ├── d67eca9db4cbea0fe791644796199119056ec3f5.nq.gz
    ├── d7bdcd957ab561459fc05ce7240f04c06f9b5e8c.nq.gz
    ├── dd576ee923478e2478b0b96ed346a5b03b543153.nq.gz
    ├── de75500cf5f92232ca466749975664ca587bf6a6.nq.gz
    ├── e0796e4e03c7239cfe2ec01533002d5f66a26480.nq.gz
    └── e1ad7d002416bca5da58549a2e853e237f2257a1.nq.gz

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

[ansible-collections/community.proxmox](https://github.com/ansible-collections/community.proxmox)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
