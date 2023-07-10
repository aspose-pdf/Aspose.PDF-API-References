---
title: VectorGraphicsAbsorber
second_title: Aspose.PDF for Java API Reference
description: Represents an absorber object of vector graphics elements.
type: docs
weight: 12
url: /java/com.aspose.pdf.vector/vectorgraphicsabsorber/
---
**Inheritance:**
java.lang.Object
```
public class VectorGraphicsAbsorber
```

Represents an absorber object of vector graphics elements. Performs vector graphics search and provides access to search results via  VectorGraphicsAbsorber.SubPaths ([VectorGraphicsAbsorber\#getSubPaths](../../com.aspose.pdf.vector/vectorgraphicsabsorber\#getSubPaths)) collection.
## Constructors

| Constructor | Description |
| --- | --- |
| [VectorGraphicsAbsorber()](#VectorGraphicsAbsorber--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getSubPaths()](#getSubPaths--) | Gets collection of search occurrences that are presented with [SubPath](../../com.aspose.pdf.vector/subpath) objects. |
| [visit(Page page)](#visit-com.aspose.pdf.Page-) | Performs search on the specified page. |
### VectorGraphicsAbsorber() {#VectorGraphicsAbsorber--}
```
public VectorGraphicsAbsorber()
```


### getSubPaths() {#getSubPaths--}
```
public final SubPathCollection getSubPaths()
```


Gets collection of search occurrences that are presented with [SubPath](../../com.aspose.pdf.vector/subpath) objects.

**Returns:**
[SubPathCollection](../../com.aspose.pdf.vector/subpathcollection) - SubPathCollection instance
### visit(Page page) {#visit-com.aspose.pdf.Page-}
```
public final void visit(Page page)
```


Performs search on the specified page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| page | [Page](../../com.aspose.pdf/page) | PDF document page object. |

