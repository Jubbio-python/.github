<p align="center">
  <img src="https://avatars.githubusercontent.com/u/257533134?s=200&v=4" alt="Lanux Logo" width="150"/>
</p>

<h1 align="center">Jubbio-Py</h1>

<p align="center">
  <strong>Python SDK for the Jubbio API</strong>
</p>

---

## 🌐 Hakkında

**Jubbio-Py**, Python ile Jubbio API’sine kolayca bağlanmanı sağlayan resmi olmayan bir SDK’dır.  
Bu kütüphane sayesinde Jubbio botlarını ve entegrasyonlarını hızlıca geliştirebilirsiniz.

**Resmî destek ve bilgi:** [Lanux Yazılım Hizmetleri](https://lanux.xyz/)

---

## 🚀 Özellikler

- Kolay ve hızlı Python entegrasyonu
- Asenkron (async) destekli mesaj ve olay yönetimi
- API çağrıları ve WebSocket desteği
- Event-driven bot mimarisi

---

## 📦 Kurulum

```bash
pip install jubbio-py 
```

⚡ Basit Örnek
```
from jubbio import Client

bot = Client("BOT_TOKEN")

@bot.event
async def on_message(msg):
    if msg.content.lower() == "ping":
        await msg.reply("pong")

bot.run() 
```

📄 Lisans

MIT License © 2026 Lanux Yazılım Hizmetleri
