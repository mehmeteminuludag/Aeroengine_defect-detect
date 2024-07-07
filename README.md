<h1><strong>Proje Adı: Hava Motoru Hatası Tespit Sistemi</strong></h1>

<h1><strong>Açıklama</strong></h1>
Bu proje, uçaklardaki hava motorlarında meydana gelen hataların türünü tespit etmeyi amaçlamaktadır. 
Bu sistem, motor verilerini analiz ederek ve derin öğrenme tekniklerini kullanarak, olası hata türlerini belirlemeyi hedeflemektedir.

<h1><strong>Özellikler</strong></h1>
Motor verilerini gerçek zamanlı olarak analiz eder.
Hata türlerini sınıflandırmak için derin öğrenme algoritmalarını kullanır.
Kullanıcı dostu arayüzü ile sonuçları görselleştirir.

<h1><strong>Kullanım</strong></h1>


<strong>ModelTest</strong> : modeli eğitip kaydettiğimizi varsayarak kaydettiğimiz adresten modeli alıp test verisi ile test edip test sonuçlarını görselleştirip okunmasını sağlar.

<strong>MobileNetV1</strong> : mobilenetv1 modeli ile transfer learning yapılıp uygun kalibrasyon ve eğitim ile bu veri için uygun hale gelmiştir.

<strong>VeriSınıflandırma</strong> : Bu yapı önemli çünkü verinin orijinalinde veriler sınıflandırılmamış ve karışık halde.Bu yapı orijinal verideki etiketler ile görsel verileri eşleştirip etiketlere göre verileri dosyalara gönderiyor kısaca veriyi işleyip model eğitimine hazır hale getiriyor.

<h1><strong>Veriler</strong></h1> 


Hazır verilere burdaki drive bağlantısından erişebilirsiniz : https://drive.google.com/drive/folders/1gyLOfgWVhGGUIL-xbW04bbBTmWemqE6D?usp=sharing

Orijinal veriye de burdaki kaggle bağlatınsından erişebilirsiniz : https://www.kaggle.com/datasets/wolfmedal/aero-engine-defect-new


