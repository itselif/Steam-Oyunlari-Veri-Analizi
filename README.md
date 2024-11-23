# Steam Oyunları Veri Analizi
Kaggle: https://www.kaggle.com/code/itselif/steam-oyunlar-verianalizi

![steam](https://github.com/user-attachments/assets/e70321a9-4299-4386-af89-563acf08dd39)

Bu proje, Steam platformundaki kullanıcı davranışlarını analiz etmeyi amaçlamaktadır. Steam, dünya çapında milyonlarca oyuncunun buluştuğu ve 6,000'den fazla oyuna ev sahipliği yapan popüler bir PC oyun platformudur. Bu geniş koleksiyonu daha iyi anlamak için kullanıcıların oynama ve satın alma davranışlarını analiz etmek büyük önem taşır.

**Veri Seti:** https://www.kaggle.com/datasets/tamber/steam-video-games
Analizde kullandığımız veri seti, Steam kullanıcılarının platform üzerindeki aktivitelerine dair bilgileri içerir ve şu sütunları içerir:

* User_ID: Her kullanıcıya özgü kimlik numarası.
* Game: Oyun adı.
* Action: Kullanıcının yaptığı işlem ('purchase' - satın alma, 'play' - oynama).
* Hours: Oyun oynama süresi (satın alma işlemi için her zaman 1).
* Other: Ekstra bilgiler (bu analizde kullanılmayacak).
Bu veri setiyle, oyunların popülerliğini, oynanma sıklığını, satın alma oranlarını ve oyuncuların tercih eğilimlerini inceleyeceğiz. Elde edilen bulgular, oyun pazarındaki dinamikleri ve oyun stratejilerini daha iyi anlamamıza yardımcı olacaktır.

# Temel Bulgular ve İşlemler
Eksik Verilerin Gözlemlenmesi ve Temizlenmesi: İlk olarak, veri setinde eksik veya hatalı veri değerleri tespit edilmiştir. Bu eksikliklerin doğru şekilde analiz yapılabilmesi için temizlenmesi gerektiği gözlemlenmiş ve eksik değerler uygun bir şekilde giderilmiştir.

Veri Dönüştürme ve Hazırlama: Satın alma ve oynama verileri, oyun bazında gruplandırılmış ve toplam saat sayıları hesaplanmıştır. Bu sayede oyunların oynama sıklığı, satın alma oranları ve oynama süresi gibi metrikler elde edilmiştir.

En Çok Oynanan Oyunlar: Oynama verileri analiz edilerek, en çok oynanan oyunlar sıralanmıştır. Bu oyunların kullanıcılar tarafından ne kadar süreyle oynandığı gözlemlenmiştir.

En Çok Satın Alınan Oyunlar: Satın alma verileri analiz edilerek, en çok satın alınan oyunlar tespit edilmiştir. Satın alma oranları hesaplanmış ve en popüler oyunlar belirlenmiştir.

En Uzun Süre Oynanan Oyunlar: Kullanıcıların oyunlar üzerinde harcadığı toplam süre analiz edilerek, en uzun süre oynanan oyunlar sıralanmıştır. Bu, oyunların kullanıcılar üzerinde oluşturduğu bağlılık düzeyini gösteren önemli bir metriktir.

Oynama Oranı ve Satın Alma Oranı: Oynama ve satın alma oranları hesaplanarak, her oyun için bu metrikler üzerinden popülerlik değerlendirmeleri yapılmıştır. Hem normal değerler hem de yüzde oranları hesaplanarak karşılaştırmalar yapılmıştır.

Popülerlik Hesaplama: Oyunların popülerlik seviyeleri, oynama oranı ve satın alma oranının birleşimiyle hesaplanmıştır. Bu iki metrik birleştirilerek her oyun için bir popülerlik puanı oluşturulmuştur.

Korelasyon Analizi: Oyunların satın alma ve oynama davranışları arasındaki ilişki incelenmiştir. Bu analiz, oyunların başarılarını etkileyen faktörleri anlamaya yönelik önemli çıkarımlar sunmuştur.

Görselleştirme: Elde edilen veriler, çeşitli grafikler aracılığıyla görselleştirilmiştir. Oynama ve satın alma oranları gibi veriler, daha anlaşılır bir şekilde sunulmuş ve grafiklerle desteklenmiştir.
