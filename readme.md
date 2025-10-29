# The Kaasch Keys Keyboard
Is a keyboard idea I've had for a while. It's not supposed be seen a product, or as competing with other established open source keyboards. But a project of learning and nerding out about the gear of which we primarily communicate with computers.

## The (simple) spec
- A somewhat ergonomic keyboard split keyboard
- Suitable for gaming, which means space for dedicated modifier keys and number keys.
- Suitable for programming and general productivity, which means it needs to be comfortable during sustained use.

### The hardware
    MCU     = nRF52840          # widely supported, modern features, boards cheap on bulk
    SWITCH  = Cherry MX         # Favorite key and shows kindness to enthusiastic use.
    CASE    = Custom 3d print   # At least I'll be the one at fault for bad design.
    PLATE   = Custom 3d print   # Same as above.
    PCB     = Custom PCB        # Made in KiCad. Has gerber and keyboard plugin support.

### The software
With a nRF52840 board, ZMK or BlueMicro should be viable firmware to drive the keyboard, and offer plenty of customizability for my taste.
I'll also be free of fixing software problems years in the future, should I still wish to use the keyboard.
