# Slatehollow

A theme family that gets out of the way. Three variants — one for each side of the day, plus one for OLED screens.

---

## Slatehollow Dark

Clean surfaces, minimal yet subtle border lines, five syntax colours. Enough to tell your code apart, not enough to distract you from it.

![Slatehollow Dark](themes/slatehollow-dark.png)

## Slatehollow Dark OLED

Same surfaces, same five colours — tuned for OLED panels. Wide-gamut displays and deep blacks make the original accents feel vivid, so this variant pulls accent saturation back by about a fifth and dims the body text a touch. Hues stay put, so every colour still means the same thing.

![Slatehollow Dark OLED](themes/slatehollow-dark-oled.png)

## Slatehollow Light

The light sibling. JetBrains Islands Light chrome, the same ink palette translated to a clean white editor with a whisper of cool in the panels.

![Slatehollow Light](themes/slatehollow-light.png)

---

## Philosophy

Borders (separator lines) only appear where colour can't do the job alone. Everything else relies on surface depth.

Syntax colours are intentional and minimal:

- **Blue** — functions, constructors
- **Sage green** — strings
- **Amber** — constants, numbers
- **Purple** — keywords
- **Dusty rose** — properties (the "pay attention" colour, used sparingly)

Everything else — variables, punctuation, namespaces — fades into the background. Structural, not semantic.

Five colours is a constraint, not a limitation. When every token is a different colour, your brain stops using colour as signal. We'd rather you read the code.

---

## Install

Open the Command Palette:

**macOS**

```text
cmd + shift + p → extensions → search "Slatehollow"
```

**Windows/Linux**

```text
ctrl + shift + p → extensions → search "Slatehollow"
```

Or search for **Slatehollow** in Zed's extension marketplace.

Configure your theme:

```json
{
  "theme": {
    "mode": "dark",
    "dark": "Slatehollow Dark", // or "Slatehollow Dark OLED"
    "light": "Slatehollow Light"
  }
}
```

---

Made by [Amsh](https://github.com/ams-sth)
