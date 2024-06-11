Proje Açıklaması
Bu proje, geri dönüşüm materyallerinin sınıflandırılmasını amaçlayan bir derin öğrenme modelinin geliştirilmesini içerir. Model, çeşitli çöp türlerini tanıyarak doğru şekilde sınıflandırmayı ve atık yönetim süreçlerini daha verimli hale getirmeyi amaçlamaktadır. Model, altı farklı çöp türünü sınıflandırmak için eğitilmiştir: karton, cam, metal, kağıt, plastik ve çöp.

Veri Kümesi
Proje kapsamında kullanılan veri kümesine aşağıdaki bağlantıdan ulaşabilirsiniz:
TrashNet Veri Kümesi

Gereksinimler
Bu projeyi çalıştırmak için aşağıdaki kütüphanelerin yüklü olması gerekmektedir:

Python 3.x
OpenCV
NumPy
Pandas
Seaborn
Matplotlib
Scikit-learn
TensorFlow
Keras
imutils

Gereksinimleri yüklemek için aşağıdaki komutu kullanabilirsiniz:


pip install opencv-python-headless numpy pandas seaborn matplotlib scikit-learn tensorflow keras imutils

Veri Ön İşleme
Veri Setinin Yüklenmesi:
Görüntüler veri kümesi dizininden yüklenir ve 224x224 piksel hedef boyuta yeniden boyutlandırılır. Her bir görüntünün etiketleri, dizin yapısına göre belirlenir.

Veri Artırma:
Eğitim verilerinin çeşitliliğini artırmak ve model performansını iyileştirmek için veri artırma teknikleri uygulanır.

Model Mimarisi
Sınıflandırma için kullanılan model, Keras ile oluşturulmuş bir Evrişimsel Sinir Ağı (CNN)'dir. Bu model, çeşitli katmanlardan oluşur ve atık materyallerini sınıflandırmak için optimize edilmiştir.

Model Eğitimi
Model, Adam optimizasyon algoritması ve kategorik çapraz entropi kayıp fonksiyonu kullanılarak derlenmiştir. Eğitim süreci, erken durdurma ve model kontrol noktası kaydetme teknikleri kullanılarak en iyi modelin saklanmasını sağlar.

Değerlendirme
Modelin performansı, kesinlik, geri çağırma ve doğruluk gibi metriklerle değerlendirilebilir. Ayrıca, model performansını değerlendirmek için karışıklık matrisi ve sınıflandırma raporu kullanılır.

Sonuç
Bu proje, atık yönetimi alanında derin öğrenmenin pratik bir uygulamasını göstermektedir. Farklı atık türlerini doğru bir şekilde sınıflandırarak, bu model geri dönüşüm süreçlerinin daha verimli hale getirilmesine katkıda bulunabilir.

Daha fazla detay ve tam kod için lütfen ekli Jupyter notebook dosyasına bakınız.
