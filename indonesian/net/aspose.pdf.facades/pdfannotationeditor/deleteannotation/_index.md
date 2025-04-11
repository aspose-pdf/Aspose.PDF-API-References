---
title: PdfAnnotationEditor.DeleteAnnotation
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfAnnotationEditor. Menghapus anotasi dengan nama anotasi yang ditentukan
type: docs
weight: 20
url: /id/net/aspose.pdf.facades/pdfannotationeditor/deleteannotation/
---
## Metode PdfAnnotationEditor.DeleteAnnotation

Menghapus anotasi dengan nama anotasi yang ditentukan.

```csharp
public void DeleteAnnotation(string annotName)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| annotName | String | Nama anotasi |

## Contoh

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.DeleteAnnotation("4cfa69cd-9bff-49e0-9005-e22a77cebf38");
editor.Save("example_out.pdf");
```

### Lihat Juga

* kelas [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)