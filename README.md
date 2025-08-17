# tdlib-rs

A Rust wrapper around the Telegram Database library. It includes a generator to automatically generate the types and functions from the TDLib's [Type Language](https://core.telegram.org/mtproto/TL) file.

It's mainly created for using it in the [Telegrand](https://github.com/melix99/telegrand) client, but it should work also for any other Rust project.

Current supported TDLib version: [1.8.52](https://github.com/tdlib/td/tree/4269f54e16b9cf564efc2db5bcd29743a2eec6ee).

## TL API file

https://raw.githubusercontent.com/tdlib/td/4269f54e16b9cf564efc2db5bcd29743a2eec6ee/td/generate/scheme/td_api.tl

## Credits

- [grammers](https://github.com/Lonami/grammers): the `tdlib-tl-gen` and `tdlib-tl-parser` projects are forks of the `grammers-tl-gen` and `grammers-tl-parser` projects.
- [rust-tdlib](https://github.com/aCLr/rust-tdlib): for inspiration about some client code.
