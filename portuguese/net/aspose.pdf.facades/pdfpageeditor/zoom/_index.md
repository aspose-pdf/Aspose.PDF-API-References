---
title: PdfPageEditor.Zoom
second_title: Aspose.PDF for .NET API Reference
description: Propriedade PdfPageEditor. Obtém ou define o coeficiente de zoom. O valor 1.0 corresponde a 100%. O valor padrão é 1.0. O exemplo a seguir demonstra como alterar o zoom das páginas do documento.
type: docs
weight: 110
url: /pt/net/aspose.pdf.facades/pdfpageeditor/zoom/
---
## Propriedade PdfPageEditor.Zoom

Obtém ou define o coeficiente de zoom. O valor 1.0 corresponde a 100%. O valor padrão é 1.0. O exemplo a seguir demonstra como alterar o zoom das páginas do documento.

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
editor.Zoom = 0.5f;
```

```csharp
public float Zoom { get; set; }
```

### Veja Também

* classe [PdfPageEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)