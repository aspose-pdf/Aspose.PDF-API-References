---
title: CgmLoadOptions
second_title: Aspose.PDF for Java API Reference
description: Contains options for loading/importing CGM file into pdf document.
type: docs
weight: 56
url: /java/com.aspose.pdf/cgmloadoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.LoadOptions](../../com.aspose.pdf/loadoptions)
```
public final class CgmLoadOptions extends LoadOptions
```

Contains options for loading/importing CGM file into pdf document.
## Constructors

| Constructor | Description |
| --- | --- |
| [CgmLoadOptions()](#CgmLoadOptions--) | Creates default load options for converting CGM file into pdf document. |
| [CgmLoadOptions(Dimension2D pageSize)](#CgmLoadOptions-java.awt.geom.Dimension2D-) | Creates load options with defined  pageSize . |
## Methods

| Method | Description |
| --- | --- |
| [getPageSize()](#getPageSize--) | Gets output page size for import. |
### CgmLoadOptions() {#CgmLoadOptions--}
```
public CgmLoadOptions()
```


Creates default load options for converting CGM file into pdf document. Default pdf page size - A4 300dpi 2480 X 3508.

### CgmLoadOptions(Dimension2D pageSize) {#CgmLoadOptions-java.awt.geom.Dimension2D-}
```
public CgmLoadOptions(Dimension2D pageSize)
```


Creates load options with defined  pageSize .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageSize | java.awt.geom.Dimension2D | Defines pdf page width and height. |

### getPageSize() {#getPageSize--}
```
public Dimension2D getPageSize()
```


Gets output page size for import.

**Returns:**
java.awt.geom.Dimension2D - Dimension2D object
