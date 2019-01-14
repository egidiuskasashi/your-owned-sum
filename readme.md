# your-owned-sum

## description
This simple solidity exercise shows how to take ownership of a sum operation with 2 addendum.

The user ask the contract to compute the sum of two integers, via mySum method.

Contextually, the user becomes the owner of that operations, via the mapping SumIdOwnedBy, which maps sums array index to the original msg.sender.

A user can submit just one sum operation, so she can own just one sumID.

Every user may read the contract to check which sum is owned by a particular address.

## deployment

the contract may be tested on Ropsten test network, [here](https://ropsten.etherscan.io/address/0x9f2b94ff2ce7a45fd1483818d6e35fd9cfb51034)
