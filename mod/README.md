# Overview

Do you like terraform stations from my mod [Aesthetic Terraform Stations](https://steamcommunity.com/sharedfiles/filedetails/?id=2622411084)?  Do you also want to have properly-skinned terraform stations for the [Machine Shipset](https://steamcommunity.com/sharedfiles/filedetails/?id=2077186491)?  Then this mod is for you!

# Changes

Adds a terraform station definition with an active terraforming beam for graphical culture `machine_01`, required for Aesthetic Terraform Stations to apply the correct appearance.

## Compatibility

Should work with practically everything that also works with Machine Shipset and Aesthetic Terraform Stations.  This mod is technically achievement compatible, but its dependencies are not.

Built for Stellaris version 3.6 "Orion" and backwards-compatible with versions 3.5 "Fornax," 3.4 "Cepheus," 3.3 "Libra," 3.2 "Herbert," 3.1 "Lem", and 3.0 "Dick."

### Required Dependency Mods

[Aesthetic Terraform Stations](https://steamcommunity.com/sharedfiles/filedetails/?id=2622411084) enables the very old-school terraform stations as visual markers for terraforming planets.

[Machine Shipset](https://steamcommunity.com/sharedfiles/filedetails/?id=2077186491) for the original graphics and other ship-related code.

### Recommended Companion Mods

[Ringworld Graphical Enhancements](https://steamcommunity.com/sharedfiles/filedetails/?id=2628518102), [Shattered Ring Shipset Fix](https://steamcommunity.com/sharedfiles/filedetails/?id=2566249278), or [Subtle Polish: A Collection of Fixes and Enhancements](https://steamcommunity.com/sharedfiles/filedetails/?id=2522974089) to set your Origin: Shattered Ring empires to have ringworlds matching their shipset (graphical culture).

[Machine Shipset Add-on: Shattered Ring Appearance](https://steamcommunity.com/sharedfiles/filedetails/?id=2628980994) ensures that the permanently-destroyed sections for Origin: Shattered Ring using the Machine Shipset properly display as that shipset.  This mod adds missing graphical definitions to the Machine Shipset.

## Changelog

* 1.0.0 Initial version
* 1.1.0 Mark as compatible with Stellaris version 3.2 "Herbert" - no script changes
* 1.2.0 Mark as compatible with Stellaris version 3.3 "Libra" - no script changes
* 1.3.0 Mark as compatible with Stellaris version 3.4 "Cepheus" - no script changes
* 1.4.0 Mark as compatible with Stellaris version 3.6 "Orion" - no script changes

## Source Code

Hosted on [GitHub](https://github.com/corsairmarks/machine_shipset_terraform_station_aesthetic)

### Development Notes

It is best to clone this repository into `<Stellaris User's Directory>/Paradox Interactive/Stellaris/mod`, and then make a connection to the `mod` folder via a `*.mod` file's `path` property.  That will ensure the game can see the files, and also that CWTools will parse them.  Also note that the README.md file exists in the `mod` directory but is symbolically linked in the root directory.