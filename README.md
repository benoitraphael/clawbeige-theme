# ClawBeige

A warm, minimal VSCode theme inspired by the Claude Desktop interface — soft beige tones, terracotta accents, and easy-on-the-eyes contrast.

Tuned as much for **writing prose** (notes, articles, Markdown drafts) as for code. Markdown and plain text files automatically render in **Inter**; code files render in **JetBrains Mono**.

> **For the best experience, install the recommended fonts first.**
>
> **macOS** (one command, copy-paste in your terminal):
> ```sh
> brew install --cask font-inter font-jetbrains-mono
> ```
>
> **Windows / Linux**: download [Inter](https://fonts.google.com/specimen/Inter) and [JetBrains Mono](https://www.jetbrains.com/lp/mono/) from their official sites.
>
> Without these fonts, the theme falls back to your system sans-serif (SF Pro on Mac, Segoe UI on Windows). Still readable — but the typography is designed around Inter and JetBrains Mono.

Available in two variants:

| Variant | Style |
|---|---|
| **ClawBeige** | ☀️ Light — warm cream background, aligned with Claude.ai (`#F8F8F6`) |
| **ClawBeige Dark** | 🌙 Dark — deep warm coffee background |

---

## Color Palette

Both themes share the same accent colors. Backgrounds are aligned with the Anthropic / Claude.ai palette (Ivory tones for light).

### Light variant

| Role | Color |
|---|---|
| Editor background | `#F8F8F6` (Claude.ai) |
| Sidebar | `#F0EEE6` (Ivory Medium) |
| Activity bar | `#E8E6DC` (Ivory Dark) |
| Text | `#2C2420` |
| Accent (terracotta) | `#C15F3C` |
| Strings | `#7A5A20` |
| Functions | `#6A4A90` |
| Types / Classes | `#2A5A8A` |
| Comments | `#A89888` |

### Dark variant

| Role | Color |
|---|---|
| Editor background | `#2C2620` |
| Sidebar | `#332C25` |
| Activity bar | `#3D362F` |
| Text | `#e8e6e3` |
| Accent (terracotta) | `#C15F3C` |
| Strings | `#d4a96a` |
| Functions | `#d4b483` |
| Types / Classes | `#c9a96e` |
| Comments | `#6a6158` |

---

## Typography

ClawBeige sets per-language font defaults so your editor adapts automatically:

- **Markdown, plain text, MDX** → **Inter** at 15px / line-height 26 (with word wrap on).
- **All other code files** → **JetBrains Mono** at 13px / line-height 22 (with ligatures).

Both fonts are free, open-source, and have proper italic designs (no synthesized slant on digits).

### Install the recommended fonts

**macOS (Homebrew Cask):**

```sh
brew install --cask font-inter font-jetbrains-mono
```

**All platforms:**

- [Inter](https://fonts.google.com/specimen/Inter) — download from Google Fonts.
- [JetBrains Mono](https://www.jetbrains.com/lp/mono/) — download from JetBrains.

If a font is missing, the theme falls back gracefully:

- Inter → `-apple-system` → `Segoe UI` → `system-ui` → generic sans-serif.
- JetBrains Mono → `SF Mono` → `Menlo` → `Consolas` → `DejaVu Sans Mono` → generic monospace.

### Override the defaults

If you'd rather use a different font, add this to your `settings.json`:

```json
"[ClawBeige]": {
  "editor.fontFamily": "'Your Mono Font', monospace",
  "editor.fontSize": 13
}
```

---

## Installation

1. Open **Extensions** in VSCode (`Cmd+Shift+X`)
2. Search for `ClawBeige`
3. Click **Install**
4. Open the Command Palette (`Cmd+Shift+P`) → **Preferences: Color Theme** → select **ClawBeige** or **ClawBeige Dark**

For the best experience, install **Inter** and **JetBrains Mono** beforehand (see above).

---

## About

Designed by [Benoit Raphael](https://flint.media) — built with Claude Code.
