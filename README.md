# ClickMaster Pro: Kullanım Kılavuzu ve Teknik Dokümantasyon

## 1. Proje Özeti

**ClickMaster Pro**, modern oyun mekanikleri ve ileri düzey otomasyon ihtiyaçları için Java tabanlı, düşük gecikme süreli (low-latency) bir tıklama motoru olarak geliştirilmiştir. Projenin temel amacı, "Legit" (doğal) tıklama dinamiklerini gelişmiş bir kullanıcı arayüzü ile sunmaktır.

## 2. Öne Çıkan Özellikler

### 2.1. Gelişmiş Tıklama Motoru (Dual Engine)
- **CPS Aralığı:** 1 - 20 CPS (Clicks Per Second) arasında hassas seçim.
- **Hold Mode:** Kısayol tuşuna basılı tutulduğu sürece aktif olan kullanım modu.
- **Toggle Mode:** Bir kez basıldığında açılır, tekrar basıldığında kapanır.

### 2.2. Legit (Doğal) Tıklama Teknolojisi
- **Humanized Timing:** Sabit milisaniyeler yerine Gaussian Dağılımı (Çan Eğrisi) kullanarak tıklama aralıklarını milisaniyelik farklarla sürekli değiştirir.
- **Gaussian Variation:** Tıklama hızını `$CPS \pm 0.5$` aralığında doğal bir şekilde dalgalandırarak anti-cheat sistemlerine yakalanma riskini minimize eder.

### 2.3. Profesyonel Rod Macro (Olta Makrosu)
PvP oyuncuları için özel olarak geliştirilen bu sistem, **"Instant Swap"** teknolojisini kullanır:
- **Hızlı Geçiş:** Olta ve kılıç slotları arasında geçiş yaparken yapay gecikmeleri ortadan kaldırır.
- **Özelleştirilebilir Gecikme:** Oltanın havada süzülme süresini milisaniyelik hassasiyetle ayarlayabilme imkanı.

### 2.4. Aircraft Radar Sistemi
Görsel takip için dashboard üzerinde bulunan radar sistemi, tıklama motorunun anlık durumunu ve tıklama tepkilerini dairesel bir grafik üzerinde gerçek zamanlı olarak gösterir.

## 3. Teknik Mimarî

| Bileşen              | Teknoloji      | Açıklama                                             |
|----------------------|----------------|------------------------------------------------------|
| **Dil / Platform**    | Java 21 (OpenJDK) | Yüksek performanslı nesne tabanlı mimari.              |
| **Arayüz (UI)**       | JavaFX 21      | GPU hızlandırmalı, modern ve akıcı kullanıcı deneyimi.|
| **Giriş İşleyici**    | JNativeHook    | Düşük seviyeli (Low-level) global klavye ve fare dinleme.|
| **Grafik Motoru**     | Prism D3D      | DirectX tabanlı donanım hızlandırmalı çizim.            |
| **Optimizasyon**      | Mini JRE       | Sadece gerekli Java modüllerini içeren 50MB'lık hafif paket. |

## 4. Kurulum ve Yapılandırma

### 4.1. İlk Çalıştırma
- **Yönetici Yetkisi:** Uygulamanın klavye ve fareyi global olarak kontrol edebilmesi için mutlaka **Yönetici Olarak Çalıştır** seçeneğiyle açılması gerekir.
- **HWID Doğrulama:** Uygulama ilk açılışta sisteminizin HWID (Hardware ID) bilgisini GitHub üzerinden kontrol eder. Erişim izniniz yoksa hata ekranıyla karşılaşırsınız.

### 4.2. Ayarların Yapılandırılması
- **Kısayol Tuşları:** `Settings` sekmesine giderek sol tık, sağ tık ve olta makrosu için klavye veya fare tuşlarını atayın.
- **Kayıt Sistemi:** Yapılan tüm ayarlar `AppData/Roaming/ClickMasterPro/config.properties` dosyasına otomatik olarak kaydedilir.

## 5. Güvenlik ve Gizlilik (HWID)

ClickMaster Pro, güvenli erişim için benzersiz bir donanım kimliği sistemi kullanır. Bu sistem:
- Uygulamanın izinsiz kopyalanmasını engeller.
- Kullanıcı bazlı yetkilendirme sağlar.
- İnternet bağlantısı üzerinden anlık lisans kontrolü yapar.

## 6. Sıkça Sorulan Sorular (SSS)

- **S: Uygulama neden açılmıyor?**  
  **C:** Bilgisayarınızda Java JDK, JRE 1.8 paketlerinin güncel olduğundan emin olun.

- **S: CPS hızı neden seçtiğim değerin biraz altında/üstünde?**  
  **C:** "Humanized Timing" özelliği aktifse, sistem sizi korumak için hızı sürekli küçük oranlarda değiştirir. Bu bir hata değil, güvenlik özelliğidir.

- **S: Olta makrosu çalışmıyor?**  
  **C:** Kısayol tuşunun başka bir program tarafından kullanılmadığından emin olun ve olta/kılıç slot numaralarının oyundaki slotlarınızla eşleştiğini kontrol edin.

## 7. İletişim ve Destek

Her türlü teknik sorun ve topluluk katılımı için:
- **Geliştirici:** untilshurawin (Discord)
- **Topluluk:** [discord.gg/arjantin](https://discord.gg/arjantin)

Copyright © 2025 ClickMaster Pro. Her hakkı saklıdır.
