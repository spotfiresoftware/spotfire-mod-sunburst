# Sunburst Chart Mod for Spotfire®

<img src="assets/sunburst.png" width="60%"/>

Visualize hierarchical data, depicted by concentric circles. A segment of the inner circle bears a hierarchical relationship to those segments of the outer circle which lie within the angular sweep of the parent segment.
A sunburst chart without any hierarchical data (one level of categories), looks similar to a donut chart. However, a sunburst chart with multiple levels of categories shows how the outer rings relate to the inner rings.

## Installation & Use

[Download latest version](https://github.com/spotfiresoftware/spotfire-mod-sunburst/releases)

The [Wiki](https://github.com/spotfiresoftware/spotfire-mod-sunburst/wiki) contains step-by-step instruction on how to install and use this Mod in Spotfire®.

## Building the Project

In a terminal window:
- `npm install`
- `npm run build-watch`

In a new terminal window:
- `npm run server`

### Building for production

The development version of bundle.js is uncompressed and not suitable for end-users. Run the following command to compress the bundle:
- `npm run build`

## About Mods for Spotfire®
-   [Spotfire Community Exchange](https://community.spotfire.com/files/): A safe and trusted place to discover ready-to-use Mods
-   [Developer documentation](https://spotfiresoftware.github.io/spotfire-mods/docs/): Introduction and tutorials for Mods developers
-   [Mods examples](https://github.com/TIBCOSoftware/spotfire-mods/): A public repository for examples projects
