# RoHelper releases

Official portable Windows app releases maintained by **Veylo Labs**.

Download the portable ZIP from Releases, extract it into its own folder, and open `RoHelper.exe`. Windows needs the Microsoft Edge WebView2 runtime and the Visual C++ x86 runtime.

RoHelper 0.7.0 and newer can check, download, verify and install stable app updates from Settings. Updates install only when chosen, preserve the local `helper-data` directory, and reopen the app afterward. Failed file replacements restore the previous application. Keep the complete `helper-data` directory when moving a portable installation; protected sessions are bound to the Windows account.

`latest.json` is the stable app update manifest. Every portable package includes a SHA-256 file index. The manifest pins its version, expected archive size and SHA-256. Published ZIPs contain app files only: no accounts, session cookies, saved inventories or progress. GitHub HTTPS and hashes provide integrity; builds are not independently code-signed.

Game content updates separately from [rohelper-game-data](https://github.com/veylolabs/rohelper-game-data). Updating the app does not migrate or replace user data.

RoHelper is GPL-3.0. Each release includes its matching source archive and dependency notices. Artwork rights remain with the respective creators.
