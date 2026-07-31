---
title: "Enum PdfFileEditor.ConcatenateCorruptedFileAction"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Aspose.Pdf.Facades.PdfFileEditorConcatenateCorruptedFileAction enum. Azione eseguita quando si incontra un file corrotto nel processo di concatenazione"
type: docs
weight: 4590
url: /it/net/aspose.pdf.facades/pdffileeditor.concatenatecorruptedfileaction/
---
## PdfFileEditor.ConcatenateCorruptedFileAction enumeration

Azione eseguita quando si incontra un file corrotto nel processo di concatenazione.

```csharp
public enum ConcatenateCorruptedFileAction
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| StopWithError | `0` | Se si incontra un file corrotto, allora interrompere il processo di concatenazione e restituire un errore. |
| ConcatenateIgnoringCorrupted | `1` | Se si incontra un file corrotto, allora non interrompere la concatenazione e non elaborare il file corrotto. L'elenco dei file corrotti è accessibile nella proprietà Failures. |
| ConcatenateIgnoringCorruptedObjects | `2` | Quando si incontra un oggetto corrotto nel documento di origine, il processo non verrà interrotto e solo l'oggetto corrotto verrà ignorato. |

### Vedi anche

* class [PdfFileEditor](../pdffileeditor/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


