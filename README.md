<div align="center">
  <h1>💻 VCS v2</h1>
  <h3>Varyant Konfigürasyon Sistemi</h3>
  <p>Bilgisayar bileşenleri ve donanım varyantları için gelişmiş maliyet ve kâr hesaplama otomasyonu.</p>

  ![Sürüm](https://img.shields.io/badge/Sürüm-v2.2.11-blue?style=for-the-badge)
  ![Python](https://img.shields.io/badge/Python-3.x-green?style=for-the-badge&logo=python&logoColor=white)
  ![Platform](https://img.shields.io/badge/Platform-Windows-lightgrey?style=for-the-badge&logo=windows&logoColor=white)
  ![Lisans](https://img.shields.io/badge/Lisans-Özel-orange?style=for-the-badge)
</div>

---

## 📋 İçindekiler

- [Hakkında](#-hakkında)
- [Özellikler](#-özellikler)
- [Kurulum](#-kurulum)
- [Kullanım](#-kullanım)
- [Otomatik Güncellemeler](#-otomatik-güncellemeler)
- [Değişiklik Günlüğü](#-değişiklik-günlüğü)

---

## 📖 Hakkında

**VCS v2 (Varyant Konfigürasyon Sistemi)**, Gökkuşağı Bilgisayar için geliştirilmiş bir masaüstü uygulamasıdır. Yüzlerce farklı bilgisayar konfigürasyonunun maliyetini ve satış fiyatını tek tıkla hesaplayarak devasa bir **Excel Konfigürasyon Matrisi** oluşturur.

Uygulama, farklı donanım bileşenlerinin tüm olası kombinasyonlarını otomatik olarak oluşturur ve her bir varyant için KDV, şirket kâr marjı ve pazaryeri kâr marjı dahil detaylı fiyat hesaplaması yapar.

---

## 🚀 Özellikler

### Bileşen Yönetimi
| Bileşen | Açıklama |
|---------|----------|
| 🧠 **Normal RAM** | 16GB – 256GB arası standart RAM seçenekleri |
| 💻 **Notebook RAM** | Standart ve Manuel mod (2 RAM slotu + maliyet) desteği |
| 🔒 **ECC RAM** | 16GB – 512GB arası sunucu sınıfı RAM seçenekleri |
| 💾 **M.2 SSD** | 128GB – 8TB arası NVMe SSD seçenekleri |
| 📀 **SATA SSD** | 128GB – 8TB arası SATA SSD seçenekleri |
| 🗄️ **HDD** | 1TB – 20TB arası sabit disk seçenekleri |
| 🎮 **Ekran Kartı (GPU)** | Dinamik GPU ekleme/silme ile sınırsız GPU desteği |
| 🖥️ **Notebook Ekran Boyutu** | İnç cinsinden ekran boyutu tanımlama |
| 🪟 **İşletim Sistemi** | FreeDOS ve Windows (özelleştirilebilir ad) seçenekleri |

### Fiyatlandırma & Hesaplama
- **KDV Hesaplaması:** Özelleştirilebilir KDV oranı ile otomatik hesaplama
- **Hedef Kâr Marjı:** Şirket kâr oranı üzerinden satış fiyatı belirleme
- **Pazaryeri Kâr Marjı:** Ek pazaryeri komisyonu dahil nihai fiyat hesaplama
- **Kartezyen Çarpım:** Tüm bileşen kombinasyonlarının otomatik oluşturulması

### Excel Çıktısı
- 📊 **17 sütunlu detaylı konfigürasyon matrisi**
- 🎨 **Renk kodlu sütunlar** (maliyet, GK satış, pazaryeri satış)
- 📌 **Otomatik barkod üretimi** (temel barkod + sıra numarası)
- 🔒 **Dondurulmuş başlık satırı** ile kolay navigasyon
- 💰 **Para birimi ve yüzde formatları** otomatik uygulanır

### Diğer
- 🔄 **Otomatik güncelleme** – GitHub Release üzerinden sessiz güncelleme
- 🔁 **Form sıfırlama** – Tek tıkla tüm alanları temizleme
- 🖱️ **Kaydırılabilir arayüz** – Mouse tekerleği ile kolay navigasyon
- 🎨 **Göz dostu tasarım** – Sıcak tonlarda soft renk paleti

---

## 📥 Kurulum

### Hazır Kurulum Paketi (Önerilen)

1. Bu repodaki **Releases** sayfasından en güncel `VCS_v2_Setup.exe` dosyasını indirin.
2. İndirdiğiniz Setup dosyasına çift tıklayarak kurulum sihirbazını başlatın.
3. Kurulumu tamamladıktan sonra masaüstünüzdeki kısayoldan uygulamayı başlatabilirsiniz.

> **Not:** Uygulama yönetici hakları gerektirmez ve kullanıcı dizinine (`%LOCALAPPDATA%\Programs`) kurulur.

---

## 💡 Kullanım

1. **Cihaz Bilgilerini Girin** – Model adı ve orijinal barkod numarasını yazın.
2. **Maliyet Ayarlarını Belirleyin** – Kasa maliyeti ($), KDV oranı, GK kâr oranı ve pazaryeri kâr oranını girin.
3. **Bileşenleri Seçin** – İstediğiniz bileşen kategorilerini aktif edin ve her birinin maliyetini dolar cinsinden girin.
4. **Excel Çıktısı Alın** – "EXCEL ÇIKTISI AL" butonuna tıklayarak tüm varyantları içeren Excel dosyasını oluşturun.

---

## 🔄 Otomatik Güncellemeler

Uygulamanın içerisinde dahili bir otomatik güncelleme modülü bulunmaktadır:

1. Uygulama her açılışta arka planda güncellemeleri kontrol eder.
2. Yeni bir sürüm tespit edildiğinde güncelleme bildirimi gözükür.
3. "Güncelle" butonuna tıkladığında, yeni sürüm indirilir.
4. İndirme tamamlandıktan sonra bir hata mesajı gelmesini beklemelisiniz, hata mesajı geldikten sonra hata penceresini kapatın ve uygulamayı açtığınızda yeni sürüme geçmiş olacaktır.

---

## 📝 Değişiklik Günlüğü

### v2.2.11 (Güncel)
- 🆕 Notebook RAM: Manuel mod eklendi (2 RAM slotu + maliyet girişi)
- 🗑️ Onboard seçenekleri kaldırıldı

### v2.2.10
- 📐 Notebook ekran boyutu bileşeni eklendi
- 🎨 Arayüz iyileştirmeleri

---

## 🛠️ Gereksinimler

| Gereksinim | Minimum |
|-----------|---------|
| İşletim Sistemi | Windows 10/11 |
| Python (kaynak kod için) | 3.8+ |
| Bağımlılıklar | `openpyxl` |

---

<div align="center">
  <i>© 2026 Umut Talip PEHLİVAN</i>
  <br><br>
  <b>VCS v2</b> ile bilgisayar konfigürasyonlarınızı profesyonelce yönetin. 🚀
</div>
