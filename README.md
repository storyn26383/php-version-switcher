# PHP Version Switcher for Homebrew

## Installation

### via curl

```bash
sh -c "$(curl -fsSL https://raw.githubusercontent.com/storyn26383/php-version-switcher/master/installer)"
```

### via wget

```bash
sh -c "$(wget https://raw.githubusercontent.com/storyn26383/php-version-switcher/master/installer -O -)"
```

## Usage

Switch to php 7.1

```bash
$ phpver 71

Switch version from php56 to php71 ...

Unlinking /usr/local/Cellar/php56/5.6.30_6... 17 symlinks removed
Linking /usr/local/Cellar/php71/7.1.5_17... 17 symlinks created

Done!

Extension differences:
- ereg
- imagick
- memcache
- mhash
- mysql
+ redis
```
