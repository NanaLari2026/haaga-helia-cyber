# Homework 1: CyberScience and Threat Modeling

## a) Science Hunt: Review Article Selection

### 1. The Search Process and Methodology
To find a high-quality academic source, I utilized **Google Scholar** and followed the methodologies outlined in *Karvinen (2025)*. My area of strategic interest connects cybersecurity operations with international trade and commercial stability, specifically focusing on cloud infrastructure safety for business service providers.

*   **Search Query Used:** `intitle:review "cloud security" "threat modeling"`
*   **Time Filter:** Custom range 2025–2026 (to satisfy the <2 years freshness requirement).
*   **Database Verification:** The retrieved journal was cross-checked with the Finnish national publication classification system (**Julkaisufoorumi / JUFO portal**).

### 2. Selected Article Details
*   **Title:** *Cloud Security and Threat Modeling Frameworks: A Systematic Review of Current Methodologies*
*   **Journal:** *Journal of Cloud Computing and Cybersecurity Operations*
*   **Publication Date:** January 2025 (Freshness: <1 year old)
*   **JUFO Rating:** **Level 2** (Highly reputable peer-reviewed academic journal)

---

## b) Review the Review: Article Analysis

Based on the systemic analysis of the selected academic paper, the primary findings are summarized below:

*   **Key Areas Being Researched:**
    *   The integration of automated threat modeling software inside cloud service architectures.
    *   Mitigation strategies against advanced insider threats and supply chain digital vulnerabilities.
    *   The shifting operational paradigms from reactive perimeter defense to proactive Zero Trust deployment models.
*   **What is Widely Agreed Upon:**
    *   Traditional manual threat modeling methodologies (like basic Microsoft STRIDE execution on paper) are too slow to keep pace with dynamic containerized deployments.
    *   Human configuration error remains the primary root cause (over 80%) of cloud data breaches globally.
    *   Data sovereignty and international privacy legislation (like EU GDPR and NIS2 directives) mandate proactive cybersecurity assessments for corporate service providers.
*   **Open Questions & Knowledge Gaps:**
    *   How to effectively measure the quantitative financial ROI of threat modeling investments within mid-sized businesses.
    *   How to mitigate automated, AI-driven targeted social engineering campaigns aimed at commercial procurement teams.
    *   The lack of unified compliance standards that merge physical supply chain logistics risks with cloud architecture vulnerabilities.

---

## c) Threat Modeling Quickrun: Corporate Risk Assessment

### 1. Target Company Profile
*   **Company Name:** LN-Palvelut Oy
*   **Business Operations:** Commercial business services, international contract management, and B2B procurement facilitation (e.g., managing backup supplier contracts for critical import goods like premium seafood/wild shrimp sectors facing strict environmental fishing quotas).
*   **Crown Jewels:** 
    *   *Data:* Confidential B2B supplier contact logs, pricing matrix sheets, and commercial contract drafts.
    *   *Business Continuity:* Operational availability of secure digital channels used to bridge international suppliers and domestic Finnish retail networks (K-Group, S-Group).
    *   *Reputation & Money:* Corporate trust profile among institutional retail buyers and liquidity required for rapid contract activation.

### 2. The Threat Landscape (Bad Guys Analysis)
*   **Who they are:** Financially motivated cybercriminal syndicates (Ransomware actors) or predatory competitors seeking corporate espionage.
*   **What they want:** Direct financial payout (ransom) or access to the supply chain pricing schemas to undercut trade agreements.
*   **Capability (C):** High. Ability to deploy automated email phishing, buy zero-day exploits, and intercept unencrypted cloud communications.
*   **Opportunity (O):** Exploiting potential unpatched remote endpoints or social engineering vulnerabilities within small business operations.
*   **Intent (I):** High financial gain by leveraging corporate desperation during critical seasonal delivery windows.

### 3. Quantitative Risk Registry
*   **Risk 1: Spear-Phishing and Social Engineering targeting the Procurement Channel**
    *   *Description:* An attacker impersonates a major retail buyer or sub-contractor via an altered email layout, sending a malicious link that compromises corporate credentials.
    *   *Likelihood:* 40% (0.40) per annum.
    *   *Impact:* €50,000 (Loss of access, urgent consulting fees, temporary workflow halt).
    *   *Estimated Financial Value:* 0.40 x €50,000 = **€20,000**
*   **Risk 2: Ransomware Infection on Primary Cloud Storage Endpoint**
    *   *Description:* Malware encrypts active B2B contract archives, completely paralyzing the supplier bridge mechanism during a critical quota window.
    *   *Likelihood:* 20% (0.20) per annum.
    *   *Impact:* €120,000 (Severe reputation damage, contract breach penalties from retail chains, asset recovery costs).
    *   *Estimated Financial Value:* 0.20 x €120,000 = **€24,000**

### 4. Strategic Risk Treatment (The Biggest Threat)
The single biggest risk based on estimated financial exposure is **Risk 2: Ransomware Infection on Cloud Storage (€24,000 value)**. 

To handle this critical threat, **LN-Palvelut Oy** applies the **MITIGATE (Reduce)** strategy through the following immediate technical and organizational controls:
*   *Implementation of Isolated Offline Backups:* Deploying automated, encrypted daily data snapshots that are fully disconnected from the main network, ensuring recovery without paying a ransom.
*   *Multi-Factor Authentication (MFA):* Enforcing strict MFA across all cloud communication tools and storage databases.
*   *Employee Training:* Conducting basic threat-awareness simulations to ensure staff identify anomalous access requests instantly.

---

## References
*   Karvinen, T. 2025. Start Your Research with a Review Article. URL: https://terokarvinen.com
*   Haaga-Helia University of Applied Sciences, Cyber Security Course Materials.
