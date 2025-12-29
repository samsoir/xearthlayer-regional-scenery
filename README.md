# XEarthLayer Regional Scenery Packages

This repository hosts regional scenery packages for [XEarthLayer](https://github.com/samsoir/xearthlayer).

## Coverage Map

**[View Interactive Coverage Map](coverage.geojson)** - Click to explore exact tile coverage

![Coverage regions: NA (blue), EU (orange)](https://img.shields.io/badge/Regions-NA%20%7C%20EU-blue)

## Available Regions

| Region | Code | Version | Tiles | Ortho Size | Overlay Size |
|--------|------|---------|-------|------------|--------------|
| Europe | EU | 0.1.0 | 1,119 | 26.4 GB | 2.1 GB |
| North America | NA | 0.2.1 | 2,107 | 35.9 GB | 1.8 GB |

## Installation

```bash
# Configure the package library URL
xearthlayer config set packages.library_url https://raw.githubusercontent.com/samsoir/xearthlayer-regional-scenery/main/xearthlayer_package_library.txt

# Install a region
xearthlayer packages install na --type ortho
xearthlayer packages install na --type overlay
```

## Package Downloads

Packages are distributed as GitHub Release assets. The package manager handles downloading automatically.

For manual downloads, see the [Releases](https://github.com/samsoir/xearthlayer-regional-scenery/releases) page.

## Coverage Details

### Europe (EU) v0.1.0

Initial release covering:
- United Kingdom & Ireland
- France, Germany, Benelux
- Spain, Portugal
- Italy, Switzerland, Austria, Alps
- Scandinavia (Norway, Sweden, Finland, Denmark)
- Iceland
- Eastern Europe (Poland, Czech Republic, Hungary, Balkans)
- Mediterranean (Greece, Turkey, Cyprus)
- Baltic States

### North America (NA) v0.2.1

Expanded coverage including:
- **Hawaii** - Main islands
- **Alaska** - Major areas
- **Canada** - Partial coverage
- **Contiguous 48 States** - Partial coverage
- **Caribbean** - Islands and coastal areas
- **Mexico** - Coverage areas

Geographic extent: +07° to +71° latitude, -078° to -163° longitude

## License

Scenery data generated from publicly available satellite imagery.
