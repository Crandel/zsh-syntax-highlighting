zsh-syntax-highlighting / highlighters / root
---------------------------------------------

This is the `root` highlighter, that highlights the whole line if the current
user is root.


### How to tweak it

This highlighter defines the following styles:

* `root` - the style for the whole line if the current user is root.

To override one of those styles, change its entry in `ZSH_HIGHLIGHT_STYLES`,
for example in `~/.zshrc`:

    ZSH_HIGHLIGHT_STYLES[root]='bg=red'

The syntax for declaring styles is documented in [the `zshzle(1)` manual
page](http://zsh.sourceforge.net/Doc/Release/Zsh-Line-Editor.html#SEC135).