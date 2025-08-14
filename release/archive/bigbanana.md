---
layout: default
title: 2410.2 BIG BANANA
permalink: /release/archive/bigbanana
parent: Archive
grand_parent: Release
nav_order: 1
has_toc: false
---

# MustardOS 2410.2 BIG BANANA

#### _Pronunciation_
/bɪɡ bəˈnæn.ə/

## Download Full Image

[Download from Gofile](https://gofile.io/d/bkHtf2){: .btn .btn-primary .fs-5 .mb-4 .mb-md-0 .mr-2 .text-grey-dk-300 }
[Download from MEGA](https://mega.nz/folder/gvpxmRST#lCTnrq90MnQOB_L2QEfOpw){: .btn .fs-5 .mb-4 .mb-md-0 }

## Download Update Only

[Download from Gofile](https://gofile.io/d/PyspvT){: .btn .btn-primary .fs-5 .mb-4 .mb-md-0 .mr-2 .text-grey-dk-300 }
[Download from MEGA](https://mega.nz/folder/MzhHVIoC#4imi8wesThvpqLK6jhxojg){: .btn .fs-5 .mb-4 .mb-md-0 }

{: .highlight }
> If you have alternative storage support please reach out to @xonglebongle on the MustardOS Community Discord server!
>
> So everybody is aware, MEGA has restrictions on certain countries and places a download limit. Use either Gofile or
> the Torrents if you cannot use MEGA. And for goodness sake we are **not** moving to a paid subscription like some
> people might be thinking.  _The absurdity..._

## Support MustardOS

Love MustardOS? Want to help us on this **crazy** journey? Here's how to get involved.

**This can be done a few ways:**

- Be helpful around the Discord community server
- [Contribute code directly to our GitHub repositories](https://github.com/MustardOS)
- Spread the word about MustardOS and all its features

**Or you can join the testing crew directly by:**

- Supporting us via Ko-fi subscription
- Boosting the Discord community server

## Important

{: .highlight }
> The update requires you to already have 2410.1 BANANA already setup and installed on your device.
>
> Using modified MustardOS installations or previous versions may have strange or breaking outcomes.
>
> You can download the full image from the links above and start fresh!

## Contributors

- achillespdx
- antiKk
- bcat
- Bitter_Bizarro
- duncanyoyo1
- gordenfreemant
- harryarry
- ikaruga921196
- illumini_85
- j0tt
- joyrider3774
- koolkidkorey
- \_\_krt\_\_
- mardeoli
- mattyj513
- nmqanh
- roastbean
- xonglebongle

## Changes

- Added ability to directly load search from content root
- Added ability to use specific fonts, images, and schemes based on device resolution
- Added additional catalogue directories
- Added additional controller profiles
- Added additional navigation sounds: `keypress.wav` (_OSK_), `error.wav`, and `muos.wav` (_?_)
- Added async audio option for specific navigation block sounds
- Added audio overdrive support
- Added Beetle GBA core to Gameboy Advance system
- Added binary size check for Syncthing
- Added catalogue priority image loader for applications, archives, and tasks
- Added column mode to advanced box art config
- Added controller support for DPADs that register as buttons
- Added custom lookup table support
- Added DAT extension to `skip.ini` file
- Added device specific RetroArch overrides on default configuration
- Added device variable to indicate RGB support
- Added Diagnostics script to task toolkit
- Added "Display Empty Folder" visual option
- Added DPAD Swap variable for hotkey listener
- Added external Flycast directories
- Added fade to black animation support
- Added favourites and history modules to use internal name lookup table
- Added formatted script logging system
- Added friendly file lookup for search results
- Added function to load grid muxlaunch images through muxlaunch folder
- Added GBA overlays
- Added grid panel theme support to `muxapp`, `muxlaunch` and `muxplore`
- Added Hebrew, Irish, and Persian languages
- Added hidden SSID network connection support
- Added INI assign files for MegaDuck and Sega Pico systems
- Added `LIST_*_GRADIENT_DIRECTION` support to the `[list]` section of theme schemas
- Added kiosk mode support
- Added lookup (_and reverse lookup_) module dependency for frontend
- Added Mednafen PCE core to SuperGrafx system
- Added menu controller support
- Added migrate and sync scripts for storage module
- Added missing HDMI audio `userdata` field
- Added missing make inclusion for `muhotkey`
- Added MPV player
- Added mReader application for general content launching
- Added network wait for web services before initialisation
- Added `pgm.zip` to skipped files
- Added PICO-8 Mouse Support
- Added PICO-8 Pixel Perfect Scaler
- Added progress bar support for `muxstart` module for first init setup
- Added RetroArch kiosk support mode
- Added script to save active theme as installable theme
- Added search content feature - Press `SELECT` on content and select search
- Added separate HDMI configuration module
- Added splash image on content launching support
- Added storage schedule option
- Added string extraction function
- Added support for controller profiles
- Added support for device specific theme previews
- Added support for disabling grid panel in `muxplore` with a `.nogrid` file
- Added support for displaying assigned core
- Added support for empty WiFi passwords
- Added support for theme specific BGM
- Added support for user defined custom packages for catalogue and RetroArch configurations
- Added support for user initialisation scripts
- Added system swap file to advanced settings
- Added Tailscale to Web Services
- Added task scripts to restore friendly names and themes
- Added tasks for saving current catalogue and RetroArch configurations
- Added theme support for boxart padding
- Added YabaSanshiro external core to SEGA Saturn system
- Added YabaSanshiro restore controls task
- Adjusted BGM script to play any valid audio file via `mpv`
- Adjusted default sound rate to 48000
- Bind all Pico-8 data to save folder
- Bind current device on startup
- Changed archive module to use collections
- Changed async sound for all modules
- Changed in-game working LED to be off on charge + sleep
- Changed Pipewire to use global configuration with realtime priority
- Changed SNES/SFC core to Snes9x as default
- Check for `skip.ini` on SD2 first on content search
- Consolidated grid mode input navigation handler
- Defaulted to `performance` governor for CD-i
- Disable drastic threaded 3D - [Drastic Link](https://drastic-ds.com/drastic_readme.txt)
  and [Reddit Link](https://old.reddit.com/r/EmulationOnAndroid/comments/1csvtic/pro_tip_do_not_use_the_multithreaded_renderer_in/)
- Disabled SDL blitter to fix YabaSanshiro flickering
- Enabled core option categories
- Enabled core updater with MustardOS core builder URL
- Enabled PICO-8 to respect modern/retro control flag
- Factored idle logic to common script and inhibited idle during `ffplay` video playback
- Fixed advanced artwork config for favourite and history box art display
- Fixed auto assign routine to avoid running on storage selection or content root
- Fixed BGM for device power and sleep states
- Fixed BGM loading logic
- Fixed BGM sleep state
- Fixed BGM state for applications
- Fixed bind mount typo for DraStic-Legacy
- Fixed boxart disappearing issue on search results
- Fixed content count display on explore content root
- Fixed content explorer previous directory location
- Fixed credit names and visual swap issue on friendly folder
- Fixed default BANANA theme layout
- Fixed default global configuration values
- Fixed DPAD stylus press on A button for drastic-trngaje
- Fixed drastic-trngaje slow stylus
- Fixed favourite and history deletion
- Fixed governor loading issue for favourites, history, and last load launch
- Fixed HDMI start stop logic
- Fixed icon alignment in `muxsearch` when using size to content
- Fixed inconsistent behaviour of scroll wrapping in interface options
- Fixed issue with customisation page defaulting to RetroArch Configurations
- Fixed issue with item text being displayed on main menu when using grid mode
- Fixed issue with searching root path
- Fixed issue with wrong game being selected from search
- Fixed kiosk temporary disable mode
- Fixed L1 and R1 glyphs in `muxtester`
- Fixed language setting for network configuration module
- Fixed low level brightness bug on sleep wake
- Fixed masked password issue for network configuration
- Fixed missing strings in translations
- Fixed muX element priority loading and improved wallpaper loading logic
- Fixed network options being shown when network disabled
- Fixed overlay image being applied twice
- Fixed overlay image priority
- Fixed package content deletion logic
- Fixed random selection double hit issue
- Fixed save and load hotkeys for RG35XX-PLUS and RG35XX-2024 devices
- Fixed ScummVM log directory
- Fixed search module holding on to box art
- Fixed skeleton directory path in RA config backup and removed RA config during factory reset
- Fixed theme preview alignment and GIF file lock issue when switching themes
- Fixed upper bound on random image range
- Fixed wallpaper and `muxtheme` preview
- Fully separated idle display and sleep timers
- Increase close-content timeout from 5s to 10s
- Increase upper bound on random image range
- Merged device-specific `input.sh` scripts into `hotkey.sh` configured via JSON
- Modified `fbpad` to accept background and foreground colouring via themes
- Modified module screen `userdata` to use module process name
- Modified screen refresh to accept wait value
- Modified skip entry file with wildcard suffix
- Moved BGM Kill function to general function script
- Moved boxart behind headers and footers
- Moved colour temperature to singular values
- Moved from cache JSON to internal lookup table
- Moved internal fallback theme to default directory
- Moved storage preference module to configuration module
- Moved to catalogue path define
- Optimised internal scripts
- Optimised item generation function
- Optimised lookup table functions
- Preserved empty directories and added progress bars during archive install
- Purged cache info directory
- Purged core specific name files in favour of internal lookup table
- Removed `evsieve` idle inhibitor
- Removed extra copy of default theme to avoid sync issues
- Removed global core auto assign options on directory change
- Removed `golden.sh` script
- Removed L3 Binding from devices without analogues
- Removed loading of network profile when network is active
- Removed naming of visible/hidden in favour of enabled/disabled
- Removed older MustardOS default themes
- Removed storage vars that are now unused
- Removed `sync_storage.sh` after storage mount updates
- Removed theme max item count
- Removed the temporary friendly name file after search results
- Removed unused input_disable function
- Renamed `/opt/muos/backup` to `/opt/muos/default` and documented restore script
- Renamed Video Player to Media Player
- Renamed web service processes
- Replaced Drastic with Drastic-trngaje
- Replaced `gotty` with `ttyd`
- Rework find script to search multiple storage paths
- Suppressed idle sleep while charging to ease file transfers
- Update controller profile name to include vendor and product id
- Updated assign to convert cache to lookup
- Updated collection to use natural sorting
- Updated extraction script to properly detect multi resolution theme files
- Updated grid panel to use panel font if available
- Updated grid panel width to be calculated off column width
- Updated languages
- Updated moonlight to use aarch64 `gptokeyb`
- Updated `muxplore` to default to SD1 if no content found
- Updated `muxsplash` to support screen resolutions
- Updated PPSSPP external emulator to 1.18.1
- Updated reader and gptk files for load/save state of files
- Updated RetroArch cheat archive
- Updated RetroArch configurations for all working systems
- Updated RetroArch cores
- Updated RetroArch overlays
- Updated supporter credits
- Updated Syncthing and Tailscale
- Updated theme overrides for radius and size
- Updated theme picker to support scrolling text
- Updated version format
