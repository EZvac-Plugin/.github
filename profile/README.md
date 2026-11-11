# EZvac

**Realistic heating, cooling and indoor climate for Minecraft.** Free and open
source, for Paper and Purpur servers on Minecraft 26.1 to 26.3 (and still
1.21.x until BETA 2.x).

> **Now in BETA:** [BETA 1.0 Pilot 6](https://github.com/EZvac-Plugin/EZvac/releases/tag/BETA-1.0-P6)
> words the weather as players see it, and comes with
> [EZclimates 0.2.0](https://github.com/EZvac-Plugin/EZclimates/releases/tag/0.2.0):
> body temperature that meets rain, fires, food and the cold's hunger.
> [Pilot 5](https://github.com/EZvac-Plugin/EZvac/releases/tag/BETA-1.0-P5)
> built EZdebug into EZvac, and
> [Pilot 4](https://github.com/EZvac-Plugin/EZvac/releases/tag/BETA-1.0-P4)
> brought 30-day seasons, the Addons menu and EZclimates. Pilots are test
> builds ahead of the full BETA 1.0.

## EZvac

EZvac lets players build working HVAC systems out of ordinary blocks:
thermostats (on a screen, or a mini one on a wall button), heat pumps, air
conditioners, furnaces, boilers and pool heat pumps, with vents that carry air
through real airflow, and dehumidifiers, humidifiers and air purifiers. One
link tool connects each thermostat to its equipment, vents and signs. Rooms
warm up and cool down over time, and every system works against a living
outdoor climate:
- every biome has its own climate, with smooth transitions between biomes;
- seasons following Minecraft's own days, rain or snow by the air, weather,
  humidity, and wind from the climate's prevailing direction that differs
  from region to region;
- the air itself: smoke (drifting downwind from fires in the open), dust and
  pollen, scored as the US EPA Air Quality Index;
- the sun, which feels warmer than the shade;
- colder air high on mountains, and steady air deep underground.

Bigger buildings need more equipment, as real ones do: open doors and holes
leak, and neighbouring systems even out. Weather stations forecast the week
ahead.

Lit screens on every device, control menus, a quick settings menu for server
owners (with a menu that switches official addons), an on-screen HUD and
PlaceholderAPI placeholders show what's going on. Built-in EZdebug shows the
system you're linking as EZvac sees it, down to where its room leaks.

- **[Modrinth](https://modrinth.com/plugin/ezvac-plugin)**: every release, ready to download
- **[GitHub](https://github.com/EZvac-Plugin/EZvac)**: the source, and the [releases](https://github.com/EZvac-Plugin/EZvac/releases) with full notes
- **[Documentation](https://github.com/EZvac-Plugin/EZvac/tree/main/docs)**: start with *Getting started*

## Official addons

Made alongside EZvac, built only on its public API. Each is its own plugin:
drop it into `plugins/` next to EZvac. From BETA 1.0 Pilot 4, EZvac's
`/hvac addons` menu lists them, switches them on and off, and says when one
has an update.

| Addon | What it does | Needs |
| --- | --- | --- |
| [**EZclimates**](https://github.com/EZvac-Plugin/EZclimates) | Seasons you can see and feel: rain and snow where EZvac's air says, leaves that turn through the year, snow that settles and melts, frozen lakes, crops that grow by the air (a heated greenhouse grows through winter), flowers and leaf litter by the season, planned weather with snowstorms, heat waves and cold snaps, and body temperature: rain soaks you, fires warm you, food helps and the cold makes you hungry. [Download 0.2.0](https://github.com/EZvac-Plugin/EZclimates/releases/tag/0.2.0) | EZvac [BETA 1.0 Pilot 4](https://github.com/EZvac-Plugin/EZvac/releases/tag/BETA-1.0-P4) or newer, Minecraft 26.1 or newer, and [packetevents](https://github.com/retrooper/packetevents) |
| [**EZdebug+**](https://github.com/EZvac-Plugin/EZdebugPlus) | Adds to EZvac's built-in EZdebug: a Debug Potion that shows every system at once, seen only by whoever drank it. Signs light up in coloured frames, equipment glows through walls, working vents puff colour, every room's edge is dotted in and its leaks glow red, weather stations' areas are outlined, and dotted lines join devices to what they're linked to. [Download 0.4.0](https://github.com/EZvac-Plugin/EZdebugPlus/releases/tag/0.4.0) | EZvac ALPHA 2.2 or newer (BETA 1.0 Pilot 5 for rooms and leaks) |
| [**MapPeek**](https://github.com/EZvac-Plugin/MapPeek) | EZvac on your web map, on squaremap or BlueMap: weather stations with their coverage, wind arrows and forecasts; the wind and air quality across the explored map, the time and season, and optionally the wind in motion. A `/mappeek` menu sets it up. [Download 0.3.0](https://github.com/EZvac-Plugin/MapPeek/releases/tag/0.3.0) | EZvac [BETA 1.0 Pilot 3](https://github.com/EZvac-Plugin/EZvac/releases/tag/BETA-1.0-P3) or newer, and [squaremap](https://modrinth.com/plugin/squaremap) or [BlueMap](https://modrinth.com/plugin/bluemap) |

**Discontinued:** [LiveExposure](https://github.com/EZvac-Plugin/LiveExposure),
a body temperature for survival players, is now part of EZclimates. Its last
release, [0.2.1](https://github.com/EZvac-Plugin/LiveExposure/releases/tag/0.2.1),
keeps working on Minecraft 1.21.x servers.

## Third-party addons

None listed yet. **Built an addon?** Open an issue on
[EZvac](https://github.com/EZvac-Plugin/EZvac/issues) with a link to it, and
it can be listed here.

### Build your own

EZvac has a public API for addons. Addons are ordinary Paper plugins, so
anything from a scoreboard to a web map to a survival mechanic can use
EZvac's climate.
- **What it offers:**
  - climate readings for any spot or player, with air quality and wind;
  - every device and where it is: thermostats, equipment, vents, sensors and more;
  - each system's size, profile and what needs attention;
  - weather stations and their seven-day forecasts;
  - the season calendar and the server's settings;
  - events, such as a system switching mode or a device being added;
  - sections of your own on EZvac's HUD;
  - a weather plan stations forecast from, and a switch in the Addons menu.
- **How to get it:** through [JitPack](https://jitpack.io/#EZvac-Plugin/EZvac).

Start with the [API guide](https://github.com/EZvac-Plugin/EZvac/blob/main/docs/api.md). The official addons are complete, open-source examples.

## Questions

**Why doesn't EZvac's addon store list third-party addons?**
The store in `/hvac addons` only ever lists official addons, and always
will. EZvac can't verify a third-party addon's code, security or who really
made it, and a link from inside EZvac would look like an endorsement.
Well-known, widely used third-party addons can still be listed in the
*Third-party addons* section on this page, which links to their own pages.

**Does EZvac download or install addons?**
No. The store only gives a link to each addon's GitHub page. You download
and install it yourself.

**Which Minecraft versions are supported?**
EZvac BETA 1.x runs on Paper and Purpur 26.1 to 26.3, and still on 1.21.x
until BETA 2.0. Some addons need 26.1 or newer (EZclimates does); each
addon's page says what it needs.

**Where do I report a bug or suggest something?**
In [EZvac's issues](https://github.com/EZvac-Plugin/EZvac/issues), or the
official addon's own repository for an official addon.

**Where do I get help with a third-party addon?**
From that addon, through its own page or issues: EZvac can't support addons
it doesn't make. If you're **developing** an addon and something in EZvac's
API doesn't work as documented, or you need something it doesn't offer yet,
that belongs in [EZvac's issues](https://github.com/EZvac-Plugin/EZvac/issues):
help for addon developers is welcome there.

## Contributing

Bug reports, ideas and pull requests are welcome. See
[CONTRIBUTING](https://github.com/EZvac-Plugin/EZvac/blob/main/CONTRIBUTING.md)
to build and test EZvac locally.

EZvac and its official addons are released under the MIT License.
