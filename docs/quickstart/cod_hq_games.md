# Quickstart for CoD HQ Games

!!! note ""
    This tutorial applies to current CoD HQ titles:

    - BO6
    - BO7

!!! warning "Risk Disclaimer"
    ^^As a tool developer, I have never been banned for developing or using these tools.^^ As long as you follow this tutorial for the correct dump procedure and avoid running the tool while the game is running, the chance of being banned by the game's anti-cheat is almost zero, since we are not developing hacks or cheats that disrupt or damage the game. As long as we use the game assets solely for community purposes, it should be entirely safe, unless the game developers takes specific action against us.

    Please be aware that while we strive to minimize risk, there is always a possibility of unforeseen issues. Follow all instructions carefully, and proceed at your own discretion.

## Tools Requirements
- Download [Saluki](https://github.com/echo000/saluki-releases/releases), which is used to extract the assets from `Cordycep`.
- Download `Cordycep` from: [Discord Channel](discord://discord.com/channels/1191534071055130645/1194338541371670609), which is used to load the game assets.
- Run `Cordycep` and wait for verification to complete. (After this you don't have to keep the Discord running.)

## Dumping Games
!!! danger ""
    ==**Turn Off the Internet**== on your computer, ensure that both your ==**Game and the Platform are Not Running**== while performing the dump, or you will be banned.

- Enter the command to dump the game you want. ==(Change it to your actual game path.)==
    - BO6: `dump "path\to\cod24\cod24-cod.exe"`
    - BO6 Campaign: `dump "path\to\sp24\sp24-cod.exe"`
    - BO7 Beta: `dump "path\to\cod25\cod25-cod.exe"`
    - BO7: `dump "path\to\cod.exe"`

!!! tip ""
    - ^^After the dump has completed successfully, you no longer need to remain offline.^^
    - ^^You don't have to dump every time you run the Cordycep, unless the game is updated or you never dump the game.^^

## Loading Assets
- Modify the bat of the game you want to extract in `Cordycep/Run` folder.
    - BO6: `RunBO6.bat`
    - BO6 Campaign: `RunBO6SP.bat`
    - BO7 Beta: `RunBO7Beta.bat`
    - BO7: `RunBO7.bat`
- Modify the game directory path in bat to ^^==CoD HQ Main Directory==^^ of yours. Examples:
    - Steam: `"path/to/Call of Duty HQ"`
    - Battle.Net: `"path/to/Call of Duty`==/\_retail_==`"`
    - Xbox Game Pass: `"path/to/Call of Duty`==/Content==`"`

!!! warning ""
    - ^^Do not include `cod24`, `sp24`, `cod25`, etc. sub game folders in the path.^^
    - ^^The path can not end with a backslash (\\).^^
    - ^^Ensure that the path is surrounded by exactly ==one== pair of double quotes (""), rather than none or two pairs.^^

- Now can just run the bat to start Cordycep.

!!! tip ""
    Just run bat directly afterwards, unless the game is updated, then you should dump again.

- With `Cordycep` loaded you can use `Saluki` to export assets.
- Enter `help` to find out how to use some `load` commands to load the assets.

!!! tip ""
    - When extracting assets by `Saluki`, make sure `Cordycep` is running and has loaded the assets you need. You can think of it as a game.
    - If you don't know them well and have enough RAM, you can just type `loadall` to load all the game files.
    - Estimated RAM Usage (GB)
        - BO6: Over 20
        - BO7 Beta: Over 4

## Notes
- Every big update like a `season update` can mess up the tools support which takes time to re-adapt. If you are worried about this, you can choose:
    - Not to update the game right away after big game updates.
    - Follow the news in the channels or make a backup for game.

- If you run into any problems, you can:
    - Ask questions in chat channels.
    - Post questions, issues or requests in: [Feedback Forum](discord://discord.com/channels/1191534071055130645/1302069283010121818).

!!! tip "Tip for Posting Issues"
    - When submitting an issue, always provide detailed information about your problem. ^^Include relevant text descriptions, screenshots, logs, and steps to reproduce the issue.^^ The more details you give, the easier and faster it will be for others to help you!
    - Such as:
        - Your operation process
        - Game name
        - Asset names you tried to extract
        - Log files
        - Crash information or crash dump files
        - For `Saluki`: dat and crash files in `%appdata%/saluki/config`
