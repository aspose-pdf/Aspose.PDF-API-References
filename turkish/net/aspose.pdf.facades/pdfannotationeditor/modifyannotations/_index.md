---
title: PdfAnnotationEditor.ModifyAnnotations
second_title: Aspose.PDF for .NET API Reference
description: PdfAnnotationEditor metodu. Belirtilen sayfa aralığında belirtilen türdeki notları değiştirir. Değiştirilen, Başlık, İçerik, Renk, Konu ve Açık gibi not özelliklerini değiştirmeyi destekler.
type: docs
weight: 120
url: /tr/net/aspose.pdf.facades/pdfannotationeditor/modifyannotations/
---
## PdfAnnotationEditor.ModifyAnnotations metodu

Belirtilen sayfa aralığında belirtilen türdeki notları değiştirir. Değiştirilen, Başlık, İçerik, Renk, Konu ve Açık gibi not özelliklerini değiştirmeyi destekler.

```csharp
public void ModifyAnnotations(int start, int end, Annotation annotation)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| start | Int32 | Başlangıç sayfa numarası. |
| end | Int32 | Bitiş sayfa numarası. |
| annotation | Annotation | Yeni özellikleri içeren not nesnesi. |

## Örnekler

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

### Ayrıca Bakınız

* sınıf [Annotation](../../../aspose.pdf.annotations/annotation/)
* sınıf [PdfAnnotationEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)