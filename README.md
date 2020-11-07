# vscode-gemtext README

VSCode extention for text/gemini files.

## Why?

Why not?

## Known issues

* Links don't actually have the "Ctrl/Cmd+LeftClick jump" thing (yet). Would be a nice touch if added.
+ You actually can't have the real "get the `ABC` part of <code>``` ABC</code> and syntax color the stuff accordingly" with only tmLanguage files. [Markdown tmLanguage in VSCode](https://github.com/microsoft/vscode/blob/master/extensions/markdown-basics/syntaxes/markdown.tmLanguage.json) does not do that, they just match a bunch of matches on the `ABC` part so it only supports languages they've written in the tmLanguage file.

## License

BSD-3-Clause
