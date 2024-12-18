**Haptic Fabric Touch Recognition with PCA ve Hiperparametre Optimizasyonu**

Bu proje, özel olarak üretilmiş akıllı kumaş üzerinde kullanıcı etkileşimlerini tanımayı amaçlamaktadır. Veri seti, kumaşa yerleştirilen 16 iletken iplik kanalından, her bir kanalda 200 farklı frekansta sinyallerin ölçüldüğü bir koleksiyondan elde edilmiştir. Amaç, dokunuş türlerini sınıflandırmak, kullanıcıları tanımak ve Principal Component Analysis (PCA) ve Hiperparametre Optimizasyonu gibi tekniklerle model performansını iyileştirmektir.

Bu proje, akıllı bir kumaş üzerinde çeşitli dokunuş türlerini (parmak, avuç içi, yumruk) tanımak için makine öğrenimi modelleri kullanmayı hedeflemektedir. Veri seti, 30 farklı kullanıcı tarafından yapılan 9 farklı dokunuş türünü içermektedir. Proje, Principal Component Analysis (PCA) kullanarak boyut indirgeme ve Hiperparametre Optimizasyonu ile Support Vector Classifier (SVC) modelini optimize etme tekniklerinin kullanımını göstermektedir. Ayrıca, Decision Tree (Karar Ağaçları) modelleri de performans değerlendirmesi için kullanılmıştır.

**Veri Seti**
Bu projede kullanılan veri seti, 16 iletken iplikten oluşan akıllı bir kumaştan elde edilen dokunuş verilerini içermektedir. Veri setinde yer alan sütunlar şunlardır:

touch_type: Dokunuş tipi (0 = dokunuş yok, 1-9 = farklı dokunuş türleri).
user_id: Kullanıcı ID'si (1-30).
Veri sütunları: 16 iletken iplikten alınan sinyal ölçümleri, her biri 200 farklı frekansta.
Dokunuş Türleri
0: Dokunuş yok
1-9: Farklı dokunuş türleri (parmak, avuç içi, yumruk).


**Kurulum**
Bu projeyi çalıştırmak için Python ve aşağıdaki bağımlılıklara ihtiyacınız olacak:

pandas
numpy
sklearn
matplotlib
seaborn
Bağımlılıkları yüklemek için aşağıdaki komutu kullanabilirsiniz:
pip install pandas numpy scikit-learn matplotlib seaborn
