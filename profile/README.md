# EZvac

**Realistic heating, cooling and indoor climate for Minecraft.** Free and open
source, for Paper and Purpur servers.

## EZvac

EZvac lets players build working HVAC systems out of ordinary blocks:
thermostats, heat pumps, air conditioners, furnaces, boilers and pool heat
pumps, with vents that carry air through real airflow, and dehumidifiers and
humidifiers. Rooms warm up and cool down over time, and every system works
against a living outdoor climate:
- every biome has its own climate, with smooth transitions between biomes;
- seasons, weather and humidity;
- colder air high on mountains, and steady air deep underground.

Lit screens on every sign, control menus, an on-screen HUD and PlaceholderAPI
placeholders show what's going on.

- **[Modrinth](https://modrinth.com/plugin/ezvac-plugin)**: every release, ready to download
- **[GitHub](https://github.com/EZvac-Plugin/EZvac)**: the source, and the [releases](https://github.com/EZvac-Plugin/EZvac/releases) with full notes
- **[Documentation](https://github.com/EZvac-Plugin/EZvac/tree/main/docs)**: start with *Getting started*

## Official addons

Made alongside EZvac, built only on its public API. Each is its own plugin:
drop it into `plugins/` next to EZvac.

| Addon | What it does | Needs |
| --- | --- | --- |
| [**LiveExposure**](https://github.com/EZvac-Plugin/LiveExposure) | A body temperature for survival players, shown on EZvac's HUD: heat and cold wear them down out in the elements, with an optional sickness system | EZvac ALPHA 2.1 or newer |
| [**EZdebug+**](https://github.com/EZvac-Plugin/EZdebugPlus) | A Debug Potion for admins: signs light up in coloured frames, equipment glows through walls, and working vents puff colour, seen only by whoever drank it | EZvac ALPHA 2.2 or newer |

## Third-party addons

None listed yet. **Built an addon?** Open an issue on
[EZvac](https://github.com/EZvac-Plugin/EZvac/issues) with a link to it, and
it can be listed here.

### Build your own

EZvac has a public API for addons. Addons are ordinary Paper plugins, so
anything from a scoreboard to a survival mechanic can use EZvac's climate.
- **What it offers:**
  - climate readings for any spot or player;
  - every device and where it is: thermostats, equipment, vents, sensors and more;
  - the season calendar;
  - events, such as a system switching mode or a device being added;
  - sections of your own on EZvac's HUD.
- **How to get it:** through [JitPack](https://jitpack.io/#EZvac-Plugin/EZvac).

Start with the [API guide](https://github.com/EZvac-Plugin/EZvac/blob/main/docs/api.md). Both official addons are complete, open-source examples.

## Contributing

Bug reports, ideas and pull requests are welcome. See
[CONTRIBUTING](https://github.com/EZvac-Plugin/EZvac/blob/main/CONTRIBUTING.md)
to build and test EZvac locally.

EZvac and its official addons are released under the MIT License.
