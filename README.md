# SenderBalance.sol
SenderBalance.sol
pragma solidity ^0.8.20;
contract SenderBalance {
    function myBalance() public view returns(uint){
        return msg.sender.balance;
    }
}
