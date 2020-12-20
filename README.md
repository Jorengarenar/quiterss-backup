# QuiteRSS Backup

[![Codacy Badge](https://api.codacy.com/project/badge/Grade/bedc8b049eef4ddf802cafa7433dff06)](https://app.codacy.com/gh/Jorengarenar/quiterss-backup?utm_source=github.com&utm_medium=referral&utm_content=Jorengarenar/quiterss-backup&utm_campaign=Badge_Grade_Settings)

Simple script, which provides more convenient backup options for
[QuiteRSS](https://quiterss.org), than the build-in one.

## Installation
To install this script simply use this command with root privileges:
```sh
make install
```

### Uninstallation
To uninstall this script simply use this command with root privileges:
```sh
make uninstall
```

## Usage
#### To create backup file with date suffix:
```sh
quiterss-backup
```
#### To create backup file without date suffix:
```sh
quiterss-backup -b
```
or
```sh
quiterss-backup --backup
```
#### To restore from backup file (if _file_ not provided, script will use _quiterss-backup.tar.gz_)
```sh
quiterss-backup -r [file]
```
or
```sh
quiterss-backup --restore [file]
```
