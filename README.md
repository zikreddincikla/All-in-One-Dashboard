# 🚀 Açık Kaynak All-in-One Dashboard & Converter - Yol Haritası

---

## 📋 Faz 1: Proje Kurulumu ve Altyapı Hazırlığı

- [x] GitHub'da yeni bir repository oluştur (Lisans: MIT seçildi)
- [ ] Sayfanın sağ altındaki yeşil **"Create repository"** butonuna basarak projeyi GitHub üzerinde yayınla
- [ ] Repository'yi bilgisayarına klonla (`git clone ...`)
- [ ] ASP.NET Core Web API projesini Clean Architecture yapısında kur (`Core`, `Infrastructure`, `API`)
- [ ] React projesini Vite ile oluştur
- [ ] Tailwind CSS ve Shadcn UI kütüphanelerini frontend projesine entegre et

---

## 🛠️ Faz 2: Temel Backend Servislerinin Geliştirilmesi

### 2.1. Widget Veri Servisleri
- [ ] Merkez bankası veya ücretsiz döviz API'si için servis yaz
- [ ] Open-Meteo veya OpenWeatherMap API için hava durumu servisini tamamla
- [ ] Dış API isteklerini sınırlandırmak için `IMemoryCache` altyapısını kur

### 2.2. Dosya İşleme & Dönüştürücü Servisleri
- [ ] `SixLabors.ImageSharp` kullanarak resim dönüştürme endpoint'lerini yaz (WebP, PNG, JPG, SVG, BMP vb.)
- [ ] `Transformers.js` / WebAssembly veya ONNX modelleri ile arka plan silme servisini entegre et
- [ ] `PdfSharp` veya `QuestPDF` ile PDF okuma ve işleme servislerini oluştur

---

## 🧠 Faz 3: Yapay Zeka Entegrasyonları (AI Hub)

### 3.1. Akıllı Asistan & Yönlendirme
- [ ] `Semantic Kernel` veya `Microsoft.Extensions.AI` paketlerini backend'e ekle
- [ ] Doğal dilde verilen komutları doğru API endpoint'ine yönlendiren asistan mantığını yaz

### 3.2. PDF ve Sunum AI Düzeltme
- [ ] PDF içeriğini analiz edip eksik metin, kaynakça ve sayfa sırasını tahmin eden LLM prompt'larını hazırla
- [ ] PDF metinlerini slayt düzenine dönüştüren PPTX yapısını kurgula (`DocumentFormat.OpenXml`)

### 3.3. AI Haber Özetleyici
- [ ] Güncel haberleri çekip LLM ile özet çıkaran arka plan görevini (`IHostedService`) yaz

---

## 🎨 Faz 4: React Frontend & Dashboard Geliştirme

### 4.1. Layout ve Tema
- [ ] Tailwind `dark` sınıfı ve LocalStorage kontrolü ile Gece Modu (Dark Mode) geçişini yap
- [ ] `react-grid-layout` ile kullanıcının widget yerlerini özelleştirebileceği yapıyı kur

### 4.2. Ana Sayfa Widget Bileşenleri
- [ ] Tarayıcı konum izni (`navigator.geolocation`) ile anlık hava durumu gösteren widget'ı yaz
- [ ] Kullanıcının dinamik saat dilimi ve döviz kartı ekleyebileceği panelleri geliştir
- [ ] Seçilen kategoriye göre AI haber özetlerini listeleyen kartı oluştur

### 4.3. Dönüştürücü Arayüzleri
- [ ] Sürükle-bırak (Drag-and-Drop) dosya yükleme alanlarını tasarla
- [ ] Format seçimi ve AI düzeltme seçenekleri için arayüz elemanlarını ekle
- [ ] İlerleme çubuğu (Progress Bar) ve bildirim panelini tamamla

---

## 🧪 Faz 5: Test, Optimizasyon ve Yayınlama

### 5.1. Test & Performans
- [ ] Backend için `xUnit` ile Unit Test'ler yaz
- [ ] Büyük dosya dönüştürmelerinde bellek kullanımını (Memory Leak) kontrol et
- [ ] Mobil uyumluluk (Responsive Design) testlerini tamamla

### 5.2. Yayınlama (Deployment)
- [ ] Backend'i Dockerize edip sunucuya (VPS, Railway, Render vb.) canlıya al
- [ ] Frontend'i Vercel veya Netlify üzerinde yayınla

---

## 🤝 Faz 6: Açık Kaynak Topluluk Hazırlıkları

- [ ] Kurulum adımlarını ve mimariyi anlatan detaylı bir `README.md` hazırla
- [ ] Katkıda bulunmak isteyenler için `CONTRIBUTING.md` dosyası oluştur
- [ ] GitHub üzerinde Issue ve Pull Request şablonlarını ekle
