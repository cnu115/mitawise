# Privacy Policy for MitaWise

**Last updated:** July 19, 2025

**Effective date:** July 19, 2025

MitaWise ("we," "us," or "our") operates the MitaWise mobile application (the "App"). This Privacy Policy explains how we collect, use, disclose, and safeguard your information when you use our App. Please read this policy carefully. By using MitaWise, you agree to the collection and use of information in accordance with this policy.

---

## 1. Information We Collect

### 1.1 Account Information

When you create an account, we collect:

- **Name** — your display name within the app
- **Email address** — used for authentication, password recovery, and transactional communications
- **Password** — stored as a one-way cryptographic hash (bcrypt); we never store or have access to your plain-text password
- **Profile photo** (optional) — if you choose to upload an avatar

### 1.2 Financial Data

To provide expense and income tracking, we collect:

- Expense records (amount, description, category, date)
- Income records (amount, description, category, date)
- Custom categories you create
- Monthly and weekly budget settings

### 1.3 User Preferences

- Theme, language, currency, date format preferences
- Reminder settings (enabled/disabled, preferred time)

### 1.4 Device and Usage Information

- Device type and operating system (collected by the platform for crash reporting)
- We do **not** collect precise location, contacts, call logs, or SMS data

### 1.5 App Ratings

If you choose to rate the app, we store your rating (1–5) and optional review text.

---

## 2. How We Use Your Information

We use the information we collect to:

- **Provide core functionality** — track your expenses, incomes, and budgets
- **Authenticate your account** — secure login, token refresh, and password recovery
- **Send transactional emails** — welcome emails and password reset codes (we do not send marketing emails)
- **Sync and backup your data** — if you opt into Google Drive backup
- **Improve the App** — understand usage patterns and fix issues

---

## 3. Third-Party Services

We use the following third-party services to operate the App:

| Service | Purpose | Data Shared |
|---------|---------|-------------|
| **Google OAuth** | Optional sign-in and Google Drive backup authentication | Email (for auth), Drive appData (backup file only) |
| **Google Drive** | Optional cloud backup of your financial data | Encrypted backup file stored in your private appDataFolder (invisible in your Drive) |
| **Cloudinary** | Profile photo storage | Avatar image file only |
| **Resend** | Transactional email delivery | Email address, name (for personalization) |
| **PostgreSQL (hosted)** | Database storage | All account and financial data |
| **Render** | Backend hosting | Data processed through their infrastructure |

Each third-party service is governed by its own privacy policy. We encourage you to review them:

- [Google Privacy Policy](https://policies.google.com/privacy)
- [Cloudinary Privacy Policy](https://cloudinary.com/privacy)
- [Resend Privacy Policy](https://resend.com/legal/privacy-policy)
- [Render Privacy Policy](https://render.com/privacy)

---

## 4. Google Drive Backup

If you choose to use the Google Drive backup feature:

- We request access to the `drive.appdata` scope, which gives us access **only** to a hidden, app-specific folder in your Google Drive — not your personal files.
- We also request `userinfo.email` to identify your Google account.
- Backup data includes your expenses, incomes, and categories in JSON format.
- You can delete the backup at any time through the App or directly in Google Drive.

---

## 5. Data Storage and Security

- All passwords are hashed using bcrypt with 12 rounds before storage.
- Authentication tokens are stored securely on your device using encrypted device storage (Expo SecureStore).
- Access tokens expire after 15 minutes; refresh tokens expire after 15 days.
- Password reset codes expire after 15 minutes.
- Data is transmitted over HTTPS.
- We implement rate limiting to protect against abuse.

---

## 6. Data Retention

- Your account and financial data are retained as long as your account is active.
- If you delete your account, all associated data (expenses, incomes, settings, tokens, and ratings) is permanently removed from our servers via cascading deletion.
- Refresh tokens are automatically deleted upon logout or expiration.

---

## 7. Your Rights and Choices

You have the right to:

- **Access your data** — view all your expenses, incomes, and account information within the App
- **Export your data** — use the export feature to download your financial data
- **Update your information** — edit your name, email, avatar, and preferences at any time
- **Delete your account** — request account deletion, which removes all your data permanently
- **Opt out of backups** — Google Drive backup is entirely optional and user-initiated

---

## 8. Children's Privacy

MitaWise is not intended for use by children under the age of 13. We do not knowingly collect personal information from children under 13. If you are a parent or guardian and believe your child has provided us with personal information, please contact us so we can delete it.

---

## 9. Permissions Used

The App may request the following device permissions:

- **Camera** — to capture photos for profile pictures or receipts
- **Photo Library** — to select images from your device for your profile
- **Internet** — required for syncing data with our servers

We do **not** request or access:

- Location data
- Contacts
- Phone/call logs
- SMS messages
- Microphone (for recording)

---

## 10. Changes to This Privacy Policy

We may update this Privacy Policy from time to time. We will notify you of any changes by posting the new Privacy Policy within the App and updating the "Last updated" date above. You are advised to review this Privacy Policy periodically for any changes.

---

## 11. Contact Us

If you have any questions or concerns about this Privacy Policy or our data practices, please contact us at:

**Email:** mitawiseapp@gmail.com

---

## 12. Consent

By using MitaWise, you consent to our Privacy Policy and agree to its terms.
