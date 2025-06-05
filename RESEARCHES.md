# 🔬 Araştırmalar ve Teknik Notlar

Bu belge, SocialTrack projesinin geliştirilmesi sırasında yapılan teknik araştırmaları ve edinilen bilgileri derlemektedir.

---

## 📌 Kullanıcı Adı Tespiti Yöntemleri

- **HTTP Durum Kodları**: Platformlardaki kullanıcı profillerinin varlığını kontrol etmek için HTTP 200 ve 404 durum kodları analiz edildi.
- **Regex ve HTML Parsing**: Bazı platformlarda kullanıcı profili sayfalarının yapısı incelenerek, kullanıcı adının varlığına dair ipuçları elde edildi.

---

## 🔐 Anonimlik ve Güvenlik

- **Tor Ağı Entegrasyonu**: Kullanıcı sorgularının anonimleştirilmesi için Tor ağı üzerinden istek gönderme özelliği test edildi.
- **Proxy Desteği**: Farklı proxy sunucuları üzerinden istek gönderme mekanizmaları araştırıldı ve entegre edildi.

---

## 📁 Veri Çıktıları

- **JSON Formatı**: Tespit edilen kullanıcı profilleri ve ilgili veriler JSON formatında dışa aktarılabilir hale getirildi.
- **CSV Formatı**: Kullanıcıların verileri tablo şeklinde inceleyebilmesi için CSV formatında çıktı desteği eklendi.

---

## 🛠️ Kullanılan Araçlar ve Kütüphaneler

- **Python 3.8+**: Projenin ana programlama dili olarak kullanıldı.
- **aiohttp**: Asenkron HTTP istekleri için tercih edildi.
- **BeautifulSoup**: HTML parsing işlemleri için kullanıldı.
- **Stem**: Tor ağı ile entegrasyon için kullanıldı.

---

## 📚 Kaynaklar

- [OSINT Framework](https://osintframework.com/)
- [Sherlock Projesi](https://github.com/sherlock-project/sherlock)
- [Tor Project](https://www.torproject.org/)