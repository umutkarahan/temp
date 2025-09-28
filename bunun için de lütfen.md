# **Yapısal Enstrümantasyon Planlama Toplantısı**

**Değerlendirmeci:** Umut Karahan

## **Toplantı Konu Özetleri**

* **Genel Amaç:** Motorun kritik statik parçaları üzerine gerinim ölçer (strain gauge) ve ısılçift (thermocouple) yerleşimi yaparak, sonlu elemanlar analiz modellerinin test verisiyle doğrulanması (validasyonu) hedeflenmektedir. Bu kapsamda Afterburner Inner Ring, HPT NGV, LPT NGV, LPT Case ve HPT Case parçaları incelenmiştir.  
* **Analiz Modellerinin Durumu ve Kontrol İhtiyacı:**  
  * **Kritik Tespit:** Sunumlarda kullanılan stres ve sıcaklık analizlerinin birçoğunun 2021-2022 yıllarına ait olduğu ve PDR (Preliminary Design Review) sonrası yapılan güncellemeleri yansıttığı belirtilmiştir. Bu analizlerin güncel aerotermal yükler ve metodolojilerle **yenilenmemiş olma ihtimali** yüksektir. Bu durum, mevcut stres ve sıcaklık dağılımlarının güvenilirliğini sorgulatmıştır.  
  * **Genel Karar:** Strain gauge yerleşimine karar vermeden önce, sunulan tüm analiz modellerinin ilgili yapısal şef (Onur) tarafından kontrol edilmesi ve güncelliğinin teyit edilmesi gerektiği kararlaştırılmıştır. Ayrıca, analiz sonuç dosyalarının (result file) eksik olduğu ve bu dosyaların yeniden oluşturulması gerektiği vurgulanmıştır.  
* **Parça Bazında Değerlendirmeler ve Planlama:**  
  * **Afterburner Inner Ring:**  
    * Önerilen bölgede gerinim (\~100 MPa) ve sıcaklık (500-600°C) seviyeleri ölçüme uygun görünmektedir. Ancak, sensör yerleşimi için önerilen alanın (\~5mm) standart bir gerinim ölçer için dar olabileceği ve uygulamanın zorlayıcı olacağı belirtilmiştir.  
    * 3 adet sensör planlanmaktadır.  
  * **HPT ve LPT NGV (Nozzle Guide Vane):**  
    * Bu parçalar ömür açısından daha kritik olarak değerlendirilmiştir.  
    * Önerilen bölgelerde sıcaklıklar 750°C mertebesindedir. Bu yüksek sıcaklık, özel kablaj ve puntolama gibi özel uygulama teknikleri gerektirecektir.  
    * Gerinim ölçülecek alanlarda yüksek gerinim gradyanları bulunmaktadır. Bu durum, ölçümün noktasal bir değer yerine bir alanın ortalamasını yansıtmasına neden olacaktır.  
    * LPT Inner Ring parçasındaki gerinimler çok düşük olduğu için bu parçaya gerinim ölçer takılmasından vazgeçilmiş, sadece sıcaklık ölçümü yapılmasına karar verilmiştir. Buradan artan kanalların NGV'lere kaydırılması planlanmıştır.  
  * **HPT ve LPT Kılıfları (Case):**  
    * Önerilen bölgelerde sıcaklıklar \~300°C mertebesindedir. Bu sıcaklık seviyesi, standart tekil gerinim ölçerler yerine **rozet (rosette)** tipi gerinim ölçerlerin kullanımına imkan tanımaktadır. Rozet kullanımı, asal gerilme yönlerindeki belirsizlikleri ortadan kaldırarak daha kapsamlı veri sağlayacaktır.  
    * 3'er adet sensör planlanmaktadır.  
* **Enstrümantasyon Metodolojisi:**  
  * Gerinim ölçerlerin, maksimum veriyi alabilmek amacıyla analizden elde edilecek **asal gerilme (principal stress) yönlerine** göre yapıştırılması planlanmıştır. Bunun için analiz sonuçlarından asal gerilme vektörlerinin de çıkartılması gerekmektedir.  
  * Ölçümün amacı, anlık bir tasarım kararı vermekten ziyade, mevcut analiz modellerinin doğruluğunu test verisiyle karşılaştırmaktır.

## **Alınan Aksiyonlar**

| Aksiyon Tanımı | Aksiyon Sahibi | Son Teslim Tarihi |
| :---- | :---- | :---- |
| Sunulan tüm parçalara ait sonlu elemanlar analizlerinin güncelliğinin (yükler, sınır koşulları vb.) kontrol edilmesi ve gerekiyorsa **analizlerin yenilenmesi.** | İlgili Analiz Sorumluları / Onur (Şef Onayı) | Bir sonraki değerlendirmeden önce |
| Tüm analizlere ait **sonuç dosyalarının (result file)** eksiksiz olarak oluşturulması ve erişilebilir olması. | İlgili Analiz Sorumluları (Arda, Furkan vb.) | Bir sonraki değerlendirmeden önce |
| Tüm parçalar için, gerinim ölçer yerleştirilecek bölgelerdeki **asal gerilme vektörlerinin (yönlerinin)** analiz sonuçlarından çıkartılması. | İlgili Analiz Sorumluları (İbrahim, Batuhan vb.) | Bir sonraki değerlendirmeden önce |
| Ölçüm yapılacak her bir parça için, sensörlerin uygulanacağı alanın **boyutlarının (mm cinsinden)** netleştirilerek Umut Karahan'a iletilmesi. | İlgili Analiz Sorumluları | En kısa sürede |
| Yüksek sıcaklık (500-750°C) ve dar alanlar için uygun gerinim ölçer uygulama tekniklerinin (yapıştırıcı, kablaj, puntolama vb.) araştırılması. | Umut Karahan | Sürekli |
| HPT ve LPT kılıfları için **rozet tipi gerinim ölçer** kullanılması planının kesinleştirilmesi. | Umut Karahan / İlgili Ekipler | Bir sonraki değerlendirme |
| Tüm değerlendirmeler tamamlandıktan sonra, toplam kanal sayısına ve risk önceliklerine göre nihai sensör adet ve konumlarının belirlenmesi için tekrar bir araya gelinmesi. | Tüm Katılımcılar | Analizler güncellendikten sonra |

