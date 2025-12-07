# Tmux Configuration

Catppuccin theme based tmux configuration with TPM plugin management.

## Included Plugins

- [catppuccin/tmux](https://github.com/catppuccin/tmux) - Theme
- [tmux-plugins/tmux-cpu](https://github.com/tmux-plugins/tmux-cpu) - CPU status
- [tmux-plugins/tmux-battery](https://github.com/tmux-plugins/tmux-battery) - Battery status

## Installation

### 1. Clone this repository

```bash
git clone <repository-url> ~/.config/tmux
```

### 2. Install TPM (Tmux Plugin Manager)

```bash
git clone https://github.com/tmux-plugins/tpm ~/.config/tmux/plugins/tpm
```

### 3. Install plugins

Start tmux and press `prefix` + <kbd>I</kbd> (capital i) to install plugins.

```bash
tmux
# Then press: Ctrl-b I
```

## Key Bindings

| Key | Action |
|-----|--------|
| `prefix` + <kbd>I</kbd> | Install plugins |
| `prefix` + <kbd>U</kbd> | Update plugins |
| `prefix` + <kbd>alt</kbd> + <kbd>u</kbd> | Remove unused plugins |

Default prefix: <kbd>Ctrl</kbd> + <kbd>b</kbd>
