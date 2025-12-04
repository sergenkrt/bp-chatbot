# 🎓 İKÜ - Bilgisayar Programcılığı Chatbot

Bu proje, İstanbul Kültür Üniversitesi (İKÜ) Bilgisayar Programcılığı bölümü öğrencileri için geliştirilmiş, yapay zeka destekli bir chatbot asistanıdır. 
Öğrencilerin ders programları, sınav tarihleri, akademisyen bilgileri ve genel üniversite duyuruları hakkında hızlıca bilgi almasını sağlar.

## 🚀 Proje Özellikleri

*   **📅 Ders Programı Sorgulama:** Derslerin gün, saat ve derslik bilgilerini anında öğrenin.
*   **📝 Sınav Takvimi:** Vize ve final sınav tarihlerini, saatlerini ve yerlerini sorgulayın.
*   **👨‍🏫 Akademisyen Bilgileri:** Hocaların iletişim bilgilerine, ofis konumlarına ve uzmanlık alanlarına erişin.
*   **📢 Duyurular:** Üniversite ve bölümle ilgili güncel duyuruları takip edin.
*   **❓ Sıkça Sorulan Sorular (SSS):** Staj, DGS, Erasmus, yemekhane ücretleri gibi konularda hazır cevaplara ulaşın.
*   **🤖 Yapay Zeka Desteği:** Google Gemini 2.0 Flash modeli ile entegre çalışarak, veritabanında bulunmayan karmaşık sorulara doğal ve akıllı cevaplar verir. 
*   **🇹🇷 Türkçe Dil Desteği:** Türkçe karakter normalizasyonu ve doğal dil işleme yetenekleri ile sorularınızı anlar.

## 📂 Proje Yapısı

*   `app.py`: Uygulamanın ana dosyası. Flask sunucusu, yapay zeka entegrasyonu ve tüm mantıksal işlemler burada bulunur.
*   `templates/`: Web arayüzü için HTML şablon dosyalarını içerir.
*   `requirements.txt`: Projenin çalışması için gerekli Python kütüphaneleri.
*   `baslat.bat`: Uygulamayı Windows üzerinde tek tıkla başlatmak için kullanılan toplu işlem dosyası.
*   `.env`: API anahtarları gibi hassas verilerin saklandığı yapılandırma dosyası.

## ⚙️ Projenin Kurulup Çalıştırılması

Projeyi yerel makinenizde çalıştırmak için aşağıdaki adımları izleyin:

### 1. Gereksinimler
*   Python 3.11 veya üzeri yüklü olmalıdır.
*   Google Gemini API anahtarı .env dosyasına girilmiş olmalıdır. (Google AI Studio'dan alınabilir)

### 2. Kurulum
*   Proje dosyalarını bilgisayarınızda bir konuma kopyalayın. C diskinde bir yere konumlandırılması tavsiye edilir.
*   .env dosyasına Google AI Studio'dan almış olduğunuz api keyini girin.
*   baslat.bat dosyasını çalıştırın.
*   Sonrasında tarayıcınızdan http://127.0.0.1:5000 adresine giderek projeyi kullanmaya başlayabilirsiniz.

## 📸 Projeden Ekran Görüntüleri

Giriş Sayfası

<img width="1835" height="936" alt="image" src="https://github.com/user-attachments/assets/6858548d-7e62-40b1-8cce-bcd9da13b318" />

