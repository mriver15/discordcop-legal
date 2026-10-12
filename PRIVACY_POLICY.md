# Privacy Policy — DiscordCop

**Last updated:** 2026-10-12

This policy explains what data the DiscordCop bot ("the Bot") collects, why it is collected, and how it is handled. The Bot is operated by the owner of the Discord server ("the Operator").

## Data we collect and process

The Bot processes only the minimum data required to function:

1. **Discord identifiers.** User IDs, server (guild) IDs, channel IDs, and permission/role state — needed to run slash commands and to enforce moderation permissions.
2. **Warning records.** When a moderator runs `/warn`, the Bot stores the warned user's ID, the moderator's ID and username, the reason, and a timestamp in a local file (`data/state.json`) on the host machine. This is the history shown by `/warnings`.
3. **Issue and bug reports.** Text you submit via `/issue create` or `/bug` (title, description, reproduction steps, severity, and your Discord username in the bug body) is sent to the configured GitHub repository and stored there as a GitHub issue.
4. **Poll cursors.** The IDs of the last-seen GitHub issue and release, stored locally so the Bot does not re-announce old items.

## What we do NOT collect

- The Bot does **not** read or store message content. It uses no Message Content intent and does not log channel messages.
- No analytics, tracking, advertising, or profiling.
- No data is sold or shared with third parties.

## Third parties

- **Discord** — interactions are processed by Discord; see [Discord's Privacy Policy](https://discord.com/privacy).
- **GitHub** — issue/bug reports are stored on GitHub; see [GitHub's Privacy Statement](https://docs.github.com/en/site-policy/privacy-policies/github-privacy-statement) and the repository owner's settings.

## Retention and deletion

- Warning records and poll cursors are stored locally for as long as the Bot is operated.
- You may request deletion of your warnings or other data by contacting a server moderator or the Operator. Warning records can also be removed by the Operator from `data/state.json`.
- Issue/bug reports follow GitHub's data policies and can be deleted from the repository like any other issue.

## Changes

This policy may be updated. Continued use of the Bot after a change constitutes acceptance of the updated policy.

## Contact

Questions or data requests: **@river8** (Discord) or rivera.devs@gmail.com.
