### URxvt-dragscroll
---

A URxvt extension designed for use with touchscreens. Dragging while holding mouse1 (left mouse button) is interpreted as scrolling.

Text dragged over in this way is not selected, although currently it is still highlighted as if it were. In the future the selection should simply be preserved, but idk how to do that with a perl extension.

Also, scrolling "inertia" is a planned feature.

---

To install, `clone` this repository and either add `dragscroll` to the key `URxvt.perl-ext-common` in your `.Xresources` file and

`$ sudo ln -s dragscroll /usr/lib/urxvt/perl/dragscroll`

or

`$ urxvt --perl-lib (pwd) -pe dragscroll`
