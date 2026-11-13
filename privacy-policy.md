# Privacy Policy — Finora: Expense Tracker

_Last updated: 13 November 2026_

Finora: Expense Tracker ("the app", "we") helps you record and understand your personal spending. This policy explains what data the app handles, why, and the choices you have. See also our [Terms of Use](terms.html).

**Contact:** supportitappdev@gmail.com

## 1. Data we collect

| Data | Why | Where it is stored |
|---|---|---|
| **Google account basics** — your name, email address and a Firebase user ID, provided when you sign in with Google | To create your account and keep your data private to you | Google Firebase Authentication |
| **Expenses and related records you enter** — amounts, dates, times, categories, sub-categories, notes, subscriptions, money lent/borrowed (including the names you type for people), budgets (including any top-up you add for a month), app settings | To show your spending, charts, insights and reminders, and to sync across your devices | Google Cloud Firestore, linked to your account |
| **Payment notifications (only if you turn on "Auto-detect payments")** — the amount, payee name and time shown in notifications from payment, UPI and SMS apps (including your phone's default SMS app) | To suggest expenses you can add with one tap | **On your phone only.** Nothing is uploaded unless you tap **Add**, which saves it as an expense in your account — or, if **"Auto-add trusted merchants"** is on, when a payment goes to a merchant you've put in the same category 3 times in a row. That payment is saved as an expense automatically (amount, payee name, date, time and that category) and you're shown an **Undo** option. You can turn auto-add off any time in Settings → Auto-detect payments |
| **Merchant → category choices (only with "Auto-detect payments")** — which category you picked for each payee | To pre-select the category next time and to decide which merchants are trusted for auto-add | On your phone only |
| **Voice entry (only when you tap the 🎤 mic)** — what you say, e.g. "30 chai" | To add expenses by speaking | The app doesn't record audio and needs no microphone permission: your phone's own speech service (Google's on most Android phones) turns your words into text and gives the app only that text, which is then handled like anything you type. See Google's privacy policy for its speech service |
| **AI category suggestions (only if "Smarter categories with AI (Gemini)" is on)** — the words of an expense the app couldn't sort itself (e.g. "kaka station"), and the names of your categories and sub-categories | To pick the right category, or suggest a new one you can accept or decline | Sent to **Google Gemini** (via Firebase AI Logic) only in that case. **No amounts, names of people, dates, account or payment details are sent.** Gemini's answers are remembered on your phone so the same words aren't sent again. Turn it off any time in Settings |
| **Signed-in phone** — a random ID the app creates for your phone (not your phone number, IMEI or any hardware ID) | So only one phone is signed in to your account at a time: signing in on a new phone signs the old one out | With your account in Google Cloud Firestore, and on your phone |
| **App preferences on the device** — reminder time, notification switches, app-lock setting, widget totals | To make the app work as you configured it | On your phone only |
| **Subscription status** — whether you're on the free trial, a monthly or yearly plan bought through Google Play, or free access given by the developer, with the dates | To unlock the app after the trial, and to count subscriptions in the developer's admin view | On your phone and with your account in Google Cloud Firestore. Each purchase carries a scrambled (one-way hashed) form of your account ID, so a subscription belongs to the account that bought it. **Payments are processed by Google Play: we never see or store your UPI, card or bank details** |
| **Your agreement to these policies** — which version of the Terms of Use and this Privacy Policy you accepted, and the date | To show you've agreed, and to ask again when they change significantly | On your phone, and with your account in Google Cloud Firestore |
| **Activity summary** — at most once every 3 days, when you open the app: your account's email address, the days you used the app (last 60 days), app version, phone make/model and Android version, which features are switched on (e.g. budget, app lock, auto-detect, dark theme), how many expenses, subscriptions and lent/borrowed entries you have, how often features were used (e.g. voice, quick add, exports, AI lookups), your subscription plan, and how many expenses use each built-in sub-category. **No amounts, notes, names of people or the names of sub-categories you created yourself** | To see how many people use the app and how often, which features help, what to fix or improve, and to keep the app's server usage efficient. The email lets the developer recognise an account (for example when you ask for help or deletion) | Google Cloud Firestore, with your account. Only the developer can see it, in an admin view |
| **Crash reports and app usage analytics** — when the app crashes: the error, app version, phone model and Android version; usage events such as app opens and screens viewed, with a random app-instance ID | To find and fix crashes and understand overall usage | **Google Firebase Crashlytics** and **Google Analytics for Firebase**. They don't include your expenses, notes or account details |
| **Advertising (only on the free trial, and only while the developer has ads switched on)** — your phone's **advertising ID**, your IP address (from which an approximate location can be inferred), phone model, Android version, app version, and how you interact with ads (shown, tapped, watched) | To show a video ad after every few expenses you add, measure it and prevent ad fraud. Paid plans and free access from the developer never show ads | Collected by **Google AdMob**. AdMob never receives your expenses, notes, amounts, categories, names or account details. The app only counts, on your phone, how many expenses were added since the last ad |

Apart from what Google AdMob collects to show ads on the free trial (above), we do **not** collect your location, contacts, photos, bank or card credentials, or the content of messages. OTPs and all non-payment notifications are ignored and never stored.

## 2. How we use data

Only to provide the app's features: recording expenses, showing charts and insights, subscription and lent/borrowed tracking, reminders and notifications, exports you create, and syncing your data to your account. The activity summary, crash reports and analytics are used only to keep the app working and to improve it. The developer can block an account that misuses the app (a blocked account is signed out and can't use the app until unblocked), and can delete an account's data when you ask (or for abuse); this is the only reason the developer's access can reach your records, and they are never viewed for any other purpose. We do **not** sell your data or share it with anyone for marketing. People on the free trial may see ads (section 3); paid plans and free access never do.

## 3. Sharing

Your data is processed by **Google Firebase** (Authentication, Cloud Firestore, Crashlytics and Google Analytics for Firebase), which stores it on our behalf. To protect your account from fake or modified copies of the app, **Firebase App Check** asks **Google Play Integrity** to confirm that each request comes from the genuine app on a real device; Google receives information about the app and device for that check, never your expenses. Subscription payments are handled by **Google Play**. If you keep "Smarter categories with AI (Gemini)" on, the expense words and category names described above are processed by **Google Gemini** through Firebase AI Logic. See Google's privacy policy: https://policies.google.com/privacy

**Ads (free trial only).** While ads are switched on, people on the free trial see a video ad from **Google AdMob** after every few expenses they add. AdMob uses the data listed in section 1, including your advertising ID, to choose and measure ads; ads may be personalised unless you opt out. Where the law requires it (for example in the EEA and the UK), the app first shows Google's consent form. You can reset or delete your advertising ID, or opt out of personalised ads, in your phone's **Settings → Google → Ads** (or **Settings → Privacy → Ads**). Subscribing to a paid plan removes ads. How Google uses this data: https://policies.google.com/technologies/partner-sites

We share data with no one else, except if required by law.

## 4. Security

Data is sent over encrypted connections (HTTPS/TLS). Firestore security rules allow only your signed-in account to read or write your data; the only exception is the developer's admin access described in section 2. You can additionally lock the app with your fingerprint, face or phone PIN.

## 5. Retention and deletion

Your data is kept while your account exists. The developer may set a limit on how long expenses are kept for everyone (for example, the last 365 days): expenses older than that are then deleted automatically from your account, oldest first, by your own app when it opens or when you add expenses. Lent/borrowed entries, subscriptions, categories and budgets are not affected. Export your data (Settings → Export) if you want a copy of older expenses.

You can delete your account and **all** your data at any time:

- **In the app:** Settings → **Delete account**. This permanently deletes everything in your account from our servers, deletes your Firebase user, and clears the app's data on your phone.
- **Without the app:** follow the steps on the [Delete your account page](https://supportitappdev-alt.github.io/expensetracker-policies/delete-account.html).

Deletion is permanent and cannot be undone. You can export your data first from Settings → Export.

## 6. Permissions the app uses

- **Notifications** — reminders, alerts and summaries you can switch off in Settings.
- **Alarms & reminders (exact alarms)** — to deliver your daily reminder at the time you chose.
- **Run at startup** — to re-schedule your reminder after the phone restarts.
- **Notification access (optional, only for "Auto-detect payments")** — to read payment notifications as described above. Asked only after you agree to an in-app explanation.
- **No microphone permission** — voice entry uses your phone's built-in speech input, which asks for and handles the microphone itself.
- **Advertising ID** — used only by Google AdMob to show ads on the free trial (section 3).
- **Biometric (optional)** — for app lock. Your fingerprint/face data never leaves the phone and is never available to the app.

## 7. Children

The app is not directed to children under 13 and we do not knowingly collect their data.

## 8. Changes

We may update this policy. The "Last updated" date above shows the latest version.

## 9. Contact

Questions or requests: supportitappdev@gmail.com
