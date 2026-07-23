# Sigortam Cepte - Akıllı Kaza Asistanı

Anadolu Sigorta mobil uygulaması için tasarlanan **Akıllı Kaza Asistanı** konsept mockup'ıdır. Kullanıcıların kaza, arıza, yangın ve yaralanma gibi acil durumlarda adım adım yönlendirilmesini sağlayan interaktif bir prototiptir.

## Özellikler

### Ana Sayfa
- Modern gradient header ve glassmorphism kartlar
- Floating bottom navigation bar
- Hızlı işlem kartları (Araç Hasar, Sağlık Tazminat, Anlaşmalı Kurumlar)
- Sigorta ürünleri ve kampanya bölümleri
- Devam eden hasar dosyası takibi

### Acil Durum Senaryoları
| Senaryo | Açıklama |
|---------|----------|
| **Çarpışma** | Başka araçla kaza — QR ile karşı taraf davet, kroki çizimi, çift imza |
| **Tekli Kaza** | Bariyer/ağaç vb. — kamu malı hasar kontrolü, polis yönlendirme |
| **Arıza** | Yolda kalma — AI arıza teşhisi, yol yardım takibi (canlı ETA) |
| **Yangın** | Tahliye rehberi, 112 arama, itfaiyeye konum paylaşma |
| **Yaralanma** | 112 yönlendirme, en yakın hastaneler, ilk yardım adımları |

### Kaza Beyanı (5 Adım)
1. **Kişisel Bilgiler** — Otomatik doldurma
2. **Konum Bilgisi** — İnteraktif harita üzerinde konum işaretleme
3. **Ehliyet / Ruhsat** — Belge fotoğrafı çekme
4. **Olay Yeri Fotoğrafları** — Çoklu fotoğraf ekleme
5. **Kaza Anlatımı** — Yazılı veya sesli beyan (speech-to-text)

### Diğer Özellikler
- **AI Hasar Tespiti** — Fotoğraftan ön hasar tahmini ve maliyet analizi
- **Otomatik Kaza Tutanağı** — PDF oluşturma ve indirme
- **QR Kod ile Karşı Taraf Entegrasyonu** — SBM/TRAMER altyapısı üzerinden
- **Kroki Çizimi** — Dokunmatik canvas üzerinde kaza krokisi
- **Dijital İmza** — Her iki sürücü için imza alanı
- **KVKK Uyumu** — Her akış öncesi aydınlatma ve onay

## Teknoloji

- Tek dosya HTML/CSS/JS (framework bağımsız)
- [Tabler Icons](https://tabler.io/icons) ikon seti
- [jsPDF](https://github.com/parallax/jsPDF) ile PDF oluşturma
- Responsive tasarım (mobil öncelikli)

## Kullanım

Projeyi çalıştırmak için herhangi bir kurulum gerekmez. `sigortam-cepte-kaza-asistani-mockup.html` dosyasını tarayıcıda açmanız yeterlidir.

## Ekran Görüntüleri

Uygulama 34 farklı ekran içermektedir: giriş, ana sayfa, olay türü seçimi, acil durum rehberleri, kaza beyanı adımları, hasar tespiti, tutanak oluşturma, QR paylaşım, kroki çizimi, dijital imza ve sonuç ekranları.

## Lisans

Bu proje bir konsept mockup'tır ve Anadolu Sigorta için hazırlanmıştır.
