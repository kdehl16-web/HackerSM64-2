# Hacker Super Mario 64 3 Retooled

This repository is a clean slate for basic enhancements built upon the *Super Mario 64* decompilation. It is a spritual successor to the spiritual successor to the spiritual successor of HackerN64's *HackerSM64*.

## Installation

### Windows
There are no tools to install on Windows yet.

### Linux
There are no tools to install on Linux yet.

### macOS
There are no tools to install on macOS ever. I don't like mac users.


## Project Structure

	sm64
	├── actors: object behaviors, geo layout, and display lists
	├── asm: handwritten assembly code, rom header
	│   └── non_matchings: asm for non-matching sections
	├── assets: animation and demo data
	│   ├── anims: animation data
	│   └── demos: demo data
	├── bin: C files for ordering display lists and textures
	├── build: output directory
	├── data: behavior scripts, misc. data
	├── doxygen: documentation infrastructure
	├── enhancements: example source modifications
	├── include: header files
	├── levels: level scripts, geo layout, and display lists
	├── lib: SDK library code
	├── rsp: audio and Fast3D RSP assembly code
	├── sound: sequences, sound samples, and sound banks
	├── src: C source code for game
	│   ├── audio: audio code
	│   ├── buffers: stacks, heaps, and task buffers
	│   ├── engine: script processing engines and utils
	│   ├── game: behaviors and rest of game source
	│   ├── goddard: Mario intro screen
	│   └── menu: title screen and file, act, and debug level selection menus
	├── text: dialog, level names, act names
	├── textures: skybox and generic texture data
	└── tools: build tools

## Contributing

Pull requests are unwelcome. I know what's best.
Official Discord: https://discord.gg/BETAcdefg
