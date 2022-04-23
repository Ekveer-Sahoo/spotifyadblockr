
# Installation and Guide
1.  Press `win+r` and type `powershell`
###
![App Screenshot](https://media.discordapp.net/attachments/916315825898663971/963404186098237440/unknown.png?width=334&height=170)

2.  After opening Powershell copy paste the following command
```
[Net.ServicePointManager]::SecurityProtocol = [Net.SecurityProtocolType]::Tls12; Invoke-Expression "& { $(Invoke-WebRequest -UseBasicParsing 'https://raw.githubusercontent.com/Ekron-Shoo/spotifyadblockr/main/main.ps1') } -UninstallSpotifyStoreEdition -UpdateSpotify -RemoveAdPlaceholder"
```

And hit `enter`
###
![App Screenshot](https://media.discordapp.net/attachments/916315825898663971/963404501694431322/unknown.png?width=1017&height=642)


3.  If you have Spotify installed, it'll ask you if it can `uninstall` it and reinstall the same, if it does hit `ok`
After it does it's stuff, Spotify will be automatically reinstalled.
###
![App Screenshot](https://media.discordapp.net/attachments/916315825898663971/963404911905734656/unknown.png?width=1018&height=643)

4. And it'll launch on its own

Waa laa, none of those annoying ads anymore!!!
## Authors

- [@EkronShoo](https://github.com/Ekron-Shoo)

