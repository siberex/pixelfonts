# Pixel fonts convertion

Effort to build a small library of some selected old-fashioned pixel fonts (aka terminal fonts) in an easy-parseable (or at least readable) format.

Mostly to be used with microcontrollers and tiny displays, like [SSD1306-based](https://github.com/adafruit/Adafruit_SSD1306) [128x32 0.91" OLED](https://github.com/raspberrypi/pico-examples/tree/master/i2c/ssd1306_i2c).


# Convertion utility

[mkwinfont](https://github.com/juanitogan/mkwinfont) by Simon Tatham and Matt Jernigan.

Usage:

```bash
python3 dewinfont.py -p DOSAPP DOSAPP.FON
python3 dewinfont.py -o Quake1.txt Quake1.fon
```


# Font sources

- [The Ultimate Oldschool PC Font Pack](https://int10h.org/oldschool-pc-fonts/) – huge pixel fonts database by [VileR](https://www.youtube.com/user/x86VileR/videos)

- [fixed](https://www.chiark.greenend.org.uk/%7Esgtatham/fonts/) exported font by [PuTTY author himself](https://www.chiark.greenend.org.uk/~sgtatham/)

- [Quake](https://quakewiki.org/wiki/Quake_font)

- [BigBlue Terminal 8x12](https://int10h.org/blog/2015/12/bigblue-terminal-oldschool-fixed-width-font/)

- [ruscii](https://plugring.farmanager.com/plugin.php?pid=345&l=ru)


# Additional resources

- https://michelbytes.blogspot.com/2012/08/how-to-make-fon-bitmap-font-files.html

- https://stackoverflow.com/questions/27470295/where-i-can-find-fon-format-specification

- [https://en.wikipedia.org/wiki/Code_page_437](Code page 437)

- [https://en.wikipedia.org/wiki/Atari_ST_character_set](Atari ST character set)
