# agy-pet Homebrew Tap

Homebrew formulae for [agy-pet](https://github.com/agy-pet) projects.

![Maggy](https://raw.githubusercontent.com/agy-pet/maggy/master/assets/social-preview.png)

## Formulae

| Formula | Description |
| --- | --- |
| [`maggy`](Formula/maggy.rb) | [Maggy](https://agy-pet.github.io/maggy/), the dancing Antigravity logo for your `agy` statusline |

## Install

```bash
brew install agy-pet/tap/maggy
maggy setup
```

Then restart `agy` (or run `/statusline enable` inside it).

Or tap once and install by name:

```bash
brew tap agy-pet/tap
brew install maggy
```

## Upgrade

```bash
brew update
brew upgrade maggy
```

## Uninstall

```bash
maggy uninstall        # removes the statusLine entry from agy's settings
brew uninstall maggy
brew untap agy-pet/tap
```

## Issues

Report problems with Maggy itself at [agy-pet/maggy](https://github.com/agy-pet/maggy/issues).
Problems with the formula (install, upgrade, checksums) can go to [this repo's issues](https://github.com/agy-pet/homebrew-tap/issues).

---

maggy is an unofficial fan project. It is not affiliated with, endorsed by, or sponsored by Google.
