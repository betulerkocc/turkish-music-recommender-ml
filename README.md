# turkish-music-recommender-ml
Kullanıcının ruh haline göre makine öğrenmesi (KNN) kullanarak şarkı öneren bir müzik asistanı.

# Mood-Based Music Recommender (Turkish Tracks)

Bu proje, kullanıcının o anki ruh haline göre en uygun Türkçe şarkıları öneren bir **Makine Öğrenmesi** tabanlı sistemdir. Spotify'ın ses özelliklerini (audio features) kullanarak müzikal benzerlik analizi yapar.

## Özellikler
* **K-Nearest Neighbors (KNN):** Şarkıları 9 boyutlu bir vektör uzayında analiz ederek en yakın benzerleri bulur.
* **Duygu-Müzik Eşleşmesi:** Enerji ve Mutluluk (Valence) değerlerini temel alan 6 farklı duygu modu içerir.
* **Spotify Entegrasyonu:** Önerilen şarkılar için otomatik arama linkleri oluşturur.
* **Veri Normalizasyonu:** Tüm müzikal verileri (tempo, enerji vb.) aynı ölçekte işlemek için normalizasyon teknikleri kullanılmıştır.

## Teknolojiler
* **Python 3.x**
* **Pandas:** Veri manipülasyonu ve temizliği.
* **Scikit-learn:** Makine öğrenmesi modeli (KNN).
* **Urllib:** Dinamik URL ve link yönetimi.

## Veri Seti
Kaggle'daki Spotify Tracks veri seti kullanılmış, sadece Türkçe şarkılar üzerine filtrelenerek optimize edilmiştir.

## Nasıl Çalıştırılır?
1. Kod dosyasını (`.ipynb` veya `.py`) çalıştırın.
2. Karşınıza çıkan menüden o anki ruh halinizi (1-6 arası) seçin.
3. Sistem size en uygun 5 şarkıyı Spotify linkleriyle birlikte listeleyecektir.

---
*Bu proje bir Bilgisayar Mühendisliği öğrencisi tarafından veri madenciliği ve makine öğrenmesi pratikleri yapmak amacıyla geliştirilmiştir.*
