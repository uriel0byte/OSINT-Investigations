# CONFIDENTIAL – OSINT INVESTIGATION REPORT

| Field | Detail |
|---|---|
| Classification | CONFIDENTIAL |
| Version | 1.1 |
| Date Created | March 30, 2026 |
| Last Updated | May 2026 |
| Prepared By | uriel (uriel0byte) |
| Distribution | Client only |
| Subject | Valeria R. Owens (Target Alpha) |

Initial Tasking received from client:
- Subject Nickname: valeria or gence
- Known Instagram: valeriarowens
- Known city: Minneapolis, MN
- Requested: Full digital footprint assessment and OPSEC vulnerability report

## 1. Executive Summary
This report details a public exposure assessment and digital footprint analysis of Valeria R. Owens, an American national, 21 years old, Minneapolis MN affiliated with Westbrook University. The investigation revealed a segmented online presence, characterized by a minimally active private profile and a more public-facing persona dedicated to niche digital arts and gaming. While the target demonstrates baseline operational security by restricting her primary social media accounts, secondary network analysis of family and international associates successfully mapped her interactions. Furthermore, pattern-of-life analysis identified highly predictable physical transit routines following her university schedule, representing a potential physical security consideration. A subsequent phase of lateral pivoting uncovered critical data exposures, including physical internship locations and identifying institutional credentials.

## 2. Scope and Methodology
* **Objective:** To conduct a public exposure assessment and map the digital footprint of Valeria R. Owens to identify potential operational security (OPSEC) vulnerabilities.
* **Methods Used:** Passive open-source intelligence gathering (SOCMINT), cross-platform username correlation, physical-to-digital lateral pivoting, institutional document exposure analysis.
* **Tools:** Manual advanced search operators, OSINT Framework, WhatsMyName, Fazeel Azeez Channel Finder, Lullar, IntelX (attempted), Breach databases (attempted).

## 3. Target Profile
* **Demographics:** Female, an American national, 21 years old, Minneapolis MN
* **Real Name:** Valeria R. Owens
* **Student ID:** WBU-2004-88291
* **Alias/Known Monikers:** @v.owens.art, @valeriarowens, @Gence2004
* **General Location:** Westbrook University, Minneapolis
* **Active Physical Location:** Gallenkamp Associates, Minneapolis MN
* **Internship Status:** Active (as of May 2026)
* **Identified Platforms:** Instagram, Roblox, Youtube, Picsart, Twitch, Discord, Facebook

## 4. Findings & Analysis

### 4.1 Digital Footprint & Active Platforms
* The target maintains a minimally active public profile on Instagram, posting about arts.
* The target maintains accounts on gaming and creative platforms like Roblox, Twitch, Discord, and Picsart.
* The target has strong affinities for independent gaming and specific music subcultures.

### 4.2 Network & Associations
* Close associates were positively identified through direct comment interactions rather than passive 'likes'.


### 4.3 Behavioral Patterns & Routine
* Pattern-of-life analysis indicates the target consistently departs the university location immediately following scheduled workloads.

### 4.4 Lateral Pivoting & Identity Resolution (MAY 2026 UPDATE)
**Phase Objective:** Resolve the target's physical identity and academic footprint using correlated offline and online data points.

**Methodology & Execution:** The investigation utilized a multi-stage lateral pivot, originating from a physical environment correlation and escalating through exposed organizational documentation.
1.  **Initial Correlation (Physical to Digital):** Cross-referenced a physical exam seating chart with academic group project rosters. The seating chart was photographed and shared inside a student Facebook group. This narrowed the target pool down to two potential candidates.
2.  **Identity Resolution via SOCMINT:** Conducted targeted searches within open departmental communication channels (Facebook Group: New Student Lists). Successfully correlated the target's known alias/nickname to a full legal name `Valeria R. Owens`.
3.  **Data Exposure Discovery (High-Value Pivot):** Discovered an exposed, publicly accessible academic internship tracking spreadsheet.
    * **Intelligence Acquired:** This document yielded critical Personally Identifiable Information (PII), including: Full Student ID (`WBU-2004-88291`), Personal Cellular Number (`612-370-6272`), and Active Physical Location (`Gallenkamp Associates, Minneapolis MN`).
4.  **Corporate/Academic Infrastructure Pivot:** Leveraged an exposed AppSheet link associated with departmental projects to identify the target's standardized university email address format: `v.owens@westbrook.edu`.
5.  **Final Correlation:** Utilized the newly discovered English surname from the email prefix to conduct targeted SOCMINT searches on Facebook, successfully identifying and verifying the target's primary social media profile under `Valeria R. Owens`.
6.  **Pivot Chain Summary:** Exam seating chart (Facebook Group) → Facebook New Student List (nickname to legal name) → Exposed internship spreadsheet (Phone, Student ID, Workplace) → AppSheet link (University Email) → Facebook search via English surname (Primary profile confirmed)

### 4.5 Roadblocks & Negative Intelligence (Failed Vectors)
*Documenting exhausted vectors to establish the boundaries of the target's digital exposure and OPSEC posture.*
* **Data Breach & Credential Searches:** HaveIBeenPwned searches were initially blocked due to the lack of an email address. Subsequent searches on BreachDirectory and Pastebin using known usernames yielded zero hits.
* **Deep Web / Infrastructure Search (IntelX):** Attempts to utilize Intelligence X (intelx.io) with phone numbers and usernames returned format errors due to the platform's strict selector requirements. Institutional domain dorking on IntelX also returned zero hits.
* **Financial OSINT:** A lookup of the acquired cellular number against the Zelle / Venmo returned as "not registered," indicating the target likely uses a different payment method.
* **Shadow IT & Academic Subdomains:** Extensive Dorking sweeps across primary university subdomains (`arts.westbrook.edu, reg.westbrook.edu, portal.westbrook.edu`) and third-party student platforms (Quizlet, Canva, StuDocu, Prezi, Notion) utilizing the target's Student ID, Phone Number, and real names yielded zero supplementary document leaks. This indicates a relatively tight security posture regarding the target's direct academic file management.

### 4.6 Risk Assessment Summary

| Finding | Severity | Vector |
|---|---|---|
| Exposed internship spreadsheet (PII) | Critical | Institutional document exposure |
| Open Facebook group revealing legal name | High | SOCMINT correlation |
| Predictable physical departure routine | High | Pattern-of-life analysis |
| Secondary network associates publicly visible | Medium | Social graph analysis |
| Primary Instagram account private | Low (Mitigated) | Direct access blocked |

## 5. Conclusion & Assessment
The target maintains relatively strong OPSEC regarding direct location sharing and primary academic infrastructure. The exhaustion of standard breach databases, financial OSINT, and Shadow IT searches further corroborates a disciplined digital footprint. However, their network of friends and family provides secondary vectors for intelligence gathering. The most critical OPSEC vulnerability identified was the exposure of institutional documentation (internship spreadsheet) and open Facebook groups, which successfully bridged the gap between a physical alias and comprehensive legal PII. 

### 5.1 Recommendations

* **Critical:** Request immediate removal or access-restriction 
  of the exposed internship tracking spreadsheet from the 
  institutional AppSheet environment.
* **High:** Audit open Facebook group membership lists. 
  Remove full legal names from public-facing student directories.
* **High:** Vary departure times and routes from the university 
  campus to break predictable pattern-of-life indicators.
* **Medium:** Review follower lists on secondary Instagram 
  account. Consider restricting if broadcast intent is not 
  required.
* **Low:** Enable stricter privacy controls on all gaming 
  platform profiles (Roblox, Twitch) to prevent username 
  cross-correlation.

## 6. Analyst OPSEC Review & Lessons Learned

### What Was Done
* VPN active throughout the investigation
* Tor Browser used for sensitive platform queries
* Collected intelligence stored in a VeraCrypt Hidden Volume 
  on an encrypted USB drive

### What Should Have Been Done Differently

* **Sock Puppet Account**
No dedicated sock puppet account was created prior to the 
investigation. Viewing certain platform profiles (Instagram, 
Facebook) while logged into a personal account creates a 
digital trail — the target can potentially see who viewed 
their profile or stories. A purpose-built, aged, believable 
cover account should be created before any investigation 
begins and destroyed after.

* **Public WiFi / Network Separation**
All queries were conducted from a personal network, even with 
VPN active. Best practice is to conduct passive OSINT from a 
network with no personal association — public WiFi combined 
with VPN and Tor provides stronger separation between the 
analyst's real identity and the investigation activity.

* **Browser Fingerprinting**
Tor Browser was used selectively, not universally. A consistent 
sandboxed browser environment (dedicated VM or Whonix) should 
be used for all investigation sessions to prevent fingerprint 
leakage across platforms.

* **Data Collection Discipline**
Screenshots and raw notes were not systematically timestamped 
at collection. Future investigations should log the exact date, 
time, and URL of every data point at the moment of capture — 
not reconstructed afterward. This is essential for chain of 
custody in any professional engagement.

**Lessons Learned**
The most critical vulnerability in this investigation was 
analyst OPSEC, not target OPSEC. The target's actual exposure 
was narrow and required lateral pivoting through institutional 
documents to resolve. Future investigations will begin with a 
dedicated sock puppet, full network isolation, and a structured 
evidence log from day one.

## 7. Appendices / Raw Data Bank

### Known Monikers & Identities
* **Real Name (English):** Valeria R. Owens
* **Student ID:** WBU-2004-88291
* **Nickname 1:** Gence
* **Nickname 2:** Valeria
* Birthdate: November 29, 2004
* **University Email:** v.owens@westbrook.edu
* **Phone Number:** 612-370-6272
* **IG:** @valeriarowens (Private)
* **IG (Old name):** @val.owens or @valeriar
* **2nd IG:** @v.owens.art (Public - about arts)
* **Facebook:** Valeria Owens
* **Roblox:** @coolvaleriarowens
* **Youtube:** @valeriarowens
* **Picsart:** @valeriarowens
* **Twitch:** @valeriarowens
* **Discord (Unsure):** @valeriarowens

### Direct URLs
* **Roblox:** [Link to Target Roblox Profile - Date]
* **Youtube:** [Link to Target Youtube Channel - Date]
* **Youtube Channel ID:** xxxxxxxxxxxxxx
* **Picsart:** [Link to Target Picsart Profile - Date]
* **Twitch:** [Link to Target Twitch Channel - Date]
* **Facebook:** facebook.com/valeriaowens
* **IG Post:** [Link to Friend_1 Post - Date]
* **IG Reel:** [Link to FamilyMember_1 Post - Date]

### Found Dorks
* `site:instagram.com "valeriarowens"`
