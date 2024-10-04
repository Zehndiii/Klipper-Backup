# Klipper-Backup 💾
Klipper-Backup is a script for manual or automated GitHub or Gitlab backups. It's Lightweight, pragmatic and comfortable.

## Installation

### Download:
```shell
git clone https://github.com/Zehndiii/Klipper-Backup.git
```

### Installation/Configuration:
```shell
~/klipper-backup/install.sh
```

If you want to do manual backups use the provided macros. During installation copy the macro file and inclue the file in your printer.cfg. 
This function is dependent on the gcode shell command you can get it from kiauh.

To scedule weekly jobs you can use anacron.

## RTFM
I would suggest reading the [docs](https://klipperbackup.xyz), as this provides detailed step-by-step instructions and further tips.
Set the server address and server type in the .env file:

server_address="github.com" # eg "gitlab.local" or "gitlab.company.com"
server_type="GITHUB"        # "GITHUB" or "GITLAB"

## YouTube
There are several YouTube videos about Klipper-Backup - thanks to everyone!

* [ModBot: This Klipper Add-on Could Save You! (Klipper-Backup)](https://www.youtube.com/watch?v=47qV9BE2n_Y)

* [Minimal 3DP: The Ultimate Guide to Using Klipper Macros to Backup Your Configuration Files](https://www.youtube.com/watch?v=J4_dlCtZY48)
