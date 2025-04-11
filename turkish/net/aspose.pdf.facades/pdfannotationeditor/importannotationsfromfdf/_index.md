---
title: PdfAnnotationEditor.ImportAnnotationsFromFdf
second_title: Aspose.PDF for .NET API Reference
description: PdfAnnotationEditor metodu. FDF dosyasından tüm notları içe aktarır
type: docs
weight: 100
url: /tr/net/aspose.pdf.facades/pdfannotationeditor/importannotationsfromfdf/
---
## PdfAnnotationEditor.ImportAnnotationsFromFdf metodu

FDF dosyasından tüm notları içe aktarır.

```csharp
public void ImportAnnotationsFromFdf(string fdfFile)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fdfFile | String | Girdi FDF dosyası. |

## Örnekler

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.ImportAnnotationsFromFdf("annots.fdf");
editor.Save("example_out.pdf");
```

### Ayrıca Bakınız

* sınıf [PdfAnnotationEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)