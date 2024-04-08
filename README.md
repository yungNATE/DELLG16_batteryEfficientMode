# DELLG16_batteryEfficientMode

<!-- ABOUT THE PROJECT -->
## About The Project
Gaming laptop are well known for not making portable life easy by rapidly devouring any MAH present in your battery. On DELL G16 (and many others) the main factor draining your battery is the 240Hz 2560*1600px (2K) screen. Here is stored 2 (tiny) batch commands that helps quickly switch from 2k240Hz to 1080p60Hz whenever you are on battery.

Like me, you can have them in your start menu and manually switch. You could also be lazy and setup an auto switch based on plugging events. As you wish. (You could also add a line to automatically switch windows to power efficient mode.)

*If you own any other laptop than DELL G16, you can tweak settings to fit your screen parameters.*

****I do not provide any installer, only a little step-by-step tutorial to set it up yourself.****
 
Use the `BLANK_README.md` to get started.

<!-- GETTING STARTED -->
## Getting Started
### Prerequisites
[Qres (download latest)](https://www.majorgeeks.com/files/details/qres.html) : Utility tool to change resolution via CLI. Available inside the repo.

[SetDPI (download latest)](https://github.com/imniko/SetDPI/releases/) : Utility tool to change DPI (windows scale) via CLI. Available in repo.

### Installation

Installation is beyond simple :

1. Download the repo. You will get a .zip.
2. Put both Qres.exe and SetDPI.exe inside *C:\Windows*
3. Execute whatever batch file you want. Done.
4. (Bonus) If you wish to have both .bat shortcut available inside your Windows Start Menu
	4. Create a shortcut of both (right click, create a shortcut)
	5. Place shotcuts inside *C:\ProgramData\Microsoft\Windows\Start Menu\Programs*
	6. In start menu, search each .bat name and add to start menu
	7. Done.

