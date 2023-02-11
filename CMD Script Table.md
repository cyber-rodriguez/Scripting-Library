|   Script   |   Description   |
| -------------- | -------------- |
| dir | Show directory |
| cd | Change directory |
| mkdir | Make directory |
| robocopy | Automated copy command	     **EX.** robocopy workfolder videofolder	Everything in workfolder is copied to videofolder. |
| route print | This prints the routing table to the screen. |
| route add | -------------- |
| route delete | -------------- |
| -------------- | -------------- |
| net statistics srv | This will give system statistics from the time it was turned on.    This is good if you want to know how long a system has been on. |
| netstat | -------------- |
| netstat -n | -------------- |
| netstat -b | Must run as admin. |
| netstat -bn | Must run as admin. |
| netstat -bno | Must run as admin. |
| netstat -ba | Must run as admin. |
| netstat -r | Shows routing table. This is the same as "route print". |
| netstat -af | -------------- |
| netstat -o | -------------- |
| netstat -e -t 5 | -------------- |
| netplwiz | This shows the user account table and how many users are on the pc |
| cipher | This allows you to encrypt and decrypt files and folder on the PC. Along securely erasing files. |
| cipher /e F:/folder | To encrypt a folder or file |
| cipher /d F:/folder | To decrypt a folder or file |
| cipher /e /s F:/folder2 | To encrypt a folder and everything inside it. |
| cipher /w:F: | To overwrite any free space on a drive. |
| tracert | trace route |
| getmac | Finds the MAC or physical address |
| getmac /v | -------------- |
| wsl | Windows Sublayer for Linux |
| wsl --install | This will install ubuntu as default |
| wsl --list --online | This show you what linux distros are available |
| wsl --install -d "kali-linux" | This will install a distro of your choice |
| wsl --set-default-version 2 | Setting the version you want as default |
| wsl --update | -------------- |
| wsl --shutdown | -------------- |
| usbipd | This tool accesses serial for micro controller dev |
| usbipd wsl list | -------------- |
| usbipd wsl attach -b 18-2 --auto-attach | This allows you attach port to Linux |
| -b | Bus |
| hiberfile.sys | Never delete |
| powercfg.exe /hibernate off | To disable |
| chkdsk | To scan for errors |
| /F | Option to auto fix |
| sfc /scannow | System File Scanner |
| format /P:count | This is what will over wright the volume w/ zeros. |
| format d: /fs:NTFS /P:2 | The number of times you want zeros to over wright the volume. The letter of the drive you want to format is after the command. The NTFS is one of the several file systems you may choose. |
| diskpart | Type diskpart and it puts you in its directory. |
| DISKPART> list all | This will show how many disks you have |
| DISKPART> select disk 2 | Choose the disk you want to erase |
| DISKPART> clean all | This will begin to erase the drive it gives no progress. |
| ipconfig | -------------- |
| ipconfig/displaydns | -------------- |
| ipconfig/displaydns|clip | -------------- |
| ipconfig/flushdns | -------------- |
| powercfg /energy | -------------- |
| powercfg /energy batteryreport | -------------- |
| assoc | -------------- |
| assoc .mp4=VLC.vlc | -------------- |
| chkdsk  | -------------- |
| chkdsk  /f | -------------- |
| chkdsk /r | Check for bad sectors and repair them |
| DISM /Online /Cleanup-Image /CheckHealth | -------------- |
| DISM /Online /Cleanup-Image /ScanHealth | -------------- |
| DISM /Online /Cleanup-Image /RestoreHealth | -------------- |
| tasklist | -------------- |
| "tasklist | findstr script" | -------------- |
| taskkill /f /pid 20184	 | The pid number is for whatever you want to remove |
| netsh wlan show wlanreport | -------------- |
| netsh interface show interface | -------------- |
| netsh interface ip show dnsservers | -------------- |
| shutdown | Shuts down the PC. |
| fc | File Compare |
| EX.   fc a.txt b.txt | -------------- |
| prompt | -------------- |
| EX.  "prompt $T $B $P $G" | This will put a timestampt and current path (no space between the P & G) |
| $T | Time Stamp |
| $B | Pipe |
| $P | Current Path |
| $G | > |
| title | Allows you to change title of the command prompt window. |
| doskey /history | Gives a history of all entered commands durring the session. |
| F7 | Creates alist previous commands as a usable menu. |
| && | Allows you to string multiple commands |
| EX.	prompt $T $B $P$G && title PepeFEST | -------------- |
| clip | Will output the command to the clipboard. |
| > | This will output to a file. The source being a command like help or a mathematic function goes before and the path and output file goes after. |
| EX. help > testFile.txt | -------------- |
| ctrl + c | In CMD it is used to abort a previous command or function. |
| ##Run as Administrator in CMD## | -------------- |
| runas /profile /user:administrator "c:\Program Files (x86)\Google\Chrome\Application\chrome.exe" | This is how you open chrome in the command prompt. |
| msiexec | Builds communication with the PC backend. Microsoft Installer executable command. |
| msiexec /i "C:\Users\YourUserAccount\Desktop\7zip.msi" /qn | -------------- |
| /i | Install |
| /q | Specifies unattended mode which means the installation only show a progress bar |
| /qn | Specifies there's no UI during the installation process. |
| echo off | -------------- |
| start /wait | -------------- |
| echo done | -------------- |
| color a | Turns the text to green |
| color b | Turns the text to teal |
| color c | Turns the text to red |
| color d | Turns the text to magenta |
| color e | Turns the text to yellow |
| color f | Turns the text to white |
| color fc | Turns the text to red with a white BG |
| dir /s | This will start a scrolling directory list |
| -------------- | -------------- |
| -------------- | -------------- |
| -------------- | -------------- |
| -------------- | -------------- |
| -------------- | -------------- |
| -------------- | -------------- |
| -------------- | -------------- |
| -------------- | -------------- |
| -------------- | -------------- |
| -------------- | -------------- |
| -------------- | -------------- |
| -------------- | -------------- |
| -------------- | -------------- |
| -------------- | -------------- |
| -------------- | -------------- |
| -------------- | -------------- |
| -------------- | -------------- |
| -------------- | -------------- |
| -------------- | -------------- |
| -------------- | -------------- |
| -------------- | -------------- |
| -------------- | -------------- |
| -------------- | -------------- |
| -------------- | -------------- |
| -------------- | -------------- |
| -------------- | -------------- |

