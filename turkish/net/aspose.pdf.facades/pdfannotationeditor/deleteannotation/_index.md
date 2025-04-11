---
title: PdfAnnotationEditor.DeleteAnnotation
second_title: Aspose.PDF for .NET API Reference
description: PdfAnnotationEditor metodu. Belirtilen not adıyla notu siler
type: docs
weight: 20
url: /tr/net/aspose.pdf.facades/pdfannotationeditor/deleteannotation/
---
## PdfAnnotationEditor.DeleteAnnotation metodu

Belirtilen not adıyla notu siler.

```csharp
public void DeleteAnnotation(string annotName)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| annotName | String | Not adı |

## Örnekler

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.DeleteAnnotation("4cfa69cd-9bff-49e0-9005-e22a77cebf38");
editor.Save("example_out.pdf");
```

### Ayrıca Bakınız

* sınıf [PdfAnnotationEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)