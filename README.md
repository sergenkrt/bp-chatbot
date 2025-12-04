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

Giriş Sayfası: Bu sayfa projeye erişmeye çalıştığımızda karşımıza çıkan ilk sayfadır.
Bu sayfaya öğrenci numaranızı ve ad soyadınızı girdikten sonra projenin ana sayfasına ulaşabilirsiniz.
Öğrenci numarası yerine sadece numara, ad soyad yerine de sadece harf girilmelidir.

<img width="1835" height="936" alt="image" src="https://github.com/user-attachments/assets/6858548d-7e62-40b1-8cce-bcd9da13b318" />

> Chatbot Ana Sayfası: Bu sayfa giriş yaptıktan sonra aktarılan chatbotun ana sayfasıdır.
Bu sayfada seçim yaparak sorabileceğimiz 8 kategori bulunmaktadır.

<img width="1860" height="945" alt="image" src="https://github.com/user-attachments/assets/cab9f7a8-4079-45a0-b965-eefaa73e5d31" />

> Ders programı kategorisine bastığımızda bilgisayar programcılığı derslerini dönem dönem görüntüleyebilmekteyiz. Bu 4 dönemden herhangi birini bota ayrı şekilde sorarak da erişebiliriz.

<img width="1799" height="673" alt="image" src="https://github.com/user-attachments/assets/71dc3299-472b-4729-8a0e-113cded29a8c" />

<img width="1755" height="448" alt="image" src="https://github.com/user-attachments/assets/adcb7964-c9d5-4122-819f-613f4c1ea86b" />

> Sınav tarihleri kategorisine bastığımızda sınavlarımızı görüntüleyebilmekteyiz.

<img width="1778" height="471" alt="image" src="https://github.com/user-attachments/assets/056e9243-3ac8-48df-a11e-5b7c592b0ad9" />

> Akedemisyenler kategorisine bastığımızda üniversitedeki akedemisyenlerin bilgilerine detaylı şekilde ve isteğe göre ayrı şekilde ulaşabiliriz.

<img width="1758" height="252" alt="image" src="https://github.com/user-attachments/assets/f8c7d5a7-5a26-404a-ad17-ed892700e471" />

<img width="1762" height="211" alt="image" src="https://github.com/user-attachments/assets/929688cc-0ce7-4dd8-85e0-8b57f26e9281" />

> Duyurular kategorisine bastığımızda bölüm duyurularını görüntüleyebilmekteyiz.

<img width="1747" height="310" alt="image" src="https://github.com/user-attachments/assets/dad0cbda-2d25-4b51-ab94-dda4f2e11228" />

> Sık sorulan sorular kategorisinde bilgisayar programcılığı bölümünde sıkça sorulan soruların özenle açıklanmış cevapları bulunmaktadır.

<img width="1758" height="377" alt="image" src="https://github.com/user-attachments/assets/e9fc1420-f202-4d81-b000-070165d6bcdd" />

> Kampüs kategorisinde ise İstanbul Kültür Üniversitesi kampüslerinin tamamının konumları, iletişim bilgileri görüntülenebilmektedir.

<img width="1742" height="369" alt="image" src="https://github.com/user-attachments/assets/cd34d213-c911-4bfa-a889-f24def10e9f3" />

> Burs kategorisinde burslar hakkında detaylı bilgi elde edebiliriz.

<img width="1749" height="274" alt="image" src="https://github.com/user-attachments/assets/e1e57d3d-88f6-4075-9c0b-02481fc12e5c" />

> Öğrenci işleri kategorisinde öğrenci işleriyle alakalı kategori isimlerine ulaşabilir. İhtiyacımız olan konuyu alt konu olarak tekrar sorabiliriz.

<img width="1750" height="202" alt="image" src="https://github.com/user-attachments/assets/b827036d-ed3e-491f-85e9-d53c97428a15" />

> Tüm bu kategorilerin dışında bir soru sorduğumuzda proje, Gemini 2.0 Flash modelini kullanarak cevap vermektedir.

<img width="1745" height="256" alt="image" src="https://github.com/user-attachments/assets/f88ff610-64ee-46e7-bede-c0350c1a61fd" />


