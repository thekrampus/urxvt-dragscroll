### URxvt-dragscroll
---

A URxvt extension designed for use with touchscreens. Dragging while holding mouse1 (left mouse button) is interpreted as scrolling.

Text dragged over in this way is not selected, although currently it is still highlighted as if it were. In the future the selection should simply be preserved, but idk how to do that with a perl extension.

Also, scrolling "inertia" is a planned feature.

---

To install, `clone` this repository and either

`$ sudo cp dragscroll /usr/lib/urxvt/perl/`

or

`$ urxvt --perl-lib (pwd) -pe dragscroll`