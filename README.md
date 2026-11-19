<h1 align="center">Aditaya </h1>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=20&pause=1200&color=8B949E&center=true&vCenter=true&width=600&lines=Web3+full-stack+engineer;Bitcoin+Script+and+PSBT;Rust+%E2%86%92+WebAssembly;Solidity+when+the+chain+needs+it" alt="What I work on" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Bitcoin-₿-F7931A?style=flat-square&logo=bitcoin&logoColor=white" alt="Bitcoin" />
  <img src="https://img.shields.io/badge/Web3-full--stack-6E56CF?style=flat-square&logo=web3dotjs&logoColor=white" alt="Web3" />
  <img src="https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fmempool.space%2Fapi%2Fv1%2Ffees%2Frecommended&query=%24.fastestFee&label=fastest%20fee&suffix=%20sat%2FvB&color=F7931A&style=flat-square" alt="Current Bitcoin fee" />
</p>

Web3 full-stack engineer, final year of a B.Tech in Computer Science. Most of my work is
Bitcoin: script execution, multisig, PSBTs. The rest is the product layer around it, plus
Solidity when the chain needs a contract.

I'd rather ship one thing that holds up under questioning than five that look good in a
screenshot.

## ⚡ Things I've built

### 🔍 [ScriptScope](https://bitcoin-script-analyser-web.vercel.app)

A debugger for Bitcoin Script. The execution engine is Rust compiled to WebAssembly, so about
75 opcodes step instruction by instruction in the browser with no round trip. An Axum API
beside it fetches and decodes mainnet transactions with provider fallback. Eight Rust
integration tests cover opcode classification, the debugger flow, and consensus limits.

<p>
  <img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white" alt="Rust" />
  <img src="https://img.shields.io/badge/WebAssembly-654FF0?style=flat-square&logo=webassembly&logoColor=white" alt="WebAssembly" />
  <img src="https://img.shields.io/badge/Axum-000000?style=flat-square&logo=rust&logoColor=white" alt="Axum" />
  <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React" />
  <a href="https://bitcoin-script-analyser-web.vercel.app"><img src="https://img.shields.io/badge/live-demo-2ea44f?style=flat-square" alt="Live demo" /></a>
</p>

### 🤝 [Auto_Lend](https://github.com/Aditaya08/Auto_Lend)

Non-custodial P2P lending on Bitcoin regtest. Each loan sits behind a 2-of-3 P2WSH multisig,
signing runs through PSBTs, and a CLTV script handles recovery when a borrower stops
responding. Express and Mongo hold the state machine, with Next.js consoles for borrowers and
lenders.

<p>
  <img src="https://img.shields.io/badge/Bitcoin_Script-F7931A?style=flat-square&logo=bitcoin&logoColor=white" alt="Bitcoin Script" />
  <img src="https://img.shields.io/badge/PSBT-F7931A?style=flat-square&logo=bitcoin&logoColor=white" alt="PSBT" />
  <img src="https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white" alt="Express" />
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white" alt="MongoDB" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js" />
</p>

### ⛓ [Bitcoin-Explorer](https://github.com/Aditaya08/Bitcoin-Explorer)

A testnet block explorer and wallet: Next.js 16 over an Express wrapper on Bitcoin Core's
JSON-RPC.

<p>
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js" />
  <img src="https://img.shields.io/badge/Bitcoin_Core-F7931A?style=flat-square&logo=bitcoin&logoColor=white" alt="Bitcoin Core" />
  <img src="https://img.shields.io/badge/JSON--RPC-4B5563?style=flat-square" alt="JSON-RPC" />
</p>

### 🐕 [dog-show-app](https://github.com/Aditaya08/dog-show-app)

The non-crypto one. Show management over a Prisma/PostgreSQL schema of five related models,
with role-based auth and audit middleware that records who changed what.

<p>
  <img src="https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white" alt="Prisma" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
</p>

## 🧰 What I use

<p align="center">
  <img src="https://skillicons.dev/icons?i=rust,solidity,typescript,react,nextjs,nodejs&theme=dark" alt="Rust, Solidity, TypeScript, React, Next.js, Node" />
  <br />
  <img src="https://skillicons.dev/icons?i=express,prisma,postgres,mongodb,docker,linux&theme=dark" alt="Express, Prisma, PostgreSQL, MongoDB, Docker, Linux" />
</p>

Bitcoin: Script, PSBT, P2WSH multisig, CLTV \
Chain work: Solidity/EVM, Bitcoin Core RPC, regtest \
Product layer: TypeScript, React, Next.js, Node, Prisma, PostgreSQL, MongoDB \
Low level: Rust, WebAssembly

## 📬 Elsewhere

<p>
  <a href="https://x.com/aditayash625"><img src="https://img.shields.io/badge/X-000000?style=flat-square&logo=x&logoColor=white" alt="X" /></a>
  <a href="https://www.linkedin.com/in/aditaya-krishna-sharma-600b122a3"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:aditayash625@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1f6feb,100:6E56CF&height=100&section=footer" alt="" />
