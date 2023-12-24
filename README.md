# About

The goal of this is to take [lighttigerXIV's ulauncher-bookmarks extension](https://github.com/lighttigerXIV/ulauncher-bookmarks/) and tweak it so it copies the URL to your clipboard by default. I really like the extension, but Gnome won't let me set Tor as default and Mullvad as the same "one instance" limit I haven't been able to work around.

This has only been hard because CopyToClipboardAction doesn't seem to work. I don't have a system right now to check if the `xclip` does, but the `wl-copy` does.

But, as I have been playing with (I have gotten it to work at one point), I've found other things I'd like to tweak:


- [ ] let user decide the name and location of the URL list
- [ ] saves each URL to a new line of the file, for easier editing
- [ ] use browser icons (probably line art cuz I can't draw)
- [ ] change commands to "a", "d", and "o." using default for copy.


That's all for now.   
I don't know python or ulauncher so this'll probably take a bit.
