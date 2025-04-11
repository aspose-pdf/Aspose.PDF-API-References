---
title: PdfPageEditor.Zoom
second_title: Aspose.PDF for .NET API Reference
description: Propriété PdfPageEditor. Obtient ou définit le coefficient de zoom. La valeur 1.0 correspond à 100. La valeur par défaut est 1.0. L'exemple suivant montre comment changer le zoom des pages du document.
type: docs
weight: 110
url: /fr/net/aspose.pdf.facades/pdfpageeditor/zoom/
---
## Propriété PdfPageEditor.Zoom

Obtient ou définit le coefficient de zoom. La valeur 1.0 correspond à 100 %. La valeur par défaut est 1.0. L'exemple suivant montre comment changer le zoom des pages du document.

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
editor.Zoom = 0.5f;
```

```csharp
public float Zoom { get; set; }
```

### Voir aussi

* classe [PdfPageEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)