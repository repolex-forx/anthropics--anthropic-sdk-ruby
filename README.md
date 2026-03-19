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
│   │   └── f6ea777542d99d669007bd9a739bfa1ad1ca1f73.nq.gz
│   ├── lsp
│   │   └── f6ea777542d99d669007bd9a739bfa1ad1ca1f73.nq.gz
│   └── repolex
│       └── f6ea777542d99d669007bd9a739bfa1ad1ca1f73.nq.gz
└── blob
    ├── 006816f03dccee73bba83cf27c47bebe77e1912a.nq.gz
    ├── 006994efb4639a092d85684ae0d8cd8a86aaf523.nq.gz
    ├── 009fafad64eee68159c5dff87a3c1cc28ab59bce.nq.gz
    ├── 00c67a10c392e33218b4c44aa3e9d8a37dfe8111.nq.gz
    ├── 01372289bbcd58e0ba4e4430022e3e7f6bff81e5.nq.gz
    ├── 01383e7a5d8e719136ec89fbfa67f9ba6158f793.nq.gz
    ├── 017b806de5eb134d97c68c3c42464301f2d66acd.nq.gz
    ├── 01f6fe89509a266839ee6193fb3c75286f6d3606.nq.gz
    ├── 0201c2a1a447af9623aab813c0c473191993c770.nq.gz
    ├── 0201e292811cba7cc2cf5bc7aa68d381aa4e35e9.nq.gz
    ├── 02733f9b0bfdfe51bc98da523fca946495448c6e.nq.gz
    ├── 0275d362b2d8d4046c1827321bead7ec00a9bb9b.nq.gz
    ├── 02ab2d128bd92f1960c15cdfa89ccf5339eb5d32.nq.gz
    ├── 02cf93dd121d8308a1da79eca77584f9855db696.nq.gz
    ├── 02d4c8e6c6dbcaf1f6556555ace3ef235ce46fa0.nq.gz
    ├── 02e5f12ac8c52847f29c1d222628a5f8f0c06243.nq.gz
    ├── 02fa959d2aa4454862180dc2510f0b9526404226.nq.gz
    ├── 034f60e3dcfbab1e0437ad33211c465394278428.nq.gz
    ├── 03c0a2703ac43eb38124b49c9b55f9f6097925cc.nq.gz
    ├── 03cbe49273cd68be124fa0ceec089d4d05b94496.nq.gz
    ├── 03de615431c95ecada2535b3c7918d67f005cb73.nq.gz
    ├── 03e520a4d13613f906c5670780a45dfb29b63299.nq.gz
    ├── 041d10feaad113fd6f591a54d70d734d366bfeb5.nq.gz
    ├── 044219982d36433e358d259ed659d286e4ca890a.nq.gz
    ├── 0449d1d62c15cdcbe9876cd45d5ad468eef31323.nq.gz
    ├── 044eb9b85f10c4b2a8e0ac3ff4c729a57964840f.nq.gz
    ├── 04b81ca8e5b454fcaa91cb656c45ccd2e51307fc.nq.gz
    ├── 04f7ee60378aea1ddda8cdf1f0ad6dcbb861415f.nq.gz
    ├── 04fd38178d15ddd3aeebf7c2584925b12c5e7c2a.nq.gz
    ├── 053da5c58bfccbc73660fc2e5221448272fd22de.nq.gz
    ├── 0588605d62e5c667f4126de16259de4d921c78b2.nq.gz
    ├── 0598dc83ea7e3f5d632bcd22f16009d267e08142.nq.gz
    ├── 05a5406b7b8d4b2098dcb0f077ba41f24a8df5d0.nq.gz
    ├── 05a766be5322c17325484f6bba761e61c262ef8f.nq.gz
    ├── 05b6fb9d5cf18f1625837fd16de4db66e026da52.nq.gz
    ├── 05c5df9a62b5e89b60b4a2b405cf878d74241e8e.nq.gz
    ├── 05cdab240b7e459f7cc40ad157c08543b78d701a.nq.gz
    ├── 05e0297de915983f73a36adbe6eff92024e6cfb4.nq.gz
    ├── 05e9a5d463defe1ab5c6899d40de9af2e1d3c248.nq.gz
    ├── 064334a38466e1dd586bca69a43b195242497194.nq.gz
    ├── 066e2f456e58ef0b90c15c93bf7fc57dbc5628b6.nq.gz
    ├── 06b9f1a3574b7a13264735b91ec48db02cf5cd85.nq.gz
    ├── 06d53c8f66506364614f69064e44e52226e3c3d9.nq.gz
    ├── 06f07680446af61e4a7922f8d210f3bf5e1c9560.nq.gz
    ├── 06f43b52136408d8cdaa1291023fe30de330a21d.nq.gz
    ├── 06fe8a2d87f39a0c4413e71713cea09e85b22e71.nq.gz
    ├── 071a8d32d146ba98accef0868f63e634df994f7f.nq.gz
    ├── 07444c10b49a2df9060008fa8a7e207ababc19a2.nq.gz
    ├── 07717294ad34e2480b2465178e5e0818958526a4.nq.gz
    ├── 07bd173d6a4ccaf7dc096f3554f76d1b45905c35.nq.gz
    ├── 080c48666ead5049056a69e84fa49ef3357c2130.nq.gz
    ├── 0819733156498d53432225059b4dda7143737d4f.nq.gz
    ├── 082d477990a99413a20cbb890c6433d30b600e1a.nq.gz
    ├── 084374b7f0fe48a5dee938c97f28b75b89979c6c.nq.gz
    ├── 088eb256f0098a493c8497c0fe70378c86b6ee80.nq.gz
    ├── 08b0dbeb6f09b7b9302c91e21d6f3199b94966dd.nq.gz
    ├── 08d099bf3ca96fe330388c8d86148212285b34b6.nq.gz
    ├── 091c528187a1910a2d8d5834074c63f7d9e6f008.nq.gz
    ├── 0930a109dbd2ba78585becc8c94a530d9cc9f947.nq.gz
    ├── 094543e8135d14af8f8e787cb6fbd5eb9c3df5d6.nq.gz
    ├── 0947597d4308736b3a17bee843237cbf73a79814.nq.gz
    ├── 0957fcb177a7d8681bb87d5c2a5e6890f9cbb798.nq.gz
    ├── 0960798735e8ca4dfb46f4410776f5c31eb228f7.nq.gz
    ├── 0972169d4adf367979dd076ec06aaad59e4c2f57.nq.gz
    ├── 09cf8bd21f74480d9bede77f98af09d1e6a46735.nq.gz
    ├── 09eb3320c88e3b67f7eee8db35425445d10e9474.nq.gz
    ├── 09f2520dea8ba30e7397b141d051771c42419506.nq.gz
    ├── 0a0c2d3251f41c33005a68aff34af799002d55ca.nq.gz
    ├── 0a113b97fd53c914786388afb3e8fa348530b1f4.nq.gz
    ├── 0a5c25d53e60422259b7046c8fa51eac583d4f26.nq.gz
    ├── 0a655359dbe86ca6a8d1da587d0d7cee0af67d9a.nq.gz
    ├── 0a6f8c9b560207da04703c379e9be2833282b7b7.nq.gz
    ├── 0aa64b099e316b06ac42fe41128a9029b10ef9ee.nq.gz
    ├── 0b1a8475b333085621dca52c272682ee7cd451f8.nq.gz
    ├── 0b31ebab99689bf413f84aeae54e114d446b5f1d.nq.gz
    ├── 0bf56230b500efea4d1ea8873d389775d3c5f8f5.nq.gz
    ├── 0c08b4ec240392596e566fd94abd5981178d074e.nq.gz
    ├── 0c0ca7e3ce791dba03eba5e8b2329d7dc5829e51.nq.gz
    ├── 0c4b85dbdf3a320e1fc250a01fa16c7c83d568c5.nq.gz
    ├── 0cb6ae8d3510622e7735f64be2d0d78c1bc8a5f1.nq.gz
    ├── 0cfede80c762ab847e33e3e1cb8f6ff596664ff7.nq.gz
    ├── 0d0681f6ad44740e3c19f09faf025680d30a2481.nq.gz
    ├── 0d13b7c2367d51fd85ebacc4f3c578ce73a871c4.nq.gz
    ├── 0d5448a7811cfa08d541e9dc6c902b57ebcbd05e.nq.gz
    ├── 0da497378d9a98598e7ddec77d4baef9f337e0d3.nq.gz
    ├── 0dae32bf1f663ea89e88f1da9ae0699ce44447f1.nq.gz
    ├── 0daece9d7c4ef2c8c5b6bb187c98ec8d6ee37954.nq.gz
    ├── 0db6361eccc303235633397e73ea275319af4473.nq.gz
    ├── 0dce413923f9e53b2db06f8fe4af111b12b908ee.nq.gz
    ├── 0df7cc0c5094c30e44a16b9355b98c6c0d43c02d.nq.gz
    ├── 0e0d49ac4a5ca2e29d2527f070e167be8a82dec2.nq.gz
    ├── 0e5d7175914ba35f8a2f4a71590229b406ac847c.nq.gz
    ├── 0e88312648df7dac1d59630f8169a954d0073d53.nq.gz
    ├── 0ecd21087bd849cb98a04f222e3741c8d4cd5e40.nq.gz
    ├── 0eee0c2b3b2bddb04587c442ec0c734d9c5af633.nq.gz
    ├── 0f443fe4823bc7266dd4754dfce762b3bd96a211.nq.gz
    ├── 0f5618ae82563aff5d58aaba3527d1abef8c3e6f.nq.gz
    ├── 0f634b17bb5564791d6979ed902c74f903a67044.nq.gz
    ├── 0f68b2cb07104985ed7488bca1306e608a6becf4.nq.gz
    ├── 0f89e77eb8a0cfa043fd8f5fb54a71bb2cb65586.nq.gz
    ├── 0f965444038b9234192710d887bccf1de6f00f8b.nq.gz
    ├── 0fb4061802972a9241de35258ee58cc700805331.nq.gz
    ├── 0fb9cc9ef516b234308100869fda6d4baf657c4b.nq.gz
    ├── 0fcfe3e2727fdf7287f7a4012173260d89aeeba6.nq.gz
    ├── 0fd0c9df265f900b945d588a3ca8aa98205d3383.nq.gz
    ├── 1006870f71c62a7d5e5e305ca6baca9483f7007a.nq.gz
    ├── 10197807b90e789da6c22127014f978c4ed87069.nq.gz
    ├── 103ed2d14d64e9283ce7eacd3ac0b7f5f0610ff5.nq.gz
    ├── 1061696d4561b1e3f6c0b6e97c47d149ceed04e2.nq.gz
    ├── 106453fd16666f8196af71daf80e2cda71d5590e.nq.gz
    ├── 10767d9d4475264cc35aa9bbeb2b1db9a689060e.nq.gz
    ├── 10d779826884304ce8ca2a1f6508696711d44324.nq.gz
    ├── 1114d975c489c805c75584ee9b4890e027c6fce7.nq.gz
    ├── 111d555a1020fbd8d9db4ef9e0f1530014ae465d.nq.gz
    ├── 114960a83be7f26e50adf3d7e6772e6710ee0e18.nq.gz
    ├── 115e046d51ce87511809b4a1010f7f01f730534c.nq.gz
    ├── 116a938dd50d8987f8523845df53a82514d24c59.nq.gz
    ├── 117966d057d1ebde38fd901c7a8c8cf6c1c79e0d.nq.gz
    ├── 11858cdf2ffb83a758f986e9112e0c2c99dba7a7.nq.gz
    ├── 120756fb40ca0ba236f36930cc5ab9d0a6efb042.nq.gz
    ├── 1220b7414977423c693f04e4ade84453ae2fbd50.nq.gz
    ├── 1227adaa47421898f8038667ade1c0563002ac49.nq.gz
    ├── 124b413ac7c45a561f4865e81bd1a01df4d832d9.nq.gz
    ├── 12776ceed1d2628bb5bdde4a72db246c2bdb5418.nq.gz
    ├── 129138357a4e5e85ec643023a934f4c07c09d7fd.nq.gz
    ├── 12b3ddc2e017643afc34408d251c7fae20806a51.nq.gz
    ├── 12b78a52f014becdff54ccdeb1502bb59343125a.nq.gz
    ├── 1314fad66ca3825dd557e033649a8ccd00a341bc.nq.gz
    ├── 131b43c14476c159643da536ab5b6664bb69a8cc.nq.gz
    ├── 132d08237c54e728b8eb0106a0d77258dae8e7b5.nq.gz
    ├── 1354ee074d6762346c56a5b28f142f27cd11e72f.nq.gz
    ├── 13714d3da4bbdd0e2685ae2710bf6b1941e1748d.nq.gz
    ├── 1380ae1ce43112a3e77ea4fba723981263e4bc12.nq.gz
    ├── 13d1965f1e95259997af3093e04315c8f459cb1a.nq.gz
    ├── 13e257d75c4ffb49426c7ffeaa0546684ccebef0.nq.gz
    ├── 13f7d667716c7538b4dc26d6e38be32fd31503c1.nq.gz
    ├── 1419d48f5e949c11900e887ed5b48403a073e74a.nq.gz
    ├── 1479ffcf0d7e331597c663f5b199b2bfd2b475d8.nq.gz
    ├── 14b92477215333c34ec91b9f78a8b72dc5ac033f.nq.gz
    ├── 14c81c823fb4868830068a18ee43c089ed2567d2.nq.gz
    ├── 14ca841152c17163f76a64c55ccd46f0566ef5a3.nq.gz
    ├── 15005a6070f8a8036904eb9394048518c509d099.nq.gz
    ├── 152698bbbf66ed382bcc82d97510d8fbd122fdb3.nq.gz
    ├── 1533c894a2671699d834bab9e73d1b9c33ed01f5.nq.gz
    ├── 155ad59560713a1a405d835cd8020ac5e84dcfc7.nq.gz
    ├── 156e87f47eb59d9a68e823a6b8c5883b19106668.nq.gz
    ├── 157410691c2e195e269fb103ea2ba18459e85ccd.nq.gz
    ├── 157f4c9ab92d36318ac8184c5c09d1208455c92b.nq.gz
    ├── 158bb143f056420a9237f75c355129f4bdaa16de.nq.gz
    ├── 159014b8201bf144c0da960a048270d73257dbdc.nq.gz
    ├── 15ac6b05ab876e3ed5441f3588419375f94feba2.nq.gz
    ├── 15f52c7dc2f01ace386da5e220779bba9a459a07.nq.gz
    ├── 160572dd21933a9064132fd86b9c43efdce26405.nq.gz
    ├── 164f089bdf5466f63d8a4406a892323c06ff98f7.nq.gz
    ├── 16969a01f57f82bc1742cf3526cb63f688e64e96.nq.gz
    ├── 16b0eecb58a46a0bcb7d34b4fcdaeed8f0ecc4e7.nq.gz
    ├── 16b640da207f01ea5e881c5fc6cb70f5853d6cdb.nq.gz
    ├── 16b71124cf105a17973af3d21b1a2923bcba3359.nq.gz
    ├── 16bdc5e623dbe9bdc07841e19b9a419271b67912.nq.gz
    ├── 16d99b4b8d9ca0c3a02b932ef84db1a4f09744cb.nq.gz
    ├── 1702b69c2b71ab411d469560e6c7c55d26e4dcd1.nq.gz
    ├── 1716cf4d10379b7a30a67da4bff97a052f4948e8.nq.gz
    ├── 17292b8e971d79a6249844a53ef4910bebccb22d.nq.gz
    ├── 1759fe96ee6e7afc52732120be511e8c17ae730b.nq.gz
    ├── 176649e3e203d00bef06117a8d11acca0f2284cc.nq.gz
    ├── 1769349b1292a353727aaf33434c62e9c5293df5.nq.gz
    ├── 177d1e6358e375756abc1693bec96d401420ff79.nq.gz
    ├── 17a1595facc85b406e22b73cab92a2fe43227f77.nq.gz
    ├── 17bde85f327aabb848688ec62f82fe163f694236.nq.gz
    ├── 17d90fe2394d29f80a6df1a75bd9673c10bf3303.nq.gz
    ├── 17ffb351257fd3f9e6167bd1f376ed5a99c4e173.nq.gz
    ├── 1800a5fc848db99db622a54fbab181bfc99bf8b1.nq.gz
    ├── 1804538d60954de45597550d7128d56729c2f9a6.nq.gz
    ├── 1805a8ee3880766c072a303895780470b38c1048.nq.gz
    ├── 187b273f7b2f2ccfb842461323ddb4059e44db17.nq.gz
    ├── 18ae8a9f78a716871d7042dd11be310aed1e7423.nq.gz
    ├── 18b16933a92b17e475ee0ccde6771df05be514e2.nq.gz
    ├── 18cfe431eabc78c26d39190fdd9d35fb4a1da0c6.nq.gz
    ├── 18d23a967470801b0b5f3b9c04f013e7cd7b4413.nq.gz
    ├── 190eb9b9774733ab33a3fca87ccb164e695ba9f6.nq.gz
    ├── 19388f7691b27cbd2f3df62fd781d96909bcfa14.nq.gz
    ├── 198711fb216ffdb189b47a25a76f9e3a23b4a19b.nq.gz
    ├── 19a86424f8af143319d8dee1da3776e795eb2f94.nq.gz
    ├── 19ef66a9545e1526b928b2bafce65fb0b3e1cc68.nq.gz
    ├── 19fd3c7fc6cfc896a53b14672ad15b94cc9d2f3a.nq.gz
    ├── 1a245a739fbc274f23a124a43c5b6113d9778b14.nq.gz
    ├── 1a2a8eae198229407c53dcac3ef53960836e0b4a.nq.gz
    ├── 1a385ec644501e2a83c1f30f04b3032e0ad423e0.nq.gz
    ├── 1a4c47185d924b4074f624c79bfe1a78098be0e2.nq.gz
    ├── 1a5bb0596806eb1a671dfc78e476e2117b29e73f.nq.gz
    ├── 1a84165a7be8f7dbec556d95c69dde62fd675eca.nq.gz
    ├── 1a8933ba3e61d403a5fde31fc1f5da071bbbbd3d.nq.gz
    ├── 1a9c9243ea701e7158a5d265b6a36f3aaf665faf.nq.gz
    ├── 1ac6aa13119c2567b5550148ad9e6964ea2411a4.nq.gz
    ├── 1ae03ca275dee74201590b284fb0d2b8a1d4c056.nq.gz
    ├── 1af1ec7976c03d327fd2102012c33df8977eb0a2.nq.gz
    └── 1b04fee998e9d582127d578ce3cf4e88e3dd604d.nq.gz

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
*Parsed on 2026-03-19 by [repolex](https://repolex.ai)*
