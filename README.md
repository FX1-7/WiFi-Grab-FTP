-----------------------------------------------------
# Rubber Ducky WiFI Grab and Upload via FTP


REM Title:         UAC, Windows Defender and WiFi Grab via FTP

REM Description    Will grab all WiFi passwords the device has and upload them to an ftp server defined in the payload.

REM Author:        FX17

REM Version:       1.0

REM Target:        Windows 10

REM Attackmodes:   HID

—————————————————————————————————————————————————

Be sure to edit the .txt file lines 96, 99 and 102.

For example the script should look like:

96: `STRING 192.168.0.69 21`

99: `STRING FX17`

102: `STRING SecurePassword123!`


After these changes encode the script and upload to your ducky!

If you have any issues running this script, please contact me via discord: @Keiran1712

-----------------------------------------------------
