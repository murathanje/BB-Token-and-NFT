# Sertifikalarımızı NFT ile saklama

### BB tokenlarımızı harcamanın keyfini sürerken sırada sertifikamızı NFT(Non Fungible Token) oalrak blockchainde depolama vakti. ✒️

* Öncelikle Bulut Bilişmciler üzerinden yeni bir terminal açıyoruz

* GitHub üzerinde bulunan repositorymizi 

   ```git clone https://github.com/murathanje/bb_NFT.git```

	ile çalışma ortamımıza çekiyoruz.

* Ardından ```cd bb_NFT/``` komutu ile dosyamıza giriyoruz.

* Daha sonra ``` npm i nft.storage mime fs path node-fetch``` komutu ile gerekli kütüphaneleri yüklüyoruz.

**Komutumuz tamamlandıktan sonra projemiz içindeki ```go.png``` adlı sertifikamızın blockchain üzerindeki referansını oluşturmakta**

* Bunun için öncelikle ``` node upload.mjs go.png "<name>" "<description>``` komutunu çalıştırmalıyız.
**name:** sertifikanın ismi
**description:** sertifikanın açıklaması

* İşlemden sonra bize ```https://bafybeietzr7c43wx7vqxqmvzp3pcyd7pgaiymrsrjmvuduykl4pknevdia.ipfs.dweb.link/go.png``` şeklinde bir çıktı gelecek. 

	Bu çıktıyı kopyalayalım

* Ardından **bb_NFT** klasörümüzün içindeki ```file.json``` dosyasının içindeki **image** kısmına kopyaladığımız bu kodu yapıştıralım

	**file.json** içindeki diğer **name** ve **description** alanlarını da sertifikamıza göre dolduralım

* Daha sonra tekrar terminal ekranına dönerek ``` node upload.mjs file.json "<name>" "<description>``` komutunu çalıştıralım ve tekrar **name** ve **description** alanlarını girerek komutu çalıştıralım
	
	Burdan çıkan çıktıyı kopyalayıp **8080** portunda çalışan uygulamamıza dönerek anasayfanın en altında yer alan **certificate** butonuna basalım

* Sayfada görünen input alanına kopyaladığımız çıktıyı yapıştırıp butona basalım ve **Metamask** üzerinden onaylayalım.
* Onay mesajı geldiğinde Metamask adresimizi kopyalayarak [Opensea](https://testnets.opensea.io/) üzerinden cüzdan adresimizi aratalım ve sertifikamızı görüntüleyelim.

### Artık Sertifikamız blockchain üzerinde NFT olarak saklanacak

## İşte Bu Kadar 🎉🥳