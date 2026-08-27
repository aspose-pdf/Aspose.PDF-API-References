---
title: "GraphicElement"
linktitle: "GraphicElement"
second_title: "Aspose.PDF for Java API Referansı"
description: "Sayfadaki grafik nesnesi için temel sınıfı temsil eder."
type: docs
weight: 10
url: /tr/java/com.aspose.pdf.vector/graphicelement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.vector.GraphicElement

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable

```
public abstract class GraphicElement extends Object implements com.aspose.ms.System.IDisposable
```

Sayfadaki grafik nesnesi için temel sınıfı temsil eder.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [addOnPage](#addOnPage-com.aspose.pdf.Page-) | Sayfaya mevcut öğeyi ekler. Eklenmesi gereken birçok öğe varsa Page#addGraphics(GraphicElementCollection,Rectangle) kullanmak daha iyidir. |
| [dispose](#dispose--) | {@link GraphicElement} sınıfı tarafından kullanılan tüm kaynakları serbest bırakır. |
| [getMatrix](#getMatrix--) | Grafik öğesi matrisini alır. Matris, öğe oluşturulduğunda ayarlanır. SetPosition() çağrıldığında değişir. |
| [getOperators](#getOperators--) | Öğeyi temsil eden operatörlerin bir koleksiyonunu alır. |
| [getParent](#getParent--) | Öğenin bulunduğu mevcut {@link XFormPlacement} öğesini alır. |
| [getPosition](#getPosition--) | Mevcut koordinat uzayındaki konumu alır veya ayarlar. Parent #getParent/#setParent(XFormPlacement) null değilse, öğenin xForm koordinat uzayı vardır. |
| [getRectangle](#getRectangle--) | {@link GraphicElement} öğesinin sınırlayıcı dikdörtgenini alır. |
| [getSourcePage](#getSourcePage--) | Grafik öğesinin çıkarıldığı sayfayı alır. |
| [remove](#remove--) | Mevcut öğeyi sayfadan kaldırır. Kaldırılacak çok sayıda öğe varsa, Page#deleteGraphics(GraphicElementCollection) kullanmak daha iyidir. |
| [saveToSvg](#saveToSvg--) | Öğeyi tek bir SVG görüntüsüne dönüştürür. |
| [saveToSvg](#saveToSvg-java.lang.String-) | Öğeyi tek bir SVG görüntüsüne dönüştürür. |
| [setPosition](#setPosition-com.aspose.pdf.Point-) | Mevcut koordinat uzayındaki konumu alır veya ayarlar. Parent #getParent/#setParent(XFormPlacement) null değilse, öğenin xForm koordinat uzayı vardır. |

### addOnPage {#addOnPage-com.aspose.pdf.Page-}
Sayfaya mevcut öğeyi ekler. Eklenmesi gereken birçok öğe varsa Page#addGraphics(GraphicElementCollection,Rectangle) kullanmak daha iyidir.

### dispose {#dispose--}
```
public final void dispose()
```

{@link GraphicElement} sınıfı tarafından kullanılan tüm kaynakları serbest bırakır.

### getMatrix {#getMatrix--}
```
public final Matrix getMatrix()
```

Grafik öğesi matrisini alır. Matris, öğe oluşturulduğunda ayarlanır. SetPosition() çağrıldığında değişir.

**Returns:**
Matris örneği

### getOperators {#getOperators--}
```
public final List < Operator > getOperators()
```

Öğeyi temsil eden operatörlerin bir koleksiyonunu alır.

**Returns:**
Operatör örneklerinin listesi

### getParent {#getParent--}
```
public final XFormPlacement getParent()
```

Öğenin bulunduğu mevcut {@link XFormPlacement} öğesini alır.

**Returns:**
XFormPlacement örneği

### getPosition {#getPosition--}
```
public Point getPosition()
```

Mevcut koordinat uzayındaki konumu alır veya ayarlar. Parent #getParent/#setParent(XFormPlacement) null değilse, öğenin xForm koordinat uzayı vardır.

**Returns:**
Nokta örneği

### getRectangle {#getRectangle--}
```
public abstract Rectangle getRectangle()
```

{@link GraphicElement} öğesinin sınırlayıcı dikdörtgenini alır.

**Returns:**
Dikdörtgen örneği

### getSourcePage {#getSourcePage--}
```
public final Page getSourcePage()
```

Grafik öğesinin çıkarıldığı sayfayı alır.

**Returns:**
Sayfa örneği

### remove {#remove--}
```
public final void remove()
```

Mevcut öğeyi sayfadan kaldırır. Kaldırılacak çok sayıda öğe varsa, Page#deleteGraphics(GraphicElementCollection) kullanmak daha iyidir.

### saveToSvg {#saveToSvg--}
```
public final String saveToSvg()
```

Öğeyi tek bir SVG görüntüsüne dönüştürür.

**Returns:**
SVG dizesi.

### saveToSvg {#saveToSvg-java.lang.String-}
Öğeyi tek bir SVG görüntüsüne dönüştürür.

**Returns:**
SVG dizesi.

### setPosition {#setPosition-com.aspose.pdf.Point-}
Mevcut koordinat uzayındaki konumu alır veya ayarlar. Parent #getParent/#setParent(XFormPlacement) null değilse, öğenin xForm koordinat uzayı vardır.
