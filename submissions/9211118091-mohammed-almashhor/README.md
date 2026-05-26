Track: C

# Nokta-Nokta: Kampüs İçi Pazar Yeri & Otonom AI Asistan

Bu proje, öğrencilerin ".edu.tr" e-posta adresleriyle üye olabildikleri, güvenli ve kampüs içi bir pazar yeri vizyonunu içerir. Geliştirilen uygulama, **Phase C (Halka Kapanışı)** gereksinimlerini eksiksiz karşılamak üzere tasarlanmıştır.

## Öne Çıkan Geliştirmeler
1. **Otonom STT ve Dudak Senkronizasyonu**: Mikrofon aracılığıyla kullanıcının ses girişleri analiz edilir ve ekrandaki 3D Avatara (`react-three-fiber` kullanılarak) dudak senkronizasyonu ile aktarılır.
2. **Hitl-STUCK (Uzman Müdahalesi)**: Yapay zekanın tıkandığı veya mimari kararlarda destek istediği durumlarda WebRTC tabanlı (Jitsi) bir video konferans odası otonom olarak tetiklenir.
3. **Engineering Probes**: Fikirlerin Slop-Check aşamasından geçirilerek en saf mimari limitlerinin ("Core Problem", "Core Mechanic", "Scope Cut") belirlenmesi sağlanmıştır.

## Dosya Yapısı
- `app/`: Expo React Native projesinin ana dizini.
- `avatar.glb`: Avaturn.me üzerinden dışa aktarılmış, projeye özel kullanıcı yüzü.
- `FORGE.md`: Geliştirici-kullanıcı simülasyon döngülerini (Commit/Rollback) barındırır.
- `BRIDGE.md`: Kasıtlı STUCK senaryosu sonrasında insan uzmanla yapılan görüşmenin özetini içerir.
- `DECISIONS.md`: Mimari kararların mantıksal zeminini belgeler.
- `app-release.apk`: Uygulamanın doğrudan test edilebilir derlenmiş Android çıktısı.
- `demo.mp4`: Tüm fonksiyonların baştan sona çalıştırıldığı 3 dakikalık video.
