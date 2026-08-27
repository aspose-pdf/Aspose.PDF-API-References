---
title: "ExcelSaveOptions"
linktitle: "ExcelSaveOptions"
second_title: "Aspose.PDF för Java API-referens"
description: "Spara alternativ för export till Excel-format"
type: docs
weight: 1260
url: /sv/java/com.aspose.pdf/excelsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.ExcelSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.ExcelSaveOptions, com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.ExcelSaveOptions

```
public class ExcelSaveOptions extends UnifiedSaveOptions
```

Spara alternativ för export till Excel-format

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [ExcelSaveOptions](#ExcelSaveOptions--) | Konstruktör |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFormat](#getFormat--) | / * / * Hämtar eller anger faktor som kommer att tillämpas på (virtuell) skalning av teckenstorlek under konvertering till Excel-tabell i det äldre motorn. Att ange ett lägre värde underlättar sökningen efter kolumner och förhindrar sammanslagning av dem för vissa dokument. Standardvärdet är 0,9; Att sätta värdet till noll låter algoritmen välja skalning automatiskt. / * / * / * |
| [getMinimizeTheNumberOfWorksheets](#getMinimizeTheNumberOfWorksheets--) | Ange true om du behöver minimera antalet arbetsblad i den resulterande arbetsboken. Standardvärdet är false; det betyder att varje PDF-sida sparas som ett separat arbetsblad. |
| [isInsertBlankColumnAtFirst](#isInsertBlankColumnAtFirst--) | Ställ in falskt om du behöver undertrycka infogning av en tom kolumn som det första kolumnen i kalkylbladet. Standardvärdet är sant; det betyder att den tomma kolumnen kommer att infogas. |
| [isUniformWorksheets](#isUniformWorksheets--) | Ställ in sant för att använda enhetlig kolumnindelning i hela dokumentet. Standardvärdet är falskt; det betyder att kolumnindelningen blir oberoende för varje sida. |
| [setFormat](#setFormat-com.aspose.pdf.ExcelSaveOptions.ExcelFormat-) | Utdatformat |
| [setInsertBlankColumnAtFirst](#setInsertBlankColumnAtFirst-boolean-) | Ställ in falskt om du behöver undertrycka infogning av en tom kolumn som det första kolumnen i kalkylbladet. Standardvärdet är sant; det betyder att den tomma kolumnen kommer att infogas. |
| [setMinimizeTheNumberOfWorksheets](#setMinimizeTheNumberOfWorksheets-boolean-) | Ange true om du behöver minimera antalet arbetsblad i den resulterande arbetsboken. Standardvärdet är false; det betyder att varje PDF-sida sparas som ett separat arbetsblad. |
| [setUniformWorksheets](#setUniformWorksheets-boolean-) | Definierar konverteringsmotor som kommer att användas för konvertering |

### ExcelSaveOptions {#ExcelSaveOptions--}
```
public ExcelSaveOptions()
```

Konstruktör

### getFormat {#getFormat--}
```
public ExcelSaveOptions.ExcelFormat getFormat()
```

/ * / * Hämtar eller anger faktor som kommer att tillämpas på (virtuell) skalning av teckenstorlek under konvertering till Excel-tabell i det äldre motorn. Att ange ett lägre värde underlättar sökningen efter kolumner och förhindrar sammanslagning av dem för vissa dokument. Standardvärdet är 0,9; Att sätta värdet till noll låter algoritmen välja skalning automatiskt. / * / * / *

**Returns:**
dubbelvärde /

### getMinimizeTheNumberOfWorksheets {#getMinimizeTheNumberOfWorksheets--}
```
public boolean getMinimizeTheNumberOfWorksheets()
```

Ange true om du behöver minimera antalet arbetsblad i den resulterande arbetsboken. Standardvärdet är false; det betyder att varje PDF-sida sparas som ett separat arbetsblad.

**Returns:**
booleskt värde

### isInsertBlankColumnAtFirst {#isInsertBlankColumnAtFirst--}
```
public boolean isInsertBlankColumnAtFirst()
```

Ställ in falskt om du behöver undertrycka infogning av en tom kolumn som det första kolumnen i kalkylbladet. Standardvärdet är sant; det betyder att den tomma kolumnen kommer att infogas.

**Returns:**
booleskt värde

### isUniformWorksheets {#isUniformWorksheets--}
```
public boolean isUniformWorksheets()
```

Ställ in sant för att använda enhetlig kolumnindelning i hela dokumentet. Standardvärdet är falskt; det betyder att kolumnindelningen blir oberoende för varje sida.

**Returns:**
booleskt värde

### setFormat {#setFormat-com.aspose.pdf.ExcelSaveOptions.ExcelFormat-}
Utdatformat

### setInsertBlankColumnAtFirst {#setInsertBlankColumnAtFirst-boolean-}
```
public void setInsertBlankColumnAtFirst(boolean value)
```

Ställ in falskt om du behöver undertrycka infogning av en tom kolumn som det första kolumnen i kalkylbladet. Standardvärdet är sant; det betyder att den tomma kolumnen kommer att infogas.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setMinimizeTheNumberOfWorksheets {#setMinimizeTheNumberOfWorksheets-boolean-}
```
public void setMinimizeTheNumberOfWorksheets(boolean value)
```

Ange true om du behöver minimera antalet arbetsblad i den resulterande arbetsboken. Standardvärdet är false; det betyder att varje PDF-sida sparas som ett separat arbetsblad.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setUniformWorksheets {#setUniformWorksheets-boolean-}
```
public void setUniformWorksheets(boolean value)
```

Definierar konverteringsmotor som kommer att användas för konvertering

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  |  |
