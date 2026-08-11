# Çoban Simulator — BUILD v3.1 FPS

Bu sürüm kullanıcı geri bildirimi üzerine birinci şahıs kameraya geçti.

Düzeltmeler:
- Cow.gltf ve Kenney environment assetleri yeniden pakete eklendi (v3.0 paketinde eksik kalmışlardı)
- Beyaz kutu inek problemi bu eksik assetlerden kaynaklanıyordu
- Karakterin yanındaki büyük kapsül, procedural gömlek meshiydi; FPS modunda tam karakter gövdesi kaldırıldı
- Kamera 1.68 m göz yüksekliğinde birinci şahıs
- Kamera önünde sadece kol + çoban sopası var
- Sopa butonuna kısa swing animasyonu eklendi
- 3D çim yaklaşık 1000 tuft'a çıkarıldı, InstancedMesh ile yaklaşık 5 draw call
- Oyuncu ve inek yürüdükçe çim yatıyor
- İnek otladıkça çevresindeki ot hızlı biçimde kısalıyor
- Yeniden büyüme belirgin biçimde yavaşlatıldı
- Cow modeli yaklaşık 1.45 m yüksekliğe normalize edildi

Çalıştır:
`python -m http.server 8080`

Tarayıcı:
`http://localhost:8080/PLAY_v3_1.html?v=3101`

Ekranda `BUILD v3.1 FPS` görmelisin.
