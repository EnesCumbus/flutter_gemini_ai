# 🤖 Flutter + Gemini AI Chat Uygulaması 🚀

Bu Flutter uygulaması, Gemini AI modeli kullanarak kullanıcılarla etkileşimli sohbetler gerçekleştirmek için tasarlanmıştır. Uygulama, kullanıcıların metin girdisi sağlayarak yapay zekadan yanıtlar almasını sağlar. 💬

---

## 🌟 Özellikler
- **Etkileşimli Sohbet:** Kullanıcılar, girdileriyle yapay zeka ile sohbet edebilir.
- **Markdown Destekli Mesajlar:** Yanıtlar Markdown formatında işlenir ve gösterilir.
- **Hata Yönetimi:** Yanıt alınamadığında kullanıcı dostu hata mesajları görüntülenir.
- **Modern ve Sade UI:** Karanlık tema ve kullanıcı dostu tasarım ile modern bir arayüz sunar.

---

## 🛠️ Gereksinimler
Uygulamayı çalıştırmadan önce aşağıdaki gereksinimlerin karşılandığından emin olun:

1. **Flutter SDK** kurulu olmalıdır.
2. **Google Generative AI API Anahtarı**: [Google Generative AI](https://developers.generativeai.google/) üzerinden bir API anahtarı alın.

---

## 🚀 Kurulum ve Çalıştırma

1. Projeyi klonlayın veya indirin:
   ```bash
   git clone https://github.com/EnesCumbus/flutter_gemini_ai_chat.git
   cd flutter_gemini_ai_chat
   ```

2. Kod düzenleme aracıyla (ör. Visual Studio Code) projeyi açın.

3. **API Anahtarını Güncelleyin:**
   `apiKey` değişkenini kendi Google Generative AI API anahtarınız ile değiştirin:
   ```dart
   const String apiKey = 'YOUR_API_KEY';
   ```

4. Flutter bağımlılıklarını indirin:
   ```bash
   flutter pub get
   ```

5. Uygulamayı çalıştırın:
   ```bash
   flutter run
   ```

---

## 📚 Kullanım

1. Metin alanına bir mesaj yazın (örneğin: "Hava bugün nasıl?").
2. **Gönder** butonuna tıklayın.
3. Yapay zekadan gelen yanıtlar ekranın üst kısmında görünecektir.

---

## 🔧 Kütüphaneler ve Araçlar
Bu proje aşağıdaki Flutter paketlerini kullanır:
- `google_generative_ai`: Google Generative AI API ile etkileşim için.
- `flutter/material.dart`: UI tasarımı için temel Flutter bileşenleri.
- `flutter_markdown`: Markdown formatında mesajların işlenmesi için.
- `url_launcher`: Harici bağlantıların açılması için.

---

## Hata Yönetimi
Uygulama, aşağıdaki durumlar için hata mesajları görüntüler:
- Geçersiz veya eksik API anahtarı.
- Ağ bağlantı hataları.
- API limit aşımları.

Hata durumunda ekranda bir hata diyalogu belirir ve kullanıcı bilgilendirilir.

---

## Katkıda Bulunma
Projeyi geliştirmek veya yeni özellikler eklemek için katkıda bulunabilirsiniz.
