---
title: PdfContentEditor.ChangeViewerPreference
second_title: Aspose.PDF for .NET API Reference
description: Método PdfContentEditor. Cambia la preferencia de vista
type: docs
weight: 90
url: /es/net/aspose.pdf.facades/pdfcontenteditor/changeviewerpreference/
---
## Método PdfContentEditor.ChangeViewerPreference

Cambia la preferencia de vista.

```csharp
public void ChangeViewerPreference(int viewerAttribution)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| viewerAttribution | Int32 | La atribución de vista definida en la clase ViewerPreference. |

## Ejemplos

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.ChangeViewerPreference(ViewerPreference.HideMenubar);
editor.ChangeViewerPreference(ViewerPreference.PageModeUseNone);
editor.Save("example_out.pdf");
```

### Ver También

* clase [PdfContentEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)