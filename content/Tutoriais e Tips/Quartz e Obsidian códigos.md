---
title: Quartz e Obsidian códigos
draft: false
tags:
  - seedling
---
## Comandos Quartz

- Pra rodar o site no localhost
  - `npx quartz build --serve`

- Pra dar commit das mudanças
  - `npx quartz sync`

---

## HTML pra mudar coisas na página

`<div style="background-color: --secondary;">`
`</div>`
colors:
  lightMode:
    light: "#E8E1D8"
    lightgray: "#e5e5e5"
    gray: "#b8b8b8"
    darkgray: "#4e4e4e"
    dark: "#2b2b2b"
    secondary: "#d1081c"
    tertiary: "#a80717"
    highlight: rgba(143, 159, 169, 0.15)
    textHighlight: "#fff23688"
  darkMode:
    light: "#161618"
    lightgray: "#393639"
    gray: "#646464"
    darkgray: "#d4d4d4"
    dark: "#ebebec"
    secondary: "#d1081c"
    tertiary: "#a80717"
    highlight: rgba(143, 159, 169, 0.15)
    textHighlight: "#b3aa0288"