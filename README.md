# Ubuntu Xdebug Toggler


### THIS IS MODIFIED VERSION OF  [ihorvorotnov/xdebug.sh](https://github.com/ihorvorotnov/xdebug.sh) TO WORK ON UBUNTU


Toggle Xdebug PHP extension on and off, from command line. Also, quickly check status (enabled/disabled) and versions (PHP and Xdebug).


## Requirements

- Ubuntu
- PHP installed via apk
- [Laravel Valet for Linux](https://github.com/cpriego/valet-linux) as your local development environment

## Installation & Usage

1. Clone this repo somewhere
2. `cd` into the dir
3. `chmod a+rx xdebug-toggle`
4. Create symlink `sudo ln -s /path/to/xdebug-toggle /usr/sbin/xdebug`
5. Run `xdebug help`

### Available commands

| Command | Description |
|:--|:--|
| `xdebug on` | Turns on Xdebug extension and reloads PHP via Valet. Checks if it’s already enabled first. |
| `xdebug off` | Turns off Xdebug extension and reloads PHP via Valet. Checks if it’s already disabled first. |
| `xdebug status` | Checks whether Xdebug extension is enabled or not. |
| `xdebug version` | Shows PHP and Xdebug versions. |
| `xdebug help` | Shows this help. |

## Update

1. `cd` into the dir
2. Run `git pull`

