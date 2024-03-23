# CasaOS Appstore 

## Add to CasaOS

To add this app store:

## App Store URL

```text
https://github.com/JorgeCarrascoBarbero/CasaOS-AppStore/archive/refs/heads/main.zip
```


 From command line, run:

```shell
casaos-cli app-management register app-store [your zip file link]
```
If your CasaOS is on a different port than `80` use the below instead:

```shell
casaos-cli app-management register app-store [your zip file link] -u localhost:[your port]
```