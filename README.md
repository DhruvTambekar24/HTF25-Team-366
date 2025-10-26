MVP (Minimum Viable Product) is Ready! 🚀

# 🎟️ MintMyTicket – Decentralized Event Ticketing DApp

MintMyTicket is a modern Web3-native ticketing platform that empowers users to create, buy, and verify event tickets using blockchain technology. By minting tickets as NFTs, MintMyTicket brings **transparency**, **ownership**, and **trust** into the event ticketing ecosystem.

---

## 🚨 Problem It Solves

Current Web2 ticketing platforms suffer from:

- ❌ Fake and duplicate tickets
- ❌ Lack of transparency in resale/ownership
- ❌ Centralized control of data and payments
- ❌ No live tracking of ticket use

---

## ✅ My Web3 Solution

MintMyTicket ensures:

- ✅ Tickets minted as **NFTs** (ERC721 or ERC1155)
- ✅ QR-based **on-chain ownership verification**
- ✅ Resale and **ownership traceability**
- ✅ Metadata stored on **IPFS/Filecoin**
- ✅ Transparent and secure purchase flows using **crypto wallets**

---

## 🧱 Tech Stack

| Layer      | Tech                                          |
| ---------- | --------------------------------------------- |
| Framework  | [Next.js 15 (App Router)](https://nextjs.org) |
| Styling    | Tailwind CSS, Framer Motion                   |
| Wallets    | Ethers.js                                     |
| Storage    | IPFS/Filecoin (via Pinata)                    |
| Blockchain | Solidity (Hardhat), Filecoin testnet          |
| UI Tools   | Shadcn UI, Lucide Icons                       |
| Hosting    | Vercel                                        |

---

## 📦 Features

- 🎨 NFT ticket minting with event metadata
- 💼 Wallet connect + balance check
- 📄 Ticket metadata hosted on IPFS
- 💳 Buy tickets with MetaMask
- 🔄 Transfer & resale support (future module)
- 📲 QR code-based entry verification
- 📊 User & Organizer dashboards
- 🧪 Contract & UI testing
- 🌗 Fully responsive UI + dark mode

---

## 🧪 Modules Breakdown

| #    | Module                | Description                                   |
| ---- | --------------------- | --------------------------------------------- |
| 1️⃣   | Project Setup         | Next.js 15 + Tailwind CSS + Framer Motion     |
| 2️⃣   | Wallet Integration    | Ethers js                                     |
| 3️⃣   | Smart Contracts       | NFT ticket contract (ERC721)                  |
| 4️⃣   | Ticket Minting + IPFS | Upload metadata to IPFS & mint NFTs           |
| 5️⃣   | Ticket Purchase Flow  | Buy tickets using wallet, handle transactions |
| 6️⃣   | QR Code Verification  | Scan and verify ticket ownership live         |
| 7️⃣   | Ticket Transfer       | Enable secondary ticketing & transfer         |
| 8️⃣   | User Dashboard        | View past/future/resold tickets               |
| 9️⃣   | Admin Panel           | Organizer dashboard to create/manage events   |
| 🔟   | UI/UX Polish          | Responsive design, animation, skeletons       |
| 1️⃣1️⃣ | Testing & Deployment  | Hardhat (contract) , Vercel (app)             |

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/gunjanghate/MintMyTicket.git
cd MintMyTicket
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Setup Environment Variables

Create a `.env.local` file and configure:

```
NEXT_PUBLIC_PROJECT_ID=<walletconnect_or_infura_id>
NEXT_PUBLIC_CONTRACT_ADDRESS=<deployed_ticket_contract_address>
NEXT_PUBLIC_IPFS_GATEWAY=https://your-ipfs-gateway
MONGODB_URI=your-mongodb-uri
NEXT_PUBLIC_ADMIN_WALLETS="admin wallet addresses"
```

### 4. Run the Dev Server

```bash
npm run dev
```

---

## 🔐 Smart Contracts

- **TicketNFT.sol** – ERC721 contract to mint event tickets as NFTs
- Deployed to: Filecoin Testnet (for now)
- Interacts with the frontend using **Ethers v6**

> Contract includes: `eventName`, `date`, `location`, `seat`, and `price` stored as metadata and mapped to tokenId.

---

## 🧠 Bonus Features (Planned)

- 🔗 ENS name resolution
- 🧠 AI-based ticket pricing recommendations
- 🎫 NFT-gated event creation
- 🌍 Community-driven event discovery

---

## 💡 Contributing

Pull requests are welcome! If you want to contribute to a module, please fork the repo and submit a PR.

---

## 🙌 Acknowledgments

Thanks to:

- OpenZeppelin Contracts
- Pinata
- Framer Motion
- Shadcn UI

---

## 📬 Contact

Made with ❤️ by [@gunjanghate](https://github.com/gunjanghate)
Open to contributions, feedback, and collaboration!

```

```

# HTF25-Team-366

## GitHub submission guide

In this Readme, you will find a guide on how to fork this Repository, add files to it, and make a pull request to contribute your changes.

<details open>
<summary><h3>1. Login to your GitHub Account</h3></summary>
<br>
<p>Go to <a href="https://github.com">github.com</a> to log in.</p>
<ul>
   <li>Open the <a href="https://github.com/cbitosc/HTF25-Team-366">current repo</a> in a new tab.</li>
   <li>Perform all operations in the newly opened tab, and follow the current tab for instructions.</li>
</ul>
</details>

<details open>
<summary><h3>2. Fork the Repository</h3></summary>
<br>
<p align="center">
  <img src="fork.jpeg" alt="Fork the Repository" height="300">
</p>
<ul>
 <li>In the newly opened tab, on the top-right corner, click on <b>Fork</b>.</li>
 <li>Enter the <b>Repository Name</b> as <b>HTF25-Team-366</b>.</li>
 <li>Then click <b>Create Fork</b>, leaving all other fields as default.</li>
 <li>After a few moments, you can view your forked repo.</li>
</ul>
</details>

<details open>
<summary><h3>3. Clone your Repository</h3></summary>
<br>
<ul>
 <li>Click on <b>Code</b> and copy the <b>web URL</b> of your forked repository.</li>
 <li>Open terminal on your local machine.</li>
 <li>Run this command to clone the repo:</li>
<pre><code>git clone https://github.com/your-username/HTF25-Team-366.git</code></pre>
</ul>
</details>

<details open>
<summary><h3>4. Adding files to the Repository</h3></summary>
<br>
<ul>
 <li>While doing it for the first time, create a new branch for your changes:</li>
<pre><code>git checkout -b branch-name</code></pre>
 <li>Add files or modify existing ones.</li>
 <li>Stage your changes:</li>
<pre><code>git add .</code></pre>
 <li>Commit your changes:</li>
<pre><code>git commit -m "Descriptive commit message"</code></pre>
 <li>Push your branch to your fork:</li>
<pre><code>git push origin branch-name</code></pre>
</ul>
</details>

<details open>
<summary><h3>5. Create a Pull Request</h3></summary>
<br>
<ul>
 <li>Click on the <b>Contribute</b> button in your fork and choose <b>Open Pull Request</b>.</li>
 <li>Leave all fields as default, then click <b>Create Pull Request</b>.</li>
 <li>Wait a few moments; your PR is now submitted.</li>
</ul>
</details>

## Thanks for participating!
