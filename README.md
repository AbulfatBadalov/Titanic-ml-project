🛳️ Titanic Yolcu Hayatta Kalma Tahmini – Decision Tree Modeli
Bu proje, Titanic felaketi sırasında yolcuların hayatta kalıp kalmayacağını öngörmek için bir karar ağacı (Decision Tree) sınıflandırma modeli geliştirmeyi amaçlamaktadır. Proje sürecinde Titanic veri seti kullanılarak temel veri ön işleme, modelleme ve değerlendirme adımları gerçekleştirilmiştir.

🔍 Proje Adımları:
Veri Yükleme ve İnceleme
Titanic yolcu verisi pandas ile yüklenmiş ve temel yapısı incelenmiştir.

Veri Ön İşleme

Gereksiz sütunlar (isim, bilet no, kabin gibi) çıkarılmıştır.

Kategorik veriler (Sex, Embarked) LabelEncoder ile sayısal formata dönüştürülmüştür.

Eksik değerler (özellikle Age ve Fare) ortalama ile doldurulmuştur.

Model Eğitimi

Veriler eğitim ve test olmak üzere %80-%20 oranında bölünmüştür.

DecisionTreeClassifier kullanılarak model eğitilmiştir.

Model Değerlendirmesi

Test verisi üzerinde accuracy, precision, recall ve f1-score gibi metriklerle değerlendirme yapılmıştır.

Model doğruluk oranı yaklaşık %78.8 olarak elde edilmiştir.

Model Görselleştirme

Eğitilen karar ağacı matplotlib ve sklearn.tree kullanılarak görselleştirilmiştir.

📈 Kullanılan Kütüphaneler:
pandas, numpy

sklearn (modelleme, değerlendirme ve görselleştirme)

matplotlib

🎯 Hedef:
Yolcuların yaşı, cinsiyeti, sınıfı gibi özelliklerine göre hayatta kalma olasılıklarını tahmin etmek ve bu süreci şeffaf bir karar ağacı ile görselleştirmek.

