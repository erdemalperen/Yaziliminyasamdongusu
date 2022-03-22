# Yazılımın-Yasam-Dongusu

Yaşamımız boyunca düzenli kullandığımız veya bir kere olsa da karşılaştığımız her yazılım ürünü karşımıza gelmeden önce belli aşamalardan geçmiştir.Bir yazılım projesinin sadece kodlardan ibaret oluştuğunu düşünmek büyük bir yanılgıdır. İster üç satırdan ibaret ister karmaşık yapılardan oluşan bir proje olsun bütün projeler planlama, analiz, tasarım ,test ve bakım gibi çeşitli aşamalardan geçer.Bu adımların bütününü ‘Yazılım Yaşam Döngüsü’ olarak adlandırabiliriz.Geçmişten günümüze kadar çeşitli ihtiyaçlara göre farklı döngü modelleri geliştirilmiştir.

Öncelikle yazılım yaşam döngüsünün temel adımlarından söz etmek gerekirse bunlar sırasıyla aşağıdaki gibidir:
1)Gereksinim (Requirements): Bu bölümde müşteriden projede olacak olan gerekliliklerin bilgisi alınır ve bu istekler çerçevesinde planlama yapılır.
2)Analiz (Analysis) : Bu bölümde gereklilikler detaylıca incelenir ve temel problem ortaya çıkarılır. Herhangi bir problemde müşteri ile temasa geçilir ve iş detaylıca dökümantasyona dökülür.
3)Tasarım (Desing): Analizin tamamlanmasıyla beraber istediğimizi nasıl elde edeceğiz sorusu sorulur ve yazılımın ilk hali oluşturulur fakat kodlama söz konusu değildir.
4)Gerçekleştirme (Implementation):Sistemin kodlandığı, test edildiği ve kurulum çalışmalarının yapıldığı bölümdür.
5)Bakım (Maintenance): Yazılımın tüm aşamaları tamamlanıp teslimi yapıldıktan sonra bu aşama başlar.Ürünün kullanımıyla alınan geri bildirimler sonucunda bakım ve güncellemeler yapılır.Bu bölüm yazılumun yaşamı boyunca sürer.
Yazılımın yaşam döngüsünde temel adımlar aynı kalmak üzere farklı modellere ayrılmıştır.Bu sayede yaşanabilecek sorunlardan ve karışıklıktan kurtularak projenin işleyişinde kolay ve rahat bir süreç geçmesini sağlar.Bu modeller kendi içinde geleneksel ve çevik olarak ikiye ayrılır.
 
Geleneksel Yazılım Süreç Modelleri:
1)	Gelişigüzel Model: Temel olarak bakıldığında bunu bir model olarak kabul etmek doğru olmaz.Çünkü bahsettiğimiz sistemde model veya bir yöntem bulunmaz.Kişiye bağlı değişiklik gösteren bu model için eskiden kalma olarak söz etmek yanlış olmaz.Bugünkü kullanımı ise genellikle basit programlamalar için uygulanır ve bakımı zordur.


2)	Barok Modeli: Gerçek anlamda ilk model olarak barok modeli kabul edebiliriz.Belgeleme sürecinden ayrı yazılımın geliştirilmesi ve testinden sonra yapılması doğrudur.Daha basit olarak yaşam döngüsü temel adımlarının sırayla uygulanması da denebilir.


3)	Çağlayan Yaşam Döngü Modeli: Üretimi kısa süren veya tanımı açık olan projeler için kullanılır.Geleneksel model olarakta bilinir.Barok model aksine geri dönüşümler iyi tanımlanmıştır.Aşamalar sırayla tamamlanarak atlama yapılmaz.Yazılımın kullanıcıya ulaşması vakit aldığından modelde sorunlar yaşanabilmektedir.Bu modelde aşama atlaması olmadığından gereken tüm detayların tasarıma yansıması için müşteriyle iyi iletişim kurulmalı ve tüm detaylar aktarılmalıdır.



4)	V Süreç Modeli: Model V harfini andırmasından adını alır.Sol tarafı üretim, sağ tarafı sınama işlemleri ile ilgili aşamalardan oluşmaktadır. Her bir aşamanın sonunda sınama işlemleri de bulunduğu için hata kaynaklarına dönüş kolaydır.Modelin üç adet temel çıktısı bulunur bunlar:  
*Kullanıcı Modeli: Kullanıcının geliştirme süreci ilişkisini tanımlayıp sistemin kabul ve sınama belirtimleri ortaya çıkarılmaktadır.
*)Mimari Model: Sistemin tasarım ve alt sistem ile bütün sistem sınama işlemlerine ilişkin işlemler.
*)Gerçekleştirim Modeli: Yazılımın modül kodlanması ve sınanmasına ilişkin fonksiyonlar.
Kullanıcının proje katkısını arttırdığı bir modeldir.İş tanımlarının keskin ve belirsizliklerin az olduğu bilgi teknolojileri projeleri için uygundur.Proje yönetim tarafında takip edilmesi ve kullannımı kolaydır.

            5 )Helezonik(Spiral) Model: 4 adet temel aşamadan oluşur bunlar:
           *Planlama: Üretimi düşünülen ara ürün için plan, amaç belirleme,önceki adımda çıkan ara ürün ile bütünleştirme.
           *)Risk Analizi:Olası risklerin belirlenmesi ve araştırılması.
           *)Üretim: Ara/Ana ürünün üretilmesi.
           *)Kullanıcı Değerlendirmesi: Çıkan ürünle ilgili olarak kullanıcı tarafından direkt yapılan değerlendirme ve sınama.
Bu modelde her zaman sonraki aşama planlanır.Risk analizi vurgusu yapılır ve olası riskler belirlenip çözülür.Alternatifler,kısıtlamlar ve hedefler belirlenir.Prototip yaklaşamı vardır ve üretilen prototipler sayesinde yinelemeli artırımlı bir yaklaşımı vardır.En önemli avantajlarından birisi kullanıcının isteklerinin tamamına yanıt verebilir ve hatalar oldukça erken fark edilerek maliyet ve zaman kaybı önlenir.Komplike bir yapıya sahiptir.Bu modelin eksisi olarak küçük ve düşük riskli projeler için çok pahalı bir sistem olması olabilir.
 
            6)Artımsal Geliştirme Süreç Modeli: Bu model tek seferde teslim yerine geliştirme ve teslimi parçalara böler. Kullanıcının ihtiyaçları önceliklendirilir ve önemli ihtiyaçlar erken teslime dahil edilir.Sıralanan parçaların bitişiyle ara ürün geliştirilir ve her seferinde kullanıcı tarafından test edilir.Olası değişiklikler ise sonraki teslimlerde ele alınır. Üretilen her sürüm birbirini içerir ve giderek artan sayıda işlev içererek geliştirilir.Kullanım ve üretim birlikte götürülür.Uzun zaman alabilecek ve eksik olması sorun olmayacak projeler bu modele uygun olabilir.Projenin tümden başarısız olma ihtimalini azaltır.

           7 )Kodla ve Düzelt Yaşam Döngü Modeli: İlk aşamada projenin ilk sürümü geliştirilir.Sistemin istenilen ürün olana kadar devam etmesi beklenir.Emekliye ayrılma safhası vardır.En kolay geliştirme modellerinden biridir fakat süreçle beraber masrafı fazla olabilir.Küçük yapıda belki birkaç yüz satır ve daha az süren projeler için uygundur.

Çevik Yazılım Süreç Modelleri: Her geçen gün büyüyen ve gelişen yazılım dünyasında, kullanıcıların daha hızlı şekilde kaliteli ve ucuz ürüne ulaşmak istemesi yazılım sektörünü de etkilemiş ve çevik süreç modellerinin oluşmasına yol açmıştır. Yöntemler geliştirme sürecindeki yavaşlık ve yüklerden kurtularak daha hızlı sonuca ulaşma ve değişen ihtiyaçlara cevap vermeyi amaçlamaktadır.Takım çalışmasının önemli olduğu bu metotlar insana dayalı ilerleyen yazılım sürecinde yazılımcıların motivasyon ve morallerini yüksek tutmayı sağladığı için üretim hızlı, kolay ve kaliteli şekilde ilerler.Çevik yazılım süreçlerinden iki popüler yöntemden bahsedebiliriz bunlar:
1)Extreme Programming(XP): Müşteri ve gereksinimleri merkezli bir modeldir.XP ile karasız kalan ve çabuk fikir değiştiren müşteri gereksinimlerine hızlı cevap verebilir.XP, projelerde formalite ve dökümantasyonu en aza çektiği için olası değişikliklerde hızlı uyum sağlayabilir.XP dört ana temel ve fazlaca ara değerden oluştuğunu söyleyebiliriz.Ana temelleri:
*)Geri Bildirim(Feedback):Hızlı ve sık şekilde bildirimler yapılır.Bu projenin gidişatını olumlu etkiler çünkü yapılan hatalar ve yanlış anlaşılmalar çabuk bir şekilde çözülür.
*)Basitlik:Geri bildirimi hızlı sağlayabilmek için basit ve karmaşıklıktan uzak çözümler tercih edilir.
*)İletişim: Bir projede ekibin tam olarak birbiriyle anlaşamaması büyük bir sorundur.XP bu problemi kaldırmak için sağlıklı bir iletişimi amaçlar.Yapılan iletişim yüz yüze ve anlaşılır olmalıdır.Bireylerin deneyimsizliği veya egoları samimi bir iletişim ortamını engeller.
*)Cesaretlendirme: “Bu projeyi bititirebilir miyiz” korkusu projeler için sıkıntılı olaylardan birisidir.Bu çok kolay bir şekilde çözülebilecek işlerin bile aksamasına neden olabilir.XP bu korkunun gereksiz olduğunu ve yazılımcının da hata yapabileceğini savunur.

 
2)SCRUM: Gün geçtikçe projelerin büyümesi ve karışıklaşması sebebiyle müşterinin olayın sonunu görememesi ve ihtiyaçlarını tam ortaya dökememesi sebebiyle projelerde bir çok hata çıkmaya başladı.Bu yapı üç temel değer üzerine kurulmuştur.Şeffaflık, projenin ilerleyişi ve yaşanan problemler herkes tarafından görülebilir olmalıdır.Denetleme, ilerleyiş düzenli olarak kontrol edilir.Uyarlama, projenin değişikliklere uyum sağlayabilmesidir.
Scrumda üç çeşit fikirleri ürünlere dönüştürebilen takımlar bulunur:
*)Ürün Sahibi(Owner):Fikirleri toplar, değerlendirir ve olma ihtimali bulunanları geliştirme takımına iletir.
*Scrum Master:Kurallar ve uygulamalar hakkında bilgi sahibidir.Kuralları takımda uygulamaktan sorumlu kişidir.
*Geliştirme Takımı(Development Team):Geliştirme çalışmalarını yaratacak şekilde yürütenlerden oluşur.
Scrumda çeşitli etkinlikler bulunur bunlar:
*Sprint: Belirli işin tamamlandığı ve incelemeye hazır hale getirildiği belli bir zaman sınırlaması bulunan bir dönemdir.Genellikler 2-4 hafta uzunluğunda sürer, ancak bir hafta kısa ve uzun olabilir.
*Sprint Planlama: Ekibin toplantıları ve hangi ürün öğelerinin teslim edileceğini ve başarılacağını belirleyen zaman olaylardır.
*Günlük Stand Up(Daily Stand Up): Ekibin her bir üyesinin ilerlemesini hızlı ve şeffaf bir şekilde ele aldığı kısa bir iletişim toplantısıdır.
*Sprint İncelemesi:Ürün sahibi , çalışmayı önceden tanımlanmış kabul kriterlerine göre kontrol eder ve çalışmayı kabul veya redderder.
Özetle scrum çok yapılı ve disiplinli bir metodolojidir.Tüm ekip üyeleri tarafından sahip olunan bireysel rollerin daha iyi anlaşılması ve benimsenmesine olanak sağlar.Bu sayede daha kaliteli ve hızlı projeler ortaya çıkar.
  
