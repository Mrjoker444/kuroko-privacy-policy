# Kuroko Bots — Privacy Policy

**Developer:** Zaw (@zawgoat)  
**Support:** https://discord.gg/j7NZeQf8Uz  
**Last updated:** 13 October 2026

## 1. Scope

This policy explains the data processing associated with the Kuroko Discord bots described in the [Kuroko Bots catalogue](https://github.com/mrjoker444). The detailed technical practices below are based on the available **Kuroko ザウ Security & Moderation** project. Other Kuroko bots may process additional categories of data described in Section 4; their individual implementation, retention and hosting practices must be verified before this policy is presented as covering them fully.

## 2. What Kuroko ザウ processes

Depending on enabled features and server configuration, the bot may process Discord user, member, guild, channel and role identifiers; member roles and join events; moderation actions, reasons and related timestamps; guild configuration, whitelists and staff permissions; message text for prefix commands and enabled anti-link/anti-token protections; presence and client status for the `+device` feature; and voice-state information for voice utilities.

The `snipe` and `editsnipe` utilities may temporarily retain deleted or edited message text and related metadata in the bot's process memory. Moderation/security events may also be posted to Discord log channels selected by server administrators. Such channels are controlled by the respective Discord server and its permissions.

## 3. Why this data is used

Data is used to execute requested commands, administer server roles, verify members, protect communities against configured security threats, record moderation decisions, operate utilities, and troubleshoot service reliability. Message inspection for security can occur on ordinary messages in servers where the relevant protections are enabled; it is not limited to messages beginning with a bot prefix.

## 4. Other Kuroko bots

The Kuroko ecosystem also includes Check, Logger, Tracker, Security (Shield), Music, Invites, Limit, Games and Pulse. Their documented features can involve member and role checks, server event logging, message edit/delete logs, voice activity, user-requested tracking, invite counts, music queues, points, and temporary voice-room management. The exact data collected, retention, user controls and security measures for **each separate application** must be confirmed from its deployed code and configuration. No claim of universal opt-out or universal no-storage is made here.

## 5. Storage and retention

Kuroko ザウ uses local persistent storage, including SQLite, for some configuration and moderation information. Such records can remain until changed or deleted by an administrator or developer; **a guaranteed 30-day deletion schedule has not been established**. Some message-recovery data may be held temporarily in application memory while the process runs. Discord channel logs are subject to the server's settings and Discord's platform behavior.

**Deployment verification required:** The developer must confirm hosting location, database backups, any automated retention/deletion jobs and encryption-at-rest controls before publishing stronger assurances. This policy does not claim that stored data is encrypted unless the deployment has been verified.

## 6. Sharing and access

Data may be visible to server administrators or authorized moderators through configured bot commands and server log channels. Hosting providers may process stored information as necessary to run the service. The bot is not intended to sell personal data. Discord itself processes data under its own policies.

## 7. Requests and choices

Users may contact **@zawgoat** on Discord or use the support server at https://discord.gg/j7NZeQf8Uz to ask about stored data or request deletion of eligible records. Requests will be reviewed and handled subject to technical capabilities, server moderation needs and applicable requirements. Server administrators can disable optional security or logging features where the bot provides configuration controls.

Using slash commands instead of prefix commands does **not** automatically prevent enabled anti-link/anti-token scanning. No universal per-user opt-out from all message processing or presence handling is claimed unless such a control is implemented and verified.

## 8. Security

Access to bot configuration and moderation features is restricted by Discord permissions and configured staff roles. Security of data at rest, backups and hosting must be verified for the actual deployment; this document does not certify encryption or other unverified technical controls.

## 9. Changes

This policy may be updated when features, data practices or deployment settings change. The updated date will be shown above. Material changes should be communicated through the bot's support resources.

## 10. Contact

**Developer:** Zaw (@zawgoat)  
**Support server:** https://discord.gg/j7NZeQf8Uz

---

**Publication note (remove after verification):** Before using this as a final public policy, confirm data retention, backup practices, encryption at rest, hosting arrangements, contact and deletion workflow, and the actual data practices of all nine other bots. If they differ materially, publish bot-specific policy sections or separate policies.
