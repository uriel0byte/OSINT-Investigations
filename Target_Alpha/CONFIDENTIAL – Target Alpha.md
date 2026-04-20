# CONFIDENTIAL – OSINT INVESTIGATION REPORT
**Date of Report:** 3/30/2026 (Updated May 2026)
**Prepared By:** uriel
**Subject:** [Target Alpha]

## 1. Executive Summary
This report details a public exposure assessment and digital footprint analysis of [Target Alpha], a Thai national in her early 20s currently affiliated with [Major University]. The investigation revealed a segmented online presence, characterized by a minimally active private profile and a more public-facing persona dedicated to niche digital arts and gaming. While the target demonstrates baseline operational security by restricting her primary social media accounts, secondary network analysis of family and international associates successfully mapped her interactions. Furthermore, pattern-of-life analysis identified highly predictable physical transit routines following her university schedule, representing a potential physical security consideration. A subsequent phase of lateral pivoting uncovered critical data exposures, including physical internship locations and identifying institutional credentials.

## 2. Scope and Methodology
* **Objective:** To conduct a public exposure assessment and map the digital footprint of [Target Alpha] to identify potential operational security (OPSEC) vulnerabilities.
* **Methods Used:** Passive open-source intelligence gathering (SOCMINT), cross-platform username correlation, physical-to-digital lateral pivoting, institutional document exposure analysis.
* **Tools:** Manual advanced search operators, OSINT Framework, WhatsMyName, Fazeel Azeez Channel Finder, Lullar, IntelX (attempted), Breach databases (attempted).

## 3. Target Profile
* **Demographics:** Female, Thai national, Early 20s
* **Real Name:** [REDACTED_THAI_NAME] / [REDACTED_ENGLISH_NAME]
* **Student ID:** [REDACTED_10_DIGIT_ID]
* **Alias/Known Monikers:** [@TargetIG_1, @TargetIG_2, @TargetLINEName_1, @TargetTwitch_1]
* **General Location:** [Employed at Major University, Near Major City]
* **Active Physical Location:** [REDACTED_CORPORATE_INTERNSHIP_LOCATION]
* **Identified Platforms:** [Instagram, LINE, Roblox, Youtube, Picsart, Twitch, Discord, Facebook]

## 4. Findings & Analysis

### 4.1 Digital Footprint & Active Platforms
* The target maintains a minimally active public profile on Instagram, posting about arts.
* The target maintains accounts on gaming and creative platforms like Roblox, Twitch, Discord, and Picsart.
* The target has strong affinities for independent gaming and specific music subcultures.

### 4.2 Network & Associations
* Link analysis indicates a one-way interaction pattern on the target's secondary Instagram account. Multiple associates follow this profile, but the target does not reciprocate follows, suggesting the account is used primarily as a public broadcast channel.
* Close associates were positively identified through direct comment interactions rather than passive 'likes'.
* Analysis of public interactions on secondary family accounts identified a familial connection, corroborated by a comment referencing past travel. This aligns with historical data suggesting the target resided in North America between 2020 and 2022.

### 4.3 Behavioral Patterns & Routine
* Pattern-of-life analysis indicates the target consistently departs the university location immediately following scheduled workloads.

### 4.4 Lateral Pivoting & Identity Resolution (MAY 2026 UPDATE)
**Phase Objective:** Resolve the target's physical identity and academic footprint using correlated offline and online data points.

**Methodology & Execution:** The investigation utilized a multi-stage lateral pivot, originating from a physical environment correlation and escalating through exposed organizational documentation.
1.  **Initial Correlation (Physical to Digital):** Cross-referenced a physical exam seating chart with academic group project rosters. This narrowed the target pool down to two potential candidates.
2.  **Identity Resolution via SOCMINT:** Conducted targeted searches within open departmental communication channels (LINE Groups: New Student/Mentorship Lists). Successfully correlated the target's known alias/nickname to a full legal name `[REDACTED_THAI_NAME]`.
3.  **Data Exposure Discovery (High-Value Pivot):** Discovered an exposed, publicly accessible academic internship tracking spreadsheet.
    * **Intelligence Acquired:** This document yielded critical Personally Identifiable Information (PII), including: Full Student ID (`[REDACTED_10_DIGIT_ID]`), Personal Cellular Number (`+66-[REDACTED_PHONE]`), and Active Physical Location (`[REDACTED_CORPORATE_INTERNSHIP_LOCATION]`).
4.  **Corporate/Academic Infrastructure Pivot:** Leveraged an exposed AppSheet link associated with departmental projects to identify the target's standardized university email address format: `[REDACTED_SURNAME_INITIAL]@[REDACTED_UNI_DOMAIN]`.
5.  **Final Correlation:** Utilized the newly discovered English surname from the email prefix to conduct targeted SOCMINT searches on Facebook, successfully identifying and verifying the target's primary social media profile under `[REDACTED_ENGLISH_NAME]`.

### 4.5 Roadblocks & Negative Intelligence (Failed Vectors)
*Documenting exhausted vectors to establish the boundaries of the target's digital exposure and OPSEC posture.*
* **Data Breach & Credential Searches:** HaveIBeenPwned searches were initially blocked due to the lack of an email address. Subsequent searches on BreachDirectory and Pastebin using known usernames yielded zero hits.
* **Deep Web / Infrastructure Search (IntelX):** Attempts to utilize Intelligence X (intelx.io) with phone numbers and usernames returned format errors due to the platform's strict selector requirements. Institutional domain dorking on IntelX also returned zero hits.
* **Financial OSINT:** A lookup of the acquired cellular number against the Thai PromptPay system returned as "not registered," indicating the target uses a different identifier (likely a National ID) for financial transactions.
* **Shadow IT & Academic Subdomains:** Extensive Dorking sweeps across primary university subdomains (`[REDACTED_ARTS_DOMAIN]`, `[REDACTED_REG_DOMAIN]`, `[REDACTED_PORTAL_DOMAIN]`) and third-party student platforms (Quizlet, Canva, StuDocu, Prezi, Notion) utilizing the target's Student ID, Phone Number, and real names yielded zero supplementary document leaks. This indicates a relatively tight security posture regarding the target's direct academic file management.

## 5. Conclusion & Assessment
The target maintains relatively strong OPSEC regarding direct location sharing and primary academic infrastructure. The exhaustion of standard breach databases, financial OSINT, and Shadow IT searches further corroborates a disciplined digital footprint. However, their network of friends and family provides secondary vectors for intelligence gathering. The most critical OPSEC vulnerability identified was the exposure of institutional documentation (internship spreadsheet) and open LINE groups, which successfully bridged the gap between a physical alias and comprehensive legal PII. 

## 6. Appendices / Raw Data Bank

### Known Monikers & Identities
* **Real Name (Thai):** [REDACTED_THAI_NAME]
* **Real Name (English):** [REDACTED_ENGLISH_NAME]
* **Student ID:** [REDACTED_10_DIGIT_ID]
* **Nickname 1:** [Target_Alpha_NickName]
* **Nickname 2:** [Target_Alpha_NickName_2]
* **University Email:** [REDACTED_SURNAME_INITIAL]@[REDACTED_UNI_DOMAIN]
* **Phone Number:** +66-[REDACTED_PHONE]
* **IG:** [@TargetIG_1] (Private)
* **IG (Old name):** [@TargetOldIG_1.1] or [@TargetIG_1.2]
* **2nd IG:** [@TargetIG_2] (Public - about Target_Alpha arts)
* **Line Name Display:** [@TargetLINEName_1]
* **Facebook:** [REDACTED_FACEBOOK_URL]
* **Roblox:** [@TargetRoblox_1]
* **Youtube:** [@TargetYoutube_1]
* **Picsart:** [@TargetPicsart_1]
* **Twitch:** [@TargetTwitch_1]
* **Discord (Not sure):** [@TargetDiscord_1]

### Direct URLs
* **Roblox:** [Link to Target Roblox Profile - Date]
* **Youtube:** [Link to Target Youtube Channel - Date]
* **Youtube Channel ID:** xxxxxxxxxxxxxx
* **Picsart:** [Link to Target Picsart Profile - Date]
* **Twitch:** [Link to Target Twitch Channel - Date]
* **Facebook:** [Link to Target Facebook Profile - Date]
* **IG Post:** [Link to Friend_1 Post - Date]
* **IG Reel:** [Link to FamilyMember_1 Post - Date]

### Found Dorks
* `site:instagram.com "[@TargetIG_1]"`