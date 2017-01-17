# Sfortzando - Advanced ABC Notation plugin

This is both a complete rewrite of the syntax definition found at [jimhawkridge/SublimeABC](https://github.com/jimhawkridge/SublimeABC), and a plugin for extended support of ABC Notation. It is used to provide syntax highlighting for ABC Notation, along with a build systems, completions, snippets, commands, etc.

Within the syntax definition, the scopes will highlight all ABC code conforming up to ABC Standard 2.2, and will also highlight embedded PostScript, JavaScript, HTML, SVG (highlighted as XML), and embedded Markdown. Embedded Markdown support is a feature unique to this plugin, and is **not** part of [abcm2ps](http://moinejf.free.fr/). As new features get introduced to the language, the syntax highlighter will be modified to match the new additions, as needed.

> **Important:** Embedded Markdown support requires at least 1 blank line _before the `%%endmd` directive or `I:endmd` instruction._ Markdown highlighting within ABC Notation files is not able to distinguish where the Markdown scope ends, otherwise, and will not highlight correctly if this isn't followed.

The original source code to the base ABC Notation syntax definition made for Sublime Text can be found at [jimhawkridge/SublimeABC](https://github.com/jimhawkridge/SublimeABC).
