### Name: Nick Leete
### Email: nplmh5@umsystem.edu
### Course/Section: CS 476-0001

## Notes:
I did not do the MetaMask for this assignment as I was unable to figure out what we were being asked to do with it.

## Reflection:
1. I enforced access control for the Admin, Minter, and Pauser roles in the contract by throwing errors if the account attempting the operation did not have the required role.
2. Batch airdrop saved 42.35% gas compared to individual transfers, because consolidating transactions into a single batch charges only a fixed cost + (variable cost * transaction), vs (fixed cost + variable cost) * transaction.
3. The only issue I ran into was with MetaMask, as I have no idea what the assignment is asking me to do with it.