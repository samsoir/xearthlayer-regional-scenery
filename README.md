# XEarthLayer Regional Scenery Packages

This repository hosts regional scenery packages for [XEarthLayer](https://github.com/samsoir/xearthlayer).

## Available Regions

| Region | Code | Version | Ortho Size | Overlay Size |
|--------|------|---------|------------|--------------|
| North America | na | 0.1.0 | 2.9 GB | 190 MB |

## Installation

```bash
# Configure the package library URL
xearthlayer config set packages.library_url https://raw.githubusercontent.com/samsoir/xearthlayer-regional-scenery/main/xearthlayer_package_library.txt

# Install a region
xearthlayer packages install na
```

## Package Downloads

Packages are distributed as GitHub Release assets. The package manager handles downloading automatically.

For manual downloads, see the [Releases](https://github.com/samsoir/xearthlayer-regional-scenery/releases) page.

## Coverage

### North America (na) v0.1.0

Initial release covering:
- US Pacific Northwest
- California
- Nevada

## License

Scenery data generated from publicly available satellite imagery.
