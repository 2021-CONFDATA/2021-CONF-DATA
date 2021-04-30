# Please note
Due to the large project size (including all commit data), we only publish the vulnerability fix data for now. We are currently undergoing the company process to publish our model, and plan to publish it once complete. 


## Data Description:
### Vulnerability fixing commits 
- Stored in .csv format
- Columns:
  1. repo: A URL to the GitHub repository the commit belongs to (e.g., "https://github.com/spring-projects/spring-webflow").<br/>
  2. commit_id: The ID of the commit (e.g., "57f2ccb66946943fbf3b3f2165eac1c8eb6b1523").<br/>
  3. Cve_id: The ID of the CVE the commit corresponds to (e.g., "CVE-2017-4971"). If the commit was labelled as a vulnerability fix by the regular expression (which matches words "vuln", "cve", or "NVD" in the commit's message), this value will be NaN.
