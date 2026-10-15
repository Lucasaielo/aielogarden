---
title: Lembretes Quartz
draft: false
tags:
  - seedling
Language: English
---
## Quartz Sync Shortcut

You can create a quick Sync Button on your desktop by creating a shortcut with this function:
`C:\Windows\System32\cmd.exe /k "cd [YourQuartzDirectory] & npx quartz sync"`

If your quartz directory is not on C:, make sure to specify the change of directory before the call. To change it to D, for example, add a /d like this:
`C:\Windows\System32\cmd.exe /k "cd /d [YourQuartzDirectory] & npx quartz sync"`

## Quartz Commands

- Test build on localhost
  - `npx quartz build --serve`

- Commit changes
  - `npx quartz sync`

---

## HTML codes from custom css

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