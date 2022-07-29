![image](https://user-images.githubusercontent.com/43322788/180246848-0ea0caa0-dd6a-445f-9887-0967b19b9aab.png)

### 3.1 Projenin Amacı ve Önemi

```
Tren istasyonları, otogarlar, şehir meydanları gibi yerlerde insanlar valizlerini terk
edebiliyorlar. Bu durum şehirlerin güvenliği için bir tehdit oluşturabilir. Üstelik valizlerin
kamera görüntüsünden insanlar tarafından takip edilmesi ise maliyetli bir süreçtir. Bu
çalışma İP kameraların bulunduğu şehir meydanlarında, otogarlarda bilgisayarlı görü
teknolojilerini kullanarak takibi ve tespitini yapmayı önermektedir.
```
### 3.2 Kaynak Araştırması

#### 3.2.1 “Detecting Abandoned Luggage Items in a Public Space” (Kevin Smith, 2006)

```
Bu çalışma eski bir çalışma olmasına rağmen yaklaşım benzerdir. Fakat bu çalışmada
yalnızca insanın valizi veya çantayı bırakma durumu ele alınmış. İnsan çantayı
bıraktıktan sonra etrafına iki daire çizilir. Bu çizilen dairelerin en dışta olanın dışına
geçildikten sonra bir süre tutulur. Bu süre 30 saniyeyi geçtiğinde alarm başlatılarak
tehdit unsuru olduğu kabul edilir.
```
#### 3.2.2 “Localized Detection of Abandoned Luggage” (Chang Jing-Ying, 2010)

```
Geçmiş yıllarda yetersiz kalan donanım gücü nedeniyle baş omuz maskesi kullanılarak
insan tespiti yapılmaya çalışmış. Bu çalışmada valizlerin birden fazla terk edilmesi
durumu için yetersiz kalmış. Fakat bu durumlar şuanda çalışmada ele alınmıştır.
```
### 3.3 Projenin Akış Şeması
```
![Adsız](https://user-images.githubusercontent.com/43322788/181806957-be6f98a2-7e5f-4116-b0f2-0c96d68a4b63.png)
```
## 4 Proje Mevcut Durum Değerlendirmesi

```
Çalışmada yalnızca bilgisayarlı görü kısmı ele alınmıştır. İlerleyen aşamalarda geliştirilen
sistem uygun uç cihaz seçilip, Nesnelerin Yapay Zekası(AİoT) projesine çevrilebilir.
Projede ele alınmış durumlara 4.1’inci başlıkta yer verilmiştir.
```
### 4.1 Projede Ele Alınmış Durumlar

#### 4.1.1 Durum 1 : İnsanın Bagajıyla Eşleştirilmesi
![image](https://user-images.githubusercontent.com/43322788/180248086-2579a43e-2ec7-460c-8996-f2480b936e08.png)

```
İnsan görüntüye girdiği andan itibaren valiziyle yeşil çizgiyle eşleşir, bu risk olmadığını
ifade eder.
```
#### 4.1.2 Durum 2 : İnsanın Bagajını Terk Etmesi
![image](https://user-images.githubusercontent.com/43322788/180248046-6caebaf5-a21b-4d9d-a474-636fcb082549.png)

```
Valizinden ayrılmaya başladığı süreçte kırmızı çizgiyle işaretlenir, bu riskli durumu ifade
eder.
```
#### 4.1.3 Durum 3 : Bagaj Sahibinin Yanına Başkalarının Gelmesi Durumu
![image](https://user-images.githubusercontent.com/43322788/180247974-654c0a63-99d5-4a5c-b6e4-677035ab43d2.png)

```
Valiz yalnızca onu kamera görüntüsünün içine getiren kişiyle eşlenir. Böylelikle valizin
kalabalık bir ortamda terk edildiği durumda başka insanlarla eşleştirilmemesi sağlanmış
olur.
```
### 5 Projenin Örnek Görüntüleri 
![mp4togif](https://user-images.githubusercontent.com/43322788/180884003-6b73fded-7c9d-435a-ab05-a6552b521362.gif?style=centerme)
```
Bütün durumları içeren örnek görüntüleri yukarıda ki gifte paylaşılmıştır.
```

