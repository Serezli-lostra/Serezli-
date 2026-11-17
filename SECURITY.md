# Güvenlik Politikası

## Güvenlik bildirimi

Güvenlik açıklarını herkese açık issue veya tartışmalarda yayımlamayın. GitHub deposunun **Security** sekmesindeki özel güvenlik bildirimi özelliğini kullanın (etkinse). Bu özellik yoksa depo sahibine GitHub üzerinden özel bir kanal aracılığıyla ulaşın.

## Gizli bilgilerin korunması

- API anahtarları, parolalar, erişim belirteçleri ve imzalama anahtarları depoya commit edilmemelidir.
- Yerel sırlar ortam değişkenleri veya güvenli bir sır yöneticisiyle saklanmalıdır.
- Yanlışlıkla yayımlanan bir anahtar yalnızca commit'i silerek güvenli hale gelmez; derhal iptal edilmeli ve yenilenmelidir.
- Şüpheli sızıntı durumunda ilgili erişim bilgileri döndürülmeli ve commit geçmişi ayrıca incelenmelidir.

## İnceleme kapsamı

Bildirimde etkilenen dosya/sürüm, etki, tekrar üretme adımları ve mümkünse düzeltme önerisi yer almalıdır. Gerçek sırları rapora eklemeyin.
