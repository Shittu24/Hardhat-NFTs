# NON FUNGIBLE TOKENS (NFTs)

We built 3 different kinds of NFTs:
1. A Basic NFT
2. IPFS Hosted NFT 
   1. That uses Randomness to generate a unique NFT
3. SVG NFT (Hosted 100% on-chain) 
   1. Uses price feeds to be dynamic


For the IPFS hosted NFT, when users mint NFT a chainlink VRF call will be triggeredto get a random number. The random number will then be used to generate a random NFT. We also set the rarity of each of the minted NFTs. Users will also have to pay to mint the NFTs and the owner of the contract can withdraw the ETH paid to mint the NFT. 

Lastly, for the dynamic NFTs the NFTs will be strored on chain so we dont have to worry about losing the data however, it is very expensive. 
