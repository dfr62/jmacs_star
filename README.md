# JmacsStar, an hybrid version of joe

Here is may configuration file of the [joe][] text editor in
its `jmacs` version.

I have the most frequent used emacs keybindings in the memory of my
fingers and I'm too lazy to learn new keystrokes for other
editors but I like also the old [wordstar][] key bindings and
its kind of _block_ treatment. So I changed the default `jmacs`
file to emulate some _jstar_ behavior (the default joe
emulation of wordstar) and added 10 *clips* (sort of registers
for write/add/insert chunks of text that use files in `/tmp` directory).

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

I use `js` in terminal to write prose, technical or not, using
[markdown][]

[joe]: http://joe-editor.sourceforge.net
[wordstar]: https://en.wikipedia.org/wiki/WordStar
[js_star_cmds]: ./js_star_cmds
[markdown]: https://en.wikipedia.org/wiki/Markdown
