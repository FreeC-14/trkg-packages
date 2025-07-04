# TRKG Üçüncü Parti Paket Deposu

Bu depo, [TRKG Paket Yöneticisi](https://github.com/dreamtechdev230/trkg) için topluluk tarafından hazırlanan `.trkg` formatında üçüncü parti paketleri içerir.

---

## Mevcut Paketler

| Paket Adı   | Sürüm | Açıklama                                      |
|-------------|-------|-----------------------------------------------|
| freefetch   | 1.4   | Nim diliyle yazılmış, hızlı ve hafif sistem bilgisi aracı |

---

## Kurulum

### Yöntem 1: Manuel İndirme

```bash
curl -LO https://github.com/FreeC-14/trkg-packages/raw/main/packages/freefetch-1.4.trkg
trkg install freefetch-1.4.trkg
```
### Yöntem 2: TRKG Aracılığıyla (yakında)

Bu depo, index.json destekli uzak depo sistemine uygun şekilde yapılandırılabilir. Böylece trkg search ve trkg upgrade gibi komutlarla doğrudan kullanılabilir hale gelecektir.


---

### Dizin Yapısı

trkg-packages/
├── packages/
│   └── freefetch-1.4.trkg
├── README.md
└── (isteğe bağlı) index.json


---

### Kendi Paketini Eklemek

Pull request ile katkıda bulunmak istiyorsan:

1. packages/ klasörüne .trkg dosyanı yerleştir.


2. README.md dosyasına açıklayıcı bilgi ekle.


3. (İsteğe bağlı) index.json dosyasına metadata ekle:



{
  "name": "freefetch",
  "version": "1.4",
  "description": "Nim ile yazılmış minimal sistem bilgi aracı",
  "url": "https://github.com/FreeC-14/trkg-packages/raw/main/packages/freefetch-1.4.trkg"
}


---

### Lisans

Bu repodaki tüm .trkg paketleri yazarlarına aittir.

README.md ve varsa index.json MIT Lisansı altındadır.



---

### Yazarlar

FreeC-14 – FreeFetch geliştiricisi

TRKG geliştiricisi: dreamtech.dev
