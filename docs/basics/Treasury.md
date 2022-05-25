
# Treasury
There are two main treasury contracts containing DAO assets.

## Protocol treasury holding all funds collected including:
- ETH from baking
- ETH from partner project earnings
- ETH/MINT LP tokens from bonding
- Any other future assets that can be used to purchase MINT

This treasury contract is responsible for producing MINT to pay bakers and staking rewards based on the RFV of treasury assets. It will be protected by 4/7 multisig. 

## DAO treasury holding funds used for operational purposes. 

This is a gnosis vault with 4/7 multisig likely with the same signers as the protocol treasury. Initially this vault will contain:
- The DAOs 8 billion pMINT allocation
- The DAOs share of MINT earned via bonding fees. 
- A portion of earned MINT and/or pMINT will likely be sold to other assets like USDC or DAI to have a stable reserve to pay contributors and other operational expenses.

