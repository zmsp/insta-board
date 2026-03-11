---
layout: default
title: Privacy Policy
date: 2026-03-11
---

# Privacy Policy
*Last Updated: March 11, 2026*

## 1. Overview
InstaBoard is designed with privacy as a core principle. We aim to provide intelligence for your saved links without compromising your personal data.

## 2. Data Collection
**Personal Information:** InstaBoard does not require a user account and does not collect personal identifiers like your name, email, or phone number.

**Link Data:** When you save a link, it is stored locally on your device in an encrypted database. We do not store your saved links on our servers.

## 3. Data Processing
When you "Analyze" a link, the URL is sent to our Cloudflare Worker service. This service:
* Extracts public metadata (title, description, image) from the provided URL.
* Uses AI (Large Language Models) to categorize and summarize the content.

This processing is enhanced by a caching layer. To provide a faster experience and reduce redundant processing, extracted metadata (non-personal link info) is stored in our Cloudflare cache for up to 7 days. This allows identical links to be served instantly to any user without re-running the extraction logic.

## 4. Security
InstaBoard does not store API keys on the client-side. All AI processing is handled through our secure backend gateway to ensure your usage remains private and secure.

## 5. Third-Party Services
We use the following third-party services to provide app functionality:
* **Cloudflare:** For hosting our metadata extraction worker.
* **OpenAI:** For natural language processing and categorization.

## 6. Local Storage
The app uses your device's local storage (SQLite/SharedPreferences) to keep your board organized. This data never leaves your device unless you explicitly share a link via the native sharing menu.

## 7. Affiliation & Content
InstaBoard's AI may identify products, books, or services within your saved links. In some cases, smart actions or links provided (e.g., "Search Product" or "Buy Book") may contain affiliate tracking codes from platforms like Amazon, Audible, or others. If you make a purchase through these links, the developer may receive a small commission at no additional cost to you. This helps support the development and maintenance of the app.

## 8. Contact
If you have questions about this policy, you can contact the developer via GitHub.

---
© 2026 InstaBoard. All rights reserved.
