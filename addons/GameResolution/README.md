![Image](https://img.itch.zone/aW1hZ2UvMTM3ODU2OC84MDI4MDExLnBuZw==/original/ZQ1nVq.png)

# Godot Plugin Project Resolution (for Godot 4.x)

Godot plugin to quickly change and test Game Window Resolution settings.

Useful to test and prevent your UI from being inconsistent in different resolutions.

Custom version from Tungill which:
	- Added Steam Deck & Nintendo Switch resolutions
	- Added the option to show/hide larger resolution
	- Updated buttons and separators names

## Download

- clone github repository at https://github.com/Tungill/Godot-4-Plugin-Project-Resolution

Original code from:
- Godot Asset Library at https://godotengine.org/asset-library/asset/9270
- or github repository at https://github.com/Danim3D/Godot-4-Plugin-Project-Resolution



## Installation

- Copy the contents of the "addons" directory to the "addons" directory of your Godot Project
- Go in "Project -> Project Settings -> Plugins (tab)" and enable "ProjectResolution"


## Usage

Once the plugin is activated, a new button will show up on the Top-Right corner of the Godot Editor, above the Inspector tab.
On use, the name of the button "Project Resolution" will be renamed by the selected resolution.

- "Fullscreen" will toggle the Fullscreen setting from the Projects Settings.
- "Play Auto on Change" will play your main project scene when you tick a box to change the resolution.
- "Play Auto Current Scene" will use the current opened scene instead of the main project settings scene when using "Play Auto on Change".
- "Hide Larger Resolution" hide/show resolutions which are larger than your desktop resolution.
- "Native" will use the current resolution of your desktop.
- "0x0" will use the project's viewport resolution as the game's window resolution.
- "Landscape" will switch mobile resolutions using Landscape instead of Portrait.
