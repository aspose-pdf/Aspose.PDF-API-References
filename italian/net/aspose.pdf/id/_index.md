---
title: "Classe Id"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.Id. Rappresenta la struttura dell'identificatore del file"
type: docs
weight: 5980
url: /it/net/aspose.pdf/id/
---
## Id class

Rappresenta la struttura dell'identificatore del file.

```csharp
public class Id
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Modified](../../aspose.pdf/id/modified/) { get; } | Modifica dell'identificatore in base al contenuto del documento al momento dell'ultimo aggiornamento. |
| [Original](../../aspose.pdf/id/original/) { get; } | Identificatore permanente basato sul contenuto del documento al momento della sua creazione originale. |

## Esempi

```csharp
Document doc = new Document("example.pdf");
string original = doc.Id.Original;
string modified = doc.Id.Modified;
```

### Vedi anche

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


