# 🧑‍💻 Minimal Hyprland Rice

Personal Linux environment configuration based on **Hyprland**, focused on a **clean, minimal and reproducible** setup.

This repository contains only **real configuration files (dotfiles)**.
No generated files, no cache, no runtime data.

---

## 📦 Included configs

Only the following components are versioned:

* **hypr** → Hyprland (Wayland compositor)
* **waybar** → status bar
* **kitty** → terminal
* **rofi** → launcher
* **mako** → notifications

---

## 🧱 Repository structure

```txt
Minimal-Hyprland-Rice/
├── hypr/
├── kitty/
├── mako/
├── rofi/
├── waybar/
├── LICENSE
├── .gitignore
└── README.md
```

---

## 🚀 Installation (manual)

```bash
cd ~
git clone git@github.com:MaximumRISC/Minimal-Hyprland-Rice.git
```

Then link the configs you want:

```bash
ln -s ~/Minimal-Hyprland-Rice/hypr ~/.config/hypr
ln -s ~/Minimal-Hyprland-Rice/waybar ~/.config/waybar
ln -s ~/Minimal-Hyprland-Rice/kitty ~/.config/kitty
ln -s ~/Minimal-Hyprland-Rice/rofi ~/.config/rofi
ln -s ~/Minimal-Hyprland-Rice/mako ~/.config/mako
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
* No backups
* No build artifacts

---

## 🎯 Purpose

This repo is designed for:

* Configuration backup
* Machine portability
* Fast setup
* Reproducible environments
* Consistent dev workflow
* Personal Linux infrastructure

---

## 🧑‍💻 Author

**Raul Santa Maria**
Linux • Hyprland • Zed • Developer

> "A good environment is not pretty — it is reproducible."
