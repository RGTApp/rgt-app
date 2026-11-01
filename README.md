# Haftalık Program

Haftalık rutin, tarihli görevler, Bugün ekranı (notlar + asistan), takvim ve özel günler.
Telefona "Ana ekrana ekle" ile uygulama gibi kurulur, internet olmadan çalışır.

**Uygulama:** https://KULLANICI-ADIN.github.io/haftalik-program/

## Özellikler
- Mevcut hafta + 2 alternatif program (isimlerini sen verirsin), 7 gün + 3 ekstra sütun, 6–15 satır
- Saat aralığı seçici, dolu saatleri ve çakışmaları gösterir
- Alt görevler, renkler, sürükle-bırak, kopyala-yapıştır, tüm haftaya yay
- 12 tema, 20 görev efekti, 8 gün bitişi efekti, ses ve titreşim
- **Haftalık Görev:** tarihli görevler, detay, alt görev notları, takvimden tarih seçimi
- **Bugün:** solda notlarım (maddeler, ruh hali, etiketler), ortada bugünün rutini ve görevleri, sağda asistan
- **Rota 0.1 (asistan, beta):** günün özeti; işin türüne göre hatırlatma (derse 30 dk, randevuya 1 saat kala); tamamlayınca kişisel mesaj; hazır sorular, uygulama hakkında cevaplar ve program analizi. İşin türünü kendisi tahmin eder, düzelttiklerinden öğrenir
- **Rota yapay zekâ (deneme):** aktivasyon kodu olanlar Rota'ya istediğini yazabilir; cevapları Claude Haiku 5.5 verir. Sunucu adresi `rota-ai.js` dosyasındadır; boşsa bu bölüm görünmez
- **Takvim:** 2021–2031, Türkiye resmî ve dinî günleri, kişisel özel günler (doğum günü, yıl dönümü, anma, etkinlik)
- Veriler cihazda saklanır (localStorage)

## Telefona kurma
- **Android (Chrome):** ⋮ menü → *Uygulamayı yükle* / *Ana ekrana ekle*
- **iPhone (Safari):** Paylaş → *Ana Ekrana Ekle*

## Güncelleme
Yeni `index.html` yükledikten sonra `sw.js` içindeki `haftalik-program-v14` numarasını bir artır (v15, v16…).
