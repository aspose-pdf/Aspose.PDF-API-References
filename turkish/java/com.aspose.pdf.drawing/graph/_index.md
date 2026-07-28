---
title: "Grafik"
linktitle: "Grafik"
second_title: "Aspose.PDF for Java API Referansı"
description: "Grafiği - grafik oluşturucu paragrafı temsil eder."
type: docs
weight: 70
url: /tr/java/com.aspose.pdf.drawing/graph/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.drawing.Graph, com.aspose.pdf.BaseParagraph, com.aspose.pdf.drawing.Graph

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class Graph extends BaseParagraph
```

Grafiği - grafik oluşturucu paragrafı temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Graph](#Graph--) | Yalnızca dahili kullanım için |
| [Graph](#Graph-double-double-) | Yeni bir {@link Graph} sınıfının örneğini başlatır. |
| [Graph](#Graph-float-float-) | Yeni bir {@code Graph} sınıfının örneğini başlatır. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [deepClone](#deepClone--) | Grafiği klonla. |
| [getBorder](#getBorder--) | Kenarı alır. |
| [getGraphInfo](#getGraphInfo--) | Grafik bilgilerini, örneğin renk, çizgi kalınlığı vb. gösteren bir {@code GraphInfo} nesnesini alır. |
| [getHeight](#getHeight--) | Grafik yüksekliğini gösteren float değerini alır. Birim point'tir. XML'de, varsayılan birim point'tir, ancak cm ve inç de desteklenir. Örneğin, GraphHeight="10cm" veya GraphHeight="5inch". |
| [getLeft](#getLeft--) | Tablonun sol koordinatını alır. |
| [getShapes](#getShapes--) | Grafikteki tüm şekilleri gösteren bir koleksiyonu alır. |
| [getTitle](#getTitle--) | Grafiğin başlığını gösteren string değerini alır. |
| [getTop](#getTop--) | Tablonun üst koordinatını alır. |
| [getWidth](#getWidth--) | Grafik genişliğini gösteren float değerini alır. Birim point'tir. XML'de, varsayılan birim point'tir, ancak cm ve inç de desteklenir. Örneğin, GraphWidth="10cm" veya GraphWidth="5inch". |
| [isChangePosition](#isChangePosition--) | Paragraf işlendiğinde mevcut konumu değiştirip değiştirmeyeceğini alır. (varsayılan true) |
| [setBorder](#setBorder-com.aspose.pdf.BorderInfo-) | Kenarı ayarlar. |
| [setChangePosition](#setChangePosition-boolean-) | Paragraf işlendiğinde mevcut konumu değiştirip değiştirmeyeceği ayarlar. (varsayılan true) |
| [setGraphInfo](#setGraphInfo-com.aspose.pdf.GraphInfo-) | Grafik bilgilerini, örneğin renk, çizgi kalınlığı vb. gösteren bir {@code GraphInfo} nesnesini alır veya ayarlar. |
| [setHeight](#setHeight-double-) | Grafik yüksekliğini gösteren float değerini ayarlar. Birim point'tir. XML'de, varsayılan birim point'tir, ancak cm ve inç de desteklenir. Örneğin, GraphHeight="10cm" veya GraphHeight="5inch". |
| [setLeft](#setLeft-double-) | Tablonun sol koordinatını ayarlar. |
| [setShapes](#setShapes-com.aspose.pdf.boundscheckablelist.BoundsCheckableList-) | Grafikteki tüm şekilleri gösteren bir koleksiyonu ayarlar. |
| [setTitle](#setTitle-com.aspose.pdf.TextFragment-) | Grafiğin başlığını gösteren string değerini ayarlar. |
| [setTop](#setTop-double-) | Tablonun üst koordinatını ayarlar. |
| [setWidth](#setWidth-double-) | Grafik genişliğini gösteren float değerini ayarlar. Birim point'tir. XML'de, varsayılan birim point'tir, ancak cm ve inç de desteklenir. Örneğin, GraphWidth="10cm" veya GraphWidth="5inch". |

### Graph {#Graph--}
```
public Graph()
```

Yalnızca dahili kullanım için

### Graph {#Graph-double-double-}
```
public Graph(double width, double height)
```

Yeni bir {@link Graph} sınıfının örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| genişlik |  | Grafiğin genişliği. |
| yükseklik |  | Grafiğin yüksekliği. |

### Graph {#Graph-float-float-}
```
@Deprecated public Graph(float width, float height)
```

Yeni bir {@code Graph} sınıfının örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| genişlik |  | Grafiğin genişliği. |
| yükseklik |  | Grafiğin yüksekliği. |

### deepClone {#deepClone--}
```
public Object deepClone()
```

Grafiği klonla.

**Returns:**
Klonlanmış nesne

### getBorder {#getBorder--}
```
public BorderInfo getBorder()
```

Kenarı alır.

**Returns:**
BorderInfo öğesi

### getGraphInfo {#getGraphInfo--}
```
public GraphInfo getGraphInfo()
```

Grafik bilgilerini, örneğin renk, çizgi kalınlığı vb. gösteren bir {@code GraphInfo} nesnesini alır.

**Returns:**
GraphInfo nesnesi

### getHeight {#getHeight--}
```
public double getHeight()
```

Grafik yüksekliğini gösteren float değerini alır. Birim point'tir. XML'de, varsayılan birim point'tir, ancak cm ve inç de desteklenir. Örneğin, GraphHeight="10cm" veya GraphHeight="5inch".

**Returns:**
grafik yüksekliğini gösteren değer.

### getLeft {#getLeft--}
```
public double getLeft()
```

Tablonun sol koordinatını alır.

**Returns:**
tablonun sol koordinatı.

### getShapes {#getShapes--}
```
public final BoundsCheckableList < Shape > getShapes()
```

Grafikteki tüm şekilleri gösteren bir koleksiyonu alır.

**Returns:**
Şekillerin BoundsCheckableList'i.

### getTitle {#getTitle--}
```
public TextFragment getTitle()
```

Grafiğin başlığını gösteren string değerini alır.

**Returns:**
grafiğin başlığı.

### getTop {#getTop--}
```
public double getTop()
```

Tablonun üst koordinatını alır.

**Returns:**
tablonun üst koordinatı.

### getWidth {#getWidth--}
```
public double getWidth()
```

Grafik genişliğini gösteren float değerini alır. Birim point'tir. XML'de, varsayılan birim point'tir, ancak cm ve inç de desteklenir. Örneğin, GraphWidth="10cm" veya GraphWidth="5inch".

**Returns:**
grafik genişliğini gösteren float değer.

### isChangePosition {#isChangePosition--}
```
public boolean isChangePosition()
```

Paragraf işlendiğinde mevcut konumu değiştirip değiştirmeyeceğini alır. (varsayılan true)

**Returns:**
boolean değer

### setBorder {#setBorder-com.aspose.pdf.BorderInfo-}
Kenarı ayarlar.

### setChangePosition {#setChangePosition-boolean-}
```
public void setChangePosition(boolean value)
```

Paragraf işlendiğinde mevcut konumu değiştirip değiştirmeyeceği ayarlar. (varsayılan true)

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setGraphInfo {#setGraphInfo-com.aspose.pdf.GraphInfo-}
Grafik bilgilerini, örneğin renk, çizgi kalınlığı vb. gösteren bir {@code GraphInfo} nesnesini alır veya ayarlar.

### setHeight {#setHeight-double-}
```
public void setHeight(double value)
```

Grafik yüksekliğini gösteren float değerini ayarlar. Birim point'tir. XML'de, varsayılan birim point'tir, ancak cm ve inç de desteklenir. Örneğin, GraphHeight="10cm" veya GraphHeight="5inch".

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | grafik yüksekliğini gösteren. |

### setLeft {#setLeft-double-}
```
public void setLeft(double value)
```

Tablonun sol koordinatını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | tablonun sol koordinatı. |

### setShapes {#setShapes-com.aspose.pdf.boundscheckablelist.BoundsCheckableList-}
Grafikteki tüm şekilleri gösteren bir koleksiyonu ayarlar.

### setTitle {#setTitle-com.aspose.pdf.TextFragment-}
Grafiğin başlığını gösteren string değerini ayarlar.

### setTop {#setTop-double-}
```
public void setTop(double value)
```

Tablonun üst koordinatını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | tablonun üst koordinatı. |

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

Grafik genişliğini gösteren float değerini ayarlar. Birim point'tir. XML'de, varsayılan birim point'tir, ancak cm ve inç de desteklenir. Örneğin, GraphWidth="10cm" veya GraphWidth="5inch".

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | grafik genişliğini gösteren float değer. |
