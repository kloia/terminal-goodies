#  "Living" in the Terminal
Low-effort, low-config, command line based tooling

 kloia / Efe Hakan Gencoglu

## Topics:
1. Terminals
2. Fonts
3. Shell & Auto-complete
4. Prompts
5. CLI Tools
6. dotfile Management
7. Other Goodies

---

## 1. Terminal (emulators*)

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

---

## 2. Fonts

**Nerd Fonts** allow you to do this:
```
--->  kloia
```

Easily installed with:
```
brew tap homebrew/cask-fonts
brew install font-jetbrains-mono-nerd-font
```

---

## 3. Shells & Auto-complete

- [**fish**](https://fishshell.com/)
  - **built in Auto-Complete**
  - low configuration needed
  - ⚠️ not-bash compatible
    - seems like a con, but you can always `bash -c`
- **zsh**
  - macOS default
  - [large ecosystem](https://github.com/unixorn/awesome-zsh-plugins)
  - auto-complete via [zsh-autocomplete](https://github.com/marlonrichert/zsh-autocomplete)
- **bash**
  - good ol' bash
  - universal

---

## 4. Prompts

- [**starship.rs**](https://starship.rs/)
  - gives you quick feedback on your environment

---

## 5. CLI Tools

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
    - alternative to find
  - ...and more
- [**slides**](https://github.com/maaslalani/slides)
  - simple markdown slideshows on terminal

---

## 6. dotfile Management

- [**chezmoi**](https://www.chezmoi.io/)
  - simple interface
  - powerful customizations as needed
    - go template support
    - pulling other git repositories
    - running commands on every sync
- [**dotbare**](https://github.com/kazhala/dotbare)
  - bare git repo based dotfile solution

## 7. Other Goodies

- [**Tailscale**](https://tailscale.com/)
  - easy to use personal/team VPN for devices
  - generous free tier for personal use
- [**Raycast**](https://www.raycast.com/)
  - a better spotlight replacement for macOS
  - neat plugins and integrations
