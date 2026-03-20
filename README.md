# Repolex Knowledge Graph of anthropics/anthropic-sdk-ruby

RDF knowledge graph data for [anthropics/anthropic-sdk-ruby](https://github.com/anthropics/anthropic-sdk-ruby), parsed by [repolex](https://repolex.ai).

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
lexq download anthropics/anthropic-sdk-ruby
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 01fa9915a35f5eee3ca41ea75cd483ef5012c10d.nq.gz
│   │   ├── 565f9de92a76da95a51afe0b854394151f9845ae.nq.gz
│   │   ├── 571838ad86ff49e866d7de1d96cc622cd2928851.nq.gz
│   │   ├── 5e1a37347aa2b8332374795fff9aa1e8f0f4e807.nq.gz
│   │   ├── 96750038bb111907da355f3f8e4ac6744797f074.nq.gz
│   │   ├── a1d9574f2ffc4c857f56e2edfc6db62757fd28d0.nq.gz
│   │   ├── b6fd5e4a006c0720e5256fdece4943e45bb789c8.nq.gz
│   │   ├── c8518b2bec257e97c27fcbaec3ea4cef4066dfda.nq.gz
│   │   ├── cd8ed5bbcada949ff5c374730281e125327e3087.nq.gz
│   │   ├── f283286a298cb92c95c6b000b2ea8c412396ec7a.nq.gz
│   │   └── f6ea777542d99d669007bd9a739bfa1ad1ca1f73.nq.gz
│   ├── lsp
│   │   ├── 01fa9915a35f5eee3ca41ea75cd483ef5012c10d.nq.gz
│   │   ├── 565f9de92a76da95a51afe0b854394151f9845ae.nq.gz
│   │   ├── 571838ad86ff49e866d7de1d96cc622cd2928851.nq.gz
│   │   ├── 5e1a37347aa2b8332374795fff9aa1e8f0f4e807.nq.gz
│   │   ├── 96750038bb111907da355f3f8e4ac6744797f074.nq.gz
│   │   ├── a1d9574f2ffc4c857f56e2edfc6db62757fd28d0.nq.gz
│   │   ├── b6fd5e4a006c0720e5256fdece4943e45bb789c8.nq.gz
│   │   ├── c8518b2bec257e97c27fcbaec3ea4cef4066dfda.nq.gz
│   │   ├── cd8ed5bbcada949ff5c374730281e125327e3087.nq.gz
│   │   ├── f283286a298cb92c95c6b000b2ea8c412396ec7a.nq.gz
│   │   └── f6ea777542d99d669007bd9a739bfa1ad1ca1f73.nq.gz
│   └── repolex
│       ├── 01fa9915a35f5eee3ca41ea75cd483ef5012c10d.nq.gz
│       ├── 565f9de92a76da95a51afe0b854394151f9845ae.nq.gz
│       ├── 571838ad86ff49e866d7de1d96cc622cd2928851.nq.gz
│       ├── 5e1a37347aa2b8332374795fff9aa1e8f0f4e807.nq.gz
│       ├── 96750038bb111907da355f3f8e4ac6744797f074.nq.gz
│       ├── a1d9574f2ffc4c857f56e2edfc6db62757fd28d0.nq.gz
│       ├── b6fd5e4a006c0720e5256fdece4943e45bb789c8.nq.gz
│       ├── c8518b2bec257e97c27fcbaec3ea4cef4066dfda.nq.gz
│       ├── cd8ed5bbcada949ff5c374730281e125327e3087.nq.gz
│       ├── f283286a298cb92c95c6b000b2ea8c412396ec7a.nq.gz
│       └── f6ea777542d99d669007bd9a739bfa1ad1ca1f73.nq.gz
└── blob
    ├── 00035f4a12da1428f8f649413fb54fbb6d2ad236.nq.gz
    ├── 0003a4d8f8ca51336d36cb44e9235944f13e79fd.nq.gz
    ├── 003c237c133ab80b9be1a7c0d205699ca5f5fa04.nq.gz
    ├── 004c697b0c387cab35eb9d859b4b2daf72e5160e.nq.gz
    ├── 006816f03dccee73bba83cf27c47bebe77e1912a.nq.gz
    ├── 006994efb4639a092d85684ae0d8cd8a86aaf523.nq.gz
    ├── 00875a33d2332a846e357fa2e4cc28f91fc35f5b.nq.gz
    ├── 009fafad64eee68159c5dff87a3c1cc28ab59bce.nq.gz
    ├── 009fe64be3efeb31873ef5eb2958bdf6a82bc761.nq.gz
    ├── 00ba1f7ad8480e1a6d9b0a46b15cc8eb41fe4011.nq.gz
    ├── 00c67a10c392e33218b4c44aa3e9d8a37dfe8111.nq.gz
    ├── 00fb8f1dfbac4fb59ad7a34b39c5adfc8b804a3c.nq.gz
    ├── 0106577fa1ed1a3538ff08aae770f34e8ee16070.nq.gz
    ├── 012f055c8d5d1e52caa199197a41d11e7a9c0825.nq.gz
    ├── 0135afee67d3662643bb989e26597935c391783a.nq.gz
    ├── 01372289bbcd58e0ba4e4430022e3e7f6bff81e5.nq.gz
    ├── 01383e7a5d8e719136ec89fbfa67f9ba6158f793.nq.gz
    ├── 017b806de5eb134d97c68c3c42464301f2d66acd.nq.gz
    ├── 01ad671ff7ed102417390125704cd996e455f3af.nq.gz
    ├── 01f6fe89509a266839ee6193fb3c75286f6d3606.nq.gz
    ├── 0201c2a1a447af9623aab813c0c473191993c770.nq.gz
    ├── 0201e292811cba7cc2cf5bc7aa68d381aa4e35e9.nq.gz
    ├── 022320302e548f99d8854da0727809ba53935d83.nq.gz
    ├── 02733f9b0bfdfe51bc98da523fca946495448c6e.nq.gz
    ├── 0275d362b2d8d4046c1827321bead7ec00a9bb9b.nq.gz
    ├── 029ed1172c5f7d8f8fdc5569abf4d61c8f8a4439.nq.gz
    ├── 02ab2d128bd92f1960c15cdfa89ccf5339eb5d32.nq.gz
    ├── 02abac4b0e00628e1d74b16ffaa1d266e0bb9a6d.nq.gz
    ├── 02b1642a36ce44ffdfa4ad6b2f6bdd9d4521a6cc.nq.gz
    ├── 02cbe062ccd59a239fc8ffcb13e9530f02c10607.nq.gz
    ├── 02cf93dd121d8308a1da79eca77584f9855db696.nq.gz
    ├── 02d4c8e6c6dbcaf1f6556555ace3ef235ce46fa0.nq.gz
    ├── 02e57b97d2c481992dc10063f01dbb2280c925a7.nq.gz
    ├── 02e5f12ac8c52847f29c1d222628a5f8f0c06243.nq.gz
    ├── 02fa959d2aa4454862180dc2510f0b9526404226.nq.gz
    ├── 0302084053d7bbd431d306b51ef231ed2f3084f0.nq.gz
    ├── 030bf1bf7cd78f269b09198de5fcec5634797d26.nq.gz
    ├── 033d19b84c171152996aadaff5c0c7b251ddfe92.nq.gz
    ├── 03484f39242648e9725527fc061ca4564e03b7fd.nq.gz
    ├── 034f60e3dcfbab1e0437ad33211c465394278428.nq.gz
    ├── 03c0a2703ac43eb38124b49c9b55f9f6097925cc.nq.gz
    ├── 03cbe49273cd68be124fa0ceec089d4d05b94496.nq.gz
    ├── 03de615431c95ecada2535b3c7918d67f005cb73.nq.gz
    ├── 03e520a4d13613f906c5670780a45dfb29b63299.nq.gz
    ├── 041d10feaad113fd6f591a54d70d734d366bfeb5.nq.gz
    ├── 0422c6c94a0d950d1d5bfab13db4431e42b71e17.nq.gz
    ├── 0429e09b0bf4f07695234aee4b3630ce2e825631.nq.gz
    ├── 044219982d36433e358d259ed659d286e4ca890a.nq.gz
    ├── 0449d1d62c15cdcbe9876cd45d5ad468eef31323.nq.gz
    ├── 044eb9b85f10c4b2a8e0ac3ff4c729a57964840f.nq.gz
    ├── 046ed2b77367e926f4ddbd7744ba64dff35cb487.nq.gz
    ├── 04933c0f350f492625aae135f35dea086a8aca4f.nq.gz
    ├── 04b81ca8e5b454fcaa91cb656c45ccd2e51307fc.nq.gz
    ├── 04c43577f8c46f301e1d0febe20f0286bfbe9166.nq.gz
    ├── 04cc8d773c41600e7ea08c2a02d26e093d2f384b.nq.gz
    ├── 04e3de92c5e44c709107cfd1e73f97793dde9648.nq.gz
    ├── 04f20ec0a592827c0df7b69d261f2e41d186cca7.nq.gz
    ├── 04f7ee60378aea1ddda8cdf1f0ad6dcbb861415f.nq.gz
    ├── 04fd38178d15ddd3aeebf7c2584925b12c5e7c2a.nq.gz
    ├── 050b12deb74fd17cb04780175d832a6ce51d6f3a.nq.gz
    ├── 053da5c58bfccbc73660fc2e5221448272fd22de.nq.gz
    ├── 0551822c8d119cf5f17bf057e6d68907f0c3826e.nq.gz
    ├── 0566019284da3b14422db863f7f9a1eb2fd381ba.nq.gz
    ├── 0588605d62e5c667f4126de16259de4d921c78b2.nq.gz
    ├── 058a3fdf6dfe55e666e4c6ba9a4697cf8e8c8688.nq.gz
    ├── 059314dfd5d685fe2dc9f266e45861023d07d3b0.nq.gz
    ├── 0598dc83ea7e3f5d632bcd22f16009d267e08142.nq.gz
    ├── 05a5406b7b8d4b2098dcb0f077ba41f24a8df5d0.nq.gz
    ├── 05a766be5322c17325484f6bba761e61c262ef8f.nq.gz
    ├── 05b6fb9d5cf18f1625837fd16de4db66e026da52.nq.gz
    ├── 05c5df9a62b5e89b60b4a2b405cf878d74241e8e.nq.gz
    ├── 05c61dd83f547ce4b9bc132ee1d9f6f00fc685c5.nq.gz
    ├── 05ca80226097dee5b4c854d308abb206b17193ef.nq.gz
    ├── 05cdab240b7e459f7cc40ad157c08543b78d701a.nq.gz
    ├── 05e0297de915983f73a36adbe6eff92024e6cfb4.nq.gz
    ├── 05e9a5d463defe1ab5c6899d40de9af2e1d3c248.nq.gz
    ├── 062256ed3f0ff5a642c738e362bb69a01251686d.nq.gz
    ├── 064334a38466e1dd586bca69a43b195242497194.nq.gz
    ├── 0660cba1253ad2cba7abfc7912a7b129cb1f3f31.nq.gz
    ├── 066e2f456e58ef0b90c15c93bf7fc57dbc5628b6.nq.gz
    ├── 06728362f37b6c5468e3121157f7f231b0ff4de0.nq.gz
    ├── 06adfee2eb69369fad12866e9c1286bf2eaea7aa.nq.gz
    ├── 06b62d390a28afc89941e11595616c81a9909c03.nq.gz
    ├── 06b9f1a3574b7a13264735b91ec48db02cf5cd85.nq.gz
    ├── 06d53c8f66506364614f69064e44e52226e3c3d9.nq.gz
    ├── 06f07680446af61e4a7922f8d210f3bf5e1c9560.nq.gz
    ├── 06f43b52136408d8cdaa1291023fe30de330a21d.nq.gz
    ├── 06fe8a2d87f39a0c4413e71713cea09e85b22e71.nq.gz
    ├── 070acff875896fdd3be6f1b8cff4f3bdca1f6572.nq.gz
    ├── 071510e6b889c1484fc1f2345a84cd043ff6959c.nq.gz
    ├── 071a8d32d146ba98accef0868f63e634df994f7f.nq.gz
    ├── 071b6e8c54b31dc214ad46c2675b0792f0de857f.nq.gz
    ├── 07444c10b49a2df9060008fa8a7e207ababc19a2.nq.gz
    ├── 0749a1f7e347e47b0b0f93436eabf79cdd41a3a1.nq.gz
    ├── 074cb70cfd642b9ce6b6e451dbd9426e73117123.nq.gz
    ├── 07717294ad34e2480b2465178e5e0818958526a4.nq.gz
    ├── 07a0217f689d33dd90ed4869f1d1300569b0d819.nq.gz
    ├── 07a4c12635be1320a2db305f3f548290e256a48f.nq.gz
    ├── 07bd173d6a4ccaf7dc096f3554f76d1b45905c35.nq.gz
    ├── 080c48666ead5049056a69e84fa49ef3357c2130.nq.gz
    ├── 0819733156498d53432225059b4dda7143737d4f.nq.gz
    ├── 08260d97a9d7539b4ade17b91ba79c295d5e5e1b.nq.gz
    ├── 082a0836f786be0af8ccaa20e13cd3c0b87d494b.nq.gz
    ├── 082d477990a99413a20cbb890c6433d30b600e1a.nq.gz
    ├── 084374b7f0fe48a5dee938c97f28b75b89979c6c.nq.gz
    ├── 088eb256f0098a493c8497c0fe70378c86b6ee80.nq.gz
    ├── 088f52e7a253bb06acf9ae6fa6a75ebf5449060d.nq.gz
    ├── 08957fc1ff961fd5de9a774ff641fdbf9fdfa59f.nq.gz
    ├── 0899de95e2b9d8a90cfd09bc17fb9f22af02eb63.nq.gz
    ├── 08ae94869f168b50bf02d348e83a4e03f174afcc.nq.gz
    ├── 08b0dbeb6f09b7b9302c91e21d6f3199b94966dd.nq.gz
    ├── 08d099bf3ca96fe330388c8d86148212285b34b6.nq.gz
    ├── 09189ed1e27eb5e8a6692fba7478014bd50a9c86.nq.gz
    ├── 091c528187a1910a2d8d5834074c63f7d9e6f008.nq.gz
    ├── 0930a109dbd2ba78585becc8c94a530d9cc9f947.nq.gz
    ├── 094543e8135d14af8f8e787cb6fbd5eb9c3df5d6.nq.gz
    ├── 0947597d4308736b3a17bee843237cbf73a79814.nq.gz
    ├── 0957fcb177a7d8681bb87d5c2a5e6890f9cbb798.nq.gz
    ├── 0960798735e8ca4dfb46f4410776f5c31eb228f7.nq.gz
    ├── 0964bfe22440395897d7ab2ad9f5b051294d5b7a.nq.gz
    ├── 09692591a53104fe71714698a4b0fe71519a97d1.nq.gz
    ├── 0972169d4adf367979dd076ec06aaad59e4c2f57.nq.gz
    ├── 098422f6171376d66bdf608b0f3aa52644ebdaad.nq.gz
    ├── 09cd821b277ec179d2159e563903345ff3d00b9d.nq.gz
    ├── 09cf8bd21f74480d9bede77f98af09d1e6a46735.nq.gz
    ├── 09e0575a46f855a241a3c564616c331e11574f5e.nq.gz
    ├── 09e8e42a9e3ac4cbbd6c81ce1888848b32629479.nq.gz
    ├── 09eb3320c88e3b67f7eee8db35425445d10e9474.nq.gz
    ├── 09f2520dea8ba30e7397b141d051771c42419506.nq.gz
    ├── 09f62de66d9ee0eba5a6667c1a4df1144a86a4d8.nq.gz
    ├── 0a0c2d3251f41c33005a68aff34af799002d55ca.nq.gz
    ├── 0a113b97fd53c914786388afb3e8fa348530b1f4.nq.gz
    ├── 0a5c25d53e60422259b7046c8fa51eac583d4f26.nq.gz
    ├── 0a655359dbe86ca6a8d1da587d0d7cee0af67d9a.nq.gz
    ├── 0a6f8c9b560207da04703c379e9be2833282b7b7.nq.gz
    ├── 0aa64b099e316b06ac42fe41128a9029b10ef9ee.nq.gz
    ├── 0ac8f30974af6b6d4dec2d9bf7bcd7e572574b55.nq.gz
    ├── 0ae834fef558763cb44af1b5bd49cebb49a07355.nq.gz
    ├── 0b1a8475b333085621dca52c272682ee7cd451f8.nq.gz
    ├── 0b31ebab99689bf413f84aeae54e114d446b5f1d.nq.gz
    ├── 0b3609a089d7bffe0b7820d5506a587c7fbcfee8.nq.gz
    ├── 0b5f61e1fc4e0db108f99640f23224859aeab9fd.nq.gz
    ├── 0b828f0763f3fc110fec72a0e22d9994069b4178.nq.gz
    ├── 0b8a95a4c9bb1e56e4b2a4a684faf59273f95ba4.nq.gz
    ├── 0b9f701a6ab7708adf1222ed23d58de1574bf4dd.nq.gz
    ├── 0bee1f7b6fa9661fe946f957dc5a89da5df1ebf5.nq.gz
    ├── 0bf56230b500efea4d1ea8873d389775d3c5f8f5.nq.gz
    ├── 0bfa161d86518a952a9e7f71f3fcc403782a4554.nq.gz
    ├── 0c08b4ec240392596e566fd94abd5981178d074e.nq.gz
    ├── 0c0ca7e3ce791dba03eba5e8b2329d7dc5829e51.nq.gz
    ├── 0c0cef2be1005721ecbf1e8064f13feb2937dc9b.nq.gz
    ├── 0c22fef74cfb12adb26370560003729af87f9c92.nq.gz
    ├── 0c2e062173a86f81031296ca4263fba9dd0a9ece.nq.gz
    ├── 0c46e833903f33296d5429308163cae4c06be1f7.nq.gz
    ├── 0c4b85dbdf3a320e1fc250a01fa16c7c83d568c5.nq.gz
    ├── 0c5fb2df7b444e5b4d7382adea750857e36f7ebf.nq.gz
    ├── 0c7eb500d1df2dc8ec870f50ecf68b3a02c61d12.nq.gz
    ├── 0c82a1cf119e69ced493f0dbf4283d7c136ff90d.nq.gz
    ├── 0cb6ae8d3510622e7735f64be2d0d78c1bc8a5f1.nq.gz
    ├── 0cfede80c762ab847e33e3e1cb8f6ff596664ff7.nq.gz
    ├── 0d02b3d2bc4a1e0023abf0e328daf1cf0c3c88f7.nq.gz
    ├── 0d0681f6ad44740e3c19f09faf025680d30a2481.nq.gz
    ├── 0d13b7c2367d51fd85ebacc4f3c578ce73a871c4.nq.gz
    ├── 0d1826c853784191db09b53e675775523512c12c.nq.gz
    ├── 0d37f8abbf0ec3095754e6879f188120c8944ee9.nq.gz
    ├── 0d5448a7811cfa08d541e9dc6c902b57ebcbd05e.nq.gz
    └── 0d73321447e97fe8b53235cf996b7a1cf6bffa0c.nq.gz

6 directories, 200 files
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

[anthropics/anthropic-sdk-ruby](https://github.com/anthropics/anthropic-sdk-ruby)

---
*Parsed on 2026-03-20 by [repolex](https://repolex.ai)*
