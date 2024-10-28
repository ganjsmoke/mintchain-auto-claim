
# Multi-Account Auto Claim Energy Bot

A bot designed to help you automatically claim energy from multiple accounts on the MintChain platform. This tool uses wallet signatures to securely log in and retrieve user rewards every 6 hours.

---

## 📝 Features
- Automatically logs into multiple accounts using private keys.
- Claims energy from available rewards.
- Processes only accounts registered with the correct referral invite.
- Logs and updates results to keep your `accounts.json` fresh.

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/ganjsmoke/mintchain-auto-claim.git

```
```bash
cd multi-account-auto-claim-bot
```

### 2. Install Dependencies
Ensure Node.js is installed. Then, run:
```bash
npm install axios web3@1.8.0 chalk@2
```

### 3. Register Using the Author’s Referral Link
To use this bot, **you must first register using the referral invite**.  
Click the link below to sign up:  
[Register with Author’s Referral Invite](https://www.mintchain.io/airdrop?inviteCode=SDQQOW1P)  
Alternatively, use the invite code during registration:  
**Invite Code:** `SDQQOW1P`

---

## 📂 Configuration

1. **Create `accounts.json`**  
   Add your accounts to the `accounts.json` file in the following format:
   ```json
   [
     {
       "private_key": "your_private_key_here",
       "access_token": ""
     }
   ]
   ```
you can leave the access_token blank as it will fill automatically

---

## 🔄 Usage

To start the bot, simply run:
```bash
node index.js
```

The bot will continuously process accounts every 6 hours.  

---

## 💬 Notes

- **Ensure Your Accounts Are Registered Using the Referral Code.**  
  Accounts that do not use the referral code (`SDQQOW1P`) during registration will not be processed by the bot.

- **Error Handling**: The bot automatically retries logins and refreshes tokens if expired. Errors are logged with detailed messages for troubleshooting.


---

## 🤖 Author
Created by: [@airdropwithmeh](https://t.me/airdropwithmeh)  

---

Enjoy seamless energy claiming on MintChain with this bot! 🎉
