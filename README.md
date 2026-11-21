# Gıda Regülasyon Bülteni — herkese açık site

Bu depo **yalnızca yayımlanmak üzere seçilmiş, temizlenmiş statik bülten dosyaları** içerir.
Özel `gida-regulasyon-radari` deposunun Python kodu, kaynak geçmişi, çalışma günlükleri ve gizli anahtarları burada bulunmaz.

## Yayına alma

1. Bu dosyaları **herkese açık** `gida-regulasyon-bulteni` deposunun köküne koyun. `docs/` klasörü korunmalıdır.
2. GitHub → Settings → Pages → Source: **GitHub Actions**.
3. `Actions → Publish static bulletin to GitHub Pages` çalıştırın. Başlangıç sayfası ilk bülten yayımlanana dek “Henüz bülten yok” diyecek.
4. Özel depodaki yayın iş akışı `BULLETIN_PUBLISH_TOKEN` ve `ENABLE_PUBLIC_BULLETIN` yapılandırılınca ilk gerçek bülteni aktarır.

**Önemli:** RSS, arşiv ve tüm yayın çıktıları kamusaldır. Yayın öncesi gözden geçirin.
