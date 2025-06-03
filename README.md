# 🔐 Create a Strong Password and Evaluate Its Strength

This project demonstrates how to create secure passwords of varying complexity, evaluate them using password strength checkers, and understand how complexity improves security.

---

## 📋 Overview

1. Generate multiple passwords with different levels of complexity.
2. Test each password using online password strength tools.
3. Record feedback and scores.
4. Identify strong password patterns and best practices.
5. Understand common attack methods like brute-force and dictionary attacks.
6. Learn how complexity improves password security.

---

## 🔑 Sample Passwords

| Password                  | Components Used                                |
|---------------------------|-------------------------------------------------|
| `apple123`                | Lowercase, numbers                              |
| `Apple123`                | Uppercase, lowercase, numbers                   |
| `Apple123!`               | Uppercase, lowercase, numbers, symbol           |
| `Ap!2e7K@`                | Uppercase, lowercase, numbers, symbols          |
| `aP9!r$Lz!w2q%`           | Uppercase, lowercase, numbers, symbols          |
| `CorrectHorseBatteryStaple` | Long passphrase                              |
| `C0mpl3x!tY@2025*`        | Strong, mixed character types                   |

---

## 🧪 Evaluation Results

Password strength was tested using tools like:

- [passwordstrength.com](https://www.passwordstrength.com/)
- [Kaspersky Password Checker](https://password.kaspersky.com/)
- [NordPass Strength Tool](https://nordpass.com/password-strength-checker/)

### 📊 Summary

| Password               | Score (Out of 5) | Feedback                                           |
|------------------------|------------------|----------------------------------------------------|
| `apple123`             | 1/5              | Too common, lacks complexity                      |
| `Apple123`             | 2/5              | Still predictable                                 |
| `Apple123!`            | 3/5              | Better, but short                                  |
| `Ap!2e7K@`             | 4/5              | Strong, could benefit from more length            |
| `aP9!r$Lz!w2q%`        | 5/5              | Excellent, highly secure                          |
| `CorrectHorseBatteryStaple` | 4/5       | Long but uses common words                        |
| `C0mpl3x!tY@2025*`     | 5/5              | Highly complex and secure                         |

---

## ✅ Best Practices

- Use **12+ characters**.
- Mix **uppercase, lowercase, numbers, and special characters**.
- Avoid **personal info** and **dictionary words**.
- Use a **password manager** to generate and store passwords.
- **Update passwords** regularly.

---

## ⚠️ Common Password Attacks

| Attack Type        | Description                                           |
|--------------------|-------------------------------------------------------|
| **Brute Force**    | Tries all combinations                                |
| **Dictionary**     | Uses wordlists to guess common passwords              |
| **Credential Stuffing** | Uses leaked credentials across multiple sites   |
| **Phishing**       | Tricks users into revealing passwords                 |
| **Keylogging**     | Captures keystrokes                                   |

---

## 🔒 Complexity vs Security

- Each additional character **exponentially increases security**.
- Complex passwords resist **brute-force** and **dictionary attacks**.
- **Randomness and length** are key to strong protection.

---

## 📁 Included Files

- `Password_Strength_Report.pdf` – Full report with analysis and a visual chart.
- `README.md` – Project summary and guide.

---

## 🛠 Tools Used

- Python (`fpdf`, `matplotlib`)
- Online password checkers
- Markdown for documentation

---

## 📎 License

This project is licensed under the MIT License.

