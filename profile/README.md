# EZvac

**Realistic heating, cooling and indoor climate for Minecraft.** Free and open
source, for Paper and Purpur servers.

EZvac lets players build working HVAC systems out of ordinary blocks:
thermostats, heat pumps, air conditioners, furnaces, boilers and pool heat
pumps, with vents that carry air through real airflow, and dehumidifiers and
humidifiers. Rooms warm up and cool down over time, and every system works
against a living outdoor climate:
- every biome has its own climate, with smooth transitions between biomes;
- seasons, weather and humidity;
- colder air high on mountains, and steady air deep underground.

## Projects

| Project | What it is |
| --- | --- |
| [**EZvac**](https://github.com/EZvac-Plugin/EZvac) | The plugin: systems, the climate simulation, lit screens on every sign, control menus, an on-screen HUD and PlaceholderAPI placeholders |
| [**LiveExposure**](https://github.com/EZvac-Plugin/LiveExposure) | The first addon: a body temperature for survival players, so heat and cold wear them down out in the elements, with an optional sickness system. Built on the EZvac API |

## Get EZvac

- **[Modrinth](https://modrinth.com/plugin/ezvac-plugin)**: every release, ready to download
- **[GitHub releases](https://github.com/EZvac-Plugin/EZvac/releases)**: the same jars, with full release notes
- **[LiveExposure releases](https://github.com/EZvac-Plugin/LiveExposure/releases)**: the addon, which needs EZvac ALPHA 2.1 Pilot 4 or newer
- **[Documentation](https://github.com/EZvac-Plugin/EZvac/tree/main/docs)**: start with *Getting started*

## Build on EZvac

EZvac has a public API for addons, starting with ALPHA 2.1 Pilot 4.
- **What it offers:** climate readings for any spot or player, thermostats and their systems, the season calendar, and events such as a player's climate changing or a system switching mode.
- **How to get it:** through [JitPack](https://jitpack.io/#EZvac-Plugin/EZvac).
- **How addons work:** they're ordinary Paper plugins, so anything from a scoreboard to a survival mechanic can use EZvac's climate.

Start with the [API guide](https://github.com/EZvac-Plugin/EZvac/blob/main/docs/api.md). [LiveExposure](https://github.com/EZvac-Plugin/LiveExposure) is a complete, open-source example of an addon.

## Contributing

Bug reports, ideas and pull requests are welcome. See
[CONTRIBUTING](https://github.com/EZvac-Plugin/EZvac/blob/main/CONTRIBUTING.md)
to build and test EZvac locally.

EZvac is released under the MIT License.
