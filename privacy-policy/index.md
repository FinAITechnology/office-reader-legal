# Privacy Policy - Office Reader

**Last Updated:** February 2026  
**Note:** This policy reflects the current state with Firebase Analytics, Crashlytics, and Cloud Messaging enabled.

## Introduction

Office Reader ("we," "our," or "the app") is committed to protecting your privacy. This Privacy Policy explains how we handle your information when you use our document viewing and PDF tools application.

## Information Collection and Use

### Personal Information
Office Reader is designed as an **offline-first, privacy-focused** application. We do NOT collect, transmit, or store any **personal documents or files** on external servers. All your documents remain stored locally on your device only.

**Analytics Data:** We collect anonymized, technical data through Firebase Analytics and Crashlytics to improve app performance and stability. This data does NOT include any personal documents or user-identifiable data.

### Data Storage
All your document data is stored **locally on your device only**:
- Opened and scanned documents
- Reading history and favorites
- Application preferences (theme, language, font size)
- Document metadata (file names, paths, timestamps)

### Data Collection and Sharing
**What We DO NOT Collect or Share:**
- ❌ Your documents or file contents (PDF, Word, Excel, PowerPoint, etc.)
- ❌ Personal identification information (name, email, phone number)
- ❌ User-entered text or annotations
- ❌ Display advertisements
- ❌ Require account registration for core features

**What We DO Collect (Anonymized Technical Data Only):**
- ✅ App usage analytics (screen views, feature interactions) - via Firebase Analytics
- ✅ Crash reports and error logs - via Firebase Crashlytics
- ✅ Device information (device model, OS version, app version) - anonymized
- ✅ Device identifiers (Firebase installation IDs) - anonymized
- ✅ App performance metrics - for debugging and improvement
- ✅ Push notification tokens - via Firebase Cloud Messaging

**Important:** All collected data is:
- **Anonymized** - no personal identification
- **Technical only** - no document content
- **Used for app improvement** - stability, performance, bug fixes
- **Shared only with Google** - as Firebase service provider
- **NOT used for advertising** - or marketing purposes

## Permissions

### Required Permissions

1. **Storage Access / All Files Access (Android)**
   - Purpose: Scan, discover, open, and manage documents across all storage directories
   - Scope: Access to documents in Downloads, Documents, external SD cards, and other directories
   - Data: Document files are processed entirely on your device and never uploaded

2. **Camera Permission**
   - Purpose: Document scanner feature to capture and convert paper documents to PDF
   - Scope: Only when user explicitly uses the scan feature
   - Data: Photos are processed locally on your device using ML Kit
   - Usage: Images are NOT transmitted. Scanned PDFs are saved locally on your device only.

3. **Internet Permission**
   - Purpose: Google Drive integration, crash reporting, analytics, in-app updates, and push notifications
   - Scope: Required for cloud features and app improvement services
   - Data: Only anonymized analytics data is transmitted (no documents)

4. **Notification Permission (Android 13+)**
   - Purpose: App update notifications and feature announcements
   - Scope: Opt-in on Android 13+
   - Data: Push notification tokens are managed by Firebase Cloud Messaging

**Important:**
- Camera permission is optional and only requested when you use the scanner feature
- All document processing happens locally on your device - no files are sent to external servers
- Google Drive access requires explicit Google Sign-In authorization by the user

## Google Drive Integration

When you connect your Google Drive account:
- ✅ Authentication is handled directly by Google Sign-In (we never see your password)
- ✅ We only access files you explicitly choose to open
- ✅ We do not store your Google credentials
- ✅ Downloaded files are processed locally on your device
- ✅ You can disconnect your account at any time from the Settings screen
- ✅ You can revoke access at any time from your Google Account settings

## Data Security

### Local Data Protection
- All documents are processed and stored locally on your device
- Application data is stored using Room Database and DataStore (encrypted preferences)
- All network connections use HTTPS encryption
- No cloud synchronization of documents or user data to our servers
- Data is protected by your device's built-in security mechanisms (file system permissions, device lock screen, PIN, biometric authentication, etc.)

### Your Responsibility
Since all documents are stored locally:
- **YOU** are responsible for backing up your important documents
- **YOU** should protect your device with a strong passcode
- Documents will remain on your device if you uninstall the app, but app preferences and history will be lost

## Data Retention and Deletion

### Data Retention
- **Local Document Data**: Retained on your device until you delete it. This data is never transmitted or stored on external servers.
- **Analytics Data**: 
  - **Firebase Analytics**: Retained according to Google's data retention policies (typically up to 14 months). Data is automatically deleted after the retention period.
  - **Firebase Crashlytics**: Retained for crash analysis and debugging purposes. Crash reports are kept to help us identify and fix issues.
  - You can request deletion of your analytics data at any time by contacting us at thuthao.finai@gmail.com

### Data Deletion
You can delete all your app data by:
1. Using the "Clear Cache" option in Settings
2. Clearing app data in device settings
3. Uninstalling the application

This will permanently delete all reading history, favorites, and app preferences from your device.

## User Rights
You have the right to:
- ✅ **Access your data**: All data is accessible within the app
- ✅ **Delete your data**: Clear app data, use Clear Cache in Settings, or uninstall
- ✅ **Control consent**: GDPR consent can be changed at any time (for EEA users)

**Local Data:** All your documents and app data are stored locally on your device and can be deleted by clearing app data or uninstalling the app. This data is never transmitted to external servers.

**Analytics Data:** If you want to request deletion of analytics data collected by Firebase Analytics or Crashlytics, please contact us at thuthao.finai@gmail.com. We will process your request within 30 days. Note that analytics data is anonymized and does not contain any personal or document information.

## Children's Privacy
Office Reader does not knowingly collect information from children under 13. The app is designed for general document viewing purposes.

## Changes to Privacy Policy
We may update this Privacy Policy periodically. Changes will be posted in this document with an updated "Last Updated" date. Continued use of the app after changes constitutes acceptance of the updated policy.

## Third-Party Services

### Analytics and Crash Reporting
Office Reader uses **Firebase Analytics** and **Firebase Crashlytics** (provided by Google) to collect anonymized technical data for app improvement purposes.

**Firebase Analytics:**
- **Purpose**: Understand how users interact with the app to improve user experience
- **Data Collected**:
  - App usage events (screen views, feature interactions, button clicks)
  - Device information (device model, OS version, app version) - anonymized
  - Anonymized usage patterns and trends
- **What is NOT Collected**:
  - ❌ Document contents (PDF, Word, Excel, etc.)
  - ❌ User-identifiable information (name, email, phone number)
  - ❌ Any data entered by users in the app
- **Data Usage**: Used only for improving app features, understanding user needs, and enhancing overall app experience
- **Data Sharing**: Data is processed by Google (Firebase service provider) but is NOT shared with other third parties
- **Data Retention**: Up to 14 months (Google's standard retention policy)

**Firebase Crashlytics:**
- **Purpose**: Identify and fix app crashes and errors to improve stability
- **Data Collected**:
  - Crash reports and error logs (technical data only)
  - Stack traces and error messages
  - Device information for debugging (device model, OS version) - anonymized
- **What is NOT Collected**:
  - ❌ Personal information or document data
  - ❌ User-entered content
  - ❌ Sensitive information
- **Data Usage**: Used only for debugging, crash analysis, and improving app stability
- **Data Sharing**: Data is processed by Google (Firebase service provider) but is NOT shared with other third parties
- **Data Retention**: Retained for crash analysis and debugging purposes

**Firebase Cloud Messaging:**
- **Purpose**: Deliver push notifications for app updates and feature announcements
- **Data Collected**: Device push notification tokens (anonymized)
- **Data Usage**: Used only for delivering relevant notifications to users

**Important Privacy Guarantees:**
- ✅ All collected data is **anonymized** and **aggregated**
- ✅ **NO document content** is ever collected or transmitted
- ✅ **NO user identification** information is collected
- ✅ Data is used **ONLY** for app improvement (stability, performance, bug fixes)
- ✅ Data is **NOT shared** with third parties except Google (as Firebase service provider)
- ✅ Data is **NOT used** for advertising, marketing, or any commercial purposes
- ✅ Your documents remain **100% local** on your device

### Other Third-Party Services
- **Google Sign-In & Drive API**: Used for optional Google Drive integration. Authentication is handled by Google. We do not store your Google credentials.
- **Google ML Kit**: Used for on-device text recognition (OCR) in the document scanner. All processing happens locally.
- **Google UMP (User Messaging Platform)**: Used for GDPR consent management for users in the European Economic Area.

Office Reader does NOT use:
- ❌ Advertising networks
- ❌ User tracking or profiling services
- ❌ Third-party data brokers

## Open Source Libraries
Office Reader uses the following key libraries:
- **Jetpack Compose** (Google) - Modern UI framework
- **Room Database** (Google) - Local database for document metadata
- **DataStore** (Google) - Encrypted preferences storage
- **PDFium** - PDF rendering engine
- **Apache POI** - Office document processing (Word, Excel, PowerPoint)
- **Readium** - EPUB reading library
- **ML Kit Text Recognition** - OCR for document scanning (processes locally)
- **CameraX** - Camera access for document scanning
- **Coil** - Image loading

**Important:** These libraries operate locally and do not transmit document data to external servers. OCR processing happens entirely on your device.

**Firebase Services:**
- **Firebase Analytics** - Collects anonymized app usage data (see Analytics section above)
- **Firebase Crashlytics** - Collects crash reports for debugging (see Analytics section above)
- **Firebase Cloud Messaging** - Push notification delivery
- **Firebase Performance** - App performance monitoring (anonymized)
- **Firebase Remote Config** - Feature configuration

## Compliance
Office Reader complies with:
- ✅ **GDPR** (General Data Protection Regulation - EU) - via Google UMP consent management
- ✅ **CCPA** (California Consumer Privacy Act - USA)
- ✅ **Google Play Store Data Safety** requirements

## Contact Information
If you have questions or concerns about this Privacy Policy or data practices:

**App Name:** Office Reader - Document Viewer & PDF Tools  
**Developer:** TechLead Development Team  
**Email:** thuthao.finai@gmail.com  
**Website:** https://github.com/thuthaofintech

## Summary
**🔒 Your Privacy Guarantee:**

**Your Documents:**
- ✅ 100% stored locally on your device
- ✅ Never transmitted to external servers
- ✅ Never collected by analytics services
- ✅ You have complete control over your files
- ✅ Can be managed anytime through the app

**Analytics Data (Firebase):**
- ✅ Only anonymized technical data collected
- ✅ NO document content collected
- ✅ NO user-identifiable information collected
- ✅ Used ONLY for app improvement (stability, performance, bug fixes)
- ✅ Shared ONLY with Google (Firebase service provider)
- ✅ NOT used for advertising or marketing
- ✅ You can request deletion at any time

**Key Points:**
- Your documents are **100% private and local**
- Analytics data is **anonymized and technical only**
- **NO personal or document data** is ever collected or shared
- All data collection is **transparent and disclosed** in this policy
- You have **full control** over your data

---

**Office Reader** - Document Viewer & PDF Tools  
*Your documents, your device, your control.*
