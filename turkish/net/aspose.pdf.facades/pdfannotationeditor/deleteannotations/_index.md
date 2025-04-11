---
title: PdfAnnotationEditor.DeleteAnnotations
second_title: Aspose.PDF for .NET API Reference
description: PdfAnnotationEditor metodu. Belgedeki tüm notları siler
type: docs
weight: 30
url: /tr/net/aspose.pdf.facades/pdfannotationeditor/deleteannotations/
---
## DeleteAnnotations() {#deleteannotations}

Belgedeki tüm notları siler.

```csharp
public void DeleteAnnotations()
```

## Örnekler

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.DeleteAnnotations();
editor.Save("example_out.pdf");
```

### Ayrıca Bakınız

* sınıf [PdfAnnotationEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## DeleteAnnotations(string) {#deleteannotations_1}

Belgedeki belirtilen türdeki tüm notları siler.

```csharp
public void DeleteAnnotations(string annotType)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| annotType | String | Silinecek not türü. |

## Örnekler

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.DeleteAnnotations("Text");
editor.Save("example_out.pdf");
```

### Ayrıca Bakınız

* sınıf [PdfAnnotationEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)