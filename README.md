Proje Adı: Geri Dönüşüm Çöpü Sınıflama

Proje Amacı:
Bu projenin amacı, atık malzemeleri doğru şekilde sınıflandırarak geri dönüşüm verimliliğini artırmak ve çevresel sürdürülebilirliğe katkı sağlamaktır.

Veri Seti:
Proje, Kaggle'dan alınan TrashNet veri seti kullanılarak gerçekleştirilmiştir.
https://www.kaggle.com/datasets/feyzazkefe/trashnet

Kullanılan Kütüphaneler:

Python

TensorFlow & Keras

OpenCV

Matplotlib & Seaborn

Scikit-learn

Numpy

Pandas

Veri İşleme:

Veri seti, resimlerin sınıflandırılması ve etiketlenmesi için yüklendi. Görseller, eğitim sürecini iyileştirmek için ImageDataGenerator ile artırıldı.

Model:

Model olarak Convolutional Neural Network (CNN) kullanıldı. Modelin yapısı şu şekildedir:

Convolutional Katmanlar

MaxPooling Katmanları

Flatten Katmanı

Dense Katmanlar

Dropout Katmanları

Eğitim:
Model, eğitim verileri ile eğitildi ve doğrulama verileri ile test edildi. Model performansı precision, recall, ve accuracy metrikleri ile değerlendirildi.

Sonuçlar:
Model, eğitim sürecinde yüksek doğruluk oranına ulaştı ve sınıflandırma görevlerinde tutarlı sonuçlar verdi.

Gelecek Çalışmalar:

Modelin daha büyük veri setleri ile eğitilmesi
Gerçek dünya uygulamaları için bir platform geliştirilmesi
