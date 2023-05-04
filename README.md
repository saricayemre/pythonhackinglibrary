# Python Hacking Kütüphaneleri

![](https://miro.medium.com/v2/resize:fit:720/format:webp/1*r6LIlBGuP9JPreOdwfRRJg.jpeg)

Python Hacking Kütüphaneleri

Herkese merhaba bu yazımda Python’un Siber Güvenlik için en çok kullanılan kütüphanelerini tanıtacağım. Bu yazıyı okurken Python’un “Hello Word” den çok farklı olduğunu, elimizin altında nasıl bir güç yattığına hep birlikte şahit olacağız. Python Etik Hack dediğimiz olay için oldukça uygun bir dildir. Bu yüzdendir ki siber güvenlik ve uygulama geliştiriciler için sıklıkla kullanılmaktadır. Giriş kısmını biraz kısa tutalım ve asıl konumuza gelelim. :)

## 1-) Requests

![](https://miro.medium.com/v2/resize:fit:720/format:webp/1*wPQnFNEyACFMlPdNAz-ZTA.png)

Requests kelime anlamı olarak istekler, talepler anlamına gelir. Bu kütüphane ile web siteleri ve sunucular üzerinden isteklerinizi gönderebilir ve geri dönen yanıta karşılık olarak sızma saldırısı veya bilgi toplama işlemleri için stratejiler geliştirebilirsiniz. Requests ile HTTP isteklerini yapacağımız söyledik. Peki bu isteklerin özel adları var mıdır? Elbette… Bu modül ile get, post, put, delete gibi istekleri gönderebilirsiniz. Buna ek olarak, parametre belirterek istek göndermek mümkündür.

'pip install requests'


## 2-) Scapy

![](https://miro.medium.com/v2/resize:fit:720/format:webp/1*Alc7ochnvThy5I-nE0iw2A.png)

Scapy ağlar için oluşturulmuş özel paketler üretmeye yarayan bir python modülüdür. Ağ tarama ve analiz işlemlerini gerçekleştirebiliriz. Scapy ağları tarayabilir ve saldırılabilir araçlar yazmamıza olanak sağlar. Yapabileceğimiza saldırı türleri şu şekildedir. ARP Spoofing, MITM, Sniffing, Ağ dinleme, Paket gönderme gibi işlemleri yapabiliriz.

## 3-) IMpacket

![](https://miro.medium.com/v2/resize:fit:720/format:webp/1*xCNp9chr77NA450XaU_mCQ.png)

Impacket, ağ protokolleri ile çalışmak için kullanılan bir kütüphanedir. TCP, UDP, IP, ICMP, IGMP, Kimlik doğrulamaları, aktarım protokolleri ile doğrudan uğraşabilir ve işlemler gerçekleştirebiliriz.

## 4-) Cryptography

![](https://miro.medium.com/v2/resize:fit:720/format:webp/1*eOvLySiDDjYJdugTR-tTHA.png)

Cryptography kütüphanesi, kriptografik işlemler yapabileceğimiz bir python kütüphanesidir. Simetrik-asimetrik şifreleme, anahtar üretme, kriptoloji algoritmalarını yapılandırma gibi işlemleri yaparız. Ağ güvenliği ile uğraşan kişiler sıklıkla bu tür işlerle ilgilenmektedir. Dolayısıyla bu kütüphane iş kolaylaştırıcı bir kütüphanedir.

## 5-) NMap

![](https://miro.medium.com/v2/resize:fit:720/format:webp/1*aMHv392crE94YxxHdgsjLA.png)

Nmap kütüphanesi. Şüphesiz hack dünyası için geliştirilmiş en iyi programlardan biri NMap’tır. Nmap ile birçok işlem gerçekleştirebiliriz. Python için de bir NMap modülü üretilmiştir ve aktif olarak kullanılmaktadır. Uygulama geliştiriciler NMap’ın bu eşsiz yönünü python ile kendi projelerine dahil edebiliyorlar. NMap kütüphanesi ile en temel haliyle “Ağ Analizi” yapabiliriz. Bunun hakkında birçok bilgi vermek mümkündür fakat kütüphane tanıtımında bu kadarıyla yetinmeyi tercih ediyorum. Detaylı anlatımını başka bir yazımda anlatacağım.

Benim sıklıkla kullandığım kütüphaneler bunlar. İlerleyen dönemlerde daha fazla kütüphane ile tanışır ve öğrenirsem mutlaka 2.kısım olarak yayınlayacağım. Sağlıcakla..
