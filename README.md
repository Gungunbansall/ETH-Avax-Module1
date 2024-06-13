# ETH-AVAX-Module1
Error Handling tehniques

 Creating a smart contract that implements the require(), assert() and revert() statements.

## Description
 There are three methods that constitute the error-handling process in Solidity:

require(): 
Used to validate certain conditions before further execution of a function. It takes two parameters as an input.
However, if the condition fails, then the function execution is terminated and the message (the second parameter) is displayed in the logs. The second parameter, however, is optional. require() will work even if you pass only parameter, that is, the condition to be checked. The require() statement is defined as follows:
require(<condition to be validated> , <message to be displayed if the condition fails>);



assert(): The assert function, like require, is a convenience function that checks for conditions. If a condition fails, then the function execution is terminated with an error message.
assert(<condition to be checked/validated>);

revert(): 
Can be used to flag an error and revert the current call. You can also provide a message containing details about the error, and the message will be passed back to the caller. However, the message, like in require(), is an optional parameter. revert() causes the EVM to revert all the changes made to the state, and things return to the initial state or the state before the function call was made.
The reason for reverting is that there is no safe way to continue execution because something unexpected happened. This is important as it helps in saving gas.





### Installing
Go to https://remix.ethereum.org/#lang=en&optimize=false&runs=200&evmVersion=null&version=soljson-v0.8.18+commit.87f61d96.js
And start writing the code 


### Executing program

First Write the code  once you have completed the code 
Compile it and check if there is any error or not if present resolve the error or you can take help from my code too .
After Compilation Deploy it  and pass the values in function 
Check Each Funtion's  output .

## Authors

Gungun
gungunbansal2604@gmail.com


## License

This project is licensed under the MIT License - see the LICENSE.md file for details
