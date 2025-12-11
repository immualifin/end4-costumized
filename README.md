# End-4 Quickshell Customized

Customized Quickshell configuration based on [end-4/dots-hyprland](https://github.com/end-4/dots-hyprland).

## Changes from Default Configuration

### Bar (BarContent.qml)

- **Active Window** - Disabled (`visible: false`)
- **Resource Indicators** - Only shows CPU (RAM and Swap hidden)
- **Media Control** - Dynamic, only appears when media is playing
  - Title and artist hidden by default
  - Appears with slide animation when hovering over the music icon
- **Battery Indicator** - Moved to right indicator group (alongside volume, network, bluetooth)
- **Center Layout** - Resources/Media positioned separately from Clock and Workspaces to maintain bar symmetry

### Panel Families (shell.qml)

- **Waffle Panel** - Added `iiOverview` so Task View works in waffle panel family

### Applications (Config.qml)

- **Task Manager** - Uses `plasma-systemmonitor`

## Screenshot

*Add your bar screenshot here*

## Installation

1. Backup your existing Quickshell configuration
2. Clone this repository to `~/.config/quickshell/ii`
3. Reload Quickshell

```bash
# Backup
mv ~/.config/quickshell/ii ~/.config/quickshell/ii.backup

# Clone
git clone https://github.com/immualifin/end4-costumized.git ~/.config/quickshell/ii

# Reload Quickshell (or restart session)
```

## Dependencies

- [Quickshell](https://github.com/quickshell-mirror/quickshell)
- [Hyprland](https://hyprland.org/)
- `plasma-systemmonitor` (for Task Manager)

## Credits

- Original configuration: [end-4/dots-hyprland](https://github.com/end-4/dots-hyprland)
