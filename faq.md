### What is RedPacket?

Red packet is a tool to store crypto money (currently ETH) in NFT. When the NFT is transfered to others, the crypto money stored in is also transfered. In Asian cultures, red packet (or red envelope) is a monetary gift given during holidays or for special occasions such as a wedding, graduation or the birth of a baby. So I think red-packet is a good name to descripe what we do with NFT.

### Why build this?
It's cool if I can store money in NFT, with red-packet, the NFT is not only an NFT, but also has real value. 

### Supported chains and protocol?

Currently, we only support Ethereum mainnet and the ERC-721 protocol, ERC-1155 is not supported. 

**Note**: [CryptoPunks](https://opensea.io/collection/cryptopunks) is not a ERC-721 compatible protocol, so we dot't support CryptoPunks, too.

### How to use it?
To use RedPacket, you need to know your NFT's contract address and NFT's token id. You can find these information at OpenSea's detail card. Eg, [Bored Ape #9240](https://opensea.io/assets/0xbc4ca0eda7647a8ab7c2061c2e118a18a936f13d/9240), open the link and at the detail card you can see:

<img src="https://i.imgur.com/PVrDBQn.png" width="380" />

Input the NFT contract address and token id, you can create redpacket, you can also open the redpacket with the same NFT address and token id. 

You can also get the NFT address and token from the opensea url, eg: 

```
https://opensea.io/assets/0xbc4ca0eda7647a8ab7c2061c2e118a18a936f13d/9240
// 0xbc4ca0eda7647a8ab7c2061c2e118a18a936f13d is the NFT address
// 9240 is the NFT token id
```

**Note**: Only the owner of the NFT can create or open an redpacket, when you transfer the NFT to others, the money stored in is also transfered. One NFT can only create one redpacket, you cannot store money to an NFT that already has a redpacket. But once the NFT's redpacket is opened, you can store money in it again.

### Does it take fees?

YES, `fee = min(0.1% * value, 0.001eth)`, value is your stored crypto money. That means we take a fee of 0.1% (at most 0.001ETH) when you open a redpacket and withdraw the stored money. For example, when you store 0.1ETH, we take `0.1*0.001 = 0.0001ETH`, but when you stored 1ETH or more, we always take 0.001ETH.

### Play in testnet?

We all know that ethereum is expensive, if you want to play with Redpacket in a testnet, just open https://redpacket.app/send#dev (with a `#dev` appendix), then switch to the testnet - Ropsten. **Note that, your NFT should also minted at the same testnet.** When you want to open the redpacket, click https://redpacket.app/open#dev (dont forget to switch network), then you can open the packet. 




