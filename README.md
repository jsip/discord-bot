# Discord Music bot

### Starting the application using Docker

```bash
# Build the image
docker build --tag discordbot .

# Run the image
docker run -d discordbot
```

## Features & Commands

> Note: The repository now uses the new Discord slash commands

* 🎶 Play music from YouTube via url

`/play YOUTUBE_URL`

* 🎶 Play music from using song name

`/play SONG_NAME`

* 📃 Pause music

`/pause`

* 🎓 Resume music

`/resume`

* 💿 Skip song

`/skip`

* 🔇 Stop music

`/stop`

* 🔀 Shuffle Queue

`/shuffle`

* ↕ Move song position

`/move TRACK_POSITION TARGET_POSITION`

* ↔️ Swap song positions

`/swap POSITION_1 POSITION_2`

* ⏏️ Remove song

`/remove POSITION`

* Now Playing (/nowplaying)
* Get information about a user (/userinfo USER)
* Ban a player (/ban USER)
* Delete the latest chat messages (/purge NUM_OF_MESSAGES)

### Dependencies aren't up to date

```bash
npm install ytdl-core@latest
```# discord-bot
