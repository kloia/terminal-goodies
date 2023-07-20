# terminal-goodies

Terminal and Command Line tools Kloians use

## Terminal (emulators*)

- [**Kitty**](https://sw.kovidgoyal.net/kitty/#kitty)
  - performance
  - low latency
  - cross-platform
  - easy configuration
- **ITerm2**
  - macOS native feeling
  - practically zero configuration
- **Windows Terminal**
  - Windows native feeling
  - neat integration with WSL2 (running vms in windows)
- **WezTerm**
  - performance
  - cross-platform
  - high level of customization (lua)

## Fonts

**Nerd Fonts** allow you to do this:
```
--->  kloia
```

(which you probably can't see without the font, or on GitHub)

Easily installed with:
```
brew tap homebrew/cask-fonts
brew install font-jetbrains-mono-nerd-font
```

---

## Shells & Auto-complete

- [**fish**](https://fishshell.com/)
  - **built in Auto-Complete**
  - low configuration needed
  - not bash compatible!
    - seems like a con, but you can always `bash -c`
- **zsh**
  - macOS default
  - [large ecosystem](https://github.com/unixorn/awesome-zsh-plugins)
  - auto-complete via [zsh-autocomplete](https://github.com/marlonrichert/zsh-autocomplete)
- **bash**
  - good ol' bash
  - universal

---

## Prompts

- [**starship.rs**](https://starship.rs/)
  - gives you quick feedback on your environment

---

## CLI Tools

- [**Modern Unix**](https://github.com/ibraheemdev/modern-unix)
  - classic unix tools rewritten for modern systems
  - **fzf**
    - fuzzy finder for piping stuff
  - cat -> **bat**
    - content aware cat
  - ls -> **exa**
    - colors, icons, `.gitignore` support
    - kinda hard to type, I alias it to "ll"
  - find -> **fd**
  - ...and more
- [**slides**](https://github.com/maaslalani/slides)
  - simple markdown slideshows on terminal

---

## dotfile Management

For backing up dotfiles and reproducing development environments:

- [**chezmoi**](https://www.chezmoi.io/)
  - simple interface
  - powerful customizations as needed
    - go template support
    - pulling other git repositories
    - running commands on every sync
- [**dotbare**](https://github.com/kazhala/dotbare)
  - bare git repo based dotfile solution

## Other Goodies

- [**Tailscale**](https://tailscale.com/)
  - easy to use personal/team VPN for devices
  - generous free tier for personal use
- [**Raycast**](https://www.raycast.com/)
  - a better spotlight replacement for macOS
  - neat plugins and integrations
