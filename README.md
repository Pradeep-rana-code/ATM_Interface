# 💳 ATM Simulation Program – Java

A simple Java console application that simulates basic **ATM operations** such as **money withdrawal** and **balance inquiry**. The program handles real-life scenarios like **insufficient balance** and displays appropriate messages.

---

## 🧠 Features

- ✅ Withdraw money from your account  
- 👀 Check your current bank balance  
- 🚫 Handle insufficient balance during withdrawal  
- 💬 Interactive console-based user interface  

---

## 🔧 How It Works

- The user is prompted to select an option:
  1. **Withdraw money**
  2. **Check account balance**
- If the user chooses to withdraw money:
  - They enter the amount
  - The program checks if the balance is sufficient
  - If **yes**, the amount is withdrawn and new balance is displayed
  - If **no**, an **"Insufficient Balance"** message is printed on the screen
- If the user chooses to check balance, the current amount in the account is displayed

---

## 🛠️ Technologies Used

- Java (Core)  
- Scanner class for input  
- Conditional statements (`if`, `else`)  
- Looping and user input handling  

---

## ▶️ How to Run

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Pradeep-rana-code/ATMSimulation.git
   cd ATMSimulation
   ```

2. **Compile and run the Java file:**
   ```bash
   javac ATM.java
   java ATM
   ```

3. **Follow the on-screen instructions to use ATM services.**

---

## 📸 Sample Output

```
Welcome to Java ATM
Please choose an option:
1. Withdraw Money
2. Check Balance

> 1
Enter amount to withdraw: 5000
Insufficient Balance!

> 2
Your current balance is: ₹2000
```

---

## 👨‍💻 Author

**Pradeep Rana**  
[GitHub](https://github.com/Pradeep-rana-code)
