# CURLING TIMER


---
## Overview
### Description
Curling Timer is a desktop application built with Electron for timekeeping curling games. The application operates entirely offline and is designed for use on laptops, desktops, and touchscreen devices.


Timer states are automatically preserved locally, allowing rapid recovery after accidental closure, application crashes, or system interruptions. A dedicated display mode allows timers to be shown on a secondary monitor while controls remain available on the primary display.


The primary goal is to provide an intuitive interface that minimizes mistakes, tracks game events, and provides reliable operation regardless of internet availability or operating system.


---

### Setup
#### Install 
``npm install``

#### Run
``npm start``

#### Build
``npm build``




## Features
### Game Management
- End tracking
- Hammer tracking
- Time tracking
- Event logging
- In-Game notes
- Preset game configurations

### Recovery and Persistence
- Automatic save after every timer state change
- Session recovery after application restart
- Crash recovery
- Local game archive storage
- Export game summaries


---

## Project Conventions

### Git Branch Naming
|`git branch` <`NAME`> |Description |
|--------------------- |----------- |
|`main`                | main branch, merge into when milestone is complete, stable|
|`dev`                 | primary development branch, merge into when feature is complete, unstable |
|`<TYPE>/<FEATURENAME>`| individual feature development, <br><br> types: `feature`, `fix`, `update`, `dropped` |

### Commit Symbology
| Char |Description|
|------|-----------|
| `⦿` | Normal Commit Node |
| `⩤` | Merge Branch |
| `⩥` | New Branch |
| `※` | Note (Empty Commit) |
| `⟁` | Problem or Concern |

### File Folder Architecture
**Note**: Folders are plural, files are singular. 

Characters: `|` `├─` `└─` `←`

```
curlingtimer/
|
├─ README.md
├─ package.json
├─ package-lock.json
├─ .gitignore
|
├─ src/
|  ├─ index.html
|  ├─ *.html
|  |
|  ├─ styles/
|  |  ├─ values.css       ← layout values
|  |  ├─ default.css
|  |  |
|  |  └─ *.css
|  |
|  ├─ scripts/
|  |  ├─ main.js
|  |  ├─ preload.js
|  |  ├─ *.js
|  |  |
|  |  ├─ utils/
|  |  |  ├─ 
|  |  |  ├─ 
|  |  |  └─
|  |  |
|  |  └─ renderers/
|  |     ├─ 
|  |     ├─ 
|  |     ├─ shell.js
|  |     └─ home.js
|  |
|  └─ assets/
|    ├─ 
|    |
|    ├─ misc/
|    |
|    └─ icons/
|      ├─ 
|      └─
|
└─ local/
  ├─ userbase.json    ← user settings
  ├─ preset.json
  ├─ temp.json        ← current or most recent game file
  |
  └─ archive/
    ├─
    |
    └─
```


---



## Misc

### Credits and Contributions



