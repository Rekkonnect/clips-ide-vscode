# CLIPS IDE

The **CLIPS IDE** extension provides an IDE-like experience for the [**CLIPS**](http://www.clipsrules.net/) programming language inside Visual Studio Code.

![Screenshot](media/vscode-clips-ide.png)

## Features

![Open Animation](media/clips-open-env.gif)

### Terminal

Improved terminal experience over the _CLIPS REPL_ by including several features:

- Command Editing (moving, removing characters, etc.)
- Command History (`up/down arrow keys`)
- Clear Line (`Ctrl+U`) and Clear Screen (`Ctrl+L`)

![Terminal Animation](media/clips-terminal.gif)

### Views

- Facts
- Agenda
- Instances

These views update their state automatically after each command.

![Views Animation](media/clips-views.gif)

## Extension Settings

This extension contributes the following settings:

- `clips.defaultEnvironmentViews`: Selection of which views should be opened whenever the `Open CLIPS Environment` command is used (the `facts` and `agenda` views are enabled by default).
- `clips.logLevel`: Sets the log level for the extension (`off` by default). Only useful for _testing/debugging_ purposes.

![Settings Animation](media/clips-settings.gif)

## Release Notes

### 1.0.0

Initial release of CLIPS IDE.
