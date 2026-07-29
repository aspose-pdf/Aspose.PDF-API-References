---
title: "Rectangle"
linktitle: "Rectangle"
second_title: "Aspose.PDF for Java API Referansı"
description: "Dikdörtgeni temsil eden sınıf."
type: docs
weight: 4100
url: /tr/java/com.aspose.pdf/rectangle/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Rectangle

**All Implemented Interfaces:**
Cloneable, Comparable < Object >

```
public final class Rectangle extends Object implements Comparable < Object >, Cloneable
```

Dikdörtgeni temsil eden sınıf.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Rectangle](#Rectangle-double-double-double-double-) | Rectangle yapıcısı. |
| [Rectangle](#Rectangle-double-double-double-double-boolean-) | Rectangle yapıcısı. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [_Intersect](#Z:Z_Intersect-com.aspose.pdf.Rectangle-) | Dikdörtgenlerin kesişmesi. Eski yöntem. Lütfen bunun yerine Intersect'i kullanın. |
| [center](#center--) | Dikdörtgenin merkezinin koordinatlarını döndürür. |
| [clone](#clone--) | Rectangle nesnesini klonlar. |
| [compareTo](#compareTo-java.lang.Object-) | CompareTo |
| [contains](#contains-com.aspose.pdf.Point-) | Verilen noktanın dikdörtgenin içinde olup olmadığını belirler. |
| [contains](#contains-com.aspose.pdf.Point-boolean-) | Verilen noktanın dikdörtgenin içinde olup olmadığını belirler. |
| [containsLine](#containsLine-double-double-double-double-) | Dikdörtgenin iki nokta ile temsil edilen bir çizgiyi içerip içermediğini belirler. |
| [containsPoint](#containsPoint-double-double-) | Verilen noktanın dikdörtgen içinde bulunup bulunmadığını belirler. |
| [deepClone](#deepClone--) | Rectangle nesnesini klonlar. |
| [equals](#equals-java.lang.Object-) | Dikdörtgenlerin eşit olup olmadığını kontrol eder, yani aynı konuma ve boyutlara sahip olup olmadığını. |
| [fromRect](#fromRect-java.awt.Rectangle-) | Verilen System.Drawing.Rectangle örneğinden yeni bir dikdörtgen başlatır. |
| [fromRect](#fromRect-java.awt.geom.Rectangle2D.Float-) | Verilen System.Drawing.Rectangle örneğinden yeni bir dikdörtgen başlatır. |
| [fromRectInternal](#fromRectInternal-com.aspose.ms.System.Drawing.RectangleF-) |  |
| [getArea](#getArea--) | Dikdörtgenin alanını hesaplar. |
| [getEmpty](#getEmpty--) | Boş dikdörtgeni alır. |
| [getHeight](#getHeight--) | Dikdörtgenin yüksekliğini al. |
| [getLLX](#getLLX--) | Alt-sol köşenin X koordinatını alır. |
| [getLLY](#getLLY--) | Alt-sol köşenin Y koordinatını alır. |
| [getTrivial](#getTrivial--) | Sıfır konum ve boyuta sahip basit bir dikdörtgen başlatır. |
| [getURX](#getURX--) | Üst-sağ köşenin X koordinatını alır. |
| [getURY](#getURY--) | Üst-sağ köşenin Y koordinatını alır. |
| [getWidth](#getWidth--) | Dikdörtgenin genişliğini al. |
| [hashCode](#hashCode--) | Objenin bir hash kodu değerini döndürür. Bu yöntem, {@link java.util.HashMap} gibi hash tablolarının faydası için desteklenir. <p> {@code hashCode} metodunun genel sözleşmesi şudur: <ul> <li>Bir Java uygulamasının çalışması sırasında aynı nesne üzerinde birden fazla kez çağrıldığında, {@code hashCode} yöntemi nesne üzerindeki {@code equals} karşılaştırmalarında kullanılan hiçbir bilgi değiştirilmediği sürece aynı tam sayıyı tutarlı bir şekilde döndürmelidir. Bu tam sayı, bir uygulamanın bir çalıştırmasından diğerine aynı kalmak zorunda değildir. <li>Eğer iki nesne {@code equals(Object)} metoduna göre eşitse, her iki nesne üzerinde {@code hashCode} metodunun çağrılması aynı tam sayı sonucunu üretmelidir. <li>{@link java.lang.Object#equals(java.lang.Object)} metoduna göre iki nesne eşit değilse, her iki nesne üzerinde {@code hashCode} metodunun çağrılması farklı tam sayı sonuçları üretmesi <em>gerekmemektedir</em>. Ancak, programcı eşit olmayan nesneler için farklı tam sayı sonuçları üretmenin hash tablolarının performansını artırabileceğinin farkında olmalıdır. </ul> <p> Makul ölçüde pratik olduğu sürece, {@code Object} sınıfı tarafından tanımlanan hashCode yöntemi farklı nesneler için farklı tam sayılar döndürür. (Bu genellikle nesnenin iç adresini bir tam sayıya dönüştürerek uygulanır, ancak bu uygulama tekniği Java<span style="font-size:70%"><sup>TM</sup></span> programlama dili tarafından zorunlu kılınmaz.) |
| [intersect](#intersect-com.aspose.pdf.Rectangle-) | Dikdörtgenlerin kesişir. |
| [isEmpty](#isEmpty--) | Dikdörtgenin boş olup olmadığını kontrol eder. |
| [isInclude](#isInclude-com.aspose.pdf.Rectangle-double-) | Bu dikdörtgenin başka bir dikdörtgeni tamamen kapsayıp kapsamadığını kontrol eder. Yani başka bir dikdörtgenin tamamen bu dikdörtgenin içinde olup olmadığını. IsIntersect yöntemiyle farkı, IsIntersect'in kısmen kesişen dikdörtgenler için doğru döndürmesi, ancak IsInclude'un yanlış döndürmesidir. |
| [isIntersect](#isIntersect-com.aspose.pdf.Rectangle-) | Bu dikdörtgenin diğer dikdörtgenle kesişip kesişmediğini belirler. |
| [isPoint](#isPoint--) | Dikdörtgenin bir nokta olup olmadığını kontrol eder, yani LLX URX'e ve LLY URY'e eşittir. |
| [isTrivial](#isTrivial--) | Dikdörtgenin önemsiz olup olmadığını kontrol eder, yani sıfır boyuta ve konuma sahiptir. |
| [join](#join-com.aspose.pdf.Rectangle-) | Dikdörtgenleri birleştirir. |
| [moveBy](#moveBy-double-double-) | Dikdörtgeni belirtilen delta değerleriyle kaydırır. |
| [nearEquals](#nearEquals-com.aspose.pdf.Rectangle-double-) | Dikdörtgenlerin yakın eşit olup olmadığını kontrol eder, yani (delta kadar) benzer konum ve boyutlara sahiptir. |
| [parse](#parse-java.lang.String-) | Dizeyi ayrıştırmayı deneyip içinden dikdörtgen bileşenleri llx, lly, urx, ury çıkarır. |
| [rotate](#rotate-com.aspose.pdf.Rotation-) | Dikdörtgeni belirtilen açıyla döndürür. |
| [rotateAngle](#rotateAngle-int-) | Dikdörtgeni belirtilen açıyla döndürür. |
| [setLLX](#setLLX-double-) | Alt sol köşenin X koordinatını ayarlar. |
| [setLLY](#setLLY-double-) | Alt sol köşenin Y koordinatını ayarlar. |
| [setURX](#setURX-double-) | Üst sağ köşenin X koordinatını ayarlar. |
| [setURY](#setURY-double-) | Üst sağ köşenin Y koordinatını ayarlar. |
| [toArray](#toArray-com.aspose.pdf.engine.data.ITrailerable-) |  |
| [toPoints](#toPoints--) | Dikdörtgeni nokta dizisine ("QuadPoints") dönüştürür. |
| [toRect](#toRect--) | Dikdörtgeni System.Drawing.Rectangle örneğine dönüştürür. Ondalıklı konum ve boyutlar kırpılır. |
| [toString](#toString--) | Dikdörtgenin dize temsili alır. |

### Rectangle {#Rectangle-double-double-double-double-}
```
public Rectangle(double llx, double lly, double urx, double ury)
```

Rectangle yapıcısı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| llx |  | Alt sol köşenin X'i. |
| lly |  | Alt sol köşenin Y'si. |
| urx |  | Üst sağ köşenin X'i. |
| ury |  | Üst sağ köşenin Y'si. |

### Rectangle {#Rectangle-double-double-double-double-boolean-}
```
public Rectangle(double llx, double lly, double urx, double ury, boolean normalizeCoordinates)
```

Rectangle yapıcısı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| llx |  | Alt sol köşenin X'i. |
| lly |  | Alt sol köşenin Y'si. |
| urx |  | Üst sağ köşenin X'i. |
| ury |  | Üst sağ köşenin Y'si. |
| normalizeCoordinates |  | Dikdörtgenin koordinatlarını normalleştir. |

### _Intersect {#Z:Z_Intersect-com.aspose.pdf.Rectangle-}
Dikdörtgenlerin kesişmesi. Eski yöntem. Lütfen bunun yerine Intersect'i kullanın.

### center {#center--}
```
public Point center()
```

Dikdörtgenin merkezinin koordinatlarını döndürür.

**Returns:**
Dikdörtgenin merkezindeki nokta.

### clone {#clone--}
```
public Rectangle clone()
```

Rectangle nesnesini klonlar.

**Returns:**
Nesneyi klonla.

### compareTo {#compareTo-java.lang.Object-}
CompareTo

### contains {#contains-com.aspose.pdf.Point-}
Verilen noktanın dikdörtgenin içinde olup olmadığını belirler.

### contains {#contains-com.aspose.pdf.Point-boolean-}
Verilen noktanın dikdörtgenin içinde olup olmadığını belirler.

### containsLine {#containsLine-double-double-double-double-}
```
public final boolean containsLine(double x1, double y1, double x2, double y2)
```

Dikdörtgenin iki nokta ile temsil edilen bir çizgiyi içerip içermediğini belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x1 |  | Çizginin başlangıç noktasının X koordinatı. |
| y1 |  | Çizginin başlangıç noktasının Y koordinatı. |
| x2 |  | Çizginin bitiş noktasının X koordinatı. |
| y2 |  | Çizginin bitiş noktasının Y koordinatı. |

**Returns:**
{@code true} eğer dikdörtgen çizgiyi içeriyorsa; aksi takdirde {@code false}.

### containsPoint {#containsPoint-double-double-}
```
public final boolean containsPoint(double x, double y)
```

Verilen noktanın dikdörtgen içinde bulunup bulunmadığını belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x |  | Noktanın X koordinatı. |
| y |  | Noktanın Y koordinatı. |

**Returns:**
{@code true} eğer nokta dikdörtgen içinde ise; aksi takdirde {@code false}.

### deepClone {#deepClone--}
```
public Rectangle deepClone()
```

Rectangle nesnesini klonlar.

**Returns:**
Nesneyi klonla.

### equals {#equals-java.lang.Object-}
Dikdörtgenlerin eşit olup olmadığını kontrol eder, yani aynı konuma ve boyutlara sahip olup olmadığını.

### fromRect {#fromRect-java.awt.Rectangle-}
Verilen System.Drawing.Rectangle örneğinden yeni bir dikdörtgen başlatır.

### fromRect {#fromRect-java.awt.geom.Rectangle2D.Float-}
Verilen System.Drawing.Rectangle örneğinden yeni bir dikdörtgen başlatır.

### fromRectInternal {#fromRectInternal-com.aspose.ms.System.Drawing.RectangleF-}


### getArea {#getArea--}
```
public final double getArea()
```

Dikdörtgenin alanını hesaplar.

**Returns:**
Genişlik ve yüksekliğin çarpılmasıyla hesaplanan, dikdörtgenin double tipindeki alanı.

### getEmpty {#getEmpty--}
```
public static Rectangle getEmpty()
```

Boş dikdörtgeni alır.

**Returns:**
yeni Rectangle nesnesi

### getHeight {#getHeight--}
```
public double getHeight()
```

Dikdörtgenin yüksekliğini al.

**Returns:**
double değer

### getLLX {#getLLX--}
```
public double getLLX()
```

Alt-sol köşenin X koordinatını alır.

**Returns:**
double değer

### getLLY {#getLLY--}
```
public double getLLY()
```

Alt-sol köşenin Y koordinatını alır.

**Returns:**
double değer

### getTrivial {#getTrivial--}
```
public static Rectangle getTrivial()
```

Sıfır konum ve boyuta sahip basit bir dikdörtgen başlatır.

**Returns:**
yeni Rectangle nesnesi

### getURX {#getURX--}
```
public double getURX()
```

Üst-sağ köşenin X koordinatını alır.

**Returns:**
double değer

### getURY {#getURY--}
```
public double getURY()
```

Üst-sağ köşenin Y koordinatını alır.

**Returns:**
double değer

### getWidth {#getWidth--}
```
public double getWidth()
```

Dikdörtgenin genişliğini al.

**Returns:**
double değer

### hashCode {#hashCode--}
```
public int hashCode()
```

Objenin bir hash kodu değerini döndürür. Bu yöntem, {@link java.util.HashMap} gibi hash tablolarının faydası için desteklenir. <p> {@code hashCode} metodunun genel sözleşmesi şudur: <ul> <li>Bir Java uygulamasının çalışması sırasında aynı nesne üzerinde birden fazla kez çağrıldığında, {@code hashCode} yöntemi nesne üzerindeki {@code equals} karşılaştırmalarında kullanılan hiçbir bilgi değiştirilmediği sürece aynı tam sayıyı tutarlı bir şekilde döndürmelidir. Bu tam sayı, bir uygulamanın bir çalıştırmasından diğerine aynı kalmak zorunda değildir. <li>Eğer iki nesne {@code equals(Object)} metoduna göre eşitse, her iki nesne üzerinde {@code hashCode} metodunun çağrılması aynı tam sayı sonucunu üretmelidir. <li>{@link java.lang.Object#equals(java.lang.Object)} metoduna göre iki nesne eşit değilse, her iki nesne üzerinde {@code hashCode} metodunun çağrılması farklı tam sayı sonuçları üretmesi <em>gerekmemektedir</em>. Ancak, programcı eşit olmayan nesneler için farklı tam sayı sonuçları üretmenin hash tablolarının performansını artırabileceğinin farkında olmalıdır. </ul> <p> Makul ölçüde pratik olduğu sürece, {@code Object} sınıfı tarafından tanımlanan hashCode yöntemi farklı nesneler için farklı tam sayılar döndürür. (Bu genellikle nesnenin iç adresini bir tam sayıya dönüştürerek uygulanır, ancak bu uygulama tekniği Java<span style="font-size:70%"><sup>TM</sup></span> programlama dili tarafından zorunlu kılınmaz.)

**Returns:**
bu nesne için bir hash kodu değeri. @see java.lang.Object#equals(java.lang.Object) @see java.lang.System#identityHashCode

### intersect {#intersect-com.aspose.pdf.Rectangle-}
Dikdörtgenlerin kesişir.

### isEmpty {#isEmpty--}
```
public boolean isEmpty()
```

Dikdörtgenin boş olup olmadığını kontrol eder.

**Returns:**
boolean değer

### isInclude {#isInclude-com.aspose.pdf.Rectangle-double-}
Bu dikdörtgenin başka bir dikdörtgeni tamamen kapsayıp kapsamadığını kontrol eder. Yani başka bir dikdörtgenin tamamen bu dikdörtgenin içinde olup olmadığını. IsIntersect yöntemiyle farkı, IsIntersect'in kısmen kesişen dikdörtgenler için doğru döndürmesi, ancak IsInclude'un yanlış döndürmesidir.

### isIntersect {#isIntersect-com.aspose.pdf.Rectangle-}
Bu dikdörtgenin diğer dikdörtgenle kesişip kesişmediğini belirler.

### isPoint {#isPoint--}
```
public boolean isPoint()
```

Dikdörtgenin bir nokta olup olmadığını kontrol eder, yani LLX URX'e ve LLY URY'e eşittir.

**Returns:**
boolean değer

### isTrivial {#isTrivial--}
```
public boolean isTrivial()
```

Dikdörtgenin önemsiz olup olmadığını kontrol eder, yani sıfır boyuta ve konuma sahiptir.

**Returns:**
boolean değer

### join {#join-com.aspose.pdf.Rectangle-}
Dikdörtgenleri birleştirir.

### moveBy {#moveBy-double-double-}
```
public final void moveBy(double dx, double dy)
```

Dikdörtgeni belirtilen delta değerleriyle kaydırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dx |  | X eksenine göre kaydırma değeri. |
| dy |  | Y eksenine göre kaydırma değeri. |

### nearEquals {#nearEquals-com.aspose.pdf.Rectangle-double-}
Dikdörtgenlerin yakın eşit olup olmadığını kontrol eder, yani (delta kadar) benzer konum ve boyutlara sahiptir.

### parse {#parse-java.lang.String-}
Dizeyi ayrıştırmayı deneyip içinden dikdörtgen bileşenleri llx, lly, urx, ury çıkarır.

### rotate {#rotate-com.aspose.pdf.Rotation-}
Dikdörtgeni belirtilen açıyla döndürür.

### rotateAngle {#rotateAngle-int-}
```
public void rotateAngle(int angle)
```

Dikdörtgeni belirtilen açıyla döndürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| açı |  | 0 ile 360 derece arasında dönüş açısı. |

### setLLX {#setLLX-double-}
```
public void setLLX(double value)
```

Alt sol köşenin X koordinatını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | double değer |

### setLLY {#setLLY-double-}
```
public void setLLY(double value)
```

Alt sol köşenin Y koordinatını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | double değer |

### setURX {#setURX-double-}
```
public void setURX(double value)
```

Üst sağ köşenin X koordinatını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | double değer |

### setURY {#setURY-double-}
```
public void setURY(double value)
```

Üst sağ köşenin Y koordinatını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | double değer |

### toArray {#toArray-com.aspose.pdf.engine.data.ITrailerable-}


### toPoints {#toPoints--}
```
public final Point [] toPoints()
```

Dikdörtgeni nokta dizisine ("QuadPoints") dönüştürür.

**Returns:**
Nokta dizisi.

### toRect {#toRect--}
```
public Rectangle toRect()
```

Dikdörtgeni System.Drawing.Rectangle örneğine dönüştürür. Ondalıklı konum ve boyutlar kırpılır.

**Returns:**
Dönüşüm sonucu.

### toString {#toString--}
```
public String toString()
```

Dikdörtgenin dize temsili alır.

**Returns:**
Dize llx,lly,urx,ury biçimindedir.
