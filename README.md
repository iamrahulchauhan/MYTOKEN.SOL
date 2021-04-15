# MYTOKEN.SOL
DEPLOY "MYTOKEN.SOL" for first user then deploy it for second user.
Get the token address for user2 approve some amount to swap from the contract deployed for user 1
Repeat the obove for the user 2 taking token address from user 1 this time.
Check allowance of of both smart contracts before moving forward.

# TOKENSWAP.SOL
Now, for any of the obove two user deploy the   "TOKENSWAP.SOL" smart contract for one of the owners.
TOKENSWAP.SOL REQUIRES msg.sender should be one the owners of obove two deployed "mytoken.sol" smart contracts.
