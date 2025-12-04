# NIGHT-OWLS
# Multilingual AI Loan Advisor (Rule-Based Android App)
**Hackathon Project: [4th December 2025]**
------------------------------------------------------------------------------
##  1. Project Overview & The Problem:

**The Problem:** Accessing formal lending is difficult for individuals with low financial literacy or those facing language barriers. Existing solutions often require complex forms or are English-only, leading to confusion, rejected applications, and wasted time.

**Our Solution:** The Multilingual AI Loan Advisor is an accessible, offline Android application that provides personalized, step-by-step guidance for loan eligibility in the user's native language.

**Core Innovation (for Hackathon):** We simulate a real-time, personalized loan advisor using a **rule-based conversational flow** and an offline **multilingual text dictionary**, making the service instantly accessible and stress-free.
------------------------------------------------------------------------------
##  2. Core Features:

* **Multilingual Support:** Full conversation and UI available in **English** and **Hindi**.
* **Conversational Flow:** Guides the user through the eligibility process one question at a time (Age, Income, Loan Amount).
* **Offline Eligibility Calculator:** Instant, rule-based check that determines maximum eligible loan amount.
* **Eligibility Result Card:** A clear, actionable card delivered directly into the chat stream.
* **Learn Section:** Simple, accessible financial literacy cards explaining concepts like EMI, CIBIL (Mock Content).
* **User Experience:** Built with clean **Material Design 3** aesthetics in mind.
--------------------------------------------------------------------------------
##  3. Technical Stack & Architecture

* **Platform:** Android
* **Language:** Kotlin
* **UI Framework:** [Jetpack Compose]
* **Design Tool:** Figma

### Architecture (The main Hackathon Scope)
To ensure rapid development and reliable performance, this version is intentionally built as a **fully standalone, offline application** with the following key design decisions:

* **No Backend or API Calls:** All logic and content are stored locally in the app.
* **Rule-Based Logic:** Conversation flow is managed by state logic (IF-THEN) within the Kotlin code, simulating an intelligent response without an LLM.
* **Multilingual:** Achieved via Android's native `strings.xml` resource files and a custom content map.
---------------------------------------------------------------------------------
##  4. Screenshots

| Language Selection | Chat Interface (Hindi) | Eligibility Result | Learn Section |
| :---: | :---: | :---: | :---: |
| 

[Image of Language Selector]
 | 
[Image of Chat Screen]
 | 
[Image of Result Card]
 |  |
 ---------------------------------------------------------------------------------
 ##  5. Team & Contributions

This project was built by a team of 4 dedicated developers/designers over [X] hours.

| Role | Team Member | Primary Contribution |
| :--- | :--- | :--- |
| Android Developer (Front-End) | [] | Chat UI, Language Selector, Multilingual Implementation |
| Android Developer (Logic & State) | [Name 2] | Conversation Flow, Eligibility Calculator, Learn Screen Logic |
| Designer / UI Developer | [Name 3] | Figma Design, Aesthetics, Asset Preparation |
| Content & Presentation | [Name 4] | Hindi/English Content, Eligibility Rules, Final Presentation |
----------------------------------------------------------------------------------
##  6. Future Scope (What comes next)

If we had more time, we would implement:

1.  **Actual LLM Integration:** Migrate the rule-based chat logic to the Gemini API for truly dynamic, context-aware responses and real-time financial education.
2.  **OCR/Document Scanning:** Use ML Kit to scan income documents or Aadhaar cards.
3.  **Local Persistence:** Store user conversation history using SQLite or Preferences.
