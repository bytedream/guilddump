# GuildDump

A `python3` driven tool for dumping messages, channels and members of discord servers.

## Setup

The server you want to dump must contain a bot within your control (or at least you have to know the token of the bot).
The bot also needs the `member` intent to enabled in order to dump members.

You this additional `pip3` requirements:
```shell
$ pip3 install discord.py simple_term_menu
```

## Run

You can download the script or run it with this:
```shell
$ curl -s https://raw.githubusercontent.com/ByteDream/guilddump/main/guilddump.py -o guilddump.py
$ python3 guilddump.py
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for more details.
