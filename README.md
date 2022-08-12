// SPDX-License-Identifier: GBL-3.0
 pragma solidity 0.8.2;
 contract func 
 {
     uint x=1;

    //view
    function addYoX(uint y) public view returns (uint )
    { 
        return x+y;
    }

    //pure
    function addIoJ(uint i,  uint j) public pure returns (uint) 
    {
        return i+j;
    }
 }
