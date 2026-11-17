# Katkıda Bulunma

## Çalışma ilkeleri

- Önce ilgili kodu ve mevcut dokümantasyonu inceleyin.
- Her iş için `feature/`, `fix/`, `docs/` veya `chore/` önekiyle ayrı dal kullanın.
- Bir commit mümkün olduğunca tek bir mantıksal değişikliği temsil etsin.
- Var olan davranışı değiştiren işlemlere test ekleyin veya mevcut testleri güncelleyin.
- Gizli anahtar, parola, kişisel veri veya yerel yapılandırma dosyalarını commit etmeyin.

## Pull request kontrol listesi

- [ ] Değişikliğin amacı ve kapsamı açıklandı.
- [ ] İlgili testler/derleme kontrolleri çalıştırıldı; sonuçlar belirtildi.
- [ ] Dokümantasyon güncellendi.
- [ ] Gizli bilgiler ve üretilmiş dosyalar eklenmedi.
- [ ] Geriye dönük uyumluluk etkisi açıklandı.

## Birleştirme

PR incelemesi ve gerekli kontroller tamamlanmadan `main` dalına birleştirme yapılmamalıdır.
