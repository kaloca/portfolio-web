---
title: Firebase Email Tracker
date: 2023/11/06
description: Email Open Tracking System
tag: web
author: You
---

# Firebase Email Tracker

Simple email tracking system designed to help Outlook users monitor when their sent emails are opened. Utilizing a small tracking pixel,it provides unique identifiers for each recipient using their IP. [Github repo](https://github.com/kaloca/firebase-email-tracker)

## Tech Stack (Typescript)

- Full Stack: Next.js 13 with App Router, Typescript
- Database: Firestore
- Deployment: Vercel (for Next.js applications)

## Functionalities

- Hidden tracking pixel generation that can be embedded into any email
- Real-time notifications for email opens
- A dashboard to view the list of people who opened the email with their unique identifiers
- Data storage and management with Firestore
- Easy to use with any email provider or client
