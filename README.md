# Repolex Knowledge Graph of tox-dev/peryx

RDF knowledge graph data for [tox-dev/peryx](https://github.com/tox-dev/peryx), parsed by [repolex](https://repolex.ai).

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
rlex download tox-dev/peryx
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── b8f0ff6f35c9c0b64bb99582fb1dde56edeeed4c
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── b8f0ff6f35c9c0b64bb99582fb1dde56edeeed4c
│           └── chunk-001.nq.gz
└── blob
    ├── 0003fed8d5878d5bf741464afa55d5a4ca7cfdef.nq.gz
    ├── 00d38a33f72d4a661eb98b9dda1b218791eba306.nq.gz
    ├── 00fec55615ff13b6e64c7c905d4424166a2217aa.nq.gz
    ├── 01c4007426424aa339cb62e50f52533e3a5e67f1.nq.gz
    ├── 0296d4c80227b91af9597b6ae8bfc702a3fb16b6.nq.gz
    ├── 03ffe749695873438ab265e1075cb5947873beba.nq.gz
    ├── 043dceabe67210c7ae38816c4c6a05ffb63c2cba.nq.gz
    ├── 0470cead18461126cdbb5c64772cf7db2ee54a78.nq.gz
    ├── 04a23bbc53826e412634c84de1718c43c6de578e.nq.gz
    ├── 051cfc6c1229ad6981946613041ef1d73fa0e34a.nq.gz
    ├── 0584274b0239608f0d47a708d8cfb836fbfbbcbb.nq.gz
    ├── 05db1030cc48120f14ba76545c6a227331ae45ae.nq.gz
    ├── 063d153f723a4f6cd5b991afdbd599a18768e48d.nq.gz
    ├── 06482eabd9ad572e73c742c98afc5e2aa957eba0.nq.gz
    ├── 07dca893b3b48005aa70924b04149df518b3d724.nq.gz
    ├── 087c946945a33527fcdb8df2b130946986a48191.nq.gz
    ├── 0951ff06f6d3ef4afffd16e254c82eb49ba1a130.nq.gz
    ├── 09941670c7f82780262e31194da1e9f56ec45679.nq.gz
    ├── 0b237edf37fef69a2cafe51fb4558149d01dbd5f.nq.gz
    ├── 0b6a5d3bfe01ae7a455e16f6ea46907eaac9d1d2.nq.gz
    ├── 0bbfa85174878196ea3f8c3e98c1aa217cc70aa7.nq.gz
    ├── 0d4a839d936d264c3b94e462947b204a4b16f824.nq.gz
    ├── 0d5e96863ac2075164738621344a964028156cfb.nq.gz
    ├── 0fd05eeb9bd998cf04e968dce75335906c816743.nq.gz
    ├── 1019f43c4e01eb1096cb492c3ec94fc4e90de574.nq.gz
    ├── 1091f62efce6c5c082ac492cf11e3cf1ef0faca2.nq.gz
    ├── 10a6b55851bca8d530e82edee39efe5cfaca4589.nq.gz
    ├── 10b1e34cfe02e81b58b4127b405c2bccea885957.nq.gz
    ├── 1133e81d1a47098e702186b87e15842fcf158a64.nq.gz
    ├── 114f261ca4076bb722a0e4fd53c52887b690dc55.nq.gz
    ├── 117101fad9a3831d4a28999c67e433997521d549.nq.gz
    ├── 118beca1fefc0ef4752d17bc49515af5eb681b4f.nq.gz
    ├── 12ad96a5b597c7a56a5539dd7a18ccbfcb676861.nq.gz
    ├── 138fc28ab6c4aab2c9c5e662af73162da892750e.nq.gz
    ├── 141229b125f2d9dd8809f916ddd716a8703c4652.nq.gz
    ├── 15ad316bb17974f60328f48839d044b54a0a6cea.nq.gz
    ├── 15c9f63e111b1d90863b67c49ec980c58458d087.nq.gz
    ├── 174950b3807e5b85689e18b595baabcee3f1f966.nq.gz
    ├── 1790f4dade556271367ceab923b94c2075a4c796.nq.gz
    ├── 18a4a374f1d2fc91367c2b27b2aaec5de60ba785.nq.gz
    ├── 194193bed61eadf469a933d9e6eb9ec89eb99ec6.nq.gz
    ├── 1995781aab16a7937f380d6f62b63b0c5071d01a.nq.gz
    ├── 19c083196478c952eb032e25b82ebdee0b2c62a9.nq.gz
    ├── 19c7ee038120c083c28cdce96a432b11751d1855.nq.gz
    ├── 19cb7ad2d551ca3b7231063ef1e70edda24a71e4.nq.gz
    ├── 1a77d1db8b8cc0317ed4a5cd5001393a9ee7e93f.nq.gz
    ├── 1ac61b261387c8b0038b045d6508904291ed78ba.nq.gz
    ├── 1b0bde59f88d843abba963723adf60e80916ca8e.nq.gz
    ├── 1beaf9d309406d8008122361d6c6e2a58ea5c192.nq.gz
    ├── 1c46182f00c8b6a9f0c5ed3bba94f936d68a1eec.nq.gz
    ├── 1c6f941f7c09278bc08446a49d476a17f18f3ef6.nq.gz
    ├── 1cbbfa59e7324f7170a86871784303e9dcd9c506.nq.gz
    ├── 1d1cbb3cf538cd7c9409dffaa177c1e3fd42b8ac.nq.gz
    ├── 1d86375dc73c3d2c8dcacca02ce82e7f58cd5324.nq.gz
    ├── 1e41232bbda771eba72312e726dd34a24cc5e148.nq.gz
    ├── 1ef4f46f5922df48495d97b3e664e2afa730d892.nq.gz
    ├── 1f17b6002267c692f19e766639ddf105d74bf840.nq.gz
    ├── 2053740b48ae247d8c7a5982197f5d3ef2b0aad0.nq.gz
    ├── 209e5a8629b7a8b11541fcc3b042d5173248e742.nq.gz
    ├── 213d64df0c3ae3930ecc2cddd4026ef8950bee34.nq.gz
    ├── 220f93d375a19bb70914391ab389759183167d01.nq.gz
    ├── 2212ca382749e27345e00c70d9edfe62e09ded97.nq.gz
    ├── 228c1121dd80f417527649622a1bf65625910150.nq.gz
    ├── 23abeae7b429706c2c0f98bb3db813313fd00ada.nq.gz
    ├── 242fbc5c2eb1fbce10fbf344b45ac83040285fd9.nq.gz
    ├── 24815093a70cbf6a6065a38102a225ba0fa9cc86.nq.gz
    ├── 2481f01e149e9f51c8c85adb23c96114c438d863.nq.gz
    ├── 2482d91e97ec8e79f65eb1c228cb42010e042cea.nq.gz
    ├── 2493ab0168b03cf5935e3afec4956c31074a0f8c.nq.gz
    ├── 24ac6bf9747d5b745e9b29ddda5343789352cce2.nq.gz
    ├── 2511df584024218146f9a86c94ca94435461657f.nq.gz
    ├── 25a62752beb7fef6bd3527da8a938c6208db4040.nq.gz
    ├── 25d99e2e597d7a74fa2b56a2149f49ba7fec66d8.nq.gz
    ├── 2689d7a762e2bce43b22f852c30062140edc2183.nq.gz
    ├── 2752b9795fabb18c48488899f713ea7e0ba218a3.nq.gz
    ├── 27fc0bf5a20d1f9155753c4b2f2a5a1ffcb49936.nq.gz
    ├── 2810470f944a70603ca7603c9ff920a042c6ca97.nq.gz
    ├── 28aaca378d7f47cb3fa1877a835413411c0c08bc.nq.gz
    ├── 292f8ac97c0a76b74cc92d612b97908e595dd5cf.nq.gz
    ├── 29420dbbe50605873b042d3ee04ccc788074813a.nq.gz
    ├── 29979c204e1a7bbb20bfa805e85e179c482cd1a4.nq.gz
    ├── 29b4bcf7732aab2078dedecad9e189ceb6e4d1ed.nq.gz
    ├── 2a054cadcab69a9660218b19d67859ae23fe050a.nq.gz
    ├── 2a809e8ad6d6b5d41433f58626bed2355f4728dd.nq.gz
    ├── 2ae9b4b39c759587dad8f511e45365732c4a1269.nq.gz
    ├── 2c23f86207aecb083cc8b5a24ed66ea84ea98a56.nq.gz
    ├── 2c428c53a2ba43d5956013491005469a1edc3e6c.nq.gz
    ├── 2c92b2a17b92b35647b775b2ad84791b8055d91d.nq.gz
    ├── 2cb0d4b716fe94837f7bdf35d28d7be3e1c15019.nq.gz
    ├── 2e189f66677c6cbc767f6f6f96b3f7c1f6094ca0.nq.gz
    ├── 2e819b83e9d298d0346cba5d48ec45bb44a3818f.nq.gz
    ├── 2ee64e92580373d0f2f77a0dff4c4355e26185ff.nq.gz
    ├── 2fe615c8fbc3bdf642609198d056ff6d36f071fe.nq.gz
    ├── 31762330e64ad9c42c7825d6f8ce6d4dcd8248f9.nq.gz
    ├── 326fdfd442651e2fc678487903b23182b4ed5e6e.nq.gz
    ├── 32960bca41290b52258aab8be22f72490c84fc2b.nq.gz
    ├── 32ea3e2a3a5ba39533a08c9035c336d52aa0f2a5.nq.gz
    ├── 33099c996b669225d0528dff186c1d8fc140804c.nq.gz
    ├── 335410dec58d6488490b275f5443cf5d94d331c4.nq.gz
    ├── 337e70e7f6c10174a9aeb77e97c8359d843c53f1.nq.gz
    ├── 341314bf56577b511d762e17bec8a635f02dfe6f.nq.gz
    ├── 34672a3111d11dc9a3fb50e1993c83811f6fae8e.nq.gz
    ├── 3589ece96181446174ab43a8382e0ad1a9a67864.nq.gz
    ├── 360d4dc1cf14bed26731ee4fa45a0aeef816d605.nq.gz
    ├── 377844ca942ae5a379a07dfb97ceb726d46d167d.nq.gz
    ├── 38d141f2565f676fdedf5d13c2f0737bac7ee106.nq.gz
    ├── 38f849f20c9722617bf6e24f8e03ecbd1f540f5b.nq.gz
    ├── 39a9df53b739e5cdb974268684756e53facfe971.nq.gz
    ├── 3a567892e1c44adffffcf09d779cd05e7a198b09.nq.gz
    ├── 3a80e84a3f2b8327fde893eddf64ca8f74c428af.nq.gz
    ├── 3afe41008317dfae94e94157dc401906feadd729.nq.gz
    ├── 3bb87c4854883ca4f863049a9b7545a920f5407d.nq.gz
    ├── 3cd4ba009c96246311a1534e27610eab899283ed.nq.gz
    ├── 3ced9fa0d7643dce2781af1924a17d56460679ff.nq.gz
    ├── 3dc3598c7a5577ae9d77d41046cce3685251e50a.nq.gz
    ├── 3e19785eaa53acd487e35777c54060166190961e.nq.gz
    ├── 3e9f061e88bd1ff6e4a44c62d976229a804742e6.nq.gz
    ├── 3ee558f43530c131781a09cc160908f56ad8fd9d.nq.gz
    ├── 3f02b5bfed9fe742495640b01b634aaa24b9c384.nq.gz
    ├── 3f83c9ebf31bb37a4214febe2b33982e4e1872e6.nq.gz
    ├── 403f7396d772fc0813190a8930cf499b82d757b6.nq.gz
    ├── 4044b968a26ffbc74092ec4f919671809074becc.nq.gz
    ├── 40db5f4e8611e01cffd5b0c482ab659324c1c7b9.nq.gz
    ├── 41ffac854dfa626c2aa36347b2cdd32f411bf3e5.nq.gz
    ├── 428324553e8e05a3c0796bb270de50c4347b80e0.nq.gz
    ├── 4304c800b6c7b763533fb2defcc468fa91235e9e.nq.gz
    ├── 43cbc905c021d6bbf83090b61564c4b8a26ea4d2.nq.gz
    ├── 43d63055a081f214181f80faa4d2dc0697802b31.nq.gz
    ├── 44c1f41f40210ef36b72a4f1cf5dfd4ee5b7338c.nq.gz
    ├── 44c6c67cf884969c0afccc53090475537144ae6a.nq.gz
    ├── 44ec28edc108a2e4cba9547d4c70ad7e1ef04b9e.nq.gz
    ├── 461d9227177bcb89dc5ac3f8bc0c39069390c476.nq.gz
    ├── 473bcf9b73ac82a4057dd990a24474d1719de851.nq.gz
    ├── 476b1b51a63f2b0ecf932f8447dc56842b00a7cc.nq.gz
    ├── 47849639c36701168c648508dfcedb6c656c227c.nq.gz
    ├── 47f7db5055d3e6c4087d3b6d586ae5e1205f3236.nq.gz
    ├── 4867edc35d3e8c39a208c16b96da3a4129d67b3e.nq.gz
    ├── 4888287203d7c5ca529cbba1966351f3d32b1fe1.nq.gz
    ├── 48e174c540bd816465b9c8b4bfcf4d57558fef97.nq.gz
    ├── 4912f8594d70f83dfc37d2b132e88f32a9590feb.nq.gz
    ├── 49ca894a7054d49b5802347994c3bc9cf941c955.nq.gz
    ├── 49e149c4e996b048d48275bdf3062ef17d4eaf2e.nq.gz
    ├── 49f485985aedffb2a61cc411cbbfb7bcc1133bb1.nq.gz
    ├── 4bb745b6d5c4c3790088414e1ebcbf2e8db26b53.nq.gz
    ├── 4c7b621bfe0bf8efb4e5f8e8dd1205153e882fda.nq.gz
    ├── 4d1200105162f4c222336f4e41e3034fa4ac626d.nq.gz
    ├── 4d5c5ecdd36766783fd2770fa4061f83a8c1a018.nq.gz
    ├── 4d9d2c27d128b59930eeb2d4e63e9ba47de16ed8.nq.gz
    ├── 4e51daad0423192aa3585a2c6ceb9bba91fd366a.nq.gz
    ├── 4f2eb5f6f47a38810e588a31ee13ed5c2cbe6ae8.nq.gz
    ├── 4f31c3bd3e6ee6fb5d1cd2de0298ea616ac9161e.nq.gz
    ├── 4f8ee2082965531677b648b5d726303ef6699ffd.nq.gz
    ├── 50ac7ee0a417ca0cd919eb361a00b2cb7ed0c989.nq.gz
    ├── 50e9b7a37f9d118f818c348b5cb5845cae89bedc.nq.gz
    ├── 51bff7fcd277491ed1dc3c0ffc0b713c2c89fe0b.nq.gz
    ├── 529b8570bbb0c7389e8de27daec58d698b0c03cf.nq.gz
    ├── 531de655ad43001823e5f473d8bf9641d2c5b17e.nq.gz
    ├── 5363f84a0b9078211c52bfeff630dd478b2237c1.nq.gz
    ├── 5410c4e93aaa37fabcded6992c49826b9229022b.nq.gz
    ├── 5477fe566ee5e50d4969caa1909ba002561ac175.nq.gz
    ├── 54a1df6c37ccbcade21418cf9ca2c0c148b4d3be.nq.gz
    ├── 54da71070ff67762e5fcb35ce938fa764f2e553f.nq.gz
    ├── 550ac36c3c6e2bb713c30bed73cb93bf90ef0233.nq.gz
    ├── 5630d6f4350f3bd2eb7c321065dba8983b605b8f.nq.gz
    ├── 5751bb0490a086aade2757f500f5f88ffb119677.nq.gz
    ├── 5763a85a487feee1fbd1dd08447b6fa028958687.nq.gz
    ├── 57ce3ed3bbcb003da0d2e92e06f6b175d2c47d92.nq.gz
    ├── 583d036d59763c3cd23e7fa227d3fee12997f207.nq.gz
    ├── 58dabaf84c2d02d10ca6dde45322c0c8e2a887c0.nq.gz
    ├── 58f7763f0429d8677e5ea6d7abd9a2849e787ab2.nq.gz
    ├── 59d4182bacd41c163d0e6ed0c0b5f971ebe65cfa.nq.gz
    ├── 5a5b5b534164f29d6451803fc8e3291bf85fe648.nq.gz
    ├── 5afb4a9a93896b80b9d526ba320387182f1e33f7.nq.gz
    ├── 5b53ba345569ae25bebddfb58ea0071a20084c2a.nq.gz
    ├── 5bb26c5a69f0a5508c84f788ae2ce5f3461a41d4.nq.gz
    ├── 5c0913e349cff27ffb7b7798cde907b8e87040ab.nq.gz
    ├── 5c7dc580fe4fa58212cd845f651aff909c452f43.nq.gz
    ├── 5cb528c3acd5e32bdada91da65f46516e8fe05a7.nq.gz
    ├── 5d269176e226bf858637dca1c70bf2ea6ff90a9b.nq.gz
    ├── 5d560d761638c6fd05992116be926d7c6e5b76ae.nq.gz
    ├── 5d783bb14976de4a485998b8df7d5894f1f4e1b6.nq.gz
    ├── 5dcc9bce26b047850ff6d718aa28b85fa79bfd9d.nq.gz
    ├── 5df81b708280e47853de3627577140b3c78416d0.nq.gz
    ├── 5e2cdb541fb4ea6e41ee30340b3753a931b10f26.nq.gz
    ├── 5e797a9025527935dac54ed53fb9cb027ccd147c.nq.gz
    ├── 5eb233d465ac8eef90fa3f2ba736805f3652e48a.nq.gz
    ├── 5f0cdee64bc63e12d39f1408d92ac70b1c2b9f5b.nq.gz
    ├── 5f797aa9598dd4a1a4c1be0bee914fc8ef9a5dfd.nq.gz
    ├── 5f9f07370104b44d25f43b6963b7e933771ca3c3.nq.gz
    ├── 5fda48ca47fd246d517094b4cac9f83d8105fd72.nq.gz
    ├── 600c696443e530a55d7e6f5e57cbb3b1745b8056.nq.gz
    ├── 6032114a18ac6a7e6469e47b889fb8efde808d48.nq.gz
    ├── 60865cab1b6a0c5dd42f6bd94b426b0a39783583.nq.gz
    ├── 60eca2ff0e2a4bf05c7823ece57b5eff75c8073c.nq.gz
    ├── 6326321d24d9a7a41b55571f7f4be628c1dd0681.nq.gz
    ├── 6361e7e7fd304c5519a7998e1df15087033d25eb.nq.gz
    ├── 636929b12788b49b1c5bed3fd0ce358805d5d582.nq.gz
    └── 639dbad2f511f26ccc657c760baa0ff4e4f21144.nq.gz

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

[tox-dev/peryx](https://github.com/tox-dev/peryx)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
