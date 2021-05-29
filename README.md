# WASD Keyboards—Custom Apple Layout

![Completed keyboard template](https://raw.githubusercontent.com/KarlPiper/apple-wasd-keyboards/master/Preview.png)
![Completed keyboard photo](https://raw.githubusercontent.com/KarlPiper/apple-wasd-keyboards/master/Final%20Product%204.png)

## About
* Template used
  * wasd-ai-104-8.28.2015.ai (104/87-Key US ANSI Layout)
  * Legends for the full-size 104 board are filled in.
* Board pictured
  * WASD V2 87-Key Custom Mechanical Keyboard

## Review & Thoughts
  * 2 year update: Sadly, the UV coating has started to age, there is yellowing on the most used keys, and coating has worn off on certain key edges. My desk is not in front of a window, and my hands are always clean. I probably wouldn't order a full white set again, unless there's a gentle way to restore them. There is no print wear or excessive shine, so that's nice.
  * No kerning issues on keys printed with words. (I used some custom kerning, so, success!)
  * No line-width related issues whatsoever. It's slightly bold compared to my macbook and old apple keyboards, printing in dark grey could offset this, as thinner lines might be risky.
  * The function row is printed in reverse, and looks just as good; possibly even sharper and less bold, but that might be an optical illusion.
  * I suggest using a more open command symbol (⌘) than mine. The counters are slightly muddy.

## Design

### Character Styles
* Normal—sets SF Compact Text Light, inherited by other styles
* Modifiers—keys with full words printed out (except media keys)
* Functions—F keys
* Stacked Keys—keys with two stacked legends (not numbers)
* Stacked Keys (tall)—used on {, }, |
* Denominator—lower character on number keys, larger
* Numerator—upper character on number keys, smaller
* Media keys—media key cluster + numpad “clear” and “enter”

### Alignment
Some legends required optical centering, e.g. J, L, Q, P, F, delete.

### Stylistic Alternates
I chose to use the straight 6, straight 9, and slashed 0.
“*” was switched out for SF Mono Light.
Proper mathematical symbols (×, +, −, /) used on numpad (in 104 key template)

### System Font Symbols
Basic set of keyboard symbols were exported from the following fonts:
* Apple Symbols
* Arial Unicode MS
* .Keyboard
* Lucida Grande
* Lucida Grande Bold
* .Lucida Grande UI
* .Lucida Grande UI Bold
* Menlo Regular
* Menlo Bold

### Touchbar Symbols
I located the .car assets file for the Macbook Touchbar symbols, and used them instead of drawing my own.

### Symbol Reference
Symbol | Key | Unicode Name
------ | ---- | ---
⌘      | Command | PLACE OF INTEREST SIGN
⌃      | Control | UP ARROWHEAD
⌥      | Option | OPTION KEY
⎇      | Option |ALTERNATIVE KEY SYMBOL
⇧      | Shift | UPWARDS WHITE ARROW
⇪      | Caps Lock | UPWARDS WHITE ARROW FROM BAR
↩      |︎ Return | LEFTWARDS ARROW WITH HOOK
⏎      | (actual return) | RETURN SYMBOL
⌅      | Enter | UP ARROWHEAD BETWEEN TWO HORIZONTAL BARS
⌦      | Delete | ERASE TO THE RIGHT
⎋      | Escape | BROKEN CIRCLE WITH NORTHWEST ARROW
⏏      | Eject | EJECT SYMBOL
⇥      | Tab | RIGHTWARDS ARROW TO BAR
fn     | Function | N/A

* New keyboards seem to use the alternative option key symbol. When using *Apple Symbols* it will display (properly) as a wider version, rather than upside-down.
* Enter ≠ Return
	* Apple uses the left hooked arrow rather than the actual return symbol.
* Backspace ≠ Delete
	* The backspace key is labeled "Delete"
	* The delete key has the delete symbol
* The Function Key has no symbol

## Resources

### DIP Switch Reference
The keyboard has six DIP switches for various functions and modes.
My chosen arrangement: 1 enabled, 2-5 disabled, 6 enabled.

Switch State | Function | Notes
------ | ---- | ---
1 off, 2 off | QWERTY mode
1 on, 2 off | Mac mode | Swap default CMD and OPT key positions
1 off, 2 on | Dvorak mode
1 on, 2 on | Colemak mode
3 off | (L) CTRL = (L) CTRL, Caps Lock = Caps Lock
3 on | (L) CTRL = (L) CTRL, Caps Lock = (L) CTRL | Caps Lock function removed
4 off | Scroll Lock = Scroll Lock
4 on | Scroll Lock = OS Key Lock | Use to enable/disable OS keys
5 off | OS Keys enabled
5 on | OS Keys disabled | If disabled, OS Key Lock mode is disabled
6 off | Menu Key = Menu Key
6 on | Menu Key = Fn Key | Use to access built-in media commands

Reading
- https://developer.apple.com/fonts/
- https://designforhackers.com/blog/san-francisco-font/
- https://developer.apple.com/videos/play/wwdc2015/804/
- https://developer.apple.com/videos/play/wwdc2016/803/
- https://github.com/aasmith/mac-wasd-keyboard
- https://github.com/kreso22/WASD-keyboard---MAC-layout
- https://github.com/jasonbraun/WASD-Mac-Layout
- https://github.com/stevenlordiam/WASDkeyboard_for_mac
- https://support.wasdkeyboards.com/hc/en-us/articles/115007847008-Download-Template-Files

Applications
- [Karabiner Elements](https://pqrs.org/osx/karabiner/)
- [Karabiner EventViewer](https://pqrs.org/osx/karabiner/document.html#eventviewer)
- [Key Codes](https://manytricks.com/keycodes/)
- [BetterTouchTool](https://folivora.ai/downloads)
