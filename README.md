# Ari Chain Wallet Auto Referral Bot

This bot automates the process of creating accounts and using referral codes for the AriChain Wallet.

## Features

- Automatically generates random email addresses.
- Handles email verification.

## Requirements

- Node.js v18.20.5 LTS or latest.
- npm (Node Package Manager)
- Use 2Captcha Services [2Captcha](https://2captcha.com/), [AntiCaptcha](https://anti-captcha.com/), free version you can using gemini apikey.
- email and password gmail (for password not your email password, use app password)

## Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/christiangrey922/Arichain-reg.git
   cd arichain-autoreff
   ```

2. Install the dependencies:

   ```sh
   npm install
   ```

3. Create a `proxy.txt` file in the root directory and add your proxies (one per line).

4. change `config.json.example` to `config.json`

5. change your email, password (app password). To get app password, you need to turn on 2FA first.

6. If you want using 2 Captcha service you can fill your apikey in `config.json` and change `"captha2Apikey": "your_2captcha_apikey",` with your apikey.

## Usage

1. Run the bot:

   ```sh
   node .
   ```

2. Follow the prompts to enter your referral code, address to transfer token and the number of accounts you want to create, and dont forget too choice your solve captcha too.

## Output

- The created accounts will be saved in `accounts.txt`.

## Notes

- Make sure to use valid proxies to avoid IP bans.
- The bot will attempt to verify the email up to 5 times before giving up.

## Stay Connected

- Telegram : [Telegram](https://t.me/christiangrey922)

## Donation

If you would like to support the development of this project, you can make a donation using the following addresses:

- Solana: `Gz7QxSUXXYH6pZQQPGxj7nU3AFUxZgMCB112AVVzaZSE`
- BNB: `0xf61dbe74a5e0e197e1c92c316ed1dd1c88db6bc6`

## Disclaimer

This tool is for educational purposes only. Use it at your own risk.
