# Güvenlik

 ### Görüntüleme geçmişimi izliyor musunuz?

 Hayır. Uzantının kodu herkese açıktır ve kendiniz görebilirsiniz.  Gönderilen tek bilgi, videolar için beğenmeme sayısını almak için gereken video kimliğidir.  Gönderilen ek başlık yok.  İletişim katmanı üzerinden, genel IP'niz sunucuya ve isteğin yapıldığı zamana maruz kalacaktır.  Ancak, bunların hiçbiri sizi hiçbir şekilde benzersiz bir şekilde tanımlamıyor.  Sıfır güven ortamını varsayarsak, elde edebileceğimizin en iyisi dinamik bir IP'dir.  Ki, bugün sizin, yarın komşunuzun.  IP'nizin izlenmesinden gerçekten endişeleniyorsanız, muhtemelen zaten bir VPN kullanıyorsunuzdur.

 ### Beğenmezsem beni benzersiz bir şekilde tanımlayabilir misin?

 Evet.  Bir videoyu beğenmediğinizde, sizin için Google hesabınıza bağlı olmayan rastgele oluşturulmuş benzersiz bir kimlik oluştururuz.  Bu, botlamayı önlemek için yapılır.  Ancak bu rastgele kimliği size veya kişisel YouTube hesabınıza bağlamanın bir yolu yoktur.

 ### Tam olarak hangi bilgilere sahipsiniz?

 Sadece video kimliği.  Yorumlarınız değil, kullanıcı adınız değil, videoyu kiminle paylaştığınız, ek meta veriler değil.  Hiç bir şey.  Sadece video kimliği.

 ### IP'm nasıl saklanır?

 Arka uç, karma olmayan IP adreslerini yalnızca geçici bellekte (RAM) tutar.  Bu adresler bir sabit sürücüde depolanmaz ve bu nedenle günlüğe kaydedilmez.  IP adreslerini hash ederiz ve bunun yerine depolanır.  Bu, veritabanı vandalizmini önlemek için yapılır.

 ### OAuth hakkında bir tartışma duydum ve YouTube hesabıma eriştim!

 Bu özellik isteğe bağlı olacak ve çok fazla tercih edilecek.  Bir YouTube içerik oluşturucusuysanız ve beğenmeme istatistiklerinizi bizimle paylaşmak istiyorsanız, yapabilirsiniz.  [OAuth](https://en.wikipedia.org/wiki/OAuth#:~:text=but%20without%20thing%20them%20the%20passwords.) yapılandırılma şekli, aslında çok güvenli.  Hesabınıza erişimi istediğiniz zaman iptal edebilir ve bize çok özel izinler verebilirsiniz.  Gerekli olmayan herhangi bir izin istemeyeceğiz.  Yalnızca video istatistiklerinizi görüntülemek için izin isteyeceğiz.

 ### Bu beğenmeme sayısına nasıl güvenebilirim?

 Bot saldırılarını önlemek için önlemler aldık ve bot önleme sisteminin etkinliğini artırmak için çalışmaya devam edeceğiz: bu, beğenmeme sayısını gerçek sayının iyi bir temsilcisi olarak tutmamıza yardımcı olacaktır.  Tabii ki hiçbir zaman %100 doğru olmayacaktır, bu yüzden sayıma güvenip güvenmemek size kalmış.

 ### Arka uç kodunu neden paylaşmıyorsunuz?

 Bir noktada paylaşacağız - ama şu anda paylaşmak için gerçekten gerçek bir sebep yok.  Yanlış bir güvenlik hissi verir - çünkü sıfır güvenli bir sistemde, bir sürümü ifşa edebilir, ancak bir başkasını devreye alabiliriz.  Özellikle spam ile nasıl mücadele ettiğimiz gibi, kodu gizli tutmak için birçok neden var.  İstenmeyen posta işleme kodunu gizlemek/Gizlemek oldukça standart bir uygulamadır.