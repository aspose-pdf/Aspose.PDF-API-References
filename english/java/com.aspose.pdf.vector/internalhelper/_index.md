---
title: InternalHelper
second_title: Aspose.PDF for Java API Reference
description: 
type: docs
weight: 13
url: /java/com.aspose.pdf.vector/internalhelper/
---
**Inheritance:**
java.lang.Object
```
public class InternalHelper
```
## Constructors

| Constructor | Description |
| --- | --- |
| [InternalHelper()](#InternalHelper--) |  |
## Methods

| Method | Description |
| --- | --- |
| [graphicAppender_addGraphicToPage(Page page, GraphicElementCollection elements, Rectangle rectangle)](#graphicAppender-addGraphicToPage-com.aspose.pdf.Page-com.aspose.pdf.vector.GraphicElementCollection-com.aspose.pdf.Rectangle-) |  |
| [getOperatorsInternal(GraphicElement el)](#getOperatorsInternal-com.aspose.pdf.vector.GraphicElement-) |  |
| [clear(GraphicElement el)](#clear-com.aspose.pdf.vector.GraphicElement-) |  |
| [getParent(GraphicElementCollection elementsToDelete)](#getParent-com.aspose.pdf.vector.GraphicElementCollection-) |  |
| [GraphicsAbsorber_isPathPaintingOperator(String name)](#GraphicsAbsorber-isPathPaintingOperator-java.lang.String-) |  |
### InternalHelper() {#InternalHelper--}
```
public InternalHelper()
```


### graphicAppender_addGraphicToPage(Page page, GraphicElementCollection elements, Rectangle rectangle) {#graphicAppender-addGraphicToPage-com.aspose.pdf.Page-com.aspose.pdf.vector.GraphicElementCollection-com.aspose.pdf.Rectangle-}
```
public static void graphicAppender_addGraphicToPage(Page page, GraphicElementCollection elements, Rectangle rectangle)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) |  |
| elements | [GraphicElementCollection](../../com.aspose.pdf.vector/graphicelementcollection) |  |
| rectangle | [Rectangle](../../com.aspose.pdf/rectangle) |  |

### getOperatorsInternal(GraphicElement el) {#getOperatorsInternal-com.aspose.pdf.vector.GraphicElement-}
```
public static System.Collections.Generic.List<Operator> getOperatorsInternal(GraphicElement el)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| el | [GraphicElement](../../com.aspose.pdf.vector/graphicelement) |  |

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.pdf.Operator>
### clear(GraphicElement el) {#clear-com.aspose.pdf.vector.GraphicElement-}
```
public static void clear(GraphicElement el)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| el | [GraphicElement](../../com.aspose.pdf.vector/graphicelement) |  |

### getParent(GraphicElementCollection elementsToDelete) {#getParent-com.aspose.pdf.vector.GraphicElementCollection-}
```
public static XFormPlacement getParent(GraphicElementCollection elementsToDelete)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| elementsToDelete | [GraphicElementCollection](../../com.aspose.pdf.vector/graphicelementcollection) |  |

**Returns:**
[XFormPlacement](../../com.aspose.pdf.vector/xformplacement)
### GraphicsAbsorber_isPathPaintingOperator(String name) {#GraphicsAbsorber-isPathPaintingOperator-java.lang.String-}
```
public static boolean GraphicsAbsorber_isPathPaintingOperator(String name)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
boolean
