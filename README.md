# VS Code Epic Effects

Minimal, CSS based code effects for VS Code, based on the [CSS of SynthWave '84 VS Code theme](https://github.com/robb0wen/synthwave-vscode/blob/master/synthwave84.css).

## Preview

![Preview](/.github/Preview.png)

Note: The VS Code theme used in the image is [GitHub Theme](https://marketplace.visualstudio.com/items?itemName=GitHub.github-vscode-theme) (Dark).

## Installation

1) Install the VS Code extensions: [Custom CSS and JS Loader](https://marketplace.visualstudio.com/items?itemName=be5invis.vscode-custom-css) & [Fix VSCode Checksums](https://marketplace.visualstudio.com/items?itemName=lehni.vscode-fix-checksums).

2) Add this into your VS Code [user settings.json](https://code.visualstudio.com/docs/getstarted/settings#_settingsjson):

    ```json
    {
      "vscode_custom_css.imports": [
        "file:///X:/Path/to/ccelik97.vscode-epic-effects/vscode-epic-effects.css"
      ],
    }
    ```

3) Run the commands: __Reload Custom CSS & JS__ and then __Fix Checksums: Apply__.
