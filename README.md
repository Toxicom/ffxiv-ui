[![ToxiUI](https://i.imgur.com/S5a4FCi.png)](https://toxiui.com)
# ToxiUI FFXIV UI

For full guide please see https://toxiui.com/ffxiv-ui-guide/

## Table of Contents
- [Assets](#assets)
   - [Fonts](#fonts)
   - [Textures](#textures)
- [Import strings](#import-strings)
- [DelvCD Profile Status](#delvcd-profile-status)
   - [Tank](#tank)
   - [Melee DPS](#melee-dps)
   - [Physical Ranged DPS](#physical-ranged-dps)
   - [Magical Ranged DPS](#magical-ranged-dps)
   - [Healer](#healer)
- [How to import](#how-to-import)
   - [DelvUI](#delvui)
   - [DelvCD](#delvcd)
   - [LMeter](#lmeter)

## Assets
ToxiUI FFXIV UI profile requires custom assets not already included with DelvUI/DelvCD.

### Fonts
- The ToxiUI font can be downloaded from [this repository](https://github.com/Toxicom/ffxiv-ui/blob/main/assets/fonts/ToxiUI.ttf)
![image](https://github.com/Toxicom/ffxiv-ui/assets/69549795/6c2de83b-a6c0-4821-9a47-70f70e6b1861)
- The Monsterrat (Black/900) font can be downloaded from multiple sources:
   - [Google Fonts](https://fonts.google.com/specimen/Montserrat) (recommended)
   - Or from [this repository](https://github.com/Toxicom/ffxiv-ui/blob/main/assets/fonts/Montserrat-Black.ttf)

### Textures
- The ToxiUI texture can be downloaded from [this repository](https://github.com/Toxicom/ffxiv-ui/blob/main/assets/textures/ToxiUI.png)
![image](https://github.com/Toxicom/ffxiv-ui/assets/69549795/3c2f3b17-f166-4dd1-8c06-6da3f4b29c50)

## Import strings
In this repository you can also find [import strings](https://github.com/Toxicom/ffxiv-ui/tree/main/import-strings)

- [DelvUI Profile](https://github.com/Toxicom/ffxiv-ui/blob/main/import-strings/DelvUI.txt)
- [DelvCD Profile](https://github.com/Toxicom/ffxiv-ui/blob/main/import-strings/DelvCD.txt)
- [LMeter Profile](https://github.com/Toxicom/ffxiv-ui/blob/main/import-strings/LMeter.txt)

## DelvCD Profile Status
* ✅ - Ready for gameplay testing
* 🟠 - WIP
* ❌ - Haven't started

### Tank
| Status | Job | Notes |
| --- | --- | --- |
| ✅ | DRK | N/A |
| ✅ | PLD | N/A |
| 🟠 | WAR | Not max level, not entirely sure what's important |
| 🟠 | GNB | Not max level, not entirely sure what's important |

### Melee DPS
| Status | Job | Notes |
| --- | --- | --- |
| ❌ | MNK | The most confusing job ever, no idea |
| ✅ | DRG | Only Lv 80, so auras will be up to that threshold |
| ✅ | NIN | N/A |
| ✅ | SAM | N/A |
| ❌ | RPR | The way I envision it might be difficult to achieve due to missing DelvCD features |

### Physical Ranged DPS
| Status | Job | Notes |
| --- | --- | --- |
| 🟠 | BRD | Can't finish due to missing DelvCD features |
| ❌ | MCH | The job I'll level last, probably |
| ❌ | DNC | See MCH |

### Magical Ranged DPS
| Status | Job | Notes |
| --- | --- | --- |
| ✅ | BLM | N/A |
| ✅ | SMN | Not max level yet |
| ✅ | RDM | N/A |
| ❌ | BLU | lol |

### Healer
I despise healing, so these will be the last ones and even then not sure if I'll make them. Let's call Healer profiles community-dependant 😳

| Status | Job | Notes |
| --- | --- | --- |
| 🟠 | WHM | Handled by FrontierPsychiatrist |
| 🟠 | SCH | Handled by FrontierPsychiatrist |
| 🟠 | AST | Handled by FrontierPsychiatrist |
| 🟠 | SGE | Handled by FrontierPsychiatrist |

## How to Import
### DelvUI

To open DelvUI settings, in the game chat type `/dui`. If the command does not work, ensure you have the plugin installed.

1. Open DelvUI settings
2. Create a new profile:
   1. Go to **Profiles**
   2. Enter a **Profile Name**
   3. Press **Copy**
3. Import fonts:
   1. Go to **Customization**
   2. Select the **Fonts** tab
   3. Click the Folder icon ![image](https://github.com/Toxicom/ffxiv-ui/assets/69549795/c76833e4-04f7-4de3-9585-4a8b3808d687)
   4. When the folder opens, extract the fonts you downloaded in that folder
      - **NOTE:** Currently there's a bug in DelvUI, so all of your assets must be directly in that specified place (by default it should be `C:\`)
   5. Go back in to the game
   6. Hit the Refresh button ![image](https://github.com/Toxicom/ffxiv-ui/assets/69549795/abccd1a8-460c-4e40-8b9b-63e48945ca4c)
   7. Select the font, it's size, and hit the Plus button ![image](https://github.com/Toxicom/ffxiv-ui/assets/69549795/13149fef-32e6-4fc4-af10-5b0cecaa9cde)
      - For ToxiUI profile you need these fonts:
         - Montserrat-Black 20
         - Montserrat-Black 24
         - ToxiUI 10
         - ToxiUI 12
         - ToxiUI 14
         - ToxiUI 16
![image](https://github.com/Toxicom/ffxiv-ui/assets/69549795/deb2eb15-b07a-4de6-a0b6-3c63fb39a505)
4. Import the textures:
   1. Go to **Customization**
   2. Select the **Bar Textures** tab
   3. Click the Folder icon ![image](https://github.com/Toxicom/ffxiv-ui/assets/69549795/c76833e4-04f7-4de3-9585-4a8b3808d687)
   4. When the folder opens, extract the textures you downloaded in that folder
      - **NOTE:** Currently there's a bug in DelvUI, so all of your assets must be directly in that specified place (by default it should be `C:\`)
6. Import the profile:
   1. Go to **Import**
   2. Paste the [DelvUI Profile string](https://github.com/Toxicom/ffxiv-ui/blob/main/import-strings/DelvUI.txt) in the text field
   3. Press **Import**
   4. Select which modules you want and confirm

### DelvCD

To open DelvCD settings, in the game chat type `/dcd`. If the command does not work, ensure you have the plugin installed.

1. Open DelvCD settings
2. Import fonts:
   1. Go to **Fonts**
   2. Click the copy icon to copy path ![image](https://github.com/Toxicom/ffxiv-ui/assets/69549795/1b283a79-d6ba-491a-af57-4114feea6924)
   3. Open that path in your file system
   4. When the folder opens, extract the fonts you downloaded in that folder
   5. Go back in to the game
   6. Hit the Refresh button ![image](https://github.com/Toxicom/ffxiv-ui/assets/69549795/abccd1a8-460c-4e40-8b9b-63e48945ca4c)
   7. Select the font, it's size, and hit the Plus button ![image](https://github.com/Toxicom/ffxiv-ui/assets/69549795/13149fef-32e6-4fc4-af10-5b0cecaa9cde)
      - For ToxiUI profile you need these fonts:
         - ToxiUI 12
         - ToxiUI 14
         - ToxiUI 16
         - Montserrat-Black 24
         - Montserrat-Black 20
3. Copy the [DelvCD Profile string](https://github.com/Toxicom/ffxiv-ui/blob/main/import-strings/DelvCD.txt)
4. In the **Elements** tab press the Import button
![image](https://github.com/Toxicom/ffxiv-ui/assets/69549795/821b51c7-ba9b-45d1-b108-6db7215eab2c)

### LMeter

![image](https://github.com/Toxicom/ffxiv-ui/assets/69549795/f9721b0b-d533-4ffd-b304-210c154c4bde)


To open LMeter settings, in the game chat type `/lm`. If the command does not work, ensure you have the plugin installed.

⚠️ **IMPORTANT:** Make sure you have the LMeter by [joshua.software.dev](https://gitlab.com/joshua.software.dev/LMeter)

1. Open LMeter settings
2. Import fonts:
   1. Go to **Fonts**
   2. Click the copy icon to copy path ![image](https://github.com/Toxicom/ffxiv-ui/assets/69549795/1b283a79-d6ba-491a-af57-4114feea6924)
   3. Open that path in your file system
   4. When the folder opens, extract the fonts you downloaded in that folder
   5. Go back in to the game
   6. Hit the Refresh button ![image](https://github.com/Toxicom/ffxiv-ui/assets/69549795/abccd1a8-460c-4e40-8b9b-63e48945ca4c)
   7. Select the font, it's size, and hit the Plus button ![image](https://github.com/Toxicom/ffxiv-ui/assets/69549795/13149fef-32e6-4fc4-af10-5b0cecaa9cde)
      - For ToxiUI profile you need these fonts:
         - ToxiUI 12
         - ToxiUI 14
3. Copy the [LMeter Profile string](https://github.com/Toxicom/ffxiv-ui/blob/main/import-strings/LMeter.txt)
4. In the **Profiles** tab press the Import button

![image](https://github.com/Toxicom/ffxiv-ui/assets/69549795/72ae2fa6-6134-4095-832b-8735ef7b7b48)
