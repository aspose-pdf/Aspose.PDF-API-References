---
title: "SubPathContainer"
linktitle: "SubPathContainer"
second_title: "Aspose.PDF for Java API Referansı"
description: "Grafik öğeleri için bir kapsayıcı sınıfı temsil eder."
type: docs
weight: 10
url: /tr/java/com.aspose.pdf.vector.extraction/subpathcontainer/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.vector.extraction.SubPathContainer

**All Implemented Interfaces:**
com.aspose.pdf.engine.utils.clustering.hierarchicalagglomerativeclustering.IDistanceMetric< SubPathContainer >, Comparable < SubPathContainer >

```
public class SubPathContainer extends Object implements com.aspose.pdf.engine.utils.clustering.hierarchicalagglomerativeclustering.IDistanceMetric< SubPathContainer >, Comparable < SubPathContainer >
```

Grafik öğeleri için bir kapsayıcı sınıfı temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [SubPathContainer](#SubPathContainer--) | Grafik öğeler için bir kapsayıcı sınıfı örnekler. |
| [SubPathContainer](#SubPathContainer-com.aspose.pdf.vector.GraphicElement-) | Grafik öğeler için bir kapsayıcı sınıfı örnekler. |
| [SubPathContainer](#SubPathContainer-int-com.aspose.pdf.vector.GraphicElement-) | Grafik öğeler için bir kapsayıcı sınıfı örnekler. |
| [SubPathContainer](#SubPathContainer-int-com.aspose.pdf.vector.GraphicElement-com.aspose.pdf.Rectangle-) | Grafik öğeler için bir kapsayıcı sınıfı örnekler. |
| [SubPathContainer](#SubPathContainer-com.aspose.pdf.Rectangle-) | Grafik öğeler için bir kapsayıcı sınıfı örnekler. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [calculateDistance](#calculateDistance-com.aspose.pdf.vector.extraction.SubPathContainer-com.aspose.pdf.vector.extraction.SubPathContainer-) | İki kapsayıcı arasındaki mesafeyi hesaplar. |
| [compareTo](#compareTo-com.aspose.pdf.vector.extraction.SubPathContainer-) | Mevcut SubPathContainer nesnesini başka bir SubPathContainer nesnesiyle karşılaştırır ve mevcut nesnenin diğer nesneden daha küçük, eşit veya daha büyük olduğunu belirten bir tamsayı döndürür. Nesneler sayısal kimlikleri (ID) üzerinden karşılaştırılır. |
| [distanceTo](#distanceTo-com.aspose.pdf.vector.extraction.SubPathContainer-) | Bu kapsayıcı ile diğer kapsayıcı arasındaki mesafeyi hesaplar. |
| [getGraphElement](#getGraphElement--) | İçerilen grafik öğeyi alır. |
| [getId](#getId--) | SubPathContainer'ın kimliğini (Id) alır. Id, hata ayıklamayı kolaylaştırmak ve render sırasında öğeleri sıralamak için gereklidir. |
| [getRect](#getRect--) | İçerilen öğenin bir dikdörtgenini temsil eder. |
| [toString](#toString--) | {@code } |

### SubPathContainer {#SubPathContainer--}
```
public SubPathContainer()
```

Grafik öğeler için bir kapsayıcı sınıfı örnekler.

### SubPathContainer {#SubPathContainer-com.aspose.pdf.vector.GraphicElement-}
Grafik öğeler için bir kapsayıcı sınıfı örnekler.

### SubPathContainer {#SubPathContainer-int-com.aspose.pdf.vector.GraphicElement-}
Grafik öğeler için bir kapsayıcı sınıfı örnekler.

### SubPathContainer {#SubPathContainer-int-com.aspose.pdf.vector.GraphicElement-com.aspose.pdf.Rectangle-}
Grafik öğeler için bir kapsayıcı sınıfı örnekler.

### SubPathContainer {#SubPathContainer-com.aspose.pdf.Rectangle-}
Grafik öğeler için bir kapsayıcı sınıfı örnekler.

### calculateDistance {#calculateDistance-com.aspose.pdf.vector.extraction.SubPathContainer-com.aspose.pdf.vector.extraction.SubPathContainer-}
İki kapsayıcı arasındaki mesafeyi hesaplar.

### compareTo {#compareTo-com.aspose.pdf.vector.extraction.SubPathContainer-}
Mevcut SubPathContainer nesnesini başka bir SubPathContainer nesnesiyle karşılaştırır ve mevcut nesnenin diğer nesneden daha küçük, eşit veya daha büyük olduğunu belirten bir tamsayı döndürür. Nesneler sayısal kimlikleri (ID) üzerinden karşılaştırılır.

### distanceTo {#distanceTo-com.aspose.pdf.vector.extraction.SubPathContainer-}
Bu kapsayıcı ile diğer kapsayıcı arasındaki mesafeyi hesaplar.

### getGraphElement {#getGraphElement--}
```
public final GraphicElement getGraphElement()
```

İçerilen grafik öğeyi alır.

**Returns:**
GraphicElement örneği

### getId {#getId--}
```
public final int getId()
```

SubPathContainer'ın kimliğini (Id) alır. Id, hata ayıklamayı kolaylaştırmak ve render sırasında öğeleri sıralamak için gereklidir.

**Returns:**
int değer

### getRect {#getRect--}
```
public final Rectangle getRect()
```

İçerilen öğenin bir dikdörtgenini temsil eder.

**Returns:**
Dikdörtgen örneği

### toString {#toString--}
```
public String toString()
```

{@code }
