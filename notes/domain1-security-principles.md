# 🛡️ 1. Security Principles
*✨ The Foundation of Everything ✨*

---

 📖 Table of Contents
- [💁‍♀️ In a Nutshell](#-in-a-nutshell)
- [🔑 Key Concepts & Definitions](#-key-concepts--definitions)
- [🎯 Exam Focus Points](#-exam-focus-points)
- [❓ Frequently Asked Questions](#-frequently-asked-questions)
- [🔗 Resources & Links](#-resources--links)
- [🧠 Active Recall Flashcards](#-active-recall-flashcards)

---

💁‍♀️ In a Nutshell

Imagine you're protecting your diary. You'd want to:
*   Keep it **secret** (Confidentiality) - maybe in a locked drawer. 🔒
*   Make sure no one has **changed** what you wrote (Integrity) - using a pen so it can't be erased.
*   Be able to **access** it whenever you want to write (Availability) - not losing the key.

That's Domain 1! It's all about these basic, fundamental ideas that form the bedrock of cybersecurity. It's the "why" behind everything we do.

---

## 🔑 Key Concepts & Definitions

### The Core Principles
| Concept | Definition | Real-World Example |
| :--- | :--- | :--- |
| **Confidentiality** | Preventing unauthorized disclosure of information. | **Encryption** (like WhatsApp's secret chats), passwords, access controls. |
| **Integrity** | Guarding against improper information modification or destruction. | **Hashing** (a digital fingerprint for files), digital signatures, checksums. |
| **Availability** | Ensuring timely and reliable access to and use of information. | Redundant servers, backups, preventing Denial-of-Service (DoS) attacks. |

### The Security Triad in Action: **AAA**
*   **Authentication:** Verifying who you are. (e.g., Password, Fingerprint, Face ID).
*   **Authorization:** Determining what you're allowed to do. (e.g., Can you edit this file or just view it?).
*   **Accounting (Auditing):** Tracking what you did. (e.g., Logs that show who accessed a file and when).

### Risk Management 101
*   **Asset:** Something of value that needs protection. (e.g., Customer data, a server, company reputation).
*   **Vulnerability:** A weakness in the asset. (e.g., Unpatched software, a weak password).
*   **Threat:** Something that can exploit a vulnerability. (e.g., A hacker, malware, a natural disaster).
*   **Risk:** The potential for loss or damage. **Risk = Threat x Vulnerability**.
*   **Control/Safeguard:** A measure taken to reduce risk. (e.g., Installing a firewall, training employees).

### Types of Security Controls
| Type | What it is | Examples |
| :--- | :--- | :--- |
| **Administrative** | Policies, procedures, and guidelines. | Security policies, hiring practices, training. |
| **Technical (Logical)** | Software and hardware mechanisms. | Firewalls, encryption, antivirus, access control lists. |
| **Physical** | Tangible measures to protect assets. | Locks, security guards, badge readers, surveillance cameras. |

### Control Functions
*   **Preventive:** Stops an incident from happening. (e.g., A fence).
*   **Detective:** Identifies an incident while it's happening. (e.g., A security camera).
*   **Corrective:** Fixes things after an incident. (e.g., Restoring from a backup).
*   **Deterrent:** Discourages a threat from attempting an incident. (e.g., "Beware of Dog" sign).
*   **Compensating:** Provides an alternative control when the primary one isn't possible. (e.g., More frequent monitoring if a patch can't be applied).

---

## 🎯 Exam Focus Points
*   **MEMORIZE the CIA Triad and AAA.** You *will* get questions on these.
*   Understand the difference between a **vulnerability**, a **threat**, and a **risk**.
*   Be able to **classify a control**. Is it administrative, technical, or physical? Is it preventive, detective, or corrective?
*   Know what **encryption** (confidentiality) and **hashing** (integrity) are used for.

---

## ❓ Frequently Asked Questions

**Q: What's the difference between Authentication and Authorization?**
> **A:** Authentication is about *identity* ("Who are you?"). Authorization is about *permissions* ("What are you allowed to do?"). You authenticate with a password so the system knows it's you, and then it authorizes you to access your files, but not the CEO's.

**Q: Is a firewall a preventive or detective control?**
> **A:** It's primarily **preventive** because it's designed to stop unauthorized traffic before it enters the network.

**Q: What's a real-world example of Integrity?**
> **A:** When you download software, the website often provides a "hash" value. After you download it, you can generate a hash of the file. If the two hashes match, you know the file hasn't been tampered with during download.

**Q: What's the goal of a Deterrent control?**
> **A:** Its goal isn't to physically stop an attack, but to psychologically discourage it. A "24/7 Video Surveillance" sign is a deterrent control.

---

## 🔗 Resources & Links
*   **Official ISC2 CC Outline:** [Link to Domain 1 Section](https://www.isc2.org/-/media/ISC2/Certifications/Outline/ISC2-Certified-in-Cybersecurity-Exam-Outline.ashx)
*   **ISC2 Free Course:** Module 1 - Security Principles.
*   **Helpful Video:** "CIA Triad Explained" by [PowerCert Animated Videos](https://www.youtube.com/watch?v=_nyVd4e_0RE) on YouTube.

---

## 🧠 Active Recall Flashcards

<details>
<summary>What are the three components of the CIA Triad?</summary>
<br>
<b>Confidentiality, Integrity, Availability.</b>
</details>

<details>
<summary>What is the primary purpose of encryption?</summary>
<br>
To provide <b>Confidentiality</b> by making data unreadable to unauthorized users.
</details>

<details>
<summary>A weak password is an example of a Vulnerability, Threat, or Risk?</summary>
<br>
A <b>Vulnerability</b> (it's a weakness).
</details>

<details>
<summary>A hacker is an example of a Vulnerability, Threat, or Risk?</summary>
<br>
A <b>Threat</b> (the actor that can cause harm).
</details>

<details>
<summary>What type of control is an antivirus software: Administrative, Technical, or Physical?</summary>
<br>
<b>Technical</b> (it's a software-based control).
</details>

<details>
<summary>What does the "AAA" in security stand for?</summary>
<br>
<b>Authentication, Authorization, Accounting (Auditing).</b>
</details>

---

*✨ You've got this! Take a deep breath, maybe sip some iced coffee, and come back to these flashcards later. 🌸*
