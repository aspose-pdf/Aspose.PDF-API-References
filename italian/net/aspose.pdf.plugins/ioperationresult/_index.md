---
title: Interface IOperationResult
second_title: Aspose.PDF for .NET API Reference
description: Interfaccia Aspose.Pdf.Plugins.IOperationResult. Interfaccia generale per il risultato delle operazioni che definisce i metodi comuni che il risultato dell'operazione del plugin concreto dovrebbe implementare
type: docs
weight: 8850
url: /it/net/aspose.pdf.plugins/ioperationresult/
---
## Interfaccia IOperationResult

Interfaccia generale per il risultato delle operazioni che definisce i metodi comuni che il risultato dell'operazione del plugin concreto dovrebbe implementare.

```csharp
public interface IOperationResult
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Data](../../aspose.pdf.plugins/ioperationresult/data/) { get; } | Ottiene i dati grezzi. |
| [IsFile](../../aspose.pdf.plugins/ioperationresult/isfile/) { get; } | Indica se il risultato è un percorso a un file di output. |
| [IsStream](../../aspose.pdf.plugins/ioperationresult/isstream/) { get; } | Indica se il risultato è uno stream di output. |
| [IsString](../../aspose.pdf.plugins/ioperationresult/isstring/) { get; } | Indica se il risultato è una stringa di testo. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [ToFile](../../aspose.pdf.plugins/ioperationresult/tofile/)() | Tenta di convertire il risultato in un file. |
| [ToStream](../../aspose.pdf.plugins/ioperationresult/tostream/)() | Tenta di convertire il risultato in un oggetto stream. |

### Vedi Anche

* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)