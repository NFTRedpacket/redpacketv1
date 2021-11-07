### What is RedPacket?

Red packet is a tool to store crypto money (currently ETH) in NFT. When the NFT is transfered to others, the crypto money stored in is also transfered. In Asian cultures, red packet (or red envelope) is a monetary gift given during holidays or for special occasions such as a wedding, graduation or the birth of a baby. So I think red-packet is a good name to descripe what we do with NFT.

### Why build this?
It's cool if I can store money in NFT, with red-packet, the NFT is not only an NFT, but also has real value. 

### How to use it?
To use RedPacket, you need to know your NFT's contract address and NFT's token id. You can find these information at OpenSea's detail card. For example, [CryptoPunk 7557](https://opensea.io/assets/0xb47e3cd837ddf8e4c57f05d70ab865de6e193bbb/7557), open the link and at the detail card you can see:

<img src="https://i.imgur.com/v8zD20Z.png" width="380" />

Input the NFT contract address and token id, you can create redpacket, you can also open the redpacket with the same NFT address and token id. 

**Note**: Only the owner of the NFT can create or open an redpacket, when you transfer the NFT to others, the money stored in is also transfered. One NFT can only create one redpacket, you cannot store money to an NFT that already has a redpacket. But once the NFT's redpacket is opened, you can store money in it again.

### Does it take fees?

YES, `fee = min(0.1% * value, 0.001eth)`, value is your stored crypto money. That means we take a fee of 0.1% (at most 0.001ETH) when you open a redpacket and withdraw the stored money. For example, when you store 0.1ETH, we take `0.1*0.001 = 0.0001ETH`, but when you stored 1ETH or more, we always take 0.001ETH.








