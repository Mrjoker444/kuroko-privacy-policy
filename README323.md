# 📚 Kuroko Bots —

> All Discord bots developed by **Zaw (@zawgoat)**
>
> [![Privacy Policy](https://img.shields.io/badge/Privacy%20Policy-Click%20Here-blue)](https://mrjoker444.github.io/kuroko-privacy-policy/)
> [![Support Server](https://img.shields.io/badge/Support%20Server-Join-green)](https://discord.gg/j7NZeQf8Uz)

---

## 📋 Bot Overview

| # | Bot Name | Type | Prefix | Slash Commands |
|---|----------|------|--------|:--------------:|
| 1 | [Kuroko ザウ](#1-kuroko-ザウ-security--moderation-bot) | Moderation & Security | `+` | ✅ |
| 2 | [Kuroko Check 🔎](#2-kuroko-check-) | Scanner & Checker | `+` | ✅ |
| 3 | [Kuroko Logger ♯](#3-kuroko-logger-) | Server Logger | `kk?` | ✅ |
| 4 | [Kuroko Tracker](#4-kuroko-tracker) | User Tracker | — | ✅ (DM) |
| 5 | [Kuroko Security](#5-kuroko-security-shield--anti-raid-protection) | Anti-Raid Protection | — | ✅ |
| 6 | [Kuroko Music ](#6-kuroko-music-) | Music Player | `k! / K! / l! / L! / Kuroko! / kuroko!` | ✅ |
| 7 | [Kuroko Invites ](#7-kuroko-invites-) | Invite Tracker | `!` | ✅ |
| 8 | [Kuroko Limit ✘](#8-kuroko-limit-) | VC Protection | `&` | ✅ (`/vc`) |
| 9 | [Kuroko Games ](#9-kuroko-games-) | Games & Fun | Configurable | ✅ |
| 10 | [Kuroko Pulse ❖](#10-kuroko-pulse--one-tap-voice-bot) | Temp Voice Rooms | `.v` | ✅ |

---

# 1️⃣ Kuroko ザウ Security — Moderation Bot

**A complete Discord management bot built to protect your server, organize staff work, manage members, and provide useful community tools.**

### 🛠️ Server Setup & Configuration
- Configure boy, girl and unverified roles
- Setup server tags and tag verification mode
- Configure jail role, booster role, jail logs and unjail logs
- Add or remove staff roles
- Setup roles allowed to verify, jail, move, pic, CTW and fullperm
- Set logs for warns, moves, fullperms, bans and moderation actions
- Change server prefix and view full server config

### 🛡️ Moderation Tools
| Command | Description |
|---------|-------------|
| `+v / +vf / +vb / +vg <user>` | Verify member (admins + verificator roles) |
| `+tag / +t <user>` | Apply boy/girl tag |
| `+warn <user> <reason>` | Warn member with reason |
| `+unwarn <user>` | Remove one warning |
| `+unwarnall <user>` | Remove all warnings |
| `+warnlist / +warnings <user>` | Show member warnings |
| `+warnlogs <user>` | Show warning logs |
| `+jail <user> <reason>` | Jail member (admins + jailpower roles) |
| `+unjail <user>` | Unjail member |
| `+jailogs / +jaillogs <user>` | Show jail logs (jailed by + reason + date) |
| `+ban <user> <reason>` | Ban member with setup ban mode |
| `+unban <user/id>` | Unban user |

### 🔎 Security & Anti-Raid Protection
| Command | Description |
|---------|-------------|
| `anti-bot on/off` | Enable/disable anti-bot protection |
| `set-logs-anti-bot <channel>` | Set anti-bot logs channel |
| `anti-link on/off` | Enable/disable anti-link protection |
| `set-logs-anti-link <channel>` | Set anti-link logs channel |
| `anti-token on/off` | Enable/disable anti-token protection |
| `set-logs-anti-token <channel>` | Set anti-token logs channel |
| `anti-webhook on/off` | Enable/disable anti-webhook protection |
| `set-logs-anti-webhook <channel>` | Set anti-webhook logs channel |
| `security` | Show all security settings |
| `wl add/remove/list` | Manage bot whitelist |
| `wl adduser/removeuser/listuser` | Manage user whitelist |
| `wl addrole/removerole/listrole` | Manage role whitelist |

### 👑 Role Commands
| Command | Description |
|---------|-------------|
| `+ctw <user>` | Give CTW role(s) |
| `+noctw <user>` | Remove CTW role(s) |
| `+move <user>` | Give move role(s) |
| `+nomove <user>` | Remove move role(s) |
| `+pic <user>` | Give pic role(s) |
| `+nopic <user>` | Remove pic role(s) |
| `+fullperm <user>` | Give fullperm role(s) |

### 📄 General Utilities
| Command | Description |
|---------|-------------|
| `+avatar / +a <user/id>` | Show user avatar |
| `+banner / +b <user/id>` | Show user banner |
| `+sb <user/id>` | Show server banner |
| `+gb <user/id>` | Show global banner |
| `+server / +serverinfo` | Show server information |
| `+stats` | Show server stats |
| `+device / +dev / +devices <user>` | Show device status (desktop/mobile/web) |
| `+afk [reason]` | Set AFK status |
| `+snipe / +sp / +snip` | Show deleted message |
| `+editsnipe / +esp` | Show edited message |
| `+join <vc>` | Make bot join voice channel |
| `+aji <user/id> <vc/id>` | Move user to voice channel |
| `+rvc / +randomvc / +pickvc` | Pick random VC member |
| `+thread <text>` | Post thread-style message |

### 🎉 Fun & Social Features
| Command | Description |
|---------|-------------|
| `+kiss / +hug / +slap / +kill / +cringe <user>` | Fun action commands |
| `+gay / +howgay <user>` | Gay percentage |
| `+love <user>` | Love percentage |
| `+marry <user>` | Propose marriage |
| `+divorce` | Divorce your partner |
| `+marrystats` | Show marriage stats |
| `+listmarry` | Show marriage list |
| `+follow <user>` | Follow a user |
| `+unfollow <user>` | Unfollow a user |
| `+following` | Show your following list |

**Prefix:** `+` • **Slash:** `/` • **Developed by Zaw (@zawgoat)**

---

# 2️⃣ Kuroko Check 🔎

**A powerful Discord checking bot made for staff checks, role scans, user information, dangerous permissions, voice checks, and voice activity leaderboards.**

### 👥 Staff & Role Checking
| Command | Description |
|---------|-------------|
| `/checkadmins <server_id>` or `+checkadmins <server_id> [blacklistIDs]` | Scans target server for owners, admins, staff members. Shows dangerous permissions, role information, shared staff, filtered bots. Mentions shared staff in your server. |
| `/checkid <server_id> <role_id>` or `+checkid <server_id> <role_id>` | Checks members inside a specific role. Shows role name, ID, server info, humans, shared members, unique members. Mentions shared members. |

### 🔍 User Investigation
| Command | Description |
|---------|-------------|
| `/cr <user>` or `+cr <@user\|ID>` | Full user check across mutual servers. Shows server name, ID, member count, nickname, join date, boost status, roles, staff/admin/owner status, dangerous permissions. Includes server selector and page navigation. |
| `/cs <user>` or `+cs <@user\|ID>` | Checks dangerous roles across servers. Detects: Administrator, Manage Guild, Manage Roles, Manage Channels, Ban Members, Kick Members, Manage Webhooks, Mention Everyone, and more. |

### 🎤 Voice & Activity
| Command | Description |
|---------|-------------|
| `/cv <user>` or `+cv <@user\|ID>` | Checks if user is in voice. Shows server, VC name, users inside, mute/deafen status, direct VC link. |
| `/mytop` or `+mytop` | Server live voice stats — total in voice, bots, humans, server rank |
| `/topma` or `/topmav2` or `+topma` / `+topmav2` | Top voice activity servers leaderboard with image, avatars, ranks, scores, navigation buttons |

**Prefix:** `+` • **Slash:** `/` • **Developed by Zaw (@zawgoat)**

---

# 3️⃣ Kuroko Logger ♯

**A complete Discord logging bot that tracks every event in your server. Per-event log channels, custom embed colors, slash + prefix commands.**

### ⚙️ Setup & Configuration
| Command | Description |
|---------|-------------|
| `/setlog <category> <event> <#channel>` or `kk?setlog` | Set a log channel for a specific event |
| `/setlogall <#channel>` or `kk?setlogall` | Send every log to one channel |
| `/removelog <category> <event>` or `kk?removelog` | Disable logging for an event |
| `/viewlogs` or `kk?viewlogs` | View current configuration |
| `/setembedcolor <color>` or `kk?setembedcolor` | Change embed color |
| `/help` or `kk?help` | Show full command list |

### 📋 Logged Events

**Member Logs**
- Member Join / Leave
- Member Ban / Unban
- Nickname changes
- Role updates on members
- Boost / Unboost tracking

**Message Logs**
- Message Delete (with old content)
- Message Edit (before/after)
- Message Pin tracking

**Channel Logs**
- Channel Create / Delete / Update

**Role Logs**
- Role Create / Delete / Update

**Emoji Logs**
- Emoji Create / Delete

**Voice Logs**
- Voice Join / Leave / Switch
- Voice Disconnect (by moderator)
- Voice Mute / Deaf changes
- Voice Stream activity

**Server Logs**
- Server Updates
- Server Boost Level changes

**Prefix:** `kk?` • **Slash:** `/` • **Developed by Zaw (@zawgoat)**

---

# 4️⃣ Kuroko Tracker

**A powerful tracking bot built to monitor Discord users in real time. Track messages, voice channel joins/leaves/switches, mute/unmute, deafen, streaming, and video status — all delivered straight to your DMs.**

### 📡 Main Features
- Real-time message tracking with attachments support
- Voice channel join/leave/switch detection
- Mute/unmute and deafen/undeafen tracking
- Streaming and video status detection
- Live VC member list with status indicators
- Server name and icon display in voice logs
- Direct DM delivery for full privacy
- Multi-self-bot fetcher for instant detection
- Smart duplicate prevention system

### 🎯 Slash Commands (DM Only)
| Command | Description |
|---------|-------------|
| `/track <id>` | Start tracking a Discord user by ID |
| `/remove <id>` | Stop tracking a user |
| `/show` | Show all users you are currently tracking |
| `/help` | Show commands list |

### 🔔 Notification Types
- Message notifications via clean embeds
- Voice events via Components V2 with VC info
- Mute/unmute notifications via plain text alerts
- Includes server name, channel, and full member list
- Status icons: 🎤 🔇 🧏 📺 📹
- Tracked target highlighted with ⭐

**Slash Only:** `/` (DM) • **Developed by Zaw (@zawgoat)**

---

# 5️⃣ Kuroko Security (Shield) — Anti-Raid Protection

**A powerful Discord protection bot built to keep your server safe from raids, dangerous permissions, abusive staff actions, unwanted bots, invite abuse, role damage, channel damage, and emoji abuse.**

### ⚠️ Protection System
- **Anti Ban** protection
- **Anti Kick** protection
- **Anti Bot Add** protection
- **Anti Role Create / Delete / Rename** protection
- **Anti Role Permission Update** protection
- **Anti Channel Create / Delete** protection
- **Anti Invite Link with roles** protection
- **Anti Emoji Delete / Rename** protection

### 🛠️ Slash Commands
| Command | Description |
|---------|-------------|
| `/help` | Show shield commands |
| `/status` | Show all protection status |
| `/actions` | Show all available shield actions |
| `/set` | Enable or disable any protection action |
| `/punish` | Set punishment type for an action (kick/ban/clear roles) |
| `/limit` | Set action limits |
| `/whitelist add` | Add user, role, or bot to whitelist |
| `/whitelist remove` | Remove whitelist access |
| `/whitelist list` | Show whitelist list |
| `/notif add/remove/list` | Manage DM notification users |

### 🔨 Punishment & Logs
- Punish dangerous actions with kick, ban, or clear roles
- Restore role names after unwanted rename actions
- Restore dangerous role permission changes
- Delete unauthorized created roles or channels
- Delete dangerous invite links with roles
- Send protection logs to the log channel
- Send DM alerts to the owner and notification users
- Bot owner is always protected and cannot be punished

**Slash Only:** `/` • **Developed by Zaw (@zawgoat)**

---

# 6️⃣ Kuroko Music 🎶

**Your all-in-one music bot. Play from Spotify, Apple Music, Deezer, SoundCloud and more!**

### Available Prefixes
`k!` `K!` `l!` `L!` `Kuroko!` `kuroko!`

### 🎵 Music Commands
| Command | Description |
|---------|-------------|
| `k!p / k!play` | Play a song from URL or search term |
| `k!s / k!skip` | Skip the current track |
| `k!stop` | Stop playback and clear queue |
| `k!pause` | Pause current track |
| `k!resume` | Resume playback |
| `k!volume` | Adjust volume |
| `k!q` | Show song queue |
| `k!forward` | Forward current song |
| `k!loop track` | Loop current track |
| `k!loop queue` | Loop entire queue |
| `k!loop off` | Disable loop |
| `k!shuffle` | Shuffle queue |

### ⚙️ Other Commands
| Command | Description |
|---------|-------------|
| `k!profile / k!pf` | Show your music profile |
| `k!ping` | Check bot latency |
| `k!help` | Show help menu |

**Prefixes:** `k! K! l! L! Kuroko! kuroko!` • **Slash:** `/` • **Developed by Zaw**

---

# 7️⃣ Kuroko Invites 📨

**Advanced Invite Tracking System — Track real / fake / left / bonus invites automatically.**

### 🏆 Features
| Command | Description |
|---------|-------------|
| `/invites` or `!invites` | Check your invite stats |
| `/leaderboard` or `!leaderboard` | Top inviters ranking |

### 📊 Invite Types
| Type | Icon | Description |
|------|:----:|-------------|
| Real Invites | ✅ | Valid joins |
| Left Invites | ❌ | Members who left |
| Fake Invites | 🚫 | New accounts detected |
| Bonus Invites | ⭐ | Staff added invites |

**Prefix:** `!` • **Slash:** `/` • **Developed by Zaw (@zawgoat)**

---

# 8️⃣ Kuroko Limit ✘

**An advanced Discord VC protection bot made for private voice channels, limited VCs, anti-abuse systems, bypass controls, and owner-only management.**

### 🔒 Voice Protection Features
| Command | Description |
|---------|-------------|
| `&vc protect-vc-add` | Protect a specific voice channel from unauthorized joins |
| `&vc protect-category-add` | Enable protection for all VCs inside a category |
| `&vc limit-category-add` | Enable VC limit protection (prevents bypassing full VCs) |
| `&vc bypass-user-add` | Allow trusted users to bypass VC protections |
| `&vc bypass-role-add` | Allow trusted roles to bypass protected VC systems |
| `&vc owner-set` | Set the official bot owner for the server |
| `&vc list` | Display all protected categories, VCs, bypass users, and roles |

**Prefix:** `&` • **Slash:** `/vc` • **Developed by Zaw (@zawgoat)**

---

# 9️⃣ Kuroko Games 🎮

**A complete Discord games bot made to bring activity, competition, points, rewards, and fun systems to your server.**

### 🎮 Available Games
- **XO / XO2** — Tic Tac Toe
- **Rock Paper Scissors** — Classic RPS
- **Roulette** — Casino-style roulette
- **Chairs** — Musical chairs game
- **Hide and Seek** — Hide and seek
- **Mafia** — Mafia party game
- **Snake** — Snake game
- **Dice** — Dice rolling
- **Flags** — Flag guessing
- **Fast, Bomb, Blocks, Guess, Emoji, Colors, Ranking** and more

### 🏆 Points & Rewards
- Earn points from winning games
- Check balance with points command
- Shop system for in-game items
- Buy items inside active games
- Transfer points between users via slash commands

### 🛠️ Server Configuration
- Admins can set a dedicated games channel
- Games only work inside the configured channel
- Only one active game at a time in the channel
- Admin stop command to halt active games
- Supports both English and Arabic commands

**Prefix + Slash:** Available • **Components v2** UI • **Developed by Zaw (@zawgoat)**

---

# 🔟 Kuroko Pulse ❖ — One Tap Voice Bot

**A premium Discord voice control bot built for temporary voice rooms, easy room management, event control, managers, whitelist, blacklist, and anti-abuse protection.**

### 🔐 Voice Room Controls (`.v`)
| Command | Description |
|---------|-------------|
| `.v lock` | Lock your private voice room so nobody can join |
| `.v unlock` | Unlock your room and make it open again |
| `.v permit <user>` | Allow a member to join your private voice |
| `.v deny <user>` | Block a member from joining your room |
| `.v kick <user>` | Kick someone from your voice channel |
| `.v limit <number>` | Set a user limit for your room |
| `.v rename <name>` | Rename your voice channel anytime |
| `.v claim` | Claim ownership when the room owner leaves |
| `.v transfer <user>` | Transfer room ownership to another member |
| `.v owner` | Check the current voice room owner |
| `.v status <text>` | Set a custom voice status |

### 👑 Setup & Managers
- Setup: Configure the temporary voice room category
- Event Manager Role: Set the event manager role
- Event Category: Set the event category
- Event Logs Channel: Set the event logs channel
- Managers: Add, remove, or clear bot managers

### 📋 Whitelist System
- Add trusted users to whitelist
- Remove users from whitelist
- View the full whitelist

### 🚫 Blacklist System
- Add users to blacklist
- Remove users from blacklist
- View the full blacklist

### ⚠️ Owner & Anti-Abuse Tools
- Enable or disable anti-abuse protection
- Add or remove anti-abuse bypass users
- Show the bypass users list
- Set server voice status for all One Tap voice channels

### 🔊 Extra Voice Features
| Toggle | Description |
|--------|-------------|
| Soundboard | Turn soundboard permissions ON/OFF |
| Camera | Turn camera permissions ON/OFF |
| Activities | Turn activities permissions ON/OFF |

**Prefix:** `.v` • **Slash:** `/` • **Developed by Zaw (@zawgoat)**

---

## 🔗 Verification Form — Single Submission for All Bots

> ✅ **All bots share the same verification submission since they are part of the same ecosystem developed by Zaw.**

### 🎯 Intents Required Per Bot

| Bot Name | Members Intent | Presence Intent | Message Content Intent |
|----------|:------------:|:--------------:|:--------------------:|
| Kuroko Security (Mod) | ✅ | ✅ | ✅ |
| Kuroko Check 🔎 | ✅ | ✅ | ✅ |
| Kuroko Logger ♯ | ✅ | ✅ | ✅ |
| Kuroko Tracker | ✅ | ✅ | ❌ |
| Kuroko Security (Shield) | ✅ | ❌ | ❌ |
| Kuroko Music 🎶 | ✅ | ✅ | ✅ |
| Kuroko Invites 📨 | ✅ | ❌ | ✅ |
| Kuroko Limit ✘ | ✅ | ✅ | ✅ |
| Kuroko Games 🎮 | ✅ | ❌ | ✅ |
| Kuroko Pulse ❖ | ✅ | ✅ | ✅ |

---

### 📋 Verification Form Responses — Complete (Single Submission)

#### Application Details

**What does your application do?**

> This application covers a **suite of 10 Discord bots** developed under the Kuroko ecosystem by Zaw:
>
> **1. Kuroko Security (Moderation Bot):** Server moderation, verification (boy/girl), warn/jail/ban systems, role management (CTW/move/pic/fullperm), anti-raid protection (anti-bot, anti-link, anti-token, anti-webhook), snipe/editsnipe, AFK system, device status, voice tools, fun actions, marriage/follow systems.
>
> **2. Kuroko Check 🔎:** Staff and role scanner that checks target servers for admins, owners, dangerous permissions, shared staff. User investigation across mutual servers. Voice activity checks and leaderboards.
>
> **3. Kuroko Logger ♯:** Full server event logging (member join/leave/ban/unban/nickname/role, message delete/edit/pin, channel/role/emoji create/delete/update, voice join/leave/switch/mute/deafen/stream, server updates). Per-event channels and custom embed colors.
>
> **4. Kuroko Tracker:** Real-time DM-based user tracking. Monitors messages, voice activity (join/leave/switch), mute/deafen/stream/video status. Delivers all notifications privately via DMs.
>
> **5. Kuroko Security (Shield):** Anti-raid protection bot. Blocks unauthorized bans, kicks, bot additions, role/channel/emoji abuse, invite abuse. Whitelist system with punishments (kick/ban/clear roles) and DM notifications.
>
> **6. Kuroko Music 🎶:** Multi-platform music playback from Spotify, Apple Music, Deezer, SoundCloud, YouTube. Queue management, loop/shuffle/volume, user music profiles.
>
> **7. Kuroko Invites 📨:** Invite tracking with real/fake/left/bonus invites detection and leaderboard ranking.
>
> **8. Kuroko Limit ✘:** Voice channel protection. Private VC access control, limit enforcement, bypass user/role whitelist, owner management.
>
> **9. Kuroko Games 🎮:** Interactive games collection (XO, RPS, Roulette, Chairs, Hide&Seek, Mafia, Snake, Dice, Flags, and more) with points, shop, and rewards system.
>
> **10. Kuroko Pulse ❖:** Temporary voice room management. Automatic room creation, lock/unlock/permit/deny/kick/claim/transfer, whitelist/blacklist, anti-abuse, soundboard/camera/activities permissions.

**Do you have a public Privacy Policy?**
> **Yes** — https://mrjoker444.github.io/kuroko-privacy-policy/

---

#### Server Members Intent — Why Required

> The **Guild Members** intent is required across multiple bots:
>
> **Kuroko Security (Mod):** Verification role assignment, tag system, warn/jail/ban member resolution, CTW/move/pic/fullperm role management, marriage/follow member data, AFK detection, snipe author resolution, whitelist member verification.
>
> **Kuroko Check:** Fetching full member lists for server scanning (`+checkadmins`), shared member detection across servers, join dates and roles for user investigation (`+cr`, `+cs`).
>
> **Kuroko Logger:** Resolving member usernames and display information for member join/leave/ban/unban/nickname/role update logs.
>
> **Kuroko Tracker:** Resolving tracked user IDs to display names and server member info for DM notifications.
>
> **Kuroko Music:** User music profiles, "requested by" display in queue, per-user volume/settings, DJ role verification.
>
> **Kuroko Invites:** Tracking inviter-invitee relationships, leaderboard display with usernames and avatars.
>
> **Kuroko Limit:** Resolving bypass users and roles, owner verification, member display in VC list.
>
> **Kuroko Games:** Points tracking per user, leaderboards with member names, shop inventory, game history.
>
> **Kuroko Pulse:** Room ownership tracking, whitelist/blacklist member resolution, manager role verification, anti-abuse member tracking.

**Are you storing any API data off-platform?**
> **No.** All member data is processed in-memory or temporarily cached for rate-limit optimization. Configuration data (server settings, whitelists, warnings) is stored per-server in a database but no raw Discord API data is stored off-platform.

---

#### Presence Intent — Why Required

> The **Presence** intent is required across multiple bots:
>
> **Kuroko Security (Mod):** Device status display (`+device`), real-time online/offline counts in server stats, voice tools (join/move/pick random VC member).
>
> **Kuroko Check:** Voice channel presence detection for `+cv`, live voice stats for `+mytop` and `+topma`, real-time VC occupancy.
>
> **Kuroko Logger:** Voice join/leave/switch/disconnect/mute/deafen/stream logging requires real-time voice state updates.
>
> **Kuroko Music:** Detecting which voice channel a user is in to join and play music, auto-disconnect on empty channel, resume playback on move.
>
> **Kuroko Limit:** Real-time VC protection enforcement, detecting unauthorized join attempts, limit protection (preventing bypass of full VCs), monitoring protected channels.
>
> **Kuroko Pulse:** Creating temporary voice rooms when a user joins the trigger channel, detecting room owner leave for claiming, real-time permission sync, room occupancy tracking.

**Can users opt-out?**
> **Yes.** Users can opt out by not using features that require presence, or by using slash commands exclusively. Presence data is only processed for users actively using voice features.

**Are you storing user activity data off-platform?**
> **No.** Presence data is processed in real-time only and never stored off-platform.

---

#### Message Content Intent — Why Required

> The **Message Content** intent is required to support **prefix-based commands**:
>
> **Kuroko Security (`+`):** Emergency moderation (`+jail`, `+ban`, `+warn`), fast verification (`+v`), role management (`+ctw`, `+move`, `+pic`), snipe/editsnipe, AFK detection.
>
> **Kuroko Check (`+`):** Server scanning (`+checkadmins`, `+checkid`), user investigation (`+cr`, `+cs`), voice checks (`+cv`), voice leaderboards.
>
> **Kuroko Logger (`kk?`):** Prefix-based log configuration (`kk?setlog`, `kk?setlogall`, `kk?viewlogs`).
>
> **Kuroko Music (`k!/K!/l!/L!/Kuroko!/kuroko!`):** Music playback commands, queue management, profile access.
>
> **Kuroko Invites (`!`):** Checking invite stats and leaderboards.
>
> **Kuroko Limit (`&`):** VC protection configuration (`&vc protect-vc-add`, `&vc bypass-user-add`, `&vc list`).
>
> **Kuroko Games (configurable prefix):** Starting games, in-game interactions, points/shop commands.
>
> **Kuroko Pulse (`.v`):** Room management commands (`.v lock`, `.v permit`, `.v claim`, `.v transfer`).
>
> All bots only read messages starting with their specific prefix. All other message content is ignored. No message content is stored, logged, or processed beyond immediate command parsing.

**Can users opt-out?**
> **Yes.** Users can avoid all message content tracking by using only slash commands instead of prefix commands.

**Are you storing message content data off-platform?**
> **No.** Message content is parsed in memory only and discarded immediately after command execution. No logs, databases, or external storage.

**Will the data be used for ML/AI training?**
> **No.**

---

## 📦 Technical Details

- **Library:** discord.js v14+
- **UI System:** Components v2 (ContainerBuilder, MediaGalleryBuilder, StringSelectMenuBuilder, etc.)
- **Command System:** Hybrid — both prefix and slash commands on all applicable bots
- **Configuration:** Per-guild persistent storage via database
- **Design Philosophy:** Privacy-first — minimal data collection, no off-platform storage of user content

## 👨‍💻 Developer

**Zaw (@zawgoat)**

## 📄 Links

- **Privacy Policy:** https://mrjoker444.github.io/kuroko-privacy-policy/
- **Support Server:** https://discord.gg/j7NZeQf8Uz

## ©️ License

Proprietary — All rights reserved © Zaw
