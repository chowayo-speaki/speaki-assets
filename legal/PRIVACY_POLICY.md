# Speaki Privacy Policy

**Effective date:** 28 November 2026

This policy explains what information **Speaki** collects, why, and what you can
do about it. Speaki is a fan-made community bot for Jena's Twitch channel. It
consists of:

- the **Speaki Discord app** (the `/speaki` commands and the status board), and
- the **Speaki Twitch chat bot** (`@chowayo_speaki_bot`), whose statistics the
  Discord app displays.

Speaki is run by an individual community member (the "operator", "we", "us").
It is not affiliated with or endorsed by Discord, Twitch, 7TV or any other
service mentioned here.

## 1. Information from Discord

**What Speaki can see.** Speaki only receives what Discord sends to an app when
someone uses one of its commands. It does **not** read messages posted in
channels, and it does not receive member lists or online/activity status.

**When you use a `/speaki` command**, Discord gives Speaki your Discord user ID,
your display name, the server and channel the command was used in, and the
options you typed. Speaki uses this only to answer you. It is not stored,
with these exceptions:

| What | Stored information | Why |
|---|---|---|
| `/speaki idea` | Your idea text, your Discord user ID and display name, the date and time, and the current stream if Jena is live | To collect and review community ideas |
| Command cooldowns | Your Discord user ID, in memory only, for the cooldown period (seconds to a minute) | To prevent command spam; erased when the cooldown ends or Speaki restarts |

**Status board.** Speaki posts and keeps updating one message in its dashboard
channel. It contains stream information only.

**Technical logs.** Speaki keeps service logs for troubleshooting (for example,
connection events, the server and channel IDs it is configured for, and
errors). They are not used to record who used which command or what they typed.

## 2. Information from Twitch shown on Discord

Speaki's Twitch chat bot processes **public chat in Jena's Twitch channel**.
Several Discord commands display statistics built from it:

- **Chat history:** Twitch username, message text and time for chat messages
  in the channel, stored in Speaki's database and daily chat log files.
- **Per-user statistics:** message counts, the number of links shared, most-used
  emotes, and first/last seen dates. Anyone using `/speaki userstats` can look
  these up for a Twitch username, and weekly recaps list the most active
  chatters and link sharers.
- **Ideas from Twitch** (`!idea`): idea text, Twitch username, Twitch user ID and
  time.
- **Emote and command usage:** counts of emotes and Speaki features used.

**Stream audio.** To identify songs, Speaki sends short clips of the
**stream's audio** to Shazam. To detect spoken keywords (such as game names),
the stream's audio is transcribed **locally on Speaki's server**. Temporary
audio files are deleted automatically. This concerns the broadcast itself, not
viewers.

## 3. Services Speaki uses

Speaki does not sell, rent or trade any information, shows no ads, and uses no
advertising or analytics trackers. To work, it exchanges data with:

| Service | Purpose | Data involved |
|---|---|---|
| Discord | Commands, replies, status board, emojis | Command interactions as described above |
| Twitch | Chat, stream status | Public chat and stream information |
| Shazam | Song recognition | Short clips of stream audio |
| MusicBrainz, YouTube | Song details and links | Song titles, artists and identifiers (no personal data) |
| 7TV and Twitch's emote image service | Emote images used as Discord emojis | Public emote images (no personal data) |

Each service handles data under its own privacy policy.

## 4. Storage and security

Speaki runs on a privately operated server. Its database is not publicly
accessible and its management dashboard is only reachable on that server.
Compressed backups of the database are kept on the same server.

## 5. How long information is kept

- **Ideas, Twitch chat history and statistics** are kept until the operator
  deletes them. There is currently no automatic expiry, because the history
  powers long-term statistics.
- **Automatic database backups** are made monthly, and the newest three are kept.
  Backups made before maintenance are kept until the operator removes them.
- **Cooldown data** exists only in memory and is lost when Speaki restarts.

## 6. Your choices

- You can simply **not use** Speaki's commands; Speaki then receives nothing
  about you from Discord.
- You can ask us to **delete** your ideas or your Twitch chat statistics, or
  to tell you what Speaki has stored about you. Contact us (see below) from the
  Discord or Twitch account concerned so we can confirm the request is yours.
  Deleted data disappears from backups as they rotate out.

## 7. Age

You must meet the minimum age required by Discord and Twitch in your country to
use Speaki.

## 8. Changes

We may update this policy when Speaki changes. The effective date above shows
the latest version.

## 9. Contact

Questions or requests: nightelada on Discord
