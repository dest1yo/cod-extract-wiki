# Quickstart for CoD Online

## Tools Requirements

!!! note ""
    Tools only support the latest version/build of COD Online.

- Download the latest version/build of [COD Online](https://drive.google.com/file/d/1g-hbStIWOwQqrHHDRvhY0Tq-6XMzF2y-/view).
    - (Thanks to `TheZombieDon` and `Kore` for putting this together!).

- Download [Cordycep-rs](https://github.com/dest1yo/Cordycep-rs-releases/releases), which is used to load the game assets.

- [Saluki](https://github.com/echo000/saluki-releases/releases), which is used to extract the assets from Cordycep.

## Getting ready to rip assets

- Once you downloaded everything above, extract all of them.

- Head to your Cordycep-rs folder and create this directory `Data/Dumps`(e.g `Cordycep-rs/Data/Dumps`).

- Download the game dump file from [Discord](discord://discord.com/channels/1191534071055130645/1302004278935945218/1425520730833158154) and put it the `Dumps` folder.

- Now go back to the root of your Cordycep-rs folder and create a new text document, rename the file to `RunOL.bat`.

- Open the bat by right clicking it and clicking edit, once open paste the following commands into it, make sure edit the directory with your games path.
    - `Cordycep-rs sethandler ol setpath "F:\CODOL_v3.19.26.22" init loadcommonfiles`

- You're now ready to rip assets from COD Online.

- Run the `RunOL.bat` and Saluki, load game in Saluki and you should see assets!

!!! warning ""
    - *You can type =="help"== into Cordycep to see the list of commands.*
    - *The X86 process can only has 4GB of RAM, so make sure don't load too many files, or the process will crash.*
    - *Unloading files is not supported.*