---
tags:
  - Proposals
  - Rev0
proposal-status:
  - Passed
proposal-type:
  - Treasury
  - Other
proposal-author:
  - lewwwk.eth
proposal-url: https://snapshot.org/#/superbenefit.eth/proposal/QmPj8MMEtqyKmPTZMJAMhfJGDRKmPHtdDybuBKhfr6VQyf
---
# SBP1: [Treasury] Authority to convert and manage balance of stables

## Summary
Grant the Treasury Squad the authority to convert up to 50% of ETH received into stable coins using the SuperBenefit hot wallet.

## Background
In order to pay out expenses and bounties in USDC or other stablecoins, treasury will need to convert ETH in to stablecoins from time to time. Performing token swaps using a multi-sig is difficult as the required numbers of signers need to be available at the same time in order to execute the swap with minimal slippage. In order to avoid this situation, it would be useful to transfer assets from the multi-sig to the SuperBenefit hot wallet to perform the swap and then send the stables back to the multi-sig for disbursement. Further, to avoid doing swaps for every stablecoin disbursement it would be helpful to maintain a balance of stables in the treasury to meet future anticipated needs of the DAO.

## Proposal
This a proposal to grant the Treasury Squad the authority convert and manage a balance of stablecoins in the SuperBenefit Treasury. The parameters of that authority are:
1. The Treasury Squad can convert up to 50% of ETH contributions received by SuperBenefit
2. The Treasury Squad can manage and swap existing balances of stable coins as desired in order to serve the needs and interests of the DAO
3. The Treasury Squad can initiate multi-sig transactions to move ETH (subject to 1 above) or stables to the SuperBenefit Hot Wallet ```0x9C3e186d24432f07847460aFa741f98a039AD57d``` (or other hardware wallet controlled by the Treasury Squad Lead)
4. Upon completion of the transaction,  Treasury Squad will promptly perform desired swap(s)
5. Upon completion of the desired swap(s), Treasury Squad will promptly send the resulting tokens to the SuperBenefit multi-sig ```0x731c837121C15e1e7e3cfc0E2588f4d0B35FdD48```