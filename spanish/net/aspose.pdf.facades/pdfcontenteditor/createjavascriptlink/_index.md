---
title: PdfContentEditor.CreateJavaScriptLink
second_title: Aspose.PDF for .NET API Reference
description: Método PdfContentEditor. Crea un enlace a JavaScript en el documento PDF
type: docs
weight: 170
url: /es/net/aspose.pdf.facades/pdfcontenteditor/createjavascriptlink/
---
## Método PdfContentEditor.CreateJavaScriptLink

Crea un enlace a JavaScript en el documento PDF.

```csharp
public void CreateJavaScriptLink(string code, Rectangle rect, int originalPage, Color color)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| code | String | El código JavaScript. |
| rect | Rectangle | El rectángulo para el clic activo. |
| originalPage | Int32 | El número de la página original donde se creará el rectángulo vinculado con el enlace. |
| color | Color | El color del rectángulo para el clic activo. |

## Ejemplos

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateJavaScriptLink("app.alert('welcome to aspose!');",
    new System.Drawing.Rectangle(0, 0, 100, 100), 1, System.Drawing.Color.Red });
editor.Save("example_out.pdf");
```

### Véase también

* clase [PdfContentEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)