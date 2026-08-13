# WinMonitor 1.1

WinMonitor 1.1 introduces per-disk drive selection, taskbar & window title refinements, and dependency updates.

## Features
- **Real-Time Data:** View CPU%, RAM%, GPU%, network speeds (Upload/Download), and per-drive disk performance active times.
- **Drive Selection System:** Enable or disable individual disk drives (e.g. show only `D:`) from the **Select Disks** context menu.
- **Customizable Visibility:** Toggle individual modules (CPU, RAM, Disk, GPU, Network) on/off directly from the right-click context menu.
- **Always on Top & Draggable:** Drag to position anywhere. Auto-resizes from the left side, keeping the right edge fixed.
- **Temperature Monitoring:** Displays CPU package and GPU core temperatures.
- **Auto-Run:** "Startup App" toggle available in the context menu.
- **Configuration Persistence:** Settings are saved locally to `winmonitor_config.json` and persist across runs.
- **Lightweight:** Minimal CPU and RAM footprint.

## What's New in v1.1
- **Per-Disk Toggle System:** Added a **Select Disks** submenu allowing users to filter which physical drives/partitions (e.g. `C:`, `D:`) are monitored and displayed.
- **Taskbar & Window Title Fixes:** Set explicit window title to "WinMonitor" and forced taskbar window style refresh (`WS_EX_TOOLWINDOW`) to eliminate taskbar buttons and prevent "tk" labels.
- **Renamed Auto-Run Toggle:** Renamed "Start with Windows" context menu item to **Startup App**.
- **GPU Deprecation Fix:** Updated NVML package dependency to `nvidia-ml-py` and suppressed import deprecation warnings.

## Installation
Download `WinMonitor.exe` attached to this release and run it directly. No installation is required.

*Released under the MIT License.*
