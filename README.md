# NEVER BE LOST • theme for VS CODE

[Never be Lost](https://github.com/Fred-Vatin/never-be-lost) © 2022 by [Fred Vatin](https://github.com/Fred-Vatin) is licensed under [CC BY-SA 4.0](http://creativecommons.org/licenses/by-sa/4.0/?ref=chooser-v1)

Never be lost in the interface of VS Code. Always know where is the focus and each element while being elegant.

<!-- todo add screenshot -->

<!-- info -->

<!-- problem -->

<!-- *** -->

<!-- ----   -->

## Install

<!-- todo add link -->

1. Go to marketplace or search for `never-be-lost` in the _**extensions**_ section of your VS Code.
2. Click on the `install` button.
3. The theme should preview. Press enter to validate

## Override this theme

To override this (or any other) theme in your personal config file, please follow the guide in the [color theme](https://code.visualstudio.com/api/extension-guides/color-theme) documentation. This is handy for small tweaks to the theme without having to fork and maintain your own theme.

<!-- todo add example -->

## Important settings

`editor.occurrencesHighlight` controls whether the editor should highlight semantic symbol occurrences. If it is too distracting, I advise you to set it to **false**.

> **Note** : there may be a bug in JSON files where when this setting is enabled, `editor.selectionHighlightBackground` color is applied when no selection. Check this [issue](https://github.com/microsoft/vscode/issues/167766) to track if it’s been fixed.

![screenshot](ressources/screenshots/editor.occurrencesHighlight.png)

## VS Codes issues to follow

-   [#167785](https://github.com/microsoft/vscode/issues/167785) Background color of lines overlaps
-   [#167766](https://github.com/microsoft/vscode/issues/167766) `editor.selectionHighlight…` colors are applied while non selected text in JSON
