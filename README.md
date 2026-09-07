# DistantLightsFX — Skettch / 2026

DistantLightsFX ürün tanıtım sayfası. Addonun satış ZIP'i bu repoya dahil değildir.

## GitHub'da yeni repo ayarları

- Repository name: `distantlightsfx`
- Description: `Official DistantLightsFX product page by Skettch — procedural city backgrounds for Blender.`
- Visibility: **Public** (GitHub Free üzerinde Pages için gerekli).
- Add README: **Kapalı**. Bu pakette hazır README vardır. Önceden açtıysan sorun değil; bu dosyayla değiştirebilirsin.
- .gitignore: **None**
- License: **None**

## Dosyaları yükle

1. ZIP'i bilgisayarında aç.
2. Yeni boş repoda **uploading an existing file** bağlantısına bas. Repo boş değilse **Add file → Upload files** kullan.
3. ZIP'in içindeki `index.html`, `embed.html`, `README.md` ve `assets` klasörünü birlikte sürükle. ZIP dosyasının kendisini yükleme.
4. **Commit changes** ile kaydet. `index.html` repo kökünde görünmeli; fazladan paket klasörünün içinde olmamalı.
5. **Settings → Pages → Build and deployment → Source → Deploy from a branch** seç.
6. Branch: **main**, Folder: **/(root)**, ardından **Save**.
7. Pages ekranında verilen site adresini aç. İlk yayın birkaç dakika sürebilir.

Örnek adres: `https://KULLANICI-ADIN.github.io/distantlightsfx/`
Mevcut diğer addon repon ve sayfan değişmez.

## Superhive'a yerleştir

1. Yayınlanan adresin sonuna `embed.html` ekleyip aç.
2. Kullanıcı adı ve repo adı otomatik gelir. **Kodu kopyala** düğmesine bas.
3. Superhive açıklama editöründe **</>** görünümüne geç ve eski açıklama kodunu bu iframe koduyla değiştir.
4. Normal görünüme dönüp kaydet; ürün önizlemesinde kontrol et.
5. Ürünün ana kapağı/galerisi ve kısa açıklaması Superhive alanlarında ayrıca kalır.

Çerçeve 1200 px yüksekliğindedir ve uzun içerik içinde kaydırılır. Parent sayfada script erişimi olmadığından iframe'in yüksekliğini içerikle otomatik eşitlediğimiz iddia edilmez. İstersen üretilen kodda iki `1200` değerini birlikte değiştirebilirsin.

## İçerik ve medya

- Asıl sayfa `index.html`; stil ve etkileşim kodları aynı dosyada.
- `assets/hero.png`: onaylanan loş bokeh kapak kompozisyonu.
- `assets/hong-kong.jpg`: sağlanan Hong Kong renderı.
- Diğer resimler ve GIF'ler kullanıcının sağladığı Superhive medya adreslerinden yüklenir.
- Medya eşleştirmesi yükleme sırası ile orijinal dosya adlarının alfabetik sırasına dayanır; uzak sunucu çalışma ortamında 403 verdiği için tek tek görsel eşleşmesi doğrulanamadı. Yayında başlık/görsel eşleşmesini kontrol et.
- Üç skyline sekmesi mevcut örnek renderları gösterir; ürünün tüm flavourlarının ayrı ayrı gösterimi değildir.
- Yayına alınmış Superhive editöründe iframe testi yapılmadı. Light Master Pro aynı dış sayfa + iframe yöntemini kullanıyor, fakat bu paketin görünümü yayın sonrası kontrol edilmeli.

## Güncelleme

`index.html` veya görselleri aynı adla repoya yükleyip commit et. Pages yeniden yayınlar; Superhive iframe adresini değiştirmek gerekmez.

Resmî rehber:
https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

© Skettch 2026
