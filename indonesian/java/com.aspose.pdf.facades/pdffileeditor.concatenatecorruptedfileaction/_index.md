---
title: "PdfFileEditor.ConcatenateCorruptedFileAction"
linktitle: "PdfFileEditor.ConcatenateCorruptedFileAction"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Aksi yang dilakukan ketika file rusak ditemui dalam proses penggabungan."
type: docs
weight: 420
url: /id/java/com.aspose.pdf.facades/pdffileeditor.concatenatecorruptedfileaction/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.facades.PdfFileEditor.ConcatenateCorruptedFileAction, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.facades.PdfFileEditor.ConcatenateCorruptedFileAction, com.aspose.ms.System.Enum, com.aspose.pdf.facades.PdfFileEditor.ConcatenateCorruptedFileAction

```
public static final class PdfFileEditor.ConcatenateCorruptedFileAction extends com.aspose.ms.System.Enum
```

Aksi yang dilakukan ketika file rusak ditemui dalam proses penggabungan.

## Fields

| Field | Deskripsi |
| --- | --- |
| [ConcatenateIgnoringCorrupted](#ConcatenateIgnoringCorrupted) | Jika file yang rusak ditemukan, maka jangan hentikan penggabungan dan jangan proses file yang rusak. Daftar file yang rusak dapat diakses melalui properti Failures. |
| [ConcatenateIgnoringCorruptedObjects](#ConcatenateIgnoringCorruptedObjects) | Ketika objek yang rusak ditemukan dalam dokumen sumber, proses tidak akan dihentikan dan hanya objek yang rusak yang diabaikan. |
| [StopWithError](#StopWithError) | Jika file yang rusak ditemukan, maka hentikan proses penggabungan dan kembalikan kesalahan. |

### ConcatenateIgnoringCorrupted {#ConcatenateIgnoringCorrupted}
```
public static final int ConcatenateIgnoringCorrupted
```

Jika file yang rusak ditemukan, maka jangan hentikan penggabungan dan jangan proses file yang rusak. Daftar file yang rusak dapat diakses melalui properti Failures.

### ConcatenateIgnoringCorruptedObjects {#ConcatenateIgnoringCorruptedObjects}
```
public static final int ConcatenateIgnoringCorruptedObjects
```

Ketika objek yang rusak ditemukan dalam dokumen sumber, proses tidak akan dihentikan dan hanya objek yang rusak yang diabaikan.

### StopWithError {#StopWithError}
```
public static final int StopWithError
```

Jika file yang rusak ditemukan, maka hentikan proses penggabungan dan kembalikan kesalahan.
