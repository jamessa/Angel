# Angel (2021)

Hand wired QMK is almost ready.  qmk/qmk_firmware#11501

A symmetric staggered ergonomic keyboard.
![a symmetric and beautiful hand wire keyboard](attachments/handwire.jpeg)

## Idea

A slightly ergonomic keyboard that fits into 60% form factor. ![layout concept](attachments/layout.jpg) 

 ## Featuring

* Staggered yet ergonmic ![Symmetric stagger is ergonomic](attachments/staggered_yet_ergonomics.jpg)

* Maximize hand distance ![hand distance](attachments/hand_distance.jpg)

* Arrow keys are must.

* Fitts' law is respected. Four corner keys are maximized while [you shall no call its name] is break into 3 keys.  The gaint space bar is a huge waste ot thumb(s). It breaks into 1.25, 1.5, 1.25 to free it up. My favorite combination is, <kbd>backspace</kbd>, <kbd>enter</kbd>, <kbd>whitespace</kbd>.

* 60% form factor which should fix your notebook perfectly.
![notebook](attachments/notebook.jpg)

* all keys are under 1.75u which means no stablizer is required. Period.

##  Cons

It's incompatible to traditioal keycaps layout. **CAPS LOCK** is the only 1.75u key on traditional keyboard. In Symmetric 60%, 4 is required but you can always swap into smaller keycaps at your wish.

## Prior work

in the order of first appearance.

[Symmetric Stagger 60%]( https://geekhack.org/index.php?topic=66965.0)  by Jesse Vincent, Keyboardio ![Symmetric Stagger](https://geekhack.org/index.php?action=dlattach;topic=66965.0;attach=84939;image) While I wait for the Model 01 boards to come back from Shenzhen, I've been messing around with a symmetric stagger 60% layout. Before I go and get 5 PCBs made, I'd love layout feedback from folks.

### Meti
[SemiErgo](https://github.com/mtei/SemiErgo_Layout) by meti (March 2017)   ![SemiErgo](https://github.com/mtei/SemiErgo_Layout/raw/master/Specification/SemiErgo_basic_physical_layout.png) I will vote it for ANSI standard without any doubt.

[Symmetric 70 hand-wire](https://github.com/qmk/qmk_firmware/tree/master/keyboards/handwired/symmetric70_proto) (2020)
![Symmetric 70](https://camo.githubusercontent.com/5c6d8242d2bdaa8c10bd91efcf5182c9fe9b18cc32800ad02bb30456bc864f72/68747470733a2f2f692e696d6775722e636f6d2f4272347048396f6c2e6a7067)

### Rominronin
[Katana 60](https://deskthority.net/viewtopic.php?t=16287&start=30) (Nov, 2017). it's a beauty. ![Katana 60](https://i.imgur.com/1yvw1uQ.jpg) ps. the character in the middle is 刀 which means sword in Chinese and Japanese.

[Tsuka60 - the Katana60 v2 PCB interest check](https://geekhack.org/index.php?topic=100468.msg2756587#msg2756587) (2019)

[Candykeys](https://candykeys.com/product/katana60-pcb-V2) (2020)

![Katana60 v2 PCB](https://ucarecdn.com/8b72e221-190f-42b6-b437-ddc6b7321744~3/nth/0/-/format/auto/-/quality/lighter/)
## Next

Now I am going to handwire one to refuse my point. Stay tune.

![handwire guide](attachments/handwire_guide.jpg)

You can [try it on paper](try_it.pdf) and [let me know](https://forms.gle/i4KZJjDPFTidD8Jt6) how to you think about Symmetric60.

## References

On space bar http://xahlee.info/kbd/keyboard_problems.html

Key symbols from http://xahlee.info/comp/unicode_computing_symbols.html

Mac keyboard shortcuts https://support.apple.com/en-us/HT201236

Human Engineering the Keyboard by K. H. Eberhard Kroemer
 Human Factors: The Journal of the Human Factors and Ergonomics Society 1972 14: 51 DOI: [10.1177/001872087201400110](
http://hfs.sagepub.com/content/14/1/51)

## Prototyping Tips

### Kicad

  - Hardware acceleration will eeschema freezes, so don't enable it. Reset settings by `rm -rf ~/Library/Preferences/kicad` or verisioning it.
  - Plot gerber files and drills based on [JCLPCB's tutorial](https://support.jlcpcb.com/article/102-kicad-515---generating-gerber-and-drill-files). [Suggested naming patterns](https://support.jlcpcb.com/article/29-suggested-naming-patterns)

Special thanks to Haway 梁, Jeff 邱, Justin 吳.