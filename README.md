# Discord Progress Bar Bot

Modern ve şık görünümlü **Progress Bar** (ilerleme çubuğu) görselleri oluşturan ve bunları Discord bot komutlarıyla kullanan bir Node.js projesidir. Kullanıcıların görev, yetki veya aktivite ilerlemelerini görsel olarak göstermek için tasarlanmıştır.

---

## Görseller

<img width="742" height="237" alt="barpng" src="https://github.com/user-attachments/assets/5490e6aa-be9c-47de-9720-aad466315c79" />

<img width="738" height="234" alt="bar2png" src="https://github.com/user-attachments/assets/c9423330-f485-46e5-adf3-a04640971c41" />

<img width="642" height="358" alt="görevpng" src="https://github.com/user-attachments/assets/8359e955-6461-490f-b98b-bcfaa1bdad1e" />

<img width="529" height="183" alt="savebars" src="https://github.com/user-attachments/assets/7b5bfc29-85a0-4f15-a285-6688de4d87fb" />

<img width="1114" height="578" alt="savebarsTerminal" src="https://github.com/user-attachments/assets/a92d3f5b-c57d-425d-ae0f-6b9d1f546b24" />



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


   

   
