# ERC-165 Interface ID List

This is a compiled list of Ethereum ERC-165 interface IDs. 

To verify these interfaces with any contract you can use the EIP-1820 contract: 
https://etherscan.io/address/0x1820a4B7618BdE71Dce8cdc73aAB6C95905faD24#readContract 

## Contributing

Feel free to submit PRs with changes/additions as needed. When adding or modifying interface IDs be sure to make changes to both the below README and the included [csv file](erc165-id-list.csv). 

### Contributors

![FungyProof](https://uploads-ssl.webflow.com/616ef6c367c9ed791f8c91ea/617b101f0e573112e40e2db4_fp-favicon.png)  Originally created by [@MIKΞR](https://github.com/mikehroth) for [FungyProof](https://fungyproof.com) 

---

|Name                          |Interface ID|Description                                                         |EIP Link                                                                             |
|------------------------------|------------|--------------------------------------------------------------------|-------------------------------------------------------------------------------------|
|ERC165                        |`0x01FFC9A7`     |Supports interface standard interface                               |https://github.com/ethereum/EIPs/blob/master/EIPS/eip-165.md                         |
|ERC173                        |`0x7F5828D0`    |Contract ownership standard interface                               |https://github.com/ethereum/EIPs/blob/master/EIPS/eip-173.md                         |
|ERC721                        |`0x80AC58CD`    |NFT standard interface                                              |https://github.com/ethereum/EIPs/blob/master/EIPS/eip-721.md                         |
|ERC721Metadata                |`0x5B5E139F`    |NFT metadata standard interface                                     |https://github.com/ethereum/EIPs/blob/master/EIPS/eip-721.md                         |
|ERC721TokenReceiver           |`0x150B7A02`    |NFT receiver standard interface                                     |https://github.com/ethereum/EIPs/blob/master/EIPS/eip-721.md                         |
|ERC721Enumerable              |`0x780E9D63`    |NFT enumerable ids standard interface                               |https://github.com/ethereum/EIPs/blob/master/EIPS/eip-721.md                         |
|ERC725X                       |`0x44C028FE`    |Smart contract based account executor standard interface            |https://github.com/ethereum/EIPs/blob/master/EIPS/eip-725.md                         |
|ERC725Y                       |`0x714DF77C`    |Smart contract based account key/value storage standard interface   |https://github.com/ethereum/EIPs/blob/master/EIPS/eip-725.md                         |
|ERC998ERC721TopDown           |`0xCDE244D9`    |Top-down composable NFT standard interface                          |https://github.com/ethereum/EIPs/blob/master/EIPS/eip-998.md                         |
|ERC998ERC721TopDownEnumerable |`0xA344AFE4`    |Top-down composable and enumerable NFT standard interface           |https://github.com/ethereum/EIPs/blob/master/EIPS/eip-998.md                         |
|ERC998ERC20TopDown            |`0x7294FFED`    |Top-down composable fungible token standard interface               |https://github.com/ethereum/EIPs/blob/master/EIPS/eip-998.md                         |
|ERC998ERC20TopDownEnumerable  |`0xC5FD96CD`    |Top-down composable and enumerable fungible token standard interface|https://github.com/ethereum/EIPs/blob/master/EIPS/eip-998.md                         |
|ERC998ERC721BottomUp          |`0xA1B23002`    |Bottom-up compsable NFT standard interface                          |https://github.com/ethereum/EIPs/blob/master/EIPS/eip-998.md                         |
|ERC998ERC721BottomUpEnumerable|`0x8318B539`    |Bottom-up composable and enumerable NFT standard interface          |https://github.com/ethereum/EIPs/blob/master/EIPS/eip-998.md                         |
|ERC998ERC20BottomUp           |`0xFFAFA991`    |Bottom-up composable fungible token standard interface              |https://github.com/ethereum/EIPs/blob/master/EIPS/eip-998.md                         |
|ERC1155                       |`0xD9B67A26`    |Semi-fungible token standard interface                              |https://github.com/ethereum/EIPs/blob/master/EIPS/eip-1155.md                        |
|ERC1155TokenReceiver          |`0x4E2312E0`    |Semi-fungible token receiver standard interface                     |https://github.com/ethereum/EIPs/blob/master/EIPS/eip-1155.md#erc-1155-token-receiver|
|ERC1155MetadataURI            |`0xE89341C`     |Semi-fungible metadata uri standard interface                       |https://github.com/ethereum/EIPs/blob/master/EIPS/eip-1155.md#metadata               |
|ERC1523                       |`0x5A04BE32`    |Insurance policy standard interface                                 |https://github.com/ethereum/EIPs/blob/master/EIPS/eip-1523.md                        |
|ERC777Name                    |`0x6FDDE03`     |Token contract name standard interface                              |https://github.com/ethereum/EIPs/blob/master/EIPS/eip-777.md                         |
|ERC777Symbol                  |`0x95D89B41`    |Token contract symbol standard interface                            |https://github.com/ethereum/EIPs/blob/master/EIPS/eip-777.md                         |
|ERC777TotalSupply             |`0x18160DDD`    |Token contract total supply standard interface                      |https://github.com/ethereum/EIPs/blob/master/EIPS/eip-777.md                         |
|ERC777BalanceOf               |`0x70A08231`    |Token contract balanceOf standard interface                         |https://github.com/ethereum/EIPs/blob/master/EIPS/eip-777.md                         |
|ERC777Burn                    |`0xFE9D9303`    |Token burn standard interface                                       |https://github.com/ethereum/EIPs/blob/master/EIPS/eip-777.md                         |
|ERC777OperatorBurn            |`0xFC673C4F`    |Token operator burn standard interface                              |https://github.com/ethereum/EIPs/blob/master/EIPS/eip-777.md                         |
|ERC777Send                    |`0x9BD9BBC6`    |Token send standard interface                                       |https://github.com/ethereum/EIPs/blob/master/EIPS/eip-777.md                         |
|ERC777OperatorSend            |`0x62AD1B83`    |Token operator send standard interface                              |https://github.com/ethereum/EIPs/blob/master/EIPS/eip-777.md                         |
|ERC777Granularity             |`0x556F0DC7`    |Token granularity standard interface                                |https://github.com/ethereum/EIPs/blob/master/EIPS/eip-777.md                         |
|ERC777DefaultOperators        |`0x06E48538`     |Token default operators standard interface                          |https://github.com/ethereum/EIPs/blob/master/EIPS/eip-777.md                         |
|ERC777AuthorizeOperator       |`0x959B8C3F`    |Token authorize operator standard interface                         |https://github.com/ethereum/EIPs/blob/master/EIPS/eip-777.md                         |
|ERC777RevokeOperator          |`0xFAD8B32A`    |Token revoke operator standard interface                            |https://github.com/ethereum/EIPs/blob/master/EIPS/eip-777.md                         |
|ERC777IsOperatorFor           |`0xD95B6371`    |Token is operator for standard interface                            |https://github.com/ethereum/EIPs/blob/master/EIPS/eip-777.md                         |
|ERC777TokensToSend            |`0x75AB9782`    |Tokens to send hook standard interface                              |https://github.com/ethereum/EIPs/blob/master/EIPS/eip-777.md                         |
|ERC777TokensReceieved         |`0x0023de29`      |Tokens received hook standard interface                             |https://github.com/ethereum/EIPs/blob/master/EIPS/eip-777.md                         |
|ERC1538                       |`0x61455567`    |Transparent contract standard interface                             |https://github.com/ethereum/EIPs/blob/master/EIPS/eip-1538.md                        |
|ERC2477                       |`0x832A7E0E`    |Token metadata integrity standard interface                         |https://github.com/ethereum/EIPs/blob/master/EIPS/eip-2477.md                        |
|ERC721GetImageSvg             |`0x87D2F48C`    |NFT SVG image storage standard interface                            |https://github.com/ethereum/EIPs/blob/master/EIPS/eip-2569.md                        |
|ERC2767                       |`0xD8B04E0E`    |Governance contract standard interface                              |https://github.com/ethereum/EIPs/blob/master/EIPS/eip-2767.md                        |
|ERC2981                       |`0x2A55205A`    |NFT royalities standard interface                                   |https://github.com/ethereum/EIPs/blob/master/EIPS/eip-2981.md                        |
|ERC721Consumable              |`0x953C8DFA`    |ERC-721 Consumer Role extension standard interface                  |https://github.com/ethereum/EIPs/blob/master/EIPS/eip-4400.md                        |
|SaferERC-20                   |`0x534F5876`    |ERC20 extension for safe transfer functions standard interface      |https://github.com/ethereum/EIPs/blob/master/EIPS/eip-4524.md                        |

