---
layout: post
title: How to Create Your First Cardano Wallet
permalink: /docs/how-to-create-your-first-cardano-wallet
series:
    name: Cardano Foundational Concepts
    description: Fundamental Cardano concepts that everyone should know.
---

So you’ve just decided to get into this hot new crypto craze, but what’s the best way to get started? And what are the safest things you can do to make sure you don’t put your money at risk?

If you are new to Cardano and to cryptocurrencies in general, be sure to check out our What is Cardano? article here to understand all of the ins and outs of the ecosystem and how it all connects together.

This tutorial is the first of a three part series, this article will go through the creation of your first wallet either on Yoroi or Daedalus. The second article will discuss how to deposit Ada into your Wallet and a comprehensive comparison between some of the most popular exchanges. The third article will walk through what delegation is and how to delegate your wallet to a particular stake pool, support the community, and make a little return on your Ada while it sits in your wallet.

## Selecting Your Cardano Wallet "Brand"

A “wallet” is essentially your private bank account in the crypto space. It comes with a private key that you must keep secret or else others will have access to your funds. Different cryptocurrencies have different wallets, so if you have already created a wallet for Bitcoin or Ethereum, you will need to create a wallet for Cardano as well.

The first step to creating a wallet is deciding which wallet “brand” you want to go with. There are two main wallets in the Cardano ecosystem: Daedalus and Yoroi. This table breaks down the main differences between these two:

| | Daedalus      | Yoroi |
|----| ----------- | ----------- |
| Version | 3.3.2      | 4.1.2       |
| Download | Standalone Download | Chrome/Firefox Extension, Android/iOS App |
| Android/iOS App | No | Yes |
| Multiple Wallet Support | Yes | Yes |
| Staking Delegation Support | Yes | Yes |
| Indvidual Stake Pool Information | Saturation, Rank, Live Stake, Pool Margin, Pledge, Cost per epoch, Produced blocks, Potential rewards | Score, 30d ROA, Share/Pool Size, Costs, Average Cost, Pledge, Number of Produced Blocks |
| Wallet Total Cumulative Rewards | Yes | Yes |
| Time to next epoch | Yes | Yes (shows next Epoch start date) |
| Next Two Epochs Delegation Information | Yes | Yes (next 3) |
| Voting Support | Yes With Catalyst App | Yes With Catalyst App |
| Native Asset Support | Coming Soon | Coming Soon |
| Send Native Assets | Yes | Yes |
| Support for Hardware Wallets | Yes | No |
| Payment Memos | No | Yes (Stored only on your Yoroi account for personal use, won’t sync to other accounts) |
| Address Book | No | Yes (Stored with your account) |


## Getting Started with Yoroi

First download the extension from the Chrome Web Store, or Firefox, Android, or iOS if you would prefer. This tutorial will show the process through the Chrome Extension though the process should be similar for the other locations.

Click Add to Chrome
![Tutorial Image](/docs/001-how-to-download-wallet/img/image19.png)

Clicking on the extension in the extensions bar will bring you to the start up screen. Select your desired language and continue.
![Tutorial Image](/docs/001-how-to-download-wallet/img/image22.png)

Read the riveting terms of use, accept, and continue.
![Tutorial Image](/docs/001-how-to-download-wallet/img/image9.png)

If this is your first time, choose simple for the level of complexity
![Tutorial Image](/docs/001-how-to-download-wallet/img/image10.png)

We recommend allowing payment urls since they can be extremely handy and lessen the likelihood of getting an address typed in wrong. Then click to allow Yoroi to open cardano+web links in Chrome.
![Tutorial Image](/docs/001-how-to-download-wallet/img/image2.png)

At this point we are ready. If you have made a wallet previously you can restore it here, if this is your first time, we’ll walk through creating a new wallet on Yoroi. Click the center button to create a wallet
![Tutorial Image](/docs/001-how-to-download-wallet/img/image12.png)

Select Cardano
![Tutorial Image](/docs/001-how-to-download-wallet/img/image15.png)

Select Create Wallet
![Tutorial Image](/docs/001-how-to-download-wallet/img/image1.png)

Give your wallet a name, this can be whatever you would like to help you keep track of what this wallet is for versus future wallets you may make. Additionally create a spending password so that if someone else gains access to your computer they won’t be able to spend your Ada without the spending password. Note that this name and password are only known within Yoroi, these are not stored or accessed on the blockchain. If someone gains access to your wallet’s secret hash they can still obtain your Ada regardless of your spending password.
![Tutorial Image](/docs/001-how-to-download-wallet/img/image25.png)

Your recovery phrase is the most important part of your wallet! Make sure not to show anyone your recovery phrase unless you want them to have unmoderated access to your funds! We at Slate Pool recommend not having any digital record of your recovery phrase ie don’t save it in a google doc or your passwords sheet because someone could gain access to it, or if you happen to have a virus on your computer which is running a keylogger hackers could gain access to it. Better is to only write it down on a piece of paper and keep that paper in your safe or with your other secure records. The only thing better than physically writing your key down is using a hardware wallet to store your key, we will talk about hardware wallets and how to use them in another article.
![Tutorial Image](/docs/001-how-to-download-wallet/img/image11.png)

Write down your secret phrase, and then Yoroi will confirm you have written it down correctly. ONCE YOU LEAVE THIS SCREEN, YOU CAN NEVER RECEIVE YOUR WALLET PHRASE AGAIN
![Tutorial Image](/docs/001-how-to-download-wallet/img/image13.png)
(Wallet phrase shown here is just as an example)

Congrats now you have just created your first Cardano wallet!
![Tutorial Image](/docs/001-how-to-download-wallet/img/image18.png)

## A Quick Tour of Yoroi
Whenever you want to launch your Yoroi wallet, click the icon in your list of Chrome extensions.
When you first load up Yoroi you will see your main dashboard as below:
![Tutorial Image](/docs/001-how-to-download-wallet/img/image7.png)

Here you can see quick details about the status of your wallet, upcoming potential rewards, and other important details (we’ll learn how to add funds to our new wallet in the next tutorial). You can have multiple Ada wallets connected in your Yoroi account by clicking “Back to my wallets” at the top and following a similar set up as before to add an additional wallet. Additional wallets are helpful if you would like to keep separate wallets with funds that are to be used for different purposes, if you have a wallet you would like to share with a partner, a wallet for particular businesses--essentially anything you’d normally open a traditional checking or savings account for.

At the top is the main control bar for all the things you’d need to do with your wallet:
![Tutorial Image](/docs/001-how-to-download-wallet/img/image14.png)

The Transactions pane shows the list of all most recent transactions with your wallet. Once again this transaction history is stored on the blockchain, so if you use your restore phrase to open up your wallet again later this transaction history will all be maintained.

Next if you would like to send Ada to another wallet, you may do so under the send tab:
![Tutorial Image](/docs/001-how-to-download-wallet/img/image16.png)

Note: You will NEVER use your secret phrase to send or receive money! NEVER give out your secret phrase, if someone asks you for it they are trying to scam you!

In order to receive money you will give a public hash of your key to the person you would like to receive money from:
![Tutorial Image](/docs/001-how-to-download-wallet/img/image21.png)

You can get a new generated hash from this page, use the copy button to copy the phrase, or scan the QR Code to obtain the phrase. Other users can enter this phrase on their wallet to send you money.

The last two tabs are for catalyst voting, and for delegating your wallet to a stake pool. We will have a separate article that goes into all the details about how to delegate and important points to consider when delegating to a pool.
![Tutorial Image](/docs/001-how-to-download-wallet/img/image27.png)

## Getting Started with Daedalus

Download the installer at [https://daedaluswallet.io/en/download/](https://daedaluswallet.io/en/download/) Make sure you are at the correct webpage for the download!
![Tutorial Image](/docs/001-how-to-download-wallet/img/image24.png)

For simplicity in this tutorial we will skip verifying the download with a hash signature, however for best practice this is recommended and can be done by following the tutorial on the daedalus website.

Run the installer, when it finishes, launch Daedalus Mainnet. The installer most likely created a desktop icon, or you can search for Daedalus Mainnet in your programs list.

The first time you start up Daedalus you will be prompted to enter your desired date and time formatting.
![Tutorial Image](/docs/001-how-to-download-wallet/img/image29.png)

Read and agree to the riveting terms of service:
![Tutorial Image](/docs/001-how-to-download-wallet/img/image28.png)

Next you should see the main screen where you will be able to either create a new Cardano Wallet, or you may add an existing wallet that you created previously via the secure key phrase. The first time you run Daedalus it may take some time for it to sync up with the mainnet. This is fine and normal, just let daedalus do it’s thing in the background. Daedalus will resume where it was previously if you turn it off in the middle of syncing.

Click the button to create a new Cardano wallet.
![Tutorial Image](/docs/001-how-to-download-wallet/img/image3.png)

Enter a name for your wallet that will help you remember what this wallet is for. Additionally add a spending password so that if someone gains access to your computer they will be unable to spend any of your Ada in the wallet. The wallet name and spending password are for your convenience, and are not stored on Cardano blockchain in any way. If someone gains access to your wallet’s secret key phrase (which we will see shortly) they will have complete access to your wallet funds regardless of whether or not they know your spending password.

Click Create Shelley Wallet
![Tutorial Image](/docs/001-how-to-download-wallet/img/image23.png)

Click to confirm that you understand the importance of keeping your recovery phrase absolutely secure, and then click to continue.
![Tutorial Image](/docs/001-how-to-download-wallet/img/image20.png)

Write down the list of 24 words which is your wallet’s recovery phrase. This phrase will allow you to gain access to the wallet again, or to add the wallet to a new computer in the future. IF SOMEONE GAINS ACCESS TO YOUR RECOVERY PHRASE THEY GAIN ACCESS TO YOUR FUNDS. We at Slate Pool recommend writing down your recovery phrase on paper and keeping the paper in your safe with your other secure records, this is because having any form of digital copy of your key can be very dangerous if someone gains access to your google account or if there happens to be a malicious keylogger on your system. For even better security you may wish to use a hardware wallet, to store your recovery phrases, that is beyond the scope of this tutorial but we will have another tutorial that discusses how to use hardware wallets. Additionally, DO NOT LOSE YOUR PHRASE, YOU WILL LOSE ALL ACCESS TO YOUR FUNDS.
![Tutorial Image](/docs/001-how-to-download-wallet/img/image4.png)

Once you have written down your recovery phrase, click to continue

Retype your recovery phrase to confirm you have written it down correctly. Accept that you understand how important it is to keep your phrase secure and not lose it, then click to continue.
![Tutorial Image](/docs/001-how-to-download-wallet/img/image17.png)

Congrats! You’ve just created your new wallet, let the wallet sync with the blockchain and you will be all good to go. It may take some time for your new wallet to sync with the blockchain depending on your computer and internet connection. It is fine if you need to close daedalus and resume the process where it left off later.
![Tutorial Image](/docs/001-how-to-download-wallet/img/image5.png)

## A Quick Tour of Daedalus
On the main screen there is a lot that you can do once opening up Daedalus.
![Tutorial Image](/docs/001-how-to-download-wallet/img/image8.png)

From the top bar you have quick access to the selected wallet’s info including sending and receiving funds to that wallet and seeing the complete list of transactions associated with that wallet.
![Tutorial Image](/docs/001-how-to-download-wallet/img/image26.png)

On the left you have access to all of your wallets, the delegation center, testnet rewards (if this is your first wallet you don’t need to worry about that one), catalyst voting, and theme settings.
![Tutorial Image](/docs/001-how-to-download-wallet/img/image6.png)

We’ll go through the details of how to delegate in another article, but on the delegation page you can see all of the various details for how to delegate your wallet to a stake pool.
![Tutorial Image](/docs/001-how-to-download-wallet/img/image30.png)

We hope this article has helped you to jump into the new and vibrant world of cryptocurrencies! If this article has helped you, please share Slate Pool resources with your friends and please consider delegating to Slate Pool so that we can continue to provide articles and resources to the community.
