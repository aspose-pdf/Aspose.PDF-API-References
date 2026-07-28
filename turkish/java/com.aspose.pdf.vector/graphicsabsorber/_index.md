---
title: "GraphicsAbsorber"
linktitle: "GraphicsAbsorber"
second_title: "Aspose.PDF for Java API Referansı"
description: "Grafik öğelerinin bir emici nesnesini temsil eder. Grafik araması gerçekleştirir ve {@code GraphicsAbsorber.Elements}({@link."
type: docs
weight: 30
url: /tr/java/com.aspose.pdf.vector/graphicsabsorber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.vector.GraphicsAbsorber

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable

```
public class GraphicsAbsorber extends Object implements com.aspose.ms.System.IDisposable
```

Grafik öğelerinin bir absorber nesnesini temsil eder. Grafik araması yapar ve arama sonuçlarına {@code GraphicsAbsorber.Elements}({@link GraphicsAbsorber#getElements}) koleksiyonu aracılığıyla erişim sağlar.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [GraphicsAbsorber](#GraphicsAbsorber--) |  |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [dispose](#dispose--) | {@link GraphicsAbsorber} sınıfı tarafından kullanılan tüm kaynakları serbest bırakır. |
| [getElements](#getElements--) | {@link GraphicElement} nesneleriyle sunulan arama oluşumlarının koleksiyonunu alır. |
| [resumeUpdate](#resumeUpdate--) | Page#getContents ve tüm @link XForm#getContents için güncellemeyi sürdür. Performans artışı için yapıldı, ayrıca bakınız. |
| [suppressUpdate](#suppressUpdate--) | Page#getContents ve tüm @link XForm#getContents için güncellemeyi engeller. Performans artışı için yapıldı, ayrıca bakınız. |
| [visit](#visit-com.aspose.pdf.Page-) | Belirtilen sayfada arama gerçekleştirir. |

### GraphicsAbsorber {#GraphicsAbsorber--}
```
public GraphicsAbsorber()
```



### dispose {#dispose--}
```
public final void dispose()
```

{@link GraphicsAbsorber} sınıfı tarafından kullanılan tüm kaynakları serbest bırakır.

### getElements {#getElements--}
```
public final GraphicElementCollection getElements()
```

{@link GraphicElement} nesneleriyle sunulan arama oluşumlarının koleksiyonunu alır.

**Returns:**
GraphicElementCollection örneği

### resumeUpdate {#resumeUpdate--}
```
public final void resumeUpdate()
```

Page#getContents ve tüm @link XForm#getContents için güncellemeyi sürdür. Performans artışı için yapıldı, ayrıca bakınız.

### suppressUpdate {#suppressUpdate--}
```
public final void suppressUpdate()
```

Page#getContents ve tüm @link XForm#getContents için güncellemeyi engeller. Performans artışı için yapıldı, ayrıca bakınız.

### visit {#visit-com.aspose.pdf.Page-}
Belirtilen sayfada arama gerçekleştirir.
