# ViMouse
Control mouse cursor using keyboard like the Vim keybind ;)

This fork implements a slightly different keybinding compared to the [original version](https://github.com/genki/ViMouse).

## Key mapping in Normal mode
* `h`, `j`, `k`, `l`: acts as you know in normal mode.
* `i`: switch to Input mode
* `<space>`: Left click
* `n`: Middle click
* `;`: Right click
* `a`, `<opt>`: Very slow cursor speed
* `s`: Slow cursor speed
* `d`: Fast cursor speed
* `f`, `<shift>`: Very fast cursor speed
* `g`: Acts as mouse wheel. Use combined with `h`,`j`,`k`,`l` and `a`, `s`, `d`, `f`.
* `y`: Yank
* `p`: Paste
* `u`: Undo
* `r`: ⌘R, typically reload.

## Key mapping in Input mode
* `^;`, `<fn>;`, `<ESC>`: switch to Normal mode;
