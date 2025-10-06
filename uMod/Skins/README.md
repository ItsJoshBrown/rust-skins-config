# uMod Skins Config

This folder contains a prebuilt `Skins.json` configuration file for the [uMod Skins plugin](https://umod.org/plugins/skins).

## Usage

1. Place `Skins.json` in the `\oxide\config` folder on your server.
2. Reload or restart the plugin with `o.reload Skins` to apply the new skin configurations.

## Alternative: Download

You can also download the latest `Skins.json` directly using `curl`:

### Linux
```bash
curl -L -o Skins.json https://raw.githubusercontent.com/ItsJoshBrown/rust-skins-config/refs/heads/main/uMod/Skins/Skins.json
```

### Windows
```Powershell
Invoke-WebRequest -Uri "https://raw.githubusercontent.com/ItsJoshBrown/rust-skins-config/refs/heads/main/uMod/Skins/Skins.json" -OutFile "Skins.json"
```


## Manual Method

If you prefer not to use `curl`, you can also open the raw version of the file and copy its contents into your existing config:

**Open:** [Skins.json](https://raw.githubusercontent.com/ItsJoshBrown/rust-skins-config/refs/heads/main/uMod/Skins/Skins.json)

Then copy everything and paste it into your own `oxide/config/Skins.json` file, replacing the old configuration.
