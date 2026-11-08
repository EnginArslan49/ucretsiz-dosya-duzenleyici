# 📁 Dosya Düzenleyici

> Dosyalarınızı uzantılarına göre otomatik olarak düzenleyen, kullanıcı dostu bir masaüstü uygulaması.

![Python](https://img.shields.io/badge/Python-3.7%2B-blue?style=flat-square&logo=python)
![Tkinter](https://img.shields.io/badge/GUI-Tkinter-green?style=flat-square)
![Platform](https://img.shields.io/badge/Platform-Windows-lightgrey?style=flat-square&logo=windows)
![License](https://img.shields.io/badge/License-MIT-yellow?style=flat-square)
![Version](https://img.shields.io/badge/Version-1.0.0-orange?style=flat-square)

**Geliştirici:** Engin ARSLAN  
**Sürüm:** 1.0.0  
**Lisans:** MIT

---

## 🌐 Bağlantılar

[![GitHub](https://img.shields.io/badge/GitHub-EnginArslan49-333333?style=for-the-badge&logo=github&logoColor=white)](https://github.com/EnginArslan49?tab=repositories)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Engin_Arslan-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/engin-arslan-49e04/)
[![Instagram](https://img.shields.io/badge/Instagram-49engn04-E1306C?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/49engn04)
[![YouTube](https://img.shields.io/badge/YouTube-@ramkafe-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@ramkafe)

---

## 📋 İçindekiler

- [Uygulama Hakkında](#-uygulama-hakkında)
- [Özellikler](#-özellikler)
- [Ekran Görüntüsü](#-ekran-görüntüsü)
- [Kurulum](#-kurulum)
- [Kullanım](#-kullanım)
- [Klasör Yapısı](#-klasör-yapısı)
- [EXE Olarak Derleme](#-exe-olarak-derleme)
- [Teknik Detaylar](#-teknik-detaylar)
- [Güvenlik ve Veri Bütünlüğü](#-güvenlik-ve-veri-bütünlüğü)
- [SSS](#-sss-sıkça-sorulan-sorular)
- [Sorun Giderme](#-sorun-giderme)
- [Katkıda Bulunma](#-katkıda-bulunma)
- [Lisans](#-lisans)
- [İletişim](#-iletişim)

---

## 🎯 Uygulama Hakkında

**Dosya Düzenleyici**, karışık dosyalarla dolu bir klasörü saniyeler içinde düzenli bir arşive dönüştüren bir masaüstü uygulamasıdır. Seçtiğiniz klasördeki tüm dosyaları **uzantılarına göre** otomatik olarak gruplandırır ve `Düzenleme` adında bir alt klasör altında toplar.

### Neden Bu Uygulama?

- 🗂️ **İndirilenler klasörünüz dağınık mı?** Tek tıkla düzenleyin.
- 📸 **Fotoğraf, video ve belgeler birbirine mi karıştı?** Uzantılarına göre ayırın.
- 🚀 **Dosya yönetimiyle vakit kaybetmek istemiyor musunuz?** Otomatikleştirin.
- 💾 **Hiçbir veri kaybı olmadan** güvenli bir şekilde organize edin.

---

## ✨ Özellikler

### Temel Özellikler
- ✅ **Otomatik Klasörleme:** Dosyalar uzantılarına göre (`jpg`, `pdf`, `mp4` vb.) alt klasörlere taşınır.
- ✅ **Düzenleme Klasörü:** Tüm düzenlemeler `Düzenleme/` adında bir ana klasör altında yapılır.
- ✅ **Uzantısız Dosyalar:** Uzantısı olmayan dosyalar `uzantisiz/` klasörüne taşınır.
- ✅ **Çakışma Önleme:** Aynı isimli dosyalar otomatik olarak numaralandırılır (`_1`, `_2`...).
- ✅ **Büyük/Küçük Harf Duyarsız:** `.JPG`, `.jpg`, `.Jpg` hepsi aynı `jpg/` klasörüne gider.

### Kullanıcı Deneyimi
- 🎨 **Modern Arayüz:** Tkinter ile tasarlanmış şık ve sade bir GUI.
- 🖥️ **Ekran Ortası:** Uygulama dikey ve yatay olarak ekranın tam ortasında açılır.
- 📊 **Canlı İşlem Günlüğü:** Her dosyanın taşınma durumu anlık olarak gösterilir.
- 📖 **Entegre Kullanım Kılavuzu:** Uygulama içinden erişilebilen detaylı rehber.
- 🎉 **Profesyonel Başarı Bildirimi:** İşlem sonunda bilgilendirici bir teşekkür penceresi.
- ⚡ **Donmayan Arayüz:** İşlem arka planda çalışır (threading), arayüz donmaz.

### Sosyal Medya Entegrasyonu
- 🌐 **Renkli Sosyal Medya Butonları:** GitHub, LinkedIn, Instagram ve YouTube ikonları ile tek tıkla erişim.
- 🔗 **Başarı Penceresinde de Linkler:** İşlem sonrası açılan pencerede de sosyal medya butonları yer alır.

### Güvenlik
- 🔒 **Kontrollü Çıkış:** X, Alt+F4 veya ESC ile çıkış **engellenir** — sadece onaylı çıkış.
- 🛡️ **Kendi EXE'sini Korur:** Uygulama kendi çalıştırılabilir dosyasını taşımaz.
- ⚠️ **İşlem Sırasında Kilit:** İşlem devam ederken çıkış yapılamaz.
- 💾 **Veri Kaybı Yok:** Dosyalar **silinmez**, sadece taşınır.

### Teknik
- 🚀 **Tek EXE:** PyInstaller ile tek dosyaya dönüştürülebilir.
- 🖥️ **Platform Bağımsız:** Windows'ta test edilmiştir (Linux/macOS'ta da çalışır).
- 📦 **Sıfır Bağımlılık:** Sadece Python standart kütüphaneleri kullanır.

---

## 🖼️ Ekran Görüntüsü

```
┌──────────────────────────────────────────────────────────┐
│              📁 DOSYA DÜZENLEYİCİ                        │
│      Dosyalarınızı uzantılarına göre otomatik düzenleyin │
│                                                          │
│   [❓ NASIL KULLANILIR?]                 [❌ ÇIKIŞ]      │
│                                                          │
│   ┌────────────────────────────────────────────────┐     │
│   │ Düzenlenecek Klasör:                           │     │
│   │ [C:\Users\Kullanıcı\Downloads.....] [Gözat...] │     │
│   └────────────────────────────────────────────────┘     │
│                                                          │
│            [🗂️  DÜZENLEMEYİ BAŞLAT]                      │
│                                                          │
│   İşlem Günlüğü:                                         │
│   ┌────────────────────────────────────────────────┐     │
│   │   ✔ foto1.jpg → Düzenleme/jpg/                 │     │
│   │   ✔ belge.pdf → Düzenleme/pdf/                 │     │
│   │ ============================================   │     │
│   │ 📊 Taşınan dosya : 3   |   Hata : 0            │     │
│   └────────────────────────────────────────────────┘     │
│                                                          │
│   🌐 Beni Sosyal Medyada Takip Edin                      │
│   [🐙 GitHub] [💼 LinkedIn] [📸 Instagram] [▶ YouTube]   │
│                                                          │
│          © Engin ARSLAN • Tüm hakları saklıdır.          │
└──────────────────────────────────────────────────────────┘
```

---

## 🚀 Kurulum

### Gereksinimler

| Gereksinim | Minimum | Önerilen |
|------------|---------|----------|
| **Python** | 3.7 | 3.10+ |
| **İşletim Sistemi** | Windows 7 | Windows 10/11 |
| **RAM** | 64 MB | 128 MB+ |
| **Disk Alanı** | 5 MB (kaynak) / 15 MB (EXE) | — |

### Yöntem 1: Doğrudan Python ile Çalıştırma

```bash
# 1. Python'un kurulu olduğundan emin olun
python --version

# 2. Depoyu klonlayın
git clone https://github.com/EnginArslan49/dosya-duzenleyici.git
cd dosya-duzenleyici

# 3. Uygulamayı çalıştırın
python dosya_duzenleyici.py
```

### Yöntem 2: EXE Olarak Kullanma

`Releases` sekmesinden `DosyaDuzenleyici_EnginARSLAN.exe` dosyasını indirin ve çift tıklayarak çalıştırın. **Python kurulumu gerekmez.**

> ⚠️ **Windows SmartScreen Uyarısı:** İmzasız EXE dosyaları ilk çalıştırmada uyarı verebilir. "Daha fazla bilgi" → "Yine de çalıştır" seçeneğini kullanın.

---

## 📖 Kullanım

### Hızlı Başlangıç (3 Adım)

```
1. GÖZAT  →  Düzenlemek istediğiniz klasörü seçin
2. BAŞLAT →  "DÜZENLEMEYİ BAŞLAT" butonuna tıklayın
3. TAMAM  →  Başarı penceresini onaylayın
```

### Detaylı Kullanım

#### Adım 1: Klasör Seçimi
- **"Gözat..."** butonuna tıklayın.
- Açılan dosya gezgininden düzenlemek istediğiniz klasörü seçin.
- Seçilen yol ekranda görüntülenecektir.

#### Adım 2: İşlemi Başlatma
- **"🗂️ DÜZENLEMEYİ BAŞLAT"** butonuna tıklayın.
- İşlem arka planda başlar; arayüz kullanılabilir kalır.
- **"İşlem Günlüğü"** alanından her dosyanın durumunu canlı izleyebilirsiniz.

#### Adım 3: Sonuç Kontrolü
- İşlem bittiğinde **başarı penceresi** açılır.
- Taşınan dosya sayısı ve hedef klasör bilgisi gösterilir.
- **"TAMAM"** butonuna basarak pencereyi kapatın.

### Kullanım Kılavuzu

Uygulama içindeki **"❓ NASIL KULLANILIR?"** butonuna tıklayarak şu bilgilere erişebilirsiniz:
- Uygulamanın amacı ve örnekler
- Adım adım kullanım talimatları
- Klasör yapısı karşılaştırması (öncesi/sonrası)
- Önemli notlar ve ipuçları
- Çıkış davranışları
- Sosyal medya bağlantıları
- SSS

---

## 🗂️ Klasör Yapısı

### İşlem Öncesi (Karışık)

```
Belgelerim/
├── foto1.jpg
├── foto2.JPG
├── belge.pdf
├── rapor.docx
├── video.mp4
├── muzik.mp3
└── README
```

### İşlem Sonrası (Düzenli)

```
Belgelerim/
├── Düzenleme/                    ← Yeni oluşturulan klasör
│   ├── jpg/
│   │   ├── foto1.jpg
│   │   └── foto2.JPG
│   ├── pdf/
│   │   └── belge.pdf
│   ├── docx/
│   │   └── rapor.docx
│   ├── mp4/
│   │   └── video.mp4
│   ├── mp3/
│   │   └── muzik.mp3
│   └── uzantisiz/
│       └── README
└── (Diğer alt klasörler etkilenmez)
```

### Çakışma Örneği

Eğer `Düzenleme/jpg/` klasöründe zaten `foto1.jpg` varsa:

```
Belgelerim/Düzenleme/jpg/
├── foto1.jpg      ← Önceden var olan
└── foto1_1.jpg    ← Yeni taşınan (otomatik numaralandırıldı)
```

---

## 🛠️ EXE Olarak Derleme

### 1. PyInstaller Kurulumu

```bash
pip install pyinstaller
```

### 2. Tek EXE Oluşturma

```bash
pyinstaller --onefile --windowed --name "DosyaDuzenleyici_EnginARSLAN" dosya_duzenleyici.py
```

### 3. Parametreler

| Parametre | Açıklama |
|-----------|----------|
| `--onefile` | Tek bir `.exe` dosyası oluşturur |
| `--windowed` | Konsol penceresi açmaz (GUI uygulaması için) |
| `--name` | Çıktı dosyasının adı |
| `--icon=ikon.ico` | *(Opsiyonel)* Özel simge ekler |
| `--uac-admin` | *(Opsiyonel)* Yönetici izni ister |
| `--clean` | *(Opsiyonel)* Önceki derleme kalıntılarını temizler |

### 4. Gelişmiş Derleme Komutu

```bash
pyinstaller --onefile --windowed --clean --name "DosyaDuzenleyici_EnginARSLAN" --icon "ikon.ico" dosya_duzenleyici.py
```

### 5. Sonuç

Derleme sonrası dosyalar:

```
proje/
├── build/                               ← Geçici derleme dosyaları (silinebilir)
├── dist/
│   └── DosyaDuzenleyici_EnginARSLAN.exe ← ✅ KULLANIMA HAZIR
├── dosya_duzenleyici.py
└── DosyaDuzenleyici_EnginARSLAN.spec
```

> 💡 **İpucu:** EXE boyutunu küçültmek için `--exclude-module` parametresi kullanabilirsiniz. Tkinter uygulamaları için tipik EXE boyutu **10-15 MB** arasındadır.

---

## 🔧 Teknik Detaylar

### Kullanılan Teknolojiler

| Teknoloji | Amaç |
|-----------|------|
| **Python 3.7+** | Ana programlama dili |
| **Tkinter** | Grafik kullanıcı arayüzü (GUI) |
| **threading** | Arka plan işlemleri (donmayan arayüz) |
| **shutil** | Dosya taşıma işlemleri |
| **os** | Dosya sistemi işlemleri |
| **webbrowser** | Sosyal medya bağlantılarını açma |
| **PyInstaller** | EXE paketleme |

### Mimari Genel Bakış

```
┌────────────────────────────────────────────┐
│           DosyaDuzenleyici (Sınıf)         │
├────────────────────────────────────────────┤
│  • arayuz_olustur()      → GUI elemanları  │
│  • sosyal_medya_olustur()→ Sosyal butonlar │
│  • sosyal_medya_ac()     → Link açıcı      │
│  • klasor_sec()          → Klasör seçimi   │
│  • duzenlemeyi_baslat()  → İşlem başlatıcı │
│  • duzenle()             → Ana mantık      │
│  • islemi_bitir()        → İşlem sonlandırıcı │
│  • basari_mesaji_goster()→ Başarı penceresi│
│  • kullanim_kilavuzu_goster() → Rehber     │
│  • guvenli_cikis()       → Kontrollü çıkış │
└────────────────────────────────────────────┘
```

### Ekran Ortalama Formülü

```python
genislik = 680
yukseklik = 720
ekran_genislik = root.winfo_screenwidth()
ekran_yukseklik = root.winfo_screenheight()
x = (ekran_genislik - genislik) // 2
y = (ekran_yukseklik - yukseklik) // 2
root.geometry(f"{genislik}x{yukseklik}+{x}+{y}")
```

---

## 🔒 Güvenlik ve Veri Bütünlüğü

### Veri Kaybı Riski: **YOK**

- ❌ Dosyalar **silinmez**
- ❌ Dosyalar **üzerine yazılmaz**
- ❌ İçerik **değiştirilmez**
- ✅ Dosyalar sadece **taşınır** (`shutil.move`)

### Kontrollü Çıkış Mekanizması

| Tetikleyici | Davranış |
|-------------|----------|
| **X (Çarpı)** | Onay sorar → Onaylanırsa çıkar |
| **Alt+F4** | Onay sorar → Onaylanırsa çıkar |
| **ESC** | Onay sorar → Onaylanırsa çıkar |
| **ÇIKIŞ butonu** | Onay sorar → Onaylanırsa çıkar |
| **İşlem sırasında** | ⚠️ Çıkış **engellenir** |

---

## ❓ SSS (Sıkça Sorulan Sorular)

### S1: Dosyalarım silinir mi?
**C:** Hayır. Dosyalar **yalnızca taşınır**, hiçbir şekilde silinmez veya içerikleri değiştirilmez.

### S2: Alt klasörlerdeki dosyalar da düzenlenir mi?
**C:** Hayır. Yalnızca seçtiğiniz klasörün **birinci seviyesindeki** dosyalar işlenir. Alt klasörlerin içeriğine dokunulmaz.

### S3: İşlemi geri alabilir miyim?
**C:** Otomatik geri alma yoktur. Ancak taşınan dosyaları `Düzenleme/` klasöründen alıp elle eski yerlerine taşıyabilirsiniz.

### S4: 10.000+ dosyalı bir klasörde çalışır mı?
**C:** Evet, ancak işlem biraz zaman alabilir. İşlem Günlüğü'nden ilerlemeyi izleyebilirsiniz.

### S5: EXE'yi nereye koymalıyım?
**C:** **İstediğiniz yere** koyabilirsiniz (Masaüstü önerilir). EXE, düzenlenecek klasörün içinde olmak zorunda değildir. Uygulama içinden "Gözat" ile klasörü seçersiniz.

### S6: Uygulama kendi EXE'sini taşır mı?
**C:** Hayır. Kod, `sys.executable` kontrolü ile kendi EXE dosyasını **otomatik atlar**.

### S7: `.JPG` ve `.jpg` ayrı klasörlere mi gider?
**C:** Hayır. Uzantılar küçük harfe çevrildiği için ikisi de `jpg/` klasörüne gider.

### S8: Aynı isimde iki dosya varsa ne olur?
**C:** Otomatik olarak numaralandırılır: `dosya.jpg`, `dosya_1.jpg`, `dosya_2.jpg`...

### S9: Uzantısız dosyalar nereye gider?
**C:** `Düzenleme/uzantisiz/` klasörüne taşınır.

### S10: Windows Defender uyarı veriyor, ne yapmalıyım?
**C:** PyInstaller ile üretilen imzasız EXE'ler ilk çalıştırmada uyarı verebilir. "Daha fazla bilgi" → "Yine de çalıştır" seçin. Kalıcı çözüm için kod imzalama sertifikası gerekir.

### S11: Sosyal medya butonları çalışmıyor, ne yapmalıyım?
**C:** Butonlar varsayılan tarayıcınızı kullanarak ilgili sayfayı açar. Tarayıcınızın varsayılan olarak ayarlı olduğundan emin olun. Sorun devam ederse bağlantıları elle tarayıcıya yapıştırabilirsiniz.

---

## 🐛 Sorun Giderme

### Sorun: Uygulama açılmıyor
**Çözüm:**
- Python 3.7+ kurulu mu kontrol edin: `python --version`
- Tkinter kurulu mu kontrol edin: `python -c "import tkinter"`
- Linux'ta: `sudo apt-get install python3-tk`
- macOS'ta: `brew install python-tk`

### Sorun: "Permission denied" hatası
**Çözüm:**
- Klasörün yazma izni olduğundan emin olun
- EXE'yi yönetici olarak çalıştırın (sağ tık → Yönetici olarak çalıştır)
- Klasör başka bir program tarafından kullanılıyor olabilir

### Sorun: EXE çok yavaş açılıyor
**Çözüm:**
- İlk açılışta Windows Defender tarama yapar; sonraki açılışlar hızlıdır
- `--onedir` parametresi ile klasör olarak derleyin (daha hızlı açılır)

### Sorun: EXE çalışmıyor / hemen kapanıyor
**Çözüm:**
- `--windowed` yerine `--console` ile derleyin, hata mesajlarını görün
- Antivirüs yazılımını geçici olarak devre dışı bırakın
- EXE'yi yönetici olarak çalıştırın

### Sorun: Uygulama ekranın ortasında açılmıyor
**Çözüm:**
- Çoklu monitör kullanıyorsanız, birincil monitörde açılır
- Ekran çözünürlüğünüz çok düşükse (ör. 800x600), pencere taşabilir

### Sorun: İşlem Günlüğü boş kalıyor
**Çözüm:**
- Klasörde taşınacak dosya olmayabilir (boş klasör veya tümü zaten düzenlenmiş)
- "Gözat" ile doğru klasörü seçtiğinizden emin olun

---

## 🤝 Katkıda Bulunma

Katkılarınız memnuniyetle karşılanır! Lütfen şu adımları izleyin:

### 1. Fork'layın
GitHub üzerinden projeyi fork'layın: [EnginArslan49/dosya-duzenleyici](https://github.com/EnginArslan49?tab=repositories)

### 2. Özellik Dalı Oluşturun
```bash
git checkout -b ozellik/yeni-ozellik-adi
```

### 3. Değişikliklerinizi Yapın
Kod standartlarına uyun:
- **PEP 8** uyumlu Python kodu
- Anlamlı değişken/fonksiyon isimleri
- Türkçe yorumlar ve docstring'ler

### 4. Test Edin
```bash
python dosya_duzenleyici.py
```

### 5. Commit ve Push
```bash
git add .
git commit -m "feat: yeni özellik eklendi"
git push origin ozellik/yeni-ozellik-adi
```

### 6. Pull Request Açın
Değişikliklerinizi açıklayan detaylı bir PR oluşturun.

### Katkı Kuralları
- ✅ Türkçe commit mesajları tercih edilir
- ✅ Kodunuzu yorumlayın
- ✅ Test edin
- ❌ Var olan özellikleri bozmayın

---

## 📝 Sürüm Geçmişi

### v1.0.1 (Sosyal Medya Güncellemesi)
- ✅ Sosyal medya butonları eklendi (GitHub, LinkedIn, Instagram, YouTube)
- ✅ Uygulama ekranın ortasında açılıyor
- ✅ Başarı penceresinde de sosyal medya butonları
- ✅ Kullanım kılavuzuna sosyal medya bölümü eklendi

### v1.0.0 (İlk Sürüm)
- ✅ Temel dosya düzenleme işlevi
- ✅ Uzantıya göre otomatik klasörleme
- ✅ "Düzenleme" ana klasörü
- ✅ Çakışma önleme (numaralandırma)
- ✅ Kontrollü çıkış mekanizması
- ✅ Entegre kullanım kılavuzu
- ✅ Profesyonel başarı penceresi
- ✅ Donmayan arayüz (threading)
- ✅ EXE olarak derleme desteği

---

## 📄 Lisans

Bu proje **MIT Lisansı** altında lisanslanmıştır. Detaylar için [LICENSE](LICENSE) dosyasına bakın.

```
MIT License

Copyright (c) 2024 Engin ARSLAN

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

---

## 📞 İletişim & Sosyal Medya

**Geliştirici:** Engin ARSLAN

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-EnginArslan49-333333?style=for-the-badge&logo=github&logoColor=white)](https://github.com/EnginArslan49?tab=repositories)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Engin_Arslan-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/engin-arslan-49e04/)
[![Instagram](https://img.shields.io/badge/Instagram-49engn04-E1306C?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/49engn04)
[![YouTube](https://img.shields.io/badge/YouTube-@ramkafe-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@ramkafe)

</div>

| Platform | Bağlantı |
|----------|----------|
| 🐙 **GitHub** | [github.com/EnginArslan49](https://github.com/EnginArslan49?tab=repositories) |
| 💼 **LinkedIn** | [linkedin.com/in/engin-arslan-49e04](https://www.linkedin.com/in/engin-arslan-49e04/) |
| 📸 **Instagram** | [instagram.com/49engn04](https://www.instagram.com/49engn04) |
| ▶ **YouTube** | [youtube.com/@ramkafe](https://www.youtube.com/@ramkafe) |

### Hata Bildirimi
Hata bulduysanız lütfen [Issues](https://github.com/EnginArslan49?tab=repositories) sekmesinden bildirin. Şunları eklemeyi unutmayın:
- Hatanın ekran görüntüsü
- İşletim sistemi ve Python sürümü
- Hatanın oluştuğu adımlar

### Özellik İsteği
Yeni bir özellik mi istiyorsunuz? [Issues](https://github.com/EnginArslan49?tab=repositories) sekmesinden `feature request` etiketiyle önerinizi paylaşın.

---

## 🙏 Teşekkürler

- **Python** topluluğuna
- **Tkinter** geliştiricilerine
- **PyInstaller** ekibine
- Ve bu uygulamayı kullanan **siz değerli kullanıcılara**

---

<div align="center">

**⭐ Bu projeyi faydalı bulduysanız yıldız vermeyi unutmayın! ⭐**

**Engin ARSLAN tarafından ❤️ ile geliştirilmiştir.**

© 2024 Engin ARSLAN — Tüm hakları saklıdır.

</div>