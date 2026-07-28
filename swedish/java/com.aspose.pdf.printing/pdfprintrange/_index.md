---
title: "PdfPrintRange"
linktitle: "PdfPrintRange"
second_title: "Aspose.PDF för Java API-referens"
description: "Anger den del av dokumentet som ska skrivas ut."
type: docs
weight: 60
url: /sv/java/com.aspose.pdf.printing/pdfprintrange/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.printing.PdfPrintRange

```
public final class PdfPrintRange extends Object
```

Anger den del av dokumentet som ska skrivas ut.

## Fält

| Fält | Beskrivning |
| --- | --- |
| [AllPages](#AllPages) | Alla sidor har skrivits ut. |
| [CurrentPage](#CurrentPage) | Den aktuellt visade sidan skrivs ut |
| [Selection](#Selection) | De valda sidorna skrivs ut. |
| [SomePages](#SomePages) | Sidorna mellan FromPage och ToPage skrivs ut. |

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [PdfPrintRange](#PdfPrintRange--) |  |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getNames](#getNames--) | Hämta strängnamn för PdfPrintRange |
| [toString](#toString-int-) | Hämta strängnamn för PdfPrintRange-element |

### AllPages {#AllPages}
```
public static final int AllPages
```

Alla sidor har skrivits ut.

### CurrentPage {#CurrentPage}
```
public static final int CurrentPage
```

Den aktuellt visade sidan skrivs ut

### Selection {#Selection}
```
public static final int Selection
```

De valda sidorna skrivs ut.

### SomePages {#SomePages}
```
public static final int SomePages
```

Sidorna mellan FromPage och ToPage skrivs ut.

### PdfPrintRange {#PdfPrintRange--}
```
public PdfPrintRange()
```



### getNames {#getNames--}
```
public static String [] getNames()
```

Hämta strängnamn för PdfPrintRange

**Returns:**
String[] objekt

### toString {#toString-int-}
```
public static String toString(int pdfPrintRange)
```

Hämta strängnamn för PdfPrintRange-element

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pdfPrintRange |  | PdfPrintRange-element |

**Returns:**
String-objekt @see PdfPrintRange
