# Flare
# 📚 Flashcards Smart Contract (Solidity)

A simple, beginner-friendly blockchain project that stores study flashcards **on-chain** using Solidity.  
This repository is perfect for learners who want to understand how smart contracts work, how data is stored on-chain, and how to build small decentralized applications.

---

## 📝 Project Description

The **Flashcards Smart Contract** is a lightweight on-chain storage system designed to help beginners learn Solidity.  
It allows the contract owner (the wallet that deploys the contract) to create flashcards consisting of:

- A **question**
- An **answer**

All flashcards are stored permanently on the blockchain inside a dynamic array.

This project is intentionally simple, readable, and easy to deploy — making it ideal for students, Web3 newcomers, and developers learning smart contract basics.

---

## 🚀 What This Project Does

✔ Stores flashcards directly on the blockchain  
✔ Ensures all data is permanent and publicly viewable  
✔ Allows the owner of the contract to add new flashcards  
✔ Lets anyone read and retrieve flashcards  
✔ Demonstrates core Solidity concepts like:
- Structs  
- Arrays  
- Modifiers  
- Access control  
- Public state variables  
- Basic view functions  

This contract can be later expanded into full DApps such as study tools, quiz apps, or learning platforms.

---

## ⭐ Features

### **🔐 Owner-only Card Creation**
Only the account that deploys the contract can add new flashcards.  
This keeps the dataset consistent and avoids spam.

### **📖 On-Chain Flashcard Storage**
Each flashcard includes:
- `question` (string)  
- `answer` (string)

These live on-chain forever.

### **📊 Retrieve Flashcards Anytime**
Anyone can:
- Get the total number of flashcards (`totalCards`)
- Read any specific flashcard by index (`getCard`)

### **👶 Beginner-Friendly Code**
- No inheritance  
- No external libraries  
- No gas-heavy logic  
- Clean, readable comments  
- Perfect for learning or teaching Solidity basics  

---


```solidity
//paste your code
