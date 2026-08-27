---
title: "TextExtractionErrorLocation"
linktitle: "TextExtractionErrorLocation"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt den Ort im PDF-Dokument dar, an dem ein Textextraktionsfehler aufgetreten ist."
type: docs
weight: 5050
url: /de/java/com.aspose.pdf/textextractionerrorlocation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextExtractionErrorLocation

```
public final class TextExtractionErrorLocation extends Object
```

Stellt den Ort im PDF-Dokument dar, an dem ein Textextraktionsfehler aufgetreten ist.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getFontUsedKey](#getFontUsedKey--) | Schlüssel (Name) des PDF-Schriftobjekts, das für die Anzeige des Operators verwendet wird, der den Textextraktionsfehler verursacht. |
| [getFormKey](#getFormKey--) | Schlüssel (Name) des PDF-Formular-XObjects, in dem der Textextraktionsfehler im Inhaltsstrom aufgetreten ist. Nicht leer, wenn ObjectType == 'xForm'. |
| [getObjectType](#getObjectType--) | Typ des PDF-Objekts (Seite oder xForm), in dem der Textextraktionsfehler im Inhaltsstrom aufgetreten ist. |
| [getOperatorIndex](#getOperatorIndex--) | Index des Textanzeigeoperators im Inhaltsstrom (Operatorensammlung), der den Textextraktionsfehler verursacht. |
| [getOperatorString](#getOperatorString--) | Textanzeigeoperator, der den Textextraktionsfehler verursacht. |
| [getPageNumber](#getPageNumber--) | Nummer der Dokumentseite, auf der der Textextraktionsfehler aufgetreten ist. |
| [getPath](#getPath--) | Ort des PDF-Dokuments, bei dem ein Text-Extraktionsfehler aufgetreten ist. |
| [getTextStartPoint](#getTextStartPoint--) | Schlüssel (Name) des PDF-Schriftobjekts, das für die Anzeige des Operators verwendet wird, der den Textextraktionsfehler verursacht. |
| [toString](#toString--) | Gibt die String-Darstellung zurück. |

### getFontUsedKey {#getFontUsedKey--}
```
public String getFontUsedKey()
```

Schlüssel (Name) des PDF-Schriftobjekts, das für die Anzeige des Operators verwendet wird, der den Textextraktionsfehler verursacht.

**Returns:**
String Wert

### getFormKey {#getFormKey--}
```
public String getFormKey()
```

Schlüssel (Name) des PDF-Formular-XObjects, in dem der Textextraktionsfehler im Inhaltsstrom aufgetreten ist. Nicht leer, wenn ObjectType == 'xForm'.

**Returns:**
String Wert

### getObjectType {#getObjectType--}
```
public String getObjectType()
```

Typ des PDF-Objekts (Seite oder xForm), in dem der Textextraktionsfehler im Inhaltsstrom aufgetreten ist.

**Returns:**
String Wert

### getOperatorIndex {#getOperatorIndex--}
```
public int getOperatorIndex()
```

Index des Textanzeigeoperators im Inhaltsstrom (Operatorensammlung), der den Textextraktionsfehler verursacht.

**Returns:**
int-Wert

### getOperatorString {#getOperatorString--}
```
public String getOperatorString()
```

Textanzeigeoperator, der den Textextraktionsfehler verursacht.

**Returns:**
String Wert

### getPageNumber {#getPageNumber--}
```
public int getPageNumber()
```

Nummer der Dokumentseite, auf der der Textextraktionsfehler aufgetreten ist.

**Returns:**
int-Wert

### getPath {#getPath--}
```
public String getPath()
```

Ort des PDF-Dokuments, bei dem ein Text-Extraktionsfehler aufgetreten ist.

**Returns:**
String Wert

### getTextStartPoint {#getTextStartPoint--}
```
public Point getTextStartPoint()
```

Schlüssel (Name) des PDF-Schriftobjekts, das für die Anzeige des Operators verwendet wird, der den Textextraktionsfehler verursacht.

**Returns:**
Point-Instanz

### toString {#toString--}
```
public String toString()
```

Gibt die String-Darstellung zurück.

**Returns:**
String-Darstellung.
