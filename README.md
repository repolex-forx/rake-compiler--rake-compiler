# Repolex Knowledge Graph of rake-compiler/rake-compiler

RDF knowledge graph data for [rake-compiler/rake-compiler](https://github.com/rake-compiler/rake-compiler), parsed by [repolex](https://repolex.ai).

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
rlex download rake-compiler/rake-compiler
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 56a1a12c38c1a5519bdcaf363ab34407ea7580cf
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 56a1a12c38c1a5519bdcaf363ab34407ea7580cf
│           └── chunk-001.nq.gz
├── blob
│   ├── 00b869ebd1bdb8b94b957c7dfe23746b5b4aa48c.nq.gz
│   ├── 02058b87f474b47c7ad9b0e93625fd4a5eebddc7.nq.gz
│   ├── 03c1d49becf6de89745ec5702f7cd5a0cba63f96.nq.gz
│   ├── 0670ea239e266ad62f87fb614fa025378b19c735.nq.gz
│   ├── 0aed2f51d968eecfd404452db36ecc636c321cc3.nq.gz
│   ├── 0c226da107e839fc5f8baf63d2185933fb9a0baa.nq.gz
│   ├── 0fdd2434170d18c000da90ddc184d17e263fb284.nq.gz
│   ├── 1072b8846790a8e499d0ba94f3a7224f5ec98255.nq.gz
│   ├── 121c90d91b871acba84d99fa5797029df9fa53c9.nq.gz
│   ├── 14990b7fd9d8b66364993ccead32d6c8bc240757.nq.gz
│   ├── 16868b5f5e59f79f67eae3fc5d7f92e5051412b6.nq.gz
│   ├── 29c987a2c56002d659eb82cfead51801d3259928.nq.gz
│   ├── 2a6a2b100b9add1080da6ae2cceaba20d92bf8f0.nq.gz
│   ├── 2bf0a8d95743eae10c065cc4f2c29af0462da469.nq.gz
│   ├── 2e4c6b6b045d7025669602d46e0f222b820795cd.nq.gz
│   ├── 30bc9abb65f93a0c4bb91a61d7a60cc9ea077ed2.nq.gz
│   ├── 312e524f5ab61f2c445fe66f200ab1d94180883f.nq.gz
│   ├── 363a57c701dc9406800a95c7fc4046af456fa8a7.nq.gz
│   ├── 372b5acf8cf1147cb2fa8889780183e10e73d9d4.nq.gz
│   ├── 4b737eba4dc7dc0537799b77dd731d0d360e30fd.nq.gz
│   ├── 4f3e96480347766443cee01f6da46cb37a79d8eb.nq.gz
│   ├── 584fd319fd36b19efc017102627f59f63128055b.nq.gz
│   ├── 5ace4600a1f26e6892982f3e2f069ebfab108d87.nq.gz
│   ├── 6267286365667300ae5ce48aeb37e8e0e23e6961.nq.gz
│   ├── 6be2b4fdaaff8ad9418c6d2d204226a4d9990e06.nq.gz
│   ├── 6e9bd1fb74f57f2ecba2e7811612671486e3db84.nq.gz
│   ├── 707d4019957bd7880356df909385815529e51c35.nq.gz
│   ├── 75f46944c423d28e9d3843a8ebb9d6481c8a0e23.nq.gz
│   ├── 7a21fdd30ceb30a5c2198d4acc38d2e1b246f827.nq.gz
│   ├── 7b294adabf3e29be565073478aaa1292ef9ad310.nq.gz
│   ├── 7b5d6c38a9d9ec513f35ef56e120809d9efce078.nq.gz
│   ├── 7edd0d01c9ccf7d910a20d80e3692096f8b8c2a6.nq.gz
│   ├── 81df2890e2e77c0b0dd244f7cb562c7096333baf.nq.gz
│   ├── 864c2814205b436d25812ac2cca8e46d93acad3d.nq.gz
│   ├── 8989078e42035675ac440f959ee14a1e838e83bd.nq.gz
│   ├── 8d82fd2d184da9b30d7003e9041b54583c1055ac.nq.gz
│   ├── 9789ceb58927b60659086429ea3b6dca53621806.nq.gz
│   ├── a248dbc896604c60d2277b6c10b053f5ec9f0d5d.nq.gz
│   ├── b145ce59affad68a8ec21ff354ac4d4b1c1b2359.nq.gz
│   ├── bd4c3f65e60496ad87b00420aef92ed121c3fdf1.nq.gz
│   ├── ce7d3001845a4ebd8555fd457ee8e05e57930243.nq.gz
│   ├── d37ab97b61a0723bc6be3a502a184fb4efcbb13e.nq.gz
│   ├── dbd0542453ec3afda7fb46b7b6e0b3c2360cb3e0.nq.gz
│   ├── e9832dc8ce4a6a49df3005e4775d20dd023180ea.nq.gz
│   ├── eff790004e7cb0be2cf3511fa14c1043927de5f2.nq.gz
│   ├── f0a53fa994f1c087cddf94fe87f5e26584ab474f.nq.gz
│   ├── f3515a856c6675e99276b9e5aebfbce4349e19b2.nq.gz
│   └── f948a0ed022db2a1bcc57d8240d2eab7c7956386.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 56a1a12c38c1a5519bdcaf363ab34407ea7580cf.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 56 files
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

[rake-compiler/rake-compiler](https://github.com/rake-compiler/rake-compiler)

---
*Parsed on 2026-11-10 by [repolex](https://repolex.ai)*
