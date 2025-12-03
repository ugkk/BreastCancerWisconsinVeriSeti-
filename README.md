# BreastCancerWisconsinVeriSeti-  
Bu proje Google Colab ile hazırlanmıştır. Google colabs linki :https://colab.research.google.com/drive/1wklILmgfFwoVZzaLI9fJkOq8TIVVi5Kn?usp=sharing

Breast Cancer Wisconsin veri seti kullanılarak meme kanseri örneklerini benign / malignant olarak sınıflandıran bir MLP (Multilayer Perceptron) sinir ağı modeli geliştirilmiş, ardından Optuna ile hiperparametre optimizasyonu yapılmış ve modeller SHAP ile açıklanabilir hâle getirilmiştir.
Amacımız sadece yüksek doğruluk elde etmek değildi aynı zamanda modelin karar verirken hangi özelliklere dayandığını da ortaya koymaktı.
Veri setimizin kaynağı sklearn.datasets.load_breast_cancer olup örnek sayısı 569 özellik sayısı 30 (tümörün yarıçapı, alanı, çevresi, konkavlık vb. morfolojik ölçümler) 
ve hedef değişkenleri malignant(0) ve benign(1)'ten oluşmaktadır.
Çalışmamızda Veri Kalite Kontrolleri, Keşifsel Veri Analizi (EDA), Ölçeklendirme, 
Veri Setinin Bölünmesi, Beş Farklı MLP Modeli, Model Karşılaştırması, Optuna ile Hiperparametre Optimizasyonu ve SHAP ile Açıklanabilirlik (XAI) adımlarından oluşmaktadır. 
Geliştirilen MLP tabanlı sınıflandırıcılar, Breast Cancer Wisconsin veri seti üzerinde yüksek doğruluk ve F1-score değerlerine ulaşmıştır.Optuna ile yapılan hiperparametre optimizasyonu, elle seçilen mimarilere göre Accuracy, Precision, F1 ve ROC-AUC metriklerini anlamlı ölçüde artırmış,Recall değerini ise neredeyse aynı seviyede korumuştur.
SHAP analizleri, modelin klinik olarak da anlamlı olan tümör boyutu ve kenar düzensizliği özelliklerine dayandığını göstermiş ve böylece modelin kararları açıklanabilir ve yorumlanabilir hâle gelmiştir.





