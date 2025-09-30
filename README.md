# CyberIntern-Task6

#  Task 6: Create a Strong Password and Evaluate Its Strength

##  Objective
The goal of this task is to **understand password strength**, explore how complexity impacts security, and learn best practices to protect against common password attacks. By creating multiple passwords and testing them with online tools, we analyze the weaknesses of weak passwords and identify the characteristics of strong ones.  

---

## 🛠 Tools Used
- **[PasswordMeter.com](https://www.passwordmeter.com/)** – Used to test password strength and get detailed feedback.    

---

##  Password Testing & Evaluation

We created multiple sample passwords with varying complexity levels and tested them using the strength checker.  

| Password Example | Strength Score | Feedback (from tool) | Screenshot |
|------------------|----------------|-----------------------|------------|
| `12345`   | 4% (Very Weak)     | Too short, dictionary word, lacks symbols/numbers. Easy to crack via dictionary attack. | <img width="1919" height="976" alt="Screenshot 2025-09-30 115844" src="https://github.com/user-attachments/assets/917d3f5c-afcd-4f2c-9b39-ebb2a8f59187" />
 |
| `Password!23`    | 45% (Fair)     | Mixed case + numbers, but still predictable and common pattern. Vulnerable to brute force/dictionary. | ![Screenshot2](screenshots/screen2.png) |
| `Cyb3r$Ec@rity!`    | 80% (Strong)   | Good mix of letters, numbers, symbols. More resistant to brute force, but pattern “P@ssw0rd” is commonly used. | ![Screenshot3](screenshots/screen3.png) |
| `!Secure_The#Future@2025` | 95% (Very Strong) | Long length, mix of characters, randomness. Difficult to guess and highly resistant to brute force/dictionary attacks. | ![Screenshot4](screenshots/screen4.png) |

---

##  Detailed Observations
1. **Length is the most critical factor** – Longer passwords (12–16+ characters) are significantly stronger than shorter ones.  
2. **Character diversity** matters – Using uppercase, lowercase, numbers, and symbols increases entropy.  
3. **Passphrases outperform random short strings** – A memorable but long passphrase is harder to crack and easier to recall.  
4. **Predictable patterns reduce strength** – Even if symbols/numbers are used, predictable patterns like `P@ssw0rd` are weak.  
5. **Feedback from tools helps identify weaknesses** – Strength checkers highlight missing elements like length, variety, or unpredictability.  

---

##  Research Findings

###  Common Password Attacks
1. **Brute Force Attack**  
   - Tries all possible combinations until the correct password is found.  
   - Longer and more complex passwords exponentially increase time required.  

2. **Dictionary Attack**  
   - Uses lists of common words/phrases.  
   - Any password based on common words (e.g., "password", "qwerty") is easily cracked.  

3. **Rainbow Table Attack**  
   - Uses precomputed hash values to quickly match passwords.  
   - Countermeasure: use **salting** with password hashes.  

4. **Credential Stuffing**  
   - Attackers reuse leaked credentials from one service to access another.  
   - Countermeasure: avoid reusing passwords across accounts.  

---

###  Password Length Matters
- Each additional character increases the number of possible combinations.  
- Example:  
  - 6 characters (lowercase only) = 26⁶ ≈ 308 million possibilities  
  - 12 characters (mixed case + symbols) = 94¹² ≈ 4.7 × 10²³ possibilities  
- Brute forcing a 12+ character random password would take centuries.  

---

###  Multi-Factor Authentication (MFA)
- Adds an extra layer of protection beyond passwords (e.g., OTP, biometrics).  
- Even if a password is stolen, attackers cannot log in without the second factor.  

---

###  Role of Password Managers
- Generate random, complex passwords without needing to memorize them.  
- Store credentials securely in an encrypted vault.  
- Help avoid reusing passwords across multiple platforms.  

---

###  Passphrases
- A passphrase is a sequence of random words (e.g., `Horse-Battery-Staple!2025`).  
- Easy to remember but extremely strong due to length and randomness.  

---

##  Best Practices for Strong Passwords
1. Use **at least 12–16 characters**.  
2. Mix **uppercase, lowercase, numbers, and symbols**.  
3. Avoid dictionary words, personal info (DOB, names, phone numbers).  
4. Prefer **passphrases** over short complex words.  
5. Enable **MFA** on all critical accounts.  
6. Use a **password manager** to generate and store credentials.  
7. Never reuse the same password across multiple platforms.  



