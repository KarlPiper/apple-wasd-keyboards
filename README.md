# Apple WASD Keyboards—Custom Layout

![Completed keyboard template](https://raw.githubusercontent.com/KarlPiper/apple-wasd-keyboards/master/Preview.png)
![Completed keyboard photo](https://raw.githubusercontent.com/KarlPiper/apple-wasd-keyboards/master/Final%20Product%204.png)

## About

* Print quality
  * No line-width related issues whatsoever. If anything the look is a bit bold compared to my Macbook and old Apple keyboards. Printing in a dark grey rather than black is one way to offset this.
  * I chose to have the funciton key row printing in white, on black keys, the printing here looks perfect. Possibly sharper and less bold; closer to the intended look.
  * A couple keys are sligntly offcenter or have slightly heavy printing. The keys are curved though so it's forgiven.
  * I suggest using a more open command symbol (⌘) than mine. The counters are slightly muddy.
  * No kerning issues on keys printed with words. (template does use some custom kerning)
* Board pictured
  * WASD V2 87-Key Custom Mechanical Keyboard
  * DIP switch arrangement: 1 enabled, 2-5 disabled, 6 enabled.
* Template used
  * wasd-ai-104-8.28.2015.ai (104/87-Key US ANSI Layout)
  * All legends for 104 key board were filled in.

## Character Styles

* Normal—sets SF Compact Text Light, inherited by other styles
* Modifiers—keys with full words printed out (except media keys)
* Functions—F keys
* Stacked Keys—keys with two stacked legends (not numbers)
* Stacked Keys (tall)—used on {, }, |
* Denominator—lower character on number keys, larger
* Numerator—upper character on number keys, smaller
* Media keys—media key cluster + numpad “clear” and “enter”

## Alignment

Some keys required optical centering, e.g. J, L, Q, P, F, delete.

## Stylistic Alternates

I chose to use the straight 6, straight 9, and slashed 0.
“*” was switched out for SF Mono Light.
Actual x, +, -, / characters used on numpad.

## System Font Symbols

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

## Touchbar Symbols

I located the .car assets file for the Macbook Touchbar symbols, and used them instead of drawing my own.

## Symbol Reference Table

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

* New keyboards seem to use the alternative key symbol. It’s wider, and is not upside down in *Apple Symbols*.
* Enter ≠ Return
	* Apple uses the left hooked arrow rather than the actual return symbol.
* Backspace ≠ Delete
	* The backspace key is labeled "Delete"
	* The delete key has the delete symbol
* The Function Key has no symbol

## Supplemental Applications

These are for setting up keyboard macros, shortcuts, alternate keybindings, etc.

- [Karabiner Elements](https://pqrs.org/osx/karabiner/)
- [Karabiner EventViewer](https://pqrs.org/osx/karabiner/document.html#eventviewer)
- [Key Codes](https://manytricks.com/keycodes/)
- [BetterTouchTool](https://folivora.ai/downloads)

## Resources

- https://developer.apple.com/fonts/
- https://designforhackers.com/blog/san-francisco-font/
- https://developer.apple.com/videos/play/wwdc2015/804/
- https://developer.apple.com/videos/play/wwdc2016/803/
- https://github.com/aasmith/mac-wasd-keyboard
- https://github.com/kreso22/WASD-keyboard---MAC-layout
- https://github.com/jasonbraun/WASD-Mac-Layout
- https://github.com/stevenlordiam/WASDkeyboard_for_mac
- https://support.wasdkeyboards.com/hc/en-us/articles/115007847008-Download-Template-Files
