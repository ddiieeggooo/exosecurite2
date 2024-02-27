Auction.sol prevents from DOS by separating bid and withdraw functions, and prevents from reentrency by setting the refunds to 0 before calling a tx.
