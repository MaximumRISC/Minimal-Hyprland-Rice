# 🧑‍💻 Dotfiles

Personal Linux environment configuration based on **Hyprland**, focused on a clean, minimal and reproducible setup.

This repository contains **only real configuration files (dotfiles)**.

---

## 📦 Included configs

Only the following components are versioned:

* `fastfetch` → system info
* `ghostty` → terminal
* `nvim` → Neovim config
* `kitty` → terminal
* `rofi` → launcher
* `hypr` → Hyprland (Wayland compositor)
* `waybar` → status bar
* `mako` → notifications

---

## 🧱 Repository structure

```txt
Dotfiles/
├── fastfetch/
├── ghostty/
├── nvim/
├── kitty/
├── rofi/
├── hypr/
├── waybar/
├── mako/
├── .gitignore
└── README.md
```

---

## 🚀 Installation (manual)

```bash
cd ~
git clone git@github.com:MaximumRISC/Dotfiles.git
```

Then link the configs you want:

```bash
ln -s ~/Dotfiles/nvim ~/.config/nvim
ln -s ~/Dotfiles/kitty ~/.config/kitty
ln -s ~/Dotfiles/rofi ~/.config/rofi
ln -s ~/Dotfiles/hypr ~/.config/hypr
ln -s ~/Dotfiles/waybar ~/.config/waybar
ln -s ~/Dotfiles/mako ~/.config/mako
ln -s ~/Dotfiles/fastfetch ~/.config/fastfetch
ln -s ~/Dotfiles/ghostty ~/.config/ghostty
```

---

## 🧠 Repository philosophy

* Clean
* Minimal
* Reproducible
* Portable
* Config-only
* No generated files
* No runtime data

---

## 🎯 Purpose

This repo is designed for:

* Configuration backup
* Machine portability
* Fast setup
* Reproducible environments
* Consistent dev workflow
* Personal infrastructure

---

## 🧑‍💻 Author

**Raul Santa Maria**
Linux • Hyprland • Zed • Developer

---

> "A good environment is not pretty — it is reproducible."
