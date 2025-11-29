<p align="center">
  🌐 Available in: 
  <a href="#فارسی">فارسی</a> | 
  <a href="#english-version">English</a>
</p>

## فارسی


**🐍 Medusa Tunnel**

یک هسته‌ی تونلینگ قدرتمند و انعطاف‌پذیر است که با تمرکز بر پایداری، امنیت و ضدشناسایی طراحی شده.
کافیست نصب کنید، لایسنس بگیرید و فقط با یک دستور شروع به استفاده کنید 🚀

----
✨ ویژگی‌ها

🔄 مدهای Direct و Reverse

🌐 پشتیبانی از TCP و UDP

🔐 رمزنگاری ChaCha20 + TLS

🕵️ ضدشناسایی و ضد Packet Analysis

⚡تغییر مسیر خودکار هر 30 ثانیه (Seamless Handoff)

📊 مانیتورینگ ترافیک و وضعیت هر تونل به صورت جداگانه


----
<img width="1713" height="744" alt="Screenshot 2025-10-03 011702" src="https://github.com/user-attachments/assets/332fbea9-3c3f-4794-85dc-7504c02e93c7" />


**⚙️ شروع سریع**

----
**1️⃣ دریافت لایسنس تست یا خرید**

به ربات تلگرام برید:

[![Telegram Bot](https://img.shields.io/badge/Telegram-%40mnxcore_bot-26A5E4?logo=telegram&logoColor=white)](https://t.me/mnxcore_bot)



می‌تونید لایسنس تست بگیرید یا لایسنس خریداری‌شده وارد کنید.

آی‌پی‌های سرور ایران و خارج رو پشت لایسنس ست کنید.

----
**2️⃣ نصب روی سرور**

دستور زیر فقط هسته **Medusa** رو نصب می‌کنه (هیچ منویی باز نمیشه):



**Linux x86_64:**
```bash
curl -fsSL "https://github.com/Karrari-Dev/Medusa/releases/download/v2.0.0/medusa-linux-x86_64.tar.gz" \
| tar -xz -C /usr/local/bin medusa && chmod +x /usr/local/bin/medusa
```


**Linux aarch64:**
```bash
curl -fsSL "https://github.com/Karrari-Dev/Medusa/releases/download/v2.0.0/medusa-linux-aarch64.tar.gz" \
| tar -xz -C /usr/local/bin medusa && chmod +x /usr/local/bin/medusa
```
⚠**️ نکته مهم:** بعد از نصب، باید دستور زیر رو بزنید تا منو باز بشه:
```
medusa
```
----
### 3️⃣ اجرای Medusa

بعد از اجرای دستور `medusa`، از منو گزینه **Start / Configure** را انتخاب کنید. سپس منوی تنظیمات ظاهر می‌شود.

---

#### حالت Direct (ایران → خارج)

- **روی سرور ایران:**
  - **Tunnel port:** مثلا `200`
  - **Tunnel password:** یک رمز (باید در هر دو سرور یکی باشد)
  - **Enter Kharej IP:** آی‌پی سرور خارج
  - **Select protocols:** یکی از `TCP`، `UDP` یا `TCP+UDP`
  - **Ports Setup:**
    ```
    How many TCP ports? [1]: 3
    TCP local #1: 80
    TCP local #2: 443
    TCP local #3: 2053
    ```
    اگر UDP هم انتخاب کرده باشید:
    ```
    How many UDP ports? [1]: 1
    UDP local #1: 2053
    ```

- **روی سرور خارج:** فقط **Tunnel port** و **Tunnel password** را وارد کنید (باید دقیقا با سرور ایران یکی باشد).

---

#### حالت Reverse (خارج → ایران)

- **روی سرور خارج:**
  - **Tunnel port:** مثلا `200`
  - **Tunnel password:** همان رمز سرور ایران
  - **Enter Iran IP:** آی‌پی سرور ایران
  - **Select protocols:** یکی از `TCP`، `UDP` یا `TCP+UDP`
  - **Ports Setup:**
    ```
    How many TCP ports? [1]: 2
    TCP local #1: 80
    TCP local #2: 443
    ```
    و اگر UDP هم فعال باشد:
    ```
    How many UDP ports? [1]: 1
    UDP local #1: 2053
    ```

- **روی سرور ایران:** فقط **Tunnel port** و **Tunnel password** را وارد کنید (دقیقا مطابق سرور خارج).

---

⚡️ **نکته مهم:**  
در هر دو حالت، **پورت‌ها و رمز عبور باید روی هر دو سرور دقیقاً یکسان باشند**.


----
**4️⃣ مدیریت سریع**



Status → وضعیت تونل

Restart → ری‌استارت سریع

Autostart → اجرای خودکار موقع بوت

Traffic (Upload/Download) → مانیتورینگ ترافیک و وضعیت هر تونل

Delete → حذف تنظیمات

----
✨ به همین سادگی: لایسنس بگیر → نصب کن → medusa رو بزن → وصل شو!

**📩 پشتیبانی و خرید لایسنس:**

[![Telegram](https://img.shields.io/badge/Telegram-%40g0dline-26A5E4?logo=telegram&logoColor=white)](https://t.me/g0dline)



---

##  English Version


---


🐍 Medusa Tunnel is a powerful and flexible tunneling core, designed with a focus on stability, security, and anti-detection.
Just install, get your license, and start with a single command 🚀

----

✨ Features

🔄 Direct and Reverse modes

🌐 TCP & UDP support

🔐 ChaCha20 + TLS encryption

🕵️ Anti-detection & Anti-Packet Analysis

⚡ Automatic seamless handoff every 30 seconds

📊 Per-tunnel traffic monitoring & statistics

----
<img width="1713" height="744" alt="Screenshot 2025-10-03 011702" src="https://github.com/user-attachments/assets/332fbea9-3c3f-4794-85dc-7504c02e93c7" />

⚙️ Quick Start


**1️⃣ Get License (Trial or Paid)**

Go to Telegram bot:

[![Telegram Bot](https://img.shields.io/badge/Telegram-%40mnxcore_bot-26A5E4?logo=telegram&logoColor=white)](https://t.me/mnxcore_bot)


You can get a trial license or use your purchased one.
Set both Iran & Foreign server IPs behind the license.

----

**2️⃣ Install on Server**


**Linux x86_64:**
```
curl -fsSL "https://github.com/Karrari-Dev/Medusa/releases/download/v1.0.4/medusa-linux-x86_64.tar.gz" \
| tar -xz -C /usr/local/bin medusa && chmod +x /usr/local/bin/medusa
```

**Linux aarch64:**
```
curl -fsSL "https://github.com/Karrari-Dev/Medusa/releases/download/v1.0.4/medusa-linux-aarch64.tar.gz" \
| tar -xz -C /usr/local/bin medusa && chmod +x /usr/local/bin/medusa
```

⚠️ After installation, run:
```
medusa
```
----
### 3️⃣ Run Medusa

After running `medusa`, select **Start / Configure** from the menu. Then you’ll see the tunnel configuration screen.

---

#### Direct Mode (Iran → Foreign)

- **On the Iran server:**
  - **Tunnel port:** e.g., `200`
  - **Tunnel password:** must match on both servers
  - **Enter Foreign IP:** foreign server IP
  - **Select protocols:** choose `TCP`, `UDP`, or `TCP+UDP`
  - **Ports Setup:**
    ```
    How many TCP ports? [1]: 3
    TCP local #1: 80
    TCP local #2: 443
    TCP local #3: 2053
    ```
    If UDP also selected:
    ```
    How many UDP ports? [1]: 1
    UDP local #1: 2053
    ```

- **On the Foreign server:** only enter **Tunnel port** and **Tunnel password** (must match Iran server).

---

#### Reverse Mode (Foreign → Iran)

- **On the Foreign server:**
  - **Tunnel port:** e.g., `200`
  - **Tunnel password:** same as Iran server
  - **Enter Iran IP:** Iran server IP
  - **Select protocols:** `TCP`, `UDP`, or `TCP+UDP`
  - **Ports Setup:**
    ```
    How many TCP ports? [1]: 2
    TCP local #1: 80
    TCP local #2: 443
    ```
    If UDP also selected:
    ```
    How many UDP ports? [1]: 1
    UDP local #1: 2053
    ```

- **On the Iran server:** only enter **Tunnel port** and **Tunnel password** (must match Foreign server).

---

⚡️ **Important:**  
In both Direct and Reverse modes, the **port(s) and password must match exactly** on both servers.

----

**4️⃣ Fast Management**

Status → Check tunnel status

Restart → Quick restart

Autostart → Run on boot

Traffic (Upload/Download) → Per-tunnel traffic monitoring

Delete → Clear configuration

✨ That’s it: Get license → Install → Run medusa → Connect!

----

**📩 Support & License Purchase:**

[![Telegram](https://img.shields.io/badge/Telegram-%40g0dline-26A5E4?logo=telegram&logoColor=white)](https://t.me/g0dline)

