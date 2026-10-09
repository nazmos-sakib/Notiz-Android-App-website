---
layout: default
title: Delete your account
nav_order: 3
description: Instructions for deleting a Notiz account and synchronized data
permalink: /account-deletion/
---

<div class="policy-hero compact">
  <p class="eyebrow">Notiz account controls</p>
  <h1>Delete your account</h1>
  <p class="lede">Request deletion of your Notiz online account and synchronized data in the app or by email.</p>
</div>

## Delete your account in Notiz

1. Open **Notiz** and sign in to the account you want to delete.
2. Tap the **Profile** icon at the top right of the notes screen to open **Account**.
3. Scroll to **Danger zone** and select **Delete account**.
4. Review the warning and confirm deletion.

Account deletion is permanent. Export anything you want to keep before confirming.

## What is deleted

Successful account deletion removes the online account and its synchronized profile, notes, labels, attachment records, and stored attachment files. Deletion also invalidates the account's ability to sign in.

Account deletion does not wipe local copies on your current or other devices. Clear Notiz's storage in Android settings or uninstall it on each device if you also want to remove local app data. Exported ZIP files are controlled by you and must be deleted separately from wherever you saved or shared them.

## What remains and when deletion completes

Restricted deletion-control records remain indefinitely in the current backend: account identifiers, upload tokens/file locators, timestamps, and cleanup state. They help block stale writes and clean up late uploads. Completed receipts do not contain note bodies or file bytes. These records have no automatic expiry.

File cleanup failures, interrupted uploads, or older files needing administrator review can delay deletion. A pending or failed result is not confirmation of completed erasure. Contact us for help; do not assume signing out or uninstalling completes an outstanding deletion.

Log, server-backup, and correspondence retention still need to be finalized before publication, as marked in the privacy policy.

## Cannot access the app?

Email [{{ site.privacy_email }}](mailto:{{ site.privacy_email }}?subject=Notiz%20account%20deletion). You do not need to install or sign in to the app to send a request. State that you want to delete your Notiz account and provide the email address associated with it. We may ask you to verify ownership before acting.

Where GDPR applies, requests must be answered without undue delay and normally within one month of receipt. Any permitted extension and its reasons will be communicated within that month.

Never send your password, session token, or note content in a deletion request.

[Read the full Privacy Policy]({{ '/privacy-policy/' | relative_url }})

