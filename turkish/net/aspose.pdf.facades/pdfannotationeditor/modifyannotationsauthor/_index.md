---
title: ModifyAnnotationsAuthor
second_title: Aspose.PDF for .NET API Referansı
description: Belirtilen sayfa aralığındaki ek açıklamaların yazarını değiştirir.
type: docs
weight: 120
url: /tr/net/aspose.pdf.facades/pdfannotationeditor/modifyannotationsauthor/
---
## PdfAnnotationEditor.ModifyAnnotationsAuthor method

Belirtilen sayfa aralığındaki ek açıklamaların yazarını değiştirir.

```csharp
public void ModifyAnnotationsAuthor(int start, int end, string srcAuthor, string desAuthor)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| start | Int32 | Başlangıç sayfa numarası. |
| end | Int32 | Bitiş sayfa numarası. |
| srcAuthor | String | Değiştirilmesi gereken yazar. |
| desAuthor | String | Yeni yazar. |

### Örnekler

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.ModifyAnnotationsAuthor(1, 2, "PREV AUTHOR", "NEW AUTHOR");
editor.Save("example_out.pdf");
```

### Ayrıca bakınız

* class [PdfAnnotationEditor](../../pdfannotationeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdfannotationeditor)
* toplantı [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
