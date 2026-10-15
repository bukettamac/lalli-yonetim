# LALLİ — yönetim paneli

Ayrı bir Vercel projesi olarak, mağazadan farklı bir adreste (ör. `yonetim.lallejewelry.com`) yayınlanır.
Arama motorlarına kapalıdır (`robots.txt`, `X-Robots-Tag`). Giriş Supabase e-posta/şifre ile yapılır;
yalnızca `admins` tablosundaki hesaplar veri görebilir — kurallar veritabanında olduğu için bu sayfanın
adresini bilen biri bile hiçbir veriye ulaşamaz.

## Bölümler
- **Özet** — ciro, sipariş, ortalama sepet, yeni üye, hazırlanacak/ödeme bekleyen/kargodaki siparişler, günlük ciro grafiği, durum dağılımı, en çok satanlar, kupon kullanımı, şehirler, bildirim tercihleri
- **Siparişler** — arama, duruma göre filtre, CSV; sipariş detayı, durum/ödeme/kargo/takip no, yönetici notu, iyzico kaydı
- **Kuponlar** — yüzde/tutar indirim, en az sepet, başlangıç-bitiş, toplam limit, kişi başı tek kullanım, aç/kapat, kullanım istatistiği
- **Üyeler** — kanal filtresi, arama, CSV
- **Müşteri paylaşımları** — LALLİ Akışı paylaşımlarını gizle/sil
- **Site içeriği** — fırsat kartları (parmakla boyutlandırma), fırsat günleri, kategoriler, ürünler, bölümler, sosyal medya, akış, SSS, yasal metinler (canlı önizlemeli)
