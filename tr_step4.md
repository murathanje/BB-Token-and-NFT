## Kurulum

**Projemize başlamdan önce projemizde blockchain etkileşimi için kullanacağımız Metamask için kurulumları yapmamız gerekiyor.**

### 1-  Metamask Kurulumu
[![Metamask](https://media.giphy.com/media/doXBzUFJRxpaUbuaqz/giphy.gif)]()


İlk olarak bir [Metamask](https://chromewebstore.google.com/detail/metamask/nkbihfbeogaeaoehlefnkodbefgpgknn?hl=tr) cüzdanına ihtiyacımız  var . ![Metamask](https://lh3.googleusercontent.com/QW0gZ3yugzXDvTANa5-cc1EpabQ2MGnl6enW11O6kIerEaBQGOhgyUOvhRedndD9io8RJMmJZfIXq1rMxUsFHS2Ttw=s20)
Bu [linkten](https://chromewebstore.google.com/detail/metamask/nkbihfbeogaeaoehlefnkodbefgpgknn?hl=tr) detaylı kurulumunu izleyebilirsinz.

Daha sonra ağımızı **Sepolia** ağına geçirelim. (Sepolia Ethereum ağının testnetidir.)

Ardından BB tokenımızı kullanmak ve takip etmek için BB tokenımızı cüzdanımıza [ekleyelim](https://www.youtube.com/watch?v=2dCsY8dFak8).


####   Token Sözleşme adresi: ```0x217151857F674683D773Ff9452BBe1C018e372c2```





### 2 - Docker Pull

Sırada projemizi Docker Hub üzerinden çekme işlemi var. Bu sayede Docker üzerinde önceden oluşturulmuş projemizi localimize çekip ayağa kaldırabileceğiz.

Öncelikle projemizi çekiyoruz:
```docker pull kaganje/bb:latest ```

Ardından docker üzerinden çekilen projemizi ayağa kaldırıyoruz:
```docker run -p 8080:8080 kaganje/bb:latest```

**Evet!! Projemiz şuan ayakta 🥳🎉**

Şimdi Bulut Bilişmciler üzerindeki port kısmından **8080** portuna gitmelisin.