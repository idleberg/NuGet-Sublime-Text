# NuGet for Sublime Text

[![The MIT License](https://img.shields.io/badge/license-MIT-orange.svg?style=flat-square)](http://opensource.org/licenses/MIT)
[![GitHub release](https://img.shields.io/github/release/idleberg/sublime-nuget.svg?style=flat-square)](https://github.com/idleberg/sublime-nuget/releases)
[![Travis](https://img.shields.io/travis/idleberg/sublime-nuget.svg?style=flat-square)](https://travis-ci.org/idleberg/sublime-nuget)

Sublime Text snippets for creating [NuGet](http://www.nuget.org/) XML files.

## Installation

### Package Control

1. Make sure you already have [Package Control](https://packagecontrol.io/) installed
2. Choose *“Install Package”* from the Command Palette (<kbd>Super</kbd>+<kbd>Shift</kbd>+<kbd>p</kbd>)
3. Type *“NuGet”* and press <kbd>Enter</kbd>

### Using Git

1. Change to your Sublime Text `Packages` directory
2. Clone repository `git clone https://github.com/idleberg/sublime-nuget.git NuGet`

### Manual installation

1. Download the latest [stable release](https://github.com/idleberg/sublime-nuget/releases)
2. Unzip the archive to your Sublime Text `Packages` directory

## Usage

By default, SublimeText does not show the completion pop-up when working in the text scope, yet the completions still work. To enable the pop-up, add `text.xml.nuspec` (or `text.xml`) to `auto_complete_selector` in your user settings.

### Snippets

All available NuGet XML elements will complete as you press the `Tab` key.

### Scaffolding

You can use `nuget_spec` to scaffold an empty XML file. Use `Tab` to jump between the available fields.

## License

This work is licensed under the [The MIT License](LICENSE).
