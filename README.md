# VladStreamReset
repo for extension configs for VladStreamReset OpenSource project
# StreamReset Pro – Remote Config Repo

### 🔐 This repo controls the remote config for my StreamReset browser extension.

StreamReset is a lightweight tool that:
- Clears cookies after website video watching limits hit
- Rotates IPs using ScraperAPI(Soon to be change to better one/cheaper one...free one)
- Unlocks full access to sites like moviebox.ng where high res streaming is capped at 6 videos per day. 
- Manages license expiration and feature control
- Sends updates via GitHub-hosted JSON

---

## 🔧 This Repo Hosts:

- `config.json`: My live JSON file fetched by the extension to:
  - Remotely expire license keys(I don't have an organized structure to automatically do that as of yet)
  - Enable/disable specific features (e.g. auto-clear, IP spoofing)
  - Push messages to users (e.g. payment required, update notices)

---

## 🧪 Sample Use Case

Student installs the extension.  
After 6 movies, the extension:
1. Clears cookies/localStorage
2. Switches IP via ScraperAPI
3. Checks this repo for license status
4. Updates user session silently

---

## 🧠 Who’s Behind This?

Built by a university student solving a real campus problem.  
Made for students, by a student -Me, Theo | follow me at https://x.com/kailogs01 |I'm also a writer, check out my latest work on X!!   
This Extension and this repo make me passive income, recurring revenue, and real utility.


