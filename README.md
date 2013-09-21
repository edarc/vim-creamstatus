Cream statusline for any Vim
============================

This is a standalone version of the [statusline from Cream][1], a mod package
for Vim. I crammed it up here so I can install it with Vundle, but you can use
it too.

  [1]: http://cream.sourceforge.net/statusline.html

How to use it
-------------

After installing it with your mechanism of choice, it should just work.
However, I suggest setting up your own color scheme in `.vimrc`. It uses the
`User1` through `User4` color slots. Here's mine:

    " This sets up some nice colors and formatting for the cream statusline.
    highlight User1  gui=bold guifg=#999999 guibg=#404040
    highlight User2  gui=bold guifg=#ffffff guibg=#404040
    highlight User3  gui=bold guifg=#ffff00 guibg=#404040
    highlight User4  gui=bold guifg=#ff3333 guibg=#404040
