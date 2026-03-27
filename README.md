======== Responder.py modified for the Hak5 Pineapple Pager! ========

1. Responder.py to be transferred to your /mmc/root/payloads/user/exfiltration/Responder_Payload/responder/ folder
2. Backup your settings.py and payload.sh and replace with my files
3. payload.sh has been included with the -v tag and runs in a loop until you give it the kill switch
4. If the payload crashes your pager, replace with your original payload.sh and continue to use my updated settings

**** Key Updates to Settings and Responder.py ****
- Upgraded to Python3 compatibility
- Absolute filepaths used for tools (ie. /sbin/ip etc.)
- $PATH defined early on
- Enhanced error handling throughout
- Additional 'Responder_console.log' file issued to the /responder/ folder
- Compatible with the pager firmware
