<p align="center"><img src="https://cdn.rawgit.com/arcticicestudio/nord-xcode/develop/src/assets/nord-xcode-banner.svg"/></p>

<p align="center"><img src="https://assets-cdn.github.com/favicon.ico" width=24 height=24/> <a href="https://github.com/arcticicestudio/nord-xcode/releases/latest"><img src="https://img.shields.io/github/release/arcticicestudio/nord-xcode.svg?style=flat-square"/></a> <a href="https://github.com/arcticicestudio/nord/releases/tag/v0.2.0"><img src="https://img.shields.io/badge/Nord-v0.2.0-88C0D0.svg?style=flat-square"/></a> <a href="https://developer.apple.com/xcode"><img src="https://img.shields.io/badge/Xcode-v8+-1C91FE.svg?style=flat-square"/></a></p>

<p align="center">An arctic, north-bluish clean and elegant <a href="https://developer.apple.com/xcode">Xcode</a> color theme.</p>

<p align="center">Designed for a fluent and clear workflow.<br>
Based on the <a href="https://github.com/arcticicestudio/nord">Nord</a> color palette.</p>

---

<p align="center"><img src="https://raw.githubusercontent.com/arcticicestudio/nord-xcode/develop/src/assets/scrot-preview.png"/><blockquote>Font: <a href="https://developer.apple.com/fonts">SF Mono</a> 12px.</blockquote></p>

  - [Getting started](#getting-started)
    - [Installation](#installation)
      - [Manual](#manual)
      - [Install Script](#install-script)
    - [Activation](#activation)
  - [Asset Catalog](#asset-catalog)
    - [Color Set](#color-set)
  - [Development](#development)
    - [Contribution](#contribution)

## Getting started
### Installation
#### Manual
Copy the [`Nord.xccolortheme`](https://github.com/arcticicestudio/nord-xcode/blob/develop/src/Nord.xccolortheme) file to the color theme directory `~/Library/Developer/Xcode/UserData/FontAndColorThemes`.

#### Install Script
The included `install.sh` shell script can be used for an automated installation.

A list of available options can be shown with the `--help` option.
```sh
./install.sh --help
```
Syntax: `install.sh [OPTIONS]`

| Option | Description |
| --- | --- |
| `-h`, `--help` | Shows the help |
| `-v`, `--verbose` | Verbose output |
| `-c  <COLOR_THEME_FILE>`, `--colortheme <COLOR_THEME_FILE>` | Use the specified color theme file |

### Activation
  1. Open *File* > *Preferences*
  2. Switch to the *Fonts & Colors* tab
  3. Select `Nord` from the list

<p align="center"><img src="https://raw.githubusercontent.com/arcticicestudio/nord-xcode/develop/assets/scrot-docs-preferences-editor.png"/><br><img src="https://raw.githubusercontent.com/arcticicestudio/nord-xcode/develop/assets/scrot-docs-preferences-console.png"/></p>

## Asset Catalog

### Color Set

Nord XCode provides a [asset catalog][asset-catalog] color set which can be used as named colors in the [Interface Builder][interface-builder] and programmatically via `UIColor(named:)`.

Install it by [adding the][add-folder-to-project] [nord.xcassets][nord-xcassets] [folder to the project][add-folder-to-project].

<p align="center"><strong>Usage with the Interface Builder</strong><br><img src="https://raw.githubusercontent.com/arcticicestudio/nord-xcode/develop/assets/scrot-asset-catalog-color-set-interface-builder.png"/></p>

For more information please read the official documentation section on how to [create a color set to use in Interface Builder][asset-catalog-creation].

<p align="center"><strong>Asset Catalog - Color Set</strong><br><img src="https://raw.githubusercontent.com/arcticicestudio/nord-xcode/develop/assets/scrot-asset-catalog-color-set.png"/><br><img src="https://raw.githubusercontent.com/arcticicestudio/nord-xcode/develop/assets/scrot-asset-catalog-color-set-selected.png"/><br><img src="https://raw.githubusercontent.com/arcticicestudio/nord-xcode/develop/assets/scrcast-assets-catalog-color-set.gif"/></p>

## Development
[![](https://img.shields.io/badge/Changelog-0.1.0-81A1C1.svg?style=flat-square)](https://github.com/arcticicestudio/nord-xcode/blob/v0.1.0/CHANGELOG.md) [![](https://img.shields.io/badge/Workflow-gitflow--branching--model-81A1C1.svg?style=flat-square)](http://nvie.com/posts/a-successful-git-branching-model) [![](https://img.shields.io/badge/Versioning-ArcVer_0.8.0-81A1C1.svg?style=flat-square)](https://github.com/arcticicestudio/arcver)

### Contribution
Please report issues/bugs, feature requests and suggestions for improvements to the [issue tracker](https://github.com/arcticicestudio/nord-xcode/issues).

<p align="center"><img src="https://cdn.rawgit.com/arcticicestudio/nord/develop/src/assets/banner-footer-mountains.svg" /></p>

<p align="center">Copyright &copy; 2017-present Arctic Ice Studio</p>

<p align="center"><a href="https://github.com/arcticicestudio/nord-xcode/blob/develop/LICENSE.md"><img src="https://img.shields.io/badge/License-MIT-5E81AC.svg?style=flat-square"/></a> <a href="https://creativecommons.org/licenses/by-sa/4.0"><img src="https://img.shields.io/badge/License-CC_BY--SA_4.0-5E81AC.svg?style=flat-square"/></a></p>

[asset-catalog]: https://developer.apple.com/library/content/documentation/Xcode/Reference/xcode_ref-Asset_Catalog_Format
[asset-catalog-creation]: http://help.apple.com/xcode/mac/current/#/dev10510b1f7
[interface-builder]: https://developer.apple.com/xcode/interface-builder
[add-folder-to-project]: http://help.apple.com/xcode/mac/current/#/dev81ce1d383
[nord-xcassets]: https://github.com/arcticicestudio/nord-xcode/tree/develop/src/nord.xcassets
