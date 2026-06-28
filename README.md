# **Password Remediation Case Study**

A real-world security improvement project for a small business, focused on eliminating weak password practices, reducing credential exposure, and empowering the business owner to manage their own security independently.

## **Project Overview**

This project documents end-to-end remediation of poor credential hygiene across a small business's critical systems, including Google Workspace, WordPress, and website management tools.

Several credentials were identified as weak, reused across services, and present in public breach data — posing a significant and immediate account compromise risk.

The solution combined:

* Password vault deployment (NordPass)  
* Encrypted remote access (NordVPN)  
* Self-service recovery guides (Scribehow)  
* Security awareness training for the business owner  
* Multi-factor authentication across all critical systems

## **Objectives**

* Eliminate weak and reused passwords across all business accounts  
* Reduce the risk of credential compromise and phishing exposure  
* Remove admin dependency for password resets  
* Apply least privilege principles to reduce insider risk  
* Improve overall security posture with minimal operational disruption

**Issues Identified**

| Issue | Detail |
| ----- | ----- |
| Weak passwords | Estimated offline crack time under 14 days |
| Credential reuse | Same passwords shared across multiple services |
| No password manager | Credentials stored insecurely or from memory |
| Admin over-exposure | Too many people with knowledge of or access to credentials |
| No encrypted browsing | Business owner accessing systems over unprotected networks |
| No MFA | Critical accounts unprotected by a second factor |

---

## **Solution**

### **1\. Password Vault Deployment (NordPass)**

Implemented NordPass across all business accounts, enforcing:

* Unique, randomly generated, lengthy and complex passwords (16–24+ characters) per service  
* Encrypted vault storage with zero-knowledge architecture  
* Limited admin privileges

### **2\. Secure Remote Access (NordVPN)**

Configured NordVPN for the business owner to provide:

* Encrypted internet traffic on all networks  
* Reduced exposure to interception attacks on public Wi-Fi

### **3\. Self-Service Password Recovery (Scribehow)**

Created step-by-step guides covering:

* Accessing and navigating the password vault  
* Password reset flows for key services  
* Account recovery procedures
* Using tech stack and maintaining security best practices as a solo business owner

This removed the dependency on IT or admin intervention for routine resets to empower the business owner to do all tasks independently and confidently.

### **4\. MFA Implementation**

Deployed Google Authenticator across all critical systems, adding a second factor to all key accounts. An example of this is, I added a passkey and touch ID to the Stripe account. 

### **5\. Security Awareness Training**

I also educated the business owner on:

* Risks of weak and reused passwords  
* Password hygiene and creation (length, age, reuse and complexity)
* Least privilege and privileged access management
* Secure credential handling and the importance of password isolation
* Phishing & Social Engineering techniques to watch out for

---

## **Results**

| Metric | Before | After |
| ----- | ----- | ----- |
| Estimated offline crack time | \< 14 days | Created using strong password principles |
| Password reuse | Present across services | Eliminated risk |
| Secure credential storage | None | Encrypted vault via NordPass |
| Admin access to passwords | Shared with other administrators | Isolated to account owner only |
| Encrypted browsing | None | NordVPN deployed |
| MFA | Not in use | Deployed across all accounts |
| Self-service recovery | Not available | Guides in place (Scribehow)|

---

## **Security Principles Applied**

* **Least privilege** — admin accounts reduced to only those requiring access  
* **Credential isolation** — only the account owner holds password knowledge  
* **Zero-knowledge storage** — vault provider cannot access stored credentials  
* **Defence in depth** — vault \+ VPN \+ MFA \+ process improvements layered together  
* **User empowerment** — business owner is able to manage and recover credentials independently without third-party support

---

## **Potential Future Improvements**

* Reducing redundant services that connect with each other to reduce the attack surface
* Periodic breach monitoring (e.g. Have I Been Pwned alerts for business domains)  
* Formal password policy documentation
* Cyber Essentials certification 

---

## **Important Note**

No real passwords, account names, domains or client-identifying information are included in this repository. All examples and references have been anonymised for security and privacy reasons to protect the small business I supported. 

---

## **Skills Demonstrated**

| Skill |
| ----- | 
| Credential management |
| Risk identification and communication |
| Security awareness training | 
| Tool deployment and configuration | 
| Practical remediation | 
| Professional documentation |



