---
title: "Enum PdfFileEditor.ConcatenateCorruptedFileAction"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Enum Aspose.Pdf.Facades.PdfFileEditorConcatenateCorruptedFileAction. Aksi yang dilakukan ketika file rusak ditemui dalam proses penggabungan"
type: docs
weight: 4590
url: /id/net/aspose.pdf.facades/pdffileeditor.concatenatecorruptedfileaction/
---
## PdfFileEditor.ConcatenateCorruptedFileAction enumeration

Aksi yang dilakukan ketika file rusak ditemui dalam proses penggabungan.

```csharp
public enum ConcatenateCorruptedFileAction
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| StopWithError | `0` | Jika file yang rusak ditemukan, maka hentikan proses penggabungan dan kembalikan kesalahan. |
| ConcatenateIgnoringCorrupted | `1` | Jika file yang rusak ditemukan, maka jangan hentikan penggabungan dan jangan proses file yang rusak. Daftar file yang rusak dapat diakses melalui properti Failures. |
| ConcatenateIgnoringCorruptedObjects | `2` | Ketika objek yang rusak ditemukan dalam dokumen sumber, proses tidak akan dihentikan dan hanya objek yang rusak yang diabaikan. |

### Lihat Juga

* class [PdfFileEditor](../pdffileeditor/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


