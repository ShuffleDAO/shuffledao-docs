
# Treasury
There are two main treasury contracts containing DAO assets. It is important to understand the differences and purposes of each.

## Protocol Treasury
The protocol treasury represents all assets owned and controlled directly by the protocol. This is referred to as Protocol Controlled Value (PCV). The treasury contract is protected by 4/7 multisig. 

The two types of asset catagories are:
- **Treasury Reserves:** Liquid reserves backing each MINT token. Currently this is only ETH and rETH.
- **Protocol Owned Liquidity (POL):** The DAO aims to own all of its MINT/ETH LP positions to ensure a liquid market. All fees generated from LP tokens are also collected into the treasury. 


## DAO Treasury
The DAO treasury holds funds used for operational purposes like paying core contributors for project work and monthly bills. This is a Gnosis Safe with 4/7 multisig.

Initially this vault will contain:
- ETH collected from partner projects
- The DAOs pMINT allocation
- The DAOs share of MINT earned via baking fees. 

DAO votes are required for spending DAO treasury assets. Quarterly budgets will be proposed to reduce the need for proposals and votes for individual expenses. 

### Bootstrap Phase

During the initial bootstrap phase all ETH collected from partner projects will split evenly between DAO contributors that work directly with our partners and the DAO treasury. Once the DAO treasury meets specific milestones a gradual transition from bootstrap mode will begin and project ETH will start to be allocated directly to the protocol treasury.

Allocation of DAO portion of project earnings:

**DAO ETH**|**DAO %**|**Protocol %**
:-----:|:-----:|:-----:
0-99|100%|0%
100-199|90%|10%
200-299|80%|20%
300-399|50%|50%
400-499|40%|60%
500+|20%|80%