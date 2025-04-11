---
title: PdfContentEditor.CreateCustomActionLink
second_title: Aspose.PDF for .NET API Reference
description: Método PdfContentEditor. Crea un enlace a acciones personalizadas en el documento PDF
type: docs
weight: 140
url: /es/net/aspose.pdf.facades/pdfcontenteditor/createcustomactionlink/
---
## Método PdfContentEditor.CreateCustomActionLink

Crea un enlace a acciones personalizadas en el documento PDF.

```csharp
public void CreateCustomActionLink(Rectangle rect, int originalPage, Color color, Enum[] actionName)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | Rectangle | El rectángulo para clic activo. |
| originalPage | Int32 | El número de la página original donde se creará el rectángulo vinculado con el enlace. |
| color | Color | El color del rectángulo para clic activo. |
| actionName | Enum[] | El arreglo de acciones (miembros del enum PredefinedAction) correspondientes a los elementos de menú que se ejecutan en el visor de Acrobat. |

## Ejemplos

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateCustomActionLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    1, System.Drawing.Color.Red,
    new Enum[] { PredefinedAction.FirstPage, PredefinedAction.PrintDialog });
editor.Save("example_out.pdf");
```

### Ver También

* clase [PdfContentEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)