# 📚 Kuroko Bots —

> All Discord bots developed by **Zaw (@zawgoat)**
>
> [![Privacy Policy](https://img.shields.io/badge/Privacy%20Policy-Read%20Policy-blue)](https://mrjoker444.github.io/kuroko-privacy-policy/)
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

## 🔗 Privacy, Verification & Developer Information

**Developer:** Zaw (@zawgoat)  
**Support:** https://discord.gg/j7NZeQf8Uz  
**Privacy Policy:** https://mrjoker444.github.io/kuroko-privacy-policy/ *(publish the updated policy at this URL before submitting)*

### Privileged Intent Review

Each Discord application must apply separately for any privileged intents it actually needs. The ten bots listed above are separate products and this catalogue is **not** a single verification submission covering all ten applications.

For **Kuroko ザウ (Security & Moderation)**, the documented use cases are:

| Intent | Specific feature | Evidence to provide |
|---|---|---|
| Guild Members | Member join verification, automatic unverified role assignment, anti-bot checks, member role management | Video showing a member join, role assignment, and a moderation workflow |
| Guild Presences | `+device` displays available online status and desktop/mobile/web client status | Video showing `+device` on a test member with presence enabled |
| Message Content | Configurable `+` prefix commands; anti-link and anti-token message inspection; AFK and snipe/editsnipe | Video showing a prefix command and a test anti-link event |

**Guild Members justification:** Kuroko processes guild member join events for verification and anti-bot protections and accesses member roles to apply configured verification, jail, and staff permissions. These member event workflows cannot be replaced by command interactions alone.

**Guild Presences justification:** The `+device` utility reads the member's available Discord presence and client status to display desktop, mobile, web and availability information. It is not requested for voice channel joins or voice state events, which use a separate gateway intent.

**Message Content justification:** Kuroko uses a configurable text prefix for its existing moderation and utility commands and analyzes ordinary messages to enforce server-configured anti-link and anti-token protections. Slash commands alone cannot provide automatic inspection of messages sent without invoking a bot command.

**Data handling:** Kuroko uses persistent local storage for some guild configurations and moderation records, including Discord identifiers. Snipe/editsnipe features may temporarily retain deleted or edited message content in application memory, and enabled moderation logs may be sent to Discord channels. See the Privacy Policy for details. Do not claim that no Discord API data is stored outside Discord.

**Important:** Other Kuroko bots have not been source-code audited for this document. Their intent requirements, data retention, consent/opt-out, and storage practices must be verified independently before applying. In particular, presence access is not automatically required for voice features.

### Evidence and review checklist

- Record real demonstrations in a test Discord server, with consenting test accounts and no real credentials or tokens.
- Upload videos to an accessible URL (for example an unlisted YouTube video) and link them in the relevant form fields.
- Confirm actual database retention periods, backups, encryption at rest, and deletion procedures with the hosting provider.
- Publish a truthful Privacy Policy and ensure that its contact method works.
- Answer all yes/no form questions according to actual deployment behavior, not the answer most likely to pass review.

---

## 👨‍💻 Developer

**Zaw (@zawgoat)**  
Support server: https://discord.gg/j7NZeQf8Uz

## ©️ License

Proprietary — All rights reserved © Zaw
