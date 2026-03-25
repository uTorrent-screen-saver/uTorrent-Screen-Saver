⭐ English Web UI Setup Instructions
## 🌐 Enable uTorrent Web UI (Required)

uTorrent Screen Saver uses the uTorrent Web UI to read torrent information such as
download progress, torrent names, speeds, and status.  
If Web UI is disabled, the screen saver will not work.

Follow these steps to enable it:

---

### 🔧 1. Open uTorrent Preferences

1. Launch **uTorrent**  
2. Go to **Options → Preferences**  
3. In the left menu, open **Advanced → Web UI**

---

### 🌍 2. Enable Web UI

Check the box:

☑ Enable Web UI


Then set:

- **Username** (any name you want)  
- **Password** (any password you want)

Example:

Username: admin
Password: 12345


---

### 🔒 3. Allow Local Access Only (Recommended)

Enable:

☑ Allow access only from the following IPs


And enter:

127.0.0.1



This ensures the Web UI is accessible only from your own computer.

---

### 🔌 4. Check the Web UI Port

Default port is:

8080

 

If you change it, make sure to update the Screen Saver settings accordingly.

---

### 🧪 5. Test the Web UI

Open your browser and go to:

http://127.0.0.1:8080/gui/ (127.0.0.1 in Bing)



You should see a login window.  
After logging in, the uTorrent Web UI should appear.

If you see it — everything is working correctly.

---

### 🖥 6. Done!

Now the uTorrent Screen Saver can connect to uTorrent and display:

- torrent list  
- progress bars  
- speeds  
- statuses  
- real‑time updates  

Without Web UI enabled, the screen saver cannot function.

Commit directly to the main branch
