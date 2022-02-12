# Gherkin

QMK OLED, Gherkin - help wanted :)
Hey everyone, after a long time of building keyboards I decided to try to build something from the PCB up, just like adult lego I really enjoyed it and have ordered a load of odd PCB's and stuff so I seem to have taken to this.

Something I was wondering was how some keyboards have OLED displaying a startup pattern and then display the text as it is typed (through a keylogger?)

I have tried for a few days to get my head around what you need to do to make this work.

I am trying to include a 128by32 I2C OLED 5v same as my pro micro

I have wired it up to the D1, D0, VCC and GND. I did include 4.7k resistors that I saw on one wiring guide but I have since removed them after seeing that some other builds don't seem to use them.

![Gherkin](https://4.bp.blogspot.com/-sQ18-lNZXOc/WCzlTde-4PI/AAAAAAAB_JQ/qQrehAMG6DMKf3i4oj4mkmLGOfTUvb3KgCLcB/s640/IMG_20161116_122926.jpg)
===

A 30 key keyboard.

* [The original TMK firmware](https://github.com/di0ib/tmk_keyboard/tree/master/keyboard/gherkin)

Keyboard Maintainer: QMK Community  
Hardware Supported: Gherkin PCB  
Hardware Availability: [Gherkin project on 40% Keyboards](http://www.40percent.club/2016/11/gherkin.html)

Make example for this keyboard (after setting up your build environment):

    make 40percentclub/gherkin:default

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

First pass at adding support for the gherkin keyboard. Compiles but completely
untested. Intended to kick-start development.
