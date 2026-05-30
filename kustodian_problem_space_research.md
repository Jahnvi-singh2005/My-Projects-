# Deep Research Report: Underserved Problem Areas Adjacent to Kustodian.life
**Prepared for:** Product Management Intern, Kustodian.life  
**Date:** May 2026  
**Methodology:** Desk research across consumer forums, regulatory disclosures, news coverage, RTI data, court judgments, and industry reports

---

## Preface

India currently has an estimated **₹1.96–3.5 lakh crore** in unclaimed or dormant financial assets scattered across banks (₹78,000+ crore), EPF (₹8,505 crore in inoperative accounts), insurance (₹25,000 crore), mutual funds (₹3,400+ crore), and shares/dividends (via IEPF). Despite the scale, the recovery rate from government funds is under 4% — a figure cited in a Supreme Court hearing in 2026. The problem is not merely about recovery. It is upstream: discovery, documentation, preparedness, and prevention. These upstream gaps represent the most fertile ground for new products adjacent to Kustodian.

---

## Part I: Problem-by-Problem Analysis

### Problem 1: Families Cannot Discover All Assets After a Death

**User Segment:** Legal heirs, surviving spouses, adult children — especially those who were not involved in managing the deceased's finances.

**User Journey:**
A man in his 50s dies unexpectedly. His wife knows he had a bank account and an LIC policy. She does not know he also had:
- An old EPF account from a job 15 years ago
- A small mutual fund folio opened through an agent in 2009
- Shares in two companies inherited from his father
- An FD at a cooperative bank in their hometown

Over the following months, some of these surface accidentally. Others never do. The widow either lacks the literacy or access to navigate five separate government portals (UDGAM for banks, MITRA for mutual funds, Bima Bharosa for insurance, IEPF for shares, EPFO for PF), each requiring different credentials, each covering different asset types.

**Evidence:**
- As of March 2026, UDGAM has had 20 lakh registered users and 44 lakh searches — yet it covers only bank deposits, not PF, insurance, or post office savings
- A 2025 fee-only investment adviser report confirms: "Indian systems do not allow name-based searches" except partially on IEPF. Heirs cannot search by the deceased's name across categories
- The Supreme Court issued notice in October 2025 on a PIL by activist Aakash Goel seeking a legal framework to track ₹3.5 lakh crore in unclaimed assets
- A Business Standard expert interview: "When the owner of an asset dies, the spouse or family members often don't know what assets the deceased owned. Even if they have a list, they don't know where the documents are"
- The Finance Minister promised an integrated portal in Budget 2023. As of early 2026, it remains unfulfilled

**Severity: HIGH**  
Assets permanently lost because they were never known to exist. Emotional cost falls on already-grieving families.

**Frequency: VERY HIGH**  
Every death in a family with multiple financial instruments triggers this. India has roughly 8–9 million deaths per year.

**Existing Solutions:**
- UDGAM (RBI): banks only, no claim ability — only discovery
- MITRA (SEBI): mutual funds only
- Bima Bharosa (IRDAI): insurance only
- IEPF portal (MCA): shares/dividends only
- EPFO: PF, but difficult to search for the deceased's old accounts

**Why Existing Solutions Fail:**
- Extreme fragmentation: a family must navigate 5+ separate systems
- Most portals require knowing something exists before they reveal it (search by account number, not by name)
- No portal covers all asset classes under one roof
- Low digital literacy among the demographic most affected (widows 50+, rural families)
- Government portals are poorly designed for grief-struck, time-pressured families

**Opportunity Gap:**  
A private, guided, family-facing "estate discovery" workflow that helps survivors systematically search across all asset classes using just the deceased's PAN/Aadhaar, with a clear checklist of what to search, where, and what documents are needed at each step.

---

### Problem 2: No Centralized Way for Individuals to Record and Share Their Own Financial Life with Family

**User Segment:** Working adults (35–60), especially salaried and self-employed individuals with multiple financial instruments; also rural households where financial knowledge is concentrated in one family member.

**User Journey:**
Ramesh, 48, holds accounts with three banks, SIPs in four fund houses, an LIC policy, EPF from two employers, and inherited agricultural land in another state. His wife manages the household; his adult son is in Bengaluru. None of them know the full picture. Ramesh has never written it down in a single place. He intends to — but hasn't.

If Ramesh dies tomorrow, his family will spend years trying to reconstruct what he owned. Some assets will never be found.

**Evidence:**
- Only 40% of Indians draft wills, per a 2025 NoBroker survey, leaving 60% intestate
- Fewer than 10% of Indians have formal estate plans (compared to 46% in the US)
- 80% of Indians die intestate, per a 2017 academic study (Liberty University)
- A Business Standard expert quote: "It is imperative to maintain detailed information on assets and share this with spouse and direct family members" — yet no tool exists to do this simply
- Death and money remain culturally taboo subjects in Indian families, per a January 2026 Business Standard column
- Families in HUF structures historically discouraged will-writing because the HUF created a false impression of collective ownership

**Severity: HIGH**  
The absence of a simple financial record creates the conditions for all other downstream problems (unclaimed assets, disputes, lost documents).

**Frequency: UNIVERSAL**  
Virtually every Indian household with more than one financial product has this problem. It is a problem of omission, so it is underreported.

**Existing Solutions:**
- DigiLocker: stores documents, not a financial inventory
- Spreadsheets: used by some, but not structured, not shared, not maintained
- Will: captures beneficiaries but not passwords, locker locations, agent contacts, or operational details
- Some banks offer "safe" services for HNIs, but nothing for the mass market

**Why Existing Solutions Fail:**
- No product combines: asset inventory + nominee mapping + document storage + family-sharing + periodic update reminders
- Will writing is perceived as expensive, morbid, and relevant only to the rich
- Spreadsheets are fragile, private, and not updated
- Cultural taboo prevents families from having the conversation

**Opportunity Gap:**  
A "financial will" or "family financial passport" product — a structured, private, shareable record of all financial assets, account details, agent contacts, locker locations, and access instructions, designed to be created in 30 minutes and updated annually. Not a legal will. Not a will substitute. A practical family-facing document.

---

### Problem 3: Nomination Gaps and Mismatches Across Financial Products

**User Segment:** All financial product holders, particularly those who opened accounts before 2015, and those who have experienced life events (marriage, childbirth, divorce, death of a previous nominee) without updating records.

**User Journey:**
Priya opened a mutual fund folio in 2010 with her mother as nominee. She married in 2015, had a child in 2018, and her mother passed away in 2021. Her folio still shows her deceased mother as nominee. She has never updated it because she was unaware she needed to, and no one proactively notified her.

Similarly, her husband's EPF account still shows his father as nominee from when he first joined employment in 2012. His PAN-linked bank account has no nominee at all.

**Evidence:**
- SEBI mandated nomination updates or opt-out by March 2023 or risk demat/MF account freeze — millions of investors were scrambling
- SEBI revamped nomination framework in January 2025 (Circular SEBI/HO/OIAE), mandating single-holder accounts to designate nominees; effective March 2025
- Banking Laws Amendment Act 2024/2025 now allows up to 4 nominees for bank accounts (previously 1), effective November 2025 — this reform was driven by the massive practical failures of the single-nominee system
- ₹3,400+ crore in mutual fund investments remain unclaimed partly because families are unaware of investments or nomination details (SEBI annual report FY2024-25)
- Court cases in 2024-2025 show contradictory rulings: some courts say nominee gets the asset; others say nominee holds it in trust for legal heirs. The legal ambiguity itself is a user problem — people don't understand what their nomination actually means
- Mondaq legal analysis (July 2025): "India's complex inheritance landscape — the law concerning life insurance nominations has become increasingly dissonant"

**Severity: HIGH**  
A missing or incorrect nominee can add months of legal process and significant cost. A misunderstood nomination (nominee ≠ legal owner in most cases) creates family conflict.

**Frequency: HIGH**  
Affects any account opened more than 3 years ago without update. Given India's low financial literacy and high life-event rates among working-age adults, outdated nominations are extremely common.

**Existing Solutions:**
- Individual institution portals allow nomination updates
- SEBI and RBI advisories
- No cross-institutional nomination health check exists

**Why Existing Solutions Fail:**
- Nominations exist in silos: you must check 8–10 platforms separately
- No reminder system tells you when a nominee has died or when you've had a life event
- Users don't understand the legal difference between a nominee and a legal heir
- KYC mismatches block updates (e.g., Aadhaar not linked to mobile means e-sign fails)

**Opportunity Gap:**  
A "nomination health dashboard" — a tool that aggregates all financial accounts' nominee status by pulling from PAN/KYC data, flags gaps and outdated nominees, and guides users through updates with institution-specific instructions.

---

### Problem 4: NRI Families Cannot Manage Indian Parental Assets Remotely

**User Segment:** NRIs (estimated 32 million) with aging parents in India; Indian parents with children abroad.

**User Journey:**
Rohan, an NRI in the US, gets a call that his father in Pune has had a stroke and is incapacitated. His father has property, FDs, an LIC policy, a PPF account, and a locker at SBI. Rohan doesn't know the full details. He flies to India. For the next three months, he navigates:
- Getting Power of Attorney notarized and apostilled in the US, then adjudicated in India
- Discovering a second FD by accident
- Getting the LIC policy serviced (premium due)
- Trying to operate the bank locker without the right authorization

**Evidence:**
- 85% of NRIs lack proper estate planning, per GoINRI (December 2025)
- Outlook Money (December 2025): "The real crisis emerges when parents pass away without a Will, leaving NRI children to navigate India's intestate succession framework from afar"
- Assets "scattered financial records and undisclosed assets often lead to losses or missed claims" — direct quote from Outlook Money's NRI estate planning analysis
- Cross-border tax complications: while India has no inheritance tax, US residents must report foreign inheritances over $100,000 via Form 3520; some US states levy inheritance taxes; NRI children often don't know this
- NRI heirs face: unauthorized occupation of property by distant relatives during probate delays; inability to operate accounts remotely; difficulty getting succession certificate without physical presence
- Property encroachment risk: "prolonged disputes and immense financial and emotional distress," per evaakil.com (October 2025)

**Severity: HIGH**  
Loss of assets, fraud risk from unauthorized occupation, tax penalties, and years of legal cost.

**Frequency: HIGH AND RISING**  
India has 32 million NRIs. The parents of the 2000s-era NRI cohort are now in their 60s–70s, creating a massive near-term wave.

**Existing Solutions:**
- Specialized NRI legal firms (expensive, fragmented)
- CA firms for tax guidance
- No integrated remote management platform

**Why Existing Solutions Fail:**
- Each service solves one piece: legal, or tax, or PF
- No single platform allows an NRI to: see all parents' assets, track what's coming due, receive alerts, and coordinate action with a trusted local representative
- High service cost (lawyers charge ₹10,000–₹50,000+ for each discrete task)
- Trust deficit: NRIs fear being overcharged or misled by Indian service providers they cannot supervise

**Opportunity Gap:**  
A remote family financial management service for NRIs — a structured way to inventory parents' assets, manage ongoing obligations (premium due dates, FD maturity, property tax), and coordinate action through verified local agents or Power of Attorney workflows.

---

### Problem 5: Elderly Indians Are Systematically Shut Out of Their Own Financial Accounts

**User Segment:** Indians 65+, especially those living without tech-savvy family members nearby; widows/widowers who were not the primary financial manager.

**User Journey:**
Lakshmi, 72, recently widowed in Chennai. Her husband handled all finances. She has a pension from his employer, a joint bank account, and an LIC policy. She doesn't know her UAN. She's never used the EPFO portal. Her branch has shifted to digital-first service. The bank is pushing her to use the app for basic transactions. She doesn't have a smartphone. She is confused, vulnerable, and increasingly isolated from her own money.

**Evidence:**
- Digital payment frauds rose 10-fold to 2.8 million cases between 2021 and 2025; losses jumped 40x to ₹23,000 crore (National Cyber Crime Reporting Portal)
- RBI (April 2026) is considering requiring a "trusted person" approval for transactions above ₹50,000 for customers 70+ — a tacit acknowledgment that the current system fails elderly users
- In Nagpur, 60% of cybercrime victims in 2025 were senior citizens; the trend was 45% in 2024
- Cybercrime incidents rose from 10.29 lakh (2022) to 22.68 lakh (2024)
- Senior citizens are targeted because: (a) they are not digitally savvy, and (b) they have accumulated savings
- Academic study (MDPI, 2023): significant anxiety, low self-efficacy, and low trust are key barriers to elderly e-banking adoption in India
- A Deccan Herald column described a Delhi senior who lost ₹5 lakh in an OTP scam while managing her husband's hospitalization: "Cloaked in politeness, the fraud preyed on her desperation"
- Women who were excluded from family financial discussions are especially vulnerable after a spouse's death

**Severity: HIGH**  
Financial fraud devastating to elderly = total loss of retirement savings, which cannot be recovered.

**Frequency: VERY HIGH AND ACCELERATING**  
India's senior population is growing. Digital fraud is accelerating. The two trends intersect fatally.

**Existing Solutions:**
- Family supervision (informal and inconsistent)
- Bank senior citizen counters (available in some branches)
- Truecaller + Khyaal partnership (awareness-focused, not operational)
- No product that actually helps elderly manage their financial life with appropriate guardrails

**Why Existing Solutions Fail:**
- Banks are reducing physical touchpoints, not expanding them
- Family supervision requires family to be physically present or constantly available
- Awareness campaigns don't prevent fraud at the moment of attack
- No "safe mode" for elderly banking that limits exposure without removing autonomy

**Opportunity Gap:**  
A family-supervised financial monitoring service for elderly — where a trusted family member receives alerts on large/suspicious transactions, can co-authorize above a threshold, and can manage routine tasks (premium renewal, FD tracking) without needing the elderly person to navigate apps. Not a power of attorney — a consent-based, dignity-preserving financial companion.

---

### Problem 6: Post-Death Document and Process Navigation Is Paralyzing for Families

**User Segment:** Families immediately after a death — regardless of income level.

**User Journey:**
A family in Mumbai loses its 55-year-old father. In the first 30 days, they must:
- Obtain death certificate from municipal authority (queue + wait + document errors)
- Establish legal heirship (different documents for different assets)
- File a claim with LIC (different form, different branch)
- Initiate EPF withdrawal (EPFO portal, which requires the deceased's UAN)
- Contact the bank for account access (needs succession certificate if no nominee)
- Begin property mutation in the revenue department
- Check for any shares in physical form
- Cancel pending SIPs in mutual funds
- Notify income tax department
- File final ITR for the deceased

Each of these involves different institutions, different forms, different offices, and different timelines. None talks to any other.

**Evidence:**
- Business Standard inheritance guide (November 2025): describes a multi-step process requiring death certificate → probate/succession certificate → institution-specific claims, each with its own documentation
- EPFO circular (August 2024): for inoperative accounts, the withdrawal process now involves sending details to 20 people who worked with the deceased, of whom 5 must confirm — "At 60 you expect people to run around the PF office umpteen times" (Moneylife forum comment)
- Succession certificate from court: requires a petition to the district court, public notice, objection period, and multiple hearings — typically 3–18 months
- Property mutation in inheritance cases: blocked by missing legal heir certificate, e-mutation portal data migration glitches (Karnataka, Maharashtra, Telangana — documented in 2024-25 RTI filings)
- Legal heir certificate vs. succession certificate vs. probate vs. letter of administration: families don't know which they need for which asset
- Fraud: forged wills and succession certificates reported in 15% of cases (Doon Law Mentor, 2025)

**Severity: HIGH**  
Families under grief are expected to navigate a multi-system bureaucratic maze. Errors lead to claim rejections and delays of months to years.

**Frequency: HIGH**  
~8-9 million deaths per year in India. Every death with financial assets triggers some version of this process.

**Existing Solutions:**
- Lawyers and CAs (expensive, not accessible to most)
- Online guides (informational only)
- Kustodian (claim-specific, not full process navigation)

**Why Existing Solutions Fail:**
- No single product maps the complete checklist for a family's specific asset portfolio after a death
- Lawyers charge for each institution and each document separately
- Most families discover they needed a succession certificate only after a bank rejects their claim
- The process is not linear — different assets require different documents in different orders

**Opportunity Gap:**  
A "post-death financial checklist engine" — a tool that, given the deceased's known assets and family structure, generates a personalized, sequenced action plan with the right forms, the right order, the right institutions, and the right documents for each step.

---

### Problem 7: Digital Assets Are Dying With Their Owners

**User Segment:** Working-age professionals (25–50) who hold crypto, NFTs, monetized social media accounts, online trading accounts, and cloud-stored investment records.

**User Journey:**
Vikram, 38, holds ₹12 lakh in WazirX, a Zerodha account with ₹7 lakh in stocks, a monetized YouTube channel earning ₹40,000/month, and a Binance wallet with cryptocurrency. He dies in an accident. His wife:
- Cannot access Zerodha because it requires OTP to his registered phone
- Cannot claim the WazirX account without knowing his password or going through a court process
- Has no way to transfer or monetize the YouTube channel
- Cannot access the Binance wallet at all without the private key, which Vikram never shared

**Evidence:**
- Madras High Court, October 2025: First Indian High Court judgment classifying cryptocurrency as property capable of inheritance. The case arose from WazirX-frozen accounts during the July 2024 $234 million hack
- India still lacks a comprehensive statutory framework for digital succession — the Information Technology Act, Indian Succession Act, and DPDP Act do not address digital estates
- "A legal right may exist on paper, but families often have no practical ability to enforce it" (Aayushi Singh, Legum Solis, quoted in crypto legal analyses)
- 50% of urban inheritance disputes in 2025 involved digital asset access issues, per NJDG data cited in Doon Law Mentor
- Self-custody crypto: "No legal document, no court order, and no amount of litigation can recover a self-custody wallet without the seed phrase"
- The Income Tax Act 2025 (effective April 2026) now formally includes digital wallets and online accounts as search-and-seizure targets — official acknowledgment that these are real, taxable property

**Severity: HIGH (for the urban professional segment) and RISING**  
Assets are permanently and irrecoverably lost without credentials. Unlike a bank account, there is no institution to petition.

**Frequency: LOW TO MEDIUM NOW, HIGH IN 3–5 YEARS**  
Currently concentrated among tech-savvy early adopters. Growing rapidly as crypto and digital assets go mainstream in India.

**Existing Solutions:**
- Dead Man's Switch services (global, not India-specific)
- Last Pass and other password managers (not succession-focused)
- No India-specific legal or operational framework

**Why Existing Solutions Fail:**
- No Indian product combines legal guidance + secure credential storage + access workflow for heirs
- Crypto platforms have no India-friendly succession process
- Legal framework is still emerging; families don't know their rights

**Opportunity Gap:**  
A "digital estate vault" — a secure, encrypted service that allows users to store access credentials, crypto seeds, and account instructions, with a legally triggered release mechanism to designated heirs upon verified death. Not just password storage: a full digital succession workflow.

---

### Problem 8: Insurance Claim Rejections Are Routine and Families Don't Know How to Appeal

**User Segment:** Nominees and legal heirs attempting to claim life/health insurance after a death.

**User Journey:**
Suresh dies at 52. His wife files a term insurance claim with a private insurer. The claim is rejected citing "non-disclosure of a pre-existing condition" — a hypertension diagnosis from 2019 that wasn't mentioned in the 2020 policy application. She doesn't know:
- Whether the rejection is legally valid
- What the appeal process is
- That she can approach the IRDAI Insurance Ombudsman for free
- That the time limit to appeal is 1 year from the insurer's final reply

She does nothing. The ₹50 lakh cover is forfeited.

**Evidence:**
- Health insurance claims worth ₹26,000 crore were rejected or repudiated in FY2024 — a 19.10% increase year-on-year (IRDAI annual report)
- 11% of health claims are rejected and 6% remain pending as of March 2024
- Life insurance: Rs 48,512 crore in death claims paid in FY2024, but significant volumes rejected
- Common rejection reasons: incorrect information at application, policy lapse, non-disclosure, nominee issues
- A righttoinformation.wiki guide (2026) notes: "A rejection letter is not a verdict — it's the start of an appeal pipeline that's free, structured, and statistically favourable to the policyholder" — but families don't know this
- Consumer court cases show that insurers routinely deny claims that consumer forums and ombudsmen later reverse
- LIC ordered to pay ₹50 lakh compensation in a Kerala case (2024) for failing to process an application within mandated timelines

**Severity: HIGH**  
Families lose substantial sums due to procedural ignorance, not legal ineligibility.

**Frequency: HIGH**  
11% rejection rate × millions of claims = hundreds of thousands of families annually.

**Existing Solutions:**
- IRDAI Ombudsman (free but unknown to most)
- Consumer courts (slow, requires legal knowledge)
- Lawyers (expensive relative to smaller claim amounts)

**Why Existing Solutions Fail:**
- Families don't know the appeal pipeline exists
- The process is opaque and intimidating
- Time limits create urgency that families miss while grieving
- No one explains that rejection letters are challengeable

**Opportunity Gap:**  
An "insurance claim appeal navigator" — a service that evaluates rejected insurance claims, identifies legal grounds for appeal, files with IRDAI Ombudsman or consumer court, and recovers the payout on a success-fee basis.

---

### Problem 9: No Preventive Asset-Preservation System Exists for Indian Families

**User Segment:** Working adults 35–55 with multiple financial instruments.

**User Journey:**
Anita, 42, has SIPs in three fund houses, an EPF account, and two FDs. She changes jobs and forgets to transfer her old EPF account. The bank where one FD is held changes its branch address; her contact details are outdated. One SIP's auto-debit fails because she changed her bank account and didn't update the mandate. She is busy. None of these institutions proactively alert her. Three years later, one EPF account is inoperative, one FD is nearly unclaimed, and one SIP has stopped.

**Evidence:**
- EPF inoperative accounts rose 5-fold: from ₹1,638 crore (2018-19) to ₹8,505 crore (2023-24)
- Primary causes of EPF dormancy: job change without transfer, employer shutdown, KYC mismatches, wrong bank details
- ₹78,000 crore in unclaimed bank deposits as of March 2024, up 26% in one year — the growth is accelerating
- Bank accounts become inoperative after 2 years of no transactions; unclaimed after 10 years — most account holders don't know these timelines
- Shares: dividends that go uncollected for 7 years, and shares not transferred for 7 years, move to IEPF — many investors have no idea this happens
- LIC unclaimed: policies lapse silently when premium auto-debit fails; families discover years later
- The core problem: financial institutions are not designed to proactively retain customers or alert them to asset-health issues

**Severity: MEDIUM-HIGH**  
Each individual event may seem minor; cumulatively they represent meaningful wealth erosion.

**Frequency: VERY HIGH**  
Every job change, address change, bank account switch, or phone number change creates the conditions for an asset to drift toward dormancy.

**Existing Solutions:**
- KYC update reminders (sporadic, institution-specific)
- Consolidated Account Statement for mutual funds (CAMS/KFintech) — exists but rarely reviewed
- No cross-institution "financial health check" service

**Why Existing Solutions Fail:**
- Each institution only monitors its own product
- No system connects events (job change) to actions (EPF transfer needed)
- Reminders, if any, go to outdated email/phone
- Users don't know what they don't know

**Opportunity Gap:**  
A "financial hygiene engine" — a subscription service that periodically audits a user's financial life for dormancy risks, outdated KYC, expiring nominations, lapsing policies, uncollected dividends, and inoperative accounts, and generates a personalized action list.

---

### Problem 10: IEPF Share Recovery Is Effectively Inaccessible to Ordinary Investors

**User Segment:** Retail investors or legal heirs trying to recover shares/dividends transferred to the Investor Education and Protection Fund (IEPF).

**User Journey:**
Rajesh's late father held shares of a public sector company that paid dividends for 10 years. His father never claimed the dividends (they were sent by cheque to an old address). After 7 years of unclaimed dividends, both the dividends and the shares were transferred to IEPF. Rajesh now must:
- File Form IEPF-5 online
- Attach multiple documents including a Demat account statement, indemnity bond, and a notarized affidavit
- Mail physical documents to the company's registered office
- Wait for the company's nodal officer to verify and forward to IEPF authority
- Wait for IEPF authority to credit shares to his Demat account

This process routinely takes 6–18 months and has multiple rejection points.

**Evidence:**
- IEPF corpus: ₹20,000+ crore in shares and dividends transferred to IEPF (Ministry of Corporate Affairs data)
- The IEPF Form 5 process is widely cited in consumer forums as confusing, poorly documented, and prone to rejection for technical errors
- Shares transferred to IEPF continue to exist in the claimant's name in IEPF's records — but recovering them requires physical paperwork and company intermediation
- Legal heirs face additional complexity: they must first establish legal heirship before IEPF will process the claim
- The beta name-search feature on IEPF "rarely works" (fee-only investment advisers report, 2025)
- Moneylife coverage of the Supreme Court PIL notes IEPF as one of the most underserved of the five unclaimed asset recovery systems

**Severity: HIGH**  
Shares in growth companies (now much higher value) are permanently out of reach for families who cannot navigate the process.

**Frequency: MEDIUM**  
Not everyone holds physical shares, but the ~2 crore retail investor base in older company shares makes this a large absolute number.

**Existing Solutions:**
- IEPF portal (government) — functional but complex
- Some CA firms help with IEPF claims (expensive, slow)

**Why Existing Solutions Fail:**
- Form IEPF-5 is technically demanding and error-prone
- The two-step process (company + IEPF) doubles failure points
- Physical document submission is a major burden for heirs in different cities
- No status tracking transparency once filed

**Opportunity Gap:**  
An IEPF claim filing and tracking service — a managed service that handles the complete IEPF recovery process (Form-5, documents, company liaison, status tracking) for a fixed fee or success fee, making share recovery accessible to ordinary families.

---

### Problem 11: Widows and Women Who Were Excluded From Financial Decisions Are Uniquely Vulnerable

**User Segment:** Widows and women who were not the primary financial manager in their household — especially in semi-urban and rural India.

**User Journey:**
Kamla, 58, from Bhopal. Her husband managed everything. She knows they had "something in LIC" and some land in the village. She doesn't know his UAN, his PAN, or even the name of his bank. She is grieving, under pressure from in-laws, and afraid of being cheated. She doesn't know who to trust.

This is not rare. It is the majority experience for women of this generation in India.

**Evidence:**
- "Money is not openly discussed in typical Indian families. Wives and daughters are usually kept outside money discussions" (Outlook Money, January 2026)
- Death and money are culturally taboo — many women learn the family's financial situation only after widowhood
- Cultural barriers and patriarchal norms deter women from claiming rights, especially in rural areas (HelpAge India data cited in 2025 succession dispute analysis)
- 50% of inheritance disputes involve gender-based claims (NJDG data, 2025)
- Elderly women targeted disproportionately by financial fraud — the "digital arrest" scam preys on fear and unfamiliarity
- Women excluded from HUF decisions are often unaware of ancestral property rights they legally possess
- Post-COVID deaths disproportionately impacted breadwinners, leaving many women in exactly this situation

**Severity: HIGH**  
Financial exclusion compounds grief and can result in permanent poverty.

**Frequency: HIGH**  
India's demographic structure (large cohort of 50–70-year-old women, many in patriarchal households) makes this extremely common.

**Existing Solutions:**
- Government legal aid (NALSA) — severely underfunded and inaccessible
- NGOs (patchy, geography-specific)
- No commercial product that serves this segment affordably

**Why Existing Solutions Fail:**
- High-cost legal services are inaccessible
- Trust deficit: who can a recently widowed woman in Bhopal trust to help her without exploiting her?
- Language barriers (most financial information is in English or complex Hindi)
- No product designed for financial onboarding of a grieving, non-digital adult

**Opportunity Gap:**  
A vernacular, human-assisted financial onboarding service for newly widowed and financially excluded women — helping them identify what they own, establish legal heirship, and access their funds, with a fee model calibrated to their economic reality.

---

### Problem 12: Physical Share Certificates and Pre-Demat Holdings Are a Bureaucratic Dead End

**User Segment:** Families of investors who bought shares before dematerialization (pre-2000), or those holding shares in physical form from gifts, inheritance, or rights issues.

**User Journey:**
A family in Pune discovers a box containing physical share certificates for companies their grandfather bought in the 1980s. Some certificates are faded. Some companies may have merged, renamed, or been delisted. They don't know: are these worth anything? How do they convert them? Whom do they contact?

**Evidence:**
- SEBI mandated that all securities be held in demat form only, effective April 2024 — physical shares can no longer be traded until dematerialized
- Millions of physical certificates remain unconverted because holders are deceased, untraceable, or unaware
- IEPF holds many such shares; but many are also simply stuck with heirs who don't know the process
- Demat conversion requires KYC, a Demat account, and the original share certificate — if the certificate is damaged or the company has changed identity, the process becomes complex
- RTA (registrar and transfer agent) processes vary by company
- Many old certificates relate to companies that have undergone multiple corporate actions (splits, buybacks, mergers) — the current equivalent value requires research

**Severity: MEDIUM-HIGH**  
Assets are stranded and may represent substantial value. The research burden is high.

**Frequency: MEDIUM**  
Concentrated among families of investors from the pre-2000 era, but absolute numbers are large.

**Existing Solutions:**
- Depository participants offer demat conversion, but only for valid, live certificates
- IEPF for transferred shares
- No service that handles the full journey: identify → verify corporate history → convert or claim from IEPF

**Opportunity Gap:**  
A physical-to-digital share recovery service — a managed service that takes physical certificates, researches corporate history, establishes current ISIN equivalents, handles conversion through a DP, and manages any necessary IEPF filings.

---

## Part II: Final Synthesis

### Step 1: Top 20 Problems Ranked

| Rank | Problem | Pain | Frequency | Solution Gap | Kustodian Fit |
|------|---------|------|-----------|--------------|---------------|
| 1 | Families cannot discover all assets after death | High | Very High | High | Very High |
| 2 | No centralized financial life record / "family financial passport" | High | Universal | High | High |
| 3 | Nomination gaps and mismatches across institutions | High | High | High | High |
| 4 | Post-death document and process navigation | High | High | Medium | Very High |
| 5 | NRI remote management of parental assets | High | High | High | High |
| 6 | Elderly excluded from own financial accounts | High | Very High | High | Medium |
| 7 | Insurance claim appeal (rejected claims) | High | High | High | Medium-High |
| 8 | Preventive asset dormancy monitoring | Medium-High | Very High | High | High |
| 9 | Women financially excluded after death of spouse | High | High | Very High | High |
| 10 | IEPF share recovery | High | Medium | High | Very High |
| 11 | Digital assets at death | High | Low-Medium (rising) | Very High | Low-Medium |
| 12 | Physical share conversion | Medium | Medium | Medium | High |
| 13 | Property mutation after inheritance | Medium | High | Medium | Medium |
| 14 | Post-death ITR filing for deceased | Medium | High | Medium | Medium |
| 15 | Succession certificate complexity | High | Medium | Medium | High |
| 16 | HUF asset tracking and dissolution | Medium | Medium | High | Medium |
| 17 | Pension/gratuity claim after death | High | Medium | Medium | High |
| 18 | Post-retirement EPF annuity navigation | Medium | Medium | Medium | Medium |
| 19 | Corporate benefit/ESOP claim post-death | Medium | Low | High | Medium |
| 20 | Minor heirs' asset management until majority | Medium | Medium | High | Medium |

---

### Step 2: Recurring Themes

**Theme A: The Discovery Problem**  
India has no unified, accessible, family-facing system to discover what assets a person holds — before or after their death. Every problem in the top 5 traces back to this.

**Theme B: The Preparedness Gap**  
India's cultural taboo around death and money, combined with no accessible tools, means virtually no middle-class family has a financial succession plan. The "preparation" market is almost entirely unaddressed at the mass-market level.

**Theme C: Process Navigation**  
Even when assets are known, the bureaucratic journey to claim or transfer them is fragmented, opaque, and hostile to ordinary families. The post-death checklist is different for every asset class, and no product aggregates this.

**Theme D: Vulnerable Populations**  
The elderly, widows, and rural families face the same problems as everyone else — but with no digital capability, no English literacy, and no ability to self-serve through online systems. They are the most underserved and most at-risk subgroup.

**Theme E: Prevention vs. Cure**  
The entire market (including Kustodian) currently addresses claims — the end-stage. The much larger and less addressed market is prevention: keeping assets from becoming dormant, nominations from lapsing, and families from being blindsided.

---

### Step 3: The 10 Strongest Opportunity Areas

**1. Family Financial Passport (Pre-death asset inventory + sharing)**  
- Pain: Severe (universal)
- Solution gap: Very high (no mass-market product)
- Kustodian fit: High (directly enables the asset discovery workflow Kustodian already solves downstream)

**2. Post-Death Financial Checklist Engine**  
- Pain: Severe
- Solution gap: High
- Kustodian fit: Very high (Kustodian already helps at individual claim level; this is the meta-layer)

**3. Nomination Health Dashboard (Cross-institution audit + update)**  
- Pain: High
- Solution gap: High
- Kustodian fit: High (directly adjacent to the "why assets become unclaimed" problem)

**4. NRI Parental Asset Remote Management**  
- Pain: Severe
- Solution gap: High
- Kustodian fit: High (NRI asset recovery is already a use case; this is the preventive/remote version)

**5. Elderly Financial Guardian Layer**  
- Pain: Severe
- Solution gap: Very high
- Kustodian fit: Medium-high (requires user design rethink for non-digital segment)

**6. Insurance Claim Appeal Service**  
- Pain: High
- Solution gap: High
- Kustodian fit: Medium-high (claim recovery expertise is directly applicable)

**7. IEPF Share Recovery (Managed)**  
- Pain: High
- Solution gap: High
- Kustodian fit: Very high (Kustodian already does managed claim recovery; IEPF is an underserved claim type)

**8. Preventive Asset Dormancy Monitoring ("Financial Hygiene Engine")**  
- Pain: Medium-high
- Solution gap: High
- Kustodian fit: High (prevents the problems Kustodian currently solves reactively)

**9. Widowhood Financial Onboarding (Vernacular, Human-Assisted)**  
- Pain: High
- Solution gap: Very high
- Kustodian fit: High (vulnerable-population navigation is core to what Kustodian does)

**10. Physical Share Certificate Recovery**  
- Pain: Medium-high
- Solution gap: Medium
- Kustodian fit: High (asset recovery expertise directly applicable)

---

## Part III: Product Directions (Post-Analysis)

The following are suggested only after the problem analysis above. Each is adjacent to Kustodian's domain, addresses a distinct underserved segment, and could plausibly be launched as a standalone product.

---

### Product Direction A: "FamilyVault" — Family Financial Passport

**Why Promising:** The single biggest reason assets become unclaimed is that family members don't know they exist. A structured financial inventory, shared with family, is the upstream intervention that prevents the downstream recovery problem. No mass-market Indian product exists for this.

**Why Adjacent to Kustodian:** Kustodian's users are people discovering forgotten assets — often after years of dormancy. FamilyVault solves the root cause. It is the product Kustodian's users wish their deceased relatives had used.

**Why Standalone:** A financial passport is useful independent of any claim recovery workflow. It can be sold on a subscription basis to anyone 30+ with financial products. It is not a feature of claim recovery — it is prevention.

**What It Is:** A guided, mobile-friendly tool that helps users create a complete inventory of their financial life (accounts, policies, PF, property, nominees, agent contacts, locker locations, digital accounts). The inventory is encrypted, stored, and released to designated family members through a simple, trust-based trigger mechanism (e.g., nominee confirms death with a death certificate).

**Implementation Complexity:** Medium. Requires secure data storage, a simple UX for non-tech users, and a legally defensible access-release mechanism. No complex integrations required in V1. The moat is trust and structured content design.

**Business Value:** Large. Subscription model (₹500–₹2,000/year). Addressable market: 150+ million Indian adults with multiple financial products. Cross-sell to Kustodian's claim recovery service when needed.

---

### Product Direction B: "GriefMap" — Post-Death Financial Checklist Engine

**Why Promising:** Every Indian family that loses a member faces the same overwhelming process navigation problem, but the specific checklist varies by asset mix, family structure, and state of residence. A personalized, sequenced, step-by-step guide — not a generic article — fills a high-pain gap.

**Why Adjacent to Kustodian:** Kustodian helps with specific claims. GriefMap is the meta-layer that tells families what claims to file, in what order, with what documents. It would naturally feed users into Kustodian's claim-recovery service.

**Why Standalone:** A checklist engine is valuable to families who don't end up needing Kustodian's recovery services (e.g., all nominations are in place, assets are small). It generates value on its own for a broader segment.

**What It Is:** A tool that generates a personalized, prioritized, step-by-step financial administration checklist for a deceased person's estate, based on inputs (known assets, nominees, state, religion, family structure). Each step includes: what to do, what documents you need, whom to contact, expected timeline, and what to do if rejected.

**Implementation Complexity:** Medium. The core is a decision-tree content engine with good UX. The hard part is keeping institutional process information current. V1 can be built as a guided questionnaire with curated content.

**Business Value:** Medium-large. Can be monetized as a premium service (₹1,500–₹5,000 per use), or offered free to convert users to paid claim recovery services.

---

### Product Direction C: "NomineePulse" — Cross-Institution Nomination Health Check

**Why Promising:** India has just overhauled its nomination rules across banking (Banking Laws Amendment, November 2025) and securities (SEBI circular, March 2025). Tens of millions of accounts have outdated, incorrect, or missing nominees. No product exists to audit this across institutions simultaneously.

**Why Adjacent to Kustodian:** Outdated nominations are a leading cause of the dormant asset and unclaimed inheritance problems Kustodian solves. This product prevents the problem upstream.

**Why Standalone:** Nomination management is a recurring, subscription-worthy need independent of any specific recovery event. It is also a highly shareable, viral product — "check if your family is protected" is a clear call to action.

**What It Is:** A tool that allows users to input their PAN and consent, then aggregates nominee status across financial institutions (pulling from KYC data and institution APIs where available), flags outdated or missing nominees, identifies legal-vs-nominee mismatches, and provides step-by-step update instructions for each institution.

**Implementation Complexity:** Medium-High. Aggregating real-time nominee data requires institution partnerships or API access. V1 can start with a guided self-audit (user manually enters nominee details from each platform) with smart analysis and update instructions.

**Business Value:** Medium. Subscription or per-check model. Can upsell to FamilyVault and GriefMap.

---

### Product Direction D: "NRI Guardian" — Remote Parental Asset Management for NRIs

**Why Promising:** 32 million NRIs, most with aging parents in India holding complex assets. The estate planning gap for NRI families is documented, growing, and poorly served. This is a high-willingness-to-pay segment.

**Why Adjacent to Kustodian:** Kustodian already handles NRI asset recovery. NRI Guardian is the proactive version — managing before things go wrong.

**Why Standalone:** NRI asset management involves ongoing tasks (premium reminders, FD maturity alerts, property tax, tenant management liaison) that are not claim-recovery specific. It is a recurring relationship, not a one-time transaction.

**What It Is:** A service for NRIs that provides: (a) a structured inventory of their parents' financial assets; (b) calendar-based reminders for renewals, maturities, and due dates; (c) a network of verified local agents/CAs for physical tasks; (d) POA drafting and apostille coordination assistance; and (e) death-event response coordination. Priced at ₹5,000–₹15,000/year.

**Implementation Complexity:** Medium. Content and coordination-heavy in early stages. Scale requires a verified local agent network and strong trust infrastructure.

**Business Value:** Large. High ARPU, strong retention, and high referral potential within NRI communities.

---

### Product Direction E: "ClaimBack" — Insurance Claim Appeal Service

**Why Promising:** ₹26,000 crore in health insurance claims rejected in FY2024 alone. Many rejections are legally challengeable. The IRDAI Ombudsman process is free and claimant-favorable — but unknown to most families. A success-fee model makes this accessible and self-funding.

**Why Adjacent to Kustodian:** Kustodian's core skill is navigating bureaucratic recovery processes. Insurance appeal is a structurally identical workflow: identify the claim, gather documents, engage the institution, escalate to regulator.

**Why Standalone:** Insurance claims are a distinct domain from EPF/bank/share recovery. They involve IRDAI, ombudsmen, and consumer courts. The user journey is different (grieving nominee vs. dormant account holder). The product can stand alone with its own brand and user acquisition strategy.

**What It Is:** A service that evaluates rejected life and health insurance claims, identifies legal grounds for appeal, manages the IRDAI Ombudsman filing on behalf of the claimant, and charges a success fee (e.g., 5–10% of the recovered amount, with a minimum). No upfront cost to the claimant.

**Implementation Complexity:** Low-Medium. The core is legal knowledge + process management. V1 can be case-by-case with a small team of insurance-literate associates. Scale requires automation of initial claim assessment.

**Business Value:** Large. Success-fee model aligns incentives. High-value claims (₹5–50 lakh) generate meaningful revenue per case. Potential to handle hundreds of cases per month.

---

## Appendix: Evidence Summary Table

| Domain | Key Statistic | Source |
|--------|--------------|--------|
| Total unclaimed financial assets (India) | ₹1.96–3.5 lakh crore | SEBI, RBI, IRDAI, MCA, EPFO |
| Unclaimed bank deposits | ₹78,000 crore (March 2024, +26% YoY) | RBI |
| Inoperative EPF accounts | ₹8,505 crore (2023-24) | Ministry of Labour, Lok Sabha |
| Unclaimed insurance | ₹25,000 crore | IRDAI |
| Unclaimed mutual funds | ₹3,400+ crore | SEBI |
| Indians dying without a will | 60–80% | NoBroker 2025, Liberty University 2017 |
| NRIs without estate plans | 85% | GoINRI |
| India estate planning vs US | <10% vs 46% | TBNG Capital report |
| Insurance claim rejection (FY24) | 11% rejected, ₹26,000 crore repudiated | IRDAI Annual Report |
| Digital fraud (2021-2025) | 10x increase in cases, 40x increase in value | National Cyber Crime Portal |
| Senior citizens as fraud victims | 60% of cases in some cities | Nagpur Cyber Police data |
| UDGAM portal users | 20 lakh users, 44 lakh searches (by April 2026) | RBI (Supreme Court hearing, May 2026) |
| DEAF fund recovery rate | Under 4% | Moneylife / Supreme Court hearing |
| Succession disputes involving gender | 50% of inheritance disputes | NJDG data |
| Digital asset access disputes | 50% of urban inheritance disputes | Pravasitax / Doon Law Mentor 2025 |

---

*This report is intended as a problem-space map to inform product discovery. Product directions in Part III are preliminary and require validation with target users before any build decision.*
