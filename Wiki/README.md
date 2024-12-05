# PalGuard Wiki

#### English / [简体中文](./README_ZH_CN.md)

## Contents

- [Commands](./Commands/README.md)
- [File Types](./Files/README.md)
- [Data Lists](./Data%20Lists/README.md)
- [FAQ](#faq)
  - [I've accidentally banned myself/someone. How can I unban them?](#ive-accidentally-banned-myselfsomeone-how-can-i-unban-them)
  - [I cannot login as an admin, it says that admin commands are whitelist protected.](#i-cannot-login-as-an-admin-it-says-that-admin-commands-are-whitelist-protected)
  - [My server crashes on startup.](#my-server-crashes-on-startup)
  - [I cannot see certain symbols properly in my server console.](#i-cannot-see-certain-symbols-properly-in-my-server-console)
  - [How can I report crashes?](#how-can-i-report-crashes)
  
</details>

## Foreword
The Wiki is currently under construction and therefor incomplete. We would appreciate if you contribute or point out mistakes, so the Wiki slowly and steady fills up.

## FAQ
### I've accidentally banned myself/someone. How can I unban them?
If you've banned their IP, for the time being you would need to edit palguard.json file and either reload the config or restart the server. If you've banned their account, you would need to remove their steamID from Pal\Saved\SaveGames\banlist.txt and restart the server afterwards.

---

### I cannot login as an admin, it says that admin commands are whitelist protected.
Make sure you have added your IP to palguard.json like shown on the picture. Alternatively, you can set useAdminWhitelist to false, but that is not recommended, since cheaters are known to have some kind of exploit to obtain admin password.

![AdminWhitelist](/.github/images/AdminWhitelist.png)

---

### My server crashes on startup.
Ensure you haven't messed up in palguard.json file, try deleting in and starting server again. If that doesn't helps and this is your first time using PalGuard, I'd suggest trying installing [VC++ redistributable](https://learn.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist?view=msvc-170).

---

### I cannot see certain symbols properly in my server console.
Please use Windows Terminal (or any alternative with proper unicode support) instead of default windows console.

---

### How can I report crashes?
Send your `\Pal\Saved\Crashes\*random numbers*\CrashContext.runtime-xml` file + palguard version used + log from `Pal\Binaries\Win64\logs` folder in bug-reports channel on [discord](https://discord.com/invite/jcvKpkUmXS).

---
