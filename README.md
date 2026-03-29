# Hak5 Pineapple Pager Responder PyFile

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3](https://img.shields.io/badge/Python-3.8%2B-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![Shell](https://img.shields.io/badge/Shell-Bash-4EAA25?logo=gnu-bash&logoColor=white)](https://www.gnu.org/software/bash/)
[![Hak5 Pineapple Pager](https://img.shields.io/badge/Hak5-Pineapple%20Pager-FF6600)](https://shop.hak5.org/products/pager)
[![Responder Payload](https://img.shields.io/badge/Payload-Responder-000000)](https://github.com/lgandx/Responder)
[![Python](https://img.shields.io/badge/Made%20with-Python-3776AB?logo=python&logoColor=white)](https://www.python.org/)

![GitHub stars](https://img.shields.io/github/stars/The-Incredible-Gamma-Man/Hak5_Pineapple_Pager_Responder_PyFile)
![GitHub forks](https://img.shields.io/github/forks/The-Incredible-Gamma-Man/Hak5_Pineapple_Pager_Responder_PyFile)
![GitHub last commit](https://img.shields.io/github/last-commit/The-Incredible-Gamma-Man/Hak5_Pineapple_Pager_Responder_PyFile)

======== **Responder.py modified for the Hak5 Pineapple Pager!** ========

1. `Responder.py` to be transferred to your `/mmc/root/payloads/user/exfiltration/Responder_Payload/responder/` folder
2. Backup your `settings.py` and `payload.sh` and replace with my files
3. `payload.sh` has been included with the `-v` tag and runs in a loop until you give it the kill switch
4. If the payload crashes your pager, replace with your original `payload.sh` and continue to use my updated settings

**** **Key Updates to Settings and Responder.py** ****
- Upgraded to Python3 compatibility
- Absolute filepaths used for tools (ie. `/sbin/ip` etc.)
- `$PATH` defined early on
- Enhanced error handling throughout
- Additional `Responder_console.log` file issued to the `/responder/` folder
- Compatible with the pager firmware
