# XeCMD
### First of its kind CLI based Xbox 360 RTE tool.


## What Is XeCMD?
XeCMD is a hacked Xbox 360 RTE (Real Time Editing) JRPC/XBDM based command line tool, for use with RGH/JTAG/BU/DevKit Xbox 360 consoles. This is good for people who want 'minimalization'. This is the first of it's kind command line based RTE tool for Xbox 360 consoles. XeCMD is set and ready to go immediatly upon launch. You do not need to have your console set as default in Xbox 360 Neighborhood, as you can connect via the consoles local ip address so long as you have XBDM setup on your Xbox 360 console.

I will be open sourcing XeCMD in the near future, as for now however, I want to wait until I am satisfied with the smoothness and the operational aspect of XeCMD, including adding many more commands in the future. Until then, for now XeCMD will not be open sourced at this current time.

![XeCMD V1.4.72-Beta](https://i.imgur.com/mhPJa4H.png)

## Requirments
- A Hacked Xbox 360/Devkit Xbox 360 Console
- Visual Studio 2010 (Required For Xbox 360 Neighborhood) [https://archive.org/details/dev-microsoft-visual-studio-2005-2015-Pro/]
- Xbox 360 SDK W/ Neighborhood (Latest SDK Version) [https://www.mediafire.com/file/oo761qxqbd6rczo/XBOX360+SDK+21256.8.exe]
- XBDM.xex [https://www.sendspace.com/file/qns1vg]
- JRPC2.xex [https://www.mediafire.com/file/omsbks5l6h1d9mo/JRPC2.xex/file]

XeCMD is setup with quite a few commands at launch. I will be adding many more in future updates as time goes on, but for now this is what XeCMD is loaded with as of V1.4.72 Public Release Beta Candidate.

*Commands*
- connect                            - Connect to the default console
- connectip [IP]                     - Connect to console via local ip
- readtemps                          - Reads current consoles hardware tempatures
- shutdown                           - Shutdown the connected console
- reboot                             - Reboot the connected console
- wreboot                            - Warm reboot the connected console
- setfanspeed [#]                    - Sets console fan speed
- runxex [.XEX/.XBE DIR]             - Launches selected executable file
- cpukey                             - Displays connected consoles cpu key
- getlaunchini [FILEOUTPUT][INIDIR]  - Retrieves launch.ini from console
- sendlaunchini [FILEDIR][OUTPUT]    - Sends launch.ini to console
- getjrpcini [FILEOUTPUT][INIDIR]    - Retrieves jrpc.ini from console
- sendjrpcini [FILEDIR][OUTPUT]      - Sends jrpc.ini to console
- opendisc                           - Opens disc tray
- closedisc                          - Closes disc tray
- readtitle                          - Reads current executable title id (if applicable)
- restitle                           - Restarts the currently active title
- getgt                              - Show current signed in gamertag
- spoofgt [GT]                       - Spoofs current gamertag
- notify [TEXT]                      - Sends entered notification to console
- msgbox [TITLE] [BODY] [BTN]        - Sends entered message box to console
- spoofgold                         - Spoofs XBL gold status for multiplayer games
- spoofmsp                            - Spoofs MS store points for purchases
- getname                            - Show the console name
- redpower                           - Sets power light to red (Slims Only)
- greenring                          - Sets ROL ring to green
- redring                            - Sets ROL ring to red (Fat Only)
- orangering                         - Sets ROL ring to orange (Fat Only)
- rrodring                           - Sets ROL ring to fake red ring of death (Fat Only)
- linuxring                          - Sets ROL ring to linux theme (Fat Only)
- xmasring                           - Sets ROL ring to xmas theme (Fat Only)
- help                               - Show this help message
- checkgt [GAMERTAG]                 - Checks if GamerTag is available for use
- exit                               - Quits XeCMD
