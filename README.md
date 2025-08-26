# Windows / Linux Komutları ve Kısayolları

Bu depo, **Windows PowerShell komutları**, **Windows ağ (Wi‑Fi) komutları**, **Linux/Unix terminal komutları** ve **terminal/klavye kısayolları** için kısa açıklamalar ve örnekler içerir. Notlar Türkçe hazırlanmıştır ve hızlı başvuru (cheatsheet) olarak kullanılabilir.

> ⚠️ **Uyarı**
>
> - Bazı komutlar yönetici/`sudo` yetkisi gerektirebilir.
> - Güvenlik araçları yalnızca **eğitim ve yetkili test** amaçlıdır. Yetkisiz kullanım yasalara aykırıdır.
> - Kişisel bilgiler (ör. kullanıcı adı/şifre) **README’ye dahil edilmemiştir**. Lütfen repoda bu tip veriler varsa kaldırın.

---

## 📁 Dosya Yapısı

- `window.md` – Windows PowerShell komutlarının özeti ve günlük kullanım örnekleri.
- `window_comments.md` – Windows ile ilgili ek notlar ve komut listeleri (alias vb.).
- `comments.md` – Linux/Unix komutları; paket/servis/ağ tanılamaya yönelik kısa açıklamalar ve örnekler.
- `klavye.md` – Terminal ve shell kısayolları; **Türkçe Q klavye** özel karakter eşlemeleri.

---

## 🚀 Hızlı Başlangıç

### Windows (PowerShell & Ağ)
- Çalışan işlemleri listeleme:  
  ```powershell
  Get-Process
  ```
- Not Defteri işlemini sonlandırma:  
  ```powershell
  Stop-Process -Name notepad
  ```
- Yakındaki Wi‑Fi ağlarını listeleme (Komut İstemi / CMD):  
  ```cmd
  netsh wlan show networks
  ```

### Linux / Unix
- Dizin içeriklerini uzun formatta listeleme:  
  ```bash
  ls -l
  ```
- Dosyada desen arama:  
  ```bash
  grep "kelime" dosya.txt
  ```
- Etkin bağlantıları görüntüleme:  
  ```bash
  ss -tuln
  ```

### Kısayollar (Terminal / Shell)
- Geçmişte arama: **Ctrl + R**
- Ekranı temizleme: **Ctrl + L**
- Satır başı/sonu: **Ctrl + A / Ctrl + E**
- Türkçe Q karakter kısayolları (örnek): `~` = **Shift + "**, `{` = **Shift + Ğ**, `|` = **Shift + ,**, `:` = **Shift + Ş**

---

## 🧭 Nasıl Kullanılır?

1. Dosyaları doğrudan GitHub’da görüntüleyebilir veya yerel olarak bir Markdown görüntüleyicide açabilirsiniz.
2. İhtiyacınız olan komutu aramak için **Ctrl+F** kullanın.
3. Komutları kopyalayıp terminalinizde/PowerShell’de çalıştırmadan önce:
   - Komutun amacını ve parametrelerini tekrar kontrol edin.
   - Üretim sistemlerinde denemeden önce güvenli bir ortamda test edin.

---

## 🤝 Katkıda Bulunma

- İyileştirme, yeni komut örnekleri veya açıklamalar için **PR** açabilirsiniz.
- Büyük değişiklikler için önce bir **Issue** oluşturarak tartışalım.

---

## 🗺️ Yol Haritası (Öneri)

- [ ] Komutları konu başlıklarına göre (dosya, ağ, süreç, servis vb.) yeniden gruplama
- [ ] Sık kullanılan komutlar için **“en hızlı 20”** bölümü
- [ ] Windows & Linux için **sık karşılaşılan hata örnekleri** ve çözüm notları
- [ ] Kısa bir **sözlük** (örn. “PID”, “pipe”, “STDOUT/STDERR”)

---

## 📄 Lisans

Bu repo bir not arşividir. Lisans tercihi belirtilmemiştir; isterseniz kök dizine `LICENSE` dosyası ekleyerek **MIT** veya tercih ettiğiniz başka bir lisansı seçebilirsiniz.
