Special Thanks:  
- ALLAH SWT dan Idolaku Nabi Muhammad SAW  
- Mama, Papa sama adek2ku  
- Ko kinyo dan Ko Andiko [BEST!!]  
- CHAT GPT + Youtube Programmer yang ga bisa di sebutin 1-1  
---
Link Download:
1. Redistributable Microsoft Visual C++ terbaru : (Kalo sudah keinstall abaikan)
  a. https://aka.ms/vs/17/release/vc_redist.x64.exe
  b. https://aka.ms/vs/17/release/vc_redist.x86.exe
2. JetCalc v 1.0
https://www.mediafire.com/file/gk6kjl8sevsaz4y
=========================================  
🧮 JetCalc - Clipboard Calculator  
=========================================

📌 Deskripsi (Bahasa Indonesia)  
JetCalc adalah sebuah aplikasi yang dibuat atas keresahan saya ketika saya ingin menghitung di komputer, tapi saya harus buka calculator dulu.  
Lalu saya mencoba mengingat-ngingat:  
"Ada gak ya Calculator kayak di aplikasi LINE Message?"  

Buat kalian yang belum tau, kalo kita menghitung sederhana di kolom chat LINE, misalnya kita ketik "1 + 1", nanti juga keluar hasilnya " = *2*".  
Btw itu di PC sih, ga tau kalo HP... Dan saya ga tau fiturnya itu masih ada sampai sekarang atau tidak...

Saya sudah mencoba searching yang mungkin ada aplikasi seperti itu fungsinya, tapi tidak ketemu (Atau saya yang kurang tepat kata kuncinya).  
Atas dasar itulah, saya bikin aplikasi calculator simple ini dengan bantuan Chat GPT dan ilmu yang sudah pernah saya dapatkan dari 2 guru saya di atas...

🛠️ Jadi cara kerjanya simpel:  
Dirimu ketik angka dan operasinya, terus blok, terus pencet Control + Shift + C, terus langsung Control + V.  
Cara kerjanya beda sama yang di LINE ya...  
Kalau di LINE abis sama dengan langsung keluar hasilnya... Sedangkan ini masih pakai hotkey...

📌 Contoh:

    125*(3+7)=  
    899123,05*115+(9+9)=  
    09/04/2025+30 hari =  
    09/04/2025+3 minggu =  
    58700*0,70 =  
    (Mode Hex)03A92AB + AC =

Abis itu dari "125" sampai "=", itu kalian blok, abis itu Pencet Control + Shift + C, terus langsung Control + V,  
maka hasilnya akan langsung seperti di bawah:

    125*(3+7) = 1250  
    899123,05*115+(9+9) = 103399168,75  
    09/04/2025 + 30 hari = Jum'at, 09/05/2025  
    09/04/2025 + 3 minggu = Rabu, 30/04/2025  
    58700*0,70 = 41090  
    (Mode Hex)03A92AB + AC = 3A9357

JetCalc ini bisa dipakai di mana aja ✨  
Termasuk di Notepad, kolom balas chat Facebook, komenan Facebook, address web di Chrome (atas) atau mana aja.
Setiap dirimu tekan Control + Shift + C saat terdeteksi penghitungan, juga ada history lognya lho. Cek aja di tray... (bentuknya sekarang masih .txt)
Selama bisa nempelin text...Btw untuk mode hex, cuma terbatas kayak gitu aja ya. Ga lebih....

📅 Oh iya untuk tanggal, aku bikin sistemnya kayak gini:
- 1 hari = 1 hari  
- 1 minggu = 7 hari  
- 1 bulan = 30 hari  
- 1 tahun = 365 hari  
🛑 Dan untuk tanggal belum ada pengurangan ya...

📝 Selain itu, ada fitur Quickpaste.  
Jadi kalo dirimu pencet Control + Shift + 1-5, terus kalian Control + V, nanti akan keluar text yang sudah kalian save di config.  
Misalnya di config 1 kalian save "BCA an Ikhlasul Amal xxxxxxxx", nanti keluarnya itu.  
Sementara ini aku hanya bikin 5 config aja...

📌 Terus ini ga ada UI Interface ya, hanya pakai System Tray Icon.  
Klik kanan logonya "JetCalc" kalo mau lihat-lihat...

⚙️ Ada fitur:
- ✅ Auto Run: Jadi kalo PC baru nyala, JetCalc ini bisa langsung jalan. Centang aja sih...
- 💡 Auto Format: Jadi kalo angkanya misalnya hasilnya "1000000", nanti keluarnya "1.000.000"

📶 Fitur ini sama sekali tidak butuh internet (Untuk sekarang).  
Ga tau deh ini ntar di lanjutin apa ngga wkwkw...

---

🔐 Dan yang terakhir gak kalah penting, tolong ini diperhatikan ya...

🛡️ Di aplikasi ini ada fitur "App Block", maksudnya gimana?

Jadi di direktori yang sama dengan JetCalc ini, ada file namanya "jet_blocklist.txt".  
Kalian juga bisa buka .txt-nya di Tray Icon.  
Itu tempatnya buat ngelist seluruh program yang kalau program yang ada di list terbuka, dan JetCalc lagi terbuka juga,  
maka JetCalc akan out secara otomatis.  
(JetCalc-nya yang out. Bukan app yang di list)

🎮 Jadi gini, aku kan orangnya main valo ya.  
Seperti yang kalian tau, Valorant itu sistem anti-cheat-nya menurutku "wah" untuk saat ini.  
Jadi setiap game Valorant dibuka, aplikasi JetCalc ini akan close secara otomatis.  

🎯 Intinya adalah: aku gak pengen Valorant ngira aku pake macro atau dikira pake hack ketika JetCalc ini dijalankan.  
Makanya aku bikinin "jet_blocklist.txt" ini. Untuk antisipasi kesalahpahaman...

📄 Di jet_blocklist.txt yang sekarang ini, kalian buka dan setting sesukanya.  
Tinggal setting aja di line baru. Misal:

VALORANT-Win64-Shipping.exe  
Notepad.exe  
Discord.exe  
V98.exe

Fitur ini aku buat karena mungkin suatu saat aku lupa buat ngeclose app JetCalc ini.  

⚠️ Dan sekali lagi aku tekankan:  
Aku sama sekali gak tanggung jawab ya kalau terjadi sesuatu hal yang tidak diinginkan.  
Yang penting aku udah ngasih tau dan ngasih fitur di atas sebagai upaya pencegahan.

🧠 SARANKU PRIBADI:  
Sebelum buka app/game yang ketat, PASTIIN JetCalc di task manager udah ga ada (sudah ke-close).  
Tambah juga list app/game yang kamu mainkan/pakai di "jet_blocklist.txt"  

🕹️ Dan buat kalian yang gak main valo atau pakai aplikasi dengan security ketat, diabaikan aja...

Oh iya 1 lagi, terakhir. Kalo misalin aplikasinya gak buka (di tray icon ga ada). Coba command deh, nanti tak PM FBnya... Buat ngecek mungkin ada kesalahan codenya...
Ini masih v1 banget ya, jadi versi beta. Tentu banyak sekali bugnya....

Cara pakai:
1. Download 3 file diatas
2. Install MSVC kalo belum
3. Klik kanan "JetCalc v1.0", ekstrak here
4. Jalankan JetCalc.exe (Pastikan Game / App yang securitya bagus di close dulu jangan lupa!!)

---

📞 Kontak:  
Dikembangkan oleh Hamzah  

💬 Saran, donasi, atau dukungan:  
- 🌐 Facebook: https://www.facebook.com/theycallmeaal  
- ☕ Sociabuzz: https://sociabuzz.com/hamzah__/tribe

---

✨ JetCalc is made to help, not to be abused.  
Use it wisely and responsibly! 🚀  

#dontforgettosholat #freepalestine

=========================================  
🧮 JetCalc - Clipboard Calculator  
=========================================

📌 Description (English)  
JetCalc is a simple utility app born out of my frustration whenever I needed to do quick calculations on my PC — I always had to open a calculator app first.  
Then I remembered something:  
"Wait, isn't there a quick calculation feature like in LINE Messenger?"  

If you’ve never seen it before, in LINE (on PC), you can type something like “1 + 1” in chat, and LINE will automatically display the result as “ = *2*”.  
I don’t know if the feature still exists or if it works on the mobile app... but it inspired me.  

I searched online for any similar apps, but couldn't find any. So, I decided to build one myself using help from ChatGPT and knowledge from my mentors.

🛠️ How it works is simple:  
Just type the math expression, highlight it, press Ctrl + Shift + C, and then paste (Ctrl + V) the result wherever you want.  
It’s not as automatic as LINE's — this one uses hotkeys.

📌 Examples:

    125*(3+7)=  
    899123.05*115+(9+9)=  
    09/04/2025+30 days =  
    09/04/2025+3 weeks =  
    58700*0.70 =  
    (Hex Mode)03A92AB + AC =

Just highlight from "125" to the "=", press Ctrl + Shift + C, then Ctrl + V,  
and the result will be like this:

    125*(3+7) = 1250  
    899123.05*115+(9+9) = 103399168.75  
    09/04/2025 + 30 days = Friday, 09/05/2025  
    09/04/2025 + 3 weeks = Wednesday, 30/04/2025  
    58700*0.70 = 41090  
    (Hex Mode)03A92AB + AC = 3A9357

JetCalc works anywhere you can paste text ✨  
In Notepad, Facebook chat, comment boxes, browser address bars — anywhere!  
It also logs every calculation in a simple .txt log. You can view it via the system tray icon.  
Note: Hex mode is limited for now.

📅 For date addition, I use these rules:
- 1 day = 1 day  
- 1 week = 7 days  
- 1 month = 30 days  
- 1 year = 365 days  
🛑 No subtraction for dates yet.

📝 There's also a QuickPaste feature:  
When you press Ctrl + Shift + 1-5 and then Ctrl + V, a pre-saved phrase from the config file will appear.  
For example, Ctrl + Shift + 1 will paste “BCA an Ikhlasul Amal xxxxxxxx”.  
There are currently 5 configurable slots.

📌 There’s no GUI — just a tray icon.  
Right-click the "JetCalc" icon in the system tray to explore.

⚙️ Features:
- ✅ Auto Run: Starts JetCalc automatically with Windows.  
- 💡 Auto Format: Formats large numbers with commas/dots, e.g., 1000000 → 1.000.000

📶 No internet required.  
I’m not sure if I’ll keep developing it — we’ll see! 😄

---

🔐 IMPORTANT: App Block Feature

There is a feature called “App Block” — in the same folder as JetCalc, there’s a file named `jet_blocklist.txt`.  
When JetCalc detects that a listed app is running, it will automatically close itself.  
(Only JetCalc closes, not the listed apps.)

🎮 I play Valorant, and it has strong anti-cheat software.  
To avoid misunderstandings (e.g., being flagged for using macros), I created this blocklist feature.

📄 You can freely edit `jet_blocklist.txt` to include any apps you want.  
One app per line, for example:

VALORANT-Win64-Shipping.exe  
Notepad.exe  
Discord.exe  
V98.exe

This helps ensure I don’t forget to close JetCalc before launching security-sensitive apps.

⚠️ DISCLAIMER:  
I take no responsibility for any consequences caused by this tool.  
Please use responsibly, and always close JetCalc before running high-security apps.

🧠 PERSONAL TIP:  
Before launching games or apps with anti-cheat or sensitive security, make sure JetCalc is completely closed via Task Manager.  
Also, maintain your blocklist to stay safe.

🕹️ If you don’t play such games or use such apps, you can ignore this feature.

Lastly, if JetCalc doesn’t appear in the tray, run it via command prompt or contact me — I’ll help you troubleshoot.  
This is version 1.0 (beta), so bugs are expected!

How to use:
1. Download the 3 files above  
2. Install MSVC Redistributable if not already installed  
3. Extract "JetCalc v1.0"  
4. Run JetCalc.exe (Make sure to close any sensitive apps first!)

---

📞 Contact:  
Developed by Hamzah  

💬 Feedback, donations, or support:  
- 🌐 Facebook: https://www.facebook.com/theycallmeaal  
- ☕ Sociabuzz: https://sociabuzz.com/hamzah__/tribe

---

✨ JetCalc is made to help, not to be abused.  
Use it wisely and responsibly! 🚀  

#dontforgettosholat #freepalestine