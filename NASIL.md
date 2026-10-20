# Duyuru yayınlama

Uygulama açılışta `https://mrtcgl.github.io/nabkap-duyuru/duyuru.json` adresini okur.
Bu dosya herkese açık `MrTCgl/nabkap-duyuru` deposunda durur (GitHub Pages açık).
Örnek biçim: `docs/duyuru/duyuru.json`.

- `id`: her duyuruda farklı olmalı. Görülen kimlik aynı kullanıcıya bir daha çıkmaz.
- `baslangic`, `bitis` (YYYY-AA-GG), `baglanti` ve `gorsel` (https) isteğe bağlıdır.
- `tr` ve `en` metinleri ayrı yazılır. Metni olmayan dildeki kullanıcı o duyuruyu görmez.
- Kurallar uygulamada: iki duyuru arasında en az 3 gün, dinlerken hiç çıkmaz, internet yoksa atlanır,
  "Bir daha gösterme" bütün duyuruları kapatır (Ayarlar > Görünüm > Duyuruları göster ile geri açılır).
- Duyurular bildirimle gönderilmez; tanıtımı bildirimle yapmak ayrıca onay ister.
- Dosyayı değiştirdikten sonra yayılması birkaç dakika sürer. Listeyi boşaltmak (`"duyurular": []`) duyuruyu durdurur.
