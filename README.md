# Radio-Id Bot (Discord Voice Bot)

Note: The default prefix is `!lounge`

* `!radio help`
List all available commands

* `!radio ping`
Check bot discord latency

* `!radio join <channel-name>`
Join to desired channel, if empty default to Author voice channel

* `!radio list `
List all available radio stations

* `!radio play <radio-station>`
Join/move to author voice channel and start playing the radio

* `!radio stop`
Stop the radio

* `!radio leave`
Leave voice channel

* `!radio about`
About this bot

* `!radio lyrics <song-name>`
Get lyrics based on provided query, lyrics provided by [ksoft.si](https://ksoft.si/)

## References
* https://discordpy.readthedocs.io/en/latest/
* https://stackoverflow.com/a/62495928/4844294
* https://realpython.com/how-to-make-a-discord-bot-python/

## Prerequisite to run/host this bot:
* Python 3.5+
* [FFMPEG](https://ffmpeg.org/download.html)

## Example how to run
on Ubuntu:

    sudo apt install ffmpeg
    virtualenv -p python3.6 venv
    . venv/bin/activate
    pip install -r requirements.txt

Create `.env` file and put your discord bot token on it\
Create `stations.yaml` file (follow the example) and store your radio stations list there\
Run the python

    python main.py
    
## About

* Contact me on [twitter]
