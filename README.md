# Token creation
This project is called "Initiate a Token", which highlights its functionality to create tokens in Solidity using state variables and then perform various actions on those tokens, such as creating and destroying them.

# Description
This Solid Initiative contains a smart contract designed to perform various functions. The contract includes information such as the symbol name, abbreviation and total amount. It matches each sender's account address with their account balance. The project has a punch function, which not only increases the total supply of tokens, but also increases the sender's account by a certain amount. On the other hand, there is a burning feature that reduces the total supply of tokens and the sender's account balance by a certain amount if the sender's account has sufficient funds. If you want to develop a similar project, you need to implement the following functionality: Your contract contains public variables that contain information about your coin (name, acronym, total supply). In addition, there is a mapping of addresses to account balances (address => uint). The project includes a punch function that accepts an address and a value, which then increments the total supply and increments the account balance of the specified address by that value. The project also includes a burning function that works against mint functions by destroying tokens.This function also accepts an address and a value, reducing the bid and account balance of the specified address by that value. It then subtracts the value of the shipping and address total balance. Finally, your burn function should have conditions that ensure the account balance is greater than or equal to the amount burned.
# Getting started
## Installing
You can download the program by clicking on the code button and then you will see the option to download it as a zip file. If you want to use it in your project, you can click on the fork repository and it will be saved to git hub for further editing.
## Executing Program
Run the program by pasting the downloaded file into RemixIDE. Then compile the code and deploy it. after installation, add your account address and the value by which you want to increase the value of the mint function in the section. Click on the mint to see the total. the offer is added by clicking the end offer button. Just like you can burn with your token, you can change things like the token's name, abbreviation, and total inventory.

# Authors
Sagar Gupta
# License
This project is licensed under the MIT License - see LICENSE.md for details.
