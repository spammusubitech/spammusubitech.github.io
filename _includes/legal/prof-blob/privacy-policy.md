# Privacy Policy for Prof Blob

Last updated: September 10, 2026

This Privacy Policy explains how Spam Musubi Technologies LLC handles information when You use Prof Blob. References to Prof Blob may include Blob, the `blob-screen-time` app, widgets, app extensions, public pages, support materials, or similar names used for the Service.

Prof Blob helps You create a short cognitive pause before opening selected apps. Screen Time selections, math-gate history, unlock timers, rules, focus sessions, emergency passes, widget snapshots, streaks, and progress summaries are primarily stored on Your Device and, depending on Your Apple and iCloud settings, may sync or back up through Apple services.

## Android App: blob: screen time control

The Android version is also named **blob: screen time control**. References below to Apple's Screen Time APIs, iOS app extensions, iCloud, App Tracking Transparency, or AdServices describe the iOS version. The Android version uses the following services and controls instead:

- **Usage Access:** With Your permission, Android usage events and summaries provide app package names, usage times, and opening counts for local screen-time statistics and selected-app limits.
- **AccessibilityService:** After an in-app disclosure and Your explicit permission in Android Settings, Blob observes window-change events to identify when a selected app opens and displays its math gate. The service is configured not to retrieve window contents. It does not read screen contents or collect typed text, perform taps or typing in other apps, or change Android settings for You. You may disable the service in Android Settings.
- **On-device storage and backups:** Selected app packages, settings, onboarding responses, gate history, pass and cooldown state, focus sessions, and progress use Android preferences and a local Room database. Depending on Your device and backup settings, Android may include this data in cloud backup or device transfer. Android backup is separate from iCloud sync.
- **Analytics:** PostHog receives app interaction and gate events, experiment assignments, settings changes, purchase-flow events, a generated app-user identifier, and technical app/device information. Selected-app analytics use a shortened hash of the package name, rather than the raw package name or app display name. These hashes are pseudonymous; they should not be treated as anonymous. Raw Android usage reports, screen contents, and typed text are not sent as product analytics.
- **Purchases:** Google Play processes Android payments. RevenueCat processes app-user identifiers, Play transaction and subscription information, entitlement status, offerings, restoration requests, and related technical data to provide purchase services. We do not receive Your full payment-card details or Google account credentials.
- **Notifications and widgets:** If permitted, Android displays local reminders and temporary-pass status notifications. Widgets read local summary information. Delivery and refresh timing depend on Android and device settings.
- **Advertising measurement:** Meta's SDK sends app-install and app-activation signals with technical app/device information. The app provides RevenueCat with Meta's app-generated anonymous identifier and available Google advertising identifiers for matching subscription activity to advertisements. RevenueCat may send trial starts, paid subscription starts, trial conversions, renewals, purchase amounts and currency to Meta, including while the app is closed. Free trials are reported separately from paid subscriptions. Android advertising-ID availability follows Your Google/device settings; Apple's App Tracking Transparency does not apply to Android. This integration does not forward protected-app selections, raw usage reports, math answers, gate history, or the PostHog event stream to Meta. The app does not request camera, microphone, or precise-location access.

Google may process downloads, purchases, subscription management, backups, device transfers, and diagnostics under its own policies and Your Google/device settings. Manage Android subscriptions in Google Play; uninstalling Blob does not cancel a subscription. Clearing app storage or uninstalling removes local app data, subject to backups. It does not automatically delete records held by Google, RevenueCat, PostHog, Meta, or Us. The contact and data-request process below also applies to Android users; do not send Google account credentials.

## Interpretation and Definitions

### Interpretation

Capitalized words have the meanings defined below. These definitions apply whether the words appear in singular or plural form.

### Definitions

For this Privacy Policy:

- **Application** means Prof Blob, the software program provided by the Company.
- **Application Store** means the Apple App Store or any other digital distribution service through which You downloaded the Application.
- **Company** means Spam Musubi Technologies LLC, 3400 Cottage Way, Ste G2 #11929 Sacramento, California 95825. The Company may also be referred to as "We," "Us," or "Our."
- **Country** refers to California, United States.
- **Device** means any device that can access or run the Service, such as an iPhone, iPad, or other compatible device.
- **In-app Purchase** means a purchase of a product, feature, service, or Subscription made through the Application and handled by the Application Store.
- **Personal Data** means information that relates to an identified or identifiable individual.
- **Service** means the Application and the features made available through it, including app extensions and widgets.
- **Service Provider** means a person or company that processes information on Our behalf or helps Us provide the Service.
- **Subscription** means paid access to premium features of the Service offered on a recurring basis.
- **Usage Data** means information collected automatically about use of the Service or the Device environment.
- **You** means the individual accessing or using the Service, or the company or other legal entity on whose behalf that individual is accessing or using the Service.

## Information We Collect

### Information You Provide

You may provide information when You use or contact Us about the Service, including:

- Support messages, email address, and other contact details if You contact Us.
- Onboarding choices, such as which apps feel distracting, when distraction usually happens, what You want more time for, and Your estimated daily phone use.
- Settings and preferences, such as unlock duration, challenge difficulty, cooldown duration, escalation sensitivity, daily goals, Hard Hours, Focus Hours, daily time or open limits, Strict Mode, emergency passes, reflection reminders, and notification preferences.
- Purchase-related choices, such as which Subscription or In-app Purchase You select, as processed through the Application Store and Our purchase provider.

### Screen Time, Protected Apps, and Usage Information

Prof Blob uses Apple's Screen Time APIs, including FamilyControls, DeviceActivity, and ManagedSettings, to provide app protection and progress features. Depending on Your permissions and choices, the Application may process:

- Screen Time authorization status.
- App, category, or web-domain selections You choose to protect.
- System-provided app tokens and app display names for protected apps.
- Protection state, unlock-pass state, emergency protection pause state, base challenge level, active schedules, Hard Hours or Focus Hours settings, daily limits, open limits, Strict Mode status, and rule configuration.
- DeviceActivity summaries, such as app display names, bundle identifiers when available, usage minutes, pickup counts, and daily or weekly usage summaries.

Screen Time data is used to run the Service, show progress, and apply Your protection rules. We do not receive Your full Apple ID credentials, full Application Store account credentials, or full payment details through Screen Time.

### Math Gate, Focus, Progress, and Streak Information

Prof Blob may store or process information about gate and focus activity, including:

- When a gate appears, is solved, is abandoned, results in a walk-away, uses an emergency unlock, or grants an unlock pass.
- Failed attempts, cooldowns, unlock duration, challenge level, challenge text, timestamps, session identifiers, and app display names or app tokens associated with the gate.
- Focus session start and end times, planned duration, completion status, focused minutes, and related challenge-level changes.
- Interceptions, solved gates, walk-aways, repeated opens, streaks, estimated time avoided, daily scores, top app summaries, pass reflections, and similar progress metrics.

This information is used to provide the gate ritual, adjust difficulty, run Focus Mode, show progress, update widgets, and support analytics about Your intentional app use.

### Widgets, App Extensions, and Shared Data

Prof Blob includes app extensions for Screen Time shields, activity reports, device activity monitoring, shield actions, and Home Screen widgets. These extensions may read or write limited data through the app group shared with the main Application, such as protected app tokens, pending gate state, unlock-pass state, notification state, protection pause state, today's interception and walk-away counts, streak timestamps, and widget snapshots.

Widget snapshots may include summary values such as daily score, screen time minutes, pickups, interceptions, solved gates, walk-aways, current streak, and a high-level state used to choose widget styling. Widgets are designed to show glanceable summaries and do not create a separate user account.

### Device Permissions and Notifications

The Application may request Screen Time authorization, notification permission, and Apple's App Tracking Transparency permission for advertising measurement. Permission choices are controlled through Your Device settings. Declining tracking permission does not prevent You from using Prof Blob or purchasing a Subscription.

If notification permission is granted, the Application can schedule local notifications, such as gate prompts, reflection reminders, or subscription trial renewal reminders. Notification content and delivery are handled by Your Device and Apple notification services.

The current iOS build is designed around local notifications and does not register You for marketing push notifications.

### Analytics, Feature Flags, and Diagnostics

The Application may use PostHog for product analytics and feature flags. Analytics events may include event names and properties such as app display name, challenge level, unlock duration, open count, gate outcome, failed-attempt events, emergency-pass events, protection-pause events, focus-session events, session identifier, paywall and offering metadata, feature flag values, app version, Device model, operating system version, approximate location derived from network information, and similar technical metadata.

We use analytics to understand whether the Service works, improve onboarding, gates, focus sessions, widgets, settings, and paywalls, evaluate feature flags, diagnose issues, and measure aggregate product usage. We do not send raw DeviceActivity reports to PostHog, but some gate analytics events may include protected app display names and gate metadata.

Apple may provide developers with App Store analytics, crash reports, performance diagnostics, purchase records, and similar information according to Your Apple settings and Apple's policies. This information may include aggregated usage metrics, crash logs, Device model, operating system version, region, and diagnostic details.

### Payment and Subscription Information

If You make an In-app Purchase or purchase a Subscription, payment is processed by the Application Store. We do not receive or store Your full payment card number, billing card security code, or full Application Store account credentials.

The Application uses RevenueCat to help manage purchases, Subscriptions, entitlements, offerings, purchase restoration, and fraud prevention. RevenueCat may process purchase identifiers, entitlement status, app user identifiers, Device identifiers, AdServices attribution information, Application Store transaction information, IP address, Device and app metadata, and related diagnostics as needed to provide purchase services.

### Advertising Measurement

Prof Blob uses Meta's SDK and RevenueCat's Meta integration to measure whether advertisements lead to app installs and paid Subscriptions. Meta's SDK sends app-install and app-activation signals, together with technical app and Device information such as app version, operating system information, network information, and app/device identifiers as permitted by Your settings. Advertising identifier (IDFA) collection is enabled only when Apple's App Tracking Transparency permission is authorized.

With authorized tracking permission, the Application provides RevenueCat with Meta's app-generated anonymous identifier and available advertising identifiers for matching subscription activity to advertisements. RevenueCat may send trial starts, trial conversions, paid subscription starts, renewals, other purchases, transaction identifiers, purchase amounts, currency, and associated attribution identifiers to Meta. Free trial starts are reported separately from paid Subscriptions. Our current RevenueCat integration requires authorized tracking consent for this delivery. Subscription events can be processed while the Application is closed, based on the consent information available to RevenueCat.

This advertising integration does not forward Your protected-app selections, raw Screen Time reports, math answers, or gate history to Meta. It does not forward Our PostHog event stream to Meta.

You can change tracking permission in Your Device's Settings under Privacy & Security > Tracking. Reopening Prof Blob refreshes the consent information shared with RevenueCat. Changing this permission does not automatically delete information previously processed by Meta or RevenueCat. See "Deleting Your Information" below for requests concerning existing data. Meta's handling of information is also described in its [Privacy Policy](https://www.facebook.com/privacy/policy/).

### Camera, Microphone, and Precise Location

The current iOS build of Prof Blob is not designed to collect camera recordings, microphone recordings, or precise location data.

If these features are added in the future, We will update this Privacy Policy as appropriate.

## How We Use Information

We use information for the following purposes:

- To provide and maintain the Service.
- To request and manage Screen Time permissions.
- To protect selected apps, show shields, run math gates, grant unlock passes, manage emergency passes, manage protection pauses, and manage cooldowns.
- To generate math challenges, evaluate answers, adjust difficulty, and apply Hard Hours, Focus Hours, Focus Mode, Strict Mode, limits, or other rules.
- To show progress, streaks, analytics, usage summaries, top apps, focus summaries, widget snapshots, daily scores, and estimated time avoided.
- To save Your app settings and preferences.
- To schedule and deliver local notifications.
- To process, verify, restore, or support In-app Purchases and Subscriptions.
- To provide product analytics, feature flags, diagnostics, and performance improvements.
- To measure advertising effectiveness and subscription conversions, subject to the permissions and choices described above.
- To respond to Your support requests.
- To comply with legal obligations and enforce Our Terms.
- To protect the rights, safety, and security of users, the Company, and others.

## How Information Is Stored

Protected app selections, rules, gate events, progress history, streaks, usage summaries, onboarding choices, focus sessions, emergency-pass state, widget snapshots, and settings are primarily stored on Your Device using local storage such as Core Data and UserDefaults, including storage shared with Prof Blob's app extensions through the app group.

Depending on Your Device settings, Apple account settings, backup settings, and Application configuration, some Application data may be included in iCloud backups or synced through Apple's CloudKit or other iCloud services. We do not operate a separate cloud service for storing raw Screen Time reports.

## Sharing of Information

We may share information in the following situations:

- **With Apple and Application Store services:** Apple may process information related to app downloads, Screen Time authorization, protected-app controls, DeviceActivity reports, ManagedSettings shields, app extensions, widgets, notifications, iCloud backup or sync, diagnostics, purchases, subscriptions, refunds, and App Store analytics.
- **With RevenueCat:** RevenueCat helps Us manage purchases, Subscriptions, entitlements, offerings, purchase restoration, attribution, and related diagnostics.
- **With PostHog:** PostHog helps Us understand product usage, run analytics, and evaluate feature flags.
- **With Meta:** Meta receives app-install, app-activation, and advertising-measurement information as described above. RevenueCat may send subscription events and matching information to Meta when the consent requirements of Our integration are met.
- **With Service Providers:** We may use providers for support, email, hosting, diagnostics, purchase validation, analytics, feature flags, or similar operational needs.
- **For legal reasons:** We may disclose information if required by law or in response to valid legal requests from public authorities.
- **To protect rights and safety:** We may disclose information when We believe it is necessary to protect the Company, users, the public, or the Service.
- **For business transfers:** Information may be transferred in connection with a merger, acquisition, financing, reorganization, sale of assets, or similar business transaction.
- **With Your consent:** We may share information for another purpose if You consent.

We do not sell Personal Data for money. The advertising measurement described above involves sharing information with Meta and matching it with information from Meta's services. Depending on applicable law, this may be considered sharing for cross-context behavioral advertising. You can decline or withdraw tracking permission in Your Device settings and contact Us about applicable opt-out rights.

## Retention

Information stored locally in the Application remains on Your Device until You delete it, erase it through an available app control, or uninstall the Application, subject to Device backups or iCloud behavior.

Support emails and related correspondence may be retained as long as needed to respond to You, maintain business records, resolve disputes, comply with legal obligations, and enforce Our agreements.

Purchase records are retained by the Application Store and RevenueCat according to their policies. We may retain limited purchase or entitlement records as needed to provide the Service, restore purchases, comply with law, and prevent fraud.

Analytics and diagnostic records may be retained by Us or Our Service Providers for as long as reasonably needed for the purposes described in this Privacy Policy.

## Deleting Your Information

You can delete local Application data by using available app controls, deleting individual records where supported, revoking Screen Time access, disabling widgets, or deleting the Application from Your Device.

Deleting the Application may not delete information stored by Apple, such as App Store purchase history, Screen Time permissions, iCloud backups, diagnostics, or subscription records. You can manage Apple data through Your Apple account and Device settings.

To request access, correction, or deletion of Personal Data held by Us or processed by providers on Our behalf, email contact@spammusubitech.com with the subject "Prof Blob data request". Describe Your request and provide only information needed to locate the relevant records, such as a support correspondence email or an app/customer identifier if You have it. Do not send passwords, complete payment-card information, or Apple Account credentials. We may ask for information needed to verify and fulfill the request, and may need to retain certain information when required or permitted by law.

Deleting the Application does not cancel an active Subscription; manage subscriptions through Your Apple Account settings. Information independently held by Apple or Meta may also be subject to those providers' own privacy controls and retention obligations.

## Security

We use reasonable measures designed to protect information handled by the Service. However, no method of electronic storage or transmission is completely secure, and We cannot guarantee absolute security.

You are responsible for maintaining the security of Your Device, Apple account, backups, Screen Time settings, and Device passcode or biometric protections.

## Children's Privacy

The Service is not directed to children under 13. We do not knowingly collect Personal Data from anyone under 13. If You believe a child under 13 has provided Us with Personal Data, please contact Us and We will take appropriate steps to delete it.

If You are under the age of majority where You live, You may use the Service only with permission from a parent or legal guardian.

## International Transfers

The Company is located in the United States. If You contact Us or if information is processed by Our providers, information may be transferred to and processed in the United States or other countries where privacy laws may differ from those where You live.

We take reasonable steps to handle information in accordance with this Privacy Policy.

## Your Privacy Rights

Depending on where You live, You may have rights to request access to, correction of, deletion of, or information about Personal Data We process about You.

Because much of Prof Blob's Screen Time, gate, focus, widget, and progress data is stored locally on Your Device or with Apple services, We may not have access to it. You can manage local data through the Application and Device controls.

To exercise rights for information You have provided directly to Us or information processed by Our Service Providers on Our behalf, contact Us at the email address below.

## Links to Other Websites

The Service may contain links to websites or services not operated by Us. We are not responsible for the content, privacy policies, or practices of third-party websites or services. Review the privacy policy of any third-party service You use.

## Changes to This Privacy Policy

We may update this Privacy Policy from time to time. We will update the "Last updated" date when changes are made. If a change is material, We will make reasonable efforts to provide notice through the Service or another appropriate method.

Changes are effective when posted or otherwise made available.

## Contact Us

If You have questions about this Privacy Policy, You can contact Us by email at contact@spammusubitech.com.
