# PeriyoDoz — Privacy Policy

**Last updated:** 10 September 2026
**Effective date:** 10 September 2026

> ⚠️ **FILL IN BEFORE PUBLISHING** (remove this block before going live)
> - `[DATA CONTROLLER]` → your legal name or company name
> - `[ADDRESS]` → postal address (required for GDPR/KVKK notice obligations)
> - `[FIRESTORE REGION]` → Firebase Console → Firestore → location (e.g. `eur3`)
> - Add store links once the app is live on the App Store / Google Play

---

## 1. Who we are and what this covers

PeriyoDoz (the "App") is a mobile application for medication reminders and family health tracking. This policy explains what data is processed when you use the App, why, who it is shared with, and what rights you have.

**Data controller:** `[DATA CONTROLLER]`
**Contact:** destek@periyodoz.com
**Address:** `[ADDRESS]`

This policy is written to comply with the EU General Data Protection Regulation (GDPR) and Turkish Law No. 6698 on the Protection of Personal Data (KVKK).

---

## 2. Important: the App is not a medical device

PeriyoDoz **does not provide medical advice, diagnosis, or treatment**. All features, including the medicine interaction check, are automated reminder and information tools based on a limited set of known interaction categories, and are not exhaustive. The absence of a warning in the App does not mean there is no risk.

**Always consult your doctor or pharmacist for any decision about your medication.**

---

## 3. Data we process

### 3.1 Account and identity data

| Data | How collected | Why |
|---|---|---|
| Email address | You enter it at sign-up | Account creation, sign-in, password reset |
| Password | You enter it at sign-up | Authentication. Your password **never reaches us**; it is stored in encrypted form by Google Firebase Authentication and cannot be viewed by us |
| Name | Optional, entered by you | In-app personalisation, identifying who a caregiver alert is about |
| Age, gender | Optional, entered by you | Tailoring features (e.g. cycle tracking is only shown to relevant users) |
| Phone number | Optional, entered by you | Stored on your device and in your account only; never used to send SMS |
| Profile photo | Optional, uploaded by you | In-app profile image |

**Anonymous use:** You can use the App without creating an account. In that case an anonymous identifier is assigned to your device and your data is linked to it. When you register with an email address, that identity is upgraded to your account and your existing data is preserved.

### 3.2 Health data (special category data)

The following is processed **only if you enter it**. The App does not collect this automatically from device sensors or third parties.

- **Medication details:** name, dosage, times, reminder days, stock, active ingredient, purpose, prescription notes, photo of the package
- **Adherence records:** when you took or missed a dose, adherence statistics
- **Measurements:** blood pressure, weight, blood glucose values and their dates
- **Health journal:** free-text notes on pain, side effects, mood, sleep, energy and stress
- **Cycle tracking:** period days, mood, symptoms, spotting, pregnancy test result, and stress/sleep/exercise/nutrition factors
- **Water intake and sleep targets**

This is **special category data** under GDPR Article 9 and KVKK Article 6, processed solely on the basis of your **explicit consent**. You may withdraw that consent at any time by discontinuing use or deleting your account.

### 3.3 Data about family members

The App lets you create sub-profiles for family members (children, parents, partner). Data you enter into these profiles **belongs to another person**.

By creating a profile for a family member you confirm that you are entitled to enter their data (as their parent/guardian, or with their consent). You are responsible for the accuracy and lawfulness of that data.

### 3.4 Caregiver linking

When you link a family member as a caregiver:
- A single-use invitation code is generated for you
- The person who redeems it can view your data **within the scope you choose** ("medicines only" or "full sharing")
- Your caregiver is notified when you miss a dose

You can stop this sharing at any time. Caregiver access is verified server-side; no user can reach another user's data without a valid invitation code.

### 3.5 Automatically collected technical data

- **Device and app information:** OS version, app version, device model, language
- **Usage analytics:** which screens are viewed, sign-in/sign-up/subscription events (event names only, not content)
- **Crash reports:** stack traces and the screen transitions leading up to a crash
- **Push token:** so caregiver notifications can be delivered
- **Advertising identifier:** free tier only, for ad delivery and fraud prevention

Analytics and crash reports **never contain the contents of your health data** — your medicine names, measurements and journal notes are not included.

### 3.6 Device permissions

| Permission | Used for | If you decline |
|---|---|---|
| **Camera** | Photographing medicine packaging, scanning barcodes | You can pick a photo from your library or add the medicine manually |
| **Photos** | Choosing medicine/profile photos from your library | The App keeps working |
| **Notifications** | Medication reminders and caregiver alerts | You will not receive reminders — this is the App's core function |
| **Tracking (iOS only)** | Personalised advertising | Ads are shown non-personalised |

All permissions are optional and can be revoked at any time in your device settings.

---

## 4. Purposes and legal bases

| Purpose | Legal basis |
|---|---|
| Account creation and authentication | Performance of a contract |
| Setting and delivering medication reminders | Explicit consent (health data) |
| Storing and syncing health data across devices | Explicit consent |
| Sharing with caregivers | Explicit consent |
| Subscription purchase and validation | Performance of a contract |
| Advertising (free tier) | Legitimate interest / consent (for personalised ads) |
| Debugging, crash analysis, security | Legitimate interest |
| Meeting legal obligations | Legal obligation |

---

## 5. Third parties we share data with

We **do not sell** your data and do not share it with third parties for marketing. The following processors are used so the App can function:

| Provider | What is shared | Purpose |
|---|---|---|
| **Google Firebase** (Authentication, Firestore, Storage, Cloud Functions, Remote Config) | Account details, health data, photos | Data storage and cross-device sync |
| **Google Firebase Analytics** | Screen views, event names, device info | Usage statistics |
| **Google Firebase Crashlytics** | Stack traces, device info, user identifier | Crash detection and resolution |
| **Google Cloud Vision** | **Photo of medicine packaging** (only when you run a scan) | Reading text on the package (OCR). The photo is sent to Google for this |
| **Google AdMob** | Advertising identifier, approximate (country-level) location, device info | Ad delivery (**free tier only**) |
| **RevenueCat** | Anonymous user identifier, purchase receipt | Verifying subscription status |
| **Apple App Store / Google Play** | Purchase information | Processing payment. **Your card details never reach us** |
| **Expo Push Service** | Push token, notification text | Delivering caregiver notifications |

Each provider receives only the data required for its own function. All of your health data is stored solely in Firebase and is not passed to the other providers.

### International transfers

Firebase and the other services are operated by Google LLC and your data may be stored on servers outside your country. Our database region is `[FIRESTORE REGION]` and our server functions run in Europe (`europe-west1`). Transfers rely on your explicit consent and on Google's Standard Contractual Clauses.

---

## 6. Advertising

Ads are shown through Google AdMob in the free tier.

- **Ads are removed entirely when you subscribe to Premium.**
- Users in the EU and UK are shown Google's consent form (UMP) for ad personalisation.
- On iOS you are asked for tracking permission when the App opens. If you decline, ads are not personalised.
- You can change your ad preferences at any time in device settings (Android: Settings → Google → Ads / iOS: Settings → Privacy → Tracking).
- **Your health data is never used for ad targeting and is never shared with ad networks.**

---

## 7. Retention

- Your data is retained for as long as your account exists.
- When you delete your account, all of your health data (medicines, measurements, journal entries, family profiles and account details) is **permanently deleted**.
- Crash reports and aggregated (de-identified) analytics are retained for up to 14 months under the provider's retention policy.
- Records we are legally required to keep (e.g. invoicing records) are retained for the period required by law.

---

## 8. Your rights

Under GDPR and KVKK you have the right to:

- **Know** whether your personal data is being processed
- **Request information** about that processing
- **Learn** the purpose of processing and whether it is used accordingly
- **Know** the third parties to whom data is transferred, domestically or abroad
- Have **inaccurate or incomplete data corrected**
- Request **erasure or destruction** of your data
- Obtain a **portable copy** of your data
- **Withdraw your consent**
- **Object** to decisions produced solely by automated analysis that adversely affect you
- **Claim compensation** if you suffer damage

### How to exercise them

| Right | In the App |
|---|---|
| Correct your data | Edit directly on the Account and profile screens |
| Get a copy of your data | Settings → PDF Health Report |
| **Delete your account and all data** | **Account → Delete My Account** (irreversible) |
| Stop caregiver sharing | Remove the link on the Caregiver screen |
| Turn off notifications | Settings → Notifications |

For anything else, write to **destek@periyodoz.com**. We respond to requests within **30 days**.

You also have the right to lodge a complaint with your national data protection authority (in Turkey: the Personal Data Protection Authority, kvkk.gov.tr).

---

## 9. Security

- All data in transit is encrypted with **TLS/HTTPS**.
- Data is stored encrypted at rest.
- Server-side security rules technically enforce that **each user can access only their own data**. It is not possible for one user to read or write another user's data.
- Caregiver access is validated on the server, not on the client.
- Your password is managed by Google Firebase Authentication and is never visible to us.
- When you sign out on a device, all data belonging to that account is removed from the device.

No system is completely secure. In the event of a breach affecting your data, we will notify you and the relevant authority within the timeframes required by law.

---

## 10. Children's privacy

The App is **not directed at children under 13** and does not knowingly collect data directly from children.

Parents may create sub-profiles for their children. In that case the child's health data is entered **by the parent or guardian and under their responsibility**. If you believe a child's data has been entered without your consent, contact destek@periyodoz.com and we will delete it promptly.

---

## 11. Subscriptions

Premium subscriptions are purchased through the App Store or Google Play and renew automatically.

- Your store account is charged when the purchase is confirmed.
- Unless you cancel at least 24 hours before the period ends, the subscription renews at the same price.
- You can manage or cancel it in your store account settings.
- **Your payment details (card number, etc.) never reach us** — payment is handled entirely by Apple/Google. We only receive whether the subscription is active.

---

## 12. Changes to this policy

We may update this policy from time to time. When a material change is made, we will notify you in the App and update the "Last updated" date above. Continuing to use the App after a change means you accept the updated policy.

---

## 13. Contact

For any privacy question, request or complaint:

**Email:** destek@periyodoz.com
**Data controller:** `[DATA CONTROLLER]`
**Address:** `[ADDRESS]`
