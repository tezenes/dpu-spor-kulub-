# CLAUDE.md — DPÜ Spor Kulübü Web Sitesi

## Proje Hakkında
- **Kulüp:** DPÜ Spor Kulübü (Dumlupınar Üniversitesi Spor Kulübü)
- **Şehir:** Kütahya
- **Klasör:** `C:\Users\tezen\Yeni klasör`

## Dosya Yapısı
- `index.html` — Ana tanıtım sayfası
- `panel.html` — Yönetim paneli
- `sporcu-takip.html` — Sporcu takip sistemi
- `images/` — Tüm görseller burada

## Branşlar (8 adet)
1. Yüzme
2. Basketbol
3. Voleybol
4. Tenis
5. Masa Tenisi
6. Pilates
7. Zumba
8. Jimnastik

## Logolar
- `images/kurumsal amblem.png` — Kurumsal logo, sitenin sol üstünde ve genel kullanımda
- `images/porsuk amblem .webp` — Porsuk amblemi, belirli alanlarda kullanılıyor
- **Logo değişikliği yapma** — logolar artık sabittir, onay olmadan değiştirme

## Tasarım Kuralları
- Renk paleti: Lacivert (`#0d1b3e`), Kırmızı (`#c8102e`), Beyaz
- Font: Mevcut fontları koru, yeni font ekleme
- Mobil uyumlu (responsive) ol, her değişiklikte mobil görünümü bozmama
- Animasyonlar sadece `transform` ve `opacity` üzerinden olsun
- Her hover/focus/active state tanımlı olsun
- Görsel kalite yüksek tutulsun, generic tasarımdan kaçın

## Görseller
- Tüm görseller `images/` klasöründe
- Yeni görsel eklenecekse `images/` klasörüne koy
- `git restore images/` ile silinmiş görseller geri getirilebilir

## Geliştirme Kuralları
- Dosya değiştirmeden önce mutlaka oku
- Küçük, odaklı değişiklikler yap — geniş kapsamlı değişikliklerden kaçın
- Her değişikten sonra git commit öner ama kullanıcı onaylamadan commit atma
- Yeni dosya oluşturmadan önce mutlaka kullanıcıya sor

## Git
- Ana branch: `main`
- Commit atmadan önce kullanıcıdan onay al
- Push yapmadan önce mutlaka kullanıcıdan onay al

## Önemli Notlar
- Kullanıcı sekmeyi kapatıp bağlamı kaybedebilir — her öğrenilen şeyi memory'e kaydet
- MEXC projesi artık geçmişte, o konuya girme
- `neon-dodge.html` kullanıcının kişisel denemesi, ona dokunma
