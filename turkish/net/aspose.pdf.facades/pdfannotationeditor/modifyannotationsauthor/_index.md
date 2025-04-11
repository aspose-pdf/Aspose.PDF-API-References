---
title: PdfAnnotationEditor.ModifyAnnotationsAuthor
second_title: Aspose.PDF for .NET API Reference
description: PdfAnnotationEditor metodu. Belirtilen sayfa aralığındaki notların yazarını değiştirir
type: docs
weight: 130
url: /tr/net/aspose.pdf.facades/pdfannotationeditor/modifyannotationsauthor/
---
## PdfAnnotationEditor.ModifyAnnotationsAuthor metodu

Belirtilen sayfa aralığındaki notların yazarını değiştirir.

```csharp
public void ModifyAnnotationsAuthor(int start, int end, string srcAuthor, string desAuthor)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| start | Int32 | Başlangıç sayfa numarası. |
| end | Int32 | Bitiş sayfa numarası. |
| srcAuthor | String | Değiştirilmesi gereken yazar. |
| desAuthor | String | Yeni yazar. |

## Örnekler

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.ModifyAnnotationsAuthor(1, 2, "PREV AUTHOR", "NEW AUTHOR");
editor.Save("example_out.pdf");
```

### Ayrıca Bakınız

* sınıf [PdfAnnotationEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)