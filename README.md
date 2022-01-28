<p align="center">
  <img src="https://telegra.ph/file/bfd3abe0c39435da3e16a.jpg" alt="Eva Maria Logo">
</p>


<h1 align="center" > LaZER-DL </h1>



# Benefits :-
    ✓ Google Drive link cloning using gclone.(wip)
    ✓ Telegram File mirrorring to cloud along with its unzipping, unrar and untar
    ✓ Drive/Teamdrive support/All other cloud services rclone.org supports
    ✓ Unzip
    ✓ Unrar
    ✓ Untar
    ✓ Custom file name
    ✓ Custom commands
    ✓ Get total size of your working cloud directory
    ✓ You can also upload files downloaded from /ytdl command to gdrive using `/ytdl gdrive` command.
    ✓ You can also deploy this on your VPS
    ✓ Option to select either video will be uploaded as document or streamable
    ✓ Added /renewme command to clear the downloads which are not deleted automatically.
    ✓ Added support for youtube playlist 😐
    ✓ Renaming of Telegram files support added. 😐
    ✓ Changing rclone destination config on fly (By using `/rlcone` in private mode)
   
##### Mandatory Variables

* `TG_BOT_TOKEN`: Create a bot using [@BotFather](https://telegram.dog/BotFather), and get the Telegram API token.

* `APP_ID`
* `API_HASH`: Get these two values from [my.telegram.org/apps](https://my.telegram.org/apps).
  * N.B.: if Telegram is blocked by your ISP, try our [Telegram bot](https://telegram.dog/UseTGXBot) to get the IDs.

* `AUTH_CHANNEL`: Create a Super Group in Telegram, add `@GoogleIMGBot` to the group, and send /id in the chat, to get this value.

* `OWNER_ID`: ID of the bot owner, He/she can be abled to access bot in bot only mode too(private mode).

##### Optional Configuration Variables

* `DOWNLOAD_LOCATION`

* `MAX_FILE_SIZE`

* `TG_MAX_FILE_SIZE`

* `FREE_USER_MAX_FILE_SIZE`

* `MAX_TG_SPLIT_FILE_SIZE`

* `CHUNK_SIZE`

* `MAX_MESSAGE_LENGTH`

* `PROCESS_MAX_TIMEOUT`

* `ARIA_TWO_STARTED_PORT`

* `EDIT_SLEEP_TIME_OUT`

* `MAX_TIME_TO_WAIT_FOR_TORRENTS_TO_START`

* `FINISHED_PROGRESS_STR`

* `UN_FINISHED_PROGRESS_STR`

* `TG_OFFENSIVE_API`

* `CUSTOM_FILE_NAME`

* `LEECH_COMMAND`

* `YTDL_COMMAND`

* `GYTDL_COMMAND`

* `GLEECH_COMMAND`

* `TELEGRAM_LEECH_COMMAND`

* `TELEGRAM_LEECH_UNZIP_COMMAND`

* `PYTDL_COMMAND`

* `CLONE_COMMAND_G`

* `UPLOAD_COMMAND`

* `RENEWME_COMMAND`

* `SAVE_THUMBNAIL`

* `CLEAR_THUMBNAIL`

* `GET_SIZE_G`

* `UPLOAD_AS_DOC`: Takes two option True or False. If True file will be uploaded as document. This is for people who wants video files as document instead of streamable.

* `INDEX_LINK`: (Without `/` at last of the link, otherwise u will get error) During creating index, plz fill `Default Root ID` with the id of your `DESTINATION_FOLDER` after creating. Otherwise index will not work properly.

* `DESTINATION_FOLDER`: Name of your folder in ur respective drive where you want to upload the files using the bot.

## CREDITS

 - [GautamKumar](https://github.com/gautamajay52/TorrentLeech-Gdrive) 😚
 - [SpEcHiDe](https://github.com/SpEcHiDe/PublicLeech) for his wonderful code😚
 - [Rclone Team](https://rclone.org) for theirs awesome tool☁️
 - [Dan Tès](https://telegram.dog/haskell) for his [Pyrogram Library](https://github.com/pyrogram/pyrogram)
 - [Robots](https://telegram.dog/Robots) for their [@UploadBot](https://telegram.dog/UploadBot)
 - [@AjeeshNair](https://telegram.dog/AjeeshNait) for his [torrent.ajee.sh](https://torrent.ajee.sh)
 - [@gotstc](https://telegram.dog/gotstc), @aryanvikash, [@HasibulKabir](https://telegram.dog/HasibulKabir) for their TORRENT groups
