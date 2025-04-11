---
title: PdfContentEditor.CreateCaret
second_title: Aspose.PDF for .NET API Reference
description: Método PdfContentEditor. Crea anotación de caret
type: docs
weight: 130
url: /es/net/aspose.pdf.facades/pdfcontenteditor/createcaret/
---
## Método PdfContentEditor.CreateCaret

Crea anotación de caret.

```csharp
public void CreateCaret(int page, Rectangle annotRect, Rectangle caretRect, string symbol, 
    string annotContents, Color color)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| page | Int32 | El número de la página original donde se creará la anotación. |
| annotRect | Rectangle | El rectángulo de anotación que define la ubicación de la anotación en la página. |
| caretRect | Rectangle | Los límites reales del caret subyacente. |
| symbol | String | Un símbolo se asociará con el caret. El valor puede ser: "P" (Párrafo), "Ninguno". |
| annotContents | String | El contenido de la anotación. |
| color | Color | El color de la anotación. |

## Ejemplos

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateCaret(1,
    new System.Drawing.Rectangle(50, 50, 100, 100),
    new System.Drawing.Rectangle(60, 60, 70, 70),
    "None", "Welcome to Aspose", System.Drawing.Color.Red);
editor.Save("example_out.pdf");
```

### Ver También

* clase [PdfContentEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)