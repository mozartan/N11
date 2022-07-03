# N11
Bu Projede,
N11 Favori Ürün Senaryosu test edilmiştir.
- www.n11.com sitesi açılır.
- Ana sayfanın açıldığı kontrol edilir.
- Siteye login olunur.
- Login işlemi kontrol edilir.
- Iphone kelimesi aranır.
- Iphone kelimesi aratıldığı kontrol edilir.
- Arama sonuçları sayfasından 2. sayfa açılır.
- 2nci sayfanın açıldığı kontrol edilir.
- Sayfadaki 3. ürün favorilere eklenir.
- Hesabım; Favorilerim / Listelerim sayfasına gidilir.
- “Favorilerim” sayfası açıldığı kontrol edilir.
- Eklenen ürün favorilerden silinir ve silme işlemi kontrol edilir.
- Üye çıkış işlemi yapılır.



### Gerekli Yazılım ve Araçlar

Bu kod IntelliJ IDEA IDE'sinde hazırlanmıştır.
Ayrıca kullanılan dil JAVA 8 ve üzeridir.
Maven 11 Build tool kullanılmıştır.

### Programın yüklenmesi

Githup ta açılan program sayfasında yeşil renkteki code bölümünden HTTPS kopyalanır.
IntelliJ programında
File<New<Project from Version Control seçilir. Açılan sayfada URL kısmına kopyalanan HTTPS yapıştırılır.
Clone düğmesine basılarak proje IntelliJ programına yüklenir.
Proje yüklendikten sonra açılan sayfada en sağ köşede bulunan maven sekmesinden Download Sources and/or Documents (Altı çizili Aşağı Ok simgesi) basılarak güncellemeler indirilir.


## Testin Çalıştırılması

Projenin çalıştırılıp HTML raporu oluşturulması için yine en sağ köşede bulunan maven sekmesinden 
N11<Lifecycle<clean seçilir.
Takiben
N11<Lifecycle<install seçilir.
Son olarak
N11<Lifecycle<verify seçilerek proje çalıştırılır.
Proje tamamlandıktan sonra en sol köşede bulunan Project sekmesinin altında
N11<target<cucumber-html-repots<overview-features.html bölümüne sağ tık yapılarak Open In < Browsers < Chrome (Firefox, Safari,..) seçilir. 
Browser da HTML olarak projenin screnshotları dahil tüm görünümü rapor halinde yer almaktadır.


Rapor almadan projeyi çalıştırmak için en sol köşede bulunan Project sekmesinin altında
N11<src<test<java<com.N11<runners<CukesRunner sayfası ana ekranda açılır. 
Açılan sayfada public class ın yanında yer alan yeşil run kısmına basılarak program çalıştırılır.


## Authors

* **Mustafa Özartan** - *Initial work* - [mozartan](https://github.com/mozartan)

