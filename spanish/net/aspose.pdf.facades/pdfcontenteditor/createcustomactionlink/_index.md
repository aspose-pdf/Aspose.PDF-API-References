---
title: CreateCustomActionLink
second_title: Referencia de API de Aspose.PDF para .NET
description: Crea un enlace a acciones personalizadas en el documento PDF.
type: docs
weight: 140
url: /es/net/aspose.pdf.facades/pdfcontenteditor/createcustomactionlink/
---
## PdfContentEditor.CreateCustomActionLink method

Crea un enlace a acciones personalizadas en el documento PDF.

```csharp
public void CreateCustomActionLink(Rectangle rect, int originalPage, Color color, Enum[] actionName)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| rect | Rectangle | El rectángulo para el clic activo. |
| originalPage | Int32 | El número de la página original donde se creará el rectángulo enlazado con el enlace. |
| color | Color | El color del rectángulo para el clic activo. |
| actionName | Enum[] | La matriz de acciones (miembros de la enumeración PredefinedAction) correspondiente a la ejecución de elementos de menú en el visor de Acrobat. |

### Ejemplos

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateCustomActionLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    1, System.Drawing.Color.Red,
    new Enum[] { PredefinedAction.FirstPage, PredefinedAction.PrintDialog });
editor.Save("example_out.pdf");
```

### Ver también

* class [PdfContentEditor](../../pdfcontenteditor)
* espacio de nombres [Aspose.Pdf.Facades](../../pdfcontenteditor)
* asamblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->