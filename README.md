# Banana Client

Banana Client is a Minecraft launcher and client project currently in development. The project is focused first on building a clean, reliable Windows launcher for Minecraft: Java Edition, with future plans for optional in-game client features.

Banana Client is intended to provide a polished launcher experience while respecting Microsoft and Minecraft account ownership requirements.

## Development Status

Banana Client is in early active development.

The current work is focused on the launcher only. The in-game client is not available yet. Planned client-side features are listed separately below and should be treated as future development goals, not current functionality.

## What Banana Client Is

Banana Client aims to be a modern Minecraft launcher with a clean interface, account management, version selection, and support for launching official Minecraft versions.

The long-term goal is to support optional Banana Client enhancements for players who want a more customized Minecraft experience, while still allowing the launcher to be used for standard Minecraft launches.

## Implemented Launcher Features

- Windows desktop launcher application
- Modern Banana Client themed interface
- Microsoft account sign-in flow
- Minecraft: Java Edition ownership verification
- Minecraft profile display using the player username
- Multiple account management
- Account nicknames
- Favorite account support
- Last-used account selection
- Official Minecraft release version selection
- Latest release support
- Vanilla launch mode
- Fabric launch mode preparation
- Launcher settings for RAM allocation, Java path, JVM arguments, theme, logging, update preferences, and launch behavior
- Dark, light, and system theme support

## Planned Client Features

These features are planned for future development and are not part of the current launcher release:

- Optional Banana Client in-game integration
- JVM agent based client injection
- In-game Banana Options menu
- Custom title screen
- Custom pause menu
- In-game account switcher
- Fabric compatibility improvements
- Mod profiles
- Client update management
- Cosmetics
- Modules and client settings

## Screenshots

Screenshots will be added as the launcher UI stabilizes.

| Launcher Home | Account Management | Version Selection |
| --- | --- | --- |
| Screenshot coming soon | Screenshot coming soon | Screenshot coming soon |

| Settings | Microsoft Sign-In | Launching Minecraft |
| --- | --- | --- |
| Screenshot coming soon | Screenshot coming soon | Screenshot coming soon |

## Roadmap

### Phase 1: Launcher Foundation

- Build the desktop launcher interface
- Support Microsoft account login
- Verify Minecraft: Java Edition ownership
- Support multiple local accounts
- Support official Minecraft release versions
- Support Vanilla launching
- Add launcher settings

### Phase 2: Launcher Improvements

- Improve UI polish and accessibility
- Improve account management flows
- Improve version and launch status feedback
- Expand Fabric support
- Add better update handling
- Add public release packaging

### Phase 3: Banana Client Foundation

- Design the optional in-game Banana Client system
- Add client update delivery
- Add initial in-game settings
- Prepare Fabric-compatible client features

### Phase 4: Expanded Client Features

- Add client modules
- Add cosmetics support
- Add mod profiles
- Add custom in-game menus
- Add additional quality-of-life features

## For Minecraft API Reviewers

Banana Client is a launcher project for Minecraft: Java Edition. Microsoft account login is used to authenticate users, verify Minecraft ownership, and retrieve the user’s Minecraft profile information required for launching the game.

The launcher is designed to prevent accounts that do not own Minecraft: Java Edition from being used to launch the game.

## Contributing

Banana Client is currently in early development. Contributions, feedback, issue reports, and design suggestions are welcome once the public repository workflow is finalized.

Planned contribution areas include:

- Launcher UI improvements
- Accessibility improvements
- Bug reports
- Documentation
- Launcher feature testing
- Future client feature discussion

## Contact

Project contact information will be added before public release.

For now, please use the repository issue tracker or discussion area once available.

## Disclaimer

Banana Client is an independent project and is not affiliated with Mojang Studios, Microsoft, Lunar Client, Feather Client, or any other Minecraft launcher or client project.

Minecraft is a trademark of Mojang Synergies AB.
