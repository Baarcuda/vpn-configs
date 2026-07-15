# 🔐 Free VPN Configs

![Updated](https://img.shields.io/badge/updated-2026---07---15-blue)
![Configs](https://img.shields.io/badge/working%20configs-899-green)
![Top100](https://img.shields.io/badge/top100-fastest-orange)

Updated: `2026-07-15 14:36 UTC`

> Configs are **Base64 encoded**. Decode before use.

## ⚡ Top 100 Fastest Configs

Best configs sorted by latency across all protocols:

📄 **[top100.txt](./top100.txt)**

---

## 📊 Stats

| Protocol | Countries | Configs |
|----------|:---------:|:-------:|
| VLESS | 10 | 333 |
| VMESS | 5 | 57 |
| TROJAN | 7 | 144 |
| SS | 10 | 365 |

## 🌍 Top Countries

🇩🇪 DE · 🇫🇷 FR · 🇺🇸 US · 🇳🇱 NL · 🇷🇺 RU · 🇬🇧 GB · 🇯🇵 JP · 🌐 SC · 🇭🇰 HK · 🇵🇱 PL

---

## 📁 Structure

```
top100.txt          # 100 fastest configs (all protocols)
vless/XX.txt        # VLESS by country
vmess/XX.txt        # VMESS by country
trojan/XX.txt       # Trojan by country
ss/XX.txt           # Shadowsocks by country
```

## 🚀 How to use

1. Copy any line from the file
2. Decode from Base64
3. Import into your VPN client (Karing, Hiddify, v2rayNG, etc.)

**Linux/Mac:** `echo 'BASE64STRING' | base64 -d`

**Windows (PowerShell):**
```powershell
[System.Text.Encoding]::UTF8.GetString([System.Convert]::FromBase64String('BASE64STRING'))
```

---

> Auto-updated by [Art.29](https://t.me/Art29vpn) VPN Parser
