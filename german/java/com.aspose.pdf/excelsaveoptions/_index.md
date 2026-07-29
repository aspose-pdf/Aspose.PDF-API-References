---
title: "ExcelSaveOptions"
linktitle: "ExcelSaveOptions"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Speicheroptionen für den Export in das Excel-Format"
type: docs
weight: 1260
url: /de/java/com.aspose.pdf/excelsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.ExcelSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.ExcelSaveOptions, com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.ExcelSaveOptions

```
public class ExcelSaveOptions extends UnifiedSaveOptions
```

Speicheroptionen für den Export in das Excel-Format

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ExcelSaveOptions](#ExcelSaveOptions--) | Konstruktor |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getFormat](#getFormat--) | / * / * Liest oder setzt den Faktor, der (virtuell) die Schriftgröße während der Konvertierung in eine Excel‑Tabelle skaliert / * Legacy‑Engine. Ein niedrigerer Wert erleichtert die Suche nach Spalten und verhindert das Zusammenführen von ihnen bei einigen / * Dokumenten. Standardwert ist 0,9; Ein Wert von null lässt den Algorithmus die Skalierung automatisch wählen. / * / * / * |
| [getMinimizeTheNumberOfWorksheets](#getMinimizeTheNumberOfWorksheets--) | Setzen Sie true, wenn Sie die Anzahl der Arbeitsblätter im resultierenden Arbeitsbuch minimieren möchten. Standardwert ist false; das bedeutet, dass jede PDF‑Seite als separates Arbeitsblatt gespeichert wird. |
| [isInsertBlankColumnAtFirst](#isInsertBlankColumnAtFirst--) | Setzen Sie false, wenn Sie das Einfügen einer leeren Spalte als erste Spalte des Arbeitsblatts unterdrücken möchten. Standardwert ist true; das bedeutet, dass eine leere Spalte eingefügt wird. |
| [isUniformWorksheets](#isUniformWorksheets--) | Setzen Sie true, um eine einheitliche Spaltenaufteilung im gesamten Dokument zu verwenden. Standardwert ist false; das bedeutet, dass die Spaltenaufteilung für jede Seite unabhängig ist. |
| [setFormat](#setFormat-com.aspose.pdf.ExcelSaveOptions.ExcelFormat-) | Ausgabeformat |
| [setInsertBlankColumnAtFirst](#setInsertBlankColumnAtFirst-boolean-) | Setzen Sie false, wenn Sie das Einfügen einer leeren Spalte als erste Spalte des Arbeitsblatts unterdrücken möchten. Standardwert ist true; das bedeutet, dass eine leere Spalte eingefügt wird. |
| [setMinimizeTheNumberOfWorksheets](#setMinimizeTheNumberOfWorksheets-boolean-) | Setzen Sie true, wenn Sie die Anzahl der Arbeitsblätter im resultierenden Arbeitsbuch minimieren möchten. Standardwert ist false; das bedeutet, dass jede PDF‑Seite als separates Arbeitsblatt gespeichert wird. |
| [setUniformWorksheets](#setUniformWorksheets-boolean-) | Definiert die Konvertierungs-Engine, die für die Konvertierung verwendet wird. |

### ExcelSaveOptions {#ExcelSaveOptions--}
```
public ExcelSaveOptions()
```

Konstruktor

### getFormat {#getFormat--}
```
public ExcelSaveOptions.ExcelFormat getFormat()
```

/ * / * Liest oder setzt den Faktor, der (virtuell) die Schriftgröße während der Konvertierung in eine Excel‑Tabelle skaliert / * Legacy‑Engine. Ein niedrigerer Wert erleichtert die Suche nach Spalten und verhindert das Zusammenführen von ihnen bei einigen / * Dokumenten. Standardwert ist 0,9; Ein Wert von null lässt den Algorithmus die Skalierung automatisch wählen. / * / * / *

**Returns:**
double‑Wert /

### getMinimizeTheNumberOfWorksheets {#getMinimizeTheNumberOfWorksheets--}
```
public boolean getMinimizeTheNumberOfWorksheets()
```

Setzen Sie true, wenn Sie die Anzahl der Arbeitsblätter im resultierenden Arbeitsbuch minimieren möchten. Standardwert ist false; das bedeutet, dass jede PDF‑Seite als separates Arbeitsblatt gespeichert wird.

**Returns:**
boolescher Wert

### isInsertBlankColumnAtFirst {#isInsertBlankColumnAtFirst--}
```
public boolean isInsertBlankColumnAtFirst()
```

Setzen Sie false, wenn Sie das Einfügen einer leeren Spalte als erste Spalte des Arbeitsblatts unterdrücken möchten. Standardwert ist true; das bedeutet, dass eine leere Spalte eingefügt wird.

**Returns:**
boolescher Wert

### isUniformWorksheets {#isUniformWorksheets--}
```
public boolean isUniformWorksheets()
```

Setzen Sie true, um eine einheitliche Spaltenaufteilung im gesamten Dokument zu verwenden. Standardwert ist false; das bedeutet, dass die Spaltenaufteilung für jede Seite unabhängig ist.

**Returns:**
boolescher Wert

### setFormat {#setFormat-com.aspose.pdf.ExcelSaveOptions.ExcelFormat-}
Ausgabeformat

### setInsertBlankColumnAtFirst {#setInsertBlankColumnAtFirst-boolean-}
```
public void setInsertBlankColumnAtFirst(boolean value)
```

Setzen Sie false, wenn Sie das Einfügen einer leeren Spalte als erste Spalte des Arbeitsblatts unterdrücken möchten. Standardwert ist true; das bedeutet, dass eine leere Spalte eingefügt wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setMinimizeTheNumberOfWorksheets {#setMinimizeTheNumberOfWorksheets-boolean-}
```
public void setMinimizeTheNumberOfWorksheets(boolean value)
```

Setzen Sie true, wenn Sie die Anzahl der Arbeitsblätter im resultierenden Arbeitsbuch minimieren möchten. Standardwert ist false; das bedeutet, dass jede PDF‑Seite als separates Arbeitsblatt gespeichert wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setUniformWorksheets {#setUniformWorksheets-boolean-}
```
public void setUniformWorksheets(boolean value)
```

Definiert die Konvertierungs-Engine, die für die Konvertierung verwendet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  |  |
