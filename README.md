# rockPaperScissors

Çalıştığımız yer, kullanıcıların hoş vakit geçirmesi için web sayfasına bu sefer bir taş-kağıt-makas oyunu eklemeye karar verdi. Bugünkü işimiz javascript kullanarak taş-kağıt-makas oyunu için tasKagitMakas adında bir fonksiyon yazmak.

Bu oyun 2 kişiyle oynanır. Kullanıcılar taş, kağıt ya da makas'tan birini seçer ve aynı anda birbirlerine söylerler. Taş makası, makas kağıdı, kağıt taşı yener. Bu üstünlük kurallarına göre kimin kazandığı belirlenir. Seçimlerin aynı olması durumunda beraberlik oluşur.

Bu fonksiyon;

Kullanıcının seçimini parametre olarak almalı,
Bilgisayar için rastgele bir tercih oluşturmalı,
Aşağıdaki örneklerdeki gibi bir metni geri dönmeli.

Örnek Kullanımlar

tasKagitMakas("makas");
"Senin seçimin: makas. Bilgisayarın seçimi: kağıt. Kazandın!" (Demek ki bu sefer bilgisayar seçimi kağıtmış.)

--

Testler:
Kullanıcı taş seçtiğinde ve bilgisayar kağıt seçtiğinde doğru sonucu döndürüyor mu?
Kullanıcı kağıt seçtiğinde ve bilgisayar makas seçtiğinde doğru sonucu döndürüyor mu?
Kullanıcı makas seçtiğinde ve bilgisayar taş seçtiğinde doğru sonucu döndürüyor mu?
Kullanıcı kağıt seçtiğinde ve bilgisayar kağıt seçtiğinde beraberlik sonucunu döndürüyor mu?
Kullanıcı taş seçtiğinde ve bilgisayar taş seçtiğinde beraberlik sonucunu döndürüyor mu?
tasKagitMakas("kağıt");
"Senin seçimin: kağıt. Bilgisayarın seçimi: taş. Kazandın!" (Demek ki bu sefer bilgisayar seçimi taşmış.)

--

tasKagitMakas("taş");
"Senin seçimin: taş. Bilgisayarın seçimi: taş. Beraberlik!" (Demek ki bu sefer bilgisayar seçimi taşmış.)
