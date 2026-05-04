# Privacy Policy

**App Name:** BreakfastBuddy (早餐圖)
**Last Updated:** 2026-05-04
**Effective Date:** 2026-05-04

Welcome to BreakfastBuddy. We respect your privacy. This policy explains what data we collect, why we collect it, how we use it, and what rights you have.

---

## 1. Who We Are

This App is provided by **YU-HSUAN PAI**.
If you have any questions about this policy, please contact us:

- In-app: **Settings → Contact Support**
- Email: **iflabs.support@gmail.com**

---

## 2. What Data We Collect

### 2.1 Information You Provide

| Category | Content | Source |
| --- | --- | --- |
| Account identifier | Email, display name, Apple/Google user ID | When you sign in with Google or Apple |
| Personal preferences | Age (integer; stored locally and shown as age group), language, share-to-community toggle, hide-watermark toggle | When you enter them in Settings |
| Meal images | Photos you take or pick from your library to be recognized | When you use the "Make Breakfast Image" flow |
| Community content | Images you publish to the community feed, comments, likes, reports you submit | When you post |
| Support messages | Free-text messages, category, your email | When you submit through Contact Support |

### 2.2 Information We Collect Automatically

| Category | Content | Purpose |
| --- | --- | --- |
| Device info | OS (iOS / Android), language, platform identifier | Service compatibility, support debugging |
| AI conversation logs | Your prompt text, the AI model's recognition output, timestamps, your user ID | Debugging, quality improvement, abuse detection |
| Violation records | If our system flags your input as violating our terms, we record your user ID, email, input, and AI response | Detecting and preventing abuse, account suspension if necessary |
| Subscription state | Your plan (free / paid), the source, last update timestamp | Unlocking paid features, cross-device sync |

We do **not** collect precise GPS location, contacts, call logs, SMS, browser history, and we do **not** silently track you across devices.

### 2.3 Subscription and Purchase Data

Subscriptions and purchases are processed by **Apple App Store** or **Google Play**. We do **not** see your credit card or payment details.
We use a third-party subscription management service, **RevenueCat**, to receive subscription events (initial purchase, renewal, expiration). These events may include:

- Your Firebase user ID (used to map events to your account)
- Subscription product identifier
- Subscription status and expiration date

---

## 3. How We Use Your Data

We use your data only for the following purposes:

1. **Provide the core service**: sign-in, food image recognition, saving and displaying your breakfast images, community posting, paid feature unlocking.
2. **Quality improvement and debugging**: analyzing whether AI recognition is accurate; fixing bugs.
3. **Abuse detection and safety**: identifying repeated violations; suspending accounts or hiding community content when necessary.
4. **Support and contact**: replying to your support messages; sending you operationally relevant notifications.
5. **Legal compliance**: responding to lawful requests from authorities.

We do **not** sell your personal data to third parties, and we do **not** use it for cross-app behavioral advertising.

---

## 4. Third-Party Services

We use the following trusted third-party services to operate this App. Each has its own privacy policy:

| Service | Provider | Purpose | Privacy Policy |
| --- | --- | --- | --- |
| Firebase Authentication | Google LLC | User sign-in | https://firebase.google.com/support/privacy |
| Cloud Firestore | Google LLC | Storing conversation logs, community posts, user state | https://firebase.google.com/support/privacy |
| Cloud Storage for Firebase | Google LLC | Storing community images | https://firebase.google.com/support/privacy |
| Cloud Functions for Firebase | Google LLC | Backend APIs, webhooks | https://firebase.google.com/support/privacy |
| Google Sign-In | Google LLC | OAuth sign-in | https://policies.google.com/privacy |
| Sign in with Apple | Apple Inc. | OAuth sign-in | https://www.apple.com/legal/privacy/ |
| Gemini API | Google LLC | Food image recognition | https://ai.google.dev/gemini-api/terms |
| RevenueCat | RevenueCat, Inc. | Cross-platform subscription management | https://www.revenuecat.com/privacy |

---

## 5. Where We Store Data and How Long We Keep It

- **Storage location**: Google Cloud (Firestore / Storage). Actual data centers are managed by Google and may be located in the United States or other countries.
- **Retention**:
  - Account data: retained until you delete your account.
  - AI conversation logs and violation records: kept for **at least 12 months** for abuse detection and quality tracking; may be deleted or anonymized afterwards.
  - Community posts and comments: kept until you delete them; auto-hidden if they exceed the report threshold.
  - Subscription state: retained until you delete your account.

---

## 6. Data Security

- All transmissions between the App and our servers are encrypted via HTTPS / TLS.
- Firestore security rules enforce that users can only read/write their own data; support messages and violation records are write-only from the client (clients cannot read them).
- The Gemini API key is stored only on the server, never bundled in the App.
- Subscription state is written exclusively by RevenueCat webhooks on the server. The App client **cannot** modify its own plan.

That said, no transmission or storage system can be 100% secure.

---

## 7. Your Rights

You may at any time:

1. **Access and modify** your personal data through Settings (language, age, community share toggle, etc.).
2. **Delete community content**: long-press or use the detail screen to delete your own posts / comments.
3. **Block other users** to stop seeing their content.
4. **Cancel subscriptions** via the subscription management page in your Apple App Store or Google Play account.
5. **Delete your account**: email **iflabs.support@gmail.com** with your deletion request. We will process within **30 business days** and delete or anonymize your personal data.

If you reside in a jurisdiction protected by GDPR, CCPA, or similar data protection laws, you may also have rights such as data portability and the right to object. Please contact us to exercise those rights.

---

## 8. Children's Privacy

This App is **not intended for children under 13** (or the equivalent minimum age in your jurisdiction), and we do not knowingly collect their data. If we become aware that a child under 13 has provided us with personal data, we will delete it immediately.
If you are a parent and believe your child has provided us with information, please contact us.

---

## 9. International Data Transfers

Some of the services we use (Firebase, Gemini, RevenueCat) operate outside Taiwan, primarily in the United States. By using this App, you understand and consent to your data being transferred to and processed in those regions in accordance with applicable laws.

---

## 10. Changes to This Policy

When we make material changes, we will announce them in the App and update the "Last Updated" date at the top of this page. Please review periodically. If a change affects how we process your data, we will use a more prominent notice.

---

## 11. Contact Us

For any questions about this policy, or to exercise the rights described above, please contact:

- **Email: iflabs.support@gmail.com**
- **In-app: Settings → Contact Support**
