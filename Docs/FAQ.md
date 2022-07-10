~ Coded by Burak Gökkaya | @burakgresmi ~

# Sıkça Sorulan Sorular

 ## GitHub veya Telegram'da soru sormadan önce lütfen buna bakın.

 ### **1.  Bu uzantı verileri nereden alıyor?**
 Google API'leri ve kazınmış verilerin bir kombinasyonu.

 Google, API'lerinde beğenmeme sayılarını kapattıktan sonra kullanılabilir olması için mevcut tüm verileri DB'mize kaydederiz.

 ### **2.  Video beğenmeme sayısı güncellenmiyor**
 Şu anda video beğenmeme durumları önbelleğe alınır ve çok sık güncellenmez.  2-3 günde bir, daha sık değil.

 Evet, ideal değil, ama olan bu. Bunları ne sıklıkta güncelleyebileceğimizi geliştirmeye çalışıyoruz.

 ### **3.  Bu nasıl çalışıyor?**
 Uzantı, izlediğiniz videonun video kimliğini toplar, beğenmeme durumlarını (ve görüntülemeler, beğeniler vb. gibi diğer alanları) API'mizi kullanarak getirir; video, API'miz tarafından ilk kez getiriliyorsa YouTube API'sini kullanır.  verileri almak için, verileri önbelleğe alma (yaklaşık 2-3 gün önbelleğe alma) ve arşivleme amacıyla bir veritabanında saklar ve size geri döndürür.  Uzantı daha sonra size hoşlanmadığınız şeyleri gösterir.

 ### **4.  YouTube API, beğenmeme sayısını döndürmeyi bıraktıktan sonra ne olacak?**
 Arka uç, arşivlenmiş beğenmeme istatistikleri, uzantı kullanıcı verilerinden tahmin edilen tahminler ve beğenmedikleri arşivlenmemiş videolar ve eski beğenmeme arşivleri için görüntüleme/beğenme oranlarına dayalı tahminlerin bir kombinasyonunu kullanmaya geçecektir.

 ## Güvenlik/gizlilik endişelerim var
 Daha fazla bilgi için [bu sayfaya](GÜVENLİK-FAQ.md) bakın.