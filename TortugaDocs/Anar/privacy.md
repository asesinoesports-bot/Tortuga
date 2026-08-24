# Privacy Policy

**Effective Date:** 24th August 2026

## 1. Introduction
Thank you for using the Anar Bot ("the Bot"). This Privacy Policy explains what information we process, how we use it, and your rights concerning your data. We aim to be fully transparent about our data handling practices.

## 2. Information We Process
We collect and store information necessary to provide the Bot's core functionality. This information is limited to Discord API data and user configurations. 

## 3. Discord Data
We process the following Discord data when you use the Bot:
*   **Guild (Server) Information:** Guild IDs, channel IDs, and role IDs to facilitate server management, auto-roles, and role persistence.
*   **Member Information:** We process member statuses (such as current roles) to facilitate cross-guild role syncing and bulk role management.
*   **User Information:** User IDs are stored temporarily or long-term depending on the specific feature configured by server administrators (e.g., review desk configurations).

## 4. How We Use Data
The data we collect is used exclusively for:
*   Providing server administration features, such as sticky messages, custom role commands, and auto-roles.
*   Synchronizing roles across multiple servers.
*   Allowing server administrators to back up and clone category structures.

## 5. Data Stored Outside Discord
We store configuration data and state information in a local database to ensure the Bot functions correctly across restarts. The data stored includes:
*   Server settings (prefixes, configured log channels, managed categories).
*   Role claim mappings and custom role command triggers.
*   Channel IDs for sticky messages and auto-roles.
*   Category cloner export payloads.

## 6. Message Content
The Bot explicitly requires the Message Content intent to function. We read message content to:
*   Process standard text commands (e.g., starting with `!`).
*   Evaluate custom role commands set up by server administrators.
*   Detect and resend sticky messages in designated channels.

**Storage of Message Content:** We do **not** log general user chat. However, the text content of **Sticky Messages** (configured by server administrators via the `!sticky add` command) is stored in our database so the bot can automatically resend it when new messages are posted. No other message content is stored off-platform. **Message content is never used to train machine learning or AI models.**

## 7. Member Information
We utilize the Server Members Intent to provide our features. The Bot fetches and reads member lists to:
*   Add or remove roles from multiple members simultaneously.
*   Verify membership and roles across different servers for our role-syncing features.
*   Process giveaway eligibility.

## 8. Presence / Activity Information
The Bot does **not** process, read, or store any Discord Presence or Activity information (such as online status, custom status, or game activity). 

## 9. Data Retention
Data is stored indefinitely to ensure persistent configuration and uninterrupted functionality. We do not have an automated 30-day deletion or TTL (Time-To-Live) policy for stored data. 

## 10. Data Deletion Requests
If you wish to have your data removed, or if a server administrator wants to completely wipe their server's configuration from the database, please contact us directly using the information provided below. Server administrators can also manually delete specific configurations (like sticky messages or custom roles) using the Bot's built-in commands.

## 11. Data Security
Data is stored in a local SQLite database. Please note that data is **not** encrypted at rest. We rely on standard server security practices to protect the host machine where the database is located. 

## 12. Third-Party Services
We do not share, sell, or transfer any data to third-party services, analytics providers, or AI/ML training platforms.

## 13. Discord's Role
This Bot operates on the Discord platform. By using the Bot, you are also subject to [Discord's Privacy Policy](https://discord.com/privacy) and [Discord's Terms of Service](https://discord.com/terms).

## 14. Children's Privacy
The Bot is not intended for use by children under the age of 13 (or the minimum age of digital consent in your country). We do not knowingly collect personal information from children.

## 15. Changes to This Policy
We may update this policy as new features are added. We encourage users to review it periodically.

## 16. Contact
If you have any questions, concerns, or data deletion requests, please contact the bot operator at:
Email: esports@tortugagaming.com
Discord Support Server: https://discord.gg/tortuga

