---
title: Enum PdfFileEditor.ConcatenateCorruptedFileAction
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfFileEditorConcatenateCorruptedFileAction enum. Action performed when corrupted file was met in concatenation process
type: docs
weight: 2980
url: /net/aspose.pdf.facades/pdffileeditor.concatenatecorruptedfileaction/
---
## PdfFileEditor.ConcatenateCorruptedFileAction enumeration

Action performed when corrupted file was met in concatenation process.

```csharp
public enum ConcatenateCorruptedFileAction
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| StopWithError | `0` | If corrupted file was met, then stop concatentation process and return error. |
| ConcatenateIgnoringCorrupted | `1` | If corrupted file was met, then don't stop concatenation and don't process corrupted file. List of corrupted files is accessible in Failures property. |
| ConcatenateIgnoringCorruptedObjects | `2` | When corrupted object is met in source document, process will not stopped and corrupted object only is ignored. |

### See Also

* class [PdfFileEditor](../pdffileeditor/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


