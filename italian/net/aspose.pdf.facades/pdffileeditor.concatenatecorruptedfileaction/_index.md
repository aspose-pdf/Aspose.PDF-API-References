---
title: Enum PdfFileEditor.ConcatenateCorruptedFileAction
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facce Editor del File PDF - Azione su un File Corrotto. Azione eseguita allorché un file corrotto è stato incontrato nel processo di concatenazione.
type: docs
weight: 4470
url: /it/net/aspose.pdf.facades/pdffileeditor.concatenatecorruptedfileaction/
---
## Enumerazione PdfFileEditor.ConcatenateCorruptedFileAction

Azione eseguita quando si incontra un file corrotto nel processo di concatenazione.

```csharp
public enum ConcatenateCorruptedFileAction
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| StopWithError | `0` | Se si incontra un file corrotto, interrompere il processo di concatenazione e restituire un errore. |
| ConcatenateIgnoringCorrupted | `1` | Se si incontra un file corrotto, non interrompere la concatenazione e non elaborare il file corrotto. L'elenco dei file corrotti è accessibile nella proprietà Failures. |
| ConcatenateIgnoringCorruptedObjects | `2` | Quando si incontra un oggetto corrotto nel documento sorgente, il processo non si interrompe e solo l'oggetto corrotto viene ignorato. |

### Vedi Anche

* classe [PdfFileEditor](../pdffileeditor/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)