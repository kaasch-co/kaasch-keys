# The Kaasch Keys Keyboard
Is a keyboard idea I've had for a while. It's not supposed be seen a product, or as competing with other established open source keyboards. But a project of learning and nerding out about the gear of which we primarily communicate with computers.

## The (simple) spec
- A somewhat ergonomic keyboard split keyboard
- Suitable for gaming, which means space for dedicated modifier keys and number keys.
- Suitable for programming and general productivity, which means it needs to be comfortable during sustained use.

### The hardware
MCU     = nRF52840          # As they're widely supported, offer modern features, and quite cheap on bulk.
SWITCH  = Cherry MX         # Favorite key due to options, comfort, and kindness to enthusiastic use.
CAS     = Custom 3d print   # Personalization. More of a hassle, but at least I'll be at fault for bad design.
PLATE   = Custom 3d print   # Same as above. But can also be adapted to fit with other materials.
PCB     = Custom PCB        # Made with KiCad which supports gerber export and has good switch footprint plugins.

### The software
Because of MCU support both ZMK and QMK should be viable firmware to flash the mcu.
I'll also be free of fixing software problems years in the future, should I still wish to use the keyboard.
