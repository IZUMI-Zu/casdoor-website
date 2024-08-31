---
title: Casdoor Authenticator App
description: Store totp code in Casdoor
keywords: [authenticator, 2fa, password manager, totp]
authors: [IZUMI-Zu]
---

## Overview

We are excited to introduce the Casdoor Authenticator App, a new addition to the Casdoor ecosystem that allows users to store TOTP (Time-based One-Time Password) codes securely in Casdoor. With this app, users can conveniently manage their two-factor authentication (2FA) needs directly from their mobile devices. The Casdoor Authenticator App supports generating TOTP codes for enhanced security during login, providing a simple and user-friendly experience for securing your accounts.

In addition to client-side functionality, Casdoor also offers server-side management capabilities for administrators, enabling them to monitor and manage user logins and authentication processes more effectively. Furthermore, the Casdoor Authenticator App supports syncing TOTP data to the server, ensuring that your authentication codes are securely backed up and always available, providing a robust solution for managing your authentication needs.

Whether you are a developer, an administrator, or an end-user, the Casdoor Authenticator App ensures a seamless, secure, and flexible way to manage your two-factor authentication.

## What is TOTP?

TOTP stands for Time-based One-Time Passwords and is a common form of two-factor authentication (2FA). Unique numeric passwords are generated with a standardized [algorithm](https://tools.ietf.org/html/rfc6238) that uses the current time as an input. The time-based passwords are available offline and provide user-friendly, increased account security when used as a second factor.

## How to use the Casdoor Authenticator App?

### Step 0: Install the Casdoor Authenticator App

Right now, the Casdoor Authenticator App is available for Android devices. You can download the app from the official GitHub repository: [Casdoor Authenticator App](https://github.com/casdoor/casdoor-app/releases/latest) and install it on your Android device.

Alternatively, you can build the app from the source code available on GitHub check this for reference [Building from Source](https://github.com/casdoor/casdoor-app/releases/tag/latest).

### Step 1: Enable Totp Account storage in Casdoor Server (Optional)

This setup is optional for users who want to store their TOTP codes in the Casdoor server. Before using the Casdoor Authenticator App, you need to enable two-factor authentication (2FA) in the Casdoor server.
