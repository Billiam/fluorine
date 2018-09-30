# Fluorine

This will hopefully be a replay viewer for Halite 3, when Halite 3 exists.

# Installation

If you have npm and [Electron](https://electron.atom.io/) installed globally, you can do:

```
npm install
electron .
```

If you only have npm, and don't want to install Electron globally, I'm told the following works instead:

```
npm install
npm install electron --save-dev --save-exact
./node_modules/.bin/electron .
```

# Other dependencies

* [node-zstandard](https://www.npmjs.com/package/node-zstandard) (gets installed by `npm install`)

# Usage

Open a file from the menu, or via command line with `electron . -o filename.hlt`. Drag-and-dropping a file onto the window may also work. Once a file is opened, navigate with left and right arrow keys.