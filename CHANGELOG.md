<p align="center"><a href="https://www.nordtheme.com/ports/xcode" target="_blank"><img src="https://raw.githubusercontent.com/arcticicestudio/nord-docs/develop/assets/images/ports/xcode/repository-hero.svg?sanitize=true"/></a></p>

<p align="center"><a href="https://github.com/arcticicestudio/nord-xcode/releases/latest"><img src="https://img.shields.io/github/release/arcticicestudio/nord-xcode.svg?style=flat-square&label=Release&logo=github&logoColor=eceff4&colorA=4c566a&colorB=88c0d0"/></a> <a href="https://www.nordtheme.com/docs/ports/xcode"><img src="https://img.shields.io/github/release/arcticicestudio/nord-xcode.svg?style=flat-square&label=Docs&colorA=4c566a&colorB=88c0d0&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxNiIgaGVpZ2h0PSIxNiI%2BCiAgICA8cGF0aCBmaWxsPSIjZDhkZWU5IiBkPSJNMTMuNzQ2IDIuODEzYS42Ny42NyAwIDAgMC0uNTU5LS4xMzNMOCAzLjg0OGwtNS4xODgtMS4xOGEuNjY5LjY2OSAwIDAgMC0uNTcuMTMzLjY3Ny42NzcgMCAwIDAtLjI0Mi41MzF2OC4xMzNjLS4wMDguMzIuMjEuNTk4LjUyLjY2OGw1LjMzMiAxLjE5OWguMjk2bDUuMzMyLTEuMmEuNjY4LjY2OCAwIDAgMCAuNTItLjY2N1YzLjMzMmEuNjU5LjY1OSAwIDAgMC0uMjU0LS41MnpNMy4zMzIgNC4xNjhsNCAuODk4djYuNzY2bC00LS44OTh6bTkuMzM2IDYuNzY2bC00IC44OThWNS4wNjZsNC0uODk4em0wIDAiLz4KPC9zdmc%2BCg%3D%3D"/></a></p>

<p align="center">Changelog for <a href="https://www.nordtheme.com/ports/xcode" target="_blank">Nord Xcode</a> — An arctic, north-bluish clean and elegant <a href="https://developer.apple.com/xcode" target="_blank">Xcode</a> theme.</p>

<!--lint disable no-duplicate-headings-->

# 0.2.0

![Release Date: 2019-12-19](https://img.shields.io/static/v1.svg?style=flat-square&label=Release%20Date&message=2019-12-19&colorA=4c566a&colorB=88c0d0) [![Project Board](https://img.shields.io/static/v1.svg?style=flat-square&label=Project%20Board&message=0.2.0&logo=github&logoColor=eceff4&colorA=4c566a&colorB=88c0d0)](https://github.com/arcticicestudio/nord-xcode/projects/3) [![Milestone](https://img.shields.io/static/v1.svg?style=flat-square&label=Milestone&message=0.2.0&logo=github&logoColor=eceff4&colorA=4c566a&colorB=88c0d0)](https://github.com/arcticicestudio/nord-xcode/milestone/2)

## Features

**Nord Docs Transition** — #9 ⇄ #10 (⊶ 278fa4b5)
↠ Transferred all documentations, assets and from „Nord Xcode“ to [Nord Docs][nord].
Please see the [corresponding issue in the Nord Docs repository][gh-nord-docs#182] to get an overview of what has changed for Nord Xcode and what has been done to migrate to Nord Docs.

<p align="center">Landing Page</p>
<p align="center"><a href="https://www.nordtheme.com/ports/xcode" target="_blank"><img src="https://user-images.githubusercontent.com/7836623/71106477-bc4f3880-21bf-11ea-987b-bd5183c1aa4b.png" alt="Preview: Nord Xcode Port Project Landing Page"/></a></p>

<p align="center">Docs Page</p>
<p align="center"><a href="https://www.nordtheme.com/docs/ports/xcode" target="_blank"><img src="https://user-images.githubusercontent.com/7836623/71106475-bc4f3880-21bf-11ea-9a9f-4c0a0472a604.png" alt="Preview: Nord Xcode Docs Page"/></a></p>

<p align="center">Installation & Activation Guide</p>
<p align="center"><a href="https://www.nordtheme.com/docs/ports/xcode/installation" target="_blank"><img src="https://user-images.githubusercontent.com/7836623/71106476-bc4f3880-21bf-11ea-8812-079bb6425777.png" alt="Preview: Nord Xcode Installation & Activation Guide Page"/></a></p>

<p align="center">Asset Catalog Guide</p>
<p align="center"><a href="https://www.nordtheme.com/docs/ports/xcode/asset_catalog" target="_blank"><img src="https://user-images.githubusercontent.com/7836623/71106473-bc4f3880-21bf-11ea-9cec-d182d526a068.png" alt="Preview: Nord Xcode Asset Catalog Guide Page"/></a></p>

**Xcode 9 Asset Catalog Color Set** — #2 ⇄ #3 (⊶ 4f3bd242) by [@ornithocoder][gh-user-ornithocoder]
↠ Added a color set for the [asset catalog][apple-dev-asset_catalog] that were introduced in Xcode 9. It can be used in the [Interface Builder][apple-dev-interface_builder] and programmatically via `UIColor(named:)`.
See [Nord's official documentation to learn how to use the color set][nord-docs-ports-xcode-asset_catalog].

<p align="center">Asset Catalog Color Set</p>
<p align="center"><a href="https://www.nordtheme.com/docs/ports/xcode/asset_catalog" target="_blank"><img src="https://raw.githubusercontent.com/arcticicestudio/nord-docs/develop/assets/images/ports/xcode/ui-asset_catalog.png" alt="Preview: Nord Xcode Asset Catalog Color Set"/></a></p>

<p align="center">Xcode Interface Builder with Nord</p>
<p align="center"><a href="https://www.nordtheme.com/docs/ports/xcode/asset_catalog" target="_blank"><img src="https://raw.githubusercontent.com/arcticicestudio/nord-docs/develop/assets/images/ports/xcode/ui-interface_builder.png" alt="Preview: Nord Xcode Interface Builder with Nord"/></a></p>

## Improvements

### Syntax

**Comment Color Brightness** — #6 ⇄ #7 (⊶ 29bfdcd0)
↠ Implemented the frequently requested and long-time outstanding increase of the comment color (`nord3`) brightness by 10% from a lightness level of ~35% to ~45%.

➜ **Please see [arcticicestudio/nord#94][gh-nord#94] for all details about this design change decision**!

<p align="center"><strong>Before</strong></p>
<p align="center"><img src="https://user-images.githubusercontent.com/7836623/57509506-b37eb600-7304-11e9-8384-6b294603854f.png" alt="Nord Xcode syntax before increased comment color brightness change"/></p>

<p align="center"><strong>After</strong></p>
<p align="center"><img src="https://user-images.githubusercontent.com/7836623/57509505-b37eb600-7304-11e9-90c4-97be51645bff.png" alt="Nord Xcode syntax after increased comment color brightness change"/></p>

## Tasks

### Documentation

**MIT License Migration** — #4 ⇄ #5 (⊶ fb58b5d3)
↠ Migrated to the MIT license to adapt to the migration of the main [Nord][gh-nord] project. Detailed information can be found in the [main task ticket][gh-nord#55].

# 0.1.0

_2017-04-23_

## Features

Detailed information and install instructions can be found in the [README](https://github.com/arcticicestudio/nord-xcode/blob/develop/README.md#installation) and in the [project wiki](https://github.com/arcticicestudio/nord-xcode/wiki).

❯ Implemented the main color theme file [`Nord.xccolortheme`](https://github.com/arcticicestudio/nord-xcode/blob/develop/src/Nord.xccolortheme). (@arcticicestudio, #1, 8a9a2ac3)

<p align="center"><img src="https://raw.githubusercontent.com/arcticicestudio/nord-xcode/develop/src/assets/scrot-preview.png"/></p>

<p align="center"><img src="https://raw.githubusercontent.com/arcticicestudio/nord-xcode/develop/src/assets/scrot-docs-preferences-editor.png"/><br><img src="https://raw.githubusercontent.com/arcticicestudio/nord-xcode/develop/src/assets/scrot-docs-preferences-console.png"/></p>

# 0.0.0

_2017-04-23_
❯ **Project Initialization**

---

<!--
+------------------+
+ Symbol Reference +
+------------------+
↠ (U+21A0): Start of a log section description
— (U+2014): Separator between a log section title and the metadata
⇄ (U+21C4): Separator between a issue ID and pull request ID in a log metadata
⊶ (U+22B6): Icon prefix for the short commit SHA checksum in a log metadata
-->

<!--lint disable final-definition-->

<!-- Base Links -->

[apple-dev-asset_catalog]: https://developer.apple.com/library/archive/documentation/Xcode/Reference/xcode_ref-Asset_Catalog_Format
[apple-dev-interface_builder]: https://developer.apple.com/xcode/interface-builder
[gh-nord]: https://github.com/arcticicestudio/nord
[nord-docs-ports-xcode-asset_catalog]: https://www.nordtheme.com/docs/ports/xcode/asset_catalog
[nord]: https://www.nordtheme.com

<!-- v0.22.0 -->

[gh-nord-docs#182]: https://github.com/arcticicestudio/nord-docs/issues/182
[gh-nord#55]: https://github.com/arcticicestudio/nord/issues/55
[gh-nord#94]: https://github.com/arcticicestudio/nord/issues/94
[gh-user-ornithocoder]: https://github.com/ornithocoder
