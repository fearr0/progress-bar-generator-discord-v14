# Discord Progress Bar Bot

Modern ve şık görünümlü **Progress Bar** (ilerleme çubuğu) görselleri oluşturan ve bunları Discord bot komutlarıyla kullanan bir Node.js projesidir. Kullanıcıların görev, yetki veya aktivite ilerlemelerini görsel olarak göstermek için tasarlanmıştır.

---

## 🚀 Özellikler

- 📦 **Progress Bar Görsel Üretimi:**  
  `%0`'dan `%100`'e kadar `%5`'lik artışlarla **PNG formatında** modern ilerleme çubuğu görselleri üretir.

- 📊 **Dinamik Yüzde Hesaplama:**  
  Kullanıcının görev ilerlemesini otomatik olarak hesaplar ve uygun yüzdeye karşılık gelen görseli sunar.

- 🎨 **Görsel Tasarım:**  
  `drawProgressBar.js` dosyası, barın renklerini, yazı tipini ve genel stilini belirler. Kendi zevkine göre düzenleyebilirsin.

- 🧩 **Modüler Yapı:**  
  `getProgressBarAttachment.js` fonksiyonu sayesinde, yüzdelik değere göre doğru bar görselini otomatik olarak alabilir ve farklı projelere kolayca entegre edebilirsin.

- 📁 **Dosya Yönetimi:**  
  Üretilen tüm görseller otomatik olarak  
  `Assets/Progress/GeneratedProgressBars` klasörüne kaydedilir.

- 🖼️ **Embed Entegrasyonu:**  
  Discord mesajlarında, yüzdelik ilerlemeyi hem **metin olarak** hem de **görsel bar** olarak gösteren embed mesajlar gönderilebilir.

---

## 🔧 Kurulum

1. **Node.js (v16 veya üzeri)** sisteminizde kurulu olmalıdır.

2. Projeyi klonlayın veya indirin.

3. Gerekli bağımlılıkları yükleyin:

   ```bash
   npm install (paketleri kurun mutlaka yoksa bot çalışmaz.)
   node .\Bot.js dosyasını çalıştırıp botu başlatın.
