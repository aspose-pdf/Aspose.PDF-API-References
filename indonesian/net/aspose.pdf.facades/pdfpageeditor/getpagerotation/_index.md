---
title: "PdfPageEditor.GetPageRotation"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "PdfPageEditor method. Mengembalikan rotasi halaman yang ditentukan"
type: docs
weight: 140
url: /id/net/aspose.pdf.facades/pdfpageeditor/getpagerotation/
---
## PdfPageEditor.GetPageRotation method

Mengembalikan rotasi halaman yang ditentukan.

```csharp
public int GetPageRotation(int page)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| halaman | Int32 | Indeks halaman. Halaman dokumen diberi nomor mulai dari 1. |

### Nilai Kembalian

Rotasi halaman dalam derajat.

## Contoh

Contoh berikut menunjukkan cara mendapatkan rotasi halaman:

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
int rotation = editor.GetPageSize(1);
Console.WriteLine("Rotation of 1st page : " + rotation + " degrees");        
```

### Lihat Juga

* class [PdfPageEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


