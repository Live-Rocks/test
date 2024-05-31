# Fren Suipport dApp 

Fren Suipport is a platform themed around the Suifrens NFT universe. The primary function of this platform is to facilitate the exchange of labor and assets in the web3 world, offering a variety of features including public tasks, private tasks, charity crowdfunding, and product crowdfunding. Currently, the first phase has implemented the public tasks feature.

Fren Suipport aims to enable individuals without any web3 assets to seamlessly enter the web3 world. Without relying on centralized exchanges, users can earn their first web3 assets directly through activities such as learning, providing labor, and participating in submission competitions.

This project also a learning task module that uses on-chain records to retain all data, ensuring fair distribution of rewards.


<br/>

Web: <https://frensuipport.vercel.app/>
<br/>
Does: <https://aa5961311s-organization.gitbook.io/fren-suipport>
<br/>
Git: <https://github.com/u2789011/suiHackthon>

Powered by Fren Suipport team.
<br/>
<br/>


# User Process

## 1. Publish Task

## 2. Accept Task

## 3. Submit Task Sheet

## 4. Supervisor Reviews Task Sheet

## 5. Executor Receives Reward

<br/>

# Main Sui Object

## 1. Main Task
Defines task fields, task manager, etc. Only those with the publication permission object can modify the task description.

It locks a Fund, which can be any Coin, specified when creating the task.

## 2. Task Sheet
Minted by users when they accept tasks on the front end. Only users with modification rights can change the content.

After completing the task, the record to be submitted is written on the task sheet. Once edited, it can be submitted.

The task sheet will be automatically transferred to the task manager (address specified by the task publisher) by the smart contract.

## 3. Proof of completion(POC)
Once approved, it will be permanently frozen on the chain and cannot be tampered with. The Main Task will record the approved task sheet ID.



