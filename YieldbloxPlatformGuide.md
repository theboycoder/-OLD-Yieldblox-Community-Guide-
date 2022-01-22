
<h1 align="center"> Yieldblox Platform Guide - Beta</h1>
<p align="center">Yieldblox Platform Guide will be a work in progress and it will be updated regularly. There will be bugs this is a testnet beta, the developers will be fixing them as they come up. To report bugs or for support join the YieldBlox Discord Server https://discord.com/invite/XQ6YS5usCe. </p>

## Intro
If you're new to DeFi on Stellar or unfamiliar with YieldBlox, Please read the [Community Guide](https://github.com/theboycoder/Yieldblox-Community-Guide-) and the [YieldBlox Docs](https://docs.ybx.script3.io/user-docs/general) before getting started.

- Lending & Borrowing
  - [Lending](https://docs.ybx.script3.io/user-docs/lending-borrowing/lending)
  - [Borrowing](https://docs.ybx.script3.io/user-docs/lending-borrowing/borrowing)
  - [Interest Rates](https://docs.ybx.script3.io/user-docs/lending-borrowing/interest-rates)
  - [Health Factors](https://docs.ybx.script3.io/user-docs/lending-borrowing/health-factors)
  - [Liquidations](https://docs.ybx.script3.io/user-docs/lending-borrowing/liquidations)
  - [Default Protection](https://docs.ybx.script3.io/user-docs/lending-borrowing/default-protection)

- Escrowing
  - [What is Escrowing?](https://docs.ybx.script3.io/user-docs/escrowing)
  
- Governance
  - [How does governance work on YieldBlox?](https://docs.ybx.script3.io/user-docs/governance#how-does-governance-work-on-yieldblox)
 
## Getting Started

After reading the users docs you are ready to get started!

Visit https://www.yieldblox.finance and click on the Launch Testnet button in the right corner to launch the testnet platform

![Untitled-2021-12-22-1013](https://user-images.githubusercontent.com/45983304/150624094-9c3b2fd0-8de0-4ca1-9143-f4d6483cd19b.png)

After launching the Testnet, click on Faucet **before** connecting your wallet to the platform.

![Untitled-2021-12-22-1013 -1](https://user-images.githubusercontent.com/45983304/150624352-088f446c-ce3c-4919-89f6-10c66ee1e2b3.png)

In the Testnet Faucet, Click on the Generate button to create a new Stellar Testnet Account for you to use. Hang tight it can take up to 30 seconds to generate the keys.

![e671fc1f2b8521fbba9840b762453bed](https://user-images.githubusercontent.com/45983304/150624531-db92e7aa-ae31-4fc8-b930-3107f96edb71.png)

After the keys have been generated copy your Secret Key, and import into the supported browser wallet to access YieldBlox! Make sure the wallet you are using is on the Testnet version.

![Untitled-2021-12-22-1013-65](https://user-images.githubusercontent.com/45983304/150624929-dcddb7bc-a466-458b-9b72-af8a4b6949c2.png)

Connect your wallet to login and get access to YieldBlox.

![357f5da5a1d911755d4036e0a8cb7ac6](https://user-images.githubusercontent.com/45983304/150625751-39c071eb-43cd-43cd-9243-c24f5de28a4a.png)

## Using the Platform - Lending
Lenders provide assets to the lending pool and receive interest in return. Borrowers can [borrow](https://docs.ybx.script3.io/user-docs/lending-borrowing/borrowing) these assets by posting [collateral](https://docs.ybx.script3.io/user-docs/lending-borrowing/borrowing#what-is-collateral) and paying interest at loan repayment.

Once you're logged into YieldBlox Dashboard, you can choose from any of the listed assets to lend and borrow in the YieldBlox protocol.

![Untitled-2021-12-22-1013-534534](https://user-images.githubusercontent.com/45983304/150628271-ef11f469-cf20-4e31-884e-f0ecb7986558.png)

Lending is simple, click on the asset you want to lend and enter the amount to deposit along with the collateral from your wallet.

![9a4b3326dcdc411f82e06ef4fe3dcf46](https://user-images.githubusercontent.com/45983304/150628665-c4663447-3883-4bff-b6b7-c7338ccbeaf5.png)

Confirm the Transaction to continue the lending process

![e8e308b6b2e0fda91862c6468cd2857d](https://user-images.githubusercontent.com/45983304/150628704-b133f513-85cd-46a3-8385-5833423617ed.png)

Confirm and sign the transaction with your wallet to finish the lending process.

![4696ef9936a6dfaef5796e96e011b799](https://user-images.githubusercontent.com/45983304/150628775-674a945e-3a34-4ea7-b552-55e2cfc34a2b.png)

Once the process is successfully done, Your transaction will be submitted!

![87ba6e96277247439a684045e72f07e2](https://user-images.githubusercontent.com/45983304/150629406-a57abf7f-3fe9-4d19-b2d7-3e2a456f4860.png)

## Using the Platform - Borrowing

When borrowing, users deposit assets into the lending pool and withdraw assets they wish to borrow from the pool. To repay, the borrower returns the borrowed assets to the lending pool. Then they are allowed to withdraw their collateral if they choose.

Click on the asset you want to borrow and enter the amount to borrow

![Untitled-2021-12-22-1013-borrow](https://user-images.githubusercontent.com/45983304/150629982-0c29a6fb-1096-437e-bf83-99dba9ce89f3.png)


Continue the borrow confirmation after entering the borrow amount for the asset

![144a78ae779fca8aefb7ed6b93caa92b](https://user-images.githubusercontent.com/45983304/150630169-e623568e-2ba7-481a-9b84-6be7d12c8765.png)

Confirm the borrowing asset transaction

![confirm borrow](https://user-images.githubusercontent.com/45983304/150630240-2368fc71-10fc-4b10-8823-3ceb8d3869b8.png)

Confirm and sign the transaction with your wallet to finish the borrowing process.

![6ab317bb9b0d47871a4b73297c118dbc- awd](https://user-images.githubusercontent.com/45983304/150630306-af0261cb-fb2b-4b38-bb93-9a1756b2a4eb.png)

Once the process is successfully done, Your transaction will be submitted!

![87ba6e96277247439a684045e72f07e2](https://user-images.githubusercontent.com/45983304/150630316-62baa55a-7b1a-476a-b885-d311c73c2d53.png)

After borrowing assets, the asset borrowed can be lent back into the protocol. The user must ensure their health factor will be above 1.10 after the loan has been originated. If a user account's health factor falls below 1.00, its positions can be liquidated until its health factor reaches 1.00.

![lending borrowed asset home page](https://user-images.githubusercontent.com/45983304/150630560-7be872aa-61da-453b-9fd2-cd8fcd81133c.png)

The borrowed asset follows the same structure as lending. The user will be able to deposit the asset and lend it to the protocol.

![ETH borrow deposit](https://user-images.githubusercontent.com/45983304/150630816-3c4430d6-1898-499c-a1b4-669bb8cd5545.png)

Confirm the asset deposit

![confirm eth borrow deposit](https://user-images.githubusercontent.com/45983304/150630875-28f6fbd4-8295-4934-9b2a-5e55d78851ee.png)

Sign and confirm the transaction 

![6ab317bb9b0d47871a4b73297c118dbc- awd](https://user-images.githubusercontent.com/45983304/150630948-2a831e8c-c97d-4c3a-879b-f144451ad550.png)

![87ba6e96277247439a684045e72f07e2](https://user-images.githubusercontent.com/45983304/150630941-3ec08af5-0f07-4a37-94c2-412dc97f69b4.png)

## Withdraw and Repay

Lenders can withdraw assets by using YieldBlox's smart contracts to burn the pool tokens they received for lending assets. Doing so will also withdraw all interest the lender has accrued. 

![withdraw](https://user-images.githubusercontent.com/45983304/150631170-735dd13e-a732-41f4-b24d-10668e0c489d.png)

Borrowers repay loans by returning all borrowed assets and accrued interest to the YieldBlox lending pool. After doing so, they can withdraw their collateral deposits if they wish.

![repay](https://user-images.githubusercontent.com/45983304/150631311-d3b8449c-fcc4-4d33-8ed2-315d07e99579.png)
