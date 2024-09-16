# 📊 Tip Tahmini için Veri Analizi ve Modelleme

## Bu çalışmada, restoran bahşiş veri seti üzerinde veri analizi, görselleştirme, ön işleme ve modelleme adımları gerçekleştirilmiştir. Aşağıda bu süreçte izlenen adımlar özetlenmiştir:

### 1. 📥 Veri Yükleme ve İnceleme:
Veri Seti: Kaggle üzerindeki The Waiter's Tip data seti kullanıldı. 🍽️

Amaç: Verinin yapısını anlamak için veri seti incelendi ve temel istatistiksel bilgiler gözden geçirildi. 🔍

### 2. 🔧 Veri Ön İşleme:
Kategorik Değişkenlerin Kodlanması:

Label Encoding: sex değişkeni, LabelEncoder kullanılarak erkekler için 1, kadınlar için 0 olacak şekilde kodlandı. 👨‍⚕️👩‍⚕️
One-Hot Encoding: smoker, day, ve time değişkenleri one-hot encoding yöntemiyle binary (ikili) değişkenlere dönüştürüldü. 🚬📅⏰
### 3. 🔍 Keşifsel Veri Analizi (EDA):
Korelasyon Matrisi: Veri setindeki değişkenler arasındaki korelasyonları incelemek için korelasyon matrisi hesaplandı ve heatmap ile görselleştirildi. 🌡️

Veri Görselleştirme: Dağılım grafikleri ve diğer görselleştirmeler ile değişkenler arası ilişkiler analiz edildi. 📈📉

### 4. 🧑‍🔬 Modelleme:
Linear Regression: İlk olarak, temel bir lineer regresyon modeli kurularak bahşiş (tip) tahminleri yapıldı. Modelin performansı MSE ve R² skorları ile değerlendirildi. 📉🔍

Çapraz Doğrulama: Modelin genelleme yeteneğini değerlendirmek için k-fold çapraz doğrulama yapıldı. 🔄

XGBoost: Ek olarak, XGBoost modeli ile tahminler gerçekleştirildi ve Linear Regression modeli ile karşılaştırma yapıldı. 🌟📊

### 5. 📝 Sonuçlar ve Değerlendirme:
Performans Karşılaştırması: Linear Regression ve XGBoost modellerinin performansları karşılaştırıldı, MSE ve R² skorları analiz edildi. ⚖️

İyileştirme Önerileri: Modelin performansını artırmak için ileriye yönelik öneriler sunuldu. 🚀
