---
title: FontAbsorber
second_title: Aspose.PDF for Java API Reference
description: Represents an absorber object of fonts.
type: docs
weight: 134
url: /java/com.aspose.pdf/fontabsorber/
---
**Inheritance:**
java.lang.Object
```
public class FontAbsorber
```

Represents an absorber object of fonts. Performs search for fonts and provides access to search results via  FontAbsorber.Fonts  collection.
## Constructors

| Constructor | Description |
| --- | --- |
| [FontAbsorber()](#FontAbsorber--) | Initializes a new instance of the  FontAbsorber  that performs search for fonts of the document. |
## Methods

| Method | Description |
| --- | --- |
| [getFonts()](#getFonts--) | Gets collection of search occurrences that are presented with  Font  objects. |
| [visit(Document pdf, int startPage, int pageCount)](#visit-com.aspose.pdf.Document-int-int-) | Performs search in the specified range of pages of the document. |
| [visit(Document pdf)](#visit-com.aspose.pdf.Document-) | Performs search on the specified document. |
### FontAbsorber() {#FontAbsorber--}
```
public FontAbsorber()
```


Initializes a new instance of the  FontAbsorber  that performs search for fonts of the document.

### getFonts() {#getFonts--}
```
public FontCollection getFonts()
```


Gets collection of search occurrences that are presented with  Font  objects.

**Returns:**
[FontCollection](../../com.aspose.pdf/fontcollection) - FontCollection object
### visit(Document pdf, int startPage, int pageCount) {#visit-com.aspose.pdf.Document-int-int-}
```
public void visit(Document pdf, int startPage, int pageCount)
```


Performs search in the specified range of pages of the document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pdf | [Document](../../com.aspose.pdf/document) | Pdf pocument object. |
| startPage | int | Pdf pocument start page. |
| pageCount | int | Pdf document page count |

### visit(Document pdf) {#visit-com.aspose.pdf.Document-}
```
public void visit(Document pdf)
```


Performs search on the specified document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pdf | [Document](../../com.aspose.pdf/document) | Pdf pocument object. |

