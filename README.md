# AIU inbox → Suno playlist

**Open the inbox. Open a playlist. Let Antigravity add the songs.**

## Three steps

1. Sign in to [AIU Uploader](https://uploader.aiu.fm/) and [Suno](https://suno.com/) in the browser Antigravity can actually control.
2. Open your **AP → Pending** inbox. Have a Suno playlist you own ready, or let the agent create one if it can.
3. Paste this into Antigravity:

```text
Read and follow https://raw.githubusercontent.com/inaratalamasca/aiu-inbox-playlist-guide/main/GUIDE.md

Help me run an AP. Ask for my inbox and playlist links if needed.
Verify one real submission first, then keep the playlist updated about every five minutes while this session is active.
Leave Discord announcements OFF.
```

For a listening party, say **LP** instead. **“Check now”** does another pass. **“Stop”** ends the watch.

If it cannot control the browser, use `/browser` and follow [Google's browser setup](https://antigravity.google/docs/commands/browser/). Signing into your usual browser does not necessarily sign into Antigravity's browser.

## Advanced — optional now-playing pings

After playlist updates work, say:

```text
Enable the Advanced now-playing helper in the guide. Ask for the playing Suno tab and the Discord channel.
```

Use **Discord web**, visible to Antigravity, for the browser-assisted route. Desktop Discord on Windows is not assumed supported. Automatic sending uses an approved bot/webhook; otherwise the helper prepares messages for you to review and send. [Advanced instructions](GUIDE.md#advanced--optional-now-playing-pings)

## Can Antigravity do this?

Google documents [browser control](https://antigravity.google/docs/commands/browser/), [MCP tools](https://antigravity.google/docs/mcp?tab=ide), and [in-chat timers](https://antigravity.google/docs/commands/schedule/). Those supply the necessary building blocks. **Pondy's installation has not been tested:** the guide checks access and verifies one addition before continuing.

Suno MCP is preferred when available; browser playlist controls are the fallback. The [official Suno MCP address](https://suno.com/mcp) is `https://api.suno.com/mcp`. Authorize your own account; having some MCP tools installed does not prove Suno is connected.

Checked **November 15, 2026**. This is a small instruction guide, not a player, extension or bot installation.
