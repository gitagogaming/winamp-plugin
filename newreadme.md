# Touch Portal Winamp/WACUP Integration
![image](https://github.com/user-attachments/assets/285185e4-bbf5-4cbb-8898-b8b584434589)

## Table of Contents
- [How to Install Touch Portal](#how-to-install-touch-portal)
- [Prerequisites](#prerequisites)
- [Installation Instructions](#installation-instructions)
- [Set Up Winamp/WACUP Page](#set-up-winampwacup-page)
- [Screen Icon Setup](#screen-icon-setup)
- [Creating a Playlist](#creating-a-playlist)
- [Possible Errors](#possible-errors)
- [Features](#features)
- [Credits](#credits)

---

## How to Install Touch Portal

1. **Purchase and install Touch Portal Pro.**
2. **Download and install the latest WACUP:** [WACUP Download](https://getwacup.com/).
3. **Download and install the latest "Winamp / WACUP" Plug-in:** [GitHub Plugin](https://github.com/gitagogaming/winamp-plugin).
4. **Download the Winamp/WACUP Touch Portal Page:** Place it in an easily accessible folder and extract it.
5. **Configure Media Files:** After installing WACUP, ensure that your media files are opened with WACUP. Right-click on any media file (e.g., .mp3, .m3u), select "Properties," and in the "General" tab, click "Change" next to "Opens with." Choose WACUP from the list or browse to `C:\Program Files (x86)\WACUP\wacup.exe`.

---

## Prerequisites

- Touch Portal Pro upgrade purchased and installed.
- Download and install the latest WACUP: [WACUP Download](https://getwacup.com/).
- Download and install the latest "Winamp / WACUP" Plug-in: [GitHub Plugin](https://github.com/gitagogaming/winamp-plugin).
- Download the Winamp/WACUP Touch Portal Page and place it in an accessible folder. Extract the folder.
- Configure your media files to open with WACUP (as detailed above).

---

## Installation Instructions

- Open the Touch Portal main interface.
- Click on the gear icon at the top middle of the page.
- Select "Import Page..." from the pop-up menu.
- Navigate to the folder where you downloaded and extracted the Winamp/WACUP Touch Portal page, and select the `.tpz2` file.
- Click "Import" on the bottom right of the window, then "OK" on the confirmation pop-up.
- When prompted to open the imported page, click "No" to stay on the Main page.

---

## Set Up Winamp/WACUP Page

- Navigate to the desired location (e.g., "Main" page).
- Click on an empty button location to open the "Edit Control Screen."
- Under the "Button Image" tab, select "from file..." and choose the `winamp.png` file from the downloaded folder.
- In the "Search" box, type "go to page" and select "Go To Page" from the results.
- In the "On Pressed" tab, select "winamp" from the drop-down menu.
- Click "Apply," then "Save & Close."

---

## Screen Icon Setup

- On the Winamp page, there may be a bug preventing the slider image from displaying after importing. 
- To fix this, click on the slider (horizontal black bar), open the "Edit Control Screen," and select the `slider.png` file.
- Click "Apply" and then "Save & Close." If the slider still doesn’t show, restart Touch Portal.
- For the Winamp logo, navigate to where WACUP is installed and select `wacup.exe` in the "Start Application" action. Click "Apply" and "Save & Close."
- To add playlists to PL1, PL2, PL3, and PL4, select a PL button and navigate to your playlist location.

---

## Creating a Playlist

- In WACUP, open the "Playlist Editor" and add your songs and radio stations.
- Click "LIST OPTS" in the bottom right corner of the "Playlist Editor."
- In the pop-up, select "Save playlist..." and choose the desired file location and name.

---

## Possible Errors

- If buttons (Play, Stop, etc.) do not work, ensure the "Winamp / WACUP" Plug-in is correctly installed.
- Check the "Quick Actions" button and select "Import plug-in..." if needed.
- The "Select File" button may not work for everyone initially. To resolve this, try selecting a different button that performs similar actions.

---

## Features

- Display current and remaining track play times.
- Display track titles.
- Positional track seeking slider.
- Function buttons: Previous, Play, Pause, Stop, Next, Open File, Shuffle, Repeat.
- Four different playlist buttons.
- Preset Winamp/WACUP volume control.
- Preset system volume control.
- Press and hold volume up and down buttons for quick adjustments.
- Shuffle, Repeat, and Playlist buttons have "Button Selected" indicators.

---

## Credits

Thanks to the developers at the Llama Group for creating Winamp and the developer behind WACUP for enhancing it. Special thanks to Gitago for providing the Winamp Plug-in and guides that made this integration possible.

---
