# JT Showcase Pro Updates

Official update server repository for **JT Showcase Pro**.

This repository contains the update metadata and release assets required to deliver Joomla updates for the Pro version of the extension.

## Overview

JT Showcase Pro is distributed through GitHub releases, while Joomla update checks are handled through XML update metadata stored in this repository.

## Included Files

- `updates.xml` — Joomla update server definition
- `changelog.xml` — Version history and release notes
- Release assets — Installable ZIP packages for each published version

## Current Release Line

- Product: **JT Showcase Pro**
- Extension Type: **Joomla Site Module**
- Stable Version: **1.0.0**

## Publishing Process

For every new release:

1. Update the module manifest version
2. Build the final installable ZIP package
3. Create a new GitHub Release
4. Upload the release ZIP asset
5. Update `updates.xml` with the new version and download package details
6. Update `changelog.xml`

## Important

This repository is maintained for the **Pro** package only.

It is intended to provide a clean and consistent update channel for JT Showcase Pro going forward.

## Maintained by

**JoomTheme**
