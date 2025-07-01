# QuantumBox

QuantumBox is an online tool for sketching and sharing instrumental music.
You can find it [here](https://quantumbox.github.io/index.html).
It is a modification of [JummBox](https://github.com/jummbus/jummbox) and [UltraBox](https://github.com/ultraabox/ultrabox_typescript), which inturn is a modification of the [original BeepBox](https://beepbox.co).

## Code

The code is divided into several folders. This architecture is identical to BeepBox's.

The [synth/](synth) folder has just the code you need to be able to play ToolBox
songs out loud, and you could use this code in your own projects, like a web
game. After compiling the synth code, open website/synth_example.html to see a
demo using it. To rebuild just the synth code, run:

```
npm run build-synth
```

The [editor/](editor) folder has additional code to display the online song
editor interface. After compiling the editor code, open website/index.html to
see the editor interface. To rebuild just the editor code, run:

```
npm run build-editor
```

The [player/](player) folder has a miniature song player interface for embedding
on other sites. To rebuild just the player code, run:

```
npm run build-player
```

The [website/](website) folder contains index.html files to view the interfaces.
The build process outputs JavaScript files into this folder.
