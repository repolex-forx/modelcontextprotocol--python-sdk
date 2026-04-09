# Repolex Knowledge Graph of modelcontextprotocol/python-sdk

RDF knowledge graph data for [modelcontextprotocol/python-sdk](https://github.com/modelcontextprotocol/python-sdk), parsed by [repolex](https://repolex.ai).

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
lexq download modelcontextprotocol/python-sdk
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 652478266702ac71a1d03692337bd5207ddbedf4
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 652478266702ac71a1d03692337bd5207ddbedf4.nq.gz
│   └── repolex
│       └── 652478266702ac71a1d03692337bd5207ddbedf4
│           └── chunk-001.nq.gz
└── blob
    ├── 00dc69828b99735c778402867de12c60236b5024.nq.gz
    ├── 010eaf6a25ea3ed0e2fef552dafe8835ce467baf.nq.gz
    ├── 0237c9ab31a8e7823c262ded9c2500b6e4454a75.nq.gz
    ├── 06020b4b0e2e822d64c3d58fad2b68a08f718c7f.nq.gz
    ├── 061a2f5bcfdfbd8296565244b5317585c39ecb55.nq.gz
    ├── 06d404e31104bd4a345b970116ba88329ace630e.nq.gz
    ├── 06eb1f29d1c0200e23473fd0de643a335519f24e.nq.gz
    ├── 071ea81553819b63fd455216237fea91ef981511.nq.gz
    ├── 078beb7a58d43b98f8471cdcf33c2624f1d7ef7d.nq.gz
    ├── 08fcabf276b561fa485f5bbbb049d94bfd41008a.nq.gz
    ├── 095753de69c29f241e778efb591e845c1cdb0f35.nq.gz
    ├── 09c174c9c00aa8ec28678a49d5770502bd476161.nq.gz
    ├── 0a0484d8949e52d9dcd720e067b745760b27e7a6.nq.gz
    ├── 0ab37448503f3e1d17169af65a5963a77d0e571c.nq.gz
    ├── 0b869216e873f13ca4113e0a45fde15e1a97de1d.nq.gz
    ├── 0c3081ed6455a9e5cdee74e354b7741f69d5c6b5.nq.gz
    ├── 0d08e47b1b7ab9432eabdaee902fba2ab9316098.nq.gz
    ├── 0d76bb958b1e2614aa821c49fbc522d70dddaeda.nq.gz
    ├── 0da0fff07aa3aafb83d26dae33ff45dbff97015f.nq.gz
    ├── 0e695695cbe759fe903978e85c5668a358633ad5.nq.gz
    ├── 0ec0879688efee538b5088129e619a3705de8195.nq.gz
    ├── 0feed368e4f27649c5db3e6f0dcd299d311d66ed.nq.gz
    ├── 103be0f1fb1d16ceb261d2486bd9aa28b94d2f76.nq.gz
    ├── 117deea83aaa381f1bffec26771a925679e848ac.nq.gz
    ├── 12691162ab37ad85a9dcfb8ae767cdb3866ad47d.nq.gz
    ├── 128fc1ae102dce0782af1fb7970279b5dae3ec16.nq.gz
    ├── 12d159515cb4042e3c894a41bde1953c730d469a.nq.gz
    ├── 13f42d7126d06e74aaad4bbf41bdc502a8c9858c.nq.gz
    ├── 140b38aedbaf7060141394135ce2770782c24411.nq.gz
    ├── 14c2bd38cc3ebabd9e396261c85d661790d0f1f1.nq.gz
    ├── 14de5025741c5140b5ecd2f8de174a90443b648f.nq.gz
    ├── 151a23eab406411af9fbb1cde9b00c54f14cbcce.nq.gz
    ├── 1552711d2ea4e45bbdeda9a14f14ca26bdc5af06.nq.gz
    ├── 1649826db20153c270658597209a7a609938cfe5.nq.gz
    ├── 1664737e3a713196647550e574691f5a4290aaa9.nq.gz
    ├── 171871ee58d60c8de3fe7cac3bef89cf05af0bbb.nq.gz
    ├── 1805d2d3159fa848572db51f715ca82b552dd325.nq.gz
    ├── 1970eca7d320afb498ee60e20eb7986d0d523525.nq.gz
    ├── 19af93fd1695fb69ec74eb86e3f98595543d778f.nq.gz
    ├── 19c557a1311b5cf59fb561736124baa1f7a46054.nq.gz
    ├── 1ae6d90d1970de9b587aeaf5c3399057fd3290f3.nq.gz
    ├── 1b8f8acb092336bbe53f102d5817c20cf0ae0ccb.nq.gz
    ├── 1c16c3cc6e6d1a252cbf47511f012605762e160b.nq.gz
    ├── 1cca4df5ab2b748c80f344d71bd5a657ec625236.nq.gz
    ├── 1d496b3f10223f8bacca0dd2fe68739bf7a345b4.nq.gz
    ├── 1defd8eaa4cfb8a604343e961ee3664db97507e7.nq.gz
    ├── 1e5c4d524cccfdb5829b7fa10a1991621b8ecdf6.nq.gz
    ├── 1f1ee7ecc484bc4324b0b7d9ba5e0235c1c49169.nq.gz
    ├── 20cbf795789006eddf0d11013e2fb20a2e2315f7.nq.gz
    ├── 20f67bbe427c8d42e4c9efa844997a631c548566.nq.gz
    ├── 21862e45fb6df2f92a79971e9a26966cba1e077a.nq.gz
    ├── 224bbc5917bef15b5107d8ee2f1ad39931219838.nq.gz
    ├── 2292072ffa8294b3c9d7a53072fb773949a29da7.nq.gz
    ├── 2365ff5a1b99eb3b9f86b988b79e7589eef6f37b.nq.gz
    ├── 23719d0f58107890968851402fea2aa659601986.nq.gz
    ├── 23ac7e4519df4442949ef348f8ae42a6f48ce972.nq.gz
    ├── 23aff8bb02a0fbc4decbc8604d80cfef99d59c86.nq.gz
    ├── 23cfc85e11628012eba923387ca483c4405081df.nq.gz
    ├── 2434dcddd944a47792602554758d19b55352a703.nq.gz
    ├── 2478cac4b3a21d395416b0198c7e5cf7da75879f.nq.gz
    ├── 24c8891deff7d3d05ab2645614cca87b505e878c.nq.gz
    ├── 252dfd9e4c8ce98524aec5d74a952188993c445e.nq.gz
    ├── 27547e79563560c3ae950beac226cdaf44fbb0e8.nq.gz
    ├── 27a8081b6297911bd622786b6ea1cf48c3b85a55.nq.gz
    ├── 28fe265746a7a24a17d1cfab7f9bd2c993e4bc13.nq.gz
    ├── 2a31541ddc2547a9bcac02366ad7e3bde8f497cf.nq.gz
    ├── 2a8cd6202e6d02babd9d2a820cd44e5f34ecf8c5.nq.gz
    ├── 2ac458f6aa80229acba6747d78d44809036d2c2d.nq.gz
    ├── 2c4604d8cee0700617db58fdccd6b3b74603c60c.nq.gz
    ├── 2ccd7056bde4d2ebca0b48fca477fdd5e41b5888.nq.gz
    ├── 2d4d06a025b4e509d889c19fd6ea4e4c92aa3d6a.nq.gz
    ├── 2d7eda4ab4a2031f5b76db8f640cee0ba2d7118f.nq.gz
    ├── 2dd1a8277ae3c71226ea45ada9d23b5647d190a9.nq.gz
    ├── 2eac31dfe6db3fb8c2da077dda7f811a7f05422a.nq.gz
    ├── 2efe05d5363cc3f0279234e643217469d3d393ee.nq.gz
    ├── 2eff688f020a2474bc384a917d6f995bfd05a7e7.nq.gz
    ├── 2f09ff154071836a83d52cdfcc5543aa437edf3a.nq.gz
    ├── 2f609cafb192bbecf4ffea1c105d75aedad8c94c.nq.gz
    ├── 2fc2cda8d95c520b9e45f0d502c6594a02bd8c24.nq.gz
    ├── 307fcdd6e547dd249124bd156dfb80e217e0d68d.nq.gz
    ├── 312a992d0a538420990e61d8d78df3db46154370.nq.gz
    ├── 31796157fec3a294de67d5cd36f93bf7effd5050.nq.gz
    ├── 32a11437ebb6e029ec5544a1ef8f774de66fe125.nq.gz
    ├── 33bcb5f2aad50a1c9fbc100c8d897c1e2255d2cc.nq.gz
    ├── 34f9c6e28e2537ea6bf3d4988c6f369f8cec79a2.nq.gz
    ├── 35094ec9c8a807662f119d7dcc9507fbd9c2ba87.nq.gz
    ├── 3512665cb9296637248f65a3caf0f0e660427f8a.nq.gz
    ├── 3570d28c2a2a9003f390fe51e78b0ca7177f654b.nq.gz
    ├── 35a83fcf1bfb41e244c364d5354e85d8caf810d0.nq.gz
    ├── 360cbc3cff875a8cf7e592a778d6d4bf553192da.nq.gz
    ├── 3717c66de8263663adb1bac030acf1d3abf95967.nq.gz
    ├── 3762b092bd58b0cae47d33f3517feb37e9ce1600.nq.gz
    ├── 379c47c1258754e056f473530ab070ea5d5034bc.nq.gz
    ├── 37d81af50bbafe1b689f81d04bbf30cc7c7d4d3b.nq.gz
    ├── 39be363c20ae89c333fdd94591237808fd4cebff.nq.gz
    ├── 39db2e6b68655f73079da6a01481af19b9ab242d.nq.gz
    ├── 3a0b9d0086b40de024ded7aaad3cbedda53130b9.nq.gz
    ├── 3a92d05d1e30ca3af0bf393ed50f128191765dd1.nq.gz
    ├── 3ae9d341e17ef0409076cae7365171641f841d75.nq.gz
    ├── 3ba13e0cec6cbbfd462e9ebf529dd2093148cd69.nq.gz
    ├── 3ba880f40dd6b019dd057929e91bbf9319658272.nq.gz
    ├── 3d03b4d4a105b78484331781c1fe0509e9676cec.nq.gz
    ├── 3d3e7a72ccbb279bb0cdc4c433f210c152319130.nq.gz
    ├── 3d48435454b105021b4f777c11b6b07d8d2ffea3.nq.gz
    ├── 3d6b16f48205026144019f9e450428ffdb638ea4.nq.gz
    ├── 3e12b318329608d0d581e98b0e3fb561148a615f.nq.gz
    ├── 3e92f29479b19911d23ff33450eae6a10427d95c.nq.gz
    ├── 3f696af543213f8d1fbc7395e12e445f08d35019.nq.gz
    ├── 40f606ba69fa06420a36200688be7d09f7736f6d.nq.gz
    ├── 42353e4ea0f3bfcfbb0423aee366033976f8e9ed.nq.gz
    ├── 42c8b0159a3ac403be315dfbd76280bb57b8618b.nq.gz
    ├── 42f5ce407f80a097365645c57248c15accd28681.nq.gz
    ├── 4442f979425da691a1b7b90627110d4e7f746831.nq.gz
    ├── 4467da61727d74c27eaabc7853ab1ab09ffa49fb.nq.gz
    ├── 44f4ab4d31f1cc77eb550acdb270af53ff5a3d3d.nq.gz
    ├── 4619fd2e04308eaa629dbe7b4f0137947895387a.nq.gz
    ├── 46aba8dc123f0c154a4ab5d9e562ee54331f49fc.nq.gz
    ├── 46af2fdeed933fc416073a1dea6f9d8e60757905.nq.gz
    ├── 4746f3f9f8d3658c639677a5e5b1b189a7b43136.nq.gz
    ├── 47cb57232dc42d43a8d0f130191fd8d701b68c14.nq.gz
    ├── 482109f97b0e895973df8098a0b47f0302d495e5.nq.gz
    ├── 4842da51753650633a55c6090b1f3967b9ecd175.nq.gz
    ├── 488bd5002c52aa422b33356d9c2e6fb70f26940c.nq.gz
    ├── 48c65b57c548510dae3f96b72fa22a4ba4c5c07a.nq.gz
    ├── 48e796e1985d2c915b54da6b168fcc68fb141f8a.nq.gz
    ├── 49195415bf50d8f2bc30a1738bc23e32e0a87be7.nq.gz
    ├── 492345ff521c967acfba7eb69502ffff8c34f169.nq.gz
    ├── 49242d6d8b9b7f5dd42e8c9a88434bca448d8500.nq.gz
    ├── 4943114912528b94f5e3c3745c4f77d90744df7a.nq.gz
    ├── 496eaad105253addcd6dc87f44412f8a9333a632.nq.gz
    ├── 4b2604b9afd499fde6c68ff895b223d917bad088.nq.gz
    ├── 4b47d3b8822d55abea736a76eb8bd74a021d82eb.nq.gz
    ├── 4d35ca8094243bb0042e15e5ce28558296953192.nq.gz
    ├── 4e68846a09c157b7d284943ec0a06a0276ec1232.nq.gz
    ├── 4feb14d5f08370cf83a18f2dfbd69a71f4500d35.nq.gz
    ├── 502a3631d492d9acc547cc68ca26580cdadb01fa.nq.gz
    ├── 50ee130c7e911e55f7896a2c7de2becfb69fdc03.nq.gz
    ├── 5158735461550da97a5f9f19bc42762acbce6df2.nq.gz
    ├── 5228d034e4df907e07308efdd19f87e7fb29e457.nq.gz
    ├── 54d49b2f6619173fe78cdbb6e6bad4e487eed7a3.nq.gz
    ├── 550e240808cfb16d6d0272bb14bdc9c2849a6bfe.nq.gz
    ├── 554efc6145c0e3ad49cea54a9f0d395895c7a318.nq.gz
    ├── 56044460df747f683b176f892a588244172bd001.nq.gz
    ├── 565c816f182e3442b96e72d5ad5d1f4fd632ce61.nq.gz
    ├── 597b291785fb5495bae444963d0cf863d17ac6e0.nq.gz
    ├── 59ede841728a380231593c8ed134b906f12a78ea.nq.gz
    ├── 5b2b7d068d633b5e4314c8bf364ebb30f8620d08.nq.gz
    ├── 5c04c269ffe2b48991de58b969b8997f20fc7f54.nq.gz
    ├── 5c1973059570ad3919ab64aea2e69cbe901fa8ba.nq.gz
    ├── 5c87f9ef8722dc119f0e121b012bed3a8a1c893d.nq.gz
    ├── 5ce8777b8675ebd2bc6f1b501828bc2bc36e16cd.nq.gz
    ├── 5cf6588c9ec26155eefe367039ffe42413837bc9.nq.gz
    ├── 5d4c3347f670bc4fb2e989167b93b109d98e3dda.nq.gz
    ├── 5d5efd16e9ba856b08a95c47aa07c16d581b3830.nq.gz
    ├── 5d885057084d68e5539ac48e149467cbca7ce48c.nq.gz
    ├── 5ed4dd55f5262113a3469dbd4824a101ab6b91db.nq.gz
    ├── 5f1d50510d47b2047f4e8c10afc7f2edc3a3eb62.nq.gz
    ├── 5f5d53412320057edcb3e53dc8e73d2033ee9985.nq.gz
    ├── 5f724301db86527b1ca952f707d9982ea53e11cf.nq.gz
    ├── 5f8bc14107862d4259b904fc749d9e42d593dcae.nq.gz
    ├── 5fa5da81af08d97766262d95be56e3b2c5ec4d0c.nq.gz
    ├── 6126c6e4f9a2578b9bcc198254147510c24874d8.nq.gz
    ├── 61e524290e05c02074fa4d316c8f26a34c56ba5d.nq.gz
    ├── 62278b6aac22973ec308a05486baf065f5dd1b75.nq.gz
    ├── 6231aa8954b063039a94dda5a6c506629a49f0e2.nq.gz
    ├── 6340687c3184b3aac4751f8f6388c25ba2e79765.nq.gz
    ├── 63d6dd8dcf5353f3c38a39244a2be22c820dc3a4.nq.gz
    ├── 63ed803846abad3dd3978e7c3753e9dd961615c6.nq.gz
    ├── 64c9b8841f9575fe4cef4108811eb2be5758b26c.nq.gz
    ├── 64d318ec4673e96aea5b3cca8a7e5b0118fd2dac.nq.gz
    ├── 65451561055e203e9c8d80c7058a610a112f316f.nq.gz
    ├── 654c00660b0a5c47be8069b8160a29f80d552b18.nq.gz
    ├── 6555a1c2d8e0a2f9588b89308a8dda2bf9acfd55.nq.gz
    ├── 65a6fbbf394e64bc2dce9eafefc47e4db161039d.nq.gz
    ├── 66d0cbaa0c5cc5f921679c9e5473d3102ac19057.nq.gz
    ├── 66df389916d96b19e2e2c943f6d257a81e3b90a8.nq.gz
    ├── 6888ffe8d94ff1f9ee9dc0bb7f52c0834e1eadc1.nq.gz
    ├── 6914e0414f60dadd6fadf1b650f1340620829e3e.nq.gz
    ├── 694b49f2fadb2cae7403cddc8b0f6b1749854deb.nq.gz
    ├── 69b660988784cad19e9810d9b210fd011f821302.nq.gz
    ├── 6a416f54276b9530860f501a8d8da02d9be62409.nq.gz
    ├── 6d032c73a02627abd9e655efdeaf0fc0ea98969d.nq.gz
    ├── 6d134af742c4713059655bdc3ecbdb1a149e015e.nq.gz
    ├── 6e20706a844b714462a9cb5bf2c0ffbac991154c.nq.gz
    ├── 6e8649d283f0094c681e2178af4af91e088091bb.nq.gz
    ├── 6f327d006bd9b7ff5f0442b437d3a7fd6e4262d8.nq.gz
    ├── 6f5464e3941b6d4c18e0673e5803964afd2e6676.nq.gz
    ├── 706c6751b27b2eb5569911f483c9678e5ccced47.nq.gz
    ├── 70948bd7e2c5e18e57fc5a71aeb4ba88a5372e91.nq.gz
    ├── 70c3b3492c53d9fcb90260bb5d584c0fc47eb406.nq.gz
    ├── 71439cc1c6dc7f6c33b039f424c4ca6b760c4758.nq.gz
    ├── 71a9c8b165fc20ecb3afbbef182a088d73ad4e60.nq.gz
    ├── 71fb4511b8896b4acc862b9bcb53d01115c88131.nq.gz
    ├── 7209ed412ae5e607cbb9138bc822fec66c9dcff2.nq.gz
    ├── 731dd20dd32e36ed3755c197a8de6f9a519db9f0.nq.gz
    ├── 733364a76750f550f268afb92ae4e60a88a902d6.nq.gz
    └── 74aa36ed4f687c64f03c29780aaf485c2b74a8d4.nq.gz

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

[modelcontextprotocol/python-sdk](https://github.com/modelcontextprotocol/python-sdk)

---
*Parsed on 2026-04-09 by [repolex](https://repolex.ai)*
