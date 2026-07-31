---
title: Lentille Studios Corporate Website Development
description: End-to-end development, hosting deployment, and SMTP transactional mail infrastructure for a premier video production company.
date: 2026-04-15 09:00:00 +0300
categories: [Personal Projects, Web Development]
tags: [wordpress, elementor, smtp, cpanel, dns, portfolio]
image:
  path: assets/lentille_studio_page_snip.png
  alt: Lentille Studios  
---

## Project Overview

[Lentille Studios](https://lentillestudios.com/) is a premier video production company specializing in corporate branding, event coverage, and creative documentary storytelling. As the solo **WordPress Developer & System Administrator** on this project, I took full ownership of translating their 5-star brand identity into a high-performance, responsive digital anchor.

The final product acts as their main corporate lead-generation platform, showcasing their elite client partnerships—such as Qwetu, Jasiri, and Legacy Hub—and driving strategic consultation calls.

---

## Core Responsibilities & Technical Architecture

### Core Responsibilities
* **Requirement Gathering:** Collaborated with cross-functional stakeholders to align design objectives with Lentille Studios' visual brand.
* **UI/UX Development:** Designed high-fidelity layouts using WordPress and Elementor to ensure fluid responsiveness across screen sizes.
* **Systems Administration:** Handled core configuration tasks including secure cPanel hosting provisioning, nameserver records, and site deployment.
* **Email Infrastructure:** Hardened user acquisition funnels by integrating custom domain emails via authenticated outbound SMTP protocols.
* **Continuous Integration:** Managed ongoing post-launch iterations by developing new feature landing pages, security patches, and media content updates.

### Technical Architecture
{% raw %}
```text
[User Device] ---> [DNS / Domain Routing] ---> [Host Server (cPanel)]
                                                        |
                                            [WordPress Core CMS]
                                                        |
                                          +-------------+-------------+

                                          |                           |
                                  [Elementor Engine]         [SMTP Mail Gateway]

                                          |                           |
                                  (Responsive UI)            (Secure Lead Delivery)
```
{% endraw %}

---

## Key Solutions Implemented

### 1. Stakeholder Translation & UI Design
Translated organizational communication goals into clean, user-centric responsive layout structures. The frontend interface fluidly scales across mobile, tablet, and desktop breakpoints to maintain visual balance for media-heavy components.

### 2. Infrastructure & DNS Management
Executed full-lifecycle platform deployment. This included managing domain name server (DNS) record mapping, configuring web hosting parameters inside cPanel, managing SSL certificates, and organizing ongoing server-side data maintenance.

### 3. High-Reliability Email Delivery
Bypassed unreliable default server mail configurations by integrating contact forms directly with custom domain-based email mailboxes. Utilizing authenticated SMTP delivery protocols guaranteed that incoming customer inquiries bypass spam filters and land immediately in the sales inbox.

---

## Technical Stack Summary

```text
CMS & Design:  WordPress, Elementor Pro, Responsive Breakpoints
Languages:     HTML5, CSS3, JavaScript basics
Systems Ops:   cPanel Infrastructure, DNS Routing, Domain Management, Web Hosting
Integrations:  Transactional Outbound SMTP Routing, Secure Contact Forms
```
