# Harmony RPC

Universal music Rich Presence for Discord on Windows.

Shows whatever you are listening to on your Discord profile — Spotify, YouTube
Music, Apple Music, TIDAL, Deezer, foobar2000, MusicBee, browsers, and anything
else that registers with Windows media controls.

## Download

Grab the latest `HarmonyRPC-windows-vX.Y.Z.zip` from
[Releases](https://github.com/evanbackup1256-ship-it/harmony-rpc/releases/latest),
extract the **whole folder**, and run `ytm_rich_presence.exe`.

Keep every file together — the app loads its media bridge from the folder
beside the executable.

## First run

The app opens a four-step wizard that walks you through creating a Discord
application and pasting its ID. It takes about a minute.

In the Discord Developer Portal, under **Rich Presence → Art Assets**, upload an
image named exactly `logo`. Optionally add `play` and `pause` for the small
badge. Without these Discord shows no artwork.

## What it does

- **Any player.** Reads the Windows media session, so it works with players
  nobody has written an integration for.
- **Smart filtering.** Prefers a real music app over a browser, and skips
  videos, trailers and adverts.
- **Custom wording.** Token templates like `{title}[[ - {album}]]` let you write
  exactly how your status reads.
- **Listening stats.** Top tracks, artists and apps, daily and hourly charts.
  Everything stays on your computer.
- **Themes.** Seven built-in, plus a builder for your own.
- **OBS overlay.** Writes a browser-source page for streaming.
- **Media controls.** Play, pause and skip from the app.
- **Updates itself.** New versions install without re-running anything.

## Privacy

Track information is read locally from Windows and sent only to your own
Discord client. There is no account, no server, and no telemetry. Listening
history is a plain file on your machine that you can export or delete.

## Requirements

Windows 10 or 11, and the Discord desktop app running.

## Credits

Built by `dshj21e72eb` on Discord.

Not affiliated with Discord, Google, Spotify, or any music service.
