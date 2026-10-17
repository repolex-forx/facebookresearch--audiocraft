# Repolex Knowledge Graph of facebookresearch/audiocraft

RDF knowledge graph data for [facebookresearch/audiocraft](https://github.com/facebookresearch/audiocraft), parsed by [repolex](https://repolex.ai).

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
rlex download facebookresearch/audiocraft
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 896ec7c47f5e5d1e5aa1e4b260c4405328bf009d
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 896ec7c47f5e5d1e5aa1e4b260c4405328bf009d
│           └── chunk-001.nq.gz
└── blob
    ├── 0041e49c303ea564d97ba38779b50adfff13d462.nq.gz
    ├── 018ad1cd61af84b616ad3088f055e8eaa36729eb.nq.gz
    ├── 019b9d19e5bef976bedddf428fd25da42a8a9726.nq.gz
    ├── 01ab323e4322d08546635861959b868c3d7b416b.nq.gz
    ├── 01f2e44b8d1bcac7b998f8f8ed34a10a414a54c9.nq.gz
    ├── 03274a1ae52b6f20473973b77619f34b2bddd6a1.nq.gz
    ├── 036628abfeaa89279790547bbb5b3ee9dd69cea3.nq.gz
    ├── 036de25d875f1e5009f96216d06165d9fa92eb50.nq.gz
    ├── 0432e44a36838c5731711f9d54f81822b21f20bd.nq.gz
    ├── 08a2157a2b61095495c78e7f5693a438ad1fd826.nq.gz
    ├── 0952fcc3f57e34b3747962e9ebd6fc57aeea63fa.nq.gz
    ├── 0a7bf7f1d4ed6ac6e7ec4d95c45149d1da2253e3.nq.gz
    ├── 0ae90c7f568e11dccc5424849cd3edca17e19286.nq.gz
    ├── 0bf4ca57b63f5f9308bd1178ddbde5d8f06748e5.nq.gz
    ├── 0e30bc3a6dde00003e13c00f15e977e39425063c.nq.gz
    ├── 108b5f002fc31efe11d881de2cd05329ebe8cc37.nq.gz
    ├── 117b2b1e496ca31b3d614672b472c9213cedb4ad.nq.gz
    ├── 11f2eb3e5c44b542a02f13db64bfb22fa0d3d212.nq.gz
    ├── 120887b00c02ffbb4d86670f7de0c6c098aa0f45.nq.gz
    ├── 1248964c8191e19f27661f0974bef9cc967eb015.nq.gz
    ├── 12d99901aa52907202690c068e1e0537735e68a9.nq.gz
    ├── 12f6d402a3c4a113d4c37be062790fa435b72104.nq.gz
    ├── 14f5d6a4fcbf4426b7987d4427ca2d98d17d6c5b.nq.gz
    ├── 1568f97fe7b84b90c7ef760ef5606fe0a475545a.nq.gz
    ├── 16d0da76cdae45a067c0d3360503509768fa0b34.nq.gz
    ├── 18e0009f9750331874e609bcaf4d9203276e206e.nq.gz
    ├── 190cc1d0a1e316347e8ebbdfc8de7e2942c1b3d7.nq.gz
    ├── 1a8dd3cc46423f9adbf0eb6cef4e4cac836e918d.nq.gz
    ├── 1ad3e0aeeb9583887d6e8ecd6d32a3dc69e102ed.nq.gz
    ├── 1b9120b79cdda15f87e102eb4a94dd22fbbf20cc.nq.gz
    ├── 1c5da22061b6bf2efa1d9a41ddd444e211bb8787.nq.gz
    ├── 1d4169f468d462c794ee6ed25017c3d78ae45d06.nq.gz
    ├── 1e0c7e429ab96d67be667e23bf7a0ffa389c036b.nq.gz
    ├── 1e4f0bbf28f1ad893a301f1bfac1da8e97370337.nq.gz
    ├── 1e739995ed6488700527529862a7a24f1afdcc7a.nq.gz
    ├── 1ed3d369bc75c2a0c765e4cc2a3637c446008809.nq.gz
    ├── 2047b6c8d5b1d58a67090b947e7e2666c3104eca.nq.gz
    ├── 205e52e28e1d7980022f6e2573ded7a9927aad15.nq.gz
    ├── 24e30d4cd87683430488bfa442e098b34229a5ee.nq.gz
    ├── 2702a3cb5fe402bf96911dbc992d2749cb18a4c0.nq.gz
    ├── 272d6bdb86eab9408261b07fb99bbaeda5ba623e.nq.gz
    ├── 27ed214929d302f594f29f1851ef4156b1fe7bbb.nq.gz
    ├── 28b214017d9ac23934b67e8254a96131cefa6501.nq.gz
    ├── 28fbc4f1a0ebaf41b56947b767958ae696e75eec.nq.gz
    ├── 2904e73de08f1c9b844818558d739715776284d6.nq.gz
    ├── 2aaabc9b61a3a7d8665f7ad7903f7983369cd65f.nq.gz
    ├── 2b32ac5d52e6ba3ba8f2b413e54e1b5ac5839016.nq.gz
    ├── 2d0fe6cfa3fb33bcdb4f9fd16bd5ab4034c68b7b.nq.gz
    ├── 2d256ad14ef69d25d62c19b73599937c8546e79b.nq.gz
    ├── 2d83d7c4c2dc84c64b724eadbe06157507d4f20d.nq.gz
    ├── 2e2d9c5b47c7b96515e03ec2d21aa77d71b14a6d.nq.gz
    ├── 2f9c1db3f69a45f02451b71da95f44356811acbb.nq.gz
    ├── 3069a3212c96beb7d50e302efbdb2a7fb14e09ad.nq.gz
    ├── 32fcc10033f3c3ff317216fe2876c65c6834e59b.nq.gz
    ├── 334836b72559a120feb8a15eef3fe96ce88a4edb.nq.gz
    ├── 3380d031739d473fb859c76b9c25350f47fa77e8.nq.gz
    ├── 33c6b5645489e8dee041749749e9f822af25efbb.nq.gz
    ├── 3474bdc4f1c88b21904d2a21ba077c93a8a70c8b.nq.gz
    ├── 35ab5980574391ee17528052a1a66d8dd5ef7ba3.nq.gz
    ├── 367c3f3c9f95ae59a95edbb60b470e03cc842fbb.nq.gz
    ├── 3793d4d08d912db575c022a6803a8909c2b25273.nq.gz
    ├── 3850af066cedd5ea38bd9aead9634d6aaf938218.nq.gz
    ├── 386df5826937178e29eec670280f8bea57f1a19e.nq.gz
    ├── 3973118d25291f2a9e20f17c6789c158e0bef6e7.nq.gz
    ├── 39b544b08c7cddc48d9c5bba6cf9048e3b3979f1.nq.gz
    ├── 39ceaf7dab15ec3f0f669cfe57ca9e932a9ab40d.nq.gz
    ├── 3c7de25f19fa39b05aa5199fab2069e0f7476d87.nq.gz
    ├── 3ca555bcdc69433f172915400bb71c3b63e68681.nq.gz
    ├── 3da88d2305e4c380435de1a3eecfe311ecfc82f9.nq.gz
    ├── 3e5998e9153afb6e68ea410d565e00ea835db248.nq.gz
    ├── 3ec689c9c5b55e6a0e04d0c8a795e18f304955c2.nq.gz
    ├── 3ee91c89c1d4b603f3e4d3fcc029618dc110e730.nq.gz
    ├── 3fcb7e87f4f700554164b0a58e9927b2f96a2c5a.nq.gz
    ├── 402669dffce94dc600fd2ce274b55b6aaffb3905.nq.gz
    ├── 40392acbd02a75a755ab1e038cd7e8457663b94d.nq.gz
    ├── 407066df1e154208af2823a6e46d16df381c5d42.nq.gz
    ├── 40c0d5ed69eff92a766dc6d176e532f0df6c2b5e.nq.gz
    ├── 40c26081b803c2017fae1b6d7d086f0b0e074cef.nq.gz
    ├── 410875acfc73c7123d9c6b1b8f1cb8a2300da2c0.nq.gz
    ├── 41c812ba9ff8afe7ee10302ad5b9f05b745877d9.nq.gz
    ├── 425e204fbecb2f6e569bccfa21ab180d656645a9.nq.gz
    ├── 42cc33ac6e829630e52a2fa74d94156e4ac90a56.nq.gz
    ├── 4337eaff066a8ca124dca3e3e63ee36e417c055c.nq.gz
    ├── 4417361c2fd9cab6697d1283eef1eeb7605cce28.nq.gz
    ├── 44f4b0a2c3c6c726857db8386491823dd85dde51.nq.gz
    ├── 451b5862fdff61ba954c67fbb2a9733374307152.nq.gz
    ├── 453269ad491fa7d05602684f71738df18d0039c1.nq.gz
    ├── 47ab4b1594faf1e9f1ce962fb980d80295b1f079.nq.gz
    ├── 4881e9d86cddf36b306a75fb498253e1e12ec5be.nq.gz
    ├── 4bfcf45c4e63ce27640e58cd4cde337e6d299844.nq.gz
    ├── 4d44b39ecbe6ce2ec4370a149d0b285ebf663f44.nq.gz
    ├── 4e28796939f9cde2b23a2c4bf43fd7ba5fa26b2d.nq.gz
    ├── 4e364614537e426f21c18a2c2a9d94b3babce051.nq.gz
    ├── 4f3401a1b44ce300e22f3f64ef9c54d5c013c153.nq.gz
    ├── 5051658e248a9efef7024732c38c59a6d0c1deda.nq.gz
    ├── 506ce35db708967bb9de6edf9c46df2564f0b0fd.nq.gz
    ├── 50ac8097e49979fc8965ac6a332412d6c209c653.nq.gz
    ├── 5151eac06e37d9cfaffc90cd331b1e3a72f35f0e.nq.gz
    ├── 53fe1f858a8d02401a033882aca407aad27ee737.nq.gz
    ├── 54dac175278d4ff509b0e44905d6b6195441f2c6.nq.gz
    ├── 555d4b7c3cecf0ec06c8cb25440b2f426c098ad2.nq.gz
    ├── 5612ff5688d85fede0e605b244919e8081cb1da9.nq.gz
    ├── 5726e414eecf8705f5deaba2a382a1317f4f0497.nq.gz
    ├── 5851222c39e173f91dc9dafe962470c52cf2fba6.nq.gz
    ├── 588938fd31a9adce56bed0c490c8a0ba9605b541.nq.gz
    ├── 5a1ce69a51a702ab309cd87e987720bad6ddb5ab.nq.gz
    ├── 5ad4b7d3324ee5b0e6064b6f71cf8caf0fdc3be7.nq.gz
    ├── 5b0aa94295e403f17608e108962f1d716e0b40ce.nq.gz
    ├── 5b688528f1f3e4efc0c2a1e9d490f33c4158b3f0.nq.gz
    ├── 5c401202f6b5ce3c24706f7d76fe44783a8878f5.nq.gz
    ├── 5cf6bb49edd74906aacacabbe3a4a2b6f2c54aa0.nq.gz
    ├── 5dcd23d8276d8f474043976672ea249d8b2a9dd1.nq.gz
    ├── 5f0e7f36da7da59f4f16a35539563e6e953e8a05.nq.gz
    ├── 5f2d77590afd8a81185358c705a6e42853e257c3.nq.gz
    ├── 60479fa6f1f30569d730dcfff700dcc0b1956cf4.nq.gz
    ├── 6055dc910cad46d80609aae57bb46b81f2663d70.nq.gz
    ├── 61418616ef18f0ecca56a007c43af4a731d98b9b.nq.gz
    ├── 627fddddbb9259ae41fd99cb85693787ec6b1891.nq.gz
    ├── 63c3c333daa3418f52f952f9d018ccedee017899.nq.gz
    ├── 64ad3f8c77afe1ab5908e407ad14d4879e1b1ad1.nq.gz
    ├── 64c002d87895bba96a0ca3b4b2712f07f0b6828e.nq.gz
    ├── 654deaa01ba9cace3f7144cc91921791c081b32a.nq.gz
    ├── 67218f87ffd5d3a9f701321f5944d635347cf897.nq.gz
    ├── 68e81d4467008d597f1e17105b37adff78c8218c.nq.gz
    ├── 6aaf0da50afbc1d02e89c708f6d80ff490823f05.nq.gz
    ├── 6b0b7866eafac173fe7b056ad5920be1df57a947.nq.gz
    ├── 6b5e10e23bc7b67d9ac6818756c2a7fc0f3bcb75.nq.gz
    ├── 6ba017a761a29c44d3385e0b483877cb4a8d1ec1.nq.gz
    ├── 6e17abb51caa30676e4860c9862b75867236ae7e.nq.gz
    ├── 70643517cd1a8b4e712eca90e23411ae89937795.nq.gz
    ├── 70fe4dbefb5bae64530dd8944b700901f98f4ccb.nq.gz
    ├── 71282fef5747b8bf1af9f43ed0366bfddd7f6772.nq.gz
    ├── 71be35a12d3e97993996806d6a94175568b2761f.nq.gz
    ├── 744ca7590c1983a8020f271bcc295c3a5cbc0e2c.nq.gz
    ├── 74ca6e3f2e7c4ff904d96dade315b0b46856778d.nq.gz
    ├── 74ffcfef96fec35c99b2a1a053a61f44f7a8bbe9.nq.gz
    ├── 75e25a0212f98e4a18d97c86c6cda225636a3215.nq.gz
    ├── 75fbc3783942602beaddaa38d0aca977aeee2dda.nq.gz
    ├── 76de9ab866240693c846834bac198833f6559f91.nq.gz
    ├── 774e88f43d54980daef0c68d11717ddb7a214db1.nq.gz
    ├── 7786880ab9c0464a0423d906c18d62bdf7194463.nq.gz
    ├── 79326db383a0c04c183512c11221d67cc5eef9e6.nq.gz
    ├── 7a762eec21bb7ea780db89a20a9e4e792d83af93.nq.gz
    ├── 7c53fc73703ec8507c384b5c9487026d362b8332.nq.gz
    ├── 7dd0b784a2f961ac1deda293ff635728dcca2318.nq.gz
    ├── 80be23e999c6366cc89ebcf55af6b958c0e45158.nq.gz
    ├── 81a9100961c7a89a39df2643b24268fb90bfeaa4.nq.gz
    ├── 83c40d6ccddc6ad2d4d54e8c1db5726e4fbc95d1.nq.gz
    ├── 83f431e8feeb7e80d571f39c9f6c1b96857b5f85.nq.gz
    ├── 8496cb618a023d3735e8381cb4c67a8ac6b9dcf0.nq.gz
    ├── 84fd86edd995ce083cbedda3b6f3f66f152c23ef.nq.gz
    ├── 864058706fbfae13d7f7dc850cc411a2f27d1510.nq.gz
    ├── 88cd27dce247106b889e9b66eda3942919d6b4e4.nq.gz
    ├── 88d89cb5ac1b183fb3a9092834cea83aa16c70a8.nq.gz
    ├── 8a0a2688450ce120088b79c3314a2f267394dc11.nq.gz
    ├── 8a0ac8adebab8cdee8f82351965195dc02800d18.nq.gz
    ├── 8abd1bbeea5909e664cf816c020bd7c37effdb66.nq.gz
    ├── 8b1bbfc546dc8d65410205a01b989ca6995e4059.nq.gz
    ├── 8b48d00bd7ca772be7232ef33ed31eda570f79dd.nq.gz
    ├── 8b6d36e407ea83449fe007c575177978d1fff207.nq.gz
    ├── 8b88cbe8016b4bd28c2de749177c9af29f7755fc.nq.gz
    ├── 8cc0dc11b39c2a849c386e8be1cde2d0d4b58a61.nq.gz
    ├── 8d53b5669273230e82419977e7ff6425869f8ef1.nq.gz
    ├── 8debd1fa72d77ca03df680facb60bdf79638cade.nq.gz
    ├── 8f24e9b2b2631eb7f6a8194e4088feb0d84f9bf8.nq.gz
    ├── 8fa509266df4ee76519b82bfbea247cb0b18bcda.nq.gz
    ├── 91d37e758ef183678cff3f7a880b6bab2e36b03c.nq.gz
    ├── 920192e8842c5635bf6f7f76618fa4a6f4b0114a.nq.gz
    ├── 933c72916653c904d36553b68615d6ed1a60975f.nq.gz
    ├── 93dea2520836f458ab1b8514dca952b51d113ec2.nq.gz
    ├── 94bdcf0d5e55a0e085b94b54499f3a3228f8aeb4.nq.gz
    ├── 96340dffe809e06f13c896b7d823f89b168221c2.nq.gz
    ├── 96397450b9b03678b35cbf58734ef14b7b33b466.nq.gz
    ├── 9734d1bf975065ab4e185f8831f9960335810655.nq.gz
    ├── 9962b2eab5ae7474f50502761a72cd8abbb9f329.nq.gz
    ├── 99c2bd64327f18de3989d7772b33fbaab547ab6e.nq.gz
    ├── 9a6b1e740465b262bfd9eeb5e81c8e303baf9e64.nq.gz
    ├── 9d4eea0f7a521a47b9f673fecab075c5223d2b07.nq.gz
    ├── 9d638f1572cf44f63199e7577c3b767177fc4800.nq.gz
    ├── 9d7442526186b3712f5d4754f928a40ecd964174.nq.gz
    ├── 9da31daa5f009f46e753601a51a06391594b8f9b.nq.gz
    ├── a00890009a88752714357210a73709a83b395849.nq.gz
    ├── a0df7c63a0d2dd9a79f33f5d869ca31c9da87e8d.nq.gz
    ├── a0ff481190fb52fe865aa66aaaa10176f7cf995c.nq.gz
    ├── a1b8ee03507dccf0327b1f2f57298b56f38827fe.nq.gz
    ├── a1dd24626e611418c4de5c1d5ac6fca50dc70876.nq.gz
    ├── a3e9507643d4439f509a8fc8b87dc73417ef9822.nq.gz
    ├── a5713c569f604db9954eea02dc4c415b5ccad9f9.nq.gz
    ├── a711c9ece23e72ed3a07032c7834ef7c56ab4f11.nq.gz
    ├── a77fefb98e62a5bbc6385910261ffdde2ffa5a25.nq.gz
    ├── a8a5cb1fac9bc7410528c20986345195867a31c3.nq.gz
    ├── a9d517e9f5bf0f4e18252c45c8db3a35a7255f69.nq.gz
    ├── adc7819305758bb50a9984928bfa7f13eabef5f5.nq.gz
    ├── ae19f3a8c51abf469697d6affa91449d668716ba.nq.gz
    ├── ae41bfc5221e0cb81b2c53f24d76e964a11af995.nq.gz
    ├── af370ceb9f005393bdda0a02e363d41abd34819e.nq.gz
    ├── af5288712b8d2cde2d9814c747275e69f6e970c8.nq.gz
    └── af77e1aac4df7a643b48726fd2cd25c67aec06d6.nq.gz

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

[facebookresearch/audiocraft](https://github.com/facebookresearch/audiocraft)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
