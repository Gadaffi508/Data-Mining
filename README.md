# GitHub Veri Çekme ve Analiz Projesi

Bu proje, GitHub API'si kullanılarak bir organizasyona ait tüm depoları çekmek, bu verileri kategorize etmek ve yorumlar oluşturmak için geliştirilmiştir. Çıkış verileri bir CSV dosyasına kaydedilir ve analize hazır hale getirilir.

## Özellikler

- Belirtilen GitHub organizasyonundan tüm depoları çeker.
- Depoların açıklamaları ve yıldız sayılarına göre kategorize eder.
- Her depo için bir yorum oluşturur:
  - Yıldız sayısına göre popülerlik yorumu.
  - Açıklamasına göre paket türü (örneğin, grafik, fizik, araçlar, yapay zeka, vb.).
- Verileri CSV dosyasına kaydeder.
- Verilerin ilk birkaç satırını konsolda gösterir.

## Kurulum

1. **Gerekli Kütüphanelerin Kurulumu**  
   Aşağıdaki kütüphaneleri yükleyin:
   ```bash
   pip install requests beautifulsoup4 pandas
