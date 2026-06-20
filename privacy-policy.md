# Privacy Policy

**Last updated:** 20 June 2026

**Blank Page Digital Ltd** (“we,” “us,” or “our”) operates the **Zora** mobile application (the “App”) on iOS and Android. This Privacy Policy explains how we collect, use, store, share, and protect personal data when you use Zora.

For users in the United Kingdom, we are the **data controller** for personal data processed through the App under the UK General Data Protection Regulation (UK GDPR) and the Data Protection Act 2018.

By signing in and using the App, you acknowledge this Privacy Policy. If you do not agree, do not use the App.

This policy should be read with our [Terms of Service](https://zora-izi.github.io/Zora-Documents/terms-and-conditions).

---

## 1. Personal data we collect

We collect only what we need to run Zora: tracking, sync, subscriptions, and automated insights.

### 1.1 Account and identity

Zora does not use email-and-password sign-up. You sign in with:

- **Apple** (iOS), or
- **Google** (Android).

We receive:

- a unique account identifier from that provider;
- your name and email (if the provider shares them).

If you use Apple’s Hide My Email, we may receive a relay address instead of your personal email. We do not receive or store your Apple or Google password.

### 1.2 Profile and onboarding

During setup you may provide:

- date of birth (used on your device for calculations; we may store age on our servers);
- gender, height, weight, activity level, and display name;
- an optional profile photo (stored on our servers if you choose one, so it can sync across reinstalls).

### 1.3 Wellness data you log in the App

Depending on how you use Zora, we may process:

- nutrition entries (manual logs, barcode lookups, text descriptions);
- food photos you upload for automated nutrition estimates;
- weight, water intake, fasting plans and sessions;
- daily feel or similar subjective check-ins;
- usage records related to nutrition search and AI features (for rate limits and abuse prevention).

### 1.4 Health platform data (on your device)

If you grant permission, Zora reads data from **Apple Health** (iOS) or **Health Connect** (Android), such as sleep, heart rate, heart rate variability, activity, workouts, VO₂ max, respiratory rate, and wrist temperature (where available).

On iOS, when Apple Health reports menstrual flow data and you have granted permission, Zora may use it as optional context for readiness metrics (for example HRV and resting heart rate). We do not provide full cycle-sync coaching.

**We do not upload your full Apple Health or Health Connect history to our database.** With your permission, we may write certain summaries back to those platforms (for example, daily nutrition totals).

Apple and Google control their own health services under their privacy policies and permission settings.

### 1.5 Automated insights (AI)

Zora uses third-party AI services (including **Google Gemini**) to:

- estimate nutrition from photos and text you submit; and
- generate short readiness, sleep, strain, stress, and recovery explanations (“coach” text) from summaries of your metrics (for example sleep duration, heart rate trends, or workout strain).

In production, these requests are usually sent through our servers so API keys stay secure. Do not put medical secrets in free-text fields you send for AI processing.

### 1.6 Technical data

We may process:

- a random installation identifier on your device (not your phone’s hardware serial number);
- app version, platform (iOS/Android), and server request timestamps;
- IP address for security, rate limiting, and fraud prevention.

---

## 2. How we use your data

We use personal data to:

- create and secure your account;
- sync your profile and logs across devices linked to the same sign-in;
- calculate and show wellness metrics and trends;
- run AI features you request;
- manage Zora Pro subscriptions (via app stores and RevenueCat);
- prevent abuse, enforce limits, and fix bugs;
- comply with law and respond to support requests.

### Legal bases (UK / EEA)

Where UK or EEA law applies, we rely on:

- **Contract** — to provide the App you signed up for;
- **Consent** — where you grant health permissions or use optional AI features;
- **Legitimate interests** — security, fraud prevention, and improving the service, balanced against your rights.

Health-related data may be special category data under UK/EU law. We process it only where we have a valid legal basis (often your explicit consent through App permissions and use of health features).

### We do not sell your data

We do not sell, rent, or share your personal data with advertisers or data brokers. We do not use your health or wellness logs for advertising, credit scoring, insurance underwriting, or employment screening.

---

## 3. Who we share data with

We share data only as needed to run the App:

| Recipient | Purpose |
|-----------|---------|
| **Apple** | Sign in with Apple, App Store purchases, HealthKit (if you enable it) |
| **Google** | Sign in with Google, Play purchases, Health Connect (if you enable it), Gemini AI processing |
| **RevenueCat** | Subscription and entitlement status |
| **Edamam** | Nutrition database lookup (via our backend) |
| **USDA FoodData Central** | Generic food nutrition lookup (via our backend) |
| **Open Food Facts** | Barcode product lookup (barcode number only; no account ID) |
| **Railway** | Encrypted hosting of synced account data and API services |
| **Resend** | Delivering support emails you send to us |

Each provider processes data under its own terms and privacy policy. We require service providers to protect data and use it only for our instructions, where contractually possible.

**AI providers:** We send content you submit (photos, text, and metric summaries for coach features) to Google for processing. We do not use your data to train our own models. Third-party AI providers have their own data practices—see Google’s policies for Gemini/API use.

---

## 4. Storage, security, and retention

### 4.1 Where data is stored

- **On your device** — logs, health permissions, and cached content.
- **Our servers** — account profile, synced logs, and related records, transmitted over encrypted connections (TLS) when cloud sync is enabled. Our backend uses **MongoDB** hosted via **Railway**. Servers may be located outside the UK/EEA (for example in the United States). Where required, we use appropriate safeguards (such as standard contractual clauses) for international transfers.

### 4.2 While you use the App

We keep your data while your account is active and as needed to provide the service.

If your complimentary access period ends and you do not subscribe, the App may lock access, but we retain your data so you can restore it if you subscribe later, unless you delete your account.

### 4.3 After you delete your account

You may delete your account in the App (**Settings → Delete account**) or at **https://zora-izi.github.io/Zora-Documents/delete-account**.

Deletion removes your data from our active systems, including profile, nutrition, weight, water, fasting, daily feel, and related usage records.

On your device, most local data is cleared. We may keep a non-personal installation identifier and basic display preferences (such as theme) so a future install can work.

**Subscriptions:** Deleting your account does not cancel Zora Pro. Cancel in Apple or Google subscription settings.

### 4.4 Backups and logs

Deleted data may remain in encrypted backups or system logs for a limited time before automatic overwrite. We aim to remove backup copies within **30 days**, unless a longer period is required by law or security needs.

---

## 5. Your rights and choices

### 5.1 Permissions

You can change Apple Health or Health Connect permissions in your device settings at any time. Some features will not work without them.

### 5.2 Access, correction, and deletion

Depending on where you live, you may have the right to:

- access your personal data;
- correct inaccurate data;
- delete your data;
- restrict or object to certain processing;
- portability (receive a copy in a usable format); and
- withdraw consent where processing is based on consent.

To exercise these rights, contact **hello@blankpagedigital.app**. We may need to verify your identity. Deletion options are in Section 5.3.

### 5.3 Account deletion

**In the App:** Settings → Delete account → verify with the same sign-in you used (Apple on iOS, Google on Android).

**Cross-platform:** An Apple account usually cannot be deleted from the Android App, and a Google account usually cannot be deleted from the iOS App. Use **https://zora-izi.github.io/Zora-Documents/delete-account** instead.

**Without the App:** Use **https://zora-izi.github.io/Zora-Documents/delete-account** or email **hello@blankpagedigital.app** from the address linked to your account.

### 5.4 Complaints (UK)

If you are in the UK and believe we mishandled your data, you may complain to the Information Commissioner’s Office (ICO) at [ico.org.uk](https://ico.org.uk). We encourage you to contact us first so we can try to resolve your concern.

### 5.5 Other regions

Users in the EEA have similar rights under GDPR. California residents may have additional rights under the CCPA/CPRA (we do not sell personal information). Contact us for requests.

---

## 6. Children

Zora is for users **18 and older**. We do not knowingly collect personal data from anyone under 18. If we learn that we have, we will delete it and may close the account.

---

## 7. Security

We use technical and organizational measures appropriate to the data we hold, including encryption in transit, access controls, and rate limiting. No method of transmission or storage is 100% secure; we cannot guarantee absolute security.

---

## 8. Changes to this policy

We may update this Privacy Policy. We will change the “Last updated” date and post the new version at **https://zora-izi.github.io/Zora-Documents/privacy-policy**. For material changes, we may notify you in the App before they take effect. Continued use after the effective date means you accept the update, where the law allows.

---

## 9. Contact us

- **Email:** hello@blankpagedigital.app
- **Postal address:** Office 10033, 321-323 High Road, Chadwell Heath, Essex, RM6 6AX, United Kingdom

---

## 10. Related policies

- [Terms of Service](https://zora-izi.github.io/Zora-Documents/terms-and-conditions)
- [Privacy Policy](https://zora-izi.github.io/Zora-Documents/privacy-policy)
- [Account deletion](https://zora-izi.github.io/Zora-Documents/delete-account)

*This document is not legal advice. Have qualified counsel review it for your entity, hosting locations, AI subprocessors, and target markets before publication.*
