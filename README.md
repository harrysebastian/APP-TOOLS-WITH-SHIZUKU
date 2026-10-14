# NoRoot Kit

Magisk-jaisa toggles + commands panel, bina root ke. Ye Shizuku ke through shell (adb) privileges use karta hai.

## Setup
1. Play Store / GitHub se **Shizuku** install karo.
2. Developer options -> Wireless debugging ON -> Shizuku app mein "Pairing" se start karo (PC ki zaroorat nahi, Android 11+).
3. Android Studio mein is folder ko kholo -> Sync -> Run.
4. App kholo -> "Shizuku permission do" -> Allow.

## Features
- 7 built-in toggles (animations, stay awake, show touches, pointer location, dark mode, private DNS, adaptive battery). Switch ki state system se read hoti hai.
- Quick actions (battery info, kill background apps, device info...).
- Terminal: koi bhi shell command.
- Custom modules: "+ Add module" (ON/OFF command + optional check command). Delete karne ke liye long-press.

## Limits (root ke bina)
- System partition / files modify nahi hote, Zygisk/Xposed-type hooks nahi.
- Sirf shell-level kaam: settings, cmd, pm, am, wm, dumpsys, appops, etc.
- Reboot ke baad Shizuku dobara start karna padta hai (wireless debugging se aasaan).
- Kuch settings Android version / OPPO ColorOS pe alag behave kar sakti hain.
