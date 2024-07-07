Proje Adı: Hava Motoru Hatası Tespit Sistemi

Açıklama
Bu proje, uçaklardaki hava motorlarında meydana gelen hataların türünü tespit etmeyi amaçlamaktadır. 
Bu sistem, motor verilerini analiz ederek ve derin öğrenme tekniklerini kullanarak, olası hata türlerini belirlemeyi hedeflemektedir.

Özellikler
Motor verilerini gerçek zamanlı olarak analiz eder.
Hata türlerini sınıflandırmak için derin öğrenme algoritmalarını kullanır.
Kullanıcı dostu arayüzü ile sonuçları görselleştirir.

Kullanım
ModelTest : modeli eğitip kaydettiğimizi varsayarak kaydettiğimiz adresten modeli alıp test verisi ile test edip test sonuçlarını görselleştirip okunmasını sağlar.
MobileNetV1 : mobilenetv1 modeli ile transfer learning yapılıp uygun kalibrasyon ve eğitim ile bu veri için uygun hale gelmiştir.
VeriSınıflandırma : Bu yapı önemli çünkü verinin orijinalinde veriler sınıflandırılmamış ve karışık halde.Bu yapı orijinal verideki etiketler ile görsel verileri eşleştirip etiketlere göre verileri dosyalara gönderiyor kısaca veriyi işleyip model eğitimine hazır hale getiriyor.

Hazır verilere burdaki drive bağlantısından erişebilirsiniz : https://drive.google.com/drive/folders/1gyLOfgWVhGGUIL-xbW04bbBTmWemqE6D?usp=sharing

Orijinal veriye de burdaki kaggle bağlatınsından erişebilirsiniz : https://www.kaggle.com/datasets/wolfmedal/aero-engine-defect-new


