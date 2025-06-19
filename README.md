# 🛡️ Saint Khen: Boundless Guild Role Automation

Welcome to the **Saint Khen auto quest script** — a powerful tool that helps you instantly complete Boundless Guild roles (`Dev`, `Prover`, or both) with zero manual setup.

⚠️ **Note:** This is **NOT** a node setup. It simply interacts with Boundless smart contracts to submit the required transactions and claim your role eligibility.

---

## ✅ Requirements

Before running the script, **make sure you have**:

- ✅ A **GitHub account older than 6 months**
- ✅ A **Discord account older than 6 months**
- ✅ A **new/clean MetaMask wallet** (for safety)

If you don’t meet these conditions, completing the final Guild quest **won’t count**.

---

## 🔧 Prerequisites

You can run this on **any free VPS or cloud server** (even the cheapest ones).

**Before setup:**

1. Go to **https://guild.xyz/boundless-xyz**
2. Connect your **MetaMask wallet**
3. Link your **Discord** and **GitHub** accounts
4. Create an **Alchemy Base Mainnet RPC URL**

   - Go to [https://www.alchemy.com/](https://www.alchemy.com/)
   - Create a new app for **Base Mainnet**
   - Copy your RPC URL (Format: `https://base-mainnet.g.alchemy.com/v2/YOUR_API_KEY`)

5. Have your **wallet private key** ready  
   ⚠️ Only use an empty wallet!

---

## 💰 Required Wallet Balances

| Role | Requirements |
|------|--------------|
| Prover | `10 USDC` + small amount of ETH for gas |
| Dev    | `0.000001 ETH` + gas ETH |
| Both   | `10 USDC + 0.000001 ETH` + ~$1-2 ETH for fees |

---

## ⚙️ Installation Steps

### 1. Connect to your server

```bash
ssh root@your-server-ip

```

2. Install dependencies
```
sudo apt update && sudo apt install -y curl git
```
3. Download and run the script
```
bash <(curl -s https://raw.githubusercontent.com/emmogrin/SaintKhen-Boundless-Auto/main/saintkhen-boundless.sh)
```
📌 Note: Setup may take several minutes depending on your system. Be patient while Rust, RISC Zero, and Boundless CLI are being installed.


---

📥 What the script will ask:

🔗 Your Alchemy Base RPC URL

🔑 Your wallet private key (input is hidden)

🎭 Your selected role: Prover, Dev, or Both

💸 The amount to stake or deposit

✅ It will check your wallet balance

📤 Then automatically submit the transaction(s)



---

✅ After Successful Setup

You will see a confirmation message like:

✅ GUILD QUEST COMPLETED!
🎉 Welcome to the Boundless Network!

Then head back to:

👉 https://guild.xyz/boundless-xyz
…to complete and verify the rest of your Guild role quests.


---

⚠️ Troubleshooting

Error: Insufficient balance

Make sure your wallet has enough USDC and ETH (for gas)

Check you're using the Base network


Error: RPC connection failed

Double-check your Alchemy RPC URL

Ensure your API key is correct and active



---

👑 Built by @admirkhen

Script designed by @admirkhen for the community.
Support or feature requests? DM me or open an issue.

Happy questing 💥
