
## 🇬🇧 Lisk SEA Challenge Week 1 – Deploy & Verify Contracts

This repository is part of the **Lisk SEA Web3 Builder Challenge**.
It demonstrates how to **deploy and verify ERC20 + ERC721 contracts** on the **Lisk Sepolia Testnet**, and connect them to a **Next.js frontend** using **Scaffold-Lisk**.

### 🧩 Overview

You’ll find two main parts:

* **Smart Contracts (Hardhat)** — contains the ERC20 and ERC721 contract sources.
* **Frontend (Next.js)** — connects wallet, displays deployed contracts, and provides access to the block explorer and debugger.

### 🚀 Features

* Deploy verified **MyToken (ERC20)** and **MyNFT (ERC721)**
* View contracts in **Blockscout**
* Interact with contracts via **Scaffold-Lisk interface**
* Deployed frontend hosted on **Vercel**

### 🛠️ Tech Stack

* **Solidity**, **Hardhat**, **TypeScript**
* **Next.js 14**, **React**, **TailwindCSS**
* **Wagmi**, **viem**, **RainbowKit**
* **Lisk Sepolia Testnet**

### ⚙️ Setup

```bash
# install dependencies
yarn install

# start local dev
yarn start

# deploy contracts
yarn hardhat deploy --network liskSepolia

# verify contracts
yarn hardhat verify --network liskSepolia <contract_address>
```

### 🌐 Live Demo

🔗 **Frontend:** [https://sztch-lisk.vercel.app](https://sztch-lisk.vercel.app)
🔗 **Token:** `0x720eABB9e58F62454c98a70432D456009B9a1c8c`
🔗 **NFT:** `0x0c6d0D811B9A82Bbe8Dc34Ea561665B9F511EbdF`

---

## 🇮🇩 Tantangan Lisk SEA Minggu 1 – Deploy & Verifikasi Kontrak

Repositori ini dibuat untuk **Lisk SEA Web3 Builder Challenge**.
Menunjukkan cara **mendeploy dan memverifikasi kontrak ERC20 & ERC721** di **Lisk Sepolia Testnet**, lalu menghubungkannya ke **frontend Next.js** menggunakan **Scaffold-Lisk**.

### 🧩 Ringkasan

Terdiri dari dua bagian utama:

* **Smart Contracts (Hardhat)** — berisi kontrak ERC20 dan ERC721.
* **Frontend (Next.js)** — menghubungkan wallet dan menampilkan kontrak yang sudah dideploy.

### 🚀 Fitur

* Deploy dan verifikasi **MyToken (ERC20)** dan **MyNFT (ERC721)**
* Lihat kontrak di **Blockscout**
* Interaksi langsung melalui **UI Scaffold-Lisk**
* Frontend sudah di-deploy di **Vercel**

### ⚙️ Langkah Menjalankan

```bash
# instal dependensi
yarn install

# jalankan lokal
yarn start

# deploy kontrak
yarn hardhat deploy --network liskSepolia

# verifikasi kontrak
yarn hardhat verify --network liskSepolia <alamat_kontrak>
```

### 🌐 Demo Langsung

🔗 **Frontend:** [https://sztch-lisk.vercel.app](https://sztch-lisk.vercel.app)
🔗 **Token:** `0x720eABB9e58F62454c98a70432D456009B9a1c8c`
🔗 **NFT:** `0x0c6d0D811B9A82Bbe8Dc34Ea561665B9F511EbdF`

---
