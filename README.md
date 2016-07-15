Mac Keyboard Layouts
--------------------

These are some of the keyboard layouts I use when using Mac computers.

This is normally checked out in to `/Users/cjs/Library/Keyboard Layouts`.
To make the keyboard layouts available, bring up the Keyboard preferences,
select the 'Input Sources' tab, click the '+' button at the bottom left,
select the 'Others' category, and at the right you should see a list of
keyboard layouts that includes these ones. Select one and click the 'Add'
button.

The following tools can be helpful when working on keyboard layouts:
* [Key Codes](https://manytricks.com/keycodes/) for looking up key codes
* [Ukelele](http://scripts.sil.org/ukelele) layout editor

Other useful keyboard-related tools include:
* [USB Overdrive](http://www.usboverdrive.com/USBOverdrive/News.html)
  for using middle-mouse-button scrolling on a ThinkPad keyboard.

### iTerm2 Notes

[iTerm2](http://iterm2.com/) will sometimes ignore key mappings set up
as per above, for example with the yen key (to the left of backspace)
configured to send backtick/yen (umodified/shifted). Going to the iTerm2
preferences will allow you to set up any failing mappings to send the
right thing by adding a key mapping that sends itself (i.e., just press
the key again) when entered in to the text field for the "Send text"
action.

You will also probably want to, as with the Terminal app, set iTerm2
(known as "iTerm" in the apps list) to use Command-X/C/V for cut/copy
paste rather than a global Ctrl-X/C/V, if you have that configured.
