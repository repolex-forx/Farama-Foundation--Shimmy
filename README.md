# Repolex Knowledge Graph of Farama-Foundation/Shimmy

RDF knowledge graph data for [Farama-Foundation/Shimmy](https://github.com/Farama-Foundation/Shimmy), parsed by [repolex](https://repolex.ai).

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
rlex download Farama-Foundation/Shimmy
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── b3c5636ca7e5b0c2f3b20741d52e5d6845ad6c3e
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── b3c5636ca7e5b0c2f3b20741d52e5d6845ad6c3e
│           └── chunk-001.nq.gz
├── blob
│   ├── 0230bbbfdcdfd92a7dece683866f97fddf5fc4c9.nq.gz
│   ├── 069422654adf642b8e81a1e6466eeca3892289e2.nq.gz
│   ├── 079e470a6481bd531e454a936656f972544f3674.nq.gz
│   ├── 0ae8271fe756f106fd642d3af20c3a43ba10ae03.nq.gz
│   ├── 121e05aaf8b0f769ba7088b496a781e8048df867.nq.gz
│   ├── 173b700c0c3c5ed5f9e94a64621b04fa78d548f2.nq.gz
│   ├── 27490a4b7fce328ed558b9cf0e044278bf1c6ea4.nq.gz
│   ├── 317c25dd97cedcf46fc67b98bc46799a94bb84f8.nq.gz
│   ├── 334877fce51fdb39beff8539666e30518bf89ef3.nq.gz
│   ├── 33bdc497ce22235540e449a60b2bcde2cfe11cc2.nq.gz
│   ├── 3856971cd681d97dc9047e21c105bd8c20270de0.nq.gz
│   ├── 3902cabea1e8f6d67a7fa585e8e2be42f3098f79.nq.gz
│   ├── 3959984b58798b3375a46c13c735bfa3581d8e43.nq.gz
│   ├── 3a5e8ffb8d575c8d82ef273ec6cfc5ed3e87cbdf.nq.gz
│   ├── 3ebf3ca28276156368f7bceafb8190e5ef42db8c.nq.gz
│   ├── 4ae8c32d8ca99d17522861484439ab102fe08380.nq.gz
│   ├── 4e059c90d85b9006928f1d4909c54b8da9eb285d.nq.gz
│   ├── 4ead7770ea6ff3ce420f1bcf9c80cb92257737b5.nq.gz
│   ├── 4f6354d2e577a1d7c423f04e87bf7c85c826e2c3.nq.gz
│   ├── 5319257b340309123a322ef0b15ead8c27977004.nq.gz
│   ├── 5839240755ec526a8389738a0fba862e27c6f7eb.nq.gz
│   ├── 5a00cfb976575504bb2b1d389e06dedc1807b146.nq.gz
│   ├── 5be39d46e6a3ea4dfd0549c036a30dab8041b45a.nq.gz
│   ├── 6025932171b4d5e243bc1c2144725954bff625e5.nq.gz
│   ├── 66fbb0706a2706049be0757bd312387677961bf4.nq.gz
│   ├── 67e2b8f2ebe40f7038d4e733aaee0f8f0aa7a1d4.nq.gz
│   ├── 6b86ae81c278f970bcc98d1309e93c7bbaba4ff4.nq.gz
│   ├── 6e31f6fb18dbe11cc723560d6ad8021d2c2bea55.nq.gz
│   ├── 6fd109f58ba9e946d1bed69b7bef8ef4947502b5.nq.gz
│   ├── 716c67ad8d98f57367fc71971471ebd27dddca15.nq.gz
│   ├── 77cba4efdc965da7600a11d72fa29c64368439a9.nq.gz
│   ├── 7ba7ff43ea89b8e4b89565646cb72583edc8dd71.nq.gz
│   ├── 7e76b0e15f03de389ea2b965ced4df2022407295.nq.gz
│   ├── 8084272b4b7828a0748ae9209f92611e196801de.nq.gz
│   ├── 8833256547c9ad6c207f0453bf8a64635feccf2a.nq.gz
│   ├── 8cc5a5697b660af1f8fabae8392071d594fc44ac.nq.gz
│   ├── 912ba7f9bb6dd662e42904ea16989de48c886016.nq.gz
│   ├── 9915d07595b761f770003410256300bec95cc434.nq.gz
│   ├── 9a6c16d079badfff08b3688677ea5e6b11b65ff5.nq.gz
│   ├── 9ba6d1c26fb782d7fd306c63ec87f6d46ecd10ec.nq.gz
│   ├── a058e425a7d6e698d06315dc49b14e52e2eff17e.nq.gz
│   ├── a0d53c266870972f87d8fa6f5ad5f961e85d3b5e.nq.gz
│   ├── a526bec05ec4b40684bada45cdbbdaa224f4a885.nq.gz
│   ├── a6d1b062d260945253b946916a6d11aecfc5b58c.nq.gz
│   ├── a81c8ee121952cf06bfaf9ff9988edd8cded763c.nq.gz
│   ├── a8a26367440a6db5552d7fcbd7b735f5bfe773b1.nq.gz
│   ├── ab24c665d127e5cf1b70fbfd85b7ac11f4cf594f.nq.gz
│   ├── abbf5f025dc345df5ceb7611afbef301a4ec08f7.nq.gz
│   ├── ace5af826a92b3b38585702290295b612adb126b.nq.gz
│   ├── adcf7a1f282cd7b68c554e53ca11e7545262220d.nq.gz
│   ├── ae21a19a3fba8402701e4e04627c821b2554cef0.nq.gz
│   ├── b3b003f1674f690b0f48f6abfffe1f438b3123aa.nq.gz
│   ├── b6e963626373ed046c5aaff4ced54367fd661037.nq.gz
│   ├── beffa54b2a70890231010a84a6ac0c3d3f417a32.nq.gz
│   ├── c0778c3771a0c5b9b08f8f33509d9ffa51cb7abf.nq.gz
│   ├── c30a71c5dd26b0ce8ed09b41f4ef5f27ba3af26a.nq.gz
│   ├── cd9d2a68bc25ef9a138b1dfe0ab992db34f7c05b.nq.gz
│   ├── cf39b68a7242de19b9c9a8f59530578fc90ea3c7.nq.gz
│   ├── d129a8a9888c8fa342261b79d6141f264acc91c2.nq.gz
│   ├── d4bb2cbb9eddb1bb1b4f366623044af8e4830919.nq.gz
│   ├── d6f86e65debe3548e2d6e6c56d883cb19ebc7901.nq.gz
│   ├── de97681b9bbd06af7d01fe5fa26854d1cc63fb73.nq.gz
│   ├── e2ab413a74638cb088c373e2eb747b42bc9e1d62.nq.gz
│   ├── e37dbf7eba197887d55658605552d09ebc774308.nq.gz
│   ├── e5bfcd5de7c92f84300a74704a1f9131b1bc0219.nq.gz
│   ├── e63f8eb0872d302d95706887b733db0c600f31f4.nq.gz
│   ├── e6c919b42f0196ca4e5f284a7e40cba0c0f7cdf9.nq.gz
│   ├── e758566b14446a3dbcf591bead758618920f1c05.nq.gz
│   ├── ea7c7d78841fa0aa66a69cd53debfbb1f1ad7ef4.nq.gz
│   ├── ec3828642a85ff1834fb73c348c4bc4ce476c499.nq.gz
│   ├── f3cee37eec58ad45727b27dc6928bee961019983.nq.gz
│   ├── f75f903434bdadd673fe198bac79b470ac78116c.nq.gz
│   └── ff59d69dce7f1e663c641af26c86526f8e4f3f93.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── b3c5636ca7e5b0c2f3b20741d52e5d6845ad6c3e.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 81 files
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

[Farama-Foundation/Shimmy](https://github.com/Farama-Foundation/Shimmy)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
