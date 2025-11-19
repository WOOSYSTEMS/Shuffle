# Shuffle – AI Job Search & Cover Letter Automation

Shuffle** is a native macOS and iOS app that automates job search and applications.  
It scrapes jobs from LinkedIn and Indeed, analyzes them with AI, and generates tailored cover letters for each role – while tracking every application in one place.

---

## ✨ Key Features

- Job Search & Scraping
  - Search LinkedIn and Indeed jobs by title, location, and keywords
  - Add custom job URLs
  - Fetch and parse full job descriptions
  - Smart deduplication of jobs

- AI Job Analysis (Claude)
  - Job–profile match scoring (0–100%)
  - Qualification assessment with natural-language reasoning
  - Automatic requirement & skills extraction
  - Batch/background analysis with progress tracking

- AI Cover Letter Generation
  - Tailored cover letter per job
  - Company & role-aware content
  - Uses a base user template as context
  - Preview & edit before use
  - Auto-save generated letters to organized folders

- Application Tracking
  - Status pipeline: Discovered → Analyzing → Qualified → Applied → Rejected → Skipped
  - Filters & search for applications
  - Daily application limits
  - Open job posting directly from the app

- Profile & Preferences
  - Personal details (name, email, phone, location)
  - Skills, experience, education
  - Target job titles, locations, salary range
  - Required & excluded keywords

- Security & Privacy
  - AES-GCM 256-bit encryption via CryptoKit
  - API keys stored securely in iOS/macOS Keychain
  - Local-only data: no cloud sync, no analytics, no 3rd-party tracking

---

## 🧱 Tech Stack

- Languages:** Swift 5.9
- UI: SwiftUI (macOS & iOS)
- Architecture:** MVVM, async/await, actor-isolated services
- Parsing:** SwiftSoup (LinkedIn/Indeed HTML)
- Crypto:** CryptoKit (AES-GCM, Keychain integration)
- AI: Claude API (Anthropic)
- Project Setup: Swift Package Manager, XcodeGen
- Platforms:
  - macOS 14+ (Apple Silicon & Intel)
  - iOS 17+ (iPhone & iPad)

---

## 🚀 Getting Started (Developer Setup)

> This repo is intended for technical buyers or developers familiar with Xcode and Swift.

### Requirements

- Xcode 15+
- macOS 14+
- A Claude API key from Anthropic

