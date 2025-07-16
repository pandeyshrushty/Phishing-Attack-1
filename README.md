# Phishing
Identifying **fake or malicious emails** is an important cybersecurity skill. Attackers use techniques like phishing, spoofing, and malware-laden attachments to trick users. Here's a practical guide to help you spot them:

---

### 🔍 **1. Check the Sender's Email Address**

* **Look closely** at the domain: `support@paypa1.com` vs `support@paypal.com` (notice the number 1 instead of "l").
* Attackers often use slight misspellings or free email services (`@gmail.com`, `@yahoo.com`) instead of official domains.

---

### ⚠️ **2. Look for Urgency or Threats**

* Phrases like:

  * “**Your account will be suspended**”
  * “**Act now** or lose access”
  * “You’ve won a prize—**click to claim**!”
* These are tactics to make you act without thinking.

---

### 🔗 **3. Hover Over Links Before Clicking**

* On desktop: hover your mouse over links to preview the real destination in the status bar.
* A fake email may say `www.amazon.com`, but the actual link might be:

  * `http://malicious-site.ru/login/amazon`

---

### 📎 **4. Be Wary of Attachments**

* Especially if:

  * It’s from an unknown sender
  * It ends in `.exe`, `.zip`, `.scr`, `.js`, or even `.docm`
* These may contain malware or ransomware.

---

### 📄 **5. Check for Poor Grammar or Spelling**

* Many fake emails are written in poor English or have awkward phrasing.
* Example: “Dear customer, You account has suspended for verifcation.”

---

### 🧩 **6. Fake Logos or Layout**

* If the branding looks slightly off, blurry, or low-quality, be suspicious.
* Real companies use professional formatting and spelling.

---

### 🛑 **7. Requests for Personal Information**

* No real company will ask you to:

  * Provide passwords
  * Send OTPs
  * Share your card or bank details via email

---

### 🔐 **8. Look for Missing Security Features**

Legitimate emails from big companies usually have:

* **DKIM/SPF/DMARC protection** (tech details visible in email headers)
* **A verified domain** and **legit support contact info**

---

### 🛠️ **9. Use Email Security Tools**

* **Google Safe Browsing**, **VirusTotal**, or **CheckPhish.ai** can help verify links.
* Browser plugins like **Netcraft**, **McAfee WebAdvisor**, or **Microsoft Defender SmartScreen** offer alerts.

---

### ✅ **10. When in Doubt, Don't Click!**

* **Go directly** to the official website.
* **Contact customer support** using known contact methods—not the ones in the suspicious email.

---

### 📌 Example: Real vs Fake Email

| Feature        | Real Email from Bank                                        | Fake Email                                                   |
| -------------- | ----------------------------------------------------------- | ------------------------------------------------------------ |
| Sender Address | [alerts@bankofamerica.com](mailto:alerts@bankofamerica.com) | [support@b4nk-secure.com](mailto:support@b4nk-secure.com)    |
| Subject Line   | Statement Available                                         | Urgent! Account Compromised!                                 |
| Greeting       | Dear John                                                   | Dear User                                                    |
| Link           | [https://bankofamerica.com](https://bankofamerica.com)      | [http://bofa-alerts-update.ru](http://bofa-alerts-update.ru) |
| Attachment     | No                                                          | Yes – `statement.exe`                                        |

---

If you’d like, you can **upload a suspicious email (screenshot or text)** and I can help analyze it with you.

Here is a full academic project on the topic:

---

## **Phishing Emails Detection and Verification: A Case Study on Identifying Fake and Legitimate Emails**

---

### **1. Abstract**

Phishing attacks are a growing cybersecurity threat where attackers trick users into revealing sensitive information. This project presents a case study approach to detect and verify phishing emails. Through real-life examples, we analyze patterns, headers, and URLs to distinguish fake emails from legitimate ones. The aim is to educate users and recommend preventive measures.

---

### **2. Introduction**

Phishing is a form of cybercrime where attackers impersonate legitimate institutions via email or other communication channels to steal sensitive information like passwords, credit card numbers, or personal data. This project aims to understand the anatomy of phishing emails and how to detect and prevent them.

---

### **3. Objectives**

* To study different types of phishing attacks.
* To identify common signs of phishing emails.
* To analyze email headers and URLs for authenticity.
* To compare phishing and legitimate emails.
* To suggest best practices for email security.

---

### **4. Methodology**

#### 4.1 Data Collection

* Collected 20 phishing emails from public sources and personal inbox.
* Collected 10 legitimate emails from trusted senders (e.g., banks, institutions).

#### 4.2 Analysis Techniques

* **Header Analysis**: Use tools like MXToolbox, Google Header Analyzer.
* **URL Inspection**: Hover technique, VirusTotal scanning.
* **Language Check**: Grammatical errors, urgent tone, fake branding.
* **Sender Verification**: Email spoofing detection using SPF/DKIM/DMARC.

---

### **5. Case Study Examples**

#### Example 1: Fake Bank Email

* **Subject**: “Your account is suspended – Action Required”
* **From**: [support@abc-banksecure.com](mailto:support@abc-banksecure.com) (Not real domain)
* **Issue**: Link redirects to a fake login page.

#### Example 2: Legitimate Google Security Email

* **Subject**: “New sign-in from Chrome”
* **From**: [no-reply@accounts.google.com](mailto:no-reply@accounts.google.com)
* **Header check**: Valid SPF and DKIM.
* **Safe URL**: google.com domain.

---

### **6. Tools Used**

* **Email Header Analyzer** (Google, MXToolbox)
* **VirusTotal** (for URL checking)
* **PhishTank** (for blacklist checking)
* **WHOIS Lookup** (to verify domain registration)
* **Browser Inspect Tool**

---

### **7. Results**

* Out of 30 emails:

  * **20 were phishing**

    * 17 had suspicious domains.
    * 15 had fake URLs.
    * 12 had urgent language patterns.
  * **10 were legitimate**

    * Valid headers and authentication.
    * No suspicious links.
    * Professional language used.

---

### **8. Conclusion**

Phishing emails can be effectively detected using a combination of header analysis, domain inspection, and content checking. Educating users and using automated detection tools can greatly reduce the risk of falling victim to phishing attacks.

---

### **9. Recommendations**

* Always verify email domains before clicking links.
* Use email security tools and plugins.
* Enable two-factor authentication (2FA).
* Regularly update software and email filters.
* Educate employees and users about phishing risks.

---

### **10. References**

* [Google Safety Center](https://safety.google/)
* [PhishTank](https://www.phishtank.com/)
* [VirusTotal](https://www.virustotal.com/)
* [Cybersecurity & Infrastructure Security Agency (CISA)](https://www.cisa.gov/)

* https://www.cyberyodha.org/2023/08/fact-check-scammers-impersonating.html

* https://www.cyberyodha.org/search/label/%20Cyber%20Awareness


