# Begum GW Detector APK Builder

Bu proje, `app/src/main/assets/index.html` içindeki HTML uygulamasını Android WebView APK olarak paketler.

## Android Studio olmadan APK alma

1. GitHub'da yeni bir repository aç.
2. Bu ZIP'in içindeki dosyaları repository'ye yükle.
3. Repository sayfasında **Actions** sekmesine gir.
4. **Build Android APK** workflow'unu seç.
5. **Run workflow** butonuna bas.
6. Build bitince sayfanın altında **Artifacts** bölümünden `Begum-GW-Detector-debug-apk` dosyasını indir.
7. İçinden `app-debug.apk` çıkar; Android telefona kurabilirsin.

## Notlar

- APK offline çalışır; HTML dosyası uygulamanın içine gömülüdür.
- Kamera ve mikrofon izinleri manifest'e eklendi.
- WebView, `file:///android_asset/index.html` üzerinden açılır.
- Bu debug APK'dır. Play Store'a koymak için release imzalama gerekir.
