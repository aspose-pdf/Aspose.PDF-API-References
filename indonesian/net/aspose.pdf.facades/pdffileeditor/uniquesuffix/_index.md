---
title: PdfFileEditor.UniqueSuffix
second_title: Aspose.PDF for .NET API Reference
description: Properti PdfFileEditor. Format dari sufiks yang ditambahkan ke nama field untuk membuatnya unik saat formulir digabungkan. String ini harus mengandung substring NUM yang akan diganti dengan angka. Misalnya jika UniqueSuffix = ABCNUM maka untuk nama field fieldName akan menjadi fieldNameABC1 fieldNameABC2 fieldNameABC3 dll
type: docs
weight: 200
url: /id/net/aspose.pdf.facades/pdffileeditor/uniquesuffix/
---
## Properti PdfFileEditor.UniqueSuffix

Format dari sufiks yang ditambahkan ke nama field untuk membuatnya unik saat formulir digabungkan. String ini harus mengandung substring %NUM% yang akan diganti dengan angka. Misalnya jika UniqueSuffix = "ABC%NUM%" maka untuk field "fieldName" nama-nama akan menjadi: fieldNameABC1, fieldNameABC2, fieldNameABC3 dll.

```csharp
public string UniqueSuffix { get; set; }
```

## Contoh

```csharp
PdfFileEditor ed = new PdfFileEditor();
ed.UniqueSuffix = "_%NUM%";
```

### Lihat Juga

* kelas [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)