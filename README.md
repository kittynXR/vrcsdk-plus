# cátte — VRCSDK+

Enhanced custom inspectors for VRChat SDK Expression Menus and Parameters.

## Installation

### VRChat Creator Companion (Recommended)
1. In VCC, click "Manage Project"
2. Add the repository: `https://vrcsdk-plus.kittyn.cat/index.json`
3. Find "cátte — VRCSDK+" in the package list and click "Add"

### Manual Installation
1. Download the latest release from [Releases](https://github.com/kittynXR/vrcsdk-plus/releases)
2. Extract the zip file to your Unity project's `Packages` folder

## Documentation

See the [package README](kittyncat_tools/cat.kittyn.vrcsdkplus/README.md) for detailed usage instructions.

## Building

This package uses a custom build script that handles versioning, packaging, and GitHub releases:

```bash
./build.sh <major|minor|patch|x.y.z>
```

Examples:
- `./build.sh patch` - Increment patch version (1.0.0 → 1.0.1)
- `./build.sh minor` - Increment minor version (1.0.0 → 1.1.0)
- `./build.sh major` - Increment major version (1.0.0 → 2.0.0)
- `./build.sh 1.5.3` - Set specific version

The build script will:
1. Update the version in package.json
2. Create a VPM-compatible zip package
3. Commit and tag the version
4. Create a GitHub release
5. Trigger VPM repository update

## License

MIT License - see package LICENSE for details

Original work by Dreadrith, ported and maintained by kittyn.

## Links

- [VPM Repository](https://vrcsdk-plus.kittyn.cat/index.json)
- [GitHub Releases](https://github.com/kittynXR/vrcsdk-plus/releases)
- [kittyn.cat](https://kittyn.cat)
