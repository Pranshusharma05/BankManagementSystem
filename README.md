# Bank Management System

A JavaScript application demonstrating Object-Oriented Programming (OOP) concepts by simulating a bank account management system.

## 📌 Features
- **Bank Account Creation**: Create accounts with account holder names and opening balances.
- **Deposit & Withdraw**: Deposit funds or withdraw money with validation (e.g., overdraft/insufficient balance checks).
- **Savings Account**: Extend the base account functionality with interest rate support.
- **Account Type Detection**: Polymorphic account identification.

## 🧱 4 Pillars of OOP Demonstrated
- **Encapsulation**: Private field `#balance` ensures balance cannot be modified directly from outside the class.
- **Inheritance**: `SavingBankAccount` extends `BankAccount` using `super()`.
- **Polymorphism**: `getAccountType()` method is overridden in `SavingBankAccount`.
- **Abstraction**: Internal balance manipulation is abstracted away through `deposit()`, `withdraw()`, and `getBalance()` methods.

## 🚀 How to Run

Make sure you have [Node.js](https://nodejs.org/) installed, then run:

```bash
node index.js
```

