# ZMK Config (for all the things?)

Notes to self about how this stuff works...

The [intended layout](https://zmk.dev/docs/config) is:

* `/boards` contains definitions as defined by the hardware vendor.
* `/config` is for the user to override.

Filetypes:

* Kconfig is for global settings.
* `.dts` is for base hardware definitions.
* `.dtsi` only intended to be included from another file.
* `.overlay` files extend/override `.dts` stuff.
* `.keymap` is for user specific config.
