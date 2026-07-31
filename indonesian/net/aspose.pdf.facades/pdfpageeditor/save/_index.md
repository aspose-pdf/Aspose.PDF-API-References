---
title: "PdfPageEditor.Save"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "PdfPageEditor method. Menyimpan dokumen yang diubah ke dalam file"
type: docs
weight: 180
url: /id/net/aspose.pdf.facades/pdfpageeditor/save/
---
## Save(string) {#save_1}

Menyimpan document yang diubah ke dalam file.

```csharp
public override void Save(string outputFile)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputFile | String | Jalur ke file tempat dokumen akan disimpan. |

## Contoh

Contoh berikut menunjukkan cara menyimpan dokumen PDF yang diubah

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
editor.Zoom = 0.5f;
editor.Save("newdocument.pdf");
```

### Lihat Juga

* class [PdfPageEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Save(Stream) {#save}

Menyimpan document yang diubah ke dalam stream.

```csharp
public override void Save(Stream outputStream)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| outputStream | Stream | Stream tempat dokumen PDF yang diubah akan disimpan. |

## Contoh

Contoh berikut menunjukkan cara menyimpan dokumen PDF yang diubah ke dalam stream.

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
editor.Zoom = 0.5f;
editor.Save("newdocument.pdf");
```

### Lihat Juga

* class [PdfPageEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


