# Privacy Policy for Arrow Escape

**Effective Date:** November 22, 2026  
**Last Updated:** November 22, 2026  
**Application Name:** Arrow Escape (Arrow Escape - Tap & Untangle)  
**Package / Application ID:** `com.playsphere.arrowescape`  
**Contact Email:** [allgames9e@gmail.com](mailto:allgames9e@gmail.com)  

---

## 1. Introduction

Welcome to **Arrow Escape** (hereinafter referred to as *"Arrow Escape"*, *"the Game"*, *"the App"*, *"we"*, *"us"*, or *"our"*). Arrow Escape is a 2D grid logic puzzle game where players tap and untangle directional arrows through over 1,000 uniquely generated stages, daily challenges, and custom puzzles.

We place the utmost importance on your privacy and transparency. This Privacy Policy explains how information is handled when you download, install, play, or access **Arrow Escape** on Android devices, via Progressive Web App (PWA), or web platforms.

By downloading, installing, or playing Arrow Escape, you agree to the collection and use of information in accordance with this Privacy Policy. If you do not agree with any part of this policy, please do not use or access the Game.

---

## 2. Summary of Key Principles

* **No Personal Account Required:** You do not need to register with your real name, email address, phone number, or password to play.
* **No Selling of Personal Data:** We never sell, rent, or trade your personal information to any third party.
* **Local Storage First:** All campaign progression, high scores, level stars, sound preferences, and unlocked visual skins are stored locally on your device.
* **Family & Children Friendly:** The game is designed for all ages and strictly avoids collecting personal identifiable information from children.
* **Transparent Monetization:** The game does not feature real-money in-app purchases. Optional rewarded ads and non-intrusive ads are provided via Google AdMob.

---

## 3. Information We Collect

### A. Personal Information (What We DO NOT Collect)
We **do not** collect, store, or solicit any Personally Identifiable Information (PII), including but not limited to:
* First or last names
* Physical postal addresses
* Personal phone numbers
* Government-issued identification numbers
* Private photos, videos, or camera captures
* Microphone audio recordings
* Contacts or address books
* Biometric data or financial account credentials

### B. Automatically Generated & Gameplay Information
To ensure seamless gameplay, leaderboard ranking, and game maintenance, the app processes the following pseudonymous and technical information:

1. **Anonymous Device Identifier (`device_id`):**
   * A pseudonymous identifier generated locally upon first launch (e.g., `dev_1732304856789_abcdef`).
   * This identifier is purely randomized and is **not** tied to your hardware IMEI, MAC address, or Android ID.
   * It is used solely to maintain your anonymous leaderboard score and device synchronization.

2. **Player Handle / Gamertag (`player_name`):**
   * An anonymous gamer tag generated automatically (e.g., `Archer #4821`).
   * Players can edit this handle locally. We urge players not to use real names or personal information in their chosen gamertag.

3. **Gameplay Statistics & Progression:**
   * Cleared level index (from Stage 1 up to Stage 1,000).
   * Star ratings earned per level (1 to 3 stars based on lives preserved).
   * Total puzzles completed, combo counts, mistakes count, and daily streak records.
   * Virtual currency balance (*"Gold Coins"*), which are earned solely through gameplay and optional rewarded video ads.
   * Unlocked arrow visual palettes/skins (e.g., Obsidian Ink, Cyberpunk Neon, Sunset Coral, Emerald Matrix, Royal Gold).
   * Audio preferences (mute status and chosen sound design: Crisp Pop, Wood Tap, or Soft Tick).
   * Game grid density setting (Normal, Dense, Mega).

4. **Technical & Telemetry Data:**
   * Platform type (Android or Web/PWA).
   * Operating system version, user-agent string, and general device model category (e.g., Mobile / Desktop Browser) for compatibility verification and troubleshooting.
   * Application version (e.g., `1.0.0`) to check for mandatory or recommended maintenance updates.
   * Coarse timestamp of activity (`last_active_at`).

---

## 4. How We Use Collected Information

The information gathered is utilized strictly for the following purposes:
1. **Core Gameplay & State Preservation:** Keeping track of unlocked puzzle stages, star ratings, and custom settings across game sessions.
2. **Anonymous Global Leaderboards:** Displaying top player achievements, stars, and levels completed within the community leaderboard via Supabase.
3. **Advertising Operations:** Serving banner, app open, interstitial, and optional rewarded advertisements in compliance with Google AdMob policies.
4. **App Health & Maintenance:** Monitoring app stability, checking for service updates, and displaying maintenance status when required.
5. **Customer Support:** Resolving technical inquiries, bug reports, and feedback submitted directly to our support email at [allgames9e@gmail.com](mailto:allgames9e@gmail.com).

---

## 5. Device Permissions

Arrow Escape requests only the minimal necessary permissions required for its basic operation on Android:

| Permission Name | Android Identifier | Purpose |
| :--- | :--- | :--- |
| **Full Network Access** | `android.permission.INTERNET` | Required to communicate with Google AdMob for ad delivery, fetch updated policy configurations, and sync anonymous leaderboard scores via Supabase. |
| **View Network Connections** | `android.permission.ACCESS_NETWORK_STATE` | Used to detect offline status and display the in-game offline indicator gracefully when no internet is available. |

### Sensitive Permissions NOT Requested
Arrow Escape **DOES NOT** request:
* Camera (`android.permission.CAMERA`)
* Microphone (`android.permission.RECORD_AUDIO`)
* Location (`ACCESS_FINE_LOCATION`, `ACCESS_COARSE_LOCATION`)
* Read / Write Contacts (`READ_CONTACTS`, `WRITE_CONTACTS`)
* Read Phone State (`READ_PHONE_STATE`)
* Read / Write External Storage or Photos (`READ_EXTERNAL_STORAGE`, `READ_MEDIA_IMAGES`)
* SMS / Phone Call permissions

---

## 6. Third-Party Services & SDKs

Arrow Escape incorporates trusted third-party service provider SDKs to facilitate advertising, cloud data persistence, and native app runtime features:

### A. Google AdMob (Google LLC / Alphabet Inc.)
* **Role:** Advertising partner for Banner Ads, App Open Ads, Interstitial Ads, and Rewarded Video Ads (rewarding players with hints, extra lives/revive, or bonus virtual coins).
* **Information Handled:** Google AdMob may collect and process pseudonymous identifiers, such as the Google Advertising ID (GAID / AAID), IP address (for coarse geographic location and fraud prevention), device diagnostics, and ad interaction metrics.
* **Google Privacy Policy:** [https://policies.google.com/privacy](https://policies.google.com/privacy)
* **Google Ad Technologies:** [https://policies.google.com/technologies/ads](https://policies.google.com/technologies/ads)
* **Ad Personalization Controls:** You can reset or delete your Google Advertising ID or opt out of personalized ads at any time through your Android device settings:
  * **Android 12+:** Go to *Settings > Google > Ads > Delete advertising ID*.
  * **Earlier Android versions:** Go to *Settings > Google > Ads > Opt out of Ads Personalization*.
  * **Web browser controls:** Visit Google Ad Settings at [https://adssettings.google.com](https://adssettings.google.com).

### B. Supabase (Supabase, Inc.)
* **Role:** Secure cloud database backend used for:
  * Synchronizing global leaderboard scores (anonymous device identifier, chosen player name, score, level reached).
  * Remote policy retrieval (in-app "How to Play", "Privacy Policy", "Share", and "Rate Us" content updates).
  * Anonymous telemetry and maintenance status announcements.
* **Information Handled:** Anonymous device token, pseudonymous player name, app version, platform string, and score data. All requests are transmitted over encrypted HTTPS/TLS.
* **Supabase Privacy Policy:** [https://supabase.com/privacy](https://supabase.com/privacy)

### C. Capacitor (Ionic / Drifty Co.)
* **Role:** Open-source native runtime bridge converting the web puzzle application into an Android package.
* **Information Handled:** Standard operating system lifecycle events (app open, app pause, app resume). Does not independently collect or sell user data.

---

## 7. In-Game Economy & No Real-Money Transactions

* **Virtual Currency ("Gold Coins"):** Arrow Escape features an in-game virtual coin economy. Gold Coins can only be earned through solving campaign levels, daily challenges, or optionally watching rewarded video advertisements.
* **No Real-Money Purchases:** There are **NO in-app purchases (IAP)**, subscriptions, or credit card transactions in Arrow Escape.
* **No Cash Value:** Virtual coins and unlocked arrow skins hold no real-world monetary value and cannot be transferred, exchanged, or redeemed for physical currency or prizes.

---

## 8. Data Storage, Retention, and Deletion

### Local Data on Device
All game states—including cleared levels, star ratings, daily challenge history, high scores, coin count, unlocked themes, and audio settings—are stored locally in your browser storage or Android Web Storage (`localStorage`).

* **How to delete your local game data:**
  1. **Inside the Game:** Open the in-game **Settings** modal and tap **"Reset Progress"**.
  2. **Via Android Device Settings:** Navigate to *Settings > Apps > Arrow Escape > Storage > Clear Data / Clear Cache*. This will permanently remove all local progress and reset the app to factory condition.

### Cloud Leaderboard Data
Anonymous scores submitted to the leaderboard are retained to preserve community leaderboards. If you wish to delete your anonymous leaderboard record:
* Send an email to **[allgames9e@gmail.com](mailto:allgames9e@gmail.com)** with the subject line *"Leaderboard Data Deletion Request"*.
* Include your chosen anonymous in-game nickname or device identifier (accessible from the settings/leaderboard screen). We will promptly locate and delete any associated records from our cloud database.

---

## 9. Children’s Privacy (COPPA & Global Standards)

Arrow Escape is designed as an accessible, family-friendly logic puzzle suitable for players of all ages.

* **Compliance with COPPA (Children's Online Privacy Protection Act):** We do not knowingly collect, solicit, or maintain any personal information from children under the age of 13 (or under 16 in applicable European Union jurisdictions).
* **Child-Directed Advertising Protections:** Where applicable under Google Play Families Policy and COPPA guidelines, advertising requests can be flagged for child-directed treatment (`tagForChildDirectedTreatment`) or restricted to non-personalized, family-appropriate ads.
* **Parental Rights:** If you are a parent or legal guardian and believe that your child has provided any personal information to us, please contact us immediately at **[allgames9e@gmail.com](mailto:allgames9e@gmail.com)**. Upon verification, we will immediately purge such data from our systems.

---

## 10. Privacy Rights for Specific Jurisdictions

### A. European Economic Area (EEA) and United Kingdom (GDPR / UK GDPR)
If you reside within the European Economic Area or the United Kingdom, you possess specific statutory rights regarding your personal data:
* **Legal Basis for Processing:** We process pseudonymous data based on our *Legitimate Interests* (providing an enjoyable, secure, and functional puzzle game, preventing fraud, and maintaining leaderboards) and *Consent* (for personalized advertising, where provided through Google's consent dialogs).
* **Your Rights:**
  * **Right of Access:** You may request details on any data held concerning you.
  * **Right to Erasure / Deletion ("Right to be Forgotten"):** You have the right to request the deletion of your telemetry or leaderboard records.
  * **Right to Restrict or Object to Processing:** You may object to the processing of your data or opt out of targeted advertising via device settings.
  * **Right to Lodge a Complaint:** You have the right to lodge a complaint with your local Data Protection Supervisory Authority.

### B. California Residents (CCPA / CPRA)
Under the California Consumer Privacy Act (CCPA) and the California Privacy Rights Act (CPRA):
* **No Sale of Personal Information:** Arrow Escape does not sell personal information as traditionally defined under California law.
* **Right to Know and Delete:** You have the right to know what categories of data are collected and request their deletion.
* **Non-Discrimination:** You will not experience any discrimination, loss of gameplay features, or price differences for exercising your privacy rights.

To exercise any of these rights, please email us at **[allgames9e@gmail.com](mailto:allgames9e@gmail.com)**.

---

## 11. Data Security

We implement reasonable technical and organizational safeguards designed to protect your information against unauthorized access, destruction, loss, or alteration:
* All cloud communications between the app and backend services (Supabase, Google AdMob) utilize encrypted **HTTPS** and **WSS** (Transport Layer Security / TLS).
* Access to cloud management databases is restricted through secure authentication mechanisms and least-privilege administrative protocols.
* However, please note that no method of transmission over the internet or electronic storage is 100% impenetrable. While we strive to use commercially acceptable means to protect your information, absolute security cannot be guaranteed.

---

## 12. External Links and Third-Party Sites

The App may contain links to external sites, including:
* The Google Play Store rating page (`play.google.com`)
* Developer project resources on GitHub
* Third-party advertising destinations

We have no control over and assume no responsibility for the content, privacy policies, or practices of any third-party websites or services. We encourage you to review the privacy policy of every external website you visit.

---

## 13. Changes to This Privacy Policy

We may update our Privacy Policy periodically to reflect changes in our practices, legal requirements, app functionality, or third-party service features.

* When updates are made, the **"Last Updated"** date at the top of this document will be revised accordingly.
* Significant updates will be highlighted via in-app notices or through our remote policies configuration.
* We recommend checking this page periodically to remain informed about how we safeguard your data. Continued use of Arrow Escape following any changes indicates your acceptance of the revised Privacy Policy.

---

## 14. Contact Us

If you have questions, feedback, concerns, or requests regarding this Privacy Policy or our data practices, please reach out to us at:

* **Contact Email:** [allgames9e@gmail.com](mailto:allgames9e@gmail.com)
* **Application:** Arrow Escape (`com.playsphere.arrowescape`)
* **Developer / Publisher:** PlaySphere / Arrow Escape Team
