---
title: DeleteAnnotations
second_title: Aspose.PDF for .NET API Referansı
description: Belgedeki tüm açıklamaları siler.
type: docs
weight: 30
url: /tr/net/aspose.pdf.facades/pdfannotationeditor/deleteannotations/
---
## DeleteAnnotations() {#deleteannotations}

Belgedeki tüm açıklamaları siler.

```csharp
public void DeleteAnnotations()
```

### Örnekler

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.DeleteAnnotations();
editor.Save("example_out.pdf");
```

### Ayrıca bakınız

* class [PdfAnnotationEditor](../../pdfannotationeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdfannotationeditor)
* toplantı [Aspose.PDF](../../../)

---

## DeleteAnnotations(string) {#deleteannotations_1}

Belgede belirtilen türdeki tüm açıklamaları siler.

```csharp
public void DeleteAnnotations(string annotType)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| annotType | String | Ek açıklama türü silinecek. |

### Örnekler

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.DeleteAnnotations("Text");
editor.Save("example_out.pdf");
```

### Ayrıca bakınız

* class [PdfAnnotationEditor](../../pdfannotationeditor)
* ad alanı [Aspose.Pdf.Facades](../../pdfannotationeditor)
* toplantı [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->