# 🍔 YBS Burger & Clicker Game

![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![Windows Forms](https://img.shields.io/badge/Windows%20Forms-0078D6?style=for-the-badge&logo=windows&logoColor=white)

A **C# Windows Forms** desktop application where users earn virtual currency through a 10-second reflex clicker game and spend their earned balance to customize and purchase burgers.

---

## 🎮 Application Previews & Gameplay

### 1. Game Tab (Currency Generation)
Once the user enters a username and clicks the **Start** button, a 10-second countdown timer begins. Each click on the randomly repositioning smiley target increases the balance by **20 ₺**. When the timer expires, the username and total earnings are automatically recorded in the **User List** on the right.

<p align="center">
  <img src="oyun-demo.gif" alt="Gameplay Demo" width="750">
</p>

### 2. YBS Burger Tab (Order & Checkout)
Users select their profile from the dropdown list and customize their burger by choosing **patty**, **bun**, and **extra toppings** within their available balance, specify the quantity, and complete the checkout.

<p align="center">
  <img src="ybs-burger.png" alt="YBS Burger Order Screen" width="750">
</p>

---

## ✨ Features

* **Reflex & Scoring Engine:** 10-second countdown timer (`Timer`) paired with dynamically randomized target positioning.
* **User & Balance Persistence:** Automatic logging of end-of-round scores with usernames and seamless profile selection in the order tab.
* **Customizable Burger Builder:**
  * **Patty Options:** Single Patty (+20 ₺), Double Patty (+40 ₺), Triple Patty (+75 ₺)
  * **Bun Options:** Classic (+0 ₺), Whole Wheat (+10 ₺), Brioche (+15 ₺)
  * **Extra Toppings:** Pastrami (+25 ₺), Onion Rings (+10 ₺), Mushrooms (+8 ₺), Jalapeño (+7 ₺), Cheddar (+12 ₺)
* **Balance Validation:** Real-time total cost calculation based on selected ingredients and quantity, validated against the user's current funds.

---

## 🛠️ Tech Stack

* **Language:** C#
* **UI Framework:** Windows Forms (WinForms)
* **IDE:** Visual Studio
