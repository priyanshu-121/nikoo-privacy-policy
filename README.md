# Privacy Policy for Nikoo

Last updated: November 22, 2026

This Privacy Policy explains how the Discord application Nikoo ("we", "us", or "the bot") handles information when added to a Discord server or used by members.

By adding Nikoo to your server or interacting with it, you agree to the collection and handling of data as described in this policy.

---

### 1. Information We Collect

Nikoo collects only the minimum amount of data required to play audio, manage playback queues, and save server preferences.

#### A. Stored Information
We store the following details in our local database:
- Server (Guild) IDs and Channel IDs: Stored to remember server-specific settings, including 24/7 voice channel mode, preferred language, and default bot channels.
- User IDs: Stored only when a user explicitly creates a custom playlist, to link that playlist to its creator.
- Playlist Data: Track names and URLs saved by users in custom playlists.

#### B. Temporary In-Memory Data
Some features process data in temporary memory while the bot is running. This data is never written to disk, never stored in databases, and is deleted as soon as the action finishes:
- Voice Connection States: Channel IDs and voice session tokens supplied by Discord to route audio into voice channels.
- Message Content: Read strictly in designated channels to parse song links in request channels, evaluate answers during trivia games, and read text aloud for mic-less voice participants. Message content is dropped immediately after processing.

#### C. Information We Never Collect
- We do not collect passwords, payment details, email addresses, IP addresses, or phone numbers.
- We do not read or record private direct messages that do not involve commands directed to the bot.
- We do not record, store, or monitor voice channel audio.

---

### 2. How We Use Information

The data collected is used solely to provide and maintain bot features:
- Playing requested audio in voice channels.
- Managing server playback queues, volume levels, and repeat settings.
- Remembering server configurations across bot restarts.
- Running interactive features like music trivia and text-to-speech for users without microphones.

We do not sell, rent, trade, or monetize user data.

---

### 3. Data Storage and Security

- Stored settings and playlists reside in a secured database on our hosting servers with restricted administrative access.
- We use industry-standard measures to safeguard stored data.
- Transient operational data (such as message text and voice tokens) exists only in volatile system memory during execution.

---

### 4. Data Retention and Deletion

- Server configurations are kept as long as Nikoo remains in the server. If the bot is removed from a server, those settings become inactive and are eligible for routine cleanup.
- Custom playlists remain saved until the creator deletes them.
- Users can request complete deletion of their stored data (including playlists and server configurations) at any time. To request deletion, reach out through our support server or contact the developer directly at the contact details listed below. Requests are verified and processed within 7 business days.

---

### 5. Third-Party Services

Nikoo connects to third-party platforms to retrieve audio metadata and media streams:
- Discord API: Used to receive interactions, process gateway events, and deliver bot responses.
- Media Platforms (such as YouTube, Spotify, and SoundCloud): Used to search for tracks and resolve audio streams requested by users. No personally identifiable user information is shared with these platforms.

---

### 6. Children's Privacy

Nikoo complies with Discord's Terms of Service. The bot is not intended for use by children under the age of 13, or the minimum age of digital consent in your jurisdiction. We do not knowingly collect personal information from children.

---

### 7. Changes to This Policy

We may update this Privacy Policy as new features are added. Updates will be published to this repository with a revised "Last updated" date. Continued use of the bot after changes are posted constitutes acceptance of the updated policy.

---

### 8. Contact

For questions about this policy, or to request data removal, contact us at:
- Discord Support Server: https://discord.gg/HjZaBmFhYx
