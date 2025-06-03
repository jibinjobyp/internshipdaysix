# Task 6: Create a Strong Password and Evaluate Its Strength

## 🎯 Objective
Understand what makes a password strong and evaluate it using password strength testing tools.

---

## 🛠️ Tools Used for Evaluation
- [Kaspersky Password Checker](https://password.kaspersky.com/)
- [Password Meter](https://passwordmeter.com/)
- [Bitwarden Password Strength Tester](https://bitwarden.com/password-strength/)

---

## 🔤 Sample Passwords Used
1. `jibinjoby`
2. `jibinjobyP`
3. `jibinjoby1234`
4. `jibinjobyP1234@!`

---

## 🧪 Evaluation Results

### 1. `jibinjoby`
- **Kaspersky:**  
  ![image](/screenshots/kas_one.png)
- **Password Meter:**  
  ![image](/screenshots/meter_one.png)
- **Bitwarden:**  
  ![image](/screenshots/bit.one)

---

### 2. `jibinjobyP`
- **Kaspersky:**  
  ![image](/screenshots/kas_two.png)
- **Password Meter:**  
  ![image](/screenshots/meter_two.png)
- **Bitwarden:**  
  ![image](/screenshots/bit_two.png)

---

### 3. `jibinjoby1234`
- **Kaspersky:**  
  ![image](/screenshots/kas_three.png)
- **Password Meter:**  
  ![image](/screenshots/meter_three.png)
- **Bitwarden:**  
  ![image](/screenshots/bit_three.png)

---

### 4. `jibinjobyP1234@!`
- **Kaspersky:**  
  ![image](/screenshots/kas_four.png)
- **Password Meter:**  
  ![image](/screenshots/meter_four.png)
- **Bitwarden:**  
  ![image](/screenshots/bit_four.png)

---

## 📌 Observations & Analysis

| Password              | Strength | Notes |
|-----------------------|----------|--------------------------------------------------|
| `jibinjoby`           | Very Weak | Only lowercase letters; easy to brute-force     |
| `jibinjobyP`          | Weak      | Adds 1 uppercase letter; slightly better        |
| `jibinjoby1234`       | Moderate  | Adds numbers; still guessable                   |
| `jibinjobyP1234@!`    | Strong    | Includes uppercase, lowercase, numbers, symbols |

### 🔎 Summary
- Using only **lowercase letters** makes your password very weak.
- Adding **uppercase letters** slightly improves strength.
- Including **numbers** further strengthens it, but not enough.
- A strong password should be a **mix of lowercase, uppercase, numbers, and symbols**, with sufficient **length** (12+ characters recommended).

---

## 🧠 Common Password Attacks

| Attack Type            | Description                                                    | Prevention |
|------------------------|----------------------------------------------------------------|------------|
| **Brute Force**        | Tries all possible combinations                                | Use long, complex passwords |
| **Dictionary Attack**  | Uses a list of common passwords or words                       | Avoid predictable words |
| **Credential Stuffing**| Uses leaked credentials from other sites                       | Use unique passwords per site |
| **Phishing**           | Tricks user into entering password on a fake site              | Enable 2FA, verify URLs |
| **Keylogging**         | Captures typed keystrokes using malware                        | Use antivirus, avoid unknown downloads |
| **Social Engineering** | Tricks users into revealing passwords verbally or via email    | Never share passwords |
| **Rainbow Table**      | Matches precomputed hashes to password hashes                  | Use salted, strong hashing |
| **MITM (Man-in-the-Middle)** | Intercepts login traffic (often on public Wi-Fi)        | Use HTTPS and VPNs |

---

## ✅ Best Practices for Creating Strong Passwords

- Use **12+ characters** minimum.
- Include **uppercase, lowercase, numbers, and symbols**.
- Avoid using names, dates, or common phrases.
- Use a **password manager** to generate and store passwords.
- Enable **two-factor authentication (2FA)** wherever possible.
- Never reuse passwords across different websites.

---



