---
title: Enum PdfFileEditor.ConcatenateCorruptedFileAction
second_title: Aspose.PDF for .NET API Reference
description: Enum Aspose.Pdf.Facades.PdfFileEditorConcatenateCorruptedFileAction. Ação realizada quando um arquivo corrompido é encontrado no processo de concatenação
type: docs
weight: 4470
url: /pt/net/aspose.pdf.facades/pdffileeditor.concatenatecorruptedfileaction/
---
## Enumeração PdfFileEditor.ConcatenateCorruptedFileAction

Ação realizada quando um arquivo corrompido é encontrado no processo de concatenação.

```csharp
public enum ConcatenateCorruptedFileAction
```

### Valores

| Nome | Valor | Descrição |
| --- | --- | --- |
| StopWithError | `0` | Se um arquivo corrompido for encontrado, então pare o processo de concatenação e retorne um erro. |
| ConcatenateIgnoringCorrupted | `1` | Se um arquivo corrompido for encontrado, então não pare a concatenação e não processe o arquivo corrompido. A lista de arquivos corrompidos está acessível na propriedade Failures. |
| ConcatenateIgnoringCorruptedObjects | `2` | Quando um objeto corrompido é encontrado no documento de origem, o processo não será interrompido e apenas o objeto corrompido será ignorado. |

### Veja Também

* classe [PdfFileEditor](../pdffileeditor/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)