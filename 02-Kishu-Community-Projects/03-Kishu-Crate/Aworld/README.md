# Aworld / Kishu Crate NFT Evidence Notes

This folder tracks public evidence around Aworld's participation in the historical Kishu Crate NFT release and related Kishu-linked NFTs.

These notes are for public record and recovery work. They should be treated as evidence notes, not legal conclusions.

## Historical Links

- Kishu Inu tweet: https://x.com/InuKishu/status/1425051033630281729?s=20
- Kishu Inu tweet: https://x.com/InuKishu/status/1439637846944591875?s=20
- Aworld tweet: https://x.com/Aworld_NFT/status/1423345117503660034?s=20
- Historical OpenSea profile: https://opensea.io/KishuInu
- Historical Aworld wallet page format:
  - https://www.aworld.vip/?address=0x90ead86fca54ee9a1fe1c55c0ace5896f4319802

## Key Kishu Wallet Link

The address used in the Aworld URL is:

`0x90eAd86FCa54eE9a1FE1C55C0ACE5896f4319802`

That same address is publicly labeled by Etherscan as `Kishu Inu: Deployer`.

It also appears in the Kishu Safe setup transaction as one of the three owner addresses for:

`0x0db80Dd6316F994c62E117C504F605B2cbf7520D`

Safe creation transaction:

https://etherscan.io/tx/0xf34f45a702fac5d2f8faff1ebf3a1e9b3353c116c9898d6f1c9513542dad0e1f#eventlog

Safe owner addresses in that setup event:

- `0x90eAd86FCa54eE9a1FE1C55C0ACE5896f4319802`
- `0x7cA5A38e51c253Ef843e418c0b7115ac1cB35f75`
- `0x05C0d0B47e6334c3C170DDB6f3d2Fa7001ff6014`

Threshold: `2`

## Aworld / Kishu Crate NFT Notes

Aworld appears to have participated in the historical Kishu Crate release. The historical Aworld link used the Kishu deployer wallet address as a query parameter:

`?address=0x90ead86fca54ee9a1fe1c55c0ace5896f4319802`

That is important because it ties the Aworld-facing page to the same wallet identity used for Kishu deployer / Safe ownership.

## Rarible Maze NFTs

The following two Kishu-themed Rarible ERC-1155 NFTs are separate from the Aworld dog NFT, but they are part of the same Kishu Crate evidence trail.

Contract:

`0xd07dc4262BCDbf85190C01c996b4C06a461d2430`

OpenSea identifies this contract as `Rarible` / ERC-1155.

### Token 756345

- Name: `A-Maze Memeoir 1# Kishu`
- OpenSea: https://opensea.io/item/ethereum/0xd07dc4262bcdbf85190c01c996b4c06a461d2430/756345
- Token ID: `756345`
- Total supply: `3`
- On-chain creator: `0x0335cc963a01ca2f7482d6eb472d1492a24252b6`
- Token URI: `ipfs://ipfs/QmUHwirESuy26tuBLmUCCaGuhrLQzsH6i8FrkK6y5XAgMZ`
- Mint transaction:
  - https://etherscan.io/tx/0x2203017ab69ba9c203da6fa5d612e3cc954f1045face4251d2a4c697b7c01c37
  - Block: `13434362`
  - Time: `2021-10-17T08:29:11Z`
  - Minted from zero address to `0x0335cc963a01ca2f7482d6eb472d1492a24252b6`
  - Minted quantity: `3`

Transfer to Kishu deployer wallet:

- Transaction: https://etherscan.io/tx/0x0b2e9829378ec3577f52c10d98ec202fdcb10a1928948ed5d3979f9d41611af5
- Block: `13500532`
- Time: `2021-10-27T16:46:27Z`
- From: `0x0335cc963a01ca2f7482d6eb472d1492a24252b6`
- To: `0x90eAd86FCa54eE9a1FE1C55C0ACE5896f4319802`
- Quantity transferred: `3`

Latest checked balance:

- `0x90eAd86FCa54eE9a1FE1C55C0ACE5896f4319802` holds `3`

### Token 756349

- Name: `AMaze QR Maze #2 Kishu`
- OpenSea: https://opensea.io/item/ethereum/0xd07dc4262bcdbf85190c01c996b4c06a461d2430/756349
- Token ID: `756349`
- Total supply: `47`
- On-chain creator: `0x0335cc963a01ca2f7482d6eb472d1492a24252b6`
- Token URI: `ipfs://ipfs/QmZju4L8cRgp7218bx4Wt2hnMCq9jUn3LSbZg7uGFSLLBF`
- Mint transaction:
  - https://etherscan.io/tx/0xe6fd964618f3c4dfba67cd9af097c29319b42795efba885541bba685b5ea3022
  - Block: `13434388`
  - Time: `2021-10-17T08:36:28Z`
  - Minted from zero address to `0x0335cc963a01ca2f7482d6eb472d1492a24252b6`
  - Minted quantity: `47`

Transfer to Kishu deployer wallet:

- Transaction: https://etherscan.io/tx/0xfb87b2044e8b9b6cf0c8839f124e26509c9ee886913e89d929993c5bdb4e487e
- Block: `13500537`
- Time: `2021-10-27T16:47:14Z`
- From: `0x0335cc963a01ca2f7482d6eb472d1492a24252b6`
- To: `0x90eAd86FCa54eE9a1FE1C55C0ACE5896f4319802`
- Quantity transferred: `44`

Latest checked balances:

- `0x90eAd86FCa54eE9a1FE1C55C0ACE5896f4319802` holds `44`
- `0x0335cc963a01ca2f7482d6eb472d1492a24252b6` holds `3`

## Working Interpretation

The public evidence supports this record:

1. Aworld was publicly connected to Kishu/Kishu Crate through historical tweets and the Aworld wallet page.
2. The Aworld page used the Kishu deployer wallet address: `0x90eAd...9802`.
3. That same address is one of the Kishu Safe owner addresses.
4. The two Rarible Kishu maze NFTs were minted by `0x0335...52b6`.
5. Most or all of those maze NFT supplies were then transferred to the Kishu deployer wallet:
   - `756345`: all `3` of `3`
   - `756349`: `44` of `47`

This makes the Kishu-side custody link clear. It does not, by itself, prove who personally controlled any wallet or who made project decisions.

## Notes To Verify Later

- Confirm whether `0x0335cc963a01ca2f7482d6eb472d1492a24252b6` was an Aworld, AMazeNFT, artist, or related operational wallet.
- Preserve screenshots or archives of the old Aworld page if available.
- Preserve screenshots of the historical X posts because X availability changes over time.
- Keep OpenSea screenshots separately because current OpenSea pages can change or disappear even though the blockchain records remain.
