# ๐๐๐๐๐'๐ ๐๐ ๐๐๐๐๐

# [![โๅฝก[๐๐๐๐๐ ๐๐ ๐๐๐๐๐]ๅฝกโ](https://te.legra.ph/file/636be2f6321a519bf56de.jpg)](https://github.com/Agora-OS/VC-Robot)

## This Is Telegram Music UserBot To Play Music Without Being Admin

## A FASTEST AND SMOOTHEST BASED ON TG CALLS AND PYROGRAM STRING.

# ๐ <a name="deploy"></a>Deploy

[![Deploy on Heroku](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/Agora-OS/VC-Robot)

# [![โๅฝก[๐๐๐๐๐ ๐๐ ๐๐๐๐๐]ๅฝกโ](https://te.legra.ph/file/1ac5a708ad44281c70ce2.jpg)](https://github.com/Agora-OS/VC-Robot)

## [REPL](https://t.me/LEGEND_STRINGSESSIONBOT)
## โ๏ธ <a name="self_host"></a>Self Host

```bash
$ git clone https://github.com/Agora-OS/VC-Robot
$ cd MusicPlayer
$ cp sample.env .env
< edit .env with your own values >
$ sudo docker build . -t musicplayer
$ sudo docker run musicplayer
```

## โ <a name="configs"></a>Configs

- `API_ID`: Telegram app id.
- `API_HASH`: Telegram app hash.
- `SESSION`: Pyrogram string session. You can generate from [here](https://replit.com/@AsmSafone/genStr).
- `SUDOERS`: ID of sudo users (separate multiple ids with space).
- `PREFIX`: Commad prefixes (separate multiple prefix with space). Eg: `! /`
- `LANGUAGE`: An [available](#languages) bot language (can change it anytime). Default: `en`
- `CUSTOM_QUALITY`: Custom stream quality for the userbot in vc. Default: `high`

## ๐ <a name="commands"></a>Commands

Command | Description
:--- | :---
โข !ping | Check if alive or not
โข !start / !help | Show the help for commands
โข !mode / !switch | Switch the stream mode (audio/video)
โข !p / !play [song name or youtube link] | Play a song in vc, if already playing add to queue
โข !radio / !stream [radio url or stream link] | Play a live stream in vc, if already playing add to queue
โข !pl / !playlist [youtube playlist link] | Play the whole youtube playlist at once
โข !skip / !next | Skip to the next song
โข !m / !mute | Mute the current stream
โข !um / !unmute | Unmute the muted stream
โข !ps / !pause | Pause the current stream
โข !rs / !resume | Resume the paused stream
โข !list / !queue | Show the songs in the queue
โข !mix / !shuffle | Shuflle the queued playlist
โข !loop / !repeat | Enable or disable the loop mode
โข !lang / language [language code] | Set the bot language in group
โข !ip / !import | Import queue from exported file
โข !ep / !export | Export the queue for import in future
โข !stop / !leave | Leave from vc and clear the queue

## ๐ฃ <a name="languages"></a>Languages

```text
en    English
```

## ๐ <a name="license"></a>License

Music Player is licenced under the GNU Affero General Public License v3.0.
Read more [here](./LICENSE).
