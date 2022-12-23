# Kotlin ve Java ile Android Programlama

## Kotlin Programlama Dili (Java, C# ve C++ programcıları için)
    Temel türler ve değişken tanımlama
    var ve val değişkenker
    string template
    Sabitler
    Fonksiyon bildirimi çağrılması
        + Default ve isimli argümanlar
        + Tek ifadeli fonksiyonlar
        + Global fonksiyomnlar
        + Yerel fonksiyonlar
    Operatörler ve karşılık gelen fonksiyonlar (operator functions)
    Kontrol deyimleri: if ifadesel deyimi, while döngü deyimi, do-while döngü deyimi, for döngü deyimi, break ve continue deyimleri, when ifadesel deyimi
    + Tür dönüşümleri
    + Sınıflar
        + Başlangıç metotları (primary ve secondary constructors)
        + init bloğu
        + Sınıfın property elemanları
        + Sınıflarkn operatör fonksiyonları
    + Örnek sınıfların kullanımı: Random ve String sınıfları
    + Temel türlerin çeşitli metotları
    + Paketler
    + import bildirimleri
    + Diziler
    + Erişim belirleyiiciler:
        + Global düzeyde erişim belirleyiciler: public, internal, private
        + Sınıf elemanlarının erişim belirleyicileri: public, internal, protected, private
    + enum sınıfları
    + Sınıflararası ilişkiler: composition, aggregatiıon, association, inheritance
    + Türetme (inheritance)
    + upcasting ve downcasting
    + Any sınıfı
    + Çok biçimlilik (polymprhisim)
    + Sanal metotlar ve override işlemi
    + Abstract sınıflar, abstract metotlar ve abstract property elemanları
    + data sınıflar (data classses)
    + component metotları ve
    + null atanabilir türler (nullable types)
    + Akıllı dönüşümler (smart casting)
    + Özel operatörler: ?., !!, as?, is, !is
    + Exception işlemleri
    + Eklenti fonksiyonlar (extension functions)
    + infix fonksiyonlar
    + Arayüzler (interfaces)
    + Generic sınıflar ve metotlar
    + Yararlı generic sınıflar
    + nested classes
    + inner classes
    + Anonim nesneler
    + object bildirimi ve companion objects
    + type aliases
    + Fonksiyon türleri
    + Lambda fonksiyonlar
    + Sınıfların üye fonksiyonların fonksiyon türlerine verilmesi
    + Fonksiyon parametreli foknsiyonlar
    + let, also, run, with ve apply fonksiyonları
    + Collection sınıflar

## Android programlamaya giriş
    + Android işletim sistemi ve sürümler
    + Android işletim sistemine ilişkin genel bilgiler
    + Android programlamada kullanılan temel araçlar: Android SDK, Android NDK, Android Studio

## Android Studio IDE programı ve Android SDK'nın kurulumu ve kullanımı
    + Android SDK kurulumu
    + Android Studio kurulumu
    + Android studio proje seçenekleri
    + Android projelerinin bileşenleri

## Emülatör kurulumu ve kullanımı
    + Android Virtual Device (AVD)
    + Android emülatör konfigürasyonu
    + Android uygulamasının emülatör ile çalıştırılması

## Context kavramı
    + Context ve ContextWrapper sınıfları
    + Application Context
    + Base context
    + Diğer context çeşitleri

## Activity ve Intent kavramları
    + Activity kavramı ve Activity sınıfı
    + Activity yaşam döngüsü (life cycle) ve yaşam döngüsüne ilişkin metotlar
    + Intent sınıfı
    + Bir activity'nin başlatılması (launch)
    + Bundle sınıf
    + Activity'ler arası haberleşme
        + Başlatan  activity'den başlatılan activity'ye veri aktarılması
        + Başlatılan activity'den başlatan activity'ye veri aktarılması
    + Örnek uygulamalar

## Temel Kullanıcı arayüzü bileşenleri (Views, Menu'ler, Layoutlar)
    + View ve ViewGroup sınıfları
    + Layout sınıfları
    + Menu işlemleri
    + Temel Adapter sınıfları
    + Temel AdapterView'lar (ListBox, Spinner vb.)
    + Custom adapter view'lar
    + Databinding
    + Viewbinding
    + Örnek Uygulamalar

## Reaktif programlama ve RxJava
    + Reaktif programlama
    + RxJava hakkında temel bilgiler
    + Android üzerinde RxJava (RxAndroid)
    + Kotlin ile RxJava kullanımı
    + RxBinding kullanımı
    + RxJava'nın detaylı incelenmesi
    + Örnek uygulamalar

## Kütüphane kullanımı: aar (android archive) ve jar (java archive) dosyaları
    + jar ve aar dosyaları
    + jar ve aar dosyalarının proje içerisinde kullanımı
    + Github üzerinde maven remote repository oluşturma ve kullanma
    + Örnek Uygulamalar

## Gradle aracı
    + Gradle kullanımı
    + Gradle direktiflerinin anlamları
    + gradle dosyalarının anlamı
    + dependencies.gradle dosyası
    + Versiyonlama
    + Proguard kullanımı

## Android kütüphane oluşturma
    + Module kavramı
    + Android modüller
    + jar modül oluşturma
    + aar modül oluşturma
    + Kütüphane dosyalarının kütüphane dosyalarını kullanması
    + Örnek uygulamalar

## Uygulamada kullanılan kalıplar (patterns)
    + Service Locator ve Singleton kalıpları
    + Dependency Injection kavramı ve kullanılan kütüphaneler
        + Dagger kütüphanesi
        + Hilt kütüphanesi
    + Örnek uygulamalar 

## Katmanlı Mimari uygulamaları
    + Katmanlı mimarı kullanarak proje geliştirme avantajları
    + Repository, service ve application katmanları
    + Katmanlı mimari kullanarak proje geliştirmede exception'ların yönetilmesi
    + Örnek uygulamalar

## Dosya sistemi ve dosya işlemleri
    + Android dosya sistemi
    + Internal ve external memory
    + Dosyanın bütünü üzerinde işlem yapan sınıflar
    + Dosyanın verileri üzerinde işlem yapan sınıflar
    + Internal memory üzerinde dosya işlemleri
        + files dizininde dosyalar
        + cache dizininde dosyalar
        + shared preferences
        + preferences
    + Serialization
    + Ham kaynaktaki (raw resource) dosyaya erişim
    + Projenin assets dizinindeki dosyalara erişim
    + External memory üzerinde dosya işlemleri
    + FileProvider ile uygulamalar arası dosya paylaşımı
    + Örnek uygulamalar

## Asenkron işlemler ve Çoklu thread (Multithreading) uygulamarı
    + Process kavramı
    + Asenkron programlama hakkında temel bilgiler
    + Çizelgeleme algoritmaları (scheduling algorithms)
    + Thread kavramı
        + Thread sınıfı ve Runnable arayüzü
        + Executor'lar ve thread havuzları
    + Looper sınıfı
    + Handler sınıfı
    + AsyncTask sınıfı
    + Kotlin coroutines
    + Timer sınıfı
    + CountDownTimer sınıfı ve kullanımı
    + RxJava ile asenkron işlemler
        + Schedulers sınıfı (Schedulers factory class)
            + computation metodu
            + io metodu
            + newThread metodu
            + single
            + trampoline
            + AndroidSchedulars sınıfı 
    + Thread'lerarası senksronizasyon
    + Örnek uygulamalar

## Yerel veritabanı işlemleri:
+ Temel veritabanı kavramları
    + CRUD işlemleri
    + İlişkisel veritabanı yönetim sistemleri (Relational Database Management Systems)
    + NoSql veritabanı yönetim sistemleri
+ SQLite veritabanı yönetim sistemi
+ SQLite API ile veritabanı işlemleri
+ RoomDatabase kullanarak veritabanı işlemleri
+ ObjectBox kullanarak veritabanı işlemleri
+ Örnek Uygulamalar 

## Content Provider'lar ile veri alışverişi
    + Content provider kullanımı  

## Android Service uygulamaları (local and remote services)
    + Android service kavramı
    + Service sınıfı
    + IntentService sınıfı
    + Yerel servisler (local services)
    + Android sürümleri arasındaki service farklılıkları ve benzerlikleri
    + Uzak servisler (Remote Servileri)
        + AIDL servisler
        + Mesaj kuyrukları
    + Örnek uygulamalar

## Broadcast işlemleri
    + Broadcast kavramı
    + Android broadcast kullanımı
    + Android sürümleri arasında broadcast farkları
    + Örnek uygulamalar

## Kaynak (resource) kullanımı
    + Kaynak kavramı
    + string kaynakları
    + string kaynakları ile uygulamada çoklu dil desteği
    + drawable kaynaklar
    + layout kaynaklar
    + Örnek uygulamalar

## TCP/IP Client-Server programlama
    + IP protokolü ve temel kavramlar
    + TCP ve UDP protokolleri
    + Socket kavramı
    + Network byte order (little mandian, big endian kavramları)
    + Client, server programlama modeli
    + TCP protokolü ile uygulama geliştirme
        + Server programın organizasyonu
        + Client programnın organizasyonu
        + Binary haberleşme
        + Text haberleşme
        + Farklı platformlarda geliştirilmiş uygulamalar ile haberleşen uygulmalar
    + UDP protokolü ve uygulama geliştirmne
        + Datagram kavramı
        + UDP programlarının organizasyonu
        + UDP kullanılan örnekler
    + Örnek uygulamalar

## Konum işlemleri
    + GPS kullanarak konum bilgisinin elde edilmesi
    + GSM kullanarak konum bilgisinin elde edilmesi
    + WiFi kullanarak konum bilgisinin elde edilmesi
    + Örnek uygulamalar

## gRPC
    + RPC (Remote Procedure Call)
    + Protobuf
    + gRPC stub
    + Örnek uygulamalar

## Web Servis kullanımı
    + Web servis kavramı
    + RESTful servisler
    + JSON ve XML veri değiştirme (data exchange) formatları
    + Android web servis erişimi (consume)
        + org.json paketindeki sınıflar
        + Spring RestTemplate sınıfı
        + Retrofit kullanımı
        + RxJava ve Retrofit birlikte kullanımı
        + XML web servislerine erişim

## IOT uygulamaları
    + IoT kavramı
    + RaspberryPi ile Android haberleşme uygulamaları
    + Örnek haberleşme uygulamaları

## Temel çizim işlemleri
    + View üzerinde çizim işlemleri
    + Android dokunma (touch) işlemleri
    + Canvas sınıfı
    + Temel OpenGL ES
    + Örnek uygulamalar

## Bazı özel işlemler
    + Android uygulamalarının icon'larının gizlenmesi
    + Sistemin yeniden başlatılmasında (boot) devreye giren uygulamalar
    + Sistem üzerinde çalışan uygulamaların (process) elde edilmesi
    + Olası bir hata (exception) durumunda uygulamanın yeniden başlatılması
    + Ortak intent'ler
    + Örnek uygulamalar

## Ve diğerleri

