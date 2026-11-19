# Aditaya

Web3 full-stack engineer, final year of B.Tech CSE at Bennett University. Most of my work is
Bitcoin: script execution, multisig, PSBTs. The rest is the product layer around it, plus
Solidity when the chain needs a contract.

I'd rather ship one thing that holds up under questioning than five that look good in a
screenshot.

## Things I've built

**[ScriptScope](https://bitcoin-script-analyser-web.vercel.app)** is a debugger for Bitcoin
Script. The execution engine is Rust compiled to WebAssembly, so about 75 opcodes step
instruction by instruction in the browser with no round trip. An Axum API beside it fetches
and decodes mainnet transactions with provider fallback. Eight Rust integration tests cover
opcode classification, the debugger flow, and consensus limits. [Code](https://github.com/Aditaya08/Bitcoin_Script_Analyser)

**[Auto_Lend](https://github.com/Aditaya08/Auto_Lend)** does non-custodial P2P lending on
Bitcoin regtest. Each loan sits behind a 2-of-3 P2WSH multisig, signing runs through PSBTs,
and a CLTV script handles recovery when a borrower stops responding. Express and Mongo hold
the state machine, with Next.js consoles for borrowers and lenders.

**[Bitcoin-Explorer](https://github.com/Aditaya08/Bitcoin-Explorer)** is a testnet block
explorer and wallet: Next.js 16 over an Express wrapper on Bitcoin Core's JSON-RPC.

**[dog-show-app](https://github.com/Aditaya08/dog-show-app)** is the non-crypto one. Show
management over a Prisma/PostgreSQL schema of five related models, with role-based auth and
audit middleware that records who changed what.

## What I use

Web3: Bitcoin Script, PSBT, P2WSH multisig, CLTV, regtest, Solidity/EVM \
Frontend: TypeScript, React, Next.js, Tailwind, React Query, Zustand \
Backend: Node and Express, NestJS, FastAPI, Prisma, PostgreSQL, MongoDB, Redis \
Systems: Rust, WebAssembly \
Also: Docker, GitHub Actions, Linux

## Elsewhere

[LinkedIn](https://www.linkedin.com/in/aditaya-krishna-sharma-600b122a3) � [aditayash625@gmail.com](mailto:aditayash625@gmail.com)
