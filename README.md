# Nighty-Tab-Plugin

An Equicord plugin that embeds a customizable web tab on the Discord home sidebar beneath the Quests tab.

## Features

- Adds a dedicated sidebar tab routing to `/nighty`.
- Embeds a user-configured HTTP or HTTPS URL within an iframe.
- Bypasses iframe restrictions on Discord Desktop via native CSP policies.
- Optional script utility actions for quick message replies.

## Configuration

Open Settings -> Plugins -> Nighty Tab:
- **URL**: The web address to display inside the embedded tab.
- **Script Utils functions**: Toggles the message context menu and popover actions.
- **Nighty Prefix**: The prefix character prepended to the `dls` reply command (defaults to `.`).

## License

GNU General Public License v3.0 (GPL-3.0-or-later). See [LICENSE](./LICENSE).
