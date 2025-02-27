SublimeLinter-contrib-yaml-lint
================================

This linter plugin for [SublimeLinter](https://sublimelinter.readthedocs.org/) provides an interface to the [yaml-lint](https://github.com/Pryz/yaml-lint) gem. It will be used with files that have the “YAML” syntax.

## Installation
SublimeLinter 3 must be installed in order to use this plugin. If SublimeLinter 3 is not installed, please follow the instructions [here](https://sublimelinter.readthedocs.org/en/latest/installation.html).

### Linter installation
Before using this plugin, you must ensure that `yaml-lint >= 0.0.9` is installed on your system. To install `yaml-lint`, do the following:

1. Install [Ruby](https://ruby-lang.org).

1. Install `yaml-lint` by typing the following in a terminal:
   ```
   [sudo] gem install yaml-lint
   ```

### Linter configuration
In order for `yaml-lint` to be executed by SublimeLinter, you must ensure that its path is available to SublimeLinter.
Once you have installed `yaml-lint`, you can proceed to install the SublimeLinter-contrib-yaml-lint plugin if it is not yet installed.

### Plugin installation
Please use [Package Control](https://sublime.wbond.net/installation) to install the linter plugin. This will ensure that the plugin will be updated when new versions are available. If you want to install from source so you can modify the source code, you probably know what you are doing so we won’t cover that here.

To install via Package Control, do the following:

1. Within Sublime Text, bring up the [Command Palette](https://docs.sublimetext.info/en/sublime-text-3/extensibility/command_palette.html) and type `install`. Among the commands you should see `Package Control: Install Package`. If that command is not highlighted, use the keyboard or mouse to select it. There will be a pause of a few seconds while Package Control fetches the list of available plugins.

1. When the plugin list appears, type `yaml-lint`. Among the entries you should see `SublimeLinter-contrib-yaml-lint`. If that entry is not highlighted, use the keyboard or mouse to select it.

## Settings
For general information on how SublimeLinter works with settings, please see [Settings](https://sublimelinter.readthedocs.org/en/latest/settings.html). For information on generic linter settings, please see [Linter Settings](https://sublimelinter.readthedocs.org/en/latest/linter_settings.html).

## Contributing
If you would like to contribute enhancements or fixes, please do the following:

1. Fork the plugin repository.
1. Hack on a separate topic branch created from the latest `master`.
1. Commit and push the topic branch.
1. Make a pull request.
1. Be patient ;-)

Please note that modications should follow these coding guidelines:

- Indent is tab.
- Code should pass flake8 and pep257 linters.
- Vertical whitespace helps readability, don’t be afraid to use it.
- Please use descriptive variable names, no abbrevations unless they are very well known.

Thank you for helping out!
