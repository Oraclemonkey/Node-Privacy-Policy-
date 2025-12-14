Privacy Policy for Node
Last Updated: December 14, 2024 Effective Date: December 14, 2024

Introduction
Node ("we," "our," or "the app") is committed to protecting your privacy. This Privacy Policy explains how Node handles your information when you use our iOS application.

Key Point: Node does NOT collect, transmit, or store any personal data on external servers. All data remains on your device.

Information We Do NOT Collect
Node does NOT collect, transmit, or sell:

Personal information (name, email, phone number)

Location data

Browsing history

Payment information

Health data

Contact lists

Photos or media

Device identifiers for tracking purposes

Analytics or usage statistics sent to servers

Information Stored Locally on Your Device
Node stores the following data locally on your device only using iOS's secure local storage (such as UserDefaults or a local database):

1. App Configuration Data
Focus Modes: Names and app selections for your custom focus modes.

Break Settings: Your selected break difficulty level.

NFC Chip Identifier: A unique identifier for your registered NFC chip/tag.

Purpose: To verify you're using the same physical chip for tap in/out.

Storage: Local only.

Deletion: Automatically deleted when you reset your NFC chip in settings.

2. Usage Statistics
Focus Time: Minutes spent in focus mode.

Session Data: Start/end times of focus sessions.

Streak Data: Count of consecutive days with minimum focus time.

Break Usage: Number of breaks taken during sessions.

Historical Data: Past focus time data used for charts and insights.

Purpose: To display your progress, insights, and motivate continued use. Storage: Local only, never transmitted to servers or third parties.

3. Onboarding & Settings
Onboarding completion status.

Selected commitment goals.

Notification preferences.

Authorization status for Family Controls.

iOS Family Controls & Screen Time API
Node uses Apple's Family Controls framework to enable app blocking functionality.

What This Means:
Restricted Access: The app uses the ManagedSettings and DeviceActivity frameworks provided by Apple.

Display Only: Usage data shown in the Insights tab is rendered using Apple's DeviceActivityReport. Node's code cannot "read" or export the specific content of your browsing history or app usage; it simply asks the operating system to display the chart.

No Storage: We do NOT store, process, or transmit Screen Time data off your device.

Apple's Control: All Screen Time data remains under Apple's strict privacy protections.

Your Control: You grant/revoke access through iOS Settings > Screen Time.

App Blocking:
Node uses ManagedSettings to temporarily restrict selected apps.

Blocking applies only to apps YOU select.

You control when blocking is active (via NFC tap or timer).

NFC (Near Field Communication)
How We Use NFC:
Reading Only: Node reads the Unique ID (UID) of the NFC tag when you tap.

Verification: This UID is compared against the one stored locally on your device to unlock or lock a session.

No Transmission: NFC data never leaves your device.

No Tracking: We do not track your physical location via NFC.

Notifications
If you enable notifications:

Local Only: All notifications are generated locally on your device by the app.

Content: Streak achievements, timer completion, and milestone reminders.

Control: You can enable/disable in iOS Settings > Notifications > Node.

We do NOT send push notifications from external servers.

Third-Party Services
Node does NOT use:

Analytics services (no Google Analytics, Firebase, Mixpanel, etc.)

Advertising networks

Crash reporting tools that transmit personal data

Social media SDKs

Cloud storage services

100% of Node's functionality runs entirely on your device.

Data Security
How Your Data is Protected:
Local Storage: All data is stored in the iOS app sandbox, accessible only by Node.

iOS Encryption: Data is protected by your device's passcode/biometric authentication (FaceID/TouchID).

No Network Transfer: No data is ever transmitted over the internet by Node.

Your Responsibility:
Keep your device secure with a passcode.

Keep iOS updated for the latest security patches.

Your Rights & Choices
Access Your Data:
All your data is visible within the app via the Insights tab and Settings menu.

Delete Your Data:
You can delete your data by:

Reset NFC Chip: In Settings > Reset NFC Chip.

Delete App: Uninstalling Node permanently deletes ALL local data associated with the app.

iOS Reset: Settings > General > Reset > Reset All Settings.

Note: Since we do not have servers, if you delete the app, we cannot restore your data. It is gone forever.

Children's Privacy:
Node is not intended for children under 13, but because it collects no personal data, it is safe for all ages. We do not knowingly collect personal information from children. If you are a parent or guardian and believe your child has provided us with personal information, please contact us, though technically impossible as we have no servers to receive it.

International Users (GDPR & CCPA):
Node is available worldwide. By using Node, you acknowledge that:

GDPR (EU): We act as the Data Controller. However, as we do not collect or process data outside your device, your data remains under your physical control at all times.

CCPA (California): We do not sell your data. We do not collect your personal data.

Contact Us:
If you have questions about this Privacy Policy or Node's privacy practices, please contact us.

Developer: Aashir Khiani Email: nodefocusapp@gmail.com

Changes to This Policy
We may update this Privacy Policy from time to time. When we do, we will update the "Last Updated" date at the top of this page. Significant changes regarding data collection (if any ever occur) will be prominently announced within the app.

App Store Privacy Details
For the purpose of Apple's App Store Privacy Details (Privacy Nutrition Labels):

Data Used to Track You:

None

Data Linked to You:

None

Data Not Linked to You:

None

Note: While the app stores usage data (focus time), it is stored locally and not collected by the developer, therefore it does not need to be declared as "collected" data in App Store Connect.
