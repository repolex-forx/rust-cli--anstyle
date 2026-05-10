# Repolex Knowledge Graph of rust-cli/anstyle

RDF knowledge graph data for [rust-cli/anstyle](https://github.com/rust-cli/anstyle), parsed by [repolex](https://repolex.ai).

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
lexq download rust-cli/anstyle
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 0fe6f0ff6d52e9f91d4071199bd0b24bd46f3d35
│   │   │   └── chunk-001.nq.gz
│   │   └── 2a2bebb1995eee2146ade598a1255c2f78f28547
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   ├── 0fe6f0ff6d52e9f91d4071199bd0b24bd46f3d35.nq.gz
│   │   └── 2a2bebb1995eee2146ade598a1255c2f78f28547.nq.gz
│   └── repolex
│       └── 2a2bebb1995eee2146ade598a1255c2f78f28547
│           └── chunk-001.nq.gz
└── blob
    ├── 022ed7888ad802f6d45a65fb702ac6d516f16306.nq.gz
    ├── 02815a7e8d663632960cb06d98d2d7f5a5c1e1fa.nq.gz
    ├── 02d3c87cb3b11b7b48a5a161963248e457c924a3.nq.gz
    ├── 02d537f49de289b4116eb5cff0dc49f4d6081111.nq.gz
    ├── 04247e58a4ffe4bb1837b596f8331cae03d0b18f.nq.gz
    ├── 046781960b7d49737320ae9fa75039472edc31b0.nq.gz
    ├── 048272217e68ac739d8c8d9873943527b6c0086a.nq.gz
    ├── 0544b8d0ddb4d916b99b9b655aadc194f72070ee.nq.gz
    ├── 084f20f526bee572e77e826b391d4f4b01c02110.nq.gz
    ├── 08bccbbe53550b7ae2d7ddc7b82d9b47651a99e2.nq.gz
    ├── 08f63a5e17af85c8976b4addd9d1b392054031e6.nq.gz
    ├── 0b9f99a0fdf49af680ac67b98c2df3e533d2028c.nq.gz
    ├── 0c124fd7940745d98d54e96a5f36e6a894710bff.nq.gz
    ├── 0f2b4fd874bf1493f61285f8ec52c31e05204e6e.nq.gz
    ├── 0fb013c6898ed84fbb28b3c8106b7f3eb79aaf52.nq.gz
    ├── 109acdd22dd225da4f91426f690b1961d29da45a.nq.gz
    ├── 10d0331f7ec2097c928ae79d592c3d66ec3e0aec.nq.gz
    ├── 10e29cf37a4df751d4fae5aee49524cfd68d32cf.nq.gz
    ├── 1189be27aacb14d7906515d690a7b9bd7aac8936.nq.gz
    ├── 11f51905ed49fb25f78db4554fd40047ecb247ae.nq.gz
    ├── 12340e00f644eb8da54e8b50e2abf0febe922d3e.nq.gz
    ├── 13e267467b0ec642d32b497c9511dbe925d73fb8.nq.gz
    ├── 14224d9f147773f69adde5990ea7a8f0a6ee6181.nq.gz
    ├── 15300f1de5df1bdcb93a30d79fe61f4fafd7ce06.nq.gz
    ├── 158193ffc52510101ee7855485bd53442de2a687.nq.gz
    ├── 15d8c4bed15a2b7d38ad1f8289801a9efdb0cbea.nq.gz
    ├── 16011406b4c8f3ce36a8a6de19b6072a44095a0e.nq.gz
    ├── 16671f41758be436670962efea371e6bc4bcc99e.nq.gz
    ├── 16c995d0a5736aad776ac191d636efd9ce89fd54.nq.gz
    ├── 17922f7b9e5e0878475451d0bf419dea20e5727d.nq.gz
    ├── 18bd2eb22f99a070076b52b3c051e4adda673bd0.nq.gz
    ├── 1a3897ca306db195e11408302b1b61b70208e04d.nq.gz
    ├── 1b6b4e0846772d517e184c9554222fa82eff63d5.nq.gz
    ├── 1bb1064dfccaae7a63993fb02620856afc1a4c1e.nq.gz
    ├── 1c8670ecb140c603bfbad55c49cf18c697e57d23.nq.gz
    ├── 1ced700086ae7a94d5dc2de4a9f7ff66c51670bf.nq.gz
    ├── 1d1e4731f690d1c41daa783603d0ec6419477962.nq.gz
    ├── 1d4c5dc66f4e229b407587965d09da9816e06eac.nq.gz
    ├── 1d4fd850696ddf8d3d0b9e3387d47cb7cf8c66e4.nq.gz
    ├── 1d9def64fe1da30ae59406c60be9b94ea8552f8a.nq.gz
    ├── 1f94d22c5bdcc4e57c95c8d8fe07286bddd8b2b9.nq.gz
    ├── 1ffdf69a22c7517afe64f48eecd5a83596e26d61.nq.gz
    ├── 2046d767a5db66f58162e3fd5d924464fc92425a.nq.gz
    ├── 2136ceebbd409a059bb815cd601664ad52e4b82f.nq.gz
    ├── 2147fe09ee8685c1843df922503fcfdb62fdc782.nq.gz
    ├── 216fdbf75ba1fa0bdcf47deb801e0d35bfbdf711.nq.gz
    ├── 22b1711bf8a6cd0bd21c55b0b57ac5c0b36e77bd.nq.gz
    ├── 2362b7532bd52998418e1d3695210ed992db8555.nq.gz
    ├── 24d7d438a2b6a3bd1f8b47f4ce12f9aa58429d67.nq.gz
    ├── 26fdc13d9bf5bf7583492b2049d76f2ef416471a.nq.gz
    ├── 27749d4b882324e51e90e35285e470e689575fc0.nq.gz
    ├── 2782dce4be90a75ce1c59a0d8519110e298708a6.nq.gz
    ├── 27a0902c71d7ffc1026f44bb085e16c2fbbc01e6.nq.gz
    ├── 27bf59a884cdc6948c686a9eb9b3f0fe99691c95.nq.gz
    ├── 27c2cfe225b3419996f71a052056df017e5509c7.nq.gz
    ├── 27dcd5c765788ed72d0c6202c8f21d461599740f.nq.gz
    ├── 28f50e42c2419a2e39a0d7b1fe4ccb542b7796e8.nq.gz
    ├── 2a74c1c1eddfdddf4e41fca8343324e0db773646.nq.gz
    ├── 2aa63a0d0a899f0ea19e5a032f7e7ed205f9d88f.nq.gz
    ├── 2e539eb645ddc379f551ed65e8745001e2b74a99.nq.gz
    ├── 3025c1880c72a6cbda462124ab7e3013457c3a7f.nq.gz
    ├── 3051b1d83f4a1b7d9e639ff563021a0e3ce8d665.nq.gz
    ├── 33444a3cf6289eb7ef798018cba68a118869a366.nq.gz
    ├── 34bf43be4452f5a32b11e2d949160ef85aed6cd1.nq.gz
    ├── 34f19ce053e78376f2e2286f5b0cadb53bd142a6.nq.gz
    ├── 3726f1b4cca2734974ba3a9456dba05f1d8f7ab7.nq.gz
    ├── 3907f2c47c82ecbe3af7237c0287f18bf62fac29.nq.gz
    ├── 3ce0974d6411e1fe879951e7bb925003a3b703de.nq.gz
    ├── 3cfea26c11798f706e2bfcc685c294ab9e0b421b.nq.gz
    ├── 3e4d9a1a53ea99ebb87be50b2cede8c72f944227.nq.gz
    ├── 3f7b33c54b670fa715a8f097aec061b4cfe1a6bd.nq.gz
    ├── 409275a4e436aa326982c4ca46262783130bacdb.nq.gz
    ├── 40e775a56df58504fe7b602f242a827500e3b320.nq.gz
    ├── 4211ae3842810ba7207dfc2148a5354e28276bda.nq.gz
    ├── 448da3e8c0cfffbfd0d1cb85c73dd28a9bf08954.nq.gz
    ├── 4521eec7bb1eb745714c58d6541ce51db2b1e7c8.nq.gz
    ├── 46da80565a170305e3e10e664547772ee86b80be.nq.gz
    ├── 476f4dcf75efc3d3fde2990d8b4f29f26275fef0.nq.gz
    ├── 47a0db0ddf3358865e0c5279ca7d578f0f4a7fd6.nq.gz
    ├── 48c2c1e255437e733a7df7dee8dda1f7cabf4565.nq.gz
    ├── 49103221a73f87479c68f4b666a1e5435556bd73.nq.gz
    ├── 4a076d4ef21c51c67ee1d080d705bab6955b8f33.nq.gz
    ├── 4a6a1abdd612113aea698f0f51e28cb675ea8ead.nq.gz
    ├── 4b626916642343d676914baf0cce9b695621a558.nq.gz
    ├── 4cb6467b31ec75c130853ebeb1bacba446c3c2c9.nq.gz
    ├── 4ccea6c86a69b991072e0ce2d0f91e947e7a7611.nq.gz
    ├── 4cfe9363cd1c60becb6414833e38310b9df7c68b.nq.gz
    ├── 4fcfeed9c87773c8d94ec16a5dc3d295e9447272.nq.gz
    ├── 508dc72ba53cc47d8da5bdcb68f51fb7afb00e4d.nq.gz
    ├── 52b187536887187f41aac6c25f3e5fe4b4ad035e.nq.gz
    ├── 545fc1db239145c75c05eef911dc9e7f608cfe96.nq.gz
    ├── 54dbca4f3664022289724214ff707de9c83ec47b.nq.gz
    ├── 56785efab766afc9efdef5baa29c6021f49f9e4e.nq.gz
    ├── 56b7473e3ffc164ce052102018fe74a6adc5e496.nq.gz
    ├── 56ba2acf85173fb1fc6b81634799a4039e5121c5.nq.gz
    ├── 570511ddf802386a39639e03186e1f18ad8cccdd.nq.gz
    ├── 5719ce3ac28d3624fd08a850dc3cf77812e289f9.nq.gz
    ├── 59e2a784b7a02b1da4e2d00df7ed4225b212280f.nq.gz
    ├── 5a02365c8dd4fefa0da3d361186562faf1f18233.nq.gz
    ├── 5ada312eac2162015989f434e4a60c85345a5a91.nq.gz
    ├── 5b6cb47e2f95b8ef868e1b831241873b17ea0dc3.nq.gz
    ├── 5ce70e8cdab637ca7819c5a2d1f7fb9056040dfd.nq.gz
    ├── 5dd3c4304bd7b9549c1ae1cb19691efd2ddc16e7.nq.gz
    ├── 60aae35ddad2e060fa299c994146f9125b44b192.nq.gz
    ├── 624eafeef0978f16529ee96dbe5cce5e95ad671d.nq.gz
    ├── 649427f5c20d60c803f4d0385e234ffcd9a61b14.nq.gz
    ├── 656c68ec16e241533d24c91a2750e941e82cd8be.nq.gz
    ├── 67c10aa2ea645cd0d1b781814293ce7db40da1e2.nq.gz
    ├── 680ff7bffe9fc52ccbd3ebff6463ccc485d63a4b.nq.gz
    ├── 6b11c19f3525bbb8adc899745b320ceff14f38cd.nq.gz
    ├── 6bbdc6bf6fe583d2a38a58253f23131e1aea146f.nq.gz
    ├── 6c3cc897a08a863193efab59bdc0340c3a322c26.nq.gz
    ├── 6fe914062437a9546f6bf849ef3d9ebe9ead4975.nq.gz
    ├── 703f4d97836532845daa43e94d95388ee9168e19.nq.gz
    ├── 705b3e0c92297939359efe1c6e9f942277d73550.nq.gz
    ├── 71ad99acf5c1222af68c477ea0ad6a538de07579.nq.gz
    ├── 71c2653af20c39c12b8b378f4431cd80d223b9dd.nq.gz
    ├── 72b5745fabd91f40ca364062c3dfdd4e736717bb.nq.gz
    ├── 743640f84a67bd7d4e8c2ef02b2d12127ed9e7f8.nq.gz
    ├── 7446e08ea367f652b2aec4ebeb3723d71ca18d8c.nq.gz
    ├── 77e98f2867b215b56b2a20f620e32e8c36d86952.nq.gz
    ├── 791b36435b5ac10f8d72669a98195731c800f1a4.nq.gz
    ├── 7995e5a3b934e86f19d78fa468c308a4216ae008.nq.gz
    ├── 7b55a3d9f5ae236cc6134ecba00925a7526498ee.nq.gz
    ├── 7be030d4e1608c685170c843a877904c7b377291.nq.gz
    ├── 7cc146fcdfa05466e6a25440eedf7878322aed6a.nq.gz
    ├── 7cc2bd5792f1fdb2e4016909bfac266be6fb8d40.nq.gz
    ├── 7d2e044b26b9bfbc958189bfd8199f5a1f6111dc.nq.gz
    ├── 7d5280bbc61be482a13421086425bef4c6211f7e.nq.gz
    ├── 7d7bad6739c1898db1293aa945ca5524929b2de5.nq.gz
    ├── 7da54c6452155169fcef2e18c368d1d1e6832887.nq.gz
    ├── 7da5a3091af61e7ed8089d7452cfd780661e1c00.nq.gz
    ├── 7e1d698211ae81cff5758dbaa47d76e1f4bcc2a3.nq.gz
    ├── 7e751d650b1c2e34f8d16f4e48bbf8aadaea928b.nq.gz
    ├── 7e934a3c3dc12ef141909782d0abc6d85ac670a7.nq.gz
    ├── 828f9f05df6c142874d5322f6d8e7d9f0af11484.nq.gz
    ├── 82fa1f4c40a0230e76e94236e1ee94af90ea27a4.nq.gz
    ├── 833a9947bb49d86a502a9c2c4b44baf777281c1b.nq.gz
    ├── 84676ac1414e5ced521095c5bd3a50796202a051.nq.gz
    ├── 858707224049b70eeda50e2dccee24d844fe7bfc.nq.gz
    ├── 860e3a8e3dffe69a2bcb053a9fe7d988784e3ee2.nq.gz
    ├── 86aa70fbff93f0ae497ff0e4ff487441b78e5c37.nq.gz
    ├── 872d504c03718fbfbf23b7d725213991369dd3e3.nq.gz
    ├── 87528822e0eb63b7ef151401f2c875b97bd3f2a9.nq.gz
    ├── 88e95bcdf3a17e519855df5e4f15939f2fcf630c.nq.gz
    ├── 88ebf3bb64509feb6ec7d3f670a76845e5d2f09f.nq.gz
    ├── 89469a7fa0b8549257f2ee6e276509eaf72442e9.nq.gz
    ├── 8ba9ffa7b8a8d27ef8805bd37bf29f060948aded.nq.gz
    ├── 8c1e98923512710636dd55d624037e97e52109b1.nq.gz
    ├── 8e58d9ec097c0d0f548b385b0850e743c0cf00fa.nq.gz
    ├── 8f532a4539cbda948e629bdf36b8c545cc3e88b9.nq.gz
    ├── 8f6817e060e886c6b0d3bb3e3ba10459b9043368.nq.gz
    ├── 8f71f43fee3f78649d238238cbde51e6d7055c82.nq.gz
    ├── 905fb94e5985576c27aa84e8f49dd224cc01d42f.nq.gz
    ├── 90c33ae6df4552580278541e9ebd48993792f532.nq.gz
    ├── 9138a8e3fc824971be7888ef3eaa8074095cd94d.nq.gz
    ├── 9233df7ce4b045dc9ae7665bcb8af83664562005.nq.gz
    ├── 92e5aafe88a5f0cafa47bab0eb5e5cdcfdc2e1ee.nq.gz
    ├── 9522e60404d7c7e15d48881805fd065268166048.nq.gz
    ├── 95a42ffbc7027f6835dc6c9d960c1b3efb228dcd.nq.gz
    ├── 9692c7c21e4f692a0501591df03fa337d7c13fdf.nq.gz
    ├── 99ea5e1a1016494916f66ba02757def96649ebde.nq.gz
    ├── 9a6221259fa3415daadfc2c4ef97434caaa74a59.nq.gz
    ├── 9a8c75392d09cac3a2452b567cd0b35f9ebe7ecd.nq.gz
    ├── 9c374165b384044ae25fbb448f9061919b2f2328.nq.gz
    ├── 9f0d28bd708ddc2beb6affb134bc30b02c11f786.nq.gz
    ├── a1d869187a8bbe5e5be655fb60861a91d465d75c.nq.gz
    ├── a1efb302dec03b2ba83f081d682d723611ebbfe6.nq.gz
    ├── a1fa97d3b6e92b5b6eab1daf30f464ecaa2fb2e7.nq.gz
    ├── a2d01088b6ce55e837a6d193943580f978fb2d2e.nq.gz
    ├── a3e5e1b23c1032f466c89c1a717617a2310670b4.nq.gz
    ├── a505dc1c59522c23574b8fde893088a32edc18dc.nq.gz
    ├── a5b97ef481d94c65a5e3c52b61ae8a1daea450fb.nq.gz
    ├── a619ebbc0e4d521d110888e506a64c2fd19c8f97.nq.gz
    ├── a66dd530f7e3ae524b315d27165651999b9571ea.nq.gz
    ├── a8802224efeb20abafd61ece6c5905ddfe2ab82e.nq.gz
    ├── a8aacae7156f0c28b57925396c83cdabf03573b9.nq.gz
    ├── a94be159105bc355661741d6114718caa37c022d.nq.gz
    ├── aa65ab065eaa0ce8ced9a32b0ddba3efad9d74da.nq.gz
    ├── ac6f5d04895476c03f37750cbe2284665df88e6d.nq.gz
    ├── ae0b825da34212d3c884d8704dc343cb939119ba.nq.gz
    ├── afba0f10d035ebc9289e0daba7940fc57d3aab5c.nq.gz
    ├── b0a71b8f39fb77bdcc055e0c1a2a3817a22a5cb0.nq.gz
    ├── b22255de09f0bdfc08a897110d44741d24e81bfa.nq.gz
    ├── b2374b7ff85b40f95c396bfed4ed06ab54ddefe2.nq.gz
    ├── b42ad5cc514447434b9fa8eb43d62ab8bdffc435.nq.gz
    ├── b581e16d6bded74e1094f8e2f74199467aa1592d.nq.gz
    ├── b9b5a8d9afac8ec9a8a8bca00a0ff0d8f86634ef.nq.gz
    ├── bb3fbdb8f765678fdbd741d04a9e8dd2177b0540.nq.gz
    ├── bbc05b9f6b38c6bef948bf44753be3ab1f05325d.nq.gz
    ├── bfe56728f7d30fef41703d9cf72a2523953dd480.nq.gz
    ├── c2114919832ca8dfbd9323cfc44220774a416942.nq.gz
    ├── c24706795dee6e968bcc481b18a5578974ee8926.nq.gz
    ├── c2fa3fb0177275094867f76865d9ffbc3039f45b.nq.gz
    └── c63405146fdb774a37d20eac77bc5a9bf5bd29b5.nq.gz

9 directories, 200 files
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

[rust-cli/anstyle](https://github.com/rust-cli/anstyle)

---
*Parsed on 2026-05-10 by [repolex](https://repolex.ai)*
