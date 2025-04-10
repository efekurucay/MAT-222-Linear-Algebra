## Doğrusal Denklemler

### Doğrusal Denklem Çözümleri,
Bir (doğrusal) denklemin çözümü, denklemi sağlayan belirli bir değerler topluluğudur.

Örneğin,` 2x + 5 = 11` denkleminde x=3 olur ve denklemin 'tek çözümü' budur. 
- `3a - 4b = 14` -- bu denklemde ise örnek olarak a=6, b=1 yani (6,1) bir çözümdür. Fakat tek çözüm olmayabilir. Bu denklem için, (22/3,2) de bir çözümdür. Aslında bu şekilde **sonsuz sayıda** çözüm barındırabilir.
	
### Doğrusal Denklem Sistemleri
Bazı durumlarda aynı anda 2 veya daha fazla denklemin çözümüyle ilgileniriz. 

1. `2a - b = 4`, `a + 3b =3 ` - 2 bilinmeyenli  2 denklem sistemi. 
2. `2a - b - c = 3 `, `a + 2b + 3c = -5 ` 3 bilinmeyenli 2 denklem sistemi. **'underdetermined'**
3. `2x + y = 5` , `-x + 4y = √3 `, `2x - 3y = 0` 2 bilinmeyenli 3 denklem sistemi.** 'overdetermined'**

Yani aslında denklem sisteminin çözülmesi için en az bilinmeyen sayısı kadar denklem gerekiyor. 

### Doğrusal Sistemlerin Kökleri

#### Örnek 1: Diyet Düzenleme

Bir laboratuvardaki tavşanlara, **Mix A**, **Mix B** ve **Mix C** olarak etiketlenmiş üç farklı besin türünden oluşan katı bir diyet verilmektedir. Bu karışımların makro besin değerleri (gram cinsinden) aşağıdaki tabloda gösterilmiştir:

|         | Karbonhidrat (g) | Protein (g) | Yağ (g) |
|---------|------------------|-------------|---------|
| **Mix A** | 3                | 1           | 1       |
| **Mix B** | 1                | 5           | 6       |
| **Mix C** | 12               | 4           | 0.5     |

Her tavşanın günlük olarak:
- 35 gram karbonhidrat,
- 28 gram protein,
- 27 gram yağ

alması gerekmektedir. Bu gereksinimleri karşılamak için her bir karışımdan ne kadar verileceğini hesaplamak amacıyla bir denklem sistemi kuracağız.

Varsayalım ki her tavşan:
- \( a \) birim **Mix A**,
- \( b \) birim **Mix B**,
- \( c \) birim **Mix C** alıyor olsun.

##### Denklem Sistemi

Tablodaki değerleri kullanarak aşağıdaki doğrusal denklemleri elde ederiz:

1. **Karbonhidrat denklemi**  
   \[3a + 1b + 12c = 35\]
2. **Protein denklemi**  
   \[a + 5b + 4c = 28 \]
3. **Yağ denklemi**   \[a + 6b + 0.5c = 27 ]

Bu üç denklem, \( a \), \( b \) ve \( c \) değerlerini bulmak için çözülmesi gereken doğrusal denklem sistemini oluşturur.

3a + b + 12c = 35 
a + 5b + 4c = 28 
2a + 6b + 0.5c = 27

**Soru:** Sadece bu üç besin türünü kullanarak, her türlü diyet ihtiyacını (farklı makro besin hedeflerini) karşılamak mümkün müdür?  

Bazı koşullarda kurulan denklem sistemlerinde pozitif olması gereken değerler negatif olabilir. Bu yüzden her zaman garanti değildir.

### Doğrusal Denklemler Sisteminin Çözümleri

#### Örnek denklem sistemi
(Doğrusal) bir sistemin çözümü, sistemdeki her denklemi sağlayan
değerlerin bir koleksiyonudur.

- `2x - y = 4`, `-x + 3y = 3` bu sisteme göre  
       -(5,6) ilk denklemin çözümü fakat ikinci denkleme uymuyor.
       -(1, 4/3) ise aynı şekilde 2. denklemi sağlıyor fakat 1. için uygun değil. 

- Denklemi çözdüğümüzde (3,2) değerlerinin iki denklemi de sağladığını görebiliriz. Bu değer, bu denklem için tek çözümdür.

#### Örnek denklem sistemi ( Sonsuz sayıda çözüm ) 

- `2x - y = 4`, `-4x + 2y = 8` denklem sisteminde görüldüğü üzere iki denklem de aynı. Çözümler yaptığımızda (1,2), (8,12) gibi değerlerin, (a, (2a-4)) , bu sistemi çözdüğünü göreceksiniz. Haliyle sonsuza kadar uzanan bir çözüm sayımız oluyor.

#### Örnek denklem sistemi ( Çözüm yok ) 

- `2x - y = 4 `, `6x - 3y = 9` bu sistemi çözmeye çalıştığımızda 2. denklemin de `2x - y = 3` e denk geldiğini görüyoruz. Yani aynı `2x - y` değeri hem 3'e, hem de 4'e karşılık geliyor. Bu da bu denklem sisteminin çözümü olmadığını bize gösteriyor.

### Eksik Belirlenmiş Sistemlerin Çözümleri (Underdetermined)

- Bu sistemlerin genellikle sonsuz sayıda çözümleri bulunur. 
- `x+y+z=2`, `x-2y+z=5` denklem sistemini incelersek,
       - `(a,-1,3-a) formundaki her üçlü çözümün bu sistemi sağladığını görüyoruz. 

- `2x-y+3z=5`, `-4x+2y-6z=8` denklem sisteminin ise çözümü yoktur. 

### Aşırı Belirlenmiş Sistemlerin Çözümleri (Overdetermined)

- Bu sistemlerin genellikle çözümü yoktur. 
- `2x+y=2`, `x-2y=5`, `-x+7y=-4` denklemini incelediğimizde tek bir ortak çözümü olmadığını göreceğiz. örneğin ilk iki denklemi çözersek `x=9/5 , y=8/5 `oluyor. fakat bu değerler 3. denklemi sağlamıyor. Fakat sağlayacak şekilde ayarladığımızda son denklem yerine `-x+7y=-13` denklemi olsaydı bu denklem sisteminin tek çözümü olurdu.

- Yani `3a - 4b = 14` gibi bir denklemin sonsuz çözümü olduğu gibi, `a=5 ve b=2` olan da sonsuz denklem yazılabilir gibi düşünebiliriz.

### Doğrusal Bir Sistemin Çözüm Sayısı

- Doğrusal bir sistem verildiğinde, çözümlerinin sayısı için 3 olası durum vardır:

      (i) Sistemin kendine özgü bir çözümü olabilir.
      (ii) Sistemin sonsuz sayıda çözümü olabilir.
      (iii) Sistemin çözümü olmayabilir.

- Sistemin en az bir çözümü varsa (durum (i) ve (ii)), bu sisteme **tutarlı sistem** denir.(**consistent**)
- Sistemin herhangi bir çözümü yoksa (durum (iii)), buna **tutarsız sistem** denir. (**inconsistent**)

- Bir doğrusal denklem sisteminin neden 2 veya daha fazla **sonlu **sayıda çözümü bulunamayacağını grafiklerini çizerek anlayabiliriz. Örneğin iki doğru düşünürsek,

        - Eğer doğrular bir noktada kesişiyorsa, sistemin tek bir çözümü vardır.
        - Eğer doğrular üst üste çakışıyorsa, sistemin sonsuz çözümü vardır.
        - Eğer doğrular paralel ve farklıysa, sistemin çözümü yoktur.

         -2 veya 3 gibi sonlu sayıda çözüm olamaz çünkü doğrusal denklemler doğrulara karşılık gelir ve iki doğru birden fazla ayrık noktada kesişemez.

Bu durum genel olarak daha yüksek boyutlar için de geçerlidir çünkü doğrusal sistemler doğrular, düzlemler veya daha yüksek boyutlu hiper düzlemler olarak yorumlanabilir ve bunların ya tek bir kesişim noktası olur, ya tamamen çakışır (sonsuz çözüm), ya da hiç kesişmez (çözüm yok).

### 2 Bilinmeyenli Sistemlerin Geometrik Yorumlanması

- ax +by = c biçimindeki her denklem, burada a,b, c bilinen sabitlerdir, analitik düzlemde bir çizgiye karşılık gelir.
- Bu, bilinmeyenli denklemli sistemlerin geometrik açıdan analiz edilmesini mümkün kılar.

![geometric.png](67b7315ca4f31-geometric.png)

---
### 3 Bilinmeyenli Sistemlerin Geometrik Yorumlanması
- Doğrusal denklemler sistemini 3 bilinmeyenli olarak düşündüğümüzde, bu sistemin her bir denklemi uzayda bir düzleme karşılık gelir. Üç düzlemin nasıl kesiştiğine bağlı olarak sistemin çözüm kümesi değişir.

#### 1. Tutarlı (Consistent) Sistemler
Bir sistemin **tutarlı** olması, en az bir çözümü olduğu anlamına gelir. Üç düzlem için şu olasılıklar vardır:

##### 1.1 Tek Çözüm (Unique Solution)
- Üç düzlem **tek bir noktada** kesişir.
- Sistem **tek bir çözüm** içerir.

##### 1.2 Sonsuz Çözüm - Doğru (Infinitely Many Solutions - Line)
- Üç düzlem **bir doğru boyunca** kesişir.
- Sistem **sonsuz sayıda çözüm** içerir.

##### 1.3 Sonsuz Çözüm - Çakışık Düzlemler (Infinitely Many Solutions - Coincident Planes)
- Üç düzlem tamamen **üst üste çakışıktır**.
- Sistem **sonsuz sayıda çözüm** içerir.

#### **2. Tutarsız (Inconsistent) Sistemler**
Bir sistemin **tutarsız** olması, hiç çözümü olmadığı anlamına gelir. 3 düzlem için şu olasılıklar vardır:

##### **2.1 Üç Düzlem Paralel (No Solution - Parallel Planes)**
- Üç düzlem birbirine **paraleldir** ve kesişmez.
- **Sistem çözümsüzdür.**

##### **2.2 İki Düzlem Paralel, Üçüncüsü Kesişmez (No Solution - Two Parallel Planes)**
- İki düzlem birbirine **paraleldir**, üçüncü düzlem bunları kesmez.
- **Sistem çözümsüzdür.**

##### **2.3 Üç Düzlem Kesişiyor Fakat Ortak Çözüm Yok (No Solution - Skew Intersections)**
- Her düzlem diğer **iki düzlemi bir doğru boyunca keser**, fakat bu doğrular aynı noktada kesişmez.
- **Sistem çözümsüzdür.**

#### **Sonuç**
- **Tutarlı sistemler** en az bir çözüme sahiptir (tekil veya sonsuz).
- **Tutarsız sistemler** çözüme sahip değildir.
- Sistemlerin geometrik yorumları, doğrusal cebirin temel kavramları arasında yer alır ve çözümlerin varlığını anlamada önemli bir rol oynar.
![consistent systems](67c05b596d0f4-Ekran-g--r--nt--s---2025-02-27-153057.png)

![inconsistent systems](67c05b412f8fb-Ekran-g--r--nt--s---2025-02-27-153119.png)

---
---
--- 
# Matrisler

Lineer sistemleri sistematik bir şekilde ele almak için yeni araçlar tanımlıyoruz.


## Matris Nedir?

**Matris**, sayıların dikdörtgensel bir düzen içinde yazıldığı bir yapıdır. (Bu derste aksi belirtilmedikçe "sayı" ile reel sayılar kastedilmektedir.)

## Matris Örnekleri

Bir matrisin kaç satır ve kaç sütundan oluştuğu onun boyutunu belirler. Genel olarak, bir matris **m × n** boyutuna sahiptir. Burada:

- **m**, satır sayısını ifade eder.
- **n**, sütun sayısını ifade eder.

### Örnek Matrisler

1. **Matris A**:

   \[
   A =
   \begin{bmatrix}
   1 & 0 & \pi \\
   \frac{\sqrt{2}}{5} & -\frac{2}{7} & 110
   \end{bmatrix}
   \]
   - **Boyut**: 2 satır × 3 sütun (**2 × 3** matrisi)
   - **Eleman (Entry)**: Matris içindeki her sayı bir elemandır ve A toplam 6 elemana sahiptir.
   - **Gösterim**: Matrisler köşeli parantez \([ ]\) ya da yuvarlak parantez \(( )\) ile gösterilebilir.


2. **Matris B**:

   \[
   B =
   \begin{bmatrix}
   1 & e \\
   1 & \sin(0.5)
   \end{bmatrix}
   \]

   - **Boyut**: 2 × 2 matrisi (**2 satır, 2 sütun**)
   - **Kare Matris**: Satır ve sütun sayısı eşitse, bu tür matrislere **kare matris** denir. Burada \( B \) kare bir matristir.

---

✅ **Özet:**  
- Matrisler sayıların tablosal düzenidir.  
- Boyutu **m × n** olup, satır ve sütun sayısıyla belirlenir.  
- Kare matrisler **m = n** olan matrislerdir.
