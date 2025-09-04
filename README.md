# 🚀 MyToken on Base

A simple ERC20 token deployed on the [Base Network](https://base.org).

---

## 📌 Features
- ERC20 Standard (transferable, fungible tokens)
- Ownable: only the owner can mint new tokens
- Built with OpenZeppelin contracts
- Deployed on **Base Sepolia Testnet** or **Base Mainnet**

---

## 🛠️ How to Deploy (Using Remix)

1. Open [Remix IDE](https://remix.ethereum.org).
2. Create a new file `MyToken.sol` and paste in the contract code.
3. Install OpenZeppelin:
   - In Remix, enable **File Explorer → Import from GitHub**.
   - Add at the top:
     ```solidity
     import "@openzeppelin/contracts/token/ERC20/ERC20.sol";
     import "@openzeppelin/contracts/access/Ownable.sol";
     ```
4. Compile with Solidity `^0.8.20`.
5. Go to **Deploy & Run**:
   - Select **Injected Web3**.
   - Connect your MetaMask wallet.
   - Choose **Base network** (see below).
6. Deploy with:
   - Initial supply (e.g. `1000000` for 1M tokens).

---

## 🌐 Add Base to MetaMask

### Base Mainnet
- **Network Name**: Base Mainnet  
- **RPC URL**: `https://mainnet.base.org`  
- **Chain ID**: `8453`  
- **Currency Symbol**: ETH  
- **Block Explorer**: [https://basescan.org](https://basescan.org)  

### Base Sepolia (Testnet)
- **Network Name**: Base Sepolia  
- **RPC URL**: `https://sepolia.base.org`  
- **Chain ID**: `84532`  
- **Currency Symbol**: ETH  
- **Block Explorer**: [https://sepolia.basescan.org](https://sepolia.basescan.org)  

---

## 📤 Interact with Your Token
- **Transfer**: send tokens to any wallet.  
- **Mint (Owner only)**: create new tokens with `mint(address to, uint256 amount)`.  
- **Check Balance**: use `balanceOf(address)`.

---

## 🖼️ Visuals

![Solidity](https://img.shields.io/badge/Solidity-363636?style=for-the-badge&logo=solidity&logoColor=white)
![Base](https://img.shields.io/badge/Base%20Network-0052FF?style=for-the-badge&logo=coinbase&logoColor=white)
![MetaMask](https://img.shields.io/badge/MetaMask-F6851B?style=for-the-badge&logo=metamask&logoColor=white)

---

## ⚡ Example Workflow
1. Deploy with `1,000,000` supply.
2. Confirm transaction in MetaMask.
3. Add token to MetaMask:
   - Copy your deployed contract address.
   - In MetaMask → **Import Tokens** → paste address.
4. You’ll see your new **MTK** tokens 🎉

---

## 📜 License
MIT License © 2025
