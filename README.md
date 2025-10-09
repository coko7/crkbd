# ⌨️ crkbd

VIAL config for my Corne (foostan/crkbd) RGB keyboard.
The keyboard config is in [keymap.vil](./keymap.vil).

![Keyboard Picture RGB Rainbow Glow](./images/crkbd_choc_rgb_transparent_small_cropped.png)

## Keyboard Specs

These are the specs for my keyboard:
- Keyboard: [Corne (foostan/crkbd)](https://github.com/foostan/crkbd) (v4.1)
- Total keys: 46 (3 × 6 + 5)
- Switches: [Kailh Choc v1 Brown](https://chosfox.com/products/kailh-chocs)
- Keycaps: [MBK Legend‡ Glow R2](https://fkcaps.com/keycaps/mbk/legend-glow-r2)
- Firmware: [VIAL](https://get.vial.today/) ([QMK](https://github.com/qmk/qmk_firmware) fork)
- Vendor: [Keebart](https://www.keebart.com/) ([keyboard reference](https://www.keebart.com/products/corne))
- RGB Lighting: yes
- QMK keyboard id: `crkbd/rev4_1`

## Layout

To better understand how I use my keyboard, I have *split* the layout in two parts:
- **Hardware layout:** How the keys are mapped via the keyboard firmware itself.
- **Software layout:** OS emulation layer that remaps some keys (ex: `qwerty`, `azerty`, `dvorak`, `colemack`, etc.)

### Hardware Layout

I primarily use two layers (layer 0 and 1) for most of my daily work.
I have two additional layers for extra keys I might need at times.

**Default Layer:** Letters and common symbols
![Default Layer (Layer 0)](./images/layer_0.png)

**Layer 1 (NavNum):** Numbers, navigation keys and media keys
![Layer 1](./images/layer_1.png)

**Layer 2:** Function Keys (F1 - F20)
![Layer 2](./images/layer_2.png)

**Layer 3:** Mouse actions and RGB control
![Layer 3](./images/layer_3.png)

These screenshots were taken directly from the VIAL desktop application: https://get.vial.today/download/
> [!IMPORTANT]  
> Screenshots may not be up to date. Check `keymap.vim` for the actual layout.

### Software Layout

I have recently moved from QWERTY over to [Ergo-L](https://ergol.org/).
Similarly to [Dvorak](https://en.wikipedia.org/wiki/Dvorak_keyboard_layout) or [Colemack](https://en.wikipedia.org/wiki/Colemak), Ergo-L is an ergonomic keyboard layout.

Ergo-L is well thought out and optimized for typing in French, English, and offering an easy access to programming symbols.
The layout comes with four main "layers":
- Default layer for letters and other characters
- [Shift](https://en.wikipedia.org/wiki/Shift_key) modifier for uppercase letters and other alternate characters
- [Alt Graph (Right Alt)](https://en.wikipedia.org/wiki/AltGr_key) modifier for symbols (with easy to reach programming symbols)
- [Dead Key](https://en.wikipedia.org/wiki/Dead_key) for diacritical marks (accents)

It's a really cool project and it fits my use case perfectly!

I recommend taking a look at their website. It is full of useful information and has some excellent advice when it comes to learning a new keyboard layout.

**Website:** https://ergol.org/

> [!NOTE]
> If we consider both pieces of hardware and software layouts, it would give a total of seven different layers.
> And if I were to map all the main 36 keys in each layer, I could have **252 different keys**.
> That's more than twice the amount of keys on a full size keyboard BUT with them being WAY closer together.

## Previous keyboard

The 46 keys corne was not my first ergo keyboard.

I started with a Sofle RGB: [coko7/sofle](https://github.com/coko7/sofle)
