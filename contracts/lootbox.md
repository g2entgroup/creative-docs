---
description: How Creative NFTs will be distributed
---

# 💰 Lootbox

* Each campaign will have a loot box \(erc1155\) containing the max supply of NFTs \(erc721\).
* Winners of the campaign will have access to this loot box to claim their NFT and other rewards.

A LootBox contract ephemerally exists within a transaction. The owner of an `ERC721` owns the LootBox.

1. A `ERC721` is created by calling `createERC721Controlled()` on the `ERC721ProxyFactory` by anyone:

```text
  function createERC721Controlled(
    string memory name,
    string memory symbol,
    string memory baseURI
  ) external returns (ERC721Controlled)
```



1. `mint()` can then be called on the `ControlledERC721` which effectively creates a LootBox with an Owner defined by the `to` field:

```text
function mint(address to) external onlyAdmin returns (uint256)
```

2. The LootBox address is calculated by calling: 

```text
computeAddress(address erc721, uint256 tokenId)
```

4. Anyone can call `plunder()` on the LootBox controller which will transfer all the passed tokens to the LootBox owner.

```text
function plunder(
  address erc721,
  uint256 tokenId,
  address[] calldata erc20s,
  WithdrawERC721[] calldata erc721s,
  WithdrawERC1155[] calldata erc1155s
)
```

where `erc20s` is defined as an array of ERC-20 addresses,

`erc721s` is defined as:

```text
struct WithdrawERC721 {
  address token;
  uint256[] tokenIds;
}
```

and `erc1155s` as:

```text
struct WithdrawERC1155 {
  address token;
  uint256[] ids;
  uint256[] amounts;
  bytes data;
}
```

