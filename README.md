# Api ve Api Testi

Eğitim kavram haritası mantığında kısa bilgiler vererek devam etmektedir.

# Apı Nedir?

İki uygulamanın birbiriyle iletişim kurmasına olanak sağlayan bir yazılım aracı olan **Uygulama Programlama Arayüzü**’nün kısaltılmasıdır.

# Apı Kullanım Yerleri

- Uygulama Sunucuları
- Bulut kaynakları
- Bulut Tabanlı Servisler
- Mobil Uygulamalar
- Database
- Web Uygulamaları

# Apı Kullanım Alanı Ve Amaçları

- Web ve uygulama geliştiricileri kulanır
- Farklı servislerin özelliklerinden yararlanma
- Süreçleri çabuk ve programlı bir hale getirir.

# Günlük Hayatta Apı Örnekleri

- Google geliştirici API’ları
- Google haritalar
- Analystics
- Takvim
- Youtube
- Google translate vb.
- Twitter ve facebook API’ları

# Apı Tipleri Nelerdir?

- Soap Apı
- Rest Apı

# Soap Apı

- SOAP(Basit Nesne Erişim Protokolu) temel anlamda, internet üzerinden belirli bilgileri yada mesajları aktarma protokoludur.
- HTTP
- TCP/IP
- SOAP mesajları xml formatlıdır.

# Rest Apı

- REST client-server arasında hıxlı ve kolay şekilde iletişim kurulmasını sağlayan bir servis yapısıdır.
- Servis yönetimli mimari üzerine oluşturulan yazılımlarda kullanılan bir veri transfer yöntemidir.
- HTTP üzerinde çalışır ve minimum içerikle veri alıp gönderdiğinden hazlıdır.
- Genellikle XML veya JSON verileri ile uygulamalar arası iletişimi sağlar.

# Web Servis Kavramı

- Web servis iki makinenin bir ağ üzerinden birbiri ile iletişim kurmak için kulandığı bir yöntemdir.
- Web servislerine sadece ağ üzerinden erişilebilir.
- Web servisler internet üzerinden haberleşirler.
- Web servisler kullanılırken HTTP metotlarına başvurur.

# Web Servis Kullanım Şekilleri

- Sürekli uygulama üzerinde yapılan işler
- Farklı uygulamalar ile veri alışverişi

# Web Servis Kullanılan Standartlar

- SOAP
- UDDI
- WSDL

# Apı ve Web Servis İlişkisi

- API
    - Her api web servis değildir.
    - Tüm API’lar internet üzerinden erişilemeyebilir.
- Web Servis
    - Her web servis bir Api dir.
    - Web servisleine her zaman ağ üzerinden erişilebilir.
    
# Soap Servis Nedir?

- HTTP ve TCP protokol kullanımı.
- Sadece XML verileri ile işlem yapabilirsiniz.
- Soap Mesaj Bölümleri
    1. Envelope
    2. Header
    3. Body
    4. Fault
    
# WSDL Kavramı

- Web servicez description language
- Elementler
    - Types
    - Message
    - PortType
    - Binding
    - Port
    - Service
    
# Rest

- Representational state transfer temsili duum transferi
- Http durum kodları   url

# Restful Servis Gereksinimleri

- Uniform interface
- Clinet-server
- Casheable
- Stateless
- Layered system
- Code on demand

# Rest Servis http Metodları

- Get
- Post
- Put
- Patch
- Delete
- Options

# Rest Servis http Sonuç Durum Kodları

- HTTP Status Code

# Sopa Ve Rest Arasındaki Farklar

1. Güvenlik
2. Format
3. Boyut ve hız
4. Ön bellek
5. Tasarım
6. Kullanım

# API Testi

- Uygulamalar arasında veri alışverinini test edilmesi ve işlemlerin verimliliğinin gözlemlenmesi.
- Yazılıma test ekipleri tarafından kapsamlı testler yapılır.
- Önem derecesi yüksek seviyede yapılan işlerdir.

# Neden API Testi?

- İşlevsellik
- Performans
- Güvenilirlik
- Güvenlik
- Kullanılabilirlik

# API Testinin Önemi

## Etkileri

> İşlevselliği doğrulamak
> 

> Sınır değer analizi yapılması
> 

> Hatalar(bug) bulmak
> 

> Kalitenin artırılması


## API Testinin Avantajları Ve Zorlukları

- Giriş parametreleri
- Beklenen sonuç çıktısı
- Cevap almak için harcanan süre
- İstek mesajları ayrıştırılması
- Hata yönetimi
- Dönen cevabı formatlama

# API Testini Faydaları

- Cevaplar ve veriler doğrulanır
- Kontrollü yönetilebilir
- Hata tespiti kolaylığı
- Kısa sürede tamamlanabilir.
- Kısa zamanda daha fazla hata bulunur ve kalite arttırılır.

# API Testinin Zorlukları

- İş uygulama mantığı bilgisi
- Karmaşık protokoller
- Kodsal değişikliği etkisi
- Test veri yönetimi
- Teknik bilgileri içeren envanter takibi

# API Testi Otomasyonu

- Önceden tahmin edilen sonuçlara gerçek sonuçların kıyaslanması ile test koşumlarının kontrol edilmesinin sağlanması.
- Manuel bir müdahale gerekmeden testlerin hızlı kosulması sağlanır.

# API Testi Test Otomasyon
- Önce başarılı case senaryoları
- Hızlı olduğundan emin olmak
- Süreklilik
- Bağımlılık azaltılmalı
- Tutarlı olması
- Gereksinim değişikleri

# API Testi Otomasyon Kazançları

1. Zaman maliyeti
2. İş yükü
3. Bakım
4. Verimlilik

# API Testi Tipleri

1. ntegrasyon testi
2. Yük testi
3. Regresyon testi
4. Güvenlik testi
5. Kullanıcı arayüz testi
6. Fonksiyonel test
7. Stres testi

# Entegrasyon Testi

Birbirinden bağımsız olarak tes edilmil olan iki yazılım ürünün birbirine bağlanması, birbiri arasına veri aktarımının sağlanması için birleştirilen mödüllerin test edilmesidir.

# Yük Testi

Belirlenen ölcüler doğrultusunda sisteme uygulanan yük altında sistem içerisinde ortaya çıkabilecek darboğazları ortaya çıkarmak için yapılan testtir.

# Regresyon Testi

Yapılan kodsal değişiklikler sonucunda sistemde değişiklik yapılan ve değişiklik yapılmayan alanlarda varsa yeni hataları bulmak için yapılan test çeşididir.

# Kullanıcı Arayüz Testi

API’ları da kapsayan uçtan uca entegrasyon testlerinin bir parçası olarak gerçekleştirilen daha büyük işlem ekransal GUI öğelerinin doğrulamasına olanak tanır.

# Güvenlik Testi

bilişim sistemlerindeki mantık hataları ve zafiyerleri tespit ederek, söz konusu güvenlik açıklıklarının kötü niyetli kişiler tarafından isitismar edilmesini önlemek ve sistemleri daha güvenli hale getirmek amacıyla yapılan testtir.

# Fonksiyonel Test

- Sistemin veya yazılımın özelliklerini ve işlevselliğini test etmek için kullanılan tekniktir.
- Fonksiyonel testlerde temel olarak bileşen veya sistem fonksiyonlarının testleri yapılır.
- 
# Stres Testi

- Belirli bir sistemin, kritik bir alyapının veya varlığının, kararlığını belirlemek için kullanılar kısıtlı olarak yoğun veya kapsamlı bir test şeklidir.
- Sonuçları gözlemek için normal çalışma kapasitesinin ötesinde, genellikle bir kırılma noktasına kadar test yapılmasını içerir.

# API Test Araçları

1. SoapUI
2. Rostman
3. Katalon studio
4. Rest-Assured
5. Karate DSL

# SOAP UI Test Araçları

- Genel olarak web servisleri kontrol etmek, herhangi bir web servisi çağırmak, web servisi sanallaştırmak ya da fonksiyonel test yapmak için kullanılır.
- Özellikle web servis entegrasyon fazlasıyşa işe yarayan bir yapıya sahiptir.
1. JMS
2. SOAP-WSDL
3. REST
4. HTTPS-HTTP
5. AMF
6. JDBC

# yazar:
  
  **Ömer Kılıç**
 
#  Yayınlanma Tarihi:
  
  **24.02.2023**
  
#  Yazar İletişim/Bilgi/Özgeçmiş:
  
  **http://omerkilic.rf.gd/**
