<center>
    <h2 align="center"> IMPORTANT ANNOUNCEMENT </h2>
    <p align="center">it wont be supported anymore. After this day, this repository will be a public archive. <strong>But it's not the end.</strong> We are moving to <a href="https://github.com/Gvazo">SpotX</a>. For more info, add me on Discord Gvazo#6970.
</center>

<center>
    <h1 align="center">SPOTIFY</h1>
    <h4 align="center">A multi-purpose adblocker and skip-bypass for the <strong>Windows</strong> Spotify desktop application.</h4>
    <h5 align="center">Please support Spotify by purchasing premium</h5>
    <p align="center">
        <strong>Last updated:</strong> 3 December 2022 <br>
        <strong>Last tested version:</strong> 1.1.99.878.g1e4ccc6e
    </p> 
</center>

#### Just run simple.bat if you lazy to read things.

#### Important checks before installing:

0. Update Windows, update Spotify and update BlockTheSpot
1. Go to "Windows Security" -> "Virus & Threat Protection"
2. Click "Allowed threats" -> "Remove all allowed threats"


### Features:

- Blocks all banner/video/audio ads within the app
- Retains friend, vertical video and radio functionality
- Unlocks the skip function for any track



### Installation/Update:

- Just download and run [SpotX](https://raw.githack.com/mrpond/Gvazo/master/SpotXBasic.bat)

or

#### Fully automated installation via PowerShell

- Run The following command in PowerShell:

```ps1
[Net.ServicePointManager]::SecurityProtocol = [Net.SecurityProtocolType]::Tls12; iex "& { $((iwr -useb 'https://raw.githubusercontent.com/amd64fox/SpotX/main/Install.ps1').Content) } -confirm_uninstall_ms_spoti -confirm_spoti_recomended_over -podcasts_on -cache_off -block_update_off -exp_standart -hide_col_icon_off -start_spoti"
```

- Checkout [SpotX Repo](https://github.com/amd64fox/SpotX) for more options and features.

#### Manual installation

1. Browse to your Spotify installation folder `%APPDATA%\Spotify`
2. Download `chrome_elf.zip` from [releases](https://github.com/mrpond/Gvazo/releases)
3. Unzip `dpapi.dll` and `config.ini` to Spotify directory.

### Uninstall:

- Just run [uninstall.bat](https://raw.githack.com/mrpond/BlockTheSpot/master/Uninstall.bat)
  or
- Reinstall Spotify

### Additional Notes:

- "dpapi.dll" may gets removed by the Spotify installer each time it updates, hence why you'll probably need to apply the patch again when it happens
- [Spicetify](https://github.com/khanhas/spicetify-cli) users will need to reapply BlockTheSpot after applying a Spicetify themes/patches.
- If the automatic install/uninstall scripts do not work, open issue at [SpotX](https://github.com/amd64fox/SpotX) or contact [Amd64Fox](https://github.com/amd64fox) or [Nuzair46](https://github.com/Nuzair46).
- For more support and discussions, join our [Discord server](https://discord.gg/p43cusgUPm).

### DISCLAIMER

- Autoinstaller is maintaned at [SpotX](https://github.com/amd64fox/SpotX). Any issue related to it should be opened in the said repo. 
- Ad blocking is the main concern of this repo. Any other feature provided by SpotX or consequence of using those features will be the sole repsonsiblity of the user and not either BlockTheSpot or SpotX team will be responsible.
