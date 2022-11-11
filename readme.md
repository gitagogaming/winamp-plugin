
# Winamp-Plugin
- [Winamp Plugin](#Winamp-Plugin)
  - [Description](#description)
  - [Features](#Features)
    - [Actions](#actions)
        - [Category: Winamp](#tp.plugin.Winamp.mainactions)
    - [Connectors](#connectors)
        - [Category: Winamp](#tp.plugin.Winamp.mainconnectors)
    - [States](#states)
        - [Category: Winamp](#tp.plugin.Winamp.mainstates)
        - [Category: Track Details](#tp.plugin.Winamp.trackDetailsstates)
  - [Bugs and Support](#bugs-and-suggestion)
  - [License](#license)
  
# Description

This documentation generated for Winamp Plugin V103 with [Python TouchPortal SDK](https://github.com/KillerBOSS2019/TouchPortal-API).
# Features

## Actions
<details open id='tp.plugin.Winamp.mainactions'><summary><b>Category:</b> Winamp <small><ins>(Click to expand)</ins></small></summary><table>
<tr valign='buttom'><th>Action Name</th><th>Description</th><th>Format</th><th nowrap>Data<br/><div align=left><sub>choices/default (in bold)</th><th>On<br/>Hold</sub></div></th></tr>
<tr valign='top'><td>Audio Controls</td><td> </td><td>[1]</td><td><ol start=1><li>Type: choice &nbsp; 
Default: <b></b> Possible choices: ['Prev', 'Next', 'Play', 'Pause', 'Stop', 'Fadeout', 'Forward', 'Fast Foward 5s', 'Rewind', 'Rewind 5s', 'EQ']</li>
</ol></td>
<td align=center>No</td>
<tr valign='top'><td>Increase / Decrease volume</td><td> </td><td>[1] the Volume by [2]</td><td><ol start=1><li>Type: choice &nbsp; 
Default: <b>Raise</b> Possible choices: ['Raise', 'Lower', 'Set']</li>
<li>Type: number &nbsp; 
Default: <b>5</b> &nbsp; <b>Min Value:</b> -2147483648 &nbsp; <b>Max Value:</b> 100</li>
</ol></td>
<td align=center>Yes</td>
<tr valign='top'><td>Track Seeking</td><td> </td><td>Seek the Track [1]</td><td><ol start=1><li>Type: choice &nbsp; 
Default: <b>Raise</b> Possible choices: ['Forward', 'Rewind']</li>
</ol></td>
<td align=center>Yes</td>
<tr valign='top'><td>Set Repeat</td><td> </td><td>Set Repeat to [1]</td><td><ol start=1><li>Type: choice &nbsp; 
Default: <b></b> Possible choices: ['On', 'Off', 'Toggle']</li>
</ol></td>
<td align=center>No</td>
<tr valign='top'><td>Set Shuffle</td><td> </td><td>Set Shuffle to [1]</td><td><ol start=1><li>Type: choice &nbsp; 
Default: <b></b> Possible choices: ['On', 'Off', 'Toggle']</li>
</ol></td>
<td align=center>No</td>
</tr></table></details>
<br>

## Connectors
<details open id='tp.plugin.Winamp.mainconnectors'><summary><b>Category:</b> Winamp <small><ins>(Click to expand)</ins></small></summary><table>
<tr valign='buttom'><th>Slider Name</th><th>Description</th><th>Format</th><th nowrap>Data<br/><div align=left><sub>choices/default (in bold)</th></tr>
<tr valign='top'><td>Volume slider</td><td> </td><td>Control volume for [1]</td><td><ol start=1><li>Type: choice &nbsp; 
Default: <b>Winamp</b> Possible choices: ['Winamp']</li>
</ol></td>
<tr valign='top'><td>Volume slider</td><td> </td><td>Track Seeking for [1]</td><td><ol start=1><li>Type: choice &nbsp; 
Default: <b>Winamp</b> Possible choices: ['Winamp']</li>
</ol></td>
</table></details>
<br>

## States
<details id='tp.plugin.Winamp.mainstates'><summary><b>Category:</b> Winamp <small><ins>(Click to expand)</ins></small></summary>


| Id | Description | DefaultValue | parentGroup |
| --- | --- | --- | --- |
| .state.Winamp_Status | Winamp | Winamp.exe Status |  |   |
| .state.playingStatus | Winamp | Playing Status |  |   |
| .state.currentVolume | Winamp | Current Volume |  |   |
| .state.repeatStatus | Winamp | Repeat Status |  |   |
| .state.shuffleStatus | Winamp | Shuffle Status |  |   |
| .state.totalTracks | Winamp | Total Tracks |  |   |
</details>

<details id='tp.plugin.Winamp.trackDetailsstates'><summary><b>Category:</b> Track Details <small><ins>(Click to expand)</ins></small></summary>


| Id | Description | DefaultValue | parentGroup |
| --- | --- | --- | --- |
| .state.currentTrack.Title | Winamp | Current Track Title |  |   |
| .state.currentTrack.Length | Winamp | Current Track Length |  |   |
| .state.currentTrack.Playtime | Winamp | Current Track Time Playing |  |   |
| .state.currentTrack.TimeLeft | Winamp | Current Track Time Left |  |   |
</details>

<br>

# Bugs and Suggestion
Open an issue on github or join offical [TouchPortal Discord](https://discord.gg/MgxQb8r) for support.


# License
This plugin is licensed under the [GPL 3.0 License] - see the [LICENSE](LICENSE) file for more information.

