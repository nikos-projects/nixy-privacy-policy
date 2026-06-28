# Nixy Privacy Policy

**Last updated:** June 28, 2026

## Table of Contents
1. [Collection of Data](#1-collection-of-data)
2. [Legal Basis for Processing](#2-legal-basis-for-processing)
3. [How We Use Your Data](#3-how-we-use-your-data)
4. [Data Retention (When Data is Deleted)](#4-data-retention-when-data-is-deleted)
5. [User Rights (How to Delete or Access Your Data)](#5-user-rights-how-to-delete-or-access-your-data)
6. [Data Security](#6-data-security)
7. [Contact Information](#7-contact-information)

---

## 1. Collection of Data

We collect specific user and server data across the following core functionalities:

- **Server Snapshots:** Nixy automatically captures snapshots of the Discord server (including channel layouts and emojis) along with the last 20 messages of each channel. This includes storing your Discord display name, profile picture, and message content.
- **Server Logging:** We track server events via the Discord API to provide moderation logs. This includes processing message content (to log edited or deleted messages), username changes, profile picture updates, and other standard Discord server events.
- **AI Feature Moderation:** When interacting with the AI features via Discord Direct Messages (DMs), we collect your message content and Discord User ID.

## 2. Legal Basis for Processing

Under GDPR Article 6, we process your data under the following lawful bases:

- **Legitimate Interest:** Server snapshots and logging are processed to protect servers from raids, restore lost data, and provide moderation tools that server administrators have explicitly requested.
- **Consent:** AI feature moderation requires your active opt-in before processing begins. You may withdraw consent at any time by ceasing use of the AI features or running the data deletion command.

## 3. How We Use Your Data

- **Server Snapshots:** Used exclusively to restore a server's state, structure, and recent context in the event of a server "raid" or malicious destruction.
- **Server Logging:** Used to display real-time changes to the server, its channels, its messages, and its users in designated administrative logging channels.
- **AI Feature Moderation:** Used to automatically review conversations for illegal or highly inappropriate content. This automated review ensures compliance with safety guidelines, and users violating these rules may be automatically banned from using the AI features.

## 4. Data Retention (When Data is Deleted)

- **Server Snapshots:** Snapshots are taken automatically every hour. We maintain a strict rolling history of the last 50 snapshots. Consequently, data captured within a specific snapshot is permanently overwritten and deleted approximately 50 hours after it was recorded.
- **Server Logging:** Logged data is stored for as long as the bot remains active in the server. Upon bot removal from a server or server shutdown, all associated logged data is purged within 30 days. Server moderators may also manually delete specific logs at any time.
- **AI Feature Moderation:** Automated safety scans run every 5 minutes. Following the completion of the scan, processed DM message data is entirely and permanently deleted from our temporary cache.

## 5. User Rights (How to Delete or Access Your Data)

Under GDPR, you have the following rights:

- **Right to Access:** You may request a copy of all data we hold about you by contacting the developer.
- **Right to Deletion:** We provide a single, unified command that triggers a complete GDPR-compliant purge. Executing this command will instantly and permanently erase all of your data from our internal databases and remove any logged messages the bot has sent to Discord channels. Please note this only affects data controlled by Nixy — Discord's own message history outside of our bot's logs is not affected.
- **Right to Rectification:** You may correct inaccurate data by updating your Discord profile or contacting the developer for manual corrections.
- **Right to Restrict Processing:** You may temporarily restrict processing by disabling the bot's features in your server or ceasing use of AI functions.

To find the current deletion command, type `help` with any valid bot prefix (e.g., `&`, `=`, `$`) and look for the command labelled for data erasure.

## 6. Data Security

All data is encrypted at rest and in transit using industry-standard protocols. Access to stored data is restricted to the bot developer and is never shared with third parties except as required by Discord's API infrastructure.

## 7. Contact Information

If you have questions regarding this Privacy Policy, wish to request a copy of your data, or require manual data assistance, you can contact the developer directly via Discord at `niko_3992` or by emailing [taubert.philipp2@gmail.com](mailto:taubert.philipp2@gmail.com). We respond to all GDPR requests within 30 days as required by law.
