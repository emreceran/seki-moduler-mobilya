# SEKİ — modüler dış mekân oturma sistemi

**10 Eki 2026:** ana sayfa artık ürün galerisi + "Nasıl yapılır" menüsü (kaynak projede `vitrin/`). Önceki site `eski/` klasöründe pasif duruyor; aşağıdaki açıklamalar ona aittir.
Yayın: https://emreceran.github.io/seki-moduler-mobilya

Ürün görselleri Blender ile üretilmiş 3B render'lardır (fotoğraf değildir).
Arka plan ortam haritası: Poly Haven (CC0).

Kaynak proje (özel): `moduler-rattan-mobilya` — mimari, çizimler ve pazar araştırması orada.

## Klasörler

| Klasör | İçerik |
|---|---|
| `index.html` | Tanıtım sitesi — modüller, dizilim kurucu, fiyatlar, malzeme |
| `img/` | Ürün render'ları |
| `prototip/` | **Prototip yapım kılavuzu** — elle imalat için kesim listeleri, adım adım imalat, kilit detayı, kabul testleri |

## Prototip durumu (18 Eyl 2026)

Seri üretime geçmeden önce elle üretilecek ilk takım: **2 × YK kolçak + 1 × O1 tekli + 1 × O2 ikili.**
Aynı dört modül tekli koltuk (980), ikili kanepe (1600) ve üçlü kanepe (2220 mm) olarak kurulabiliyor.

- Kılavuz: [`prototip/index.html`](prototip/index.html)
- Net el emeği ~9 iş günü, takvim ~14 iş günü (fason beklemeleri paralel)
- Toplam örgü 4,07 m² · ~552 m şerit · 12 panel

### Kılavuzdaki ölçüler hakkında

Çerçeve geometrisi, kesim ölçüleri ve MK-01/MK-02 kilit detayı **yayındaki ürün verilerinden
türetilmiştir** — ürünün kendi teknik paftaları `moduler-rattan-mobilya` deposunda.
Tutarlılık kontrolü olumlu (kesim listesinden çıkan ağırlıklar 9,3 / 7,7 / 13,2 kg, sitenin
verdiği 10 / 9 / 15 kg'a oturuyor) ama **imalata başlamadan önce paftalarla karşılaştırılmalı.**

### Açık kalan kararlar

- [ ] Kama konik açısı: 1:22 hesapla bulundu, denenmedi. Lazere 1:22 ve 1:15 olarak 4+4 plaka kestirilip prototipte seçilecek.
- [ ] O2 sırt paneli 1240 × 665 — sineklik profili bu boyda bükülürse 2 × 620 mm'ye bölünecek.
- [ ] PE şerit gevşemesi (creep): prototip iki hafta yük altında bekletilip sehim tekrar ölçülecek.

### Prototip bitince siteye dönülecek

1. Render'ların yerine gerçek fotoğraflar.
2. Siteye dürüst bir "proje durumu" bölümü — şu an kesin fiyat, "stokta 3 iş günü" teslim ve
   EN 581-3 deney raporu vaat ediliyor; ürün üretilmediği için üçü de henüz karşılanamıyor.
   RATTAMAK sitesinde bu bölüm var, burada yok.