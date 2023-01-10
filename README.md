# Rust Arduino Uno Template

This is a basic template that builds on [this](https://github.com/Rahix/avr-hal-template.git)
template from the mighty Rahix themself.

Specifically:
- Generic rust nightly instead.
- Debug symbols disabled in debug mode.
- No license or any extra files, meant to Just Work™.

First time use:
- Install the arduino stuff: `avr-gcc`, `avrdude`, `avr-binutils`, etc.
- Have rust nightly installed.

Be sure to edit Cargo.toml to match your project and remove this README.

## Lazy Setup

```
curl https://raw.githubusercontent.com/davnotdev/rust_arduino_uno_template/main/init | sh
```

## Manual Setup

If you don't have curl or the init script fails (you don't see the finish message), do the following:
- Clone this repo.
- Delete `init` and this file.
- Modify Cargo.toml.
- Switch to rust nightly if you haven't alread.
- Enjoy!

## Usage

`cargo r` will flash to the arduino. (Isn't that neat.)

