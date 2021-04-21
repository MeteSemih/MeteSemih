-***YAZILIMDA TEMİZLİK***
Günlük hayattada olduğu gibi temizlikte yazılım dünyasından önemli bir yere sahiptir.Burda temizlikten kastım olusutracağımız projenin belli bir mimariye uyarak basit ve anlaşılır bir program yazmaktır.
Yazacağımız projede en basta kullandığımız yöntemlerden plan yapmaktır.Plan yapmamız bize projenin ilk çıktığı zamandaki gibi kalmasını amaçlamaz her zaman ileriye yönelikte bir proje olmasını sağlamaktır aslında.Plan yaparken o projenin müşteriye ulaştıktan sonra yeni bir sürümünün gelmesi için ve bu sürümü kısa vadede gelebilmesi için yaptığımız bir aşamadır aslında.
Bu aşamada ise Clean Code devreye girer.Bir projeyi karmaşık bir şekilde alelacele yapıp yetiştirmemiz bizi zamandan tasarruf  yaptığımızı düşündürebilir ama aslında öyle değildir.
Yazdığımız projeyi karmaşık bir şekilde clean code kurallarına uygun bir şekilde yazmamamız projenin geleceğinde bize zara verir.Çünkü o projeyi ileriki zamanlarda geliştirmemiz gerekecektir çünkü müşterinin istekleri dinamik bir süreçtir zaman geçtikçe değişebilir,artabilir bızde bu ısteklere en kısa sürede yanıt verebilmemiz için kodumuzun anlaşılır düzgün ve basitlik ilkesine uygun bir şekilde yazmamız bizim ileriki dönemlerde projemizi geliştirmemizi kolaylaştıracaktır.
Söyle düşünelim yaptığımız proje ilk basta gayet güzel bir şekilde çalışıyor ama zamanı gelince yeni bir uzantılar eklememiz gerekli olduğunu düşünelim biz bu gerekliliği en kısa sürede gidermemiz lazım bunun içinde projemizin var olan kodları üstünde değişikliğe ihtiyacımız vardır.Ama bu değişiklikleri yapmamız için önce koddaki değiştirmemiz gereken yerleri anlamamız üstünde düşünebilmemiz  lazımdır.Eğer biz bu projeyi yukarda bahsettiğim basitlik ilkesine aykırı olarak cok aceleci bir şekilde yapmış olursak yazdığımız kodları anlamamız değiştirebilmemiz çok uzun süreler alır.Bu uzun süreç sadece müşteriye değil yapımcı firmayada ciddi bir anlamda kötü yansır.
Örneğin o kodu yazmayı bitirdiğimizde yapımcı firmanın uzun bir çalışmadan dolayı populiterini kaybetmiş olabilir.Müşteri artık beklemekten bıkıp başka firmalara yönlenmiş olabilir.Ayrıca projeyi geliştirmek için çalışan mühendislerin,yazılım uzamanların alacağı  total maaş miktarı zamanla altından kalkamayacağımız bir seviyeye gelebilir .
Bu anlamda o kodu zamanından karmakarışık yazmak hem firmanın maddiyat  anlamında zarara uğramasını hem de ürünü geç sunduğu için müşterilerinden kayba uğrarak her yerden zarar etmiş olmasını sağlar.
Peki clean code nasıl yazılmalıdır birkaç maddeyle bakalım.
1)Her kavram için tek kelime kullanarak  farklı sınıfların benzer metotları için aynı tek kelime seçilerek her yerde o kelimeyi kullanmak.
2)Metot isimlerinde fiil kullanmak daha etklili olur(Ertele,yazdır,okut vb.).
3)Fazla kodlamalardan kaçınılmalıdır unutmayın ki amacımı en uzun kodu yazmak değil aynı işlevi daha basit ve analasılır bir şekilde kısa yazmaktır.
4)Çok fazla boşluk bırakmamaya dikkat edilmeli ve yan yana yazmaktan kaçınılmalıdır.
Bi kaç temiz ve karmaşık kodlara bakalım beraber.
Aşağıdaki  örnekte a değişkenimiz sıralı ve boşluk bırakılmadan yazılmıştır temiz kod örneğidir.Diğer değişkenimiz b ise aralarında büyük boşluklar bırakılarak yazılmıştır.Bu hatalı yazılım büyük projelerde arttıkça okunması zor bir hale gelir.
 
Bir diğer örneğimize bakacak olursak bu örnektede int,float,double değişkenlerimizin ayrı ve anlaşılır bir şekilde alt alta yazdığımız görüyoruz.Ama ikinci  bi yazım türünde ise bu değişkenler yan yana yazılarak tanımlanmıştır bu kirli koda örneğidir bu yazım türü mantıksal olarak aynı olsada okunması zor bir hale gelmesini sağlar.
 


