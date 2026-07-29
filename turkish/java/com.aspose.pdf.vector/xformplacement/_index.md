---
title: "XFormPlacement"
linktitle: "XFormPlacement"
second_title: "Aspose.PDF for Java API Referansı"
description: "XForm yerleşimini temsil eder. XForm sayfada birden fazla kez görüntülenirse, bu XForm ile ilişkili tüm XFormPlacements ortak grafik öğelere sahip olur, ancak."
type: docs
weight: 70
url: /tr/java/com.aspose.pdf.vector/xformplacement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.vector.GraphicElement com.aspose.pdf.vector.XFormPlacement, com.aspose.pdf.vector.GraphicElement, com.aspose.pdf.vector.XFormPlacement

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable

```
public final class XFormPlacement extends GraphicElement
```

XForm yerleşimini temsil eder. XForm sayfada birden fazla kez görüntülenirse, bu XForm ile ilişkili tüm XformPlacements ortak grafik öğelere sahip olur, ancak farklı grafik durumlarına sahiptir.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [addOnPage](#addOnPage-com.aspose.pdf.Page-) | Sayfaya mevcut öğeyi ekler. Eklenmesi gereken birçok öğe varsa Page#addGraphics(GraphicElementCollection,Rectangle) kullanmak daha iyidir. |
| [getElements](#getElements--) | Bu XForm içindeki grafik öğelerini alır. |
| [getName](#getName--) | XForm'un adını alır. |
| [getRectangle](#getRectangle--) | GraphicElement'in sınırlayıcı dikdörtgenini alır. |
| [getXForm](#getXForm--) | Bu XFormPlacement ile ilişkili XForm'u alır. |
| [setPosition](#setPosition-com.aspose.pdf.Point-) | Mevcut koordinat uzayındaki konumu alır veya ayarlar. |

### addOnPage {#addOnPage-com.aspose.pdf.Page-}
Sayfaya mevcut öğeyi ekler. Eklenmesi gereken birçok öğe varsa Page#addGraphics(GraphicElementCollection,Rectangle) kullanmak daha iyidir.

### getElements {#getElements--}
```
public final GraphicElementCollection getElements()
```

Bu XForm içindeki grafik öğelerini alır.

**Returns:**
GraphicElementCollection örneği

### getName {#getName--}
```
public final String getName()
```

XForm'un adını alır.

**Returns:**
String değeri

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

GraphicElement'in sınırlayıcı dikdörtgenini alır.

**Returns:**
Dikdörtgen örneği

### getXForm {#getXForm--}
```
public final XForm getXForm()
```

Bu XFormPlacement ile ilişkili XForm'u alır.

**Returns:**
XForm örneği

### setPosition {#setPosition-com.aspose.pdf.Point-}
Mevcut koordinat uzayındaki konumu alır veya ayarlar.
