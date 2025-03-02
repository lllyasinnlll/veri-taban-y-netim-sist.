1. Soru
Cevap) Geleneksel Dosyalama Sisteminde veri sıralı veya doğrudan erişim yöntemiyle kullanılır. Sıralı Erişim Yönteminde bilgilerin tutulduğu dosya içeriği tarama yöntemiyle okunur. İstenilen kayda gelindiğinde işlem yapar. En büyük dezavantajı istenilene anında ulaşılamamasıdır. Bu sorunun önüne geçmek için bilgiye doğrudan ulaşılabilen Doğrudan Erişimli Yöntem geliştirilmiştir. Geleneksel Dosyalama Sistemi zamanla artan veri kapasitesi, veri işleme hızı gibi ihtiyaçlara cevap veremez duruma gelmiştir. Bu yüzden fazla veri akışı olan sistemlerde veritabanı yönetim sistemleri kullanılır.
Örnek Tablo:
1)Öğrenci Tablosu
Öğrenci No       Ad-Soyad         Yaş
101              Cenk Baş         34
102              Furkan Öztürk    23
103              Yasin Kağan      27

Öğrenci No: Primary Key
Ad-Soyad: Öğrencinin adı ve soyadı
Yaş: Öğrencinin yaşı

2)Ders Tablosu       
Ders Kodu      Ders Adı       Kredi
201            Elektrik       5
202            Biyoloji       3
203            Aerodinamik    5

Ders Kodu: Primary Key
Ders Adı: Alınacak dersin adı
Kredi: Dersin kredisi

3)Not Tablosu
Not ID      Öğrenci No     Ders Kodu     Not
10          101            201           45
11          102            202           79 
12          103            203           91

Not ID: Primary Key
Öğrenci No: Foreign Key (Öğrenci Tablosu) 
Ders Kodu: Foreign Key (Ders Tablosu)
Not: Öğrencinin aldığı not.

2. Soru
Cevap) Her iki sistem de veri depolamak, ver saklamak amacıyla kullanılır.(benzerlik)
Geleneksel Sistemde veri tekrarları olurken vtys'de bu ortadan kaldırılmıştır veya en aza indirgenmiştir.
Geleneksel Sistemde aynı verinin tekrar tekrar kullanılması belleğin israfına yol açarken vtys'de tekrarlar önlendiği için israf en aza indirilir.
VTYS'de standart bir sorgu dili kullanmak mümkünken Geleneksel Sistemde standart bir dil söz konusu değildir. Yani programa göre dosyaya erişim farklılık gösterebilir.

3. Soru
Cevap) Gizlilik ve güvenlik istenilen düzeyde sağlanabilir.
Veri bütünlüğüne sahip olması verilen tutarlı olmasını sağlar.
Eş zamanlı olarak birden fazla kullanıcı verilere erişebilir ve paylaşabilir. 

4. Soru
Cevap) Veritabanları, fazla miktarda veriyi düzenli şekilde depolar ve bu verilere hızlı ve güvenli bir erişim sağlar.
İstenen veriye, istenen türde ve istenen sürede saklanmasını sağlamaktadır.
Verilerin girişini, yönetilmesini, güncellenmesini kolay hale getirir.
Gereksiz veri tekrarını engeller.
Veritabanı sistemleri otomotiv, bankacılık, sağlık ve hava sistemleri ve akademik kurumlar gibi alanlarda kullanılır. Müşteri veya kullanıcı bilgilerini depolar, Ürün miktarı, satış verileri gibi büyük boyutlu verileri saklar.

5. Soru
Cevap) Tablo: Satır ve sütunlardan oluşur, veritabanı içerisinde verilerin depolanmasına olanak sağlar. Kullanılan sisteme göre birden fazla tablo oluşturulabilir.
Satır: Genellikle "kayıt" olarak ifade edilir. Her kayıt içerisinde farklı alanlar vardır.
Sütun: Alan olarak da ifade edilir. Tablo içinde tutulan her bir veri türüne verilen isimdir. Bir tablo içerisinde birden fazla kullanılmaktadır.
-Satır ve sütunları birbirinden bağımsız düşünmek mümkün değildir.

6. Soru
Cevap) Birincil anahtar: Bir tabloda tutulan verilerden benzersiz olan sütun birincil anahtardır. Her tablonun yalnızca bir tane birincil anahtarı olur. NULL değerleri veya aynı olan değerleri içeremez.
Kayıt silme, düzeltme gibi işlemlerde büyük kolaylık sağlar.
Yabancı Anahtar: Birincil anahtarda olduğu gibi sütun yabancı anahtar olarak belirlenemez. İlişki kurulmadığı sürece kullanılamaz.Aynı tabloda veya başka bir tablodaki birincil anahtar olan sütunla ilişkilendirilebilir.
Farklılıkları: Birincil anahtar tablodaki her kaydı benzersiz şekilde tanımlar.
Yabancı anahtar ise iki tablo arasında ilişki kurmak için kullanılır.

7. Soru
Cevap) -Veritabanı Yöneticisi(DBA): Veritabanının tasarımı, performans analizi, erişim yetkilerini düzenleme, yedekleme ve geri yükleme, veri bütünlüğünü sağlama görevlerini üstlenir.
-Uygulama Geliştiriciler: Temel görevleri, veritabanlarını kullanabilecek son kullanıcıya yönelik yazılımlar geliştirmektir. Veritabanı ile etkileşimli yazılımlar yazar.
-Sorgu Dili Kullanıcıları: İhtiyaç duyulan hazırlamaktan ve işletmekten sorumludur. SQL gibi sorgu dillerini kullanırlar.
-Son Kullanıcılar: Uygulama Programcıları tarafından geliştirilen yazılımları kullanır. Bu kullanıcıların veritabanı yapısı hakkında bilgi sahibi olmasına ve üst düzey kullanıcı olmasına gerek yoktur. 

8. Soru
Cevap) -Veritabanı Yöneticisi(DBA):Tüm veritabanı üzerinde işlemler yapma yetkisine sahiptir. Tablo güncelleme,silme...
-Uygulama Geliştiriciler: Mevcut veritabanındaki yapıları değiştirme yetkisine sahiptir.
-Veri Analisti: Tablolar üzerinde analiz yapma yetkisine sahiptir.
-Veri Giriş Personeli: Mevcut verileri güncelleyebilir ve belirli tablolara veri ekleyebilir.
-Raporlama Uzmanı: Veritabanından raporlar oluşturabilir.
-Güvenlik Yöneticisi: Kullanıcı hesaplarını yönetebilir. Erişim izinlerini düzenleyebilir.
-Yedekleme Operatörü: Veritabanının yedeklenmesini ve geri yüklenmesi işlemlerini gerçekleştirir.
-Misafir Kullanıcı: Veri ekleme,silme yetkisi yoktur. Belli tablolarda sınırlı okuma yetkisine sahiptir.

9. Soru
Cevap) Veritabanı, verileri organize bir şekilde depolamak,yönetmek,saklamak ve erişmek için kullanılan araçlardır. Genellikle birbiriyle ilişkili bilgileri içerir. Kısaca verilerin depolandığı yapıdır.
VTYS ise veritabanlarını tanımlamak, kullanmak, değiştirmek ve çeşitli işlem yapmak için tasarlanmış yazılımdır. Verinin güvenliğini, bütünlüğünü sağlar. MySQL, Oracle yazılımları VTYS'dir. Kısaca verilere erişimi ve yönetimini sağlar.

10. Soru
Cevap) İlişkisel veri modeli, birbiriyle bir şekilde ilişkili olan çeşitli türdeki bilgileri depolamak için kullanılan araçlardır.Kısaca verileri depolayan ve aralarında bir bağlantı noktası sağlayan bir veri tabanıdır.

11. Soru
Cevap) 1. Tablo
-Öğrenciler: Öğrencilerin bilgilerini saklar.
Sütunlar: Öğrenci No (birincil anahtar), Bölüm adı, Fakülte
-Bölümler: Üniversitedeki bölümleri temsil eder.
Sütunlar: Bölüm Kodu(birincil anahtar), Bölüm adı, Fakülte
-Dersler: Dersleri ifade eder.
Sütunlar: Ders Kodu(birincil anahtar), Ders adı, Kredii Bölüm Kodu(Yabancı anahtar)
-Öğretmenler: Dersi veren öğretmenler.
Sütunlar: ÖğretmenID(birincil anahtar), İsim, Soyisim, Bölüm Kodu(Yabancı anahtar)
-Notders: Öğrencilerin not ve aldıkları dersleri tutar.
Sütunlar: Öğrenci No, Ders No, Not
Tablolar Arası İlişkiler
-Öğrenciler birden fazla ders alabilir ve her ders birden çok öğrenci tarafından alınabilir. (çoka çok)
-Bir bölümde birden fazla öğretmen vardır. (bire çok)
-Bir dersi bir öğretmen verebilir. (birebir)
-Bir öğrencinin birden fazla notu olabilir (bire çok)
