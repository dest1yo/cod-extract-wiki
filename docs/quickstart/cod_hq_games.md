# Quickstart for CoD HQ Games

!!! note ""
    This tutorial applies to current CoD HQ titles:

    - BO6
    - BO7

!!! warning "Risk Disclaimer"
    ^^As a tool developer, I have never been banned for developing or using these tools.^^ As long as you follow this tutorial for the correct dump procedure and avoid running the tool while the game is running, the chance of being banned by the game's anti-cheat is almost zero, since we are not developing hacks or cheats that disrupt or damage the game. As long as we use the game assets solely for community purposes, it should be entirely safe, unless the game developers takes specific action against us.

    Please be aware that while we strive to minimize risk, there is always a possibility of unforeseen issues. Follow all instructions carefully, and proceed at your own discretion.

## How To Get Tools
^^Tools for the latest CoD HQ titles are currently available only to supporters.^^

??? note "Notes on Donations (Click to expand)"
    **Sincere thanks to everyone for your support! Hope you can enjoy the tools.** :blue_heart:

    ^^The donation amount is set low because I don't make a living from donations—all support simply motivates me to keep developing these tools.^^ To be honest, I spend far more time developing these tools than I receive in compensation, but I have never felt that this is unfair and actively complained about it.

    Donations will let me know people find my work useful and are willing to support me, which helps me stay positive and keep going—nothing more.  
    (I think we need at least some sponsorship to at least cover the cost of buying the game lmao.)

    ^^If you feel this is too much or are unable to pay, you can wait for the free public version to be released later.^^  
    I prefer not to get into arguments or over-explain about this, since I believe nice people can be able to understand how developers feel. :smile:

    To those who tend to be self-centered and try to hurt others, I don't mean to blame you, but I have to point out that it's important to consider other people's feelings, not just your own, since no one is forcing you to use these tools.

- You can support me on following ways with a single donation, which grants you the Supporter role for life on my server.
    - [Ko-fi](https://ko-fi.com/dest1yo) ($5)
    - [爱发电 Afdian](https://afdian.com/a/dest1yo) (￥35)

- After you donating in `Ko-fi`, there should be a button on the page called `"Claim Discord Role"`, click it to link your Discord account and have the role automatically assigned by the bot.

- If the button isn't available or you donated in `爱发电 Afdian` (which doesn't have a bot to add role), you can provide your order information to [Support Role Request Channel](discord://discord.com/channels/1191534071055130645/1303034681691738154), and wait for an admin to manually add your role. You can also `@dest1yo`(me) to make sure your message isn't missed.

- Once you have the Supporter role, you'll be able to access the supporter channels and get the latest tools.

## Tools Requirements
- Download [Saluki](https://github.com/echo000/saluki-releases/releases), which is used to extract the assets from `Cordycep`.
- Download `Cordycep` from: [Discord Channel](discord://discord.com/channels/1191534071055130645/1302004278935945218), which is used to load the game assets.
- Get a `License.ccl` for `Cordycep` from: [Discord Message](discord://discord.com/channels/1191534071055130645/1307976595583012865/1312029819005046826).
- Put the `License.ccl` together with `Cordycep.CLI.exe`.
- Make sure you are running the ==Discord APP client== (Not the web version).
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
    - Ask questions in [Supporter Channel](discord://discord.com/channels/1191534071055130645/1301475313749987339).
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
