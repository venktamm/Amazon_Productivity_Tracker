
Productivity Tracker

A Tampermonkey userscript for Amazon case management systems (Paragon & Photon).

 Version
Current: v6.4.1

 Features
- Real-time dashboard with case count, AHT, and efficiency score
- AUX status monitoring (Available, Break, Offline, etc.)
- Multi-UoW Photon case tracking with composite key system
- Auto-export CSV when AUX status changes to Offline
- Monthly scorecard generation (21st–20th period)
- Calendar view with historical performance metrics
- Excel upload for case status updates

 Installation
1. Install tampermonkey.net/ in Chrome
2. Click on the `.user.js` file in this repo
3. Click **Raw**
4. Tampermonkey will detect the script and prompt you to install it
5. Click **Install**

 Supported Systems
- Amazon Paragon (case management)
- Amazon Photon (UoW workflow)

 Queue Types Tracked
- HSI Queue
- Initial Validation
- ASIN Review
- PAA

 Export Format
Auto-exported CSV includes: Date, Case ID, Type, Queue, Status, Reason Code, AHT (min), ASIN Count, ASIN Adjustment + summary section.

 Notes
- Data is stored locally using Tampermonkey's GM_setValue/GM_getValue
- Auto-export triggers when AUX status changes to Offline
- Use 24-hour format for scheduling preferences
