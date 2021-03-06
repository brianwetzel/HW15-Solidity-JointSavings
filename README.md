![alt=“”](Execution_Results/JointSavingsAccount.jpeg)


# How to interact with your Joint Savings Smart Contract
Congratultions!  You're Joint Savings Smart Contract has been deployed and is now ready to use.  Here are some instructions with examples to help you learn how to interact with your contract:

<br>


## Set Accounts

Use the `setAccounts` function to define the authorized Ethereum addresses that will be able to withdraw funds from your contract.

<br>

>**EXAMPLE:** Below we used two dummy addresses to show the functinality: <br> <br>
![alt=“”](Execution_Results/1_SetAccounts.png)

<br>

_______________________________

<br>

## Deposit
Use the `deposit` function to send funds to the smart contract.

<br>

> **EXAMPLE:** Below we are sending 1 ether as wei: <br> <br>
> ![alt](Execution_Results/2_Deposit.png)

<br>

*Note: Remembering how to convert ether to wei and vice versa can be challenging. So, you can use a website like [Ethereum Unit Converter](https://eth-converter.com/) to ease doing the conversion.*

<br>

_______________________________

<br>

## Contract Balance
 Use the `contractBalance` function to verify the balance of the smart contract:

<br>

> **EXAMPLE:** Here is our balance after receiving 1 ether as wei: <br> <br>
![alt=“”](Execution_Results/3_Balance.png)

<br>

> **EXAMPLE:** Here is our balance after receiving 10 ether as wei: <br> <br>
![alt=“”](Execution_Results/4_Balance.png)

<br>

> **EXAMPLE:** Here is our balance after receiving 5 ether:  <br><br>
![alt=“”](Execution_Results/5_Balance.png)



<br>

_______________________________

<br>


## Withdraw

Use the `withdraw` function to withdraw funds from the smart contract and deposit into one of the two authorized accounts.

<br>

 > **EXAMPLE:** Withdrawing 5 ether into `accountOne`:  
 <br><br>
![alt=“”](Execution_Results/6_Withdraw.png)
<br> <br>
Use the `contractBalance` function check the smart contrat balance and verify that the funds were withdrawn:
<br> <br>
![alt=“”](Execution_Results/7_Balance.png)


<br><br>


 > **EXAMPLE:** Withdrawing 10 ether into `accountTwo`:
 <br><br>
![alt=“”](Execution_Results/8_Withdraw.png)
<br> <br>
Use the `contractBalance` function check the smart contrat balance and verify that the funds were withdrawn:
<br> <br>
![alt=“”](Execution_Results/9_Balance.png)


<br>

_______________________________

<br>
 
## Last Address to Withdraw
Use the `lastToWithdraw` function to see the address of the last wallet to withdraw.

<br>

 > **EXAMPLE:** The last address to withdraw was accountTwo:
 <br><br>
![alt=“”](Execution_Results/10_LastToWithdraw.png)

<br>

_______________________________

<br>

## Last Amount Withdrawn
Use the `lastWithdrawAmount` function to see the amount of the last withdraw.

<br>

 > **EXAMPLE:** The amount withdrawn was 10 Ether, or 10000000000000000000 Wei:
 <br><br>
![alt=“”](Execution_Results/11_LastWithdrawAmount.png)
<br> <br>

