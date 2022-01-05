# SaferWater for Cubeville

A plugin for Minecraft Bukkit servers that makes the underwater world a bit safer. Built for [Cubeville](https://www.cubeville.org/).

## Installation

Simply drop the appropriate file into the `plugins/` folder for your Bukkit installation, and then (re-)start the server.

The currently-supported versions of Bukkit are:
- 1.18.1

_Please Note: This plugin may work with other versions of Bukkit, but is not guaranteed to._

### Configuration

A default configuration file (`config.yml`) will be created in the plugin's data folder when you start the server for the first time after installing the plugin. You can then edit the configuration file as needed, and then run the reload command to reload the configuration file:
- `/saferwater reload`

When new releases of the plugin are made available, the default configuration file may update; however, the configuration file in the plugin's data folder will not be updated. While we try not to change the configuration file, sometimes it is unavoidable. You may obtain an up-to-date version of the default file from [here](https://github.com/unixminecraft/SaferWater/blob/main/src/main/resources/config.yml). You can simply drop the updated file in place of the old one, updating the values to reflect your requirements and/or previous settings. You can then run the reload command in-game to load the updated configuration.

The SaferWater plugin can accept alternative names for its configuration file, if the default `config.yml` is confusing to keep track of (configuration files will be in the plugin's data folder). The plugin will also accept `saferwater.yml` as a configuration file name. More information can be found at the top of the default configuration file (can be viewed [here](https://github.com/unixminecraft/SaferWater/blob/main/src/main/resources/config.yml)).

## In-Game Usage / Commands & Permissions

There is no main functionality that can be triggered or otherwise run by in-game commands. The plugin's functionality is in the backend spawning mechanics.

The only in-game command that can be run will reload the configuration file. The command, along with its respective description and permission node, is listed below:

**Base SaferWater Command:** The base command for all SaferWater commands. If this command has no arguments, a list of all subcommands that the sender has permission to use, and their respective syntax, will be displayed. **Please Note:** This permission **MUST** be granted to all that wish to use any SaferWater subcommand.
- `/saferwater` - `saferwater.command.saferwater`

**Reload Command:** Reloads the configuration file, adding and/or removing mobs from the water-spawning blacklist.
- `/saferwater reload` - `saferwater.command.saferwater.reload`

## Licensing

The project uses the following licenses:
- [The GNU General Public License, Version 3](https://www.gnu.org/licenses/gpl-3.0.en.html)
