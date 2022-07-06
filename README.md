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

Test senoryaları N11<src<test<resources<features<N11.feature ayrıntılı görülebilir.

# In this Project, the N11 Favorite Product Scenario was tested.

- The www.n11.com site opens.
- Check that the main page is opened.
- Login to the site.
- The login process is checked.
- The word iphone is searched.
- It is checked that the word iphone is searched.
- The 2nd page opens from the search results page.
- It is checked that the 2nd page is opened.
- The 3rd product on the page is added to favourites.
- My account; Go to My Favorites / My Lists page.
- Check that the "My Favorites" page is opened.
- The added product is deleted from the favorites and the deletion process is checked.
- Member logout process is done.

# Required Software and Tools
This code is prepared in IntelliJ IDEA IDE. In addition, the language used is JAVA 8 and above. Maven 11 Build tool is used.

# Installing the program
HTTPS is copied from the green code section on the program page opened in Githup. In IntelliJ program, File<New<Project from Version Control is selected. On the page that opens, the copied HTTPS is pasted into the URL part. By clicking the Clone button, the project is loaded into the IntelliJ program. After the project is loaded, the updates are downloaded by clicking Download Sources and/or Documents (Underlined Down Arrow icon) from the maven tab in the far right corner of the page that opens.

# Running the Test
In order to run the project and generate an HTML report, N11<Lifecycle<clean is selected from the maven tab in the far right corner. Then N11<Lifecycle<install is selected. Finally, the project is run by selecting N11<Lifecycle<verify. After the project is completed, under the Project tab in the far left corner, right click on N11<target<cucumber-html-repots<overview-features.html and select Open In < Browsers < Chrome (Firefox, Safari, ..). In the browser, the entire view of the project, including the screnshots, is included in the report as HTML.

To run the project without getting a report, N11<src<test<java<com.N11<runners<CukesRunner page is opened on the main screen under the Project tab in the far left corner. The program is run by pressing the green run part next to the public class on the page that opens.

Test scenarios N11<src<test<resources<features<N11.feature can be viewed in detail.

## Authors

* **Mustafa Özartan** - *Initial work* - [mozartan](https://github.com/mozartan)

