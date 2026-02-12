# Clicker Heroes Access

*Code written by Claude 4.6 Opus (Max subscription).*

A [MelonLoader](https://github.com/LavaGang/MelonLoader) mod that adds screen reader accessibility to [Clicker Heroes](https://store.steampowered.com/app/363970/Clicker_Heroes/) on Steam.

## Installation

There are two ways to install this mod: **automatic** (recommended) or **manual**.

---

### Automatic Installation (Recommended)

Use the **ClickerHeroesAccessPatcher** — a standalone installer that handles everything for you.

1. Download **ClickerHeroesAccessPatcher.exe** from the [ch_patcher releases page](https://github.com/ShotgunSpoon/ch_patcher/releases/latest).
2. Run the exe.
3. The installer will ask for your Clicker Heroes install folder. The default is:
   ```
   C:\Program Files (x86)\Steam\steamapps\common\Clicker Heroes
   ```
   If your game is installed elsewhere, see [Finding Your Install Folder](#finding-your-install-folder) below.
4. Click **Patch Clicker Heroes**.
5. If MelonLoader is not installed, the patcher will download and launch the MelonLoader installer for you. Follow the prompts in the MelonLoader installer, then close it.
6. The patcher will download the latest mod DLL and place it in the correct folder automatically.
7. Launch Clicker Heroes through Steam. Done!

---

### Manual Installation

If you prefer to install everything yourself:

#### Step 1: Install MelonLoader

1. Download the MelonLoader installer from the [MelonLoader v0.6.6 release page](https://github.com/LavaGang/MelonLoader/releases/tag/v0.6.6).
2. Run **MelonLoader.Installer.exe**.
3. In the installer, click the file/folder icon and browse to your Clicker Heroes install folder. Select **Clicker Heroes.exe**.
4. Click **Install**.
5. Close the MelonLoader installer.

#### Step 2: Install the Mod

1. Download **ClickerHeroesAccess.dll** from the [latest release](https://github.com/ShotgunSpoon/ch_access/releases/latest).
2. Navigate to your Clicker Heroes install folder.
3. Open the **Mods** folder. If it doesn't exist, create it.
4. Copy **ClickerHeroesAccess.dll** into the **Mods** folder.
5. Launch Clicker Heroes through Steam.

---

### Finding Your Install Folder

If you don't know where Clicker Heroes is installed:

1. Open **Steam**.
2. Go to your **Library**.
3. Right-click **Clicker Heroes** and select **Properties**.
4. Click the **Installed Files** tab.
5. Click **Browse**.
6. This opens the folder where the game is installed. Copy the path from the address bar.

The default Steam install path is:
```
C:\Program Files (x86)\Steam\steamapps\common\Clicker Heroes
```

---

## Controls

All screens use standard navigation: **Up/Down** or **Page Up/Page Down** to browse lists, **Left/Right** to switch sub-lists or adjust sliders, **Enter** to activate or confirm, **Escape** to go back or close.

### Navigation

| Key | Action |
|-----|--------|
| **Tab / Shift+Tab** | Cycle through screens (Combat → Heroes → Ancients → Outsiders → Stats → Achievements) |
| **T** | Cycle level scale for the current tab (x1, x10, x25, x100, etc.) |
| **F10** | Toggle between Screen Reader and SAPI speech output |

### Combat

| Key | Action |
|-----|--------|
| **Space** | Click on monster (attack). With Engine Clicker purchased, hold Space for max-speed clicking. |
| **Left Arrow / Right Arrow** | Navigate zones |
| **C** | Collect clickable (treasure chest, orange fish) on screen. Press repeatedly for floaters. |

### Information

| Key | Action |
|-----|--------|
| **G** | Announce current gold |
| **S** | Announce stats (DPS, click damage) |
| **Z** | Announce zone info |
| **H** | Announce enemy health |
| **I** | Announce current item/hero info |
| **O** | Announce hero list summary |
| **R** | Read current screen content |
| **Shift+R** | Announce ruby count from anywhere |

### Heroes

| Key | Action |
|-----|--------|
| **L** | Hire, level up, or purchase upgrades for the selected hero |
| **U** | Toggle upgrade navigation mode for the selected hero |
| **K** | Toggle skill navigation mode |
| **B** | Buy all available upgrades |

### Panels

| Key | Action |
|-----|--------|
| **Shift+G** | Open Gilded Heroes popup |
| **Shift+I** | Open Items/Relics popup |
| **Shift+M** | Open/close Mercenary navigation |

### Mercenaries (Shift+M to open)

| Key | Action |
|-----|--------|
| **N / Shift+N** | Navigate forward/backward through mercenaries |
| **Q** | Quest action: start quest (idle), revive (dead), or check status (on quest) |
| **Shift+Q** | Bury dead mercenary for gold reward |
| **F** | Collect completed quest reward |

### Relics (Shift+I to open Items popup)

| Key | Action |
|-----|--------|
| **Up / Down** | Browse relics (equipped first, then unequipped) |
| **Enter** | Equip or unequip the selected relic |
| **X / Delete** | Salvage the selected relic for forge cores |
| **Shift+J** | Salvage all unequipped (junk) relics |

### Progression

| Key | Action |
|-----|--------|
| **A** | Check ascension progress (hero souls to gain, zone info) |
| **Ctrl+A** | Ascend (open ascension confirmation) |
| **Shift+T** | Check transcension progress (ancient souls, transcendent power) |
| **Ctrl+T** | Transcend (open transcension confirmation) |

### Shop

| Key | Action |
|-----|--------|
| **R** | Announce ruby count |
| **H** | Show shop help / ruby info |
| **B** | Open gold-to-ruby conversion popup |

---

## Ruby Shop Upgrades

The mod adds a progression of game-altering upgrades to the ruby shop. These unlock in order — each upgrade appears after the previous one is purchased.

| Upgrade | Cost | Effect |
|---------|------|--------|
| **Instant Spawn** | 5,000 rubies | Removes the 0.5s delay between monster spawns. Monsters appear immediately. |
| **Instakill Chain** | 7,500 rubies | Overflow damage carries to the next monster, chaining kills through weaker enemies. |
| **Engine Clicker** | 10,000 rubies | Hold Space for max-speed clicking (~3000+ clicks/sec) instead of one click per press. |
| **DPS Multiplier** | 500+ rubies (stackable) | Each purchase doubles all damage. Cost increases by 500 per purchase (500, 1000, 1500...). |

All purchases are saved in your game save file and sync with Steam Cloud.

---

## Known Issues

- Sound effects may not always play as expected. Some audio cues may be missing, delayed, or fail to trigger in certain situations.

---

## DLC Support

Clicker Heroes has several paid DLC packs on Steam. Each DLC provides one Auto Clicker unit (a gameplay item that automates clicking) with a unique cosmetic skin. The DLCs do not add new game mechanics, heroes, or zones — just auto-clickers with skins.

The mod's existing auto-clicker skin selection popup is already accessible, announcing skin names, owned/locked status, and which skin is equipped.

---

### Don't Have the Game?

Clicker Heroes is free to play! Add it to your Steam library here:

[Clicker Heroes on Steam](https://store.steampowered.com/app/363970/Clicker_Heroes/)
