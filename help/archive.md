---
layout: default
title: Archive Manager
permalink: /help/archive
nav_order: 4
parent: Help
has_children: false
---

# Archive Manager

NOTE: Only install archives that you trust!
{: .label .label-yellow }

**We accept no responsibility for either the content of your archives or any loss of data or functionality as a result
of using this feature.**

The Archive Manager is located at `Applications > Archive Manager`
![](assets/images/archive.png)

## How does it work?

If it doesn't exist, you can create a folder named `ARCHIVE` in the root of `SD1, SD2, USB`   
Here you can place specially created archive manager `.muxzip` files.  
The archive manager will extract the contents of **any** `.muxzip` file, so it's important that they are created
correctly.

### Example

```
SD2
└── Archive
    ├── BIOS Files.muxzip
    ├── Retroarch Overrides.muxzip
    ├── Save Games.muxzip
    └── WiFi Config.muxzip
USB
└── Archive
    └── Box Art.muxzip
```

## How should I structure the Archive .zip files?

Each archive file extracts to / so this means you need to ensure that the archive contains the **Full Path** you wish to
extract to.

### Example

To create an archive of your muOS saves the zip should contain the complete file path.

```
mnt
└─ mmc
   └── MUOS
       └── save
           ├── file
           │   └── <core>
           │       └── <save files>
           └── state
               └── <core>
                   └── <save files>
```

SD1 root is `/mnt/mmc`   
SD2 root is `/mnt/sdcard`   
USB root is `/mnt/usb`

## What can I restore with this Archive Manager?

It's very flexible and can be used for pretty much anything.  
Simply create a `.muxzip` file with the correct path.

### Example

Want to backup and restore your favourite games? Go for it!

```
mnt/mmc/roms/Game Boy Color/Opossum Country.zip
```

Want to share your latest Pokemon save with a friend? No problem!

```
run/muos/global/save/file/gpSP/Pokemon Emerald.srm
```
