# Hafta 1 - Ödevler :

## Hesaplarım :
- [Github](https://github.com/ramisyk)
- [HackerRank](https://www.hackerrank.com/ramisyk?hr_r=1)
- [StackOverFlow](https://stackoverflow.com/users/14502282/ramisyk)

## Docker :
Geliştiricinin bilgisayarında yazılan projenin başka bilgisayarda çalışması için gerekli kurulumların yapılmasının gerekmesi programların çalışmalarında sorun çıkarabilir. 
Docker container teknolojisi ile uygulama oluşturma, çalıştırma ve değitmayı amaçlamıştır.
konteynerlar yalnızca işletim sistemini sanallaştırarak kendisine ait bir sanal işletim sistemi gereksinimi duymadan fiziksel bir sunucu veya bilgisayar üzerinde uygulamanın çalışmasını sağlar.
Ölçeklendirme işlemleri için hızlı cevap verir
Bulut uygulamaları - hızlı microservis uygulamalarında performanslı 

|Virtual Machine                             |Docker                                         |
|--------------------------------------------|-----------------------------------------------|
|Donanım düzeyinde sanallaştırma             |Sadece işletim sistemi düzeyinde sanallaştırma |
|Her makine için farklı işletim sistemi      |Ana makinenin işletim sisteminin paylaşımı     |
|Yüksek boyut                                |Düşük boyut                                    |
|Yavaş çalışma                               |Hızlı çalışma                                  |
|Yüksek kaynak kullanımı                     |Düşük kaynak kullanımı                         |
|Donanımın izin verdiği kadar makine çalışır |Bir çok konteyner çalışabilir                  |


**Container :** Yazılım paketleme teknolojisi. VM in üzerine geliştirilmiştir. Çekirdek fonksiyonları kullanır işletim sistemi katmanı içermez ve daha az kaynak tüketir. 

**Docker Image :** Uygulamanın çalışması için gerekli kütüphaneler, ortam değişkenleri ve konfigürasyon dosyalarını içinde saklayan, çalıştırılan paketlerdir. Containerlerin ayağa kalkması için gereklidir. 

**Docker Registry :** Docker Hub da imaj dosyalarını alıp kullanabildiğimiz, yeni imaj dosyaları yükleyip konfigüre edebildiğimiz imajların bulunduğu kayıt alanıdır. Public olarak bulunur. 

## .NET Araştırmaları :
![https://docs.microsoft.com/tr-tr/dotnet/standard/library-guidance/media/cross-platform-targeting/platforms-netstandard.png](https://docs.microsoft.com/tr-tr/dotnet/standard/library-guidance/media/cross-platform-targeting/platforms-netstandard.png)

### .NET CORE Versiyonları :

###### .NET Core:
.Net Core temelde farklı sistemlerde ve farklı işlemci mimarilerinde çalışmasına imkan sunmakla beraber, docker desteği sağlamaktadır.

###### .NET Core 2.0:
- C# 7,1 'yi destekle
- Önceki versiyondan en büyük farkı çok hızlı çalışma sürelerini elde etmesidir.
- .NET Core 2,0 ' de mevcut olan API 'lerin toplam sayısı, .NET Core 1,1 ile karşılaştırıldığında iki katına çıkar.
- 

###### .NET Core 3.0:
- C# 8,0 için destek ekler.
- Varsayılan olarak framework-dependent executables (çerçeveye bağlı yürütülebilir dosyaları) oluşturur. Eski hali: self-contained deployments
- Katmanlı derleme ile çalışma zamanının daha iyi performans elde edilmiştir.


### .NET 5.0:
- .Net Core ile platformlar arası bir geçişe başlayan Microsoft .Net 5 ile yeniden bir araya geliyor.
- Xamarin, Unity, ML.Net gibi bütün frameworkler bir arada toplanacak.
- Windows, Linux, macOS, iOS, Android, tvOS, watchOS and WebAssembly gibi birçok platform için destek sağlanıyor.
- Hızlı başlangıç ve düşük bellek tüketimi sağlıyor.
- .Net Framework ile yazılmış bir uygulamayı .Net Core’a geçirirken shared library olarak bazı tanımlamalar yapmak gerekebiliyor. Çözüm olarak tanımlamalarımızı .Net Standart ile geliştirmemiz gerekiyordu ancak .Net 5 ile birlikte artık tek bir Base Class Library olacak.
- Docker’a kolay adapte olabilen yapısı ile containerization işlemlerinde kolaylıklar sağlanacak.

**.NET 5 den sonra kalkacaklar:** 
- ASP.NET Web Forms yerini Blazor'a bırakıyor.
- Farklı makineler üzerindeki uygulamaların iletişimini sağlayan Windows Communication Foundation yapısı yerine gRPC kullanılabilecektir.

### Azure Servisleri:
Azure bir çok alanda bulun tabanlı hizmetler vermektedir.
- **Ağ İletişimi:** Altyapı ve hizmetler arasında bağlantı kurarak hizmet sunar.
- **Analiz:** Veri toplama, depolama, işleme, analiz etme ve görselleştirme işlemlerinde destek sunar.
- **Geliştirici Araçları:** Herhangi bir platform ya da dil için bulut uygulamalarını oluşturma, yönetme ve kullanıma sunmayı sağlar.
- **Mobil:** Mobil uygulama servisleri sunar.
- **Güvenlik:** Veri ve uygulama bazında tehditlere karşı savunma hizmeti.
- **Nesnelerin İnterneti:** Altyapı değişimine gereksinim duymadan kullanılan cihaz ve platformlara IoT desteği eklenir. 
- **Web:** Web uygulamalarının hızlı ve verimli bir şekilde oluşturulmasını, dağıtımını ve ölçeklendirilmesini sağlar.
- **Windows Sanal Masaüstü**
- **Yapay Zeka ve Makine Öğrenimi:** Birçok işlem için kod yazma gereksinimi olmadan yapay zeka ve makine öğrenmesi ekletileri ile uygulamalara destek sunar.
- **Yönetim ve İdare:** Bulut kaynaklarının yönetimini ve uyumluluğunu basitleştirme, otomatikleştirme ve iyileştirme işlemlerini gerçekleştirir.

### Takip Ettiklerim
- [Bora Kaşmer](http://www.borakasmer.com/)
- [Muhammed Hilmi Koca - Medium](https://medium.com/@mhkoca)
- [Ugur Umutluoglu - Youtube](https://www.youtube.com/channel/UCpFcAp-klqUMATCKS71ZXPw)
- [freeCodeCamp](https://www.freecodecamp.org/news/)
- [GeeksforGeeks](https://www.geeksforgeeks.org/)

**Sosyal Medya:**
- [Nilay Yener](https://twitter.com/nlycskn)  
- [Halid Altuner](https://twitter.com/halidaltuner)
- [Adem ilter](https://twitter.com/ademilter)

**Eğitim:**
- [Engin Demiroğ](https://www.youtube.com/channel/UCRjiquPh4mjPNoOV9eCilXQ) ⇒ Yazılım Eğitimleri
- [BilgisayarKavramlari](https://www.youtube.com/channel/UCkkgrhDCJheXQNIFqUVw0_g) ⇒ Bilgisayar Bilimi dersleri üzerine

**Ek ⇒** 
[https://twitter.com/ademilter/status/1221859809278025729](https://twitter.com/ademilter/status/1221859809278025729)

### İş ilanı
- [Türkcell Sınırsız Yetenek](https://kariyerim.turkcell.com.tr/sinirsiz-yetenek/)
- [Türkcell Genç Yetenek](https://kariyerim.turkcell.com.tr/genc-yetenek)

### Kodun Kalitesi
- 
