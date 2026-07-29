---
title: "Id"
linktitle: "Id"
second_title: "Aspose.PDF für Java API-Referenz"
description: "<p> Stellt die Dateikennzeichnungsstruktur dar. </p> <hr> <pre> Document doc = new Document(\\\"example.pdf\\\"); String original = doc.getId().getOriginal(); String modified =."
type: docs
weight: 2220
url: /de/java/com.aspose.pdf/id/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Id

```
public class Id extends Object
```

<p> Stellt die Dateikennzeichnerstruktur dar. </p> <hr> <pre> Document doc = new Document(\"example.pdf\"); String original = doc.getId().getOriginal(); String modified = doc.getId().getModified(); </pre>

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getModified](#getModified--) | Ändert den Bezeichner basierend auf dem Inhalt des Dokuments zum Zeitpunkt der letzten Aktualisierung. |
| [getOriginal](#getOriginal--) | Permanenter Bezeichner basierend auf dem Inhalt des Dokuments zum Zeitpunkt der ursprünglichen Erstellung. |

### getModified {#getModified--}
```
public String getModified()
```

Ändert den Bezeichner basierend auf dem Inhalt des Dokuments zum Zeitpunkt der letzten Aktualisierung.

**Returns:**
String Wert

### getOriginal {#getOriginal--}
```
public String getOriginal()
```

Permanenter Bezeichner basierend auf dem Inhalt des Dokuments zum Zeitpunkt der ursprünglichen Erstellung.

**Returns:**
String Wert
