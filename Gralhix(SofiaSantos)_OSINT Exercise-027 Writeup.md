**Genel Bilgiler** :
Gralhix tarafından hazırlanan OSINT Ctf'i

**Kategori** :
OSINT [Kolay]Error Code: -101
Unable to connect to server. Server may be offline or you may not be connected to the internet.

**İpuçları** :
Yok

**Sorular** :

	1-)Konuşan kişinin isimi
	
	2-)Konuşanın yakasında ne giydiğini belirleyin
	
	3-)Konuşmanın fotoğrafını bulun
	
	

**Çözüm:**

Bu CTF Gralhix tarafından web sitesinde yayınlanıyor çözmek isteyen kişiler için CTF linki(https://gralhix.com/list-of-osint-exercises/osint-exercise-027/) elimizdeki veriler kısıtlı sadece bir fotoğrafa sahibiz. Bu fotoğrafı incelemek için yeni sekmede açtığımızda konuşmacının siyah bir ceket içinde beyaz gömlek ve açık mavi renkli kravat taktığını görebiliyoruz.

![osintexercise027.png](https://github.com/boryokusha/OSINT-Writeup/blob/main/osintexercise027.png)

Ekranda yansıtılan fotoğrafa baktığımızda ise ekranda büyük font ile yazılan "LECTURA EN MOVIMIENTO" yazsını görebiliriz. Diğer görebildiğimiz detayların arasında konuşmacının arkasında duran 3 bayrak ile ekranın üstünde yer alan sponsor ve etkinlikle alakalı kurum ve kuruluşların bilgilerini görebiliriz. Bayrakların önemi bizim için büyük çünkü etkinlikte en göze çarpan detaylar bunlar , bunlar ya konuşmayı düzenleyen kurumun ya da sponsorların bayrağı olması lazım bunların arasından "OEI" bayrağını rahatlıkla seçebiliyoruz. 

![lag.webp](https://github.com/boryokusha/OSINT-Writeup/blob/main/flag.webp)

Elimizde bulunan en güçlü veriyi kullanarak arama motorumuzda "LECTURA EN MOVIMIENTO en Lima" aramasını yapıyoruz. Görsellere tıkladığımız zaman karşımıza ilk veri olarak bu web sitesi çıkıyor.
![1.png](https://github.com/boryokusha/OSINT-Writeup/blob/main/1.png)

Web sitesine giriş yaptığımızda bu web sitesinin OEI(İbero-Amerikan Devletleri Örgütü) sitesi olduğunu anlıyoruz bu kurumu bayraktan ve ekrandan tanıyabiliriz. Bu bizim için güzel bir ipucudur çünkü etkinliğin web sitesinde konuşmacıları bulabiliriz. 
Sayfada aşağıya indiğimizde karşımıza bu bölüm geliyor.

![2.png](https://github.com/boryokusha/OSINT-Writeup/blob/main/2.png)

Yazının bu kısımından konuşmacının OEI Peru Direktörü Juan Carlos Ruiz
olduğunu ve konuşmanın bu kısımının projenin yürütülmesi sırasında gerçekleştirilecek faaliyetler hakkında olduğunu anlıyoruz.
En son olarak takılan rozet hakkında bilgi toplamamız lazım. Bu kısım için arama motorumuza "juan carlos ruiz" +"lectura en movimiento en lima" formatında bir arama yapıyoruz ve karşımıza bu ekran çıkıyor.

![3.png](https://github.com/boryokusha/OSINT-Writeup/blob/main/3.png)

Web sitesini açıp etkinlik tarihlerini karşılaştırdıktan sonra ise resmi büyüttüğümüzde takılan rozetin OEI rozeti olduğunu anlıyoruz.
