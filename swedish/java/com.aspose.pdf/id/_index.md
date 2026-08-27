---
title: "Id"
linktitle: "Id"
second_title: "Aspose.PDF för Java API-referens"
description: "<p> Representerar strukturen för filidentifierare. </p> <hr> <pre> Document doc = new Document(\\\"example.pdf\\\"); String original = doc.getId().getOriginal(); String modified =."
type: docs
weight: 2220
url: /sv/java/com.aspose.pdf/id/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Id

```
public class Id extends Object
```

<p> Representerar filidentifieringsstruktur. </p> <hr> <pre> Document doc = new Document(\"example.pdf\"); String original = doc.getId().getOriginal(); String modified = doc.getId().getModified(); </pre>

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getModified](#getModified--) | Ändrar identifieraren baserat på dokumentets innehåll vid den tidpunkt det senast uppdaterades. |
| [getOriginal](#getOriginal--) | Permanent identifierare baserat på dokumentets innehåll vid den tidpunkt det ursprungligen skapades. |

### getModified {#getModified--}
```
public String getModified()
```

Ändrar identifieraren baserat på dokumentets innehåll vid den tidpunkt det senast uppdaterades.

**Returns:**
String värde

### getOriginal {#getOriginal--}
```
public String getOriginal()
```

Permanent identifierare baserat på dokumentets innehåll vid den tidpunkt det ursprungligen skapades.

**Returns:**
String värde
