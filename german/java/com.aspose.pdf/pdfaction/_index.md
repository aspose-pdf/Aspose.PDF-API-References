---
title: "PdfAction"
linktitle: "PdfAction"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt eine Aktion in einem PDF-Dokument dar"
type: docs
weight: 3670
url: /de/java/com.aspose.pdf/pdfaction/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfAction

**All Implemented Interfaces:**
IAppointment

```
public abstract class PdfAction extends Object implements IAppointment
```

Stellt eine Aktion in einem PDF-Dokument dar

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PdfAction](#PdfAction--) |  |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getECMAScriptString](#getECMAScriptString--) | Liefert die Zeichenkette für die ECMAScript-Aktion. |
| [getNext](#getNext--) | Nächste Aktionen in der Reihenfolge. |

### PdfAction {#PdfAction--}
```
public PdfAction()
```



### getECMAScriptString {#getECMAScriptString--}
```
public final String getECMAScriptString()
```

Liefert die Zeichenkette für die ECMAScript-Aktion.

**Returns:**
Gibt die Zeichenkette für den JS-Eintrag der ECMAScript-Aktion zurück oder sonst null.

### getNext {#getNext--}
```
public ActionCollection getNext()
```

Nächste Aktionen in der Reihenfolge.

**Returns:**
ActionCollection-Objekt
