# php-garden
PHP ve MySQL ile geliştirilmiş e-ticaret yönetim sistemi
# Bahçe Dünyası - PHP E-Ticaret Yönetim Sistemi
Bu proje, bir bahçe marketinin ürünlerini sergileyebileceği, kullanıcıların üye olup alışveriş yapabileceği ve bir yöneticinin tüm sistemi kontrol edebileceği kapsamlı bir Native PHP web uygulamasıdır.
# Öne Çıkan Özellikler

Dinamik Ürün ve Kategori Yönetimi: Ürünler, veritabanından çekilen kategorilere göre (Mobilya, Aydınlatma, Alet Edevat vb.) dinamik olarak listelenir.


Gelişmiş Sepet Sistemi: PHP Session (Oturum) yapısı kullanılarak, veritabanına yük bindirmeden hızlı ve akıcı bir sepet deneyimi sunulmuştur.


Kullanıcı Yetkilendirme: Üye kayıt, giriş ve çıkış sistemleri ile kullanıcı bazlı oturum yönetimi sağlanmıştır.


Yönetim (Admin) Paneli: Sadece yetkili kullanıcıların erişebildiği, ürün ekleme ve resim yükleme fonksiyonlarını içeren özel bir kontrol paneli mevcuttur.
# Kullanılan Teknolojiler

Dil: PHP (Procedural/Native) 


Veritabanı: MySQL 


Arayüz: HTML5, CSS3 


Sunucu: Apache (XAMPP/WAMP ortamına uyumlu)
# Proje Yapısı

baglan.php: MySQL veritabanı ile güvenli bağlantı kurar.


index.php: En yeni ürünlerin sergilendiği ana vitrin.


sepet.php: Kullanıcının eklediği ürünleri gördüğü ve toplam tutarın hesaplandığı alan.

admin/: Sitenin yönetim merkezi; ürün stok ve içerik yönetimini sağlar.


bahce_db.sql: Projenin çalışması için gerekli olan tüm tablo yapılarını ve örnek verileri içeren veritabanı şeması.
# Kurulum ve Çalıştırma
Proje dosyalarını yerel sunucunuzun (XAMPP/htdocs vb.) içine kopyalayın.


bahce_db.sql dosyasını PhpMyAdmin üzerinden içe aktarın (Import edin).


baglan.php dosyasındaki veritabanı kullanıcı adı ve şifre bilgilerini kendi ayarlarınıza göre güncelleyin.

Tarayıcınızdan localhost/php-bahce adresine giderek projeyi test edin.
# Geliştirici Notu
Bu projeyi geliştirirken veritabanı ilişkileri, oturum yönetimi ve dinamik içerik üretimi konularında pratik deneyim kazandım. Kod yapısını sade ve anlaşılır tutarak sürdürülebilir bir uygulama hedefledim.
