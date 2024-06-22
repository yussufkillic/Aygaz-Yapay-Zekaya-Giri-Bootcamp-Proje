# Aygaz-Yapay-Zekaya-Giri-Bootcamp-Proje


# 1. PROJENİN AMACI 

Bu proje, MNIST veri setini kullanarak el yazısı rakamları tanıma problemini çözmeyi amaçlamaktadır. Temel amaç, farklı makine öğrenimi modellerini eğitmek, bu modellerin doğruluğunu değerlendirmek ve 
en iyi performansı gösteren modeli belirlemektir. Proje, veri ön işleme adımlarıyla başlayarak, farklı sınıflandırma algoritmalarının (KNN, SVM, Lojistik Regresyon, Karar Ağacı, Rastgele Orman, Gradient Boosting) 
eğitimini içermektedir. Her bir modelin doğrulama setindeki performansı ölçülmüş ve en iyi performans gösteren model, test seti üzerinde de değerlendirilmiştir. 
Sonuç olarak, MNIST veri seti üzerinde hangi modelin en iyi sonucu verdiği belirlenerek, el yazısı rakamlarını tanıma problemine yönelik etkili bir çözüm sunulmuştur.

# 2. KULLANILAN VERİ SETİ HAKKINDA

MNIST veri seti, el yazısı rakamlarını içeren ve genellikle makine öğrenimi modellerinin eğitimi ve değerlendirmesi için kullanılan bir benchmark olarak kabul edilen bir veri setidir. 
Veri seti, Modified National Institute of Standards and Technology (MNIST) tarafından hazırlanmıştır ve geniş bir araştırma topluluğu tarafından yaygın olarak kullanılmaktadır.

MNIST veri seti şu özelliklere sahiptir:

Veri Boyutu: Toplamda 70,000 el yazısı rakam görüntüsü içerir.
Eğitim Seti: 60,000 görüntüden oluşur. Bu görüntüler, elle yazılmış rakamların 28x28 piksel boyutlarındaki siyah-beyaz görüntüleridir.
Test Seti: 10,000 görüntüden oluşur. Eğitim setinden farklı el yazısı rakamlar içerir ve aynı boyutta görüntülerden oluşur.
Etiketler: Her bir görüntü, içerdiği rakamın doğru etiketiyle eşleştirilmiştir (0'dan 9'a kadar olan rakamlar)

# 3. BULGULAR

Proje kapsamında, MNIST veri seti üzerinde farklı makine öğrenimi modelleri kullanılarak el yazısı rakamlarını tanıma görevi değerlendirilmiştir. 
Modeller arasında KNN, SVM, Lojistik Regresyon, Karar Ağacı, Rastgele Orman ve Gradient Boosting bulunmaktadır. Eğitim sürecinde veri öncelikle normalizasyon ve düzleştirme işlemlerinden geçirilmiştir.

Yapılan değerlendirmeler sonucunda en yüksek doğruluğa (accuracy) ve kesinliğe (precision) sahip model olarak SVM ve Lojistik Regresyon modelleri belirlenmiştir. 
Bu modeller, doğrulama seti üzerinde diğer modellere kıyasla daha yüksek performans sergilemiştir. 
Özellikle SVM modeli, çok sınıflı sınıflandırma problemlerinde iyi bir performans göstermiş ve test seti üzerinde de başarılı sonuçlar vermiştir.

Karar Ağacı ve Rastgele Orman modelleri ise diğer modellere göre daha düşük doğruluk skorları elde etmiştir. 
Gradient Boosting ise orta düzeyde bir performans sergilemiş ancak SVM ve Lojistik Regresyon modellerinin gerisinde kalmıştır.

Sonuç olarak, MNIST veri seti üzerinde yapılan çalışmada SVM ve Lojistik Regresyon modellerinin el yazısı rakamları tanıma görevinde en iyi performansı gösterdiği ve 
bu modellerin tercih edilmesi gerektiği sonucuna varılmıştır. Bu bulgular, el yazısı tanıma ve sınıflandırma problemlerine yönelik gelecekteki çalışmalarda kullanılabilecek önemli bir referans sağlamaktadır.
