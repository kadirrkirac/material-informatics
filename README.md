GitHub reponun README.md dosyasına doğrudan yapıştırabileceğin Markdown kodunu aşağıda bulabilirsin. Dosyayı düzenle (edit) moduna alıp bu içeriği yapıştırdığında her şey doğru formatta ve profesyonel görünecektir.

Markdown
# Material Informatics for SOFC Cathode Design: SCaSC-SDC System

Bu proje, orta ve düşük çalışma sıcaklıkları (**400-650°C**) için geliştirilen **SCaSC-SDC** ($Sr_{1-x}Ca_xSm_yCo_{3-\delta}$ - Samaryum Katkılı Seryum Oksit) kompozit katotların yapısal kararlılığını ve termodinamik özelliklerini analiz etmek amacıyla geliştirilmiştir. Çalışma, malzeme bilimi prensiplerini modern bilişim (informatics) araçlarıyla birleştirerek deneysel süreç öncesi teorik bir optimizasyon sunar.

## 🎯 Proje Hedefleri

*   **Geometrik Kararlılık Analizi:** Ca katkısının perovskit yapısındaki kafes bozulmasına etkisini **Goldschmidt Tolerans Faktörü ($t$)** üzerinden teorik olarak hesaplamak.
*   **Veri Madenciliği (Data Mining):** Materials Project veri tabanı üzerinden Co-O tabanlı sistemlerin oluşum enerjilerini (Formation Energy) çekerek termodinamik trendleri belirlemek.
*   **Özellik Mühendisliği (Feature Engineering):** Elementlerin iyonik yarıçap, elektronegatiflik ve valans elektronu gibi fiziksel özelliklerini sayısallaştırarak makine öğrenmesi modellerine girdi sağlamak.
*   **Performans Tahminleme:** Makine öğrenmesi (**Random Forest**) algoritmaları kullanarak farklı kompozisyonların enerji kararlılığını öngörmek.

## 🛠 Kullanılan Araçlar ve Metodoloji

*   **Pymatgen:** Kristal yapı analizi ve Shannon iyonik yarıçap verilerinin otomatik çekilmesi.
*   **Materials Project API (MP-API):** DFT tabanlı hesaplanmış malzeme verilerine erişim ve veri seti oluşturma.
*   **Scikit-learn:** Malzeme özelliklerine dayalı regresyon modellerinin geliştirilmesi.
*   **Plotly & Matplotlib:** İnteraktif stabilite haritaları ve veri görselleştirme.
*   **Google Colab:** Bulut tabanlı Python geliştirme ortamı.

## 🧪 Akademik Bağlam

Bu çalışma, kalsiyum katkısının **faz kararlılığını koruma**, **termal genleşme katsayısını azaltma** ve **oksijen boşluk konsantrasyonunu artırma** potansiyelini teorik olarak doğrulamayı amaçlar. Elde edilen veriler, TÜBİTAK kapsamında yürütülen "SCaSC-SDC bazlı kompozit katotların üretimi ve karakterizasyonu" projesinin dijital temelini oluşturmaktadır.

---
*Bu proje Kadir Kıraç tarafından Malzeme İnformatiği çalışmaları kapsamında geliştirilmiştir.*
