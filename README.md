# python-notlar

| Bilgi | Açıklama |
| --- | --- |
| type() : | Öğenin tipini denetlemeyi sağlar |
| len() : | Öğenin uzunluğunu döndürür |
| pow() : | İlk parametre asıl sayıyı, ikincisi alınmak istenen üssü belirtir |
| _ : | Shell içinde son kullanılan öğenin yerini alır |
| import keyword;keyword.kwlist : | Python içindeki tüm özel ifadeler |
| sep : | print() içinde virgüller arasına koyulacak ifadeyi belirler |
| end : | print() içinde en sona yazılacak ifadeyi belirler |
| file : | print() içinde yazılan ifadenin nereye çıktı verileceğini belirtir |
| import os;os.getcwd() : | O anki dosya konumunu gösterir |
| flush : | print() içine verilen girdileri tamponda tutan parametre, True verirsek girdi direkt belgeye yansır |
| print* : | print() içindeki kelime dizisinin her bir öğesini parçalara ayırarak teker teker print()'e gönderir |
| import sys;sys.exit() : | Shellden çıkmayı sağlar |
| import <modül_adı> : | Modülleri mevcut program içine aktarır |
| import sys;sys.stdout = <dosya_referansı> : | print() çıktılarımızı teker teker file içinde belirtmeden belli bir dosyaya yazdırmayı sağlar |
| \" : | String içinde çift tırnak kullanımını sağlar |
| \\ : | String içinde kaçış karakterlerinden kurtulmamızı sağlar |
| \r : | Aynı satırın başına döner |
| \v : | Düşey sekme oluşturur |
| r : | String içinde kaçış karakterlerini yoksayar, kullanımı r"String ifade" |
| input() : | Karşı taraftan veri almayı sağlar, alınan değer string tanımlanır |
| int() : | Sayı değerli bir karakter dizisini veya float değeri tamsayıya çevirir |
| float() : | Sayı değerli bir karakter dizisini veya integer değeri floata çevirir |
| str() : | Bir tamsayı ya da floatı String'e çevirir |
| complex() : | Herhangi bir sayıyı veya sayı değerli bir karakter dizisini karmaşık sayıya çevirir |
| eval() : | İçine karakter dizisi olarak girilen python komutlarını çalıştırır |
| format() : | Karakter dizilerine eklenilmesi gereken verileri dışarıdan eklememizi sağlar |
| ½ : | Modülüs ifadesi kısaca mod almaya yarar |
| // : | Taban bölme işareti , kalanı tamsayı olarak gösterir |
| round() : | Sayı yuvarlamamızı sağlar, ilk parametre yuvarlanacak sayı, ikincisi yuvarlama hassasiyetini belirler |
| bool() : | İçindeki verinin True ya da False karşılığını gösterir (0 ve "" ifadeleri False geri kalan True değerlendirilir) |
| in : | Aitlik işlecidir |
| id() : | İçine verilen öğenin bellek içerisindeki öğeye ait id numarasını verir |
| is : | İki veriyi id numaralarına göre karşılaştırır |
| == : | İki veriyi içeriğine göre karşılaştırır |
| import sys;sys.version_info : | Bilgisayardaki python versiyonu hakkında bilgi verir |
| range() : | Belli bir aralıkta sayı listelemizi sağlar, direkt yazdırılamaz |
| pass : | Döngü ve fonksiyon içerisini işlem yapmadan geçmemizi sağlar |
| break : | Döngüyü koşulsuz sonlandırır |
| continue : | Koşulsuz döngünün başına geçer |
| raise : | Hata fırlatmayı sağlar, kullanımı raise TypeError("Hata metni"), ayrıca expect bloğu içerisine raise ekleyerek normal hata mesajına kendimiz birşeyler ekleyebiliriz |
| reversed() : | Karakter dizisini ters çevirir ancak direkt kullanılmaz |
| sorted() : | İçine verilen öğeyi alfabetik veya numerik sıralar |
| dir() : | İçine verilen veri tipine ait tüm metotları gösteir |
| enumerate() : | İçine verilen veriyi parçalara ayırarak her birini numaralandırır , ikinci parametresine numaralandırmanın hangi sayıdan başlayacağını belirtebiliriz |
| help() : | İçine verilen metot, fonksiyon veya obje hakkında bilgi verir |
| replace() : | String içindeki bir karakteri değiştirmeyi sağlar |
| split() : | String içinde belli ölçütlere göre bölme yapmayı sağlar |
| rsplit() : | split() işleminin sağa göre işleyeni |
| splitlines() : | Metin içindeki her bir satırı bölmemizi sağlar |
| lower() : | Metin içindeki tüm harfleri küçültür |
| upper() : | Metin içindeki tüm harfleri büyültür, ancak iki metot türkçe karakterlerde sorun yaşar |
| isupper() : | String içerisindeki tüm harfler büyük ise True döner, değilse False döner |
| islower() : | String içerisindeki tüm harfler küçük ise True döner, değilse False döner |
| endswith() : | String'in metot içerisinde belirtilen String ile bitip bitmediğini sorgular |
| startswith() : | String'in metot içerisinde belirtilen String ile başlayıp başlamadığını sorgular |
| capitalize() : | String'in sadece ilk harfini büyük yapar |
| title() : | String içindeki kelimelerin ilk harflerini büyük yapar |
| swapcase() : | String içindek büyük harfleri küçük yaparken küçükleri de büyük hale getirir |
| casefold() : | lower() metotuyla aynı işlevi görür |
| strip() : | String'in başında ve sonunda istenmeyen karakterleri temizler |
| lstrip() : | String'in başındaki istenmeyen karakterleri siler |
| rstrip() : | String'in sonundaki istenmeyen karakterleri siler |
| join() : | Liste veri tipini String'e çevirir, kullanımı "".join(<liste>) |
| count() : | Bir String içerisinde belli bir karakterin kaç kere geçtiğini gösterir |
| index() : | String içinde aradığımız karakterin index numarasını döner, karakter yoksa ValueError verir |
| rindex() : | index() metotunun yaptığını sağdan sola olacak şekilde yapar |
| find() : | String içerisinde aranan karakterin index numarasını döner, kelime bulunamazsa -1 döner |
| rfind() : | find() metotunun yaptığını sağdan sola index alacak şekilde döner |
| center() : | İçerisine verilen parametre Stringin karakter sayısını aştığı zaman o karakteri ortalamaya yarar |
| ljust() : | String'i sola hizalar, parametre String'in karakter sayısından uzun olmalı |
| rjust() : | String'i sağa hizalar, parametre String'in karakter sayısından uzun olmalı |
| zfill() : | String'lerin soluna istediğimiz ölçütte 0 yerleştirmemizi sağlar |
| partition() : | Bu metot ile String'leri belli bir ölçüte göre üçe bölebiliriz |
| rpartition() : | partition() metotunun sağdan sola referans alarak işlenen hali |
| encode() : | Bu metot ile Stringleri istediğimiz kodlama sistemine göre kodlayabiliriz |
| expandtabs() : | Bu metot ile String içerisindeki tab boşluklarını genişletebiliriz |
| str.maketrans();translate() : | İkisi de String içerisinde istediğimiz karakterleri başka karakterler ile değiştirmemizi sağlar, kullanımı <çeviri_tablosu> = str.maketrans(<kaynak>,<hedef>) |
| isalpha() : | String'in sadece alfabetik karakterlerden oluşup oluşmadığını kontrol eder |
| isdigit() : | String'in sadece rakamlı karakterlerden oluşup oluşmadığını kontrol eder  |
| isalnum() : | String'in hem alfabetik hem rakamlı karakterlerden oluşup oluşmadığını kontrol eder |
| isdecimal() : | String içerisindeki sayının ondalık olup olmadığına bakar |
| isidentifier() : | String içerisindeki ifadenin tanımlayıcı olup olamayacağını kontrol eder |
| isnumeric() : | String'in nümerik tipten oluşup oluşmadığını kontrol eder |
| isspace() : | String'in sadece boşluktan oluşup oluşmadığını kontrol eder |
| isprintable() : | String'in basılabilir bir değer olup olmadığına bakar, örn. sadece kaçış karakterlerinden oluşan bir String printable değildir |
| "{:>15}".format("") : | Format metotu ile sağa hizalama yapmayı sağlar |
| "{:<15}".format("") : | Format metotu ile sola hizalama yapmayı sağlar |
| "{:^15}".format("") : | Format metotu ile ortaya hizalama yapar |
| "{:.2f}".format(50) : | Format metotu ile virgülden sonra koymak istediğimiz rakam sayısını belirleriz |
|  print(*liste) : | Liste görünümü dışında tüm öğeler sırayla gösterilir |
| append() : | Metot içine verilen öğeyi listenin sonuna ekler |
| extend() : | Metot içine verilen öğeyi listenin sonuna ekler, append() ile benzer ancak birden çok eleman ekleyebiliyor |
| insert() : | Belirli bir index'e öğe yerleştirebilmemizi sağlar, ilk parametre index ikincisi öğe olacak şekilde |
| remove() : | Listeden belirli bir elemanı silmeye yarar |
| pop() : | Listeden öğe silmeye yarar, silinen öğeyi ekrana basar, parametresiz çağrılırsa listenin sonundaki elemanı siler |
| sort() : | Liste içinde alfabetik ve numerik sıralama yapar |
| sort(reversed=True) : | Liste içinde tersten alfabetik ya da numerik sıralama yapar |
| index() : | İçine verilen öğenin liste içerisindeki index numarasını döner |
| count() : | İçine verilen veri tipinin listede kaç kere geçtiğini gösterir |
| copy() : | Bir listenin elemanlarını başka bir listeye kopyalamayı sağlar |
| clear() : | Listenin içini boşaltır ancak ortadan kaldırmaz, del <liste> şeklinde listeyi programdan kalıcı silebiliriz |
| bin() : | İçerisine verilen sayının ikilik sayma sistemindeki karşılığını verir, başındaki 0b o sayının ikilik sistemde olduğunu belirtir |
| hex() : | İçine verilen sayının onaltılık sayma sistemindeki karşılığını verir, başındaki 0x onun onaltılık sistemde olduğunu belirtir |
| oct() : | İçindeki sayıyı sekizli sistemde gösterir başında 0o vardır |
| int(<sayı>,<sayı_sistemi> | İkinci parametrede belirtilen sayı sisteminde olan sayıyı onluk tabana dönüştürür |
| <sayı>.bitlength() : | İçine verilen integer sayının kaç bit olduğunu gösterir |
| <float>.as_integer_radio() : | BU metot birbirine bölündüğünde yazılan float değeri veren iki tam sayı döner |
| <float>.is_integer() : | Verilen float değerin ondalık kısmında 0 harici bir sayı olup olmadığını kontrol etmemizi sağlar |
| <complex>.imag : | Karmaşık sayının sanal kısmını verir |
| <complex>.real : | Karmaşık sayının gerçek kısmını verir |
| abs() : | İçine verilen sayının mutlak değerini verir |
| divmod() : | Bir sayının diğer sayıya bölünmesi sonucu oluşan bölümü ve kalanı gösterir |
| max() : | İçine verilen sayılardan en büyüğünü verir |
| max(<str_list> , key= len) | String'lerden oluşan listenin en uzun elemanını verir |
| min() : | İçine verilen değerlerden en küçüğünü verir |
| sum() : | Bir dizi içinde yer alan tüm sayıları toplamaya yarar |








