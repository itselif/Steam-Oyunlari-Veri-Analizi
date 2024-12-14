# Steam Oyunları Veri Analizi

Bu proje, Steam platformundaki kullanıcı davranışlarını analiz etmeyi amaçlamaktadır. Steam, dünya çapında milyonlarca oyuncunun buluştuğu ve binlerce oyuna ev sahipliği yapan popüler bir PC oyun platformudur. Kullanıcıların oynama ve satın alma davranışlarını analiz etmek, oyun sektöründeki dinamikleri anlamak ve stratejiler geliştirmek için çok önemlidir.

---

## **Projenin Amacı**

Bu projede aşağıdaki sorulara cevap aranmaktadır:

1. Hangi oyunlar en çok oynanıyor ve satın alınıyor?
2. Kullanıcıların oynama davranışları ve süreleri arasında ne gibi ilişkiler var?
3. Oyun popülerliğini etkileyen faktörler nelerdir?
4. Oynama sıkılığı ve satın alma oranları arasındaki korelasyon nedir?

---

## **Veri Seti**

Analizde kullanılan veri seti, Steam kullanıcılarının platformdaki aktivitelerine dair bilgileri içermektedir. Veri setine [buradan ulaşabilirsiniz](https://www.kaggle.com/datasets/tamber/steam-video-games). Kaggle linkine ise [buraya tıklayarak](https://www.kaggle.com/code/itselif/steam-oyunlar-veri-analizi) ulaşabilirsiniz. Veri setimiz şu sütunlardan oluşmaktadır:

- **User_ID**: Her kullanıcıya özgü kimlik numarası.
- **Game**: Oyun adı.
- **Action**: Kullanıcının yaptığı işlem ("purchase" - satın alma, "play" - oynama).
- **Hours**: Oyun oynama süreleri (satın alma işlemi için her zaman 1 olarak kaydedilmiştir).
- **Other**: Ekstra bilgiler (bu analizde kullanılmamıştır).

---

## **Analiz Adımları**

1. **Eksik Verilerin Temizlenmesi:**
   - Veri setindeki eksik veya hatalı değerler belirlenerek uygun şekilde temizlenmiştir.

2. **Veri Dönüştürme ve Hazırlama:**
   - Satın alma ve oynama verileri, oyun bazında gruplandırılarak toplam saat sayıları hesaplanmış ve bu sayede temel metrikler oluşturulmuştur.

3. **En Popüler Oyunların Tespiti:**
   - En çok oynanan, satın alınan ve uzun süre oynanan oyunlar belirlenmiştir.

4. **Oynama ve Satın Alma Oranlarının Hesaplanması:**
   - Her oyun için bu iki metrik karşılaştırılarak popülerlik analiz edilmiştir.

5. **Korelasyon Analizi:**
   - Kullanıcı davranışları arasındaki ilişkiler incelenmiştir.

6. **Görselleştirme:**
   - Oynama sıklığı ve toplam oynama süresi gibi veriler grafiklerle desteklenmiştir.

---

## **Bulgular ve Yorumlar**

### 1. **En Çok Oynanan Oyunlar**
- Kullanıcıların toplam oynama sürelerine göre en popüler oyunlar: "Counter-Strike: Global Offensive" ve "Dota 2".

### 2. **En Çok Satın Alınan Oyunlar**
- Satın alma verilerine göre en çok tercih edilen oyunlar tespit edilmiştir.

### 3. **Oyun Popülerlik Puanları**
- Oynama ve satın alma oranları birleştirilerek oyun popülerlik puanları oluşturulmuştur.

### 4. **Korelasyon Sonuçları**
- Oynama süreleri ve satın alma oranları arasındaki ilişki incelenmiştir. Çok satın alınan fakat az oynanan oyunlar belirlenmiştir.

---

## **Kullanılan Araçlar ve Yöntemler**

- **Programlama Dili:** Python
- **Kütüphaneler:**
  - Pandas ve Numpy (veri işleme)
  - Matplotlib ve Seaborn (görselleştirme)
  - Scipy (korelasyon analizi)

---

## **Sonuçlar ve Gelecek Planları**

Bu analiz, Steam platformundaki kullanıcı davranışlarını anlamak için temel bir çerçeve sağlamıştır. Bulgular, oyun geliştiricilere stratejik kararlar alırken önemli bilgiler sunmaktadır.

### **Gelecek Adımlar:**
- Kullanıcı davranışlarını anlamak için makine öğrenmesi modellerinin uygulanması.
- Zaman serisi analizi ile trendlerin öngörülmesi.
- Daha ayrıntılı oyun tavsiye sistemleri geliştirilmesi.

---

Proje hakkında sorularınız için benimle iletişime geçebilirsiniz!

