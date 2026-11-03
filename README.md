# Kronos Workshop

The content list for the Workshop in the Kronos launcher for Call of Duty: Black Ops 7.

The Workshop is a page in the launcher. It reads `index.json` from this repository, shows every mod in it, and installs them for you:

- Every mod goes to `cod25/kronos/mods/<id>/`
- Scripts, UI and asset mods all install the same way; the type only sets the tag on the card

Installed mods show on the launcher's Library page and in the game's Mods menu, where they can be turned on or off.

Every file is checked against the SHA-256 hash in `index.json` before it is installed. A file that does not match is deleted. The list itself is signed; the launcher ignores a list that has been changed by anyone else.

## Submitting

Read the [wiki](https://github.com/Divity/kronos-data/wiki).
