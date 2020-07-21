### Hafif, açık kaynak kodlu, evrensel bir kağıt cüzdan üreticisi

#### Önsöz
Bağımsız kuruluşlar tarafından uygun kod denetimi yapılmadan, kağıt cüzdan oluşturma sitelerini kullanmaktan kesinlikle kaçınılmalıdır. Gereksiz kodlar ve kötü yazılmış kütüphaneler sıklıkla kullanılır, bu da kullanıcılar için büyük bir güvenlik riski oluşturur. Bazı servisler, cüzdan üreticilerin çevrimdışında çalıştıklarını ve böylece kullanıcılarının özel anahtar hırsızlığa karşı bağışık olduklarını bildirmektedir.

Bununla birlikte, bir çevrimdışı kağıt cüzdan üreticisinin, bu bilgiyi herhangi bir şekilde iletme gereği duymadan, determinist olarak anahtarlar oluşturması olasılığı hala mevcuttur. Bu nedenle, uygun araştırma yapmadan rastgele bir çevrimdışı kağıt cüzdan üreticisine güvenmeyin. Öte yandan, bu evrensel üretici, hiç bir kötü kod içermez, ancak gerekli iyi kodları kullanır.

Lütfen kullanmaktan çekinmeyin.

#### Özellikler
* Basit, etkili, güvenli
* İstemci taraflı çevrimdışı çalışır
* Düzenli güncelleme sağlanır
* Şeffaftır ve denetlemesi kolaydır
* Az mürekkep kullanır
* Kullanılan dosyaların değiştirilmediği sha-256 bütünlüğü ile kolayca doğrulanabilir
* 510'dan fazla kripto para destekler

#### Yönergeler
* Maksimum güvenlik için bu üreticiyi kesinlikle çevrimdışı kullanın.
* Bilgisayarınıza indirin ve internet bağlantınızı kesin.
* Cüzdanınızı oluşturun, yazdırın ve mutlaka güvenli bir yerde saklayın.
* Kağıt cüzdanınızdaki genel adrese gönderim yaparak bakiye yatırın.
* Özel anahtarınız bakiyenizi harcamak için kullanılır. Asla paylaşmayın!

#### Bağışlar için
**BTC**: 3MEmomSUDWqWmEtRNoakSxF9ZgZuxn8tJj   


#### Bütünlük doğrulama
* [bitcoinjs-lib.js](https://github.com/bitcoinjs/bitcoinjs-lib) v3.3.2
	* [SHA-256] 34fb2141b70f690a8eb9fa75e703e99b39f8538201250115fc895343b7739708
* [bitcoincash-0.1.10.js](https://github.com/bitcoincashjs/bitcoincashjs)
	* [SHA-256] 0f98a457e504ffa94a0cd01488cb4dd94327a5fc655950de5a1e0b739faba252
* [web3-eth-accounts.js](https://github.com/ethereum/web3.js) (Resmi Ethereum API)
	* [SHA-256] 486fcaf21777aded0550ff96001f146855430904d7da2e3858a07835edd53212
* [ripple-0.22.js](https://github.com/ripple/ripple-lib/releases) (Resmi Ripple API)
	* [SHA-256] AB98026FABE296BD938297C48CB58E01DFDBE90F3C66C9617D6A3E1EFD4C6B93
* [lodash.js](https://github.com/lodash/lodash) (Ripple API dependency)
	* [SHA-256] 11e0a812af465183a588e62dc73b14bcb06fd33797740616e3b1a07922e9bc6a
* [stellar-base.js](https://github.com/stellar/bower-js-stellar-base) v0.8.2 (Resmi Stellar API)
	* [SHA-256] AD6BE647329F8159B6BB2F7F6E7CC8DE9B39B092951858EBB3F8ED5A1C66C8F4
* [bitcore-lib-zcash.js](https://github.com/bitmex/zcash-bitcore-lib)
	* [SHA-256] 621ad3c644508da28ac671c432a78de1d3b0f51a24edbd065bdb2c0e8f2f154c
* [monero.js](https://github.com/monero-project/monero) (Official Monero API)
	* [SHA-256] 8542b18b60ce05c69e69be0ed42aabbceca00bf26cf6f23930e8426a0428f726
* [qrcode.js](https://github.com/davidshimjs/qrcodejs) 
	* [SHA-256] 3ee72de9f69c668f9567363a9358df955960bae9000d9ebd66414670f88e8735
