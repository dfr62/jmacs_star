# JmacsStar, an hybrid version of joe

Here is my configuration file of the [joe][] text editor in
its `jmacs` version.

I have the most common emacs keybindings in the memory of my
fingers and I'm too lazy to learn a complete new set of
keystrokes of other editors but I like also the old
[wordstar][] key bindings and its kind of _block_ treatment. So
I changed the default `jmacs` file to emulate some _jstar_
behavior (the default joe emulation of wordstar) and added 10
*clips* (sort of registers, for write/add/insert chunks of
text, that use files in `/tmp` directory).

I also added a new help window for these new keybindigs (it's
the fourth).

With this new `*rc` file the program becomes a sort of an hybrid
text editor so I renamed it **JmacsStar** or, simply, **JS**.

The configuration file is called `jsrc` and I added a symbolic
link from `$HOME/bin/js` to `/usr/bin/joe` to call it directly.

You can see all the new keybindings and macros in the file
[js_star_cmds][].

If you like to test it insert the [js_star_cmds][] file at the
end of your `main` section of keybindings

The `jsrc` file contains also other little additions or
changes that pertains the emacs part of the configuration file.

I'm using `joe` 4.1 on [Xubuntu][] 16.04 and testing my
configuration here.

I use `js` in terminal to write prose, technical or not, using
[markdown][].

[GNU emacs][] is very good but, IMHO, it's too much for writing
simple, not too long texts, with a simple markup language.

[joe]: http://joe-editor.sourceforge.net
[wordstar]: https://en.wikipedia.org/wiki/WordStar
[js_star_cmds]: ./js_star_cmds
[markdown]: https://en.wikipedia.org/wiki/Markdown
[GNU emacs]: https://www.gnu.org/s/emacs
[Xubuntu]: http://xubuntu.org
