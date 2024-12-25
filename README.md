<div align="center">
  <img width="220" height="220" src="./logo.png" />
  <h1>Awesome ZMK</h1>
  <br/>
</div>

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Unlicense](https://upload.wikimedia.org/wikipedia/commons/e/ee/Unlicense_Blue_Badge.svg)](https://unlicense.org)

A collection of useful resources, drivers, behaviors, tools, and more for the ZMK firmware.

## Table of Contents

- [Official Resources](#official-resources)
- [Behaviors](#behaviors)
- [Drivers](#drivers)
- [Other Resources](#other-resources)

---

## Official Resources

- [Official website](https://zmk.dev/)
- [Source code](https://github.com/zmkfirmware/zmk)
- [Discord](https://zmk.dev/community/discord/invite)

## Tools

- [keymap-drawer](https://github.com/caksoylar/keymap-drawer) - Visualizes keymaps that use advanced features like hold-taps and combos, with automatic parsing.
- [keymap-editor](https://github.com/nickcoutsos/keymap-editor) - Graphical keymap editor.
- [zmk-locale-generator](https://github.com/joelspadin/zmk-locale-generator) - Python module to generate localized keyboard layout headers for ZMK Firmware.

## Behaviors

- [zmk-tri-state](https://github.com/dhruvinsh/zmk-tri-state) - Tri-state (swapper) implementation.
- [zmk-num-word](https://github.com/dhruvinsh/zmk-num-word) - Num-word implementation.
- [zmk-auto-layer](https://github.com/urob/zmk-auto-layer) - Auto-layer (including num-word) implementation.
- [zmk-split-peripheral-input-relay](https://github.com/badjeff/zmk-split-peripheral-input-relay) - This module adds an input relay to the input subsystem for ZMK. This would allow, for example, sending trackpoint events from the peripheral to the center split.
- [zmk-split-peripheral-output-relay](https://github.com/badjeff/zmk-split-peripheral-output-relay) - This module adds an output relay for ZMK. This allows sending events from the central to peripherals, for example, to trigger haptic feedback or LEDs on certain events.
- [zmk-behavior-insomnia](https://github.com/badjeff/zmk-behavior-insomnia/) - Insomnia Behavior for ZMK. This module prevents the board from entering sleep mode if BLE is connected, useful for multi-peripheral setups to avoid continuous BLE advertisement scanning.
- [zmk-adaptive-key](https://github.com/urob/zmk-adaptive-key) - A ZMK module adding a adaptive-key behavior.
- [zmk-antecedent-morph](https://github.com/ssbb/zmk-antecedent-morph) - ZMK Antecedent Morph Behavior aka Adaptive Keys.
- [zmk-leader-key](https://github.com/urob/zmk-leader-key) - A ZMK module adding a leader-key behavior.
- [zmk-deadkey-slayer](https://github.com/ssbb/zmk-deadkey-slayer) - A ZMK module to drop illegal keycodes.

## Drivers

- [zmk-rgbled-widget](https://github.com/caksoylar/zmk-rgbled-widget) - A ZMK module to add battery & BT indicators using an RGB LED (like in Xiao BLEs).
- [zmk-drv2605-driver](https://github.com/badjeff/zmk-drv2605-driver/) - DRV2605 haptic feedback driver.
- [inorichi's zmk-pmw3610-driver](https://github.com/inorichi/zmk-pmw3610-driver) - PMW3610 trackball sensor driver.
- [badjeff's zmk-pmw3610-driver](https://github.com/badjeff/zmk-pmw3610-driver) - Other implementation of PMW3610 driver.
- [zmk-adns9800-driver](https://github.com/badjeff/zmk-adns9800-driver) - ADNS9800 trackball sensor driver.
- [zmk-ps2-mouse-trackpoint-driver](https://github.com/infused-kim/kb_zmk_ps2_mouse_trackpoint_driver) - PS/2 trackpoint driver.
- [ec-support-zmk-module](https://github.com/petejohanson/ec-support-zmk-module) - Electrostatic Capacitive (Topre) matrix scan implementation.

## Other

- [Hammerbeam Slideshow](https://github.com/GPeye/hammerbeam-slideshow) - A zmk module to implement a slideshow of 30 of Hammerbeam's 1 bit art on the peripheral (right) nice!view display.
- [nice!view Elemental](https://github.com/kevinpastor/nice-view-elemental) - A bold while minimalistic interface for your keyboard's display.

## Guides

- [ZMK design guide](https://github.com/ebastler/zmk-designguide) - A short hardware-designguide for ZMK keyboards.
- [Maintaining a personal ZMK fork](https://gist.github.com/urob/68a1e206b2356a01b876ed02d3f542c7) - A cookbook approach to maintaining a personal ZMK fork.
