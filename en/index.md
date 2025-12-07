---
layout: default
title: UNOES Dictionary Privacy Policy
---

# 📄 UNOES Dictionary Privacy Policy

This privacy policy explains how UNOES Dictionary (hereinafter referred to as "this app" or "we") collects and handles user information through this app.

**Last Updated: 2025-12-03**

### 1. Information We Collect and How We Use It

This app collects and uses the following information to provide services, improve the app, deliver advertisements, and ensure security.

| Type of Information | Collection Method | Purpose of Use |
| :--- | :--- | :--- |
| **Account Information** | When users log in | Identifying service users, providing login functionality, managing subscription status, and synchronizing data. |
| **Personal Identification Information** | When logging in with Google/Email | **Google Account**: Google User ID, name, email address (profile images are not currently collected). **Email Login**: Email address, password hash. |
| **Authentication Information** | When logging in | JWT tokens, ID tokens (for Google authentication), client fingerprint. Managing authentication state and ensuring security. |
| **Subscription Information** | When purchasing a subscription | Purchase token, plan ID, subscription status, start date/time, expiration date/time, cancellation date/time. Managing subscriptions and granting access rights. |
| **Payment Information** | When purchasing a subscription | Managing and processing user subscription plan purchases and granting service access. (※Payment processing is handled by **Google Play Store**, and we do not directly store sensitive information such as credit card numbers.) |
| **Advertising Identifier** | When displaying ads | Advertising identifier (Ad ID) from Google AdMob. Displaying ads based on user interests and measuring ad effectiveness. |
| **Usage Information** | When using the app | API request logs (request path, method, status code, response time), crash reports, performance data. Improving services, developing new features, and handling issues. ※**Dictionary search history is not saved.** Searches are processed in real-time, and search content is not stored on the server. |
| **Device Information** | When using the app | Device type, OS version, language settings, platform information (Android/Web), client IP address, User-Agent. Ensuring service stability, handling issues, user support, and ensuring security. |
| **Log Information** | When making API requests | Request method, path, query parameters, status code, response time, client IP address, User-Agent, request/response headers (controllable via environment variables). Service operation, security monitoring, and issue investigation. |

### 2. Subscriptions and Payment Information

This app offers subscription plans for monetization.

* When users purchase a subscription, actual payment processing is handled through Google Play Store.
* We **do not directly collect or store sensitive payment information such as credit card numbers or bank account information.** We only receive information necessary to manage subscriptions, such as transaction status, purchased product ID, and expiration dates.

### 3. About Advertising

This app implements advertising through a third-party ad network (**Google AdMob**) to generate revenue.

* This app displays the following types of ads:
  * **Banner Ads**: Ads constantly displayed at the bottom of the app screen
  * **Interstitial Ads**: Full-screen ads displayed during screen transitions
  * **Rewarded Ads**: Reward-based ads that remove ads for 24 hours after viewing
* The ad network (Google AdMob) may collect and use information using **advertising identifiers (Ad ID)**, cookies, and other technologies to display ads based on user interests.
* This information collection and use is conducted in accordance with Google AdMob's privacy policy (https://policies.google.com/privacy).
* Users can reset or disable advertising identifiers from their device settings.

### 4. Third-Party Information Sharing

This app does not share users' personal identification information with third parties except in the following cases:

1. When required by law.
2. When sharing with service providers necessary for service maintenance (data analysis, server hosting, crash reporting, ad delivery) under confidentiality agreements, within the necessary scope.
3. When users have explicitly consented.

**Third-Party Service Providers:**
* **Google AdMob**: Ad delivery service (advertising identifiers, device information, etc.)
* **Google Play Store**: Subscription payment processing (payment information is directly processed by Google Play Store)
* **Google Sign-In**: Authentication service (Google account information)

### 5. Information Management and Security

We implement appropriate security measures and strictly manage information to prevent leakage, loss, destruction, or tampering of collected information.

**Security Measures:**
* User passwords are **hashed** and stored in a way that cannot be restored.
* Authentication uses **JWT (JSON Web Token)** with token expiration settings.
* API communications are encrypted using **HTTPS**.
* Log information is controllable via environment variables, and sensitive information (passwords, tokens, etc.) is not recorded in logs.
* Database access is appropriately restricted.

### 6. User Rights

Users have the following rights regarding their information held by us:

* **Right to Disclosure**: You can request disclosure of personal information held by us.
* **Right to Correction**: You can request correction of incorrect personal information.
* **Right to Deletion**: You can request deletion of personal information.
* **Right to Suspension of Use**: You can request suspension of use of personal information.
* **Data Portability**: You can request provision of personal information.

Please contact us at the contact information listed at the end of this policy. We will respond within a reasonable period.

**Notes:**
* Account deletion may also delete subscription information. Refunds for subscriptions follow Google Play Store policies.
* Log information is stored for a certain period and may be used for security monitoring and issue investigation.

### 7. Data Retention Period

We retain personal information for the following periods:

* **Account Information**: Until the account is deleted or until a deletion request is made by the user
* **Subscription Information**: During the period the subscription is valid, and for the retention period required by law
* **Log Information**: For the period necessary for security monitoring and issue investigation (usually within 90 days)
* **Authentication Tokens**: Until the token expiration (usually from a few hours to a few days)

### 8. Changes to This Policy

We may revise this policy due to changes in laws or services. If there are significant changes, we will notify you within the app or on this app's website. If you continue to use this app after changes, you are deemed to have agreed to the revised privacy policy.

### 9. Contact Information

For questions, inquiries, or requests regarding personal information related to this policy, please contact us at:

* **Developer Name:** UNOES
* **Contact Email:** unoesjapan@gmail.com
* **Website:** https://seijishii.github.io/unoes-dictionary-policy/

**Last Updated: 2025-12-03**

---

**Language / 言語:**
- [English](./index.md) | [日本語](../ja/index.md)

