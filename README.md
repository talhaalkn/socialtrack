
# SocialTrack

## ✨ Proje Hakkında

**SocialTrack**, kullanıcı tarafından girilen bir kullanıcı adının sosyal medya ve çeşitli platformlarda var olup olmadığını tarar. OSINT (Açık Kaynak İstihbaratı) yaklaşımıyla çalışan bu araç, tespit ettiği profillerden bazı verileri toplayarak kullanıcı hakkında temel analiz yapmanı sağlar.

---

## ⚙️ Özellikler

✅ Kullanıcı adının çok sayıda platformda varlığını tespit eder  
✅ Asenkron isteklerle **hızlı tarama** yapar  
✅ Bazı platformlardan takipçi sayısı, gönderi sayısı, biyografi gibi bilgileri çeker  
✅ JSON ve CSV formatında **çıktı alma** desteği  
✅ Opsiyonel olarak **proxy / Tor** üzerinden anonim sorgulama  

---

## 🖥️ Kullanım

```bash
python3 main.py --username omertalhaalkin --export json
```

🔎 Örnek Çıktı:
```
[+] GitHub: https://github.com/omertalhaalkin (Bulundu)
[+] Instagram: https://instagram.com/omertalhaalkin (Bulundu)
[-] TikTok: Kullanıcı bulunamadı.
```

### 📌 Desteklenen Platformlar

| Platform   | Durum     |
|------------|-----------|
| GitHub     | ✅        |
| Instagram  | ✅        |
| Twitter (X)| ✅        |
| LinkedIn   | ✅        |
| TikTok     | ✅        |
| Reddit     | ✅        |
| Facebook   | ⏳ (Yakında) |
| Pinterest  | ⏳ (Yakında) |
| Steam      | ✅        |

Yeni platformlar için katkıda bulunabilirsin!

---

## 🛠️ Kurulum

```bash
git clone https://github.com/talhaalkn/socialtrack.git
cd socialtrack
pip install -r requirements.txt
```

> Python 3.8+ sürümü önerilir.

---

## 📁 Klasör Yapısı

```bash
socialtrack/
├── platforms/       # Her platform için özel kontrol dosyaları
├── core/            # Ana sistem modülleri (checker, fetcher, output)
├── output/          # JSON ve CSV çıktı dosyaları
├── main.py          # Giriş noktası
├── requirements.txt # Gerekli kütüphaneler
└── README.md        # Proje tanımı (bu dosya)
```

---

## 🧠 Kullanım Amacı

Bu proje yalnızca eğitimsel ve yasal OSINT amaçlı geliştirilmiştir.  
🔴 Kötü niyetli ve yasa dışı faaliyetlerde kullanılması yasaktır ve geliştirici hiçbir sorumluluk kabul etmez.

---

## 🤝 Katkıda Bulun

Her türlü katkı (yeni platform eklemek, bug düzeltmek, performans geliştirmek vs.) memnuniyetle kabul edilir:

```bash
1. Forkla 🍴
2. Yeni bir branch oluştur 🔧
3. Geliştirmeni yap ✍️
4. Pull Request gönder 🚀
```

---

## 📜 Lisans

Bu proje MIT lisansı ile korunmaktadır. Ayrıntılar için LICENSE dosyasını inceleyiniz.

<p align="center"><i>Developed with 💻 and ☕ by Ömer Talha Alkın</i></p>

---

## 🔧 Yapılacaklar

- [ ] GitHub’a yüklemeden önce şu alanları değiştir:
  - `kullaniciadi` → GitHub kullanıcı adın
- [ ] Görsel örnek ekran görüntüsü ekle (`/docs` klasörüne koy ve Markdown içinde göster)
