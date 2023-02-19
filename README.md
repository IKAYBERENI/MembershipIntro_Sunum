# MembershipIntro_Sunum

Merhaba, MembershipIntro İstanbul - Beşiktaş Wissen Akademi'de Eğitim aldığım süreçte 302 sınıfım ile yazdık.Bu projedeki amaç üyelik sistemlerini yakınsamaktır.Bu proje ile amacımız gerçek hayata yaklaşmak ve istihdam sürecindeki hazır bulunuşluğu maksimum seviyeye getirebilmektir.

Bu projenin tüm hakları hocamız Betül Akşan'a, bana ve 302 sabah grubu sınıfımın öğrencilerine aittir. Burada projenin ekran resimlerini ve kaynak kodlardan bazı kod parçalarını aşağıda görebilirsiniz.

PROJE HAKKINDA TEKNİK BİLGİLER:

Proje Visual Studio .Net 6 ASP.NET MVC CORE ile yazıldı.
Proje Entity Framework Core Code-First yaklaşımıyla yazılmıştır.
Projede üye olurken üyelerin şifreleri System.Security.Cryptography-SHA512 ile hash-salt yapısıyla gizlenerek kayıt edilmiştir.
Şifremi unuttum butonu ile üyeye email gönderilerek şifresini yenilemesi sağlanır.
Projeyi 4 katman (EL,DAL,BLL,UI) olarak yazdık.
Projede Kayıt Ol, Giriş Yap, Telefon Ekle, Telefon Sil sayfaları bulunmaktadır. Üye sisteme giriş yaptıktan sonra aşağıdaki adımları izleyerek telefon ekleyebilir.
Proje gelişmeye açık olup zaman buldukça yeni sayfalar ya da yeni özellikler eklenecektir.
Ekran resimleri ve kaynak kodlardan bir parça aşağıda görebilirsiniz.

<img width="958" alt="AnaSayfa" src="https://user-images.githubusercontent.com/112905722/219973490-cf0e877a-9153-444f-8f73-34470be2fb47.png">


<img width="959" alt="TelefonEkleme" src="https://user-images.githubusercontent.com/112905722/219973498-bbb7d7e2-d8f3-4c5c-8e14-ad2d1102c007.png">


<img width="960" alt="YeniNumara" src="https://user-images.githubusercontent.com/112905722/219973506-07904bb6-0818-4664-b840-21d94c318f34.png">

<img width="959" alt="ŞifreTalebi" src="https://user-images.githubusercontent.com/112905722/219973510-0f0ac609-2267-46d3-b259-6e9f7e06b355.png">

<img width="960" alt="KullanıcıAdıHata" src="https://user-images.githubusercontent.com/112905722/219973516-f27e2bfa-9d16-4bb0-b505-d2c818a18cb1.png">

<img width="956" alt="ŞifremiUnuttumMaili" src="https://user-images.githubusercontent.com/112905722/219973519-2c91f5a6-c725-445c-a109-674b2461ff08.png">


<img width="960" alt="AccountController" src="https://user-images.githubusercontent.com/112905722/219973520-60f47901-0e1e-4e12-a816-2612093ce048.png">
