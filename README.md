# 🎮 Dil Telaffuz Oyunu (Language Pronunciation Game)

Python ile geliştirilmiş, mikrofonunuzu kullanarak farklı dillerde kelime telaffuzu yapmanızı sağlayan interaktif ve eğlenceli bir konsol oyunudur!

![Python Version](https://img.shields.io/badge/Python-3.x-blue.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)

---

## ✨ Özellikler

* **🌍 Çoklu Dil Desteği:** 9 farklı dilde (İngilizce, Türkçe, Almanca, İspanyolca, İtalyanca, Rusça, Portekizce, Lehçe, Endonezce) pratik yapma imkanı.
* **🎯 Zorluk Seviyeleri:** Her dil için **Kolay**, **Orta** ve **Zor** olmak üzere kademeli seviyeler.
* **💡 İsteğe Bağlı Telaffuz Yardımı:** Oyunun başında aktif edebileceğiniz okunuş ipuçları (fonetik rehber) ile yabancı kelimeleri daha rahat seslendirin.
* **🎤 Ses Tanıma Entegrasyonu:** `sounddevice` ve `speech_recognition` kütüphaneleri sayesinde sesinizi kaydedip Google Speech Recognition ile anında analiz eder.
* **🏆 Puanlama ve Hata Sistemi:** Doğru telaffuzlarda puan kazanın, 3 hata hakkınızla sınırları zorlayın!
* **🔄 Akıllı Eşleştirme:** Büyük/küçük harf duyarsızlığı ve noktalama temizliği ile esnek doğrulama.

---

## 📦 Gereksinimler ve Kurulum

Projeyi bilgisayarınızda çalıştırmak için aşağıdaki kütüphaneleri yüklemeniz gerekmektedir.

1. **Python'un yüklü olduğundan emin olun** (Örn: Python 3.8+).
2. Gerekli kütüphaneleri yüklemek için terminal veya komut satırına şunu yazın:

```bash
pip install sounddevice scipy SpeechRecognition
