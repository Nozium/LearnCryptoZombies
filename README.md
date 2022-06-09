# LearnCryptoZombies
## Purpose 
This repository is memo for pythonia to start learning cryptoZombies.

## Learning Logs
- day01 : Start learning CryptoZombies
    - chapter 01 - 0X
    - Named as camelCase
    - type of variables
        - uint : Unsigned Integers (alias of uint256)
        - int : signed Integers
        - struct : c-like struct object 
        ~~~
        struct hogehoge{
            string name;
            uint age;
        }
        ~~~
        - array : (NOT as Array varname) `vertype[length] vername;` 
 if length is blank, array without length limit. This object can use similer as Databases. Use Public option, when store public READABLE contract information.(NOT writerble)  
    - Math Operations >> same as Python
    - Functions :function method is near to JS function, BUT function has some modifiler. 
    EX : function functionName(variableType _local_variablename, variableType _local_variablename ){}  
        - private:   
        EX in private : function **_functionName**(variableType _local_variablename, variableType _local_variablename ) **private**{}
        - public : same usecase of private
        - returns : define function has a return or not similer to python -> variableType. ? sample has public modifier but this may not requierment.  
        EX : function functionName() **public returns (returnVariableType)** {**return returnVariableName**}
        - view : retern read only data ? example in chapter page is not full view.  
        EX : function functionName()  **public view returns (returnVariableType)**{ return viewAttr }
        - pure : similer to static function decorater, but this modifiler to only use arguments.  
        EX : function _multiply(uint a, uint b) **private pure** returns (uint) { return a * b; }
    - keccak256 : hash function default in eth.
    - Events : `Events are a way for your contract to communicate that something happened on the blockchain to your app front-end, which can be 'listening' for certain events and take action when they happen. ` >> This is user interaction base event, so mostly not used in python. Python GUI tool may use while loop for detect event, but this event modifier is not required while loop. Hum...  
    [more information](https://solidity-jp.readthedocs.io/ja/latest/contracts.html#events)
    - Frontend : Web3.js (only use)
    

## The Remains Charanges
- hogehoge : foo bar


## References
- [Ethereum](https://ethereum.org/en/developers/docs/)
- [solidity](https://solidity-jp.readthedocs.io/ja/latest/)
