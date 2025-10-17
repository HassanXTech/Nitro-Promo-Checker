# 🔮 Nitro Promo Checker - Advanced Promo Checker

> **Made by [@anomus.ly](https://t.me/anomus.ly) | Discord**  
> **Get Here:** [https://anomus.mysellauth.com](https://anomus.mysellauth.com)

---

## 📋 Description

Nitro Promo Checker is a high-performance promo checker with a beautiful terminal UI, built with the Rich library. It features multi-threading, proxy support, hit sending to Telegram/Discord, and real-time result saving.

---

## ✨ Features

- 🎨 **Beautiful UI** - Gradient colors, animated menus, live statistics
- ⚡ **Multi-threaded** - Fast checking with customizable thread count
- 🌐 **Proxy Support** - HTTP/HTTPS proxies with authentication
- 📊 **Live Stats** - Real-time CPM, hits, valid, dead, errors tracking
- 💾 **Auto-Save** - Results saved immediately as they're found
- 📱 **Hit Sender** - Send notifications to Telegram or Discord
- 🧪 **Proxy Tester** - Test proxy speed and validity
- ⏸️ **Cancel Support** - Press 'C' to cancel operations anytime
- 📁 **Organized Results** - Timestamped folders with categorized files

---

## ⚙️ Settings

### 1. Proxy Settings

#### Supported Formats:
```
host:port
user:pass@host:port
host:port:user:pass
http://host:port
```

#### Options:
- **Set Single Proxy** - Use one proxy for all checks
- **Load Proxies From File** - Load multiple proxies (automatic rotation)
- **Test Proxies** - Verify proxy speed and functionality
- **Clear Proxies** - Remove all proxy settings

#### Example Proxy File (`proxies.txt`):
```
proxy1.example.com:8080
user123:pass456@proxy2.example.com:3128
192.168.1.1:8080:username:password
```

---

### 2. Hit Sender Settings

Send real-time notifications when hits are found.

#### Telegram Setup:
1. Create a bot with [@BotFather](https://t.me/BotFather)
2. Get your **Bot Token**
3. Get your **Chat ID** from [@userinfobot](https://t.me/userinfobot)
4. Enter both in **Hit Sender Settings**
5. Set Status to **Telegram**
6. Click **Test Hit Senders** to verify

#### Discord Setup:
1. Go to your Discord channel settings
2. **Integrations → Webhooks → New Webhook**
3. Copy the **Webhook URL**
4. Paste in **Hit Sender Settings**
5. Set Status to **Discord**
6. Click **Test Hit Senders** to verify

---

### 3. Thread Settings

- **Checker Threads** - Number of concurrent checking tasks (Default: 25)
  - Lower = Slower but less resource usage
  - Higher = Faster but more CPU/RAM usage
  
- **Proxy Tester Threads** - Concurrent proxy tests (Default: 100)

**Recommended Settings:**
- Fast PC: 50-100 threads
- Average PC: 20-50 threads
- Slow PC: 10-20 threads

---

---

## 📊 Live Checker UI

During checking, you'll see:

```
╔════════════════════════════════════╗
║ HITS     : 15                      ║
║ VALID    : 42                      ║
║ DEAD     : 128                     ║
║ ERRORS   : 5                       ║
║ CHECKED  : 190/500                 ║
║ CPM      : 485                     ║
╚════════════════════════════════════╝

╔══════ Latest Captures ══════╗
║ [HIT] user@email.com:pass123 ║
║ [VALID] test@mail.com:test   ║
╚══════════════════════════════╝

         Press 'C' to Cancel
```

## ⚠️ Disclaimer

**This tool is for EDUCATIONAL PURPOSES ONLY.**

- The developer assumes NO liability for misuse
- Use responsibly and at your own risk
- Always comply with applicable laws and terms of service
- This tool is NOT intended for malicious activities

---

## 🛒 Purchase & Support

- **Official Store:** [https://anomus.mysellauth.com](https://anomus.mysellauth.com)
- **Discord:** [@anomus.ly](https://t.me/anomus.ly)

⚠️ **Warning:** Only purchase from official seller. Anything else is a SCAM!

---

## 📜 License

© 2025 Anomus Service. All rights reserved.

---

<div align="center">

**🔮 Made with ⚡ by @anomus.ly 🔮**

</div>
