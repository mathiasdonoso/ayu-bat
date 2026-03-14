# ayu-bat

A `bat` theme based on the [Ayu](https://ayutheme.com/) color palette.

## Installation

```bash
mkdir -p "$(bat --config-dir)/themes"
cd "$(bat --config-dir)/themes"
git clone https://github.com/mathiasdonoso/ayu-bat
bat cache --build
```

## Usage

List all installed Ayu themes:
```bash
bat --list-themes | grep ayu
```

Use a theme directly
```bash
bat --theme="ayu-dark" main.c
```

Or set it permanently via the `BAT_THEME` environment variable in your shell's startup file:
```bash
export BAT_THEME="ayu-dark"
```
