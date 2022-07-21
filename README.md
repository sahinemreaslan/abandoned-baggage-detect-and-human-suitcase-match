![image](https://user-images.githubusercontent.com/43322788/180246848-0ea0caa0-dd6a-445f-9887-0967b19b9aab.png = 400x400)

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
## 4 Proje Mevcut Durum Değerlendirmesi

```
Çalışmada yalnızca bilgisayarlı görü kısmı ele alınmıştır. İlerleyen aşamalarda geliştirilen
sistem uygun uç cihaz seçilip, Nesnelerin Yapay Zekası(AİoT) projesine çevrilebilir.
Projede ele alınmış durumlara 4.1’inci başlıkta yer verilmiştir.
```
### 4.1 Projede Ele Alınmış Durumlar

#### 4.1.1 Durum 1 : İnsanın Bagajıyla Eşleştirilmesi

```
İnsan görüntüye girdiği andan itibaren valiziyle yeşil çizgiyle eşleşir, bu risk olmadığını
ifade eder.
```
#### 4.1.2 Durum 2 : İnsanın Bagajını Terk Etmesi

```
Valizinden ayrılmaya başladığı süreçte kırmızı çizgiyle işaretlenir, bu riskli durumu ifade
eder.
```
#### 4.1.3 Durum 3 : Bagaj Sahibinin Yanına Başkalarının Gelmesi Durumu

```
Valiz yalnızca onu kamera görüntüsünün içine getiren kişiyle eşlenir. Böylelikle valizin
kalabalık bir ortamda terk edildiği durumda başka insanlarla eşleştirilmemesi sağlanmış
olur.
```
