# Privacy Policy — Easy Parking

**Last updated: 20 September 2026**

Easy Parking ("the app") lets you find a car park, pay for parking from a
wallet balance, and keep a record of what you spent. This policy explains what
the app collects, why, who it is shared with, and what you can ask us to do
with it.

The app is operated by **[LEGAL ENTITY NAME]**, [registered address],
Ulaanbaatar, Mongolia. Contact: **[privacy@your-domain.mn]**.

> **Before publishing:** replace the four bracketed placeholders above, host
> this page at a public URL, and put that URL in App Store Connect and Google
> Play. Apple requires a working privacy policy link on the product page.

---

## What we collect

Everything below is tied to your account. We collect nothing anonymously and
nothing before you register.

### You give us

| Data | When | Why |
|---|---|---|
| **Mobile phone number** | Registration and every sign-in | It identifies your account. A one-time SMS code proves the number is yours |
| **PIN** | Registration | Your credential. It is stored only as a salted one-way hash — we cannot read it back, and nobody at [LEGAL ENTITY NAME] can tell you what it is |
| **Full name** | Registration, optional | Shown in the app. You may skip it |
| **Vehicle plate numbers** | When you add a car | Parking is matched to a plate, so a visit reaches the right wallet |
| **Tax registration number (ТТД/TIN)** | Only if you ask for a company receipt | Required by the tax authority to issue a VAT receipt to a company |

### The app produces

| Data | Why |
|---|---|
| **Wallet balance and transaction history** — top-ups, parking charges, refunds, reversals | It is your money; the ledger is what shows where it went |
| **Parking records** — which car park, entry and exit times, what was charged | To bill correctly and to show you your history |
| **Top-up records** — amount, status, QPay invoice reference | To credit your wallet and to resolve a payment that did not arrive |
| **Tax receipts (e-Barimt)** — receipt number, lottery number, VAT amount | Mongolian law requires a tax receipt for a sale |
| **Push notification token** | So we can tell your device that a car entered or left a car park, or that a top-up completed. Only the token and the platform (iOS or Android) are sent — nothing else about your device |

## What we do **not** collect

- **We do not collect your location.** The app contains no location tracking.
  It never asks for location permission, and the map opens on the city centre
  or on a car park one of your cars is parked in — never on you.
- **We do not track you.** There is no advertising identifier, no ad network,
  no analytics SDK, no cross-app or cross-site tracking, and we do not sell
  or share data with data brokers.
- **We do not see your card or bank details.** Top-ups are paid inside your own
  banking app through QPay. Your card number never reaches Easy Parking.
- **We do not store your PIN or your biometrics.** Face ID and Touch ID are
  handled entirely by your phone; the app is only told pass or fail, and the
  biometric data itself never leaves your device.

## What is stored on your phone

Your session tokens are kept in the platform keychain (iOS) or the encrypted
keystore (Android). Preferences such as your theme, your language, and whether
you have hidden your balance are stored on the device only and are never sent
to us. Signing out clears the session tokens.

## Who we share it with

We share the minimum required, and only with parties that need it to make the
service work:

| Recipient | What they receive | Why |
|---|---|---|
| **Car park operators** | The plate and the visit that occurred at their site | They operate the barrier and set the tariff |
| **QPay** (payment processor, Mongolia) | The top-up amount and an invoice reference | To collect the payment from your bank |
| **Google Firebase Cloud Messaging** (Google LLC) | Your push token and the notification | It is the only way to deliver a push notification to a phone. No wallet figures, plate numbers or personal details are put in the payload — a notification is a signal, and the app fetches the content from our own servers |
| **General Department of Taxation (ТЕГ)** | The sale, and your ТТД if you asked for a company receipt | Mongolian law requires a tax receipt to be issued through their system |

We also disclose data where the law requires it, or to establish or defend a
legal claim.

Firebase Cloud Messaging is operated by Google and may process the push token
outside Mongolia. Google's privacy policy: https://policies.google.com/privacy

## How long we keep it

- **Your account and its data** — while your account exists.
- **Financial and tax records** — for the period Mongolian accounting and tax
  law requires, currently **10 years**, even after an account is closed. We
  cannot delete a tax receipt on request; the law does not allow it.
- **Push tokens** — until you sign out or the token is reissued.

## Your rights

You may ask us to:

- **see** the data we hold about you;
- **correct** anything wrong;
- **delete** your account and the data we are not legally required to keep;
- **object** to a particular use, or withdraw consent for push notifications
  (turning them off in your phone's settings is enough).

Write to **[privacy@your-domain.mn]** and we will respond within 30 days.
Deleting your account closes the wallet — ask us to transfer out any remaining
balance first, because a closed wallet cannot be reopened.

## Children

Easy Parking is for licensed drivers and is not directed at children. We do
not knowingly collect data from anyone under 18. If you believe a child has
registered, write to us and we will remove the account.

## Security

Every request between the app and our servers travels over TLS. PINs are
stored as salted one-way hashes. Sessions use short-lived access tokens with
single-use refresh tokens, so a stolen token expires quickly and a replayed
one revokes the session. Five wrong PINs lock an account for 15 minutes.

No system is perfectly secure. If a breach affects your data, we will tell you
and the relevant authority as the law requires.

## Changes

We will post any change here and update the date at the top. A change that
materially affects how we use your data will be announced in the app before it
takes effect.

## Contact

**[Easy Parking]**
 Ulaanbaatar, Mongolia
**[easyparking@gmail.com]
