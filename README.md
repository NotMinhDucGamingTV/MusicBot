<img align="right" src="https://i.imgur.com/zrE80HY.png" height="200" width="200">

# MusicBot

A cross-platform Discord music bot with a clean interface, and that is easy to set up and run yourself!

## Features
  * Easy to run (just make sure Java is installed, and run!)
  * Fast loading of songs
  * No external keys needed (besides a Discord Bot token)
  * Smooth playback
  * Server-specific setup for the "DJ" role that can moderate the music
  * Clean and beautiful menus
  * Supports many sites, including Youtube, Soundcloud, and more
  * Supports many online radio/streams
  * Supports local files
  * Playlist support (both web/youtube, and local)

## Supported sources and formats
JMusicBot supports all sources and formats supported by [lavaplayer](https://github.com/sedmelluq/lavaplayer#supported-formats):
### Sources
  * YouTube
  * SoundCloud
  * Bandcamp
  * Vimeo
  * Twitch streams
  * Local files
  * HTTP URLs
### Formats
  * MP3
  * FLAC
  * WAV
  * Matroska/WebM (AAC, Opus or Vorbis codecs)
  * MP4/M4A (AAC codec)
  * OGG streams (Opus, Vorbis and FLAC codecs)
  * AAC streams
  * Stream playlists (M3U and PLS)

## Example
![Loading Example...](https://i.imgur.com/kVtTKvS.gif)

## Setup
1️⃣ Install Java#

    Instructions on how to install Java on your system: Installing Java

2️⃣ Download JMusicBot#

    Download the latest JMusicBot-X.Y.Z.jar (and optionally, example config.txt file) from the releases page (or, get the URL from the releases page and then use wget or similar command-line tool to download).
    Your folder should look similar to this (on desktop):
    View

Warning

Do not put this in the Downloads or Desktop. Use a folder within Documents
3️⃣ Edit the config file#

    Fill in the config file (if you downloaded it). If you didn't download it, you will be prompted when you run for the first time. An example config.txt is provided below (See Getting a Bot Token and Finding Your User ID if you need help with the config).

    token = MJHJkljflksdjfCoolTokenDudeILikeItkasdk
    owner = 113156185389092864
    prefix = "!"

You can also copy & paste a template from the Example Config
4️⃣ Run JMusicBot#

    Run the jar file (choose one of these options):
    Double-click the jar file (on desktop environments), OR
    Run java -Dnogui=true -jar JMusicBot-X.Y.Z.jar from the command line (replace X, Y, and Z with the release numbers), OR
    Run nohup java -Dnogui=true -jar JMusicBot-X.Y.Z.jar & to run in the background (Linux only)
    Provide the requested information, if prompted.
    Wait for the "Finished Loading" message.

5️⃣ Add your bot to your server#

    When the bot starts, if it hasn't been added to any servers yet, it will provide you with a link in the console.
    Alternatively, follow these instructions (with images): Adding Your Bot To Your Server


## Questions/Suggestions/Bug Reports
**Please read the [Issues List](https://github.com/1stminhcar/MusicBot/issues) before suggesting a feature**. If you have a question, need troubleshooting help, or want to brainstorm a new feature, please start a [Discussion](https://github.com/1stminhcar/MusicBot/discussions). If you'd like to suggest a feature or report a reproducible bug, please open an [Issue](https://github.com/1stminhcar/MusicBot/issues) on this repository. If you like this bot, be sure to add a star to the libraries that make this possible: [**JDA**](https://github.com/DV8FromTheWorld/JDA) and [**lavaplayer**](https://github.com/sedmelluq/lavaplayer)!

## Editing
This bot (and the source code here) might not be easy to edit for inexperienced programmers. The main purpose of having the source public is to show the capabilities of the libraries, to allow others to understand how the bot works, and to allow those knowledgeable about java, JDA, and Discord bot development to contribute. There are many requirements and dependencies required to edit and compile it, and there will not be support provided for people looking to make changes on their own. Instead, consider making a feature request (see the above section). If you choose to make edits, please do so in accordance with the Apache 2.0 License.
