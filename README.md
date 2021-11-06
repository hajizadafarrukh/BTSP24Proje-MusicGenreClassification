# Music Genre Classification Django

BTSP 24 FINAL Project (METU-ODTÜ)
 Django website for predicting Genre of Music by using Machine Learning Model.
 
# Working of website:
* You need to upload the .wav music file in order to predict the genre of that file.
* If the file is not .wav file then it will show an error.
* If the file is .wav format then within 30 seconds our model will predict the genre of the music file that you uploaded and show it to you.

## Enjoy.
 

 
Proje Tanımı


Müziği türe göre sınıflandırmak için ML tabanlı bir projedir. ML modeli, Django kullanılarak dağıtılır. Bu projede kullanıcılar, web uygulamaya müziğin türünü tahmin etmek için müzik dosyasını yüklemeleri gerekir. Bu Dosya .wav dosyası değilse kullanıcılar bir hata görecekler. 30 saniye içinde modelimiz yüklenilen müzik dosyasının türünü tahmin edecek ve kullanıcıya gösterecektir.


Projenin Kapsamı

Ses dosyalarından olan  farklı müzik türlerini otomatik olarak sınıflandırmak için bir derin öğrenme projesi geliştireceğiz. Bu ses dosyalarını düşük seviyeli frekans ve zaman alanı özelliklerini kullanarak sınıflandıracağız.

Bu proje için, benzer boyuta ve benzer frekans aralığına sahip bir ses parçası veri setine ihtiyacımız var. GTZAN tür sınıflandırma veri kümesi, müzik türü sınıflandırma projesi için en çok önerilen veri kümesidir ve yalnızca bu görev için toplanmıştır.

GTZAN tür koleksiyonu veri kümesi her biri 30 saniye süreli 1000 ses dosyasından oluşur. Her biri 100 ses parçası içeren 10 sınıf (10 müzik türü) vardır. Her parça .wav biçimindedir. Aşağıdaki 10 türden ses dosyalarını içerir:

●	Blues
●	Klasik
●	Ülke
●	Disko
●	Hiphop
●	Caz
●	Metal
●	Pop
●	Reggae
●	Rock


Yöntemler, Yazılım Araçları ve Platform

Süreç Modeli:  Çağlayan modeli prensibi dikkate alınacaktır. 

İşletim Sistemi: Windows/Linux/MacOS(Web platforma uyarlama düşünülmektedir.)

Veri Tabanı Sunucusu: sqlite3(Django Paketinden Gelir)

Programlama Dili ve Framework: Python / Django

