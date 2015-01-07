### there is 3 modes for configuring graphic card
1. the old static method -> /etc/X11/xorg.conf -> sax2
2. the one for transition
3. the automated one

#### support method metrics
method|configF|GUItool
------|-------|-------
static|xorg.conf|sax2
middle|xorg.conf.d|sax3
auto|non-conf?|xrandr?


#### notes and pending:
1. precedence order: xorg.conf -> xorg.conf.d -> auto config
2. Xorg -configure: this command could be used in all version to create the xorg.conf. (to check if support) for the most oldest one?
3. xrandr: just support for the automatic arch or could used in every method? (sax2 and sax3 are GUI tool and the xrandr is the CLI)


#### reference info:
[bug608237](https://bugzilla.novell.com/show_bug.cgi?id=608237)
[wiki](https://en.opensuse.org/SDB:Configuring_graphics_cards)
[trySteps](https://en.opensuse.org/SDB:Configuring_graphics_cards)
