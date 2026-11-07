# Privacy Policy — ExpenseTracker

_Last updated: 7 November 2026_

ExpenseTracker ("the app", "we") helps you record and understand your personal spending. This policy explains what data the app handles, why, and the choices you have.

**Contact:** silentupgrade.x@gmail.com

## 1. Data we collect

| Data | Why | Where it is stored |
|---|---|---|
| **Google account basics** — your name, email address and a Firebase user ID, provided when you sign in with Google | To create your account and keep your data private to you | Google Firebase Authentication |
| **Expenses and related records you enter** — amounts, dates, times, categories, sub-categories, notes, subscriptions, money lent/borrowed (including the names you type for people), savings goals, app settings | To show your spending, charts, insights and reminders, and to sync across your devices | Google Cloud Firestore, linked to your account |
| **Payment notifications (only if you turn on "Auto-detect payments")** — the amount, payee name and time shown in notifications from payment, UPI and SMS apps (including your phone's default SMS app) | To suggest expenses you can add with one tap | **On your phone only.** Nothing is uploaded unless you tap **Add**, which saves it as an expense in your account — or, if **"Auto-add trusted merchants"** is on, when a payment goes to a merchant you've put in the same category 3 times in a row. That payment is saved as an expense automatically (amount, payee name, date, time and that category) and you're shown an **Undo** option. You can turn auto-add off any time in Settings → Auto-detect payments |
| **Merchant → category choices (only with "Auto-detect payments")** — which category you picked for each payee | To pre-select the category next time and to decide which merchants are trusted for auto-add | On your phone only |
| **Voice entry (only when you tap the 🎤 mic)** — what you say, e.g. "30 chai" | To add expenses by speaking | The app doesn't record audio and needs no microphone permission: your phone's own speech service (Google's on most Android phones) turns your words into text and gives the app only that text, which is then handled like anything you type. See Google's privacy policy for its speech service |
| **AI category suggestions (only if "Smarter categories with AI (Gemini)" is on)** — the words of an expense the app couldn't sort itself (e.g. "kaka station"), and the names of your categories and sub-categories | To pick the right category, or suggest a new one you can accept or decline | Sent to **Google Gemini** (via Firebase AI Logic) only in that case. **No amounts, names of people, dates, account or payment details are sent.** Gemini's answers are remembered on your phone so the same words aren't sent again. Turn it off any time in Settings |
| **App preferences on the device** — reminder time, notification switches, app-lock setting, widget totals | To make the app work as you configured it | On your phone only |

We do **not** collect your location, contacts, photos, bank or card credentials, or the content of messages. OTPs and all non-payment notifications are ignored and never stored.

## 2. How we use data

Only to provide the app's features: recording expenses, showing charts and insights, subscription and lent/borrowed tracking, reminders and notifications, exports you create, and syncing your data to your account. We do **not** sell your data, show ads, or share your data with anyone for marketing.

## 3. Sharing

Your data is processed by **Google Firebase** (Authentication and Cloud Firestore), which stores it on our behalf. If you keep "Smarter categories with AI (Gemini)" on, the expense words and category names described above are processed by **Google Gemini** through Firebase AI Logic. See Google's privacy policy: https://policies.google.com/privacy

We share data with no one else, except if required by law.

## 4. Security

Data is sent over encrypted connections (HTTPS/TLS). Firestore security rules allow only your signed-in account to read or write your data. You can additionally lock the app with your fingerprint, face or phone PIN.

## 5. Retention and deletion

Your data is kept while your account exists. You can delete your account and **all** your data at any time:

- **In the app:** Settings → **Delete account**. This permanently deletes everything in your account from our servers, deletes your Firebase user, and clears the app's data on your phone.
- **Without the app:** follow the steps on the [Delete your account page](https://sudarshan692.github.io/expensetracker-policies/delete-account.html).

Deletion is permanent and cannot be undone. You can export your data first from Settings → Export.

## 6. Permissions the app uses

- **Notifications** — reminders, alerts and summaries you can switch off in Settings.
- **Alarms & reminders (exact alarms)** — to deliver your daily reminder at the time you chose.
- **Run at startup** — to re-schedule your reminder after the phone restarts.
- **Notification access (optional, only for "Auto-detect payments")** — to read payment notifications as described above. Asked only after you agree to an in-app explanation.
- **No microphone permission** — voice entry uses your phone's built-in speech input, which asks for and handles the microphone itself.
- **Biometric (optional)** — for app lock. Your fingerprint/face data never leaves the phone and is never available to the app.

## 7. Children

The app is not directed to children under 13 and we do not knowingly collect their data.

## 8. Changes

We may update this policy. The "Last updated" date above shows the latest version.

## 9. Contact

Questions or requests: silentupgrade.x@gmail.com
