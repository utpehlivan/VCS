<div align="center">
  <h1>💻 VCS v2</h1>
  <h3>Varyant Konfigürasyon Sistemi</h3>
  <p>Bilgisayar bileşenleri ve donanım varyantları için gelişmiş maliyet ve kâr hesaplama otomasyonu.</p>

  ![Sürüm](https://img.shields.io/badge/Sürüm-v2.2.20-blue?style=for-the-badge)
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
| 🧠 **Normal RAM** | 4GB – 256GB arası standart RAM seçenekleri (Standart / Manuel mod) |
| 💻 **Notebook RAM** | 4GB – 256GB arası notebook RAM seçenekleri (Standart / Manuel mod) |
| 🔒 **ECC RAM** | 16GB – 512GB arası sunucu sınıfı RAM seçenekleri (Standart / Manuel mod) |
| 💾 **M.2 SSD** | 128GB – 8TB arası NVMe SSD seçenekleri |
| 📀 **SATA SSD** | 128GB – 8TB arası SATA SSD seçenekleri |
| 🗄️ **HDD** | 1TB – 20TB arası sabit disk seçenekleri |
| 🎮 **Ekran Kartı (GPU)** | Dinamik GPU ekleme/silme ile sınırsız GPU desteği |
| 🖥️ **Notebook Ekran Boyutu** | İnç cinsinden ekran boyutu tanımlama |
| 🪟 **İşletim Sistemi** | FreeDOS ve Windows (özelleştirilebilir ad) seçenekleri |

> **Not:** Tüm RAM bileşenleri (Normal, Notebook, ECC) iki modda çalışır:
> - **Standart mod:** Önceden tanımlı kapasite seçeneklerinden maliyet girişi
> - **Manuel mod:** RAM 1 (GB) + RAM 2 (GB) + Maliyet şeklinde serbest satır girişi (dinamik satır ekleme/silme)

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
2. **Maliyet Ayarlarını Belirleyin** – Taban Maliyet ($), KDV oranı, GK kâr oranı ve pazaryeri kâr oranını girin.
3. **Bileşenleri Seçin** – İstediğiniz bileşen kategorilerini aktif edin ve her birinin maliyetini dolar cinsinden girin.
4. **Excel Çıktısı Alın** – "EXCEL ÇIKTISI AL" butonuna tıklayarak tüm varyantları içeren Excel dosyasını oluşturun.

---

## 🔄 Otomatik Güncellemeler

Uygulamanın içerisinde dahili bir otomatik güncelleme modülü bulunmaktadır:

1. Uygulama her açılışta arka planda güncellemeleri kontrol eder.
2. Yeni bir sürüm tespit edildiğinde güncelleme bildirimi gözükür.
3. "Güncelle" butonuna tıkladığında, yeni sürüm indirilir.
4. İndirme tamamlandıktan sonra uygulama tamamen kapanacaktır. Uygulamayı yeniden açtığınızda yeni sürüme geçmiş olursunuz.

---

## 📝 Değişiklik Günlüğü

### v2.2.20 (Güncel)
- 🚀 Güncelleme dosyasının indirme hatası giderildi.

### v2.2.19
- 🚀 Genel iyileştirmeler ve hata düzeltmeleri yapıldı.

### v2.2.18
- 🚀 Genel iyileştirmeler ve hata düzeltmeleri yapıldı.

### v2.2.17
- 🚀 Genel iyileştirmeler ve hata düzeltmeleri yapıldı.
- 🛑 Otomatik yeniden başlatma kaldırıldı, güncelleme sonrası program sadece kapanır.
- 🏷️ Uygulama içi etiketlerde iyileştirmeler yapıldı ("Cihazın Maliyeti" -> "Taban Maliyet").

### v2.2.16

### v2.2.15
- 🚀 Genel iyileştirmeler ve hata düzeltmeleri yapıldı

### v2.2.13
- 🏷️ Normal RAM ve ECC RAM: Standart/Manuel mod eklendi. Uygulama ismi güncellendi. Ram seçenekleri güncellendi.

### v2.2.12
- 🆕 Normal RAM: Standart/Manuel mod eklendi (2 RAM slotu + maliyet girişi)
- 🆕 ECC RAM: Standart/Manuel mod eklendi (2 RAM slotu + maliyet girişi)
- 🏷️ Uygulama ismi güncellendi

### v2.2.11
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
