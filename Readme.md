The idea was first proposed by jdcarpe at the mechnical keyboard forum known as GeekHack. It was to design a portable, fully programmable mechanical keyboard, which fits cases available in the mechanical keyboard market. Original thread can be found at https://geekhack.org/?topic=34959.0 

GH60 Custom Keyboard
Ever wanted your Poker/Pure to have a programmable controller? Did you love the different layout options of the Phantom, but wanted it in a smaller form factor? This is a 60% form-factor Geekhack custom keyboard that will be somewhat similar to the Phantom, but it will not include the function row, cursor arrows, or insert key group.

- Includes support for programmable layers.

- PCB populated from factory with all electronics, including diodes and ATmega32u4 programmable controller chip. Only switches will need to be sourced and mounted. Support for PCB-mount switches.

- Support for Poker/Pure cases, including aluminum cases from imsto, oneproduct, or treble318.

Supported Layouts:

- Normal/Standard Ansi layout
- ISO layout (vertical enter key, smaller left shift, additional key to the left of "z" key)
- 1.75x right shift, allowing extra 1x Fn/Mod/etc key to the right or left of the right shift key
- Model M "winkeyless" style layout with 1.5x - 1x - 1.5x modifier keys on left and right sides, with 7x spacebar
- lysol's proposed layout with two 1.5x modifiers on the left and 1.5x - 1x - 1x - 1.5x on the right, with 7x spacebar


The ATmega32u4 controller chip
This is the same chip as on the Teensy2.0. It is a 16MHz 8-bit AVR from Atmel.

Additionally find some blog posts on Komar's blog here: http://blog.komar.be/introducing-the-gh60-keyboard-project/

Project assumptions

The basic assumptions were:

    60% form-factor - that means the keyboard is limited to the block of keys from tilde to right control; no arrows, numpad, page up/down or F keys,
    persistent, programmable layout - it had to allow for easy changing of which scancode each key sends,
    compatible with existing cases: KBC Poker plastic case and other custom Poker cases,
    support for both ISO and ANSI, making it the first ISO 60% mechanical keyboard,
    support for both PCB- and plate-mounted Cherry MX switches.

The GH60 is not a complete keyboard for an end-user, but a so-called custom keyboard, which means that its users will only get the PCB populated with all the SMD components, but will have to solder the switches themselves. 
