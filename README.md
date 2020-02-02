# Vortex Pok3r cheatsheet

## Notes

* The POK3R built in 4-layers. The default layer can not be programmed.
* `FN` + `Right CTRL`, `M`, `<`, `>`, and `?` keys are fixed can not be programmed.

## Programming

1. Choose the layer (`FN` + `<`,`>` or `?` key) you want to program.
2. Press `FN + Right CTRL` to enter the programming mode (Spacebar right LED steadily lit)
3. Press the key you want to program (Spacebar right LED flashing)
4. Key in the programming content and then press `Menu` (Spacebar right LED steadily lit again)
5. Repeat step 2 and step 3 to program other keys.
6. Press `FN + Right CTRL` to exit programming mode ( Spacebar right LED off) 

## Switching Layers

| Combination | Result | Remarks |
| ------------ | --- | ---|
| `FN` + `M` | Default | Spacebar left LED off |
| `FN` + `, <` | Layer 2 | Spacebar left LED showing <span style="color:red">RED</span> color |
| `FN` + `. >` | Layer 3 | Spacebar left LED showing <span style="color:green">GREEN</span> color |
| `FN` + `/ ?` | Layer 4 | Spacebar left LED showing <span style="color:blue">BLUE</span> color |

## FN General Keys

| Combination | Result |
| ------------ | --- |
| `FN` + `ESC` | ``` |
| `FN` + `1` | F1 |
| `FN` + `2` | F2 |
| `FN` + `3` | F3 |
| `FN` + `4` | F4 |
| `FN` + `5` | F5 |
| `FN` + `6` | F6 |
| `FN` + `7` | F7 |
| `FN` + `8` | F8 |
| `FN` + `9` | F9 |
| `FN` + `0` | F10 |
| `FN` + `- _ ` | F11 |
| `FN` + `= +` | F12 |
| `FN` + `I` | &uarr; |
| `FN` + `J` | &larr; |
| `FN` + `K` | &darr; |
| `FN` + `L` | &rarr; |
| `FN` + `P` | PrtSc |
| `FN` + `[ {` | ScrLk |
| `FN` + `] }` | Pause |
| `FN` + `Z` | App |
| `FN` + `H` | Home |
| `FN` + `N` | End |
| `FN` + `U` | PgUp |
| `FN` + `O` | PgDn |
| `FN` + `Backspace` | Del |
| `FN` + `' "` | Del |
| `FN` + `; :` | Ins |

## RGB Backlight Programming

### Selecting Colors

* `PN` + `ESC` for color palette
* `PN` + `1`, `2`, or `3` for a custom color

### Selecting Effect Speed
* `PN` + `<` to speed up
* `PN` + `>` to slow down

### Pok3r Reactive Presets

| Combination | Name | Remarks |
| ------------ | --- | ---|
| `PN` + `4` | Reaction Effect 1 | Single-key light up on press down (mono-color) |
| `PN` + `4`' | Reaction Effect 2 | Single-key light up on press down (multi-color) |
| `PN` + `4`'' | Reaction Effect 3 | Disco (mono-color) |
| `PN` + `4`''' | Reaction Effect 4 | Disco (multi-color) |
| `PN` + `4`'''' | Reaction Effect 5 | Single-line Wave (mono-color) |
| `PN` + `4`''''' | Reaction Effect 6 | Single-line Wave (multi-color) |
| `PN` + `4`'''''' | No Effect | You've cycled through all the effects |

### Pok3r Static Presets (Entire Keyboard)

| Combination | Name | Remarks |
| ------------ | --- | ---|
| `PN` + `5` | Full Mono-color | Lit with a single color |
| `PN` + `5`' | Breathing | LEDs will "breathe" (multi-color) |
| `PN` + `5`'' | Color Wheel | LEDs will "spin" (multi-color) |
| `PN` + `5`''' | Rainbow Raindrops | LEDs will light up like raindrops hitting the keyboard (multi-color) |

### Pok3r Custom Presets (Entire Keyboard)

You have to ability to create and store a 2 custom color profiles. The first profile can change the LED for each *key*. The second profile will only change LEDs for each *row*.

| Combination | Name | Remarks |
| ------------ | --- | ---|
| `PN` + `9` | Recording 1 |
| `PN` + `0` | Recording 2 |
| `PN` + `- _` | Play Recording 1 | |
| `PN` + `= +` | Play Recording 2 | |

1. `PN` + `9` (or `0`) to start recording. The menu key will light up white when "recording".
2. Use `PN` + `ESC` to load the color palette. Select a color.
3. Press keys you want that color to be under.
4. You can use other colors by going back to step 2.
5. `PN` + `9` (or `0`) to save. The menu key LED will shut off.
6. `PN` + `- _` (or `= +`) to use that profile.