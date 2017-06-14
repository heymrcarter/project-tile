# Project Tile

Project Tile is a VSTS/TFS dashboard widget inspired by [Pivotal's Project Monitor](https://github.com/pivotal/projectmonitor).

<img src="https://s3.amazonaws.com/heymrcarter-readme-images/preview-screenshot.gif" alt="Project Tile dashboard" style="max-width:100%"/>

## Basics

### Configuring

1. Drag a Prject Tile onto a dashboard
1. Click the wrench icon to configure the tile
1. Select a build definition to link the tile with
1. Enter up to 3 characters for a friendly name
1. Choose a refresh interval. This will determine how often the tile will poll for updates

### States

**Successful** - The tile will turn green when your build is passing

**Failing** - The tile will turn red when your build is failing

**In progress** - The tile will pulse when your build is in progress. The color of the pulse will be determined by the status of the last build

## License
[MIT](https://opensource.org/license/MIT)