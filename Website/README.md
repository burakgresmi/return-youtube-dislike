# youtube-beğenmeme-sitesine dönüş

 ## Yapı Kurulumu

 ```bash
 # bağımlılıkları yükle
 $ npm yükleme

 # localhost'ta sıcak yeniden yükleme ile servis yapın:3000
 $ npm dev çalıştırma

 # değişikliklerinizi silin
 $ npm çalıştırma tiftiği

 # üretim için oluştur ve sunucuyu başlat
 $ npm çalıştırma derlemesi
 $ npm çalıştırma başlangıcı

 # statik proje oluştur
 $ npm çalıştırma oluşturma
 ```

 İşlerin nasıl yürüdüğüyle ilgili ayrıntılı açıklama için [belgelere](https://nuxtjs.org) bakın.

 ## Önerilen VSCode Kurulumu
  - [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint) `ext install dbaeumer.vscode-eslint`
  - [Güzel](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) `ext install esbenp.prettier-vscode`
  - [Vetur](https://marketplace.visualstudio.com/items?itemName=octref.vetur)

 >`Ctrl(Cmd)` + `Shift` + `P` > Ayarları Aç (JSON)
 ```
 "editor.formatOnSave": doğru,
 "editor.codeActionsOnSave": {
     "source.fixAll.eslint": doğru
 }
 "vetur.validation.template": yanlış,
 ```

 ## Özel Dizinler

 Bazıları özel davranışlara sahip olan aşağıdaki ekstra dizinleri oluşturabilirsiniz.  Yalnızca "sayfalar" gereklidir;  işlevlerini kullanmak istemiyorsanız bunları silebilirsiniz.

 ### 'varlıklar'

 Varlıklar dizini, Stylus veya Sass dosyaları, resimler veya yazı tipleri gibi derlenmemiş varlıklarınızı içerir.

 Bu dizinin kullanımı hakkında daha fazla bilgiyi [belgelerde](https://nuxtjs.org/docs/2.x/directory-structure/assets) bulabilirsiniz.

 ### "bileşenler"

 Bileşenler dizini, Vue.js bileşenlerinizi içerir.  Bileşenler, sayfanızın farklı bölümlerini oluşturur ve yeniden kullanılabilir ve sayfalarınıza, mizanpajlarınıza ve hatta diğer bileşenlere aktarılabilir.

 Bu dizinin kullanımı hakkında daha fazla bilgiyi [belgelerde](https://nuxtjs.org/docs/2.x/directory-structure/components) bulabilirsiniz.

 ### 'düzenleri'

 Nuxt uygulamanızın görünümünü ve verdiği hissi değiştirmek istediğinizde, bir kenar çubuğu eklemek veya mobil ve masaüstü için farklı düzenlere sahip olmak istediğinizde, düzenler çok yardımcı olur.

 Bu dizinin kullanımı hakkında daha fazla bilgiyi [belgelerde](https://nuxtjs.org/docs/2.x/directory-structure/layouts) bulabilirsiniz.

 ### "sayfalar"

 Bu dizin, uygulama görünümlerinizi ve rotalarınızı içerir.  Nuxt, bu dizindeki tüm `*.vue` dosyalarını okuyacak ve Vue Router'ı otomatik olarak kuracaktır.

 Bu dizinin kullanımı hakkında daha fazla bilgiyi [belgelerde](https://nuxtjs.org/docs/2.x/get-started/routing) bulabilirsiniz.

 ### `eklentiler`

 Eklentiler dizini, kök Vue.js Uygulamasını başlatmadan önce çalıştırmak istediğiniz JavaScript eklentilerini içerir.  Burası Vue eklentileri eklemek ve işlevler veya sabitler enjekte etmek için kullanılan yerdir.  Vue.use()'u her kullanmanız gerektiğinde, 'plugins/' içinde bir dosya oluşturmalı ve yolunu 'nuxt.config.js' içinde eklentilere eklemelisiniz.

 Bu dizinin kullanımı hakkında daha fazla bilgiyi [belgelerde](https://nuxtjs.org/docs/2.x/directory-structure/plugins) bulabilirsiniz.

 ### 'statik'

 Bu dizin statik dosyalarınızı içerir.  Bu dizindeki her dosya `/` ile eşlenir.

 Örnek: `/static/robots.txt`, `/robots.txt` olarak eşlenir.

 Bu dizinin kullanımı hakkında daha fazla bilgiyi [belgelerde](https://nuxtjs.org/docs/2.x/directory-structure/static) bulabilirsiniz.

 ### 'mağaza'

 Bu dizin, Vuex mağaza dosyalarınızı içerir.  Bu dizinde bir dosya oluşturmak, Vuex'i otomatik olarak etkinleştirir.

 Bu dizinin kullanımı hakkında daha fazla bilgiyi [belgelerde](https://nuxtjs.org/docs/2.x/directory-structure/store) bulabilirsiniz.