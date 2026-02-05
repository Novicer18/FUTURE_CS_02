# FUTURE_CS_02
# Phishing Email Detection & Awareness System  
Cyber Security Task 2 (2026) – Future Interns

## 🛠️ Tools Used

The following tools were used to analyze email headers and validate sender authenticity:

### 1. Google Admin Toolbox – Message Header Analyzer
https://toolbox.googleapps.com/apps/messageheader/

- Used to analyze full email headers
- Identified SPF, DKIM, and DMARC authentication results
- Helped detect sender spoofing and domain mismatches

### 2. MXToolbox – SuperTool
https://mxtoolbox.com/SuperTool.aspx

- Used to inspect sender domains and IP reputation
- Verified DNS, SPF, and mail server configurations
- Assisted in identifying suspicious or misconfigured domains

### 3. Gmail “Show Original” Feature

- Used to extract the original email headers directly from Gmail
- Ensured header integrity and accuracy during analysis
- Allowed safe inspection without interacting with links or attachments

---

## 🔍 Analysis Approach

Each email was analyzed using a structured Security Operations Center (SOC) methodology:

1. **Header Examination**
   - Reviewed SPF, DKIM, and DMARC results
   - Checked for authentication failures or inconsistencies

2. **Sender Verification**
   - Compared the “From” address with the actual sending domain
   - Identified impersonation or spoofing attempts

3. **Link & URL Inspection**
   - Examined embedded links without clicking
   - Checked domain legitimacy and URL structure

4. **Content & Language Review**
   - Analyzed tone, urgency, and psychological manipulation techniques
   - Identified generic greetings and suspicious wording

5. **Risk Classification**
   - Classified each email as:
     - Phishing
     - Safe
   - Classification was based on combined technical and behavioral indicators
