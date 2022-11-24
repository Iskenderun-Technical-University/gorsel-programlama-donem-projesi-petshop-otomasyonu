ncelikli amacımız bu otomasyonu kullanmak isteyen bir petshop’a girip çıkan bütün hayvanların kaydını tutmaktır. Bu kayıtları cins,tür,sayı gibi ölçütler vasıtasıyla sınıflandırdık. Sonuçta işletme sadece bir şubeden oluşmayabilir, birçok şubesi olan bir petshop zinciri olabilir. Bu sayede bir veya birden fazla şubede elde olan veriler birleştirilebilir.

Bu konuda üç tane form hazırladık.

![Admin Giriş Paneli](https://user-images.githubusercontent.com/104498895/203740207-ea17279a-b8c7-4f46-962c-a1f5ac7b9e9a.png)

Birinci forumda Admin Giriş Paneli yaptık ve veritabanı tarafında üç tane admin ve onların farklı farklı şifrelerini tanımladık.

![2022-10-27 18_55_17-Video webm - Google Drive](https://user-images.githubusercontent.com/104498895/203741500-c183c0d5-6f4d-46d0-a429-026c11c0cf8a.png)

Kullanıcı adımızı ve şifremizi yazınca karşımıza Form1 paneli çıkıyor.

![Form1](https://user-images.githubusercontent.com/104498895/203743344-33723118-3e92-44bb-beba-f2266349bee7.png)

Bu panel sayesinde petshopa alınan ve satılan hayvanların verilerini değiştirmemiz için çeşitli butonlar var. Girdiğimiz hayvan bilgilerini istediğimiz butonla güncellediğimiz zaman, yeni veriler anında panelin altındaki datagridview'e düşüyor. Tabii bunu yapabilmek için oluşturduğumuz otomasyon ve veritabanının ikişkilendirmek gerekiyor. Bunu da kod kısmında yapıyoruz.

Verileri güncelledikten sonra tuttuğumuz kayıtların güncellenmiş halini görüntülemek için istatistik-form adlı bir panel oluşturduk.

![istatistik-form](https://user-images.githubusercontent.com/104498895/203744924-e98aa26b-a842-4313-ad0a-1ec929029ff2.png)

Genel istatistiklere ek olarak en çok alınıp satılan hayvan türlerinin ayrı ayrı istatistiklerini oluşturduk. Dişi ve erkek sayısını, o türe ait hayvanların toplam değerleri gibi bilgileri saklamak için sekmeler koyduk. Yukarıdaki Form1 panelinde de güncellediğimiz veriler her zaman için güncellenmiş haliyle istatistik-form panelinde yer alır.




