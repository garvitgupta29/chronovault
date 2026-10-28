# 🔐 ChronoVault — Zero-Knowledge Time-Locked Prediction & Future Message Platform

> **⏳ Seal a prediction for the future or leave a personal time-locked message—mathematically locked until the exact reveal second arrives.**
>
> `🔒 Zero-Knowledge PBKDF2-HMAC-SHA256` · `🛡️ Tamper-Evident SHA-256 Proof` · `📂 Cloud Ledger & Stateless .cvault Files` · `🌍 Multi-Timezone Sync`

**ChronoVault** is a free, zero-knowledge cryptographic time-lock platform created by **Garvit Gupta**. Whether you want to prove you called a future event beforehand or send a personal digital time capsule to friends, family, or your future self, ChronoVault seals your entry in authenticated ciphertext so it cannot be read or altered by anyone—not even the platform administrator—before your scheduled reveal timestamp.

🚀 **Launch Live Web App:** https://chronovault.pythonanywhere.com/

## ✨ Key Public Features

* **🔮 Time-Locked Predictions & Future Messages:** Log verifiable forecasts, hypotheses, personal milestones, or future letters locked until any future date and time down to the exact second.
* **🛡️ Verifiable SHA-256 Commitment Proofs:** Every entry generates an immutable **SHA-256 commitment hash** bound to the creation time, reveal time, creator, and recipient—proving your prediction existed beforehand without exposing the plaintext early.
* **👤 Registered Account Ledger:** Sign in with email and password (verified via a 6-digit OTP) to manage received and sent entries, track live second-by-second countdowns, search or filter entries by status, and toggle decoded messages between visible and hidden views.
* **👥 Unlimited Friends & Spam-Protected Requests:** Add and accept **unlimited friends** in your Friends list, assign private nicknames for instant search, include an optional personal note with friend requests, or block unwanted senders at any time. When sealing a new prediction or future message, you can address up to **25 friends per entry** (or send to yourself, up to 3 personal entries per day).
* **🔐 Stateless No-Registration `.cvault` File Vault:** Prefer an instant, account-free workflow? Generate a downloadable `.cvault` encrypted file paired with a shareable **256-Bit Secret Key** (`CVK-...`) without registering an account. Upload the `.cvault` file and enter the Secret Key in the Decoder Panel once the reveal timestamp arrives.
* **🗑️ Right to Regret & Recipient Safety:** Creators can delete their sent entries at any time, and recipients can report inappropriate content directly from the proof inspector with cryptographic verification.
* **🌍 Synchronized Global Timezones & Live Status Bar:** Switch seamlessly across global timezones (`IST`, `UTC`, `GST`, `SGT`, `JST`, `GMT/BST`, `CET`, `EST`, `CST`, `PST`, `AEST`, plus your auto-detected local timezone) with an authoritative server-synchronized clock, live character counters, and unread browser-tab notification badges.

## 🧭 Two Ways to Seal an Entry on ChronoVault

| Feature / Aspect | 👤 Account Ledger Mode | 🔐 No-Registration File Vault (`.cvault`) |
| :--- | :--- | :--- |
| **Account Required** | Yes (Email + Password with 6-Digit OTP Verification) | No registration or sign-in required |
| **Friends & Recipients** | Connect with **unlimited friends**; select up to **25 friends per entry** (or yourself) | Downloaded as a portable `.cvault` file + **256-Bit Secret Key** (`CVK-...`) |
| **Time-Lock Enforcement** | Server-synchronized UTC reveal timestamp + zero-knowledge encryption | Authoritative UTC timestamp verification + 256-Bit Secret Key decryption |
| **Tamper Proofing** | Inspectable **SHA-256 Commitment Hash** & Authenticated Encryption | Embedded **SHA-256 Commitment Hash** & Authenticated File Armour |
| **Best For** | Predictions between friends, scheduled future letters, and cloud countdown tracking | Offline storage, sharing over external messengers, or one-off capsules |

## 🔒 Zero-Knowledge Security & Privacy Highlights

* **Mathematically Sealed Until Reveal Time:** Every entry is encrypted with **PBKDF2-HMAC-SHA256** key derivation and authenticated with **HMAC-SHA256** (`Encrypt-then-MAC`), ensuring nobody can read the content before the scheduled unlock timestamp.
* **Tamper-Evident Verification:** Modifying even a single character of a `.cvault` file, secret key, or commitment hash causes cryptographic authentication to fail immediately.
* **Responsive Cross-Device Design:** Built with a dark-mode glassmorphic interface optimized for mobile phones, tablets, and desktop monitors.

## 👨‍💻 Creator & Feedback

* **Created By:** Garvit Gupta *(with the help of Gemini Argon)*
* **Official Website:** https://chronovault.pythonanywhere.com/
* **Questions or Feedback:** Visit the **About Us → Contact Us** section inside the web application to send a direct message or suggestion.

## 📄 Copyright & Terms

© 2026 Garvit Gupta. All Rights Reserved. ChronoVault is an independent personal project created by Garvit Gupta and is provided "AS IS" without warranties.
