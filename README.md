# 🍔 YBS Burger & Clicker Game

![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![Windows Forms](https://img.shields.io/badge/Windows%20Forms-0078D6?style=for-the-badge&logo=windows&logoColor=white)

A **C# Windows Forms** desktop application where users earn virtual currency through a 10-second reflex game and use their accumulated balance to customize and purchase burgers.

---

## 🎮 Gameplay & Application Screenshots

### 1. Game Tab (Earning Currency)
When the user enters a username and clicks the **Start** button, a 10-second countdown begins. Each click on the smiley face appearing at random positions on the screen increases the balance by **20 ₺**. Once the timer expires, the username and total earnings are recorded in the **User List** on the right.

<p align="center">
  <img src="oyun-demo.gif" alt="Gameplay Demo" width="750">
</p>

### 2. YBS Burger Tab (Ordering & Checkout)
Users select their profile from the list and customize their order by choosing **patty**, **bun**, and **extra toppings** along with the desired quantity within their available balance to complete the purchase[cite: 1].

<p align="center">
  <img src="ybs-burger.png" alt="YBS Burger Order Screen" width="750">
</p>

---

## ✨ Features

* **Reflex & Scoring System:** 10-second countdown (`Timer`) paired with dynamically positioning target mechanics.
* **User & Balance Management:** Automatic logging of earned balances alongside usernames and profile selection on the checkout screen.
* **Customizable Burger Menu:**
  * **Patty Options:** Single Patty (+20 ₺), Double Patty (+40 ₺), Triple Patty (+75 ₺)[cite: 1]
  * **Bun Options:** Classic (+0 ₺), Whole Wheat (+10 ₺), Brioche (+15 ₺)[cite: 1]
  * **Extra Toppings:** Pastrami (+25 ₺), Onion Rings (+10 ₺), Mushrooms (+8 ₺), Jalapeno (+7 ₺), Cheddar (+12 ₺)[cite: 1]
* **Balance Validation:** Real-time total cost calculation based on selected ingredients and quantity
