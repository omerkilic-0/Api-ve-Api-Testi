# Api ve Api Testi

Eğitim kavram haritası mantığında kısa bilgiler vererek devam etmektedir.

# 1. Apı Nedir?

İki uygulamanın birbiriyle iletişim kurmasına olanak sağlayan bir yazılım aracı olan **Uygulama Programlama Arayüzü**’nün kısaltılmasıdır.

# 2. Apı Kullanım Yerleri

- Uygulama Sunucuları
- Bulut kaynakları
- Bulut Tabanlı Servisler
- Mobil Uygulamalar
- Database
- Web Uygulamaları

# 3. Apı Kullanım Alanı Ve Amaçları

- Web ve uygulama geliştiricileri kulanır
- Farklı servislerin özelliklerinden yararlanma
- Süreçleri çabuk ve programlı bir hale getirir.

# 4. Günlük Hayatta Apı Örnekleri

- Google geliştirici API’ları
- Google haritalar
- Analystics
- Takvim
- Youtube
- Google translate vb.
- Twitter ve facebook API’ları

# 5. Apı Tipleri Nelerdir?

- Soap Apı
- Rest Apı

# 6. Soap Apı

- SOAP(Basit Nesne Erişim Protokolu) temel anlamda, internet üzerinden belirli bilgileri yada mesajları aktarma protokoludur.
- HTTP
- TCP/IP
- SOAP mesajları xml formatlıdır.

# 7. Rest Apı

- REST client-server arasında hıxlı ve kolay şekilde iletişim kurulmasını sağlayan bir servis yapısıdır.
- Servis yönetimli mimari üzerine oluşturulan yazılımlarda kullanılan bir veri transfer yöntemidir.
- HTTP üzerinde çalışır ve minimum içerikle veri alıp gönderdiğinden hazlıdır.
- Genellikle XML veya JSON verileri ile uygulamalar arası iletişimi sağlar.

# 8. Web Servis Kavramı

- Web servis iki makinenin bir ağ üzerinden birbiri ile iletişim kurmak için kulandığı bir yöntemdir.
- Web servislerine sadece ağ üzerinden erişilebilir.
- Web servisler internet üzerinden haberleşirler.
- Web servisler kullanılırken HTTP metotlarına başvurur.

# 9. Web Servis Kullanım Şekilleri

- Sürekli uygulama üzerinde yapılan işler
- Farklı uygulamalar ile veri alışverişi

# 10. Web Servis Kullanılan Standartlar

- SOAP
- UDDI
- WSDL

# 11. Apı ve Web Servis İlişkisi

- API
    - Her api web servis değildir.
    - Tüm API’lar internet üzerinden erişilemeyebilir.
- Web Servis
    - Her web servis bir Api dir.
    - Web servisleine her zaman ağ üzerinden erişilebilir.
    
# 12. Soap Servis Nedir?

- HTTP ve TCP protokol kullanımı.
- Sadece XML verileri ile işlem yapabilirsiniz.
- Soap Mesaj Bölümleri
    1. Envelope
    2. Header
    3. Body
    4. Fault
    
# 13. WSDL Kavramı

- Web servicez description language
- Elementler
    - Types
    - Message
    - PortType
    - Binding
    - Port
    - Service
    
# 14. Rest

- Representational state transfer temsili duum transferi
- Http durum kodları   url

# 15. Restful Servis Gereksinimleri

- Uniform interface
- Clinet-server
- Casheable
- Stateless
- Layered system
- Code on demand

# 16. Rest Servis http Metodları

- Get
- Post
- Put
- Patch
- Delete
- Options

# 17. Rest Servis http Sonuç Durum Kodları

- HTTP Status Code

# 18. Sopa Ve Rest Arasındaki Farklar

1. Güvenlik
2. Format
3. Boyut ve hız
4. Ön bellek
5. Tasarım
6. Kullanım

# 19. API Testi

- Uygulamalar arasında veri alışverinini test edilmesi ve işlemlerin verimliliğinin gözlemlenmesi.
- Yazılıma test ekipleri tarafından kapsamlı testler yapılır.
- Önem derecesi yüksek seviyede yapılan işlerdir.

# 20. eden API Testi?

- İşlevsellik
- Performans
- Güvenilirlik
- Güvenlik
- Kullanılabilirlik

# 21. API Testinin Önemi

## 21.1 Etkileri

> İşlevselliği doğrulamak
> 

> Sınır değer analizi yapılması
> 

> Hatalar(bug) bulmak
> 

> Kalitenin artırılması


## 21.2 API Testinin Avantajları Ve Zorlukları

- Giriş parametreleri
- Beklenen sonuç çıktısı
- Cevap almak için harcanan süre
- İstek mesajları ayrıştırılması
- Hata yönetimi
- Dönen cevabı formatlama

# 22. API Testini Faydaları

- Cevaplar ve veriler doğrulanır
- Kontrollü yönetilebilir
- Hata tespiti kolaylığı
- Kısa sürede tamamlanabilir.
- Kısa zamanda daha fazla hata bulunur ve kalite arttırılır.

# 23. API Testinin Zorlukları

- İş uygulama mantığı bilgisi
- Karmaşık protokoller
- Kodsal değişikliği etkisi
- Test veri yönetimi
- Teknik bilgileri içeren envanter takibi

# 24. API Testi Otomasyonu

- Önceden tahmin edilen sonuçlara gerçek sonuçların kıyaslanması ile test koşumlarının kontrol edilmesinin sağlanması.
- Manuel bir müdahale gerekmeden testlerin hızlı kosulması sağlanır.

# 25. API Testi Test Otomasyon
- Önce başarılı case senaryoları
- Hızlı olduğundan emin olmak
- Süreklilik
- Bağımlılık azaltılmalı
- Tutarlı olması
- Gereksinim değişikleri

# 26. API Testi Otomasyon Kazançları

1. Zaman maliyeti
2. İş yükü
3. Bakım
4. Verimlilik

# 27. API Testi Tipleri

1. ntegrasyon testi
2. Yük testi
3. Regresyon testi
4. Güvenlik testi
5. Kullanıcı arayüz testi
6. Fonksiyonel test
7. Stres testi

# 28. Entegrasyon Testi

Birbirinden bağımsız olarak tes edilmil olan iki yazılım ürünün birbirine bağlanması, birbiri arasına veri aktarımının sağlanması için birleştirilen mödüllerin test edilmesidir.

# 29. Yük Testi

Belirlenen ölcüler doğrultusunda sisteme uygulanan yük altında sistem içerisinde ortaya çıkabilecek darboğazları ortaya çıkarmak için yapılan testtir.

# 30. Regresyon Testi

Yapılan kodsal değişiklikler sonucunda sistemde değişiklik yapılan ve değişiklik yapılmayan alanlarda varsa yeni hataları bulmak için yapılan test çeşididir.

# 31. Kullanıcı Arayüz Testi

API’ları da kapsayan uçtan uca entegrasyon testlerinin bir parçası olarak gerçekleştirilen daha büyük işlem ekransal GUI öğelerinin doğrulamasına olanak tanır.

# 32. Güvenlik Testi

bilişim sistemlerindeki mantık hataları ve zafiyerleri tespit ederek, söz konusu güvenlik açıklıklarının kötü niyetli kişiler tarafından isitismar edilmesini önlemek ve sistemleri daha güvenli hale getirmek amacıyla yapılan testtir.

# 33. Fonksiyonel Test

- Sistemin veya yazılımın özelliklerini ve işlevselliğini test etmek için kullanılan tekniktir.
- Fonksiyonel testlerde temel olarak bileşen veya sistem fonksiyonlarının testleri yapılır.
- 
# 34. Stres Testi

- Belirli bir sistemin, kritik bir alyapının veya varlığının, kararlığını belirlemek için kullanılar kısıtlı olarak yoğun veya kapsamlı bir test şeklidir.
- Sonuçları gözlemek için normal çalışma kapasitesinin ötesinde, genellikle bir kırılma noktasına kadar test yapılmasını içerir.

# 35. API Test Araçları

1. SoapUI
2. Rostman
3. Katalon studio
4. Rest-Assured
5. Karate DSL

# 36. SOAP UI Test Araçları

- Genel olarak web servisleri kontrol etmek, herhangi bir web servisi çağırmak, web servisi sanallaştırmak ya da fonksiyonel test yapmak için kullanılır.
- Özellikle web servis entegrasyon fazlasıyşa işe yarayan bir yapıya sahiptir.
1. JMS
2. SOAP-WSDL
3. REST
4. HTTPS-HTTP
5. AMF
6. JDBC

# 37. yazar:
  
  **Ömer Kılıç**
 
#  38. Yayınlanma Tarihi:
  
  **24.02.2023**
  
#  39. Yazar İletişim/Bilgi/Özgeçmiş:
  
  **http://omerkilic.rf.gd/**
