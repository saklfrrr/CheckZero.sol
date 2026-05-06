# CheckZero.sol
CheckZero.sol
pragma solidity ^0.8.20;
contract CheckZero {
    function isZero(uint x) public pure returns(bool) {
        return x == 0;
    }
}
