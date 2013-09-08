electric_boogaloo.vim
=====================

![breakin_two_electric_boogaloo](http://img181.imageshack.us/img181/92/breakin2gl6.jpg)

electric_boogaloo is designed to make [breakin'][1] long lines faster in vim.

Plugin is a direct copy of [this script][2] from the Vim wiki.

Installation
------------

Using Vundle:

    $ echo "Bundle 'adarsh/electric_boogaloo.vim'" >> ~/.vimrc
    $ vim +BundleInstall

Usage
-----

Insert newline after each '(' and ')' in current line.

    :Breakin ( )

Same, in lines 10 to 20 inclusive.

    :10,20Breakin ( )

Same, whole buffer.

    :%Breakin ( )

Insert newline before each '(' and ')' in current line.

    :Breakin! ( )

Insert newline after each occurrence of last-used search pattern.

    :%Breakin

Insert newline before each occurrence of last-used search pattern.

    :%Breakin!


License
-------

Copyright (c) Adarsh Pandit.  Distributed under the same terms as Vim itself.
See `:help license`.

[1]: http://www.imdb.com/title/tt0086999/
[2]: http://vim.wikia.com/wiki/Add_a_newline_after_given_patterns
