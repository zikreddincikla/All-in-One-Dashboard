# All-in-One Dashboard & Converter: Yol Haritası

---

## Yapısal Değişiklikler

- [ ] Katman katman değil, **dikey dilimlerle** ilerle (her özellik backend + endpoint + React bileşeniyle baştan sona bitsin)
- [ ] Frontend'i erkene çek: dashboard iskeleti ve dark mode kurulumdan hemen sonra gelsin
- [ ] AI asistanı en sona taşı, haber özetleyiciyi widget fazına al
- [ ] Clean Architecture'ı hafiflet: `Core/Infrastructure/API` yeterli, gereksiz interface/repository yazma

---

## Teknik Düzeltmeler

- [ ] Arka plan silmede `Transformers.js` (tarayıcı) ile `Microsoft.ML.OnnxRuntime` (backend) arasında birini seç
- [ ] PDF okuma için `QuestPDF` yerine `PdfPig` kullan (QuestPDF yalnızca üretir)
- [ ] SVG ve HEIC/AVIF'i MVP'den çıkar, sonra `Magick.NET` ile ekle
- [ ] Raster→SVG için "dönüştürme" yerine "vektörleştirme (trace)" ifadesini kullan
- [ ] Docker'ı Faz 0'a al, Vercel/Netlify + ayrı backend için CORS ve ortam değişkenlerini erken test et
- [ ] GitHub Actions CI'ı (build + test) ilk günden kur
- [ ] Testleri sona bırakma, kritik servislerle birlikte yaz

---

## Faz 0: Temel (1 hafta)

- [ ] Repo, MIT lisansı, solution yapısı
- [ ] Vite + Tailwind + Shadcn kurulumu
- [ ] Dockerfile ve docker-compose
- [ ] GitHub Actions workflow
- [ ] Dashboard iskeleti
- [ ] Dark mode

## Faz 1: Widget MVP (2-3 hafta)

- [ ] Hava durumu widget'ı (Open-Meteo, anahtar gerektirmez)
- [ ] Dünya saatleri (backend'siz, `Intl` ile)
- [ ] Döviz paneli (Frankfurter API)
- [ ] `IMemoryCache` ile önbellekleme
- [ ] `react-grid-layout` ile sürükle-bırak yerleşim

## Faz 2: Resim Dönüştürücü (2 hafta)

- [ ] PNG / JPG / WebP / GIF / BMP / TIFF dönüşümü
- [ ] Drag-and-drop yükleme alanı
- [ ] Progress bar ve hata yönetimi
- [ ] Dosya boyutu ve tür sınırı
- [ ] İşlem sonrası dosya silme
- [ ] Birim testleri (xUnit)

## Faz 3: Açık Kaynak Yayını (birkaç gün)

- [ ] `README.md`
- [ ] `CONTRIBUTING.md`
- [ ] Issue ve PR şablonları
- [ ] "good first issue" etiketleri
- [ ] v0.1 yayını ve geri bildirim toplama

## Faz 4: Gelişmiş Araçlar

- [ ] Arka plan silme (ONNX Runtime + RMBG / U²-Net)
- [ ] HEIC / AVIF desteği (Magick.NET)
- [ ] AI haber özetleri (kullanıcı kendi API anahtarını girer)

## Faz 5: PDF Araçları

- [ ] PDF birleştir
- [ ] PDF böl
- [ ] PDF'ten metin çıkar (PdfPig)
- [ ] PDF→PPTX (OpenXML SDK), "deneysel" etiketiyle
- [ ] Kaynakça eşleştirme: çıkar veya "beta" olarak işaretle

## Faz 6: AI Hub

- [ ] Function calling ile mevcut araçları asistana bağla

---

## Son Tavsiye

İlk sürümde sözü az, işi çok tut. Küçük ama sağlam çalışan bir v0.1, her şeyi vaat eden ama yarım kalan bir projeden çok daha fazla katkıcı çeker. Kaynakça ve sayfa sırası tahmini gibi AI için gerçekçi olmayan vaatlerden kaçın.
