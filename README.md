ATASÖZÜ AVCISI - OKUMA ANLAMA OYUNU 
Atasözü Avcısı , ilkokul seviyesinde (1-4.sınıflarda) okuma-anlama yeteneklerini geliştirme ve atasözlerini eğlenceli bir hikaye kurgusu içinde öğrenmelerini sağlamak amacıyla geliştirilmiş interaktif bir eğitim oyunudur.

OYUN HAKKINDA
Bu proje, çocukların sıkılmasından eğitim alabilmesi için oyunlaştırılmıştır. Her sınıf seviyesi için özel hikayeler ve bu hikayelerin içinde gizlenmiş ipuçları bulunur. Oyuncunun hikâyesini okur, özet yanıtları ve doğru kelimeleri bulan bölümleri tamamlar.

Özellikler
4 Farklı Seviye: 1., 2., 3. ve 4. sınıflar için ayrı içerikler.

İnteraktif Hikayeler: Her bölümde farklı bir macera ve yapılması gereken açıklamalar.

Akıllı Cevap Sistemi:

Kullanıcı dostu metin programı.

Yanıp sönen imleç desteği.

Yanlış cevap girildiğinde kutunun otomatik olarak temizlenmesi.

Doğru cevapta yeşil onay işareti (✓).

Görsel Ödül Sistemi: Bölüm tamamlandığında konfeti animasyonu ve kutlama ekranı.

Kullanıcı Arayüzü: Ahşap pencereli butonlar ve çocuklara uygun renk paleti.



KURULUM
Projeyi kendi akışında tutmak için aşağıdaki adımları izleyin:

1. Gereksinimler
Bilgisayarda Python'un kurulu olması gerekmektedir. Ayrıca oyun motoru olarak pygamekütüphanesi kullanılır.

2. İndirme
Terminali veya komut satırını açın ve projeyi klonlayın (veya ZIP olarak indirip çıkarın):

Bash

git clone https://github.com/KULLANICI_ADIN/atasozu-avcisi.git
cd atasozu-avcisi
3. Kütüphaneyi Yükle
Gerekli olanınpygame katılımını sağlayın:

Bash

pip install pygame
4. doğuma
Oyunu başlatmak için şu çalıştırmayı çalıştırın:

Bash

python main.py
(Not: Eğer dosya adı farklıysa main.pyyerine kendi dosya adınızı yazmanız gerekir.)

PROJE YAPISI VE DOSYALAR
Oyunun sorunsuz çalışabilmesi için.py aşağıdaki görsel dosyaların ( assets) saklanması gerekir:

atasozu-avcisi/
├── main.py             # Oyunun kaynak kodu
├── giriş.png           # Ana menü arka planı
├── harita.png          # Sınıf seçim ekranı
├── bölüm.png           # 1. Sınıf arka planı
├── bölüm2.png          # 2. Sınıf arka planı
├── bölüm3.png          # 3. Sınıf arka planı
├── bölüm4.png          # 4. Sınıf arka planı
├── hikaye.png          # Hikaye ekranı arka planı
└── karakter.png        # Gezgin karakter görseli

NASIL OYNANIR?
Sınıfını Seç: Ana menüden "Başla" butonu ile temel ve sınıf seviyesini seçin.

Bölüm Beğen: Harita üzerinden oynamak istediğiniz bölümü seçin.

Hikayeyi Oku: Ekrana gelen kısa hikayeyi ayrıntılı olarak oku.

Soruları Cevapla:

Sağ taraftaki kutucuklara tıklayın.

Klavyeyi kullanarak cevap yaz.

ENTER tuşuna basın.

İpucu: Eğer cevap doğruysa kutu yeşil olur, yanlışsa silinir tekrar denemeniz gerekir.

Şifreyi Çöz: Tüm bilgilerin bildiğinde bölümü tamamlar ve ödülü kazanırsın!
