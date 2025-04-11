---
title: PdfContentEditor.GetViewerPreference
second_title: Aspose.PDF for .NET API Reference
description: Método PdfContentEditor. Devuelve la preferencia de vista
type: docs
weight: 390
url: /es/net/aspose.pdf.facades/pdfcontenteditor/getviewerpreference/
---
## Método PdfContentEditor.GetViewerPreference

Devuelve la preferencia de vista.

```csharp
public int GetViewerPreference()
```

### Valor de Retorno

Devuelve un conjunto de banderas de ViewerPreference

## Ejemplos

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
int prefValue = editor.GetViewerPreference();
if ((prefValue & ViewerPreference.PageModeUseOutline) != 0)
{ // ... }
```

### Ver También

* clase [PdfContentEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)