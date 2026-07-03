---
title: PdfPrintRange
second_title: Aspose.PDF for Java API Reference
description: Specifies the part of the document to print.
type: docs
weight: 60
url: /java/com.aspose.pdf.printing/pdfprintrange/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.printing.PdfPrintRange

```
public final class PdfPrintRange extends Object
```

Specifies the part of the document to print.

## Fields

| Field | Description |
| --- | --- |
| [AllPages](#AllPages) | All pages are printed. |
| [CurrentPage](#CurrentPage) | The currently displayed page is printed |
| [Selection](#Selection) | The selected pages are printed. |
| [SomePages](#SomePages) | The pages between FromPage and ToPage are printed. |

## Constructors

| Constructor | Description |
| --- | --- |
| [PdfPrintRange](#PdfPrintRange--) |  |

## Methods

| Method | Description |
| --- | --- |
| [getNames](#getNames--) | Get String names for PdfPrintRange |
| [toString](#toString-int-) | Get String name for PdfPrintRange element |

### AllPages {#AllPages}
```
public static final int AllPages
```

All pages are printed.

### CurrentPage {#CurrentPage}
```
public static final int CurrentPage
```

The currently displayed page is printed

### Selection {#Selection}
```
public static final int Selection
```

The selected pages are printed.

### SomePages {#SomePages}
```
public static final int SomePages
```

The pages between FromPage and ToPage are printed.

### PdfPrintRange {#PdfPrintRange--}
```
public PdfPrintRange()
```



### getNames {#getNames--}
```
public static String [] getNames()
```

Get String names for PdfPrintRange

**Returns:**
String[] object

### toString {#toString-int-}
```
public static String toString(int pdfPrintRange)
```

Get String name for PdfPrintRange element

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pdfPrintRange |  | PdfPrintRange element |

**Returns:**
String object @see PdfPrintRange
