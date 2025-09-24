# 🚀 dapp-workshop-public | EN | ID

This project is a hands-on example of how to deploy a smart contract using **Hardhat** and build a dApp frontend using **React**.

Proyek ini adalah contoh praktis cara deploy smart contract dengan **Hardhat** dan membangun dApp frontend pakai **React**.

---

## 🛠️ Hardhat Deployment Steps | Langkah Deploy Hardhat

## 1️⃣ Init Node Project
```bash
npm init
```

## 2️⃣ Install Hardhat Locally | Install Hardhat sebagai dependency lokal
```bash
npm install --save-dev hardhat
```

## 3️⃣ Setup Hardhat (TypeScript + Viem)
```bash
npx hardhat init
```

## 4️⃣ Write Your Smart Contract
Write a contract and place it in the smartContract/contracts/ folder.
You can see an example: Certifications.sol or use it directly.

## 5️⃣ Compile Contract
```bash
npx hardhat compile
```

## 6️⃣ Run Tests (Optional)
```bash
npx hardhat test
```
## 7️⃣ Setup Environment Variables
Rename the .env.example file to .env:
### Linux/Mac:
```bash
mv .env.example .env
```
### Windows:
```bash
rename .env.example .env
```
Fill in the private key without 0x:
```bash
WALLET_API_KEY = "39a17e36bEXAMPLEabcdefghijkaa6b4d238ff944bacb478cbed5efcae784d7bf4f2ff80"
WALLET_ADDRESS = "f39fd6e51aad88f6f4ce6abEXAMPLEcfffb92266"
```

## 8️⃣ Deploy Smart Contract to KiiChain
```bash
npx hardhat ignition deploy ignition/modules/Certifications.ts --network kiichain
```
