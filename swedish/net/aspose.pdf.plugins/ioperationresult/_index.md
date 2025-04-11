---
title: Interface IOperationResult
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.IOperationResult-gränssnitt. Allmänt gränssnitt för operationens resultat som definierar gemensamma metoder som konkreta plugin-operationers resultat bör implementera
type: docs
weight: 8850
url: /sv/net/aspose.pdf.plugins/ioperationresult/
---
## IOperationResult-gränssnitt

Allmänt gränssnitt för operationens resultat som definierar gemensamma metoder som konkreta plugin-operationers resultat bör implementera.

```csharp
public interface IOperationResult
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Data](../../aspose.pdf.plugins/ioperationresult/data/) { get; } | Hämtar rådata. |
| [IsFile](../../aspose.pdf.plugins/ioperationresult/isfile/) { get; } | Indikerar om resultatet är en sökväg till en utdatafil. |
| [IsStream](../../aspose.pdf.plugins/ioperationresult/isstream/) { get; } | Indikerar om resultatet är en utdataström. |
| [IsString](../../aspose.pdf.plugins/ioperationresult/isstring/) { get; } | Indikerar om resultatet är en textsträng. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [ToFile](../../aspose.pdf.plugins/ioperationresult/tofile/)() | Försöker konvertera resultatet till filen. |
| [ToStream](../../aspose.pdf.plugins/ioperationresult/tostream/)() | Försöker konvertera resultatet till strömobjektet. |

### Se Även

* namnrymd [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* samling [Aspose.PDF](../../)