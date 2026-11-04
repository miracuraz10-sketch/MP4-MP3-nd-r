# 🚀 Mirdombili Downloader Pro

**Mirdombili Downloader Pro**, bilgisayarınıza indirebileceğiniz, modern ve şık tasarımlı bir medya indirme uygulamasıdır. YouTube, Instagram, TikTok ve yt-dlp'nin desteklediği 100'den fazla platformdan en yüksek kalitede video (MP4) ve ses (MP3) indirmenizi sağlar. 

Reklam yok, karmaşık siteler yok. Sadece indir, izle ve keyfine bak!

## ✨ Özellikler
*   **Çoklu Platform Desteği:** YouTube, Instagram Reels, TikTok ve daha fazlası.
*   **Gelişmiş Hız ve Süre Hesaplama:** İnternet hızınıza ve videonun boyutuna göre kalan süreyi (ör. `04:35`) tam olarak hesaplar.
*   **Akıllı Geçmiş Sistemi:** İndirdiğiniz dosyalar `gecmis.json` dosyasına kaydedilir. Uygulamayı kapatsanız bile geçmişiniz asla silinmez.
*   **5 Farklı Tema:** Dark Neon, Cyberpunk, Mirdombili (Kırmızı-Sarı), Buz Mavisi ve Ateş Kırmızısı temaları.
*   **Otomatik Pano Algılama:** Kopyaladığınız linkleri (isteğe bağlı olarak) anında algılar ve kutuya yapıştırır.
*   **Dahili FFmpeg Kontrolü:** MP3 dönüştürme sırasında FFmpeg eksikse sizi uyarır.

## 📸 Ekran Görüntüsü
*(Buraya uygulamanın bir ekran görüntüsünü koyabilirsin. Örn: `![Uygulama Ekranı](screenshot.png)`)*

## 🛠️ Kurulum

Uygulamayı çalıştırmak için bilgisayarınızda **Python** kurulu olmalıdır.

1. Bu depoyu bilgisayarınıza indirin (ZIP olarak indirip çıkarabilirsiniz).
2. Klasörün içindeki **`kur.bat`** dosyasına çift tıklayın. 
   *Bu script gerekli Python kütüphanelerini (PyQt5, yt-dlp) ve FFmpeg'i otomatik olarak kuracaktır.*
3. Kurulum bittikten sonra **`calistir.bat`** dosyasına çift tıklayarak uygulamayı başlatın.

### 🐍 Manuel Kurulum (Geliştiriciler İçin)
Eğer terminal kullanmayı seviyorsanız:
```bash
# Kütüphaneleri yükleyin
pip install PyQt5 yt-dlp

# Uygulamayı çalıştırın
python main.py
