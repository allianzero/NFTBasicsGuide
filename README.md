# NFTBasicsGuide

NFT basics: what they are, how minting works, and how to avoid fakes. An NFT (non-fungible token) is a unique token on a blockchain that proves ownership of a specific item — usually a digital image, but also music, tickets, game items, and more.

> This guide is educational only, not financial advice. Most NFTs lose value, many are fakes or scams, and "owning" an NFT does not always mean owning the copyright to the art.

## 1. Fungible vs non-fungible, in plain language

- **Fungible:** interchangeable. One bitcoin is the same as any other bitcoin, like one dollar bill is the same as another.
- **Non-fungible:** unique. Each NFT has its own token ID, and one NFT is not interchangeable with another, even in the same collection.

An NFT is a token on a blockchain (commonly ERC-721 or ERC-1155 on Ethereum-compatible chains) that points to something: usually metadata (name, description, image link) stored on-chain or, more often, off-chain.

## 2. What you actually own when you buy an NFT

This is the most misunderstood part. Buying an NFT usually gives you:

- Ownership of **that token** on the blockchain, recorded in your wallet.
- The ability to transfer, sell, or display that token.

It usually does **not** give you:

- Copyright to the artwork. The creator usually keeps copyright unless the licence explicitly says otherwise.
- Exclusive use of the image. Anyone can copy, screenshot, or download the image file.
- Control over where the image is hosted. If the metadata points to a server that goes down, your NFT may point to nothing.

**Always read the project's licence and terms** before buying. "Owning the NFT" and "owning the art" are different things.

## 3. How minting works

**Minting** means creating a new NFT on the blockchain.

1. A project deploys a smart contract for its collection, with rules: total supply, price, mint limit per wallet, and start time.
2. During the mint window, you connect your wallet and pay the mint price (if any) plus a network gas fee.
3. The contract creates a new token with a unique ID and assigns it to your wallet.
4. The token's metadata — name, traits, image — is revealed immediately or after a "reveal" step, depending on the project.

**Free mints** still cost gas, and gas can spike during a popular mint. A "free" mint that costs more in gas than the NFT is worth is not free. Always preview the total cost before confirming.

**Allowlist / whitelist:** some mints reserve early access for specific wallets. Allowlist spots are frequently faked or sold by scammers — verify through the project's official channels only.

## 4. Marketplaces: buying and selling

An NFT marketplace (such as OpenSea, Blur, or chain-specific markets) is where NFTs are listed and traded.

- **Listing:** you approve the marketplace to transfer your NFT, then set a price and duration. Approval is a real permission — only approve marketplaces you trust.
- **Buying:** you pay the price plus marketplace fees and gas. Check the collection contract address, not just the name and image, before buying.
- **Royalties:** many collections pay the creator a percentage on secondary sales. Royalty enforcement varies by marketplace and chain — do not assume it is guaranteed.
- **Floor price:** the lowest listing price in a collection. It is a rough signal, not a valuation. One low listing does not mean the whole collection is worth that, and a high floor can be manipulated by wash trading.

## 5. How to verify a collection is real

Fakes are the biggest beginner trap. Before buying, check all of these:

1. **Contract address:** get it from the project's official website or official social accounts, and compare it exactly with the marketplace listing. A fake collection can copy the name, art, and description perfectly — only the contract address is hard to fake.
2. **Official links:** follow links from the project's own site, not from a search result, ad, or DM.
3. **Trading history:** a real, established collection usually has a history of sales over time. A collection created yesterday with sudden volume is suspicious.
4. **Holder distribution:** if a handful of wallets hold most of the supply, the price can be manipulated easily.
5. **Team and roadmap:** anonymous teams are common, but a project with no verifiable history, no clear terms, and only hype is a warning sign.

If any check fails, do not buy. There will always be another collection.

## 6. Common NFT scams

| Scam | How it works | Defence |
|---|---|---|
| Fake collection | A copy of a popular collection, same art, different contract | Verify the contract address from official sources |
| Phishing mint site | A fake mint page that drains your wallet when you "mint" | Only mint from links on the project's official site |
| Fake airdrop | An NFT appears in your wallet; its site asks you to connect and claim | Do not interact with unknown NFTs; hide or ignore them |
| Malicious approval | A site tricks you into approving unlimited transfers | Read approvals; use a separate wallet for minting |
| Wash trading | The same wallets trade an NFT back and forth to fake volume and price | Check holder and trade history, not just volume |
| Pump and dump | Influencers hype a collection, then sell into the buyers they attracted | Research before buying; ignore urgency |
| Fake support / giveaway | "Send your NFT to verify it" or "win a rare NFT" | No legitimate project asks you to send your NFT for verification |

**Never send your NFT to anyone for "verification", "upgrading", or "repair".** There is no such process.

## 7. Costs beyond the price

- **Mint price:** what the project charges, if anything.
- **Gas fee:** paid to the network for minting, buying, listing, and transferring. Gas spikes during popular mints.
- **Marketplace fee:** a percentage of the sale price, charged by the marketplace.
- **Royalty:** a percentage of secondary sales, paid to the creator where enforced.
- **Bridge and transfer fees:** if you move an NFT between chains, if that is even supported.

Add all of these before deciding whether a trade is profitable. Many "profitable" flips lose money after fees.

## 8. Storing and displaying NFTs safely

- Keep valuable NFTs in a wallet you do not connect to random mint sites. Use a separate "minting wallet" for experiments.
- Do not approve marketplaces or apps with unlimited permissions on your vault wallet.
- Back up your seed phrase on paper, as with any wallet — losing it loses the NFTs too.
- If an unknown NFT appears in your wallet, do not interact with it, do not list it, and do not visit its linked site. Hide it if your wallet allows that.

## 9. Valuation: why most NFTs lose value

- **Supply vs demand:** most collections have thousands of items but only a handful of genuine buyers.
- **Hype cycles:** prices driven by social media attention fall when attention moves on.
- **No cash flow:** unlike a stock or a rental property, most NFTs produce no income. Their value depends entirely on someone else wanting to buy later.
- **Illiquidity:** a listed NFT can sit unsold for months. A "floor price" is meaningless if nobody buys at that price.

Treat NFT buying as collecting or speculating with money you can afford to lose completely — not as investing.

## 10. Frequently asked questions

**Can anyone copy my NFT's image?**
Yes. The image file can be copied by anyone. What is unique is the token and its ownership record, not the image itself.

**Do I own the copyright if I buy an NFT?**
Usually no. Check the project's licence. Some projects grant broad commercial rights; most grant little or nothing beyond owning the token.

**What is a "reveal"?**
Some projects mint tokens with hidden metadata, then reveal the actual art and traits later. Until reveal, you do not know which item you got.

**Can an NFT be stolen?**
Yes — through phishing, malicious approvals, or a compromised wallet. The same wallet security rules apply (see WalletSetupGuide and CryptoSecurityBasics).

**Are NFTs only art?**
No. NFTs are also used for game items, event tickets, membership passes, domain names, and digital identity. The technology is general; the art bubble is only one use.

> Educational content only. This is not financial, legal, or tax advice.
