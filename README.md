# ZorinGDM3

Customize your login screen background for Zorin OS 16.

## Installation

Download the script via wget:

```bash
wget https://raw.githubusercontent.com/wingedz/zoringdm3/main/zoringdm3
```
Grant permissions:

```bash
chmod 775 zoringdm3
```
## Usage

Use an image:
```bash
sudo ./zoringdm3 /absolute/path/to/image
```
Use an hex color code:
```bash
sudo ./zoringdm3 \#aAbBcC
```
Reset:
```bash
sudo ./zoringdm3 --reset
```

## Theme Path
To be able to use this script you need to specify the **gnome-shell-theme.gresource**'s absolute path

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## Credits
This script is based on [focalgdm3](https://github.com/PRATAP-KUMAR/focalgdm3) by [PRATAP-KUMAR](https://github.com/PRATAP-KUMAR)

## License
[GNU GPL](https://github.com/wingedz/zoringdm3/blob/main/LICENSE)
