# krmnlhmza.github.io

Muhammed Hamza Karamanlı'nın kişisel websitesi. Türkçe (`/`) ve İngilizce (`/en/`) olarak GitHub Pages üzerinde yayınlanır.

## Canlıya alma
1. GitHub'da `krmnlhmza.github.io` adında **public** repo aç.
2. Bu klasörü pushla:
   ```
   git init && git add -A && git commit -m "İlk sürüm"
   git branch -M main
   git remote add origin https://github.com/krmnlhmza/krmnlhmza.github.io.git
   git push -u origin main
   ```
3. Birkaç dakika içinde site `https://krmnlhmza.github.io` adresinde yayında olur.

## Yapılacaklar
- [ ] Formspree hesabı aç (ücretsiz), form ID'sini `index.html` ve `en/index.html` içindeki `FORM_ID_BURAYA` yerine yaz.
- [x] Profil fotoğrafı ve logolar `assets/` klasörüne eklendi.
- [ ] İleride: AI asistan (MCP tabanlı mail cevaplama) entegrasyonu.

Not: `gerekli logolar ve fotolar/` klasörü kaynak dosyalar içindir; site `assets/` içindeki kopyaları kullanır. Pushlamadan önce istersen bu klasörü silebilirsin.
