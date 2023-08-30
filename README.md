Ruby On Rails İle Mini E-Ticaret Projesi Admin Paneli

Bu proje, Ruby on Rails çerçevesi kullanılarak geliştirilen bir mini e-ticaret yönetim panelini içerir. Bu panel, temel e-ticaret işlemlerini kolaylaştırmak üzere tasarlanmıştır ve kullanıcı dostu arayüzü ile dikkat çeker.

Özellikler
Sipariş İşlemleri: Siparişleri arama, ekleme, silme ve güncelleme işlemleri için kullanıcı dostu bir arayüz sağlar. Sipariş durumlarına göre kolay bir şekilde filtreleme yapabilir ve siparişlerinizi düzenleyebilirsiniz.

Ürün İşlemleri: Ürünleri arama, ekleme, silme ve güncelleme işlemleri için özel bir yönetim paneli sunar. Ürünleri kategorilere ve markalara göre filtreleyebilir, stok durumunu takip edebilirsiniz.

Kategorizasyon İşlemleri: Ürünleri kategorilere ayırmak ve kategorileri düzenlemek için kolay bir yol sağlar. Yeni kategoriler ekleyebilir, mevcut kategorileri düzenleyebilirsiniz.

Marka Yönetimi: Ürünlere markalar eklemek ve mevcut markaları yönetmek için kullanıcı dostu bir arayüz sunar. Bu sayede ürünlerin marka bazında analizini yapabilirsiniz.

Kullanıcı Giriş İşlemleri: Farklı kullanıcı rolleri (örneğin admin, editör) için giriş işlemlerini yönetir. Kullanıcıların yetkilendirmelerine göre belirli işlevleri gerçekleştirmelerine izin verir.

Veri Analitiği: Satış istatistikleri, popüler ürünler, sipariş analizleri gibi temel veri analitiği sunarak işletme performansını değerlendirmenize yardımcı olur.

Kullanılan Önemli Gem'ler

[Ransack:](https://github.com/activerecord-hackery/ransack) Gelişmiş arama ve sıralama işlemleri için kullanılan bir gem.

[Turbo Rails:](https://github.com/hotwired/turbo-rails) Ruby on Rails projeleri için Hotwire Turbo desteği sağlar.

[Haml:](https://github.com/haml/haml) Hızlı ve temiz HTML markup oluşturmak için kullanılan bir gem.

[Simple Form:](https://github.com/heartcombo/simple_form) Form oluşturmayı basit ve esnek bir hale getiren bir gem.

[Bootstrap:](https://getbootstrap.com/) Kullanıcı arayüzü geliştirmek için popüler bir HTML, CSS ve JS framework'ü.

[Ancestry:](https://github.com/stefankroes/ancestry) Kategorizasyon işlemleri için kullanılan bir gem.

[Devise:](https://github.com/heartcombo/devise) Kullanıcı yetkilendirmesi ve giriş işlemleri için popüler bir gem.


Nasıl Başlanır

Bu depoyu bilgisayarınıza klonlayın.
```
git clone https://github.com/Yasingthb/mini-e-commerce-project/
```

Gerekli gem'leri yüklemek için terminalde proje dizininde aşağıdaki komutları çalıştırın.
```
bundle install
```

Veritabanını oluşturun ve örnek verileri eklemek için aşağıdaki komutları sırasıyla çalıştırın.
```
rails db:create
rails db:migrate
rails db:seed
```
Sunucuyu başlatın.
```
rails server
```
Tarayıcınızda ```http://localhost:3000``` adresine giderek admin paneline erişebilirsiniz.
