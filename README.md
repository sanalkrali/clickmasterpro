# ClickMaster Pro: Gelişmiş Tıklama Motoru

ClickMaster Pro, **oyun deneyiminizi bir üst seviyeye taşımak için geliştirilmiş** güçlü bir tıklama motorudur. Modern oyun mekaniklerine uyum sağlamak için tasarlandı ve **gerçek zamanlı tıklama yönetimi** ile sizi rakiplerinizin bir adım önüne geçirir.

## Öne Çıkan Özellikler

### **Dual Engine Teknolojisi**
ClickMaster Pro, **sol ve sağ tıklamalar için bağımsız çalışan iki motor** ile size tam kontrol sağlar. Bu, aynı anda farklı tıklama işlevlerini kullanarak oyunun her anında maksimum performansı elde etmenize olanak tanır.

- **CPS Seçimi:** 1 - 20 CPS arası hassas seçim yapabilirsiniz.
- **Hold Mode:** Tıklama tuşuna basılı tuttuğunuzda sürekli tıklama.
- **Toggle Mode:** Bir kez basarak başlatır, tekrar basarak durdurur.

### **Humanized Timing – Doğal Tıklama Deneyimi**
ClickMaster Pro, **sabit zaman dilimleri yerine doğal, insan benzeri tıklama aralıkları** kullanarak, her tıklamanın gerçek bir oyuncuya ait gibi görünmesini sağlar. Bu, oyunların **anti-cheat sistemlerine yakalanma riskinizi azaltır.**

- **Gaussian Variation:** Tıklama hızını doğal bir şekilde dalgalandırır ve size gerçekçi bir deneyim sunar.

### **Rod Macro (Olta Makrosu)**
PvP oyuncuları için özel olarak geliştirilmiş olan bu özellik, olta ve kılıç slotları arasında geçiş yaparken **yapay gecikmeleri** ortadan kaldırır.

- **Instant Swap:** Hızlı geçişler sayesinde, rakiplerinizi anında şaşırtabilirsiniz.
- **Özelleştirilebilir Gecikme:** Olta havada süzülürken, süresini milisaniyelik hassasiyetle ayarlayabilirsiniz.

### **Gerçek Zamanlı Radar Sistemi**
ClickMaster Pro’nun **Radar Sistemi**, tıklama motorunun anlık durumunu ve tepkilerini görsel olarak izleyebilmenizi sağlar. Bu, özellikle **oyunun ilerleyişine göre** stratejilerinizi anında ayarlamanıza yardımcı olur.

## Teknik Özellikler

| Bileşen              | Teknoloji      | Açıklama                                             |
|----------------------|----------------|------------------------------------------------------|
| **Dil / Platform**    | Java 21 (OpenJDK) | Yüksek performanslı nesne tabanlı mimari.              |
| **Arayüz (UI)**       | JavaFX 21      | GPU hızlandırmalı, modern ve akıcı kullanıcı deneyimi.|
| **Giriş İşleyici**    | JNativeHook    | Düşük seviyeli (Low-level) global klavye ve fare dinleme.|
| **Grafik Motoru**     | Prism D3D      | DirectX tabanlı donanım hızlandırmalı çizim.            |
| **Optimizasyon**      | Mini JRE       | Sadece gerekli Java modüllerini içeren 50MB'lık hafif paket. |

## Kullanıcı Rehberi

### **İlk Çalıştırma**
- Uygulamayı **Yönetici olarak çalıştırın**. Bu, programın klavye ve fareyi global olarak kontrol etmesine izin verir.
- **HWID doğrulaması** yapılacaktır; sisteminizin HWID bilgisi kontrol edildikten sonra, uygulamayı sorunsuzca kullanabilirsiniz.

### **Ayarları Yapılandırma**
1. **Kısayol Tuşları:** `Settings` sekmesinden, sol tıklama, sağ tıklama ve olta makrosu için tuş atamaları yapın.
2. **Kayıt:** Ayarlar, **AppData/Roaming/ClickMasterPro/config.properties** dosyasına kaydedilir.

## Güvenlik ve Gizlilik

**ClickMaster Pro**, benzersiz bir donanım kimliği (HWID) sistemi kullanarak:
- Uygulamanın **izinsiz kopyalanmasını engeller.**
- **Kullanıcı bazlı** yetkilendirme sağlar.
- İnternet üzerinden **lisans doğrulama** yaparak güvenli erişim sunar.

## Sıkça Sorulan Sorular (SSS)

- **S: Uygulama neden açılmıyor?**
  - **C:** Bilgisayarınızda Visual C++ Redistributable paketlerinin güncel olduğundan emin olun. Ayrıca, antivirüs yazılımınızın dosyayı karantinaya alıp almadığını kontrol edin.

- **S: CPS hızı neden sabit değil?**
  - **C:** "Humanized Timing" özelliği aktiftir ve tıklama hızını küçük oranlarda değiştirerek gerçekçi hale getirir. Bu, güvenlik önlemidir.

- **S: Olta makrosu çalışmıyor?**
  - **C:** Kısayol tuşlarının başka bir program tarafından kullanılmadığından ve olta/kılıç slotlarının doğru şekilde eşleştiğinden emin olun.

## İletişim ve Destek

Herhangi bir teknik sorunla karşılaşırsanız veya topluluğa katılmak isterseniz:
- **Geliştirici:** untilshurawin (Discord)
- **Topluluk:** [discord.gg/arjantin](https://discord.gg/arjantin)

Copyright © 2025 ClickMaster Pro. Tüm hakları saklıdır.
