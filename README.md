# 5ire Full Node Kurma & Contrat Oluşturma Rehberi

![image](https://user-images.githubusercontent.com/76253089/209724364-5059536c-bce0-4f9c-af58-8ca73deae445.png)

Eğer mailiniz geldiyse bu rehberi kullanarak node kurup kontrat oluşturmaya başlayabilirsiniz. <br> Öncelikle OVPN kurulumundan başlayacağız sonrasında içine client dosyamızı atacağız ve mailinize gelen bağlantıları açıp cüzdan oluşturma, trasfer, swap gibi adımları yapacağız. Dikkatli okuyun bazı adımlar karışık, Başlayalım. Hangi adımda kaldıysanız ordan devam edin.

1. Gelen maildeki şifre ile OVPN Client Oluşturma.
2. OVPN kurulum ve oluşturulan Cliente Bağlama.
3. Cüzdan oluşturma & Swap & Transfer aşaması
4. 5ire'ı Metamaska Eklemek.
5. Node Kurma ve Validatör oluşturma aşaması.
6. Contrat oluşturma ve etkileşime geçme.



<details>

<summary> 
<h1> 1.) Gelen Maildeki Şifre ile OVPN Client Oluşturma. 
</summary> </h1>

Gelen Maildeki ilk linke tıklayalım ve rehberde verilen siteye giriş yapalım.

<img src="https://user-images.githubusercontent.com/76253089/209724502-e6241f31-69e1-4878-8f94-8dd3f49e9057.png" align="center" height="600" width="500" />    

Açılan sayfada Mailinizde verilen bilgileri girin ve giriş yapın. Ben daha önce yaptığım için sonraki aşamaları gösteremeyeceğim..

![Screenshot_3](https://user-images.githubusercontent.com/76253089/210077847-a74446e1-20af-423f-aca2-6d32c130de7a.png)

Client oluşturma tamamdır bir sonraki adıma geçin.
</details>

<details>

<summary> 
<h1> 2.) OVPN kurulum ve oluşturulan Cliente Bağlama. 
</summary> </h1>

[OVPN Indirme Linki](https://www.ovpn.com/en/guides#openvpn) Burdan indirip bilgisayarınıza kurun. <br>
Uygulamayı açın, açtıktan sonra küçültülmüş olarak açılacaktır. Aşağıdaki görselden sırasıyla işaretlediklerime basın ve oluşturduğunuz clienti OVPN içine aktarın ve bağlanın.

![image](https://user-images.githubusercontent.com/76253089/210079192-6d108d75-bf58-4455-ac4f-fbb895c9fba2.png)

Sonrasinda mailde verilen diğer link olan explorer sitesine giriş yapacağız (OVPN bağlantısı açık olmazsa Access Denied hatası alırsınız. Cliente bağlandığınıza emin olun.) <br>
[Explorer Linki](https://explorer.5ire.network/)

Cüzdan oluşturup kesinlikle not edin, vpn bağlantısını kestiğinizde cüzdan siliniyor mnemonicleri tekrar girmeniz gerekiyor. <br>
Sağdan wallet kısmına basıp Create new wallete basın.

![image](https://user-images.githubusercontent.com/76253089/210079969-704af0e1-3e76-418b-aaad-2083796f8c68.png)

Sonra swap ve transfer işlemleri yapın, Aynı işlemleri Metamask kısmında da yapmamız gerekiyor, önce explorer üzerinden yapalım. Adresime gönderim yapabilirsiniz. <br>
`EVM Chain Address: (Metamask)
0xcf42d1D77912240Ce805f102E6158eF25f91619a
`
<br>
`
Native Chain Address: (Explorerdeki)
5EDM8ZQaqdZiNsf4RP2qbZrTpgsRmswD3hRqs8tFQnHFnrAH
`
Şimdi Metamask kısmına geçelim önce Ağı Manuel olarak Metamaska eklememiz lazım alttaki bilgileri girin.
`
Network Name: 5ireChain
New RPC Url: https://chain-node.5ire.network
Chain ID: 997
Currency Symbol: 5ire
Explorer URL: https://explorer.5ire.network
`
</details>
