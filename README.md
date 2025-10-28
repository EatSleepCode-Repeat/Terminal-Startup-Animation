# 🚀 Epic Terminal Startup Animation

<div align="center">

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Shell](https://img.shields.io/badge/shell-zsh-blueviolet.svg)
![Platform](https://img.shields.io/badge/platform-macOS%20%7C%20Linux-lightgrey.svg)

*Transform your terminal startup into a cinematic hacker experience* 🎬

[Features](#-features) • [Installation](#-installation) • [Usage](#-usage) • [Customization](#-customization) • [Demo](#-demo)

</div>

---

## ✨ Features

Transform your boring terminal into an **epic cyberpunk command center** with:

- 🎭 **Hollywood-Style Animations** - Matrix rain, glitch effects, and scan lines
- 🔐 **Security Theater** - Quantum encryption, neural networks, and blockchain validators
- 📊 **Resource Monitoring** - Animated progress bars for CPU, memory, and encryption
- 🎨 **Beautiful UI** - Color-coded status indicators and box-drawing characters
- ⚡ **Lightning Fast** - Optimized 5-6 second sequence that doesn't slow you down
- 🛠️ **Zero Dependencies** - Pure Zsh, no external tools required
- 🎮 **Multiple Modes** - Full cinematic mode or quick startup option

## 🎬 Demo

```
╔═══════════════════════════════════════╗
║   SECURE TERMINAL INITIALIZATION     ║
╚═══════════════════════════════════════╝

[✓] Initializing quantum encryption...
[✓] Establishing neural network bridge...
[✓] Loading cryptographic modules...
[✓] Synchronizing blockchain validators...
[✓] Mounting distributed filesystems...

SYSTEM RESOURCES
CPU Cores:  [██████████████████████████████] 100%
Memory:     [██████████████████████████████] 100%
Neural Net: [██████████████████████████████] 100%
Encryption: [██████████████████████████████] 100%

⚠ RUNNING SECURITY SCAN...
✓ Port scanning complete
✓ Firewall rules validated
✓ SSL certificates verified
✓ Intrusion detection active
✓ Quantum key distribution ready

>>> ACCESS GRANTED <<<

╔══════════════════════════════════════╗
║  🚀 TERMINAL READY                   ║
║  Welcome back, user                  ║
╚══════════════════════════════════════╝
```

## 📦 Installation

### Quick Install

```bash
# Create the scripts directory
mkdir -p ~/zsh-scripts

# Download the animation script
curl -o ~/zsh-scripts/terminal-animations.zsh https://raw.githubusercontent.com/yourusername/terminal-animations/main/terminal-animations.zsh

# Add to your .zshrc
echo "source ~/zsh-scripts/terminal-animations.zsh" >> ~/.zshrc

# Reload your shell
source ~/.zshrc
```

### Manual Install

1. **Create the directory:**

   ```bash
   mkdir -p ~/zsh-scripts
   ```

2. **Copy the script:**
   - Download `terminal-animations.zsh`
   - Place it in `~/zsh-scripts/`

3. **Source in your `.zshrc`:**

   ```bash
   # Add this line to ~/.zshrc
   source ~/zsh-scripts/terminal-animations.zsh
   ```

4. **Reload your shell:**

   ```bash
   source ~/.zshrc
   ```

## 🎯 Usage

### Run Animation Manually

```bash
# Full cinematic experience (5-6 seconds)
startup-animation

# Quick mode (2 seconds)
startup-animation-quick
```

### Run Automatically on Startup

Add this line to the **bottom** of your `~/.zshrc`:

```bash
# For full animation
startup-animation

# OR for quick mode
# startup-animation-quick
```

### Commands

| Command | Description |
|---------|-------------|
| `startup-animation` | Full epic animation sequence |
| `startup-animation-quick` | Shortened version for speed |

## 🎨 Customization

### Adjust Animation Speed

Open `~/zsh-scripts/terminal-animations.zsh` and modify the `_anim_sleep` values:

```bash
# Faster animations - reduce sleep times
_anim_sleep 50   # Change to 25 for 2x speed

# Slower animations - increase sleep times
_anim_sleep 50   # Change to 100 for 0.5x speed
```

### Change Colors

Modify the color variables at the top of the script:

```bash
_anim_green="\033[32m"          # System messages
_anim_bright_green="\033[92m"   # Success indicators
_anim_cyan="\033[36m"           # Headers
_anim_red="\033[31m"            # Warnings
_anim_yellow="\033[33m"         # Loading states
```

### Customize Messages

Edit the system check messages in the script:

```bash
_anim_type "Initializing quantum encryption..."
_anim_type "Establishing neural network bridge..."
# Add your own messages here!
```

### Skip Specific Phases

Comment out phases you don't want:

```bash
# Phase 1: Matrix rain initialization
# _anim_matrix_rain_bg 8  # Comment this to skip
```

## 🔧 Requirements

- **Shell:** Zsh (Z Shell)
- **OS:** macOS, Linux, or WSL2
- **Terminal:** Any modern terminal with 256-color support
- **Unicode:** UTF-8 support for special characters

## 🎭 What's Happening?

The animation includes these cinematic phases:

1. **Matrix Rain** - Green binary code cascade
2. **System Header** - Animated border with glowing text
3. **System Checks** - 5 critical systems with checkmarks
4. **Resource Loading** - 4 progress bars (CPU, Memory, Neural Net, Encryption)
5. **Security Scan** - Animated scan lines with validation
6. **DNA Helix** - Authentication visualization
7. **Access Granted** - Epic reveal with ASCII art logo
8. **Welcome Screen** - User info and system details

## 🚨 Troubleshooting

### Animation appears broken or garbled

- Ensure your terminal supports 256 colors
- Check that UTF-8 encoding is enabled
- Try resizing your terminal window

### Animation too slow/fast

- Adjust `_anim_sleep` values throughout the script
- Use `startup-animation-quick` for a faster experience

### Doesn't run on startup

- Make sure the `startup-animation` call is at the **end** of `.zshrc`
- Check that the script is properly sourced: `source ~/zsh-scripts/terminal-animations.zsh`
- Verify file permissions: `chmod +x ~/zsh-scripts/terminal-animations.zsh`

### Colors not working

- Check terminal color support: `tput colors` (should show 256)
- Try a different terminal emulator (iTerm2, Hyper, Alacritty)

## 🤝 Contributing

Contributions are welcome! Here are some ideas:

- 🎨 New animation phases
- 🎭 Different themes (cyberpunk, retro, minimal)
- 🌍 Language translations
- 🐛 Bug fixes and optimizations
- 📚 Documentation improvements

## 📝 License

MIT License - feel free to use this in your own projects!

## 🌟 Show Your Support

If you find this project useful, please consider:

- ⭐ Starring the repository
- 🐦 Sharing it on social media
- 🍺 Buying me a coffee

## 💡 Inspiration

Created for developers who want their terminal to feel as powerful as it actually is. Because if you're going to stare at a terminal all day, it might as well look awesome! 🚀

---

<div align="center">

Made with ❤️ by developers, for developers

**[⬆ Back to Top](#-epic-terminal-startup-animation)**

</div>
