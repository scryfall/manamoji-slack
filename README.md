# Manamoji for Slack

Slack emojis for _Magic: the Gathering_ card symbols.

![](https://cloud.githubusercontent.com/assets/769083/24091884/48c75d26-0d21-11e7-83ea-06f6c6e6f4d4.png)

These symbols are designed for use with [Scryfall’s Slack bot](https://scryfall.com/bots). After you install these emojis, the Slack bot will automatically start using them with your Slack team.

### Installation

1. [Download this project as a ZIP file](https://github.com/scryfall/manamoji-slack/archive/master.zip)
2. [Upload each of the emoji](https://get.slack.help/hc/en-us/articles/206870177-Create-custom-emoji) images to your Slack team, or [bulk upload](#bulk-uploading) them. 
3. 👉 **Important:** You must name the emoji you create the same as their image file name. For example, the green mana symbol in `mana-g.png` must become an emoji named `:mana-g:`. Scryfall’s Slack bot will detect emojis with this name style.
4. Done!


### Bulk Uploading

You may quickly upload all Manamojis to Slack using [emojipacks](https://github.com/lambtron/emojipacks). Follow the [install instructions](https://github.com/lambtron/emojipacks#install), and then run the `emojipacks` command to start the upload process. Follow the subsequent propmts for Slack login information, and then provide the following for the emojipack file reference:

```
Path or URL of Emoji yaml file: https://raw.githubusercontent.com/scryfall/master/yaml-importer/emojipack.yaml
```

:fire:

### License

We hereby release this project to [the public domain](LICENSE.md).
