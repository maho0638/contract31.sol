# contract31.sol
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.0;

// Base network Web3 practice contract
contract Contract31 {
    uint public version = 1;

    function upgrade() public {
        version += 1;
    }
}
