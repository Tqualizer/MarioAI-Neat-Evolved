# Neat-Evolved
Update to [Seth Bling's Mar I/O][1] lua code, forked from [mam91/Neat-Genetic-Mario][2].
Tweaks made to learning algorithm parameters and gui.

Latest editions: Train from existing model + new buttons added in gui

## (Planned) additions & changes 
* [x] Track learning rate in GUI - fitness improvement percentage added
* [ ] Enhanced speed learning mode (implementing frameskip learning)
* [ ] Modularise the code better into seperate files for the GUI and Learning algoritm
* [ ] Update GUI
* [ ] Train from human input parameters
* [ ] Full Super Mario World save state selections

## Instructions from mam91's repo
1. Install [BizHawk](https://github.com/TASVideos/BizHawk) prerequesites & emulator:
   1. [BizHawk prerequesites (currently 2.1)](https://github.com/TASVideos/BizHawk-Prereqs/releases)
   2. [BizHawk (currently 2.2.2)](https://github.com/TASVideos/BizHawk/releases)
2. Get the rom of [Super Mario World (USA)](https://www.google.de/search?q=Super+Mario+World+(USA).sfc). (Other Super Mario World roms might work too but are not tested)

CRC | MD5 | SHA1
------------- | ------------- | -------------
B19ED489 | CDD3C8C37322978CA8669B34BC89C804 | 6B47BB75D16514B6A476AA0C73A683A2A4C18765
3. Clone the repository or download the zip file and place the neat-mario folder in your \BizHawk-2.2\Lua\SNES\ folder. (like: BizHawk-2.2\Lua\SNES\neat-mario)
4. Open config.lua and change variable _M.BizhawkDir to point on your BizHawk directory.
5. Open BizHawk (EmuHawk.exe)
6. Click File > Open ROM (Ctrl + O) and find Super Mario World (USA).sfc file. 
7. Once loaded, click Tools > Lua Console
8. In the new window, click Script > Open Script (Ctrl + O) and select mario-neat.lua in your \BizHawk-2.2\Lua\SNES\neat-mario folder.
9. The NEAT control window will display and you can then click Start to begin training.

Select "Load" from the NEAT control window to load an existing.pool file.
The save state for the pool to use can be changed using the seperate Config file.
