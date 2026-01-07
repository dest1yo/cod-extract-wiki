# Quickstart for CoD Online

## Tools Requirements

!!! warning ""
    Tools only support the latest version/build of COD Online.

- Download the latest version/build of [COD Online](https://www.rootz.so/d/22M2S).
    - (Thanks to `TheZombieDon` and `Kore` for putting this together!).

- Download [Cordycep-rs](https://github.com/dest1yo/Cordycep-rs-releases/releases), which is used to load the game assets.

- Download [Saluki](https://github.com/echo000/saluki-releases/releases), which is used to extract the assets from Cordycep.

- [COD:Online Fastfile Names txt](../assets/codol_ff_names.txt), List of all fastfile names.

## Getting ready to rip assets

- Once you downloaded everything above, extract all of them.

- Head to your Cordycep-rs folder and create this directory `Data/Dumps`
    - (e.g `Cordycep-rs/Data/Dumps`).

- Download the game dump file from [Discord](discord://discord.com/channels/1191534071055130645/1302004278935945218/1425520730833158154) and put it in the `Dumps` folder.

- Now go back to the root of your Cordycep-rs folder and create a new text document and rename it to `RunOL.bat`.

- Edit the bat by right clicking it and clicking edit, once open paste the following commands into it.

!!! note ""
    `Cordycep-rs sethandler ol setpath "F:\CODOL_v3.19.26.22" init loadcommonfiles`

- Edit the directory with your games path.

- You're now ready to rip assets from COD Online.

- Run the `RunOL.bat` and Saluki, load game in Saluki and you should see assets!

!!! warning ""
    - *You can type =="help"== into Cordycep to see the list of commands.*
    - *The X86 process can only has 4GB of RAM, so make sure don't load too many files, or the process will crash.*
    - *Unloading files is not supported.*