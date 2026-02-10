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

### General

| Key | Action |
|-----|--------|
| **Tab** | Cycle forward through screens (Combat → Heroes → Stats → Achievements) |
| **Enter** | Activate / confirm current selection |
| **Escape** | Go back / close popup |
| **F10** | Toggle between Screen Reader and SAPI speech output |

### Combat

| Key | Action |
|-----|--------|
| **Space** | Click on monster (attack) |
| **Left Arrow** | Previous zone |
| **Right Arrow** | Next zone |

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

### Hero Screen

| Key | Action |
|-----|--------|
| **Page Up / Page Down** | Navigate through hero list |
| **Shift+Page Up / Shift+Page Down** | Jump 10 heroes |
| **Left Arrow / Right Arrow** | Navigate buttons on current hero |
| **L** | Hire, level up, or purchase upgrades for the selected hero |
| **U** | Toggle upgrade navigation mode for the selected hero |

### Upgrades (U Mode)

| Key | Action |
|-----|--------|
| **U** | Enter/exit upgrade mode for the current hero |
| **Page Up / Page Down** | Browse upgrades |
| **Enter** | Purchase the selected upgrade |

### Skills

| Key | Action |
|-----|--------|
| **K** | Toggle skill navigation mode |
| **Page Up / Page Down** | Navigate between skills (in skill mode) |
| **Enter** | Activate selected skill (in skill mode) |

### Achievements

| Key | Action |
|-----|--------|
| **Up Arrow / Down Arrow** | Navigate achievements in the current list |
| **Left Arrow / Right Arrow** | Switch between unclaimed and claimed achievement lists |
| **Enter** | Claim reward for the selected achievement |

### Shop

| Key | Action |
|-----|--------|
| **R** | Announce ruby count |
| **H** | Show shop help / ruby info |
| **B** | Open gold-to-ruby conversion popup |
| **Left Arrow / Right Arrow** | Adjust sliders in popups |

---

## Known Issues

- Sound effects may not always play as expected. Some audio cues may be missing, delayed, or fail to trigger in certain situations.

---

## DLC Support

Clicker Heroes has several paid DLC packs on Steam. Each DLC provides one Auto Clicker unit (a gameplay item that automates clicking) with a unique cosmetic skin. The DLCs do not add new game mechanics, heroes, or zones — just auto-clickers with skins.

All DLC code and assets are included in the base game files regardless of purchase. The mod's existing auto-clicker skin selection popup is already accessible, announcing skin names, owned/locked status, and which skin is equipped. No additional purchase is required for the mod to work with DLC content.

---

### Don't Have the Game?

Clicker Heroes is free to play! Add it to your Steam library here:

[Clicker Heroes on Steam](https://store.steampowered.com/app/363970/Clicker_Heroes/)
