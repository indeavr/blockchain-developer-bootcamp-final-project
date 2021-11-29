# Design Patterns

## Inheritance and Interfaces
- Using OpenZeppelin ERC-721
  - `lib/DynamicERC721.sol`
  - `CondoToken.sol`
  - `CondoGovernor.sol`

## Access Control Design Patterns
- Using `onlyOwner` to limit critical functions like `safeMint()` , `addUpgrade` being accessed by anyone except the contract `owner`

## Oracles
- `OracleDynamicERC721/sol`
