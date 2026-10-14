# Tortuga Scrims Privacy Policy

**Effective Date:** October 2026  
**Last Updated:** October 2026

## 1. Introduction
Tortuga Scrims ("the Bot", "we", "our") is a Discord application designed to provide automated esports tournament management, community onboarding, and server automation. This Privacy Policy explains our practices regarding the collection, processing, storage, and protection of user and server data when using Tortuga Scrims.

By inviting or interacting with Tortuga Scrims, you agree to the collection and use of information in accordance with this Privacy Policy.

---

## 2. Information We Process and Collect

To operate its core functions, Tortuga Scrims collects and processes minimal necessary data:

### A. General Discord Identifiers
- **User IDs:** Used to identify team captains, players, and authorized administrators.
- **Server (Guild) IDs:** Used to associate server-specific configurations and active events.
- **Role & Channel IDs:** Used to configure administrative permissions, IDP channels, and stage roles.

### B. Tournament & Event Registration Data
- Team names, clan tags, and registered player Discord IDs submitted through registration forms or interactive components.
- Scrim and tournament match records, group allotments, and placement results.

### C. Server Members Intent (`GUILD_MEMBERS`) Processing
- **Member Join Events:** Processes incoming member IDs and avatars ephemerally to render custom welcome greeting cards and assign starter auto-roles.
- **Server Roster Verification:** Evaluates member IDs during tournament registration to ensure registered players are active server members before issuing competitor roles.

### D. Message Content Intent (`MESSAGE_CONTENT`) Processing
- **Ephemeral Autoresponder Matching:** When enabled by server administrators, the bot passively evaluates message text in designated channels solely in volatile memory to match configured keyword triggers (Exact, Contains, Starts-With).
- **Modmail Direct Messages:** Reads text messages sent directly to the bot's DMs to relay support inquiries to server staff threads.
- **Sticky Message Channel Flow:** Detects message flow in channels with active stickies to re-anchor tournament announcements to the bottom.

---

## 3. Information We Do NOT Collect or Store

Tortuga Scrims strictly adheres to the principle of data minimization:
- **No Message Content Storage:** We do **NOT** store, log, archive, or database message text. All message content processed for autoresponders is evaluated ephemerally in RAM and immediately discarded.
- **No Voice or Media Scraping:** We do not record voice calls or scrape user media files outside bot-specific interactions.
- **No Personal Identifiable Information (PII):** We do not collect passwords, real-world addresses, or payment card information.

---

## 4. How We Use Information

Collected data is used strictly to:
- Register teams and allocate competitive scrimmage slots.
- Assign and remove Discord roles based on tournament stage qualification or leave actions.
- Automatically reply to member questions via the keyword autoresponder.
- Deliver onboarding welcome cards to newly joined members.
- Maintain tournament database integrity and crash-recovery state.

---

## 5. Storage and Third-Party Infrastructure

Stored data is restricted to tournament rosters and server settings, hosted on secure infrastructure:
- **Database Storage:** SQLite (WAL mode) and Google Firebase Realtime Database for operational state.
- **Export Services:** Google Sheets API (used strictly when server administrators explicitly configure export tabs for tournament brackets).

We do **not** sell, rent, monetize, or share user data with third-party advertisers or data brokers under any circumstances.

---

## 6. Data Retention and Deletion Rights

- **Retention Duration:** Registration data is retained only for the duration of the active tournament or competitive season, after which it is archived or purged by server administrators.
- **Right to Erasure / Deletion:** Users have the right to request the complete deletion of their stored data at any time.
  - Players can remove themselves from teams directly via the interactive **Leave Team** button.
  - Server owners or individual users can request complete data purge by contacting us in the official support server or via email. Requests are honored within 48 hours.

---

## 7. Children's Privacy
Tortuga Scrims does not knowingly collect data from children under the age of 13 (or the minimum legal age of digital consent in their jurisdiction), in full compliance with Discord's Terms of Service.

---

## 8. Changes to This Policy
We reserve the right to update this Privacy Policy to reflect technical updates or Discord Developer Policy modifications. Continued use of the Bot constitutes acceptance of any revised terms.

---

## 9. Contact Us
For questions, data deletion requests, or support regarding this Privacy Policy:

- **Official Support Server:** https://discord.gg/tortuga
- **Support Email:** esports@tortugagaming.com
