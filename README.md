# 🔐 Task 6: Password Strength Evaluation

## 📅 Date
July 1, 2025

## 🎯 Objective
To understand what makes a password strong by testing different passwords using a password strength estimation tool.

---

## 🧪 Process

I used an online password testing site that implements the `zxcvbn` estimator to test how different combinations of characters affect password strength.

### 🔹 Test 1
- **Password Used**: A basic word with no numbers or special characters  
- **Result**: Very weak  
- **Crack Time**: Less than 1 second  
- **Observation**: Lacked complexity, extremely guessable.

---

### 🔹 Test 2
- **Password Used**: Same base with added numbers  
- **Result**: Weak  
- **Crack Time**: Approximately 11 minutes  
- **Observation**: Some improvement due to added digits, but still predictable.

---

### 🔹 Test 3
- **Password Used**: Mix of uppercase, lowercase, numbers, and special characters  
- **Result**: Strong  
- **Crack Time**: Estimated 4 months  
- **Observation**: Major increase in strength due to complexity and character variety.

---

## 🧠 Insights

- Passwords with just letters are extremely easy to crack.
- Adding numbers helps, but still isn't very secure.
- Combining uppercase letters, symbols, and longer length significantly increases security.
- Password strength tools like `zxcvbn` give a better understanding than just relying on arbitrary rules.

---
