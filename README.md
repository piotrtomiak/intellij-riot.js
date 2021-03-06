# WebStorm Riot.js plugin

The plugin can be installed in WebStorm, IntelliJ IDEA Ultimate, PhpStorm, PyCharm Pro, GoLand and RubyMine v2019.1 and above.

## Installation

To install the plugin open the IDE Preferences | Plugins, then click Browse repositories... and search for Riot.js.

[Plugin repository link](https://plugins.jetbrains.com/plugin/12748-riot-js) 

## Features

* Support for ".riot" and ".tag" extension
* Parsing expressions inside xml-tags
* Navigation based on component names
* TypeScript
* SASS and SCSS

![Example](example.png)


## Known issues

* Riot 1,2,3 optional script tags [are not supported](https://github.com/anstarovoyt/intellij-riot.js/issues/8)
* Expression parsing uses pure stategy and [doesn't allow nested braces "{" and "}"](https://github.com/anstarovoyt/intellij-riot.js/issues/4)

