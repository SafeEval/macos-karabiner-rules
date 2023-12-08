# MacOS Karabiner Rules

Keyboard mapping rules for Karabiner on MacOS.

Rules are in JSON format, and placed in `$HOME/.config/karabiner/assets/complex_modifications/*.json`.

## Other Keyboard Setup

MacOS keyboard configurations don't have character key repeating by default.
Enable it with `defaults` in the terminal.

```sh
defaults write -g ApplePressAndHoldEnabled -bool false
```

## Links

- [Karabiner home](https://karabiner-elements.pqrs.org/)
- [Karabiner reference docs](https://karabiner-elements.pqrs.org/docs/json/)
- [Karabiner complex rule examples](https://karabiner-elements.pqrs.org/docs/json/typical-complex-modifications-examples/)
- [Karabiner community complex rules](https://ke-complex-modifications.pqrs.org/)
