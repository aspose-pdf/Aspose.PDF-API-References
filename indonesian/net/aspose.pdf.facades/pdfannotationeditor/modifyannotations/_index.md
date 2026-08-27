---
title: "PdfAnnotationEditor.ModifyAnnotations"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "PdfAnnotationEditor method. Memodifikasi anotasi tipe yang ditentukan pada rentang halaman yang ditentukan. Mendukung modifikasi properti anotasi berikut: Modified, Title, Contents, Color, Subject, dan Open."
type: docs
weight: 120
url: /id/net/aspose.pdf.facades/pdfannotationeditor/modifyannotations/
---
## PdfAnnotationEditor.ModifyAnnotations method

Mengubah anotasi dari tipe yang ditentukan pada rentang halaman yang ditentukan. Mendukung pengubahan properti anotasi berikut: Modified, Title, Contents, Color, Subject, dan Open.

```csharp
public void ModifyAnnotations(int start, int end, Annotation annotation)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| start | Int32 | Nomor halaman awal. |
| end | Int32 | Nomor halaman akhir. |
| annotation | Annotation | Objek anotasi berisi properti baru. |

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

* class [Annotation](../../../aspose.pdf.annotations/annotation/)
* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


