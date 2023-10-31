---
title: GraphicsAbsorber
second_title: Aspose.PDF for Java API Reference
description: Represents an absorber object of graphics elements.
type: docs
weight: 12
url: /java/com.aspose.pdf.vector/graphicsabsorber/
---
**Inheritance:**
java.lang.Object
```
public class GraphicsAbsorber
```

Represents an absorber object of graphics elements. Performs graphics search and provides access to search results via  GraphicsAbsorber.Elements ([GraphicsAbsorber\#getElements](../../com.aspose.pdf.vector/graphicsabsorber\#getElements)) collection.
## Constructors

| Constructor | Description |
| --- | --- |
| [GraphicsAbsorber()](#GraphicsAbsorber--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getElements()](#getElements--) | Gets collection of search occurrences that are presented with [GraphicElement](../../com.aspose.pdf.engine.pagemodel/graphicelement) objects. |
| [visit(Page page)](#visit-com.aspose.pdf.Page-) | Performs search on the specified page. |
| [suppressUpdate()](#suppressUpdate--) | Suppresses update for Page\#getContents and all @link XForm\#getContents Was made for performance increase, see also. |
| [resumeUpdate()](#resumeUpdate--) | Resume update forPage\#getContents and all @link XForm\#getContents Was made for performance increase, see also. |
### GraphicsAbsorber() {#GraphicsAbsorber--}
```
public GraphicsAbsorber()
```


### getElements() {#getElements--}
```
public final GraphicElementCollection getElements()
```


Gets collection of search occurrences that are presented with [GraphicElement](../../com.aspose.pdf.engine.pagemodel/graphicelement) objects.

**Returns:**
[GraphicElementCollection](../../com.aspose.pdf.vector/graphicelementcollection) - GraphicElementCollection instance
### visit(Page page) {#visit-com.aspose.pdf.Page-}
```
public final void visit(Page page)
```


Performs search on the specified page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | PDF document page object. |

### suppressUpdate() {#suppressUpdate--}
```
public final void suppressUpdate()
```


Suppresses update for Page\#getContents and all @link XForm\#getContents Was made for performance increase, see also.

### resumeUpdate() {#resumeUpdate--}
```
public final void resumeUpdate()
```


Resume update forPage\#getContents and all @link XForm\#getContents Was made for performance increase, see also.

