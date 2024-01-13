# mcu_chats_with_you
Basic micro:bit v2 display messaging with constant brightness.

#### Show
![software9119.technology](https://github.com/bravequickcleverfibreyarn/mcu_chats_with_you/blob/main/pre/software9119.technology.gif)

#### Guide

- For micro:bit v2 you are good to go with

```console
cargo flash  --target thumbv7em-none-eabihf --chip nRF52833_xxAA --release --features panic_abort
```

- Uses ug-max font. See https://crates.io/crates/ug_max.
