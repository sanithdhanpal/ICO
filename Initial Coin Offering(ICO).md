# PART I

The present ICO's are not sophisticated as they should be. But there are some vey good ICO's which are doing better.
Currently there are many ICO's and each of them differ on the basis on their simplicity, security provided by them etc.
There are various concepts such as overflows, address attacking, double-spending and the differences between ERC20 and ERC23 which we need to consider while creating an ICO.

# PART II

### SafeMath.sol
With the help of SafeMath.sol library we can solve attacks like "overflows". SafeMath doesn't come under any ERC standard but it is useful in any token. It enhances the ordinary usage of arithmetic operators like *+, -, *, /, %** with the help of **assert** to check whether the statement is **true** or **false**.

### ERC20 Basic.sol

It is a basic function that we can add in any token. It consists of:
- TotalSupplt method: specifies the number of tokens present
- balanceOf method: gives the balance present in a specific address
- transfer method: sends amount to a specific address
- transfer event: tells network that the transfer of tokens is executed

Tokens with enhanced qualitits comes regularly into the market. They include more security, advanced from previous standards and are useful when compared to before standards.
But all of them operate in a same way.

### ERC@.sol

Inherits **ERC@Basic**.
Allowance, transferFrom, approve are used as to authorize some sort of sub-contracts, or sub-addresses to spent some of the tokens on our behalf which is used for some advanced wallets.

### BasicToken.sol

With the help of **Payloadsize** the token standards increases and it can now withstand certain attacks.

# PART III

Here we need to specify our address which the users use to send their ether to buy our coins.
Here we need to set the price, so that for one ether the users can get a particular number of coins. let's say 1 ether = 500 coins.
So when the users transfer 1 ether to our account we need to transfer 500 coins to the users account.


                
                
                                