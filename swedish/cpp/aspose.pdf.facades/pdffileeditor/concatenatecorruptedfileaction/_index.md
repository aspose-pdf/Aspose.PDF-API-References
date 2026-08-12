---
title: "Aspose::Pdf::Facades::PdfFileEditor::ConcatenateCorruptedFileAction-enum"
linktitle: "ConcatenateCorruptedFileAction"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Facades::PdfFileEditor::ConcatenateCorruptedFileAction-enum. Åtgärd som utförs när en korrupt fil påträffas i sammanslagningsprocessen i C++."
type: docs
weight: 7200
url: /sv/cpp/aspose.pdf.facades/pdffileeditor/concatenatecorruptedfileaction/
---
## ConcatenateCorruptedFileAction enum


Åtgärd som utförs när en korrupt fil påträffas i sammanslagningsprocessen.

```cpp
enum class ConcatenateCorruptedFileAction
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| StopWithError | 0 | Om en korrupt fil påträffas, stoppa sammanslagningsprocessen och returnera ett fel. |
| ConcatenateIgnoringCorrupted | 1 | Om en korrupt fil påträffas, stoppa inte sammanslagningen och bearbeta inte den korrupta filen. Lista över korrupta filer är tillgänglig i egenskapen Failures. |
| ConcatenateIgnoringCorruptedObjects | 2 | När ett korrupt objekt påträffas i källdokumentet stoppas processen inte och endast det korrupta objektet ignoreras. |

## Se även

* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
