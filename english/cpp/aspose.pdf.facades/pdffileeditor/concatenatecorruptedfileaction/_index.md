---
title: Aspose::Pdf::Facades::PdfFileEditor::ConcatenateCorruptedFileAction enum
linktitle: ConcatenateCorruptedFileAction
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::PdfFileEditor::ConcatenateCorruptedFileAction enum. Action performed when corrupted file was met in concatenation process in C++.'
type: docs
weight: 7200
url: /cpp/aspose.pdf.facades/pdffileeditor/concatenatecorruptedfileaction/
---
## ConcatenateCorruptedFileAction enum


Action performed when corrupted file was met in concatenation process.

```cpp
enum class ConcatenateCorruptedFileAction
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| StopWithError | 0 | If corrupted file was met, then stop concatentation process and return error. |
| ConcatenateIgnoringCorrupted | 1 | If corrupted file was met, then don't stop concatenation and don't process corrupted file. List of corrupted files is accessible in Failures property. |
| ConcatenateIgnoringCorruptedObjects | 2 | When corrupted object is met in source document, process will not stopped and corrupted object only is ignored. |

## See Also

* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
