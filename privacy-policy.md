---
title: Privacy Policy
---

# Privacy Policy

**Last updated: July 11, 2026**

Servo ("we", "our", or "us") operates the Servo – NZ Fuel Prices mobile application (the "App"). This Privacy Policy explains how we collect, use, store, and protect your information when you use the App.

By using the App, you agree to the collection and use of information as described in this policy. If you do not agree, please do not use the App.

---

## 1. Information We Collect

### 1.1 Location Data
- **What**: Your device's precise location (latitude and longitude).
- **When**: Only while the App is in use and you have granted location permission.
- **Why**: To find nearby fuel stations, sort stations by distance, display your location on the map, and limit Widget results to your selected search radius. When you submit a price, the current coordinates may be sent with that submission for verification and abuse prevention.
- **Note**: Your last known location and selected search radius are stored locally in Servo's shared App Group so the Widget can calculate nearby results. You can use the App without granting location permission, but location-based features and nearby Widget results will be unavailable.

### 1.2 User Account Information
- **What**: Email address and display name (if you create an account).
- **When**: When you register or sign in via Email, Apple Sign In, or Google Sign In.
- **Why**: To enable personalised features such as favourite stations, fuel type preferences, and price submissions.

### 1.3 User-Submitted Content (UGC)
- **What**: Fuel prices you submit, including optional photos of price boards.
- **When**: When you choose to submit a price update.
- **Why**: To provide up-to-date fuel price information to all users. Servo first attempts OCR entirely on your device. If local recognition is not sufficient and you have not enabled the default AI setting, the App explains that the photo can be sent through our backend to **Google Gemini**. You may choose **Use AI This Time**, **Always Use AI**, or **Enter Manually**. **Always Use AI** saves a local preference so later photos that local recognition cannot read are sent for server AI processing automatically. You can also enable or disable this preference at any time in Profile. If you choose **Enter Manually**, the photo is not sent for server AI processing.
- **Photo storage**: Servo sends the resized JPEG in the authenticated recognition request and processes it in memory. Servo does not save a copy in Supabase Storage or associate the photo with the submitted price. The photo is not displayed publicly. Google processes the image under its own privacy terms as listed in Section 4.

### 1.4 Reports and Moderation Records
- **What**: Your account identifier, the station or specific displayed price you report, a fixed reason, an optional suggested price, and optional private details of up to 300 characters. We also retain a server-generated snapshot of the reported station or price so the report remains understandable if the public data later changes.
- **When**: When a signed-in user chooses **Report** on a station page, withdraws a report, or adds requested information.
- **Why**: To investigate inaccurate data, respond to the reporter, prevent abusive submissions, apply or reverse moderation actions, and maintain an audit record.
- **Visibility**: Other users and the price contributor cannot see your identity or private report details. Only the reporter can read the reporter-facing record; restricted operators can access the moderation queue and audit information.

### 1.5 Device and Usage Data
- **What**: Device model, operating system version, app version, diagnostics, and crash reports.
- **When**: Automatically during app usage.
- **Why**: To diagnose technical issues and improve app performance.

---

## 2. How We Use Your Information

We use the information we collect to:

- Display nearby fuel stations and prices
- Sort stations by distance from your location
- Enable user accounts and personalised features
- Process and display user-submitted fuel prices
- Receive, investigate, and respond to reports about prices or station information
- Prevent abusive price submissions and reports, and audit moderation actions
- Improve app performance and fix bugs
- Comply with legal obligations

We do **not** use your information for:
- Advertising or ad targeting
- Selling to third parties
- Behavioural profiling or tracking

---

## 3. Data Storage and Security

- **Backend**: Your data is stored on [Supabase](https://supabase.com), which uses Amazon Web Services (AWS) infrastructure with encryption at rest and in transit.
- **Region**: Data is stored in the AWS Seoul (ap-northeast-2) region.
- **Security**: We implement row-level security (RLS) policies to ensure users can only access their own data. All API communication uses HTTPS/TLS encryption.
- **Retention**: Account data is retained while your account is active. You may delete your account in the App at any time (see Section 6). Price observations may remain as anonymised community data. Reports and moderation audit records may also be retained after account deletion with the account identifier removed, for data integrity, abuse prevention, dispute handling, and legal or security obligations, and are removed or anonymised when no longer reasonably necessary.
- **AI photos**: Servo does not persist server-AI photos in its backend. The resized image exists only for the authenticated recognition request and is released when processing finishes or fails. Google Gemini's handling of the transmitted image is governed by Google's privacy terms.

---

## 4. Third-Party Services

We use the following third-party services:

| Service | Purpose | Privacy Policy |
|---------|---------|---------------|
| **Supabase** | Backend, authentication, database | [supabase.com/privacy](https://supabase.com/privacy) |
| **Apple Sign In** | Authentication | [apple.com/privacy](https://www.apple.com/privacy/) |
| **Google Sign In** | Authentication (via Supabase Auth) | [policies.google.com/privacy](https://policies.google.com/privacy) |
| **Google Gemini** | Optional AI-assisted fuel price recognition after one-time or remembered, revocable consent; Servo does not retain a backend copy of the transmitted photo | [policies.google.com/privacy](https://policies.google.com/privacy) |
| **Firebase Crashlytics** | Crash diagnostics and stability monitoring | [firebase.google.com/support/privacy](https://firebase.google.com/support/privacy) |
| **Apple Xcode Organizer** | Crash reporting and diagnostics | [apple.com/privacy](https://www.apple.com/privacy/) |

We do **not** use advertising SDKs, data brokers, or cross-app tracking.

---

## 5. Data Sources

Fuel prices displayed by Servo are structured observations submitted by Servo users. Station-directory information is maintained as operational reference data. Servo does not describe its fuel-price observations as official government price data.

---

## 6. Your Rights

Under the **New Zealand Privacy Act 2020**, you have the right to:

- **Access**: Request a copy of the personal information we hold about you.
- **Correction**: Request correction of any inaccurate personal information.
- **Deletion**: Delete your account in the App from Profile → About Servo → Account → Delete Account. You may also contact us for deletion support. Fuel prices may remain as anonymised community data. Reporter identifiers are removed from retained reports when the account is deleted; non-identifying report and audit data may remain for the purposes described in Section 3.

To exercise any of these rights, contact us at the address below. We will respond within 20 working days as required by the Privacy Act 2020.

---

## 7. Children's Privacy

The App is rated 4+ and does not knowingly collect personal information from children under 16. If you believe a child has provided us with personal information, please contact us and we will delete it promptly.

---

## 8. Changes to This Policy

We may update this Privacy Policy from time to time. We will notify you of any material changes by updating the "Last updated" date at the top of this page. Continued use of the App after changes constitutes acceptance of the updated policy.

---

## 9. Contact Us

If you have any questions about this Privacy Policy or wish to exercise your rights, please contact us at:

📧 **Email**: alex.pengfei.wang@gmail.com

---

*This privacy policy complies with the New Zealand Privacy Act 2020 and Apple's App Store Review Guidelines.*
