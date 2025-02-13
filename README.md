# Tinybird support for Visual Studio Code

![Screenshot](https://github.com/tinybirdco/vscode-tinybird-support/raw/main/images/banner.png)

This extension provides some helpers for your [Tinybird](https://tinybird.co) data projects:

## Syntax highlighting

Adds syntax highlight for `.datasource`, `.pipe` and `.incl` files.

![Syntax highlighting screenshot](https://github.com/tinybirdco/vscode-tinybird-support/raw/main/images/screenshot.jpg)

## Commands

### tinybird.sql

Execute arbitrary SQL in yout Tinybird workspace by selecting it in the editor and pressing the default `f5` keybinding (alternatively, you can call the command from the command bar).

You'll see the results in the `Tinybird SQL` output panel.

![tinybird.sql screenshot](https://github.com/tinybirdco/vscode-tinybird-support/raw/main/images/tinybird.sql.jpg)

> Note: you need to have your `tb` command properly configured for this command to work. Please, [refer to our docs](https://www.tinybird.co/docs/quick-start-cli.html) for a quick start.

#### Configure the extension

For the Tinybird commands to work, you need to setup the following settings:
- `tinybird.dataProjectSubdir`: Where your data project is located in the active workspace.
- `tinybird.venv`: If you use a Python virtual env to work with Tinybird, put the venv name here.
- `tinybird.venvActivate`: The activation command for your virtual env (see setting `tinybird.venv`). Default is `bin/activate` but for some shells you might need another one (for example `bin/activate.fish` for the [fish shell](https://fishshell.com/)).


