# workouts_and_body_information
# Vücut Kitle İndeksi ve Kas Grubu Takibi Programı
Bu Python programı, kullanıcıların vücut kitle indeksi (BMI) ve vücut yağ oranlarını hesaplamalarına yardımcı olur. 
Ayrıca kullanıcıların haftalık egzersizlerini kaydederek hangi kas gruplarını çalıştırdıklarını takip eder ve bunlara göre sağlık puanları oluşturur.
Haftalık veriler görsel olarak pasta ve çubuk grafikleriyle gösterilir.

## Özellikler:

* Vücut Kitle İndeksi (BMI) ve Vücut Yağ Oranı hesaplama
* Haftalık egzersiz takibi ve kas grubu kullanım verilerinin kaydedilmesi
* Kas grubu kullanım yüzdelerinin görsel gösterimi
* Haftalık sağlık puanları verilmesi ve egzersiz istatistiklerinin hesaplanması
  
## Kullanım:
1.Python ve Gerekli Kütüphaneler:
* math (Matematiksel hesaplamalar için)
* matplotlib (Grafik çizimi için)
* json (Veri saklamak için)

2. Kurulum:
* Python son sürüm yüklü olmalıdır.
* Gereksinimlerinizi kurun:
  -pip install matplotlib

3.Programı Çalıştırma:
Lütfen kodları Google Colab gibi online sürücülerde çalıştırmayınız.
Tercihen Anaconda üzerinden JupyterLab'de çalıştırınız.

4. Kullanıcı Girişi:
* Program, yaş, boy, kilo, cinsiyet, bel, boyun, kullanıcı kadın ise kalça ölçüleri gibi veriler isteyecektir.
* Her gün için kullanıcının spor egzersizlerini girmesini istenecektir.

5.Çıktılar:
* Vücut Kitle İndeksi ve Vücut Yağ Oranı.
* Haftalık kas grubu kullanım yüzdeleri.
* Önceki haftaya göre kas grubu kullanım karşılaştırmaları.
* Haftalık sağlık puanları ve grafikler.

## Önemli Notlar:
* Kadınlar için kalça ölçüsü gereklidir.
* Eğer spor hareketi bilinmiyorsa, program bunu bildirecektir.
* JupyterLab,Spyder gibi IDElerde çalıştırınız.


## Programın yazılış süreci hakkında önemli bilgiler
* Süreçte kas grubu verileri chatgpt ile çekilmiştir. En fazla 2 kas grubu en çok çalıştırılan bölgelerden seçilmiştir.
* Hareket çeşitliliği noktasında MacFit spor uygulamasından yararlanılmıştır.
