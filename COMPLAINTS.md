Complaints
==========
>Note: These should be taken with a bag of salt. Most users won't care about
>most of these (probably?). I just needed a place to write them down.

General Linux / BSD
-------------------
- Not specific to any distro, but AirPlay to an Airport Express is not a thing
  that can be done. I know this is unhelpful and maybe even rude to complain
  about, but I also haven't seen any OS standards popup for this sort of audio
  streaming. I wouldn't mind setting up a Raspberry Pi or other silly little
  mini computer to stream audio / media to if there were a decent alternative,
  but I just haven't found one

- Terminal emulators are either all ugly or have stupid keyboard shortcuts or
  both

- Email clients suck. Thunderbird is ugly and looks enterprisey, but I'm not
  necessarily willing to convert to mutt full time. Geary looks good but has a
  completely different set of keyboard shortcuts than Gmail. Which is stupid
  for an email client designed for Gmail users

- Chromium is far less powerful than the Mac OS X version of Chrome. No `C-M-[`
  to switch tabs to the left? What am I, 12?

- Dual monitors don't work out of the box. This is 2014 and the terminal doesn't
  even register if I hotplug another monitor in. I have to **restart the entire
  PC** to get it to realize it has two potential displays

- The default console resolution (out of the box, no tweaking) is like 83 x 20

Debian
------
- Comes with Apache installed by default? wat

- Have to remove libperl and libperl-dev because otherwise they interfere with
  compiling vim using my own version of perl from plenv. I don't even
  necessarily think this is Debian's fault but I do think it's stupid that
  I have to have a line in my config file that says "make sure these packages
  are ABSENT"

Ubuntu
------
- Your SSH DAEMON (`sshd` on every other sane OS) is called `ssh`. So now I have
  to add in a custom variable for your little snowflake of a system to decide
  whether the SSH DAEMON is called `sshd` or `ssh` based on whether the system
  self-reports as `Ubuntu` or not

RedHat
------
- Your fucking vim installation is broken by default. `sudo yum install
  big-vim-or-whatever` doesn't work out of the box because it conflicts with the
  builtin vim

- Your perl modules get installed in the weirdest fucking places. I have an
  entire task dedicated to creating a symlink for `xsubpp` because you chose to
  ignore convention and install it in some arbitrary fucking location

GNOME
-----
- The "Emacs" key binding mode for GTK (Gnome?) text fields is stupid. C-a
  becomes go to the beginning of the line but there's no alternative for
  "select all". Mac OS X shortcuts really really shine in comparison

- Related to the above there's no easily obvious way of customizing those same
  keyboard shortcuts

- Gnome notifications (are they actually Gnome's?) stay for 5 seconds and are
  not actionable (including early dismissal)

- Notifications don't have any sort of notification center, or even any sort of
  "these are the last 5 notifications you've received"

- Pidgin also doesn't have any (obvious? googleable?) way of changing some
  keyboard shortcuts (like next / prev tab)

- Empathy is hideous and underpowered compared to Pidgin. Why is it the
  default?

- Why do I need a "tweaks" tool in the first place? Why can't you just let me
  tweak these things without having to install another binary?

Elementary OS
-------------
- Elementary OS doesn't have a (obvious?) way of stopping `M-l` from locking
  the screen

- ElementaryOS (Gnome?) doesn't have a "toggle pause / play" shortcut, only a
  "pause" and a "play" one. I want to use the same shortcut for both and I
  shouldn't have to connect up a script for it

- ElementaryOS has no way of reorganizing spaces

- ElementaryOS's window manager (Pantheon?) seems designed for mouse use only

- ElementaryOS has no more precise adjectives for window size than
  "fullscreen", "half on the left", and "half on the right"

- Shotwell is weak and underpowered

- Application launcher in eOS doesn't get dismissed after pressing escape

- Terminal in eOS (based on Gnome Terminal?) is not configurable (maybe without
  installing eOS tweaks?) and has a transparent and dark background because
  it's "pretty"

- Installing Steam in eOS failed randomly and for random reasons (something to
  do with Ubuntu One?)

- There's a huge amount of empty space in my eOS taskbar but no options to add
  stuff like RAM / CPU usage

- Same as above but w/ desktop. Doesn't seem to be a way to add desktop icons
  and Conky isn't built in so why even have a desktop?

- The "no menubar" idea in eOS is cute but some apps (pidgin) are really not
  designed for it. Stuff like pulling up the buddy list is painful

- Spaces in general seem weirdly done in eOS. For example if I'm using
  urxvtzeuzrt and I create some form of urgent bell by mistyping a command or
  trying to autocomplete when there's nothing to complete, a little red light
  will appear under the dock icon. When I click on that icon it will take me to
  (if I have one running) another instance of urxvtzeuzrt (e.g. cycling through
  open windows) instead of to the window that caused the stupid little red
  light to appear in the first place

- Opening a link in Gnome terminal (clicking on it?) doesn't switch me to the
  new browser window, it just puts one of those annoying red lights under it in
  the dock
