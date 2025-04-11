---
title: Class Id
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Id. Rappresenta la struttura dell'identificatore del file
type: docs
weight: 5850
url: /it/net/aspose.pdf/id/
---
## Id class

Rappresenta la struttura dell'identificatore del file.

```csharp
public class Id
```

## Properties

| Name | Description |
| --- | --- |
| [Modified](../../aspose.pdf/id/modified/) { get; } | Identificatore che cambia in base ai contenuti del documento al momento dell'ultimo aggiornamento. |
| [Original](../../aspose.pdf/id/original/) { get; } | Identificatore permanente basato sui contenuti del documento al momento della sua creazione originale. |

## Examples

```csharp
Document doc = new Document("example.pdf");
string original = doc.Id.Original;
string modified = doc.Id.Modified;
```

### See Also

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)