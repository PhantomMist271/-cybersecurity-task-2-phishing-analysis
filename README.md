
# 📧 Phishing Email Analysis – Cyber Security Internship Task 2

## 📝 Task Objective
Analyze a suspicious email to identify phishing traits using email header analysis and phishing indicators.

---

## 🔍 Sample Phishing Email Details

**Subject:** Urgent Action Required – Your Account Has Been Limited  
**Sender Email:** support@paypal-alert.com  
**Message:**

> Dear Customer,  
>  
> We have detected suspicious activity in your PayPal account. As a precaution, your account has been temporarily limited.  
>  
> To restore full access to your account, please verify your identity by clicking the link below:  
>  
> [Verify Now](http://paypal-verification-services.com/login)  
>  
> If you do not respond within 24 hours, your account will be permanently suspended.  
>  
> Thank you for your prompt attention to this matter.  
>  
> *PayPal Security Team*

---

## ⚠️ Phishing Indicators Identified

| Indicator | Description |
|----------|-------------|
| **Suspicious Sender** | The sender address `support@paypal-alert.com` is **not a legitimate PayPal domain**. |
| **Spoofing Detected** | Email failed **SPF and DKIM checks** — means sender identity is forged. |
| **Urgency Language** | Phrases like "Your account will be permanently suspended" create panic and prompt action. |
| **Fake Link** | "Verify Now" points to `http://paypal-verification-services.com` instead of the real PayPal domain. |
| **Generic Greeting** | Uses “Dear Customer” instead of your real name – phishing emails avoid personalization. |

---

## 🛠 Tools Used

- **MXToolbox Email Header Analyzer**  
  [https://mxtoolbox.com/EmailHeaders.aspx](https://mxtoolbox.com/EmailHeaders.aspx)

---

## 🖼️ Screenshots

### 1. Header Analyzer Result
![Header Analysis](screenshots/Screenshot 2025-06-24 133336.png)

### 2. Spoofed Sender Verification (SPF/DKIM Fail)
![Spoof Evidence](screenshots/Screenshot 2025-06-24 133457.png)

---

## 📚 Concepts Covered

- ✅ Phishing Identification  
- ✅ Email Spoofing  
- ✅ SPF/DKIM Header Analysis  
- ✅ Social Engineering Awareness  
- ✅ Threat Detection and Prevention

---

## 📦 Project Structure

```
Internship_Task2_Phishing_Analysis/
│
├── README.md
├── screenshots/
│   ├── Screenshot 2025-06-24 133336.png
│   └── Screenshot 2025-06-24 133457.png
```

---


