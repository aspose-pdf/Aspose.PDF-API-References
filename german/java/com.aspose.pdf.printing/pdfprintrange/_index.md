---
title: "PdfPrintRange"
linktitle: "PdfPrintRange"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Gibt den zu druckenden Teil des Dokuments an."
type: docs
weight: 60
url: /de/java/com.aspose.pdf.printing/pdfprintrange/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.printing.PdfPrintRange

```
public final class PdfPrintRange extends Object
```

Gibt den zu druckenden Teil des Dokuments an.

## Felder

| Feld | Beschreibung |
| --- | --- |
| [AllPages](#AllPages) | Alle Seiten werden gedruckt. |
| [CurrentPage](#CurrentPage) | Die aktuell angezeigte Seite wird gedruckt |
| [Selection](#Selection) | Die ausgewählten Seiten werden gedruckt. |
| [SomePages](#SomePages) | Die Seiten zwischen FromPage und ToPage werden gedruckt. |

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PdfPrintRange](#PdfPrintRange--) |  |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getNames](#getNames--) | String‑Namen für PdfPrintRange abrufen |
| [toString](#toString-int-) | String‑Name für PdfPrintRange‑Element abrufen |

### AllPages {#AllPages}
```
public static final int AllPages
```

Alle Seiten werden gedruckt.

### CurrentPage {#CurrentPage}
```
public static final int CurrentPage
```

Die aktuell angezeigte Seite wird gedruckt

### Selection {#Selection}
```
public static final int Selection
```

Die ausgewählten Seiten werden gedruckt.

### SomePages {#SomePages}
```
public static final int SomePages
```

Die Seiten zwischen FromPage und ToPage werden gedruckt.

### PdfPrintRange {#PdfPrintRange--}
```
public PdfPrintRange()
```



### getNames {#getNames--}
```
public static String [] getNames()
```

String‑Namen für PdfPrintRange abrufen

**Returns:**
String[]-Objekt

### toString {#toString-int-}
```
public static String toString(int pdfPrintRange)
```

String‑Name für PdfPrintRange‑Element abrufen

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pdfPrintRange |  | PdfPrintRange‑Element |

**Returns:**
String‑Objekt @see PdfPrintRange
