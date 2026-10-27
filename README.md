# CHIP-8 Emulator

A CHIP-8 emulator written in Rust, using Macroquad for its window and display.

## Example: Snake

The screenshots below show the emulator running Snake: first at the game's main
menu, then during gameplay.

![Snake game main menu](screenshots/snake%201.png)

![Snake game in progress](screenshots/snake%202.png)

## Run

Install the Rust toolchain, then run the project from the repository root:

```sh
cargo run
```

The ROM to load is currently hard-coded in `src/main.rs` and points to a
machine-specific path for `br8kout.ch8`. Update that path to the location of a
CHIP-8 ROM on your machine before running. Making the ROM selectable by the user
is the next step for the project.
