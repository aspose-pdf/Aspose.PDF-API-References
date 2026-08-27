---
title: "Id"
linktitle: "Id"
second_title: "Riferimento API Aspose.PDF per Java"
description: "<p> Rappresenta la struttura dell'identificatore del file. </p> <hr> <pre> Document doc = new Document(\\\"example.pdf\\\"); String original = doc.getId().getOriginal(); String modified =."
type: docs
weight: 2220
url: /it/java/com.aspose.pdf/id/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Id

```
public class Id extends Object
```

<p> Rappresenta la struttura dell'identificatore del file. </p> <hr> <pre> Document doc = new Document("example.pdf"); String original = doc.getId().getOriginal(); String modified = doc.getId().getModified(); </pre>

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getModified](#getModified--) | Modifica dell'identificatore basata sul contenuto del documento al momento dell'ultimo aggiornamento. |
| [getOriginal](#getOriginal--) | Identificatore permanente basato sul contenuto del documento al momento della creazione originale. |

### getModified {#getModified--}
```
public String getModified()
```

Modifica dell'identificatore basata sul contenuto del documento al momento dell'ultimo aggiornamento.

**Returns:**
valore String

### getOriginal {#getOriginal--}
```
public String getOriginal()
```

Identificatore permanente basato sul contenuto del documento al momento della creazione originale.

**Returns:**
valore String
