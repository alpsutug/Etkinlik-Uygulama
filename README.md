# Etkinlik-Uygulama
Etkinlik Uygulaması (Kullanıcı Giriş,Admin Panel,Sepete Ekle)
Öncelikle bu projede etkinlik uygulaması yapmayı amaçladım. Anasayfamda bulunan navbar menümde Etkinlik Uygulaması kısmı ana sayfamı temsil ediyor.
Hemen Yanında bulunan Etkinlikler kısmında ise yine ana sayfamda bulunan etkinliklere ait bir sayfa bulunmakta. Admin Paneli sadece admin girişi 
yapıldığında geliyor. Ve hakkımızda kısmında ise Bize Ulaşın, Kurum Politikası, Sosyal Hesaplar gibi kısımlar mevcut. Giriş yapmadan sepete gitmeye çalışırsak
giriş sayfasına yönlendiriliyoruz. Giriş yaptıktan sonra etkinlik seçtikten sonra direkt sepete git butonuna basarsak hata alıyoruz çünkü öncelikle
Etkinlik için koltk seçimi yapılmalı. Koltuk seçimi yapıldıktan sonra en altta haritadan etkinlik yeri de görülebilir. Sonrasında septe git diyoruz.
Gelen sayfada hangi etkinliği satın alıyor olduğumuzu ve bilgilerini görüyoruz. Aslında bu projeyi düşünürken bir alışveriş sitesi gibi düşündüm çünkü
sepete ekle ve koltuk seçme kısmı beni bu tasarıma itti. Admin panelinde ise kullanıcı, kategori ekleme ve daha bir çok özellik bulunmakta. Projeye erişmek için
Microsoft SQL Server'in bilgisayarımızda kurulu olması lazım. Databaseden tablo oluşturmak yerine tüm bağlantılarım kodların içerisinde.
Sadece Microsoft SQL Server Managament Studio'yu açıp içerisinde shopappDb isminde bir veri tabanı oluşturmak ve daha sonrasında appsettings.json dosyalarındaki server name ve
database name (shopappDb) kısımlarını kendinize göre düzenlemek projeyi çalıştırmak için yeterli olacaktır.
Ayrıca mail doğrulama işlemleri için https://www.brevo.com , hakkımıda sayfasındaki mesaj gönderme işlemleri için https://formspree.io ve son olarak 
harita eklemek için ise https://www.google.com/maps/d/u/0/ adreslerini kullanabilirsiniz. 
