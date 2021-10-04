# vscode ijkl move

Now I only use these
~~~
{
        "key": "alt+k",
        "command": "cursorDown",
        "when": "editorTextFocus"
    },
    {
        "key": "alt+i",
        "command": "cursorUp",
        "when": "editorTextFocus"
    },
    {
        "key": "alt+l",
        "command": "cursorRight",
        "when": "editorTextFocus"
    },
    {
        "key": "alt+j",
        "command": "cursorLeft",
        "when": "editorTextFocus"
    },
~~~

But also

~~~
    // vscode-keybindings for navigation with I/J/K/L and additional functionality with surrounding characters 
    // Place your key bindings in this file to overwrite the defaults
    // ALT + I/J/K/L: up/left/down/right
    // ALT + SHIFT + I/J/K/L: mark text up/left/down/right
    // CTRL + J/L: send cursor to start/end of line
    // CTRL + ALT + J/L: send cursor to start/end of word
    // CTRL + ALT + Y: got to declaration
    // CTRL + I/K: add/remove another cursor up/down
    // -- IF LINEJUMPER IS INSTALLED -- //
    // CTRL + ALT + I/K: move cursor 10 lines up/down
    // CTRL + ALT + SHIFT + I/K: mark 10 lines up/down
    {
        "key": "ctrl+shift+i",
        "command": "editor.action.moveLinesUpAction",
        "when": "editorTextFocus"
    },
    {
        "key": "ctrl+shift+k",
        "command": "editor.action.moveLinesDownAction",
        "when": "editorTextFocus"
    },
    {
        "key": "alt+k",
        "command": "cursorDown",
        "when": "editorTextFocus"
    },
    {
        "key": "alt+i",
        "command": "cursorUp",
        "when": "editorTextFocus"
    },
    {
        "key": "alt+l",
        "command": "cursorRight",
        "when": "editorTextFocus"
    },
    {
        "key": "alt+j",
        "command": "cursorLeft",
        "when": "editorTextFocus"
    },
    {
        "key": "alt+shift+k",
        "command": "cursorDownSelect",
        "when": "editorTextFocus"
    },
    {
        "key": "alt+shift+i",
        "command": "cursorUpSelect",
        "when": "editorTextFocus"
    },
    {
        "key": "alt+shift+l",
        "command": "cursorRightSelect",
        "when": "editorTextFocus"
    },
    {
        "key": "alt+shift+j",
        "command": "cursorLeftSelect",
        "when": "editorTextFocus"
    },
    {
        "key": "alt+ctrl+l",
        "command": "cursorWordEndRight",
        "when": "editorTextFocus"
    },
    {
        "key": "alt+ctrl+j",
        "command": "cursorWordStartLeft",
        "when": "editorTextFocus"
    },
    {
        "key": "alt+shift+ctrl+l",
        "command": "cursorWordRightSelect",
        "when": "editorTextFocus"
    },
    {
        "key": "alt+shift+ctrl+j",
        "command": "cursorWordLeftSelect",
        "when": "editorTextFocus"
    },
    {
        "key": "ctrl+l",
        "command": "cursorEnd",
        "when": "editorTextFocus"
    },
    {
        "key": "ctrl+j",
        "command": "cursorHome",
        "when": "editorTextFocus"
    },
    {
        "key": "ctrl+alt+y",
        "command": "editor.action.goToDeclaration"
    },
    {
        "key": "ctrl+i",
        "command": "cursorColumnSelectUp",
        "when": "editorTextFocus"
    },
    {
        "key": "ctrl+k",
        "command": "cursorColumnSelectDown",
        "when": "editorTextFocus"
    }
~~~

I forgot where I found these,
Sorry for that :(
