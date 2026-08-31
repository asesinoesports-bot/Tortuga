# Privacy Policy for Transient Discord Bot

**Last Updated:** August 31, 2026

Thank you for using **Transient** ("the Bot"). We are committed to protecting your privacy. This Privacy Policy explains how the Bot collects, uses, stores, and protects your information in compliance with the Discord Developer Terms of Service.

---

## 1. Information We Collect
To provide temporary voice channel management, Transient collects and stores the following minimal data:
*   **User Identifiers (User IDs):** To track channel ownership, whitelisted (trusted) users, and blacklisted (blocked) users.
*   **Guild/Server Identifiers (Guild IDs):** To maintain system configurations, custom command prefixes, and moderator settings.
*   **Channel Identifiers (Channel IDs):** To monitor active voice channels, target categories, and logging channels.
*   **Voice/Presence Metadata:** Timestamps of when users join or leave temporary voice channels, and the names of games played by occupants (used solely for the majority-based channel auto-rename feature).

### 🔒 Crucial Voice Privacy Statement
*   **No Audio Recording:** Transient **does not** record, stream, store, or monitor any voice audio streams. Your conversations remain 100% private and encrypted through Discord's infrastructure.

---

## 2. How We Use the Information
Collected data is used strictly for the core features of the Bot:
*   Restoring your custom room settings (locked states, user limits, trust lists) when you create a new voice channel.
*   Authenticating that only the authorized owner or moderators can execute channel actions.
*   Routing event logs (creations, deletions, moderation kicks) to your server's designated logging channels.

---

## 3. Data Storage & Retention
*   **Storage:** All configurations and records are stored in a secure local SQLite database hosted on our private server.
*   **Retention:** 
    *   **User Preferences:** Saved until manually cleared via the controller panel or deleted by server staff.
    *   **Backups:** Local database snapshots are retained for exactly **10 days** and automatically deleted thereafter.
    *   **Deleted Channels:** Channels marked as deleted in the database are retained as historical records for server audit logs.

---

## 4. Your Rights & Data Deletion
You have complete control over your data.
*   **Manual Deletion:** You can clear your saved channel preferences at any time directly through the controller UI panel.
*   **Request Deletion:** If you want all historical logs or configurations associated with your Discord account or Guild deleted from our database, you can:
    1.  Join our Support Server: [https://discord.gg/tortuga](https://discord.gg/tortuga) and open a support ticket.
    2.  Send an email to: [esports@tortugagaming.com](mailto:esports@tortugagaming.com) with your user/guild ID.
*   All requests are processed and permanently deleted from our database within 48 hours.

---

## 5. Contact Us
If you have any questions or concerns regarding this Privacy Policy, please reach out to us:
*   **Support Server:** [https://discord.gg/tortuga](https://discord.gg/tortuga)
*   **Support Email:** [esports@tortugagaming.com](mailto:esports@tortugagaming.com)
