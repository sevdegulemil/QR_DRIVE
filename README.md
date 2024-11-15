
# QR_DRIVE - Fotoğraf ve Video Yükleme Sayfası

Bu proje, kullanıcıların etkinlikler için fotoğraf ve video yüklemelerini kolaylaştırmak amacıyla oluşturulmuş basit ve şık bir web sayfasıdır. Kullanıcılar, etkinliğinizde çektikleri fotoğraf ve videoları belirttiğiniz Google Drive veya alternatif bir bulut depolama alanına yükleyebilirler. Bu sayede farklı kanallar üzerinden düşük kaliteli fotoğraf ve videolar ile uğraşmadan bulutunuzdan erişebilirsiniz.

## İçindekiler

- [Özellikler](#özellikler)
- [Kurulum](#kurulum)
- [Kullanım](#kullanım)

## Özellikler

- **Arka Plan Görseli**: Özelleştirilebilir arka plan görseli ile estetik bir sayfa tasarımı.
- **Etkinlik Başlığı ve Tarihi**: Etkinliğinizi tanıtmak için büyük başlık ve tarih alanları.
- **Fotoğraf ve Video Yükleme**: Kullanıcıların etkinlikten fotoğraf ve video yükleyebilmeleri için Google Drive entegrasyonu.
- **Alternatif Yükleme Yöntemi**: Dropbox veya başka bir bulut alanı gibi alternatif yükleme seçenekleri.
- **Mobil Uyumluluk**: Tüm cihazlarda düzgün görüntüleme için responsive tasarım.

## Kurulum

1. **Projeyi İndirin**:
    ```bash
    git clone https://github.com/kullanici-adi/qr_drive_yukleme.git
    cd qr_drive_yukleme
    ```

2. **HTML Dosyasını Düzenleyin**:
   - `index.html` dosyasında aşağıdaki alanları değiştirerek kendi tasarımınızı uygulayabilirsiniz:
     - Arka plan görseli URL'si
     - Etkinlik adı, tarihi ve mesajı
     - Google Drive yükleme linkleri
     - Alternatif bulut depolama alanı linki
     - Yazı fontları, büyüklükleri
     - Renkler
     - Buton ve ikon tasarımları vb.

3. **Sayfayı Yerel Olarak Çalıştırın**:
    - HTML dosyasını herhangi bir tarayıcıda açın.
  
4. **QR code oluşturma**:
    - "QRcode monkey" vb. siteler üzerinden sayfa URL si ile bir qr oluşturun.
    - QR kodu indirin ve kameranız ile tarayıp sayfaya yönlendirildiğinizden ve her şeyin sorunsuz çalıştığından emin olduktan sonra kullanıma sunabilirsiniz:).

## Kullanım
Etkinlik alanına elde ettiğiniz QR kodu yerleştirebilirsiniz. 
1. Kullanıcılar, etkinlik sırasında çektikleri fotoğrafları yüklemek için **"Fotoğraf Yükle"** butonuna tıklayabilir.
2. Videoları paylaşmak isteyen kullanıcılar ise **"Video Yükle"** butonunu kullanabilir.
3. Alternatif bir yükleme yöntemi tercih eden kullanıcılar için **"Alternatif Yükleme"** seçeneği de mevcuttur.
