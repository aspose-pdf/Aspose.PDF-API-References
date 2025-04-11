---
title: Enum PdfFileEditor.ConcatenateCorruptedFileAction
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfFileEditorConcatenateCorruptedFileAction enum. Tindakan yang dilakukan ketika file yang rusak ditemukan dalam proses penggabungan
type: docs
weight: 4470
url: /id/net/aspose.pdf.facades/pdffileeditor.concatenatecorruptedfileaction/
---
## PdfFileEditor.ConcatenateCorruptedFileAction enumeration

Tindakan yang dilakukan ketika file yang rusak ditemukan dalam proses penggabungan.

```csharp
public enum ConcatenateCorruptedFileAction
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| StopWithError | `0` | Jika file yang rusak ditemukan, maka hentikan proses penggabungan dan kembalikan kesalahan. |
| ConcatenateIgnoringCorrupted | `1` | Jika file yang rusak ditemukan, maka jangan hentikan penggabungan dan jangan proses file yang rusak. Daftar file yang rusak dapat diakses di properti Failures. |
| ConcatenateIgnoringCorruptedObjects | `2` | Ketika objek yang rusak ditemukan dalam dokumen sumber, proses tidak akan dihentikan dan objek yang rusak hanya diabaikan. |

### See Also

* class [PdfFileEditor](../pdffileeditor/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)