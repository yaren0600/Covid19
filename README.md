
# 🦠 COVID-19 Veri Analizi

Bu proje, COVID-19 pandemisine dair veriler üzerinde temel veri analizlerini içeren bir Jupyter Notebook çalışmasıdır. Amaç, veri setini incelemek, temizlik işlemleri yapmak ve çeşitli istatistiksel çıkarımlarda bulunmaktır.

## 📁 İçerik

Notebook aşağıdaki işlemleri gerçekleştirmektedir:

- Verinin pandas ile okunması ve kopyalanması
- İlk ve son 5 verinin görüntülenmesi
- Veri seti hakkında genel bilgi (`info()` ve `describe()` metodları)
- Eksik verilerin kontrolü ve işlenmesi
- Grafiksel analizler (muhtemelen matplotlib/seaborn ile)
- Zaman serisi ve ülke bazlı incelemeler

## 🛠 Kullanılan Kütüphaneler

Projede aşağıdaki Python kütüphaneleri kullanılmıştır:

- `pandas`
- `numpy`
- `matplotlib` (varsa)
- `seaborn` (varsa)
- `datetime` (varsa)

> Not: Kütüphane listesi Notebook'un ilerleyen hücrelerini görmeden tahmini olarak verilmiştir. İstersen detaylı liste çıkarabilirim.

## 📦 Veri Seti

Notebook içerisinde kullanılan veri seti: `covid_19_clean_complete.csv`  
Bu veri seti genellikle Johns Hopkins Üniversitesi’nin paylaştığı COVID-19 verilerinin temizlenmiş halidir.

## ▶️ Nasıl Çalıştırılır?

1. Gerekli kütüphanelerin yüklü olduğundan emin olun:
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```

2. Notebook'u çalıştırın:
   ```bash
   jupyter notebook Covid.ipynb
   ```

3. Gerekli veri dosyasının proje dizininde bulunduğundan emin olun:  
   `covid_19_clean_complete.csv`

## 📊 Örnek Görseller

Notebook içerisinde grafiksel analizler yer alıyorsa, örnek görseller buraya eklenebilir.

## 👤 Yazar

- Proje Sahibi: Begüm Yaren ÖZTÜRK
