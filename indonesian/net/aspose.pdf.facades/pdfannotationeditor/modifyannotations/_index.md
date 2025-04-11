---
title: PdfAnnotationEditor.ModifyAnnotations
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfAnnotationEditor. Memodifikasi anotasi dari tipe yang ditentukan pada rentang halaman yang ditentukan. Ini mendukung untuk memodifikasi properti anotasi berikut: Modified, Title, Contents, Color, Subject dan Open
type: docs
weight: 120
url: /id/net/aspose.pdf.facades/pdfannotationeditor/modifyannotations/
---
## Metode PdfAnnotationEditor.ModifyAnnotations

Memodifikasi anotasi dari tipe yang ditentukan pada rentang halaman yang ditentukan. Ini mendukung untuk memodifikasi properti anotasi berikut: Modified, Title, Contents, Color, Subject dan Open.

```csharp
public void ModifyAnnotations(int start, int end, Annotation annotation)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| start | Int32 | Nomor halaman awal. |
| end | Int32 | Nomor halaman akhir. |
| annotation | Annotation | Objek anotasi yang berisi properti baru. |

## Contoh

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
TextAnnotation annot = new TextAnnotation();
annot.Modified = DateTime.Now;
annot.Title = "NEW AUTHOR";
annot.Contents = "NEW CONTENTS";
annot.Color = Color.Red;
annot.Subject = "NEW SUBJECT";
annot.Open = true;
editor.ModifyAnnotations(1, 2, annot);
editor.Save("example_out.pdf");
```

### Lihat Juga

* kelas [Annotation](../../../aspose.pdf.annotations/annotation/)
* kelas [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)