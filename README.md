# Interface-1.9.4-.sh-MacOS-
Ported from the Windows 10 + 11 Version,Now Avaiable for MacOS.

NOTE: This macOS version will not be updated as frequently as the original Windows release, due to lack of support for certain features used in development for the Windows version.

MacOS Startup Integration — Team Video Interface v1.9.4 BETA
This guide enables automatic launch of the Team Video Interface at login on macOS systems.

Place the TeamVideo.sh script into:
/Users/YOUR-USERNAME/TeamVideoInterface/TeamVideo.sh

Make it executable by running:
chmod +x ~/TeamVideoInterface/TeamVideo.sh

Open Automator and create a new Application.
Add the Run Shell Script action.
Paste:
open -a Terminal "/Users/YOUR-USERNAME/TeamVideoInterface/TeamVideo.sh"

Save the application as TeamVideoLauncher to Applications or Desktop.

Open System Settings > General > Login Items, and add Interface.app (Or whatever the device has Auto-named it) to the list.

