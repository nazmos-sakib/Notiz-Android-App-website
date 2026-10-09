---
layout: default
title: Privacy Policy
nav_order: 2
permalink: /privacy-policy/
description: Privacy Policy for the Notiz Android application
---

<div class="policy-hero">
  <p class="eyebrow">Notiz for Android</p>
  <h1>Privacy Policy</h1>
  <p class="lede">Notiz is an offline-first note-taking app. Your notes stay on your device unless you choose to use account synchronization.</p>
  <p class="effective-date">Effective August 25, 2026 · Last updated October 9, 2026</p>
</div>

<aside class="plain-language" aria-labelledby="summary-title">
  <h2 id="summary-title">Privacy at a glance</h2>
  <ul class="feature-grid">
    <li><strong>Local by default</strong><span>You can use the core app without creating an account.</span></li>
    <li><strong>No ads or tracking</strong><span>Notiz has no advertising SDK and does not perform behavioral tracking.</span></li>
    <li><strong>Optional cloud sync</strong><span>Cloud notes synchronize with our self-hosted server in Germany.</span></li>
    <li><strong>You control deletion</strong><span>Delete individual notes or your online account from within the app.</span></li>
  </ul>
</aside>

This Privacy Policy explains how Notiz ("Notiz," "we," "us," or "our") handles information when you use the Notiz Android application. It applies to local app features, optional account features, synchronization, and related support requests.

## Who is responsible

Notiz is operated by an independent individual developer, not a registered company. The developer is responsible for the processing described here (the data controller).

**Controller name: [Full legal name required before publication]**

**Contact address: [Confirm applicable public contact/address details before publication]**

Privacy and deletion contact: [{{ site.privacy_email }}](mailto:{{ site.privacy_email }}).

## 1. Information we process

### Information stored locally

Notiz stores notes, labels, formatting, checklists, preferences, selected images, drawings, and audio recordings in the app's private storage on your device. Other apps cannot normally access this private storage. Some settings may remain specific to one device.

Notiz accesses images and files only after you choose them using Android's system picker or import feature. It does not scan your photo library and does not request broad storage access. Selected attachments are copied into the app's private storage.

### Optional account information

If you create an account, our self-hosted Parse authentication service processes information such as:

- Your email address and display name;
- A password credential handled by the authentication service, or Google sign-in information if you choose that method;
- Account identifiers, authentication method, and session tokens.

We use this information to create and secure your account, keep you signed in, provide password recovery, maintain your profile, and provide synchronization.

### Synchronized content

If you sign in and enable synchronization, Notiz transmits account data and selected app content to the cloud. This can include notes, labels, formatting, checklists, archive and deletion status, images, audio recordings, drawings, attachment metadata, and the technical data required to reconcile changes across devices.

Notes kept only on your device are separate from cloud notes. When signed in, you can add notes to Cloud, including through the local-note migration control. Cloud notes synchronize automatically when the service and network are available, including through scheduled background work. Choosing **Move to this device** keeps a local note and queues removal of its cloud copy for the next successful synchronization; it does not immediately remove the server copy while offline.

### Google sign-in

If you choose Google sign-in, Google authenticates you and the app uses your Google account identifier, email address, display name, and an ID token to sign in to the Notiz backend. Notiz does not receive your Google password. Google processes information for its sign-in service under its own [Privacy Policy](https://policies.google.com/privacy).

### Support correspondence

When you email us, we receive your email address, message, and any information you choose to include. We use these to answer questions, verify account ownership where necessary, and handle privacy or deletion requests. The support mailbox is provided by Gmail. Do not send passwords, session tokens, or private note content.

### Technical information

Service infrastructure may process network addresses, object identifiers, timestamps, app and request information, authentication events, error codes, and server logs to operate, secure, troubleshoot, and prevent abuse of the synchronization service. Notiz does not automatically upload note content to a separate analytics service.

The app also keeps local sync diagnostics: attempt and success timestamps, uploaded/downloaded item counts, and error categories. These diagnostics are not automatically sent to a separate analytics service and can be cleared from the account controls or by clearing app data.

## 2. Microphone, images, and files

Notiz requests microphone permission only when you choose to record audio. Recording occurs locally and is not started in the background. If synchronization is enabled, a saved recording may be uploaded as part of its note. You may deny or revoke microphone access; other note features will continue to work.

Images and files are accessed only when you select or import them. Android grants Notiz access to the item you chose. Notiz does not request access to browse your entire media library.

## 3. Why we process information

We process information only as needed to:

- Provide local note-taking, attachment, backup, and restore features;
- Create, authenticate, secure, and administer optional accounts;
- Synchronize content across devices at your request;
- Detect errors, prevent abuse, and protect the service and its users;
- Respond to privacy, security, and support requests; and
- Meet applicable legal obligations.

Where applicable law requires a legal basis, processing necessary to provide account and synchronization features is based on performing our service agreement with you. Security and service reliability may rely on our legitimate interests, and legally required processing relies on the applicable obligation. Device permissions and optional features remain under your control.

## 4. Hosting, service providers, and international processing

The Notiz backend is a self-hosted Parse server located in Germany and operated by the developer. Account information and synchronized content are sent to this server. Back4App is not the hosting provider for this release.

Google sign-in, when selected, and our Gmail support mailbox involve Google services. Hosting the Notiz backend in Germany does not mean that information processed by these services stays exclusively in Germany. See Google's [Privacy Policy](https://policies.google.com/privacy) and [international data-transfer information](https://policies.google.com/privacy/frameworks).

**Before publication:** confirm any infrastructure provider with access to server data, outbound account-email provider, backup locations, and applicable contractual or international-transfer arrangements. These deployment details have not yet been finalized in this notice.

Notiz does not sell personal information. It does not include advertising SDKs or intentionally share information for cross-context behavioral advertising.

## 5. Sharing, export, and import

When you use Android's Share feature, selected content is sent to the app or recipient you choose. Their handling of that content is governed by their own terms and privacy practices.

Export creates a ZIP archive containing notes, labels, formatting, and attachments. Exported ZIP files are **not additionally encrypted**, so store and transfer them securely. Import reads a ZIP archive you select and merges its supported content into local app storage. Sharing, export, and import are initiated by you and are separate from cloud synchronization.

Android automatic cloud backup and device-transfer backup are disabled by the app configuration. Use the app's export feature to create a separate backup you control.

## 6. Security

We use HTTPS for data in transit, authenticated sessions, and per-user access controls intended to limit synchronized content to its owner. Attachment files are encrypted by the app with AES-256-GCM before upload. The account-specific key is held separately in an owner-restricted backend record, so a direct attachment file URL exposes encrypted bytes. This protects attachment storage but is not end-to-end encryption against the backend operator because the backend can access the account key.

Note titles, text, labels, and other structured note fields do not receive the app-level attachment encryption described above. They are transmitted over HTTPS and stored as backend records accessible to the server operator.

No storage or transmission method is completely secure. Protect your device and password, and sign out on devices you no longer control.

## 7. Retention and deletion

Local content remains until you delete it, clear Notiz's app data, or uninstall the app. Items placed in Trash remain recoverable until permanently deleted.

Synchronized content generally remains while your account is active. Permanently deleting an item removes its local record and, when synchronization is active, queues deletion of the synchronized copy and attachments that are no longer referenced by another note. Signing out or uninstalling Notiz does not delete your online account.

You can request permanent deletion of your online account and synchronized application data from the account controls in Notiz or by email. Export anything you wish to keep first. Successful account deletion removes the account, synchronized profile, notes, labels, attachment content and account attachment key. It does not erase local copies on your devices or exported/shared files.

Deletion can remain pending if file cleanup fails or an interrupted or older upload needs administrator attention. A failed or pending attempt is not confirmation that all data has been erased. Contact us if deletion cannot be completed. See the [account deletion instructions]({{ '/account-deletion/' | relative_url }}).

### Records retained after account deletion

The current backend retains restricted deletion-control records indefinitely, with no automatic expiry. These include the deleted account identifier, upload tokens and file locators, request/check/completion timestamps, and cleanup status or error state. They are retained to block stale writes, identify late uploads, and retry cleanup. Completed cleanup records do not contain note bodies or attachment bytes; retaining a file locator does not mean the file itself remains stored. These records are accessible only through privileged backend operations.

### Logs, server backups, and correspondence

**Retention details pending before publication:** operational-log rotation, any server-backup retention, and support/request correspondence retention have not yet been established. No fixed deletion period is promised for these categories in this draft. The developer must define and implement periods or meaningful retention criteria, including any necessary legal exceptions, before publishing this notice.

## 8. Your choices and rights

You may:

- Use Notiz locally without creating an account;
- Choose whether to synchronize your content;
- Deny or revoke optional device permissions;
- Export your notes and attachments;
- Correct your account profile information;
- Delete individual content or your online account; and
- Request access, correction, deletion, restriction, objection, or portability where provided by applicable law.

You may also lodge a complaint with your local data-protection authority. We may need to verify your identity before fulfilling an account-related request. Where GDPR applies, requests must be answered without undue delay and normally within one month of receipt. If a permitted extension is necessary because of complexity or the number of requests, we will explain it within that month. This response period is not a promise that every technical deletion finishes instantly.

## 9. Children

Notiz is not directed to children below the minimum age required to consent to an online service in their country. Do not create an account if you cannot legally consent without a parent or guardian. Contact us if you believe a child supplied account information improperly.

## 10. Changes to this policy

We may update this policy when Notiz's features, service providers, or legal obligations change. We will update the date above and, when appropriate, present material changes in the app or on this site.

## 11. Contact

For privacy questions, rights requests, or account-deletion assistance, email [{{ site.privacy_email }}](mailto:{{ site.privacy_email }}). You do not need to reinstall the app to request account deletion.

Please do not include passwords, authentication tokens, or private note content in a support request.

<p class="legal-note">Local release draft: complete the marked identity, provider, and retention details and verify the production configuration before publication.</p>

