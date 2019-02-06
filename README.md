# Intro programme to solidity
here is the intro programme about solidity language which is somewhat same as c language
pragma solidity ^0.4.24;

contract Mycontract {
    string value;
    
    constructor() public {
        value = "myvalue";
    }
    
    function get() public view returns(string) {
        return value;
    }
    
    function set(string _value) public {
        value = _value;// here underscore "_" used to differentiate arguement and variable
    }
}

// above code for mycontract programme 


which having just a small code get and set functions 
both functions which we defined above are public any one can use that function.
