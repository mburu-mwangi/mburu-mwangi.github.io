---
title: Email Forwarding From Cpanel and Importing on Gmail
date: 2026-07-31 11:59:00 +0300
categories: [Email Hosting, Email Forwarding]
tags: [cpanel, gmail, hostpinnacle]
image: 
  path: /assets/cpanel_gmail2.png
  alt: Feature image for cpanel and gmail
render_with_liquid: false
---

Setting up a professional custom domain email using **cPanel** and linking it with **Gmail** is a great way to manage your business communications for free. 

Because Google has officially deprecated direct **POP3 email fetching** for third-party mailboxes, the best remaining method is combining **cPanel Email Forwarding** (for incoming mail) with Gmail's **Send mail as (SMTP)** feature (for outgoing mail). 

Here is a complete step-by-step guide tailored for [HostPinnacle Kenya](https://www.hostpinnacle.co.ke/) hosting servers.

---

## Step 1: Route Incoming Mail via cPanel Forwarders

This step ensures that any email sent to your custom address (e.g., `info@yourdomain.co.ke`) instantly copies directly over to your personal Gmail inbox.

1. Log into your **HostPinnacle Client Area** and launch your **cPanel** dashboard.
2. Scroll down to the **Email** section and click on **Forwarders**.
3. Click the **Add Forwarder** button.
4. In the **Address to Forward** box, type your email prefix (e.g., `info`).
5. Choose your correct website domain from the dropdown list.
6. Under **Destination**, select **Forward to Email Address** and input your destination **Gmail address**.
7. Click **Add Forwarder** to save the rule.

---

## Step 2: Configure Outgoing Mail (SMTP) in Gmail

This setup allows you to compose and reply to messages directly inside the Gmail interface while using your professional HostPinnacle domain in the "From" header.

1. Open your account on the [Gmail Web App](https://mail.google.com/).
2. Click the **Settings Gear Icon** in the top right, then select **See all settings**.
3. Open the **Accounts and Import** tab.
4. Find the **Send mail as** section and click **Add another email address**.
5. Enter your name and full business email address (e.g., `info@yourdomain.co.ke`), then click **Next Step**.
6. Enter the official **HostPinnacle SMTP server** credentials:
   * **SMTP Server:** `mail.yourdomain.co.ke` *(Replace with your actual domain)*
   * **Username:** Your complete business email address
   * **Password:** Your cPanel email account password
   * **Port:** `465` (Recommended)
   * **Connection:** Select **Secured connection using SSL**
7. Click **Add Account**.
8. Check your Gmail inbox for a verification email from Google, copy the numeric confirmation code, paste it into the setup window, and click **Verify**.

---

## HostPinnacle Server Configuration Quick Reference

| Mail Parameter | Secure SSL/TLS (Recommended) | Non-SSL / TLS Alternative |
| :--- | :--- | :--- |
| **SMTP Outgoing Server** | `mail.yourdomain.co.ke` | `mail.yourdomain.co.ke` |
| **SMTP Server Port** | **465** | **587** or **25** |
| **Authentication Requirement** | Required (Same as email password) | Required (Same as email password) |

---

## Why POP3 Import Fails

If you previously tried using Gmail’s *"Check mail from other accounts"* section, you likely ran into errors. Google has retired legacy POP3 fetch pipelines for non-Google mail ecosystems. Relying on an explicit mail forwarder is the only reliable way to view incoming external mail instantaneously inside Gmail without synchronization delays.