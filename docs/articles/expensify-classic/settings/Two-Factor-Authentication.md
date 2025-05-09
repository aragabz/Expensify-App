---
title: Two-Factor Authentication
description: Enhance your account security by enabling two-factor authentication (2FA) in Expensify.
keywords: [two-factor authentication, 2FA, security, Expensify, authenticator app, backup codes]
---
<div id="expensify-classic" markdown="1">

Setting up two-factor authentication (2FA) adds an extra layer of security to protect your financial data. When you log in, you must enter a code generated by your preferred authenticator app (such as Google Authenticator or Microsoft Authenticator).

Expensify's 2FA is implemented via a Time-based One-Time Password (TOTP) algorithm. Each time you log in, you must use an authenticator app to generate a unique 6-digit code, adding a second “factor” to your login.

---

# Recommended Authenticator Apps

You can use any authenticator app, but here are a few we recommend:

- [1Password](https://support.1password.com/one-time-passwords/)
- [Authy](https://authy.com/)
- [Google Authenticator](https://support.google.com/accounts/answer/1066447)
- [Microsoft Authenticator](https://www.microsoft.com/en-us/security/mobile-authenticator-app)

Ensure you have an authenticator app installed before proceeding.

---

# Enable Two-Factor Authentication

1. Go to **Settings > Account > Profile**.
2. Enable **Two-factor authentication**.
3. Save a copy of your backup codes:
   - Click **Download** to save them to your computer.
   - Click **Copy** to store them in a secure location.
- **Important!** If you lose access to your authenticator app and do not have your recovery codes, you will lose access to your account.
4. Click **Continue**.
5. Open your authenticator app and either:
   - Scan the QR code displayed on your screen.
   - Enter the 6-digit code from your authenticator app into Expensify and click **Verify**.

**Once set up, when logging into Expensify, you will:**
- Receive a Magic Code email to initiate login.
- Be prompted to enter a 6-digit code from your authenticator app.

Codes refresh every few seconds. If you receive a message that the code is expired, re-refer to your authenticator app and use the most up-to-date code.

---

# Lost Recovery Codes or Access to the Authenticator App

If you lose your mobile device and recovery codes, a **Domain Admin** can reset an employee's 2FA settings **only if**:

- The employee uses a company email or a domain you own.
- The Domain Admin also has 2FA enabled.

## Reset 2FA as a Domain Admin

1. Go to **Settings > Domains > Domain Members**.
2. Click **Edit Settings** for the affected email address.
3. Click **Reset** to disable 2FA.
4. The user can now log in and reconfigure 2FA.

If your domain does not have 2FA enabled:
1. Go to **Settings > Domains > Domain Members**.
2. Enable **Two-Factor Authentication**.
3. Follow the previous steps to reset 2FA for the user.

**Note:** If you use a non-corporate email (e.g., Gmail, Yahoo, Hotmail), Expensify cannot disable 2FA. If recovery codes are lost, you may need to create a new account with a different email.

If no Domain Admin is available, follow [this guide](https://help.expensify.com/articles/expensify-classic/domains/Claim-And-Verify-A-Domain) to verify the domain, and then run through the steps above.

---

# Troubleshooting

Ensure your phone’s time is set to **automatic update**. A manual time difference can cause issues when entering the authentication code. See this resource for more details on [setting the timezone in your account](https://help.expensify.com/articles/expensify-classic/settings/Set-Time-Zone).

Make sure you're not still logged in on another device. If you are, do the following:
  1. Go to **Settings > Account > Profile**.
  2. Toggle **Two-factor authentication** to off.
  3. Try logging in again.
  4. Once logged in, you can re-enable 2FA.

Following these steps ensures your account remains secure while preventing access issues.

</div>
