# OZET
---
## Arrays
---
* Arrays (Diziler), anlam ifade etmesi için birden fazla nesneye ihtiyaç duyabilir. Mesela, Şu an karşısında olduğunuz bilgisayar örneğini inceleyelim. Masaüstü bilgisayarlar, klavye-mouse-monitör üçlüsünü bir araya getirince anlam ifade eder. Herhangi biri olmadan bir işlem yapmanız olasıdır ama zorludur.
* Array (Dizi), dezavantajlarından biri olan hafıza problemini inceleyelim. Bilgisayar örneğimizden devam edelim. Hali hazırda bir klavye, bir mouse ve bir monitörümüz var. Yeni bir monitör aldığımızda daha büyük bir masaya ihtiyacımız var. Aynı şekilde yeni bir klavye veya mouse aldığımızda da aynı durum geçerli. Bir yerden bir yere taşırken zaman ve güç kaybına uğruyoruz.
* Dynamic Arrays (Dinamik diziler) ise yeni bir eleman için boşta yer tutmasından ötürü esnektir. Örneğin, bazı mutfak masaları açılan sürgülü bir yapıya sahiptir. Masanın küçük kaldığı durumlarda büyütmek için kullanılır. Dinamik dizilerde aynı mantığa sahiptir. Yeni elemanlar için yer tutarlar.
* Dynamic Array (Dinamik dizinin) dezavantajlarından biri ise hafızada fazladan yer kaplaması, gerçekleşecek olan bir diğer olayı engelleyebilir. Nasıl mı, hemen örnek ile kavrayalım. Masa örneğinden bahsetmiştik. Misafirleriniz bir işi çıkması durumunda fazladan yer kapladık ve hareket kabiliyetimizi kaybettik.
* Hep dezavantajlarını konuşuyorsun, e yahu bunun avantajı yok mu? Tabii ki var. Array'lerin birbirine bağlı olması ulaşılabilirliğini kolaylaştırır. Klavye-Mouse-Monitör örneğini vermiştik. Hepsi bir masada bulununca ulaşılması kolaydır. (Masa = Array, Klavye-Mouse-Monitör = Array Elemanı)
---

### NOTLAR
---

Bir arada tutulma mantigi bu kutucuklarin yan yana olmak zorunda .


Arraylerde yeni eleman ekleme masrafli bir is olmakta ornek olarak vermek gerekirse sinemaya 5 arkadas gittik ve yan yana oturuduk daha sonrasinda 2 arkadas daha geldi ama yanimizda bos yer yok bundan dolayi , kalkip 7 kisi yan yana bos olan bir yere gittik . Yani yeni gelen elemanlardan dolayi bir zorluk yasadik bir nevi arraylerin mantigi bu sekilde islemekte .Peki buna cozum olarak ne sunmaktayiz . 
Buna cozum olarak Dynamic Array cozum olarak ortaya cikmistir .
Cozumu yeni gelen kisilerden once ben 5 + 5 kisilik yer tutuyorum sinemada bu sekilde yeni gelen kisilerle de birlikte yan yana oturabiliyoruz.
* Burada negatif yanlar gelecek kisi sayisi 3 oldu diyelim ve ben 10 kisilik yer ayirdim bundan dolayi hafizada fazla yer tuttum.
* Bir negatif yonu daha 10 kisiden fazla kisi gelirse gene goc etmemiz gerekecek . 

Arti ne derseniz ? 
* Erismek istedigim verilere yani arkadaslarima hizli bir sekilde ulasabilecegim .


