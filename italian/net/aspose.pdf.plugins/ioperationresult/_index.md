---
title: "Interfaccia IOperationResult"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Interfaccia Aspose.Pdf.Plugins.IOperationResult. Interfaccia di risultato di operazione generale che definisce i metodi comuni che il risultato dell'operazione del plugin concreto deve implementare"
type: docs
weight: 8980
url: /it/net/aspose.pdf.plugins/ioperationresult/
---
## IOperationResult interface

Interfaccia generale del risultato dell'operazione che definisce i metodi comuni che il risultato dell'operazione del plugin concreto deve implementare.

```csharp
public interface IOperationResult
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Data](../../aspose.pdf.plugins/ioperationresult/data/) { get; } | Ottiene i dati grezzi. |
| [IsFile](../../aspose.pdf.plugins/ioperationresult/isfile/) { get; } | Indica se il risultato è un percorso a un file di output. |
| [IsStream](../../aspose.pdf.plugins/ioperationresult/isstream/) { get; } | Indica se il risultato è un flusso di output. |
| [IsString](../../aspose.pdf.plugins/ioperationresult/isstring/) { get; } | Indica se il risultato è una stringa di testo. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [ToFile](../../aspose.pdf.plugins/ioperationresult/tofile/)() | Cerca di convertire il risultato nel file. |
| [ToStream](../../aspose.pdf.plugins/ioperationresult/tostream/)() | Cerca di convertire il risultato nell'oggetto stream. |

### Vedi anche

* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


